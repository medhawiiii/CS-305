# CS-305 Module 8-1 Journal: Portfolio

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

  Artemis Financial is a financial consulting company that handles sensitive client data The company wanted to enhance their web application
and improve its security to ensure theintegrity of uploaded files and the confidentiality of its users information

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

  I took a layered approach to dealing with the vulnerabilities as that is what seemed to make the most amount of sense, and would also allow
the security of the applicaiton to be more solid and through. I added multiple layers of security:
    - checksums for input validation,
    - SSL/HTTPS for secure client/server communication,
    - proper error handeling,
    - automated and manual code reviews,
    - utilzied OWASP Dependency-Check.

  Coding securely is important as it helps prevent malicious attackers, ensures that sensitive data and personal information remains safe,
and aids in making sure that an application functions reliably for a long time. It also makes it easier to read, maintain, and expand as needed.
Having a software with strong software security builds more trust with clients and reduces risks of regulartory violations. It also works in the 
company's best interest as having good, trustworhty software security reflects well on the company's reputation and on the overall well-being of 
comany opperations.

3. Which part of the vulnerability assessment was challenging or helpful to you?

  I struggled mainly with the manual code review because I was unfamilar with the IDE, as well as with the type of coding and material we were working with as Java is one of my weaker languges. 
I also had a bit of a diffuclt time figuring out how to place some of the vulnerabilities as it seemed like they fell under more than one. Learning to recognize the different types of 
vulnerabilties, what constitues as one, how overlaps between different vulnerabilites may come to be, and how to deal with that has been really beneficial. I know know more about the different
ways your code can be vulnerable, and your system/appliction be weak, beyond simply just shoddy coding.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

  As stated previously I increased the layers by implementing:
    - checksums,
    - secure error handling,
    - the OWASP Dependency-Check,
    - and manual code reviews as well.
      
  Before all that though, I first did the ODC and manual code reviews to find out what the vulnerabiltiies were, and then spent a good amount of time making sure
that I understood and knew what and how exactly they were vulnerabiltiies, and then how to mitigate them. 

  In the future I would first continue to implement 
the above as a starting point and then combine static and dynamic tools and vulnerability scanners alongside industry-standard frameworks like 
the OWASP Top 10 and the NIST guidelines to assess the risks and understand them so that I can select the appropriate mitigation techniques.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

  I checked each of the different features, like the checksums and client-server interactions, to ensure that they were working as intended. I checked the security as well by 
  utilzing ODC to perform a static analysis, running manual code reviews, and testing input validation and SSL/HTTPS connections.

6.What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

  There are quite a few that I am glad to have learned about/how to use:
    - ODC will definetly be very useful in the future,
    - Learning how to find false positives has been intersting,
    - How configure an application.properties file to ensure a connection is secure, the differences beteen HTTP and HTTPS,
    - The vulnerability assessment diagram which has helped me better understand vulnerabilities,
    - Java's MessageDigest class, as well as all the different types of ciphers for encrypting and hashes, and other algorithms,
    - And how to use Tomcat to change a hash into a hex.

7.Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would like to say my ability to assess vulnerabilities in an application, however, I think I still have a lot of room to improve, so I am not entirely show. 
