# CS305
SNHU's 2026 CS 305 Software Security course

## 1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

The client, Artemis Financial, is an online consulting company that develops individualized financial plans for its customers. Artemis Financial contacted Global Rain to assist in modernizing and securing their web-based software application. Specifically, Artemis Financial wanted Global Rain to implement measures to ensure that the company, client data, and archived financial information was protected from external threats. 

## 2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

One of my strengths was recognizing security weaknesses in how applications handled API requests and communicated with other systems. Identifying these issues allowed me to make targeted code improvements that reduced security risks and strengthened the application. Secure coding is essential for any business because it helps prevent data breaches, protect sensitive information, and avoid costly damage to a company's reputation. This is particularly important for a financial services company like Artemis Financial, where customers rely on the company to keep their financial information safe. By maintaining secure and reliable software, businesses can build customer trust, establish a positive reputation, and encourage long-term customer relationships.

## 3. Which part of the vulnerability assessment was challenging or helpful to you?

I found analyzing the vulnerabilities in the OWASP Dependency-Check report to be the most challenging part of the vulnerability assessment. Much of the difficulty came from the fact that the entire codebase was severely outdated. This meant that each dependency came with a laundry list of known vulnerabilities and identifying which critical issue genuinely impacted the current code was quite challenging.

## 4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

The security of Artemis Financial’s software was improved by refactoring the code to follow secure coding best practices, implementing exception handling, upgrading the application to Java 17, updating dependencies to address known vulnerabilities, and enabling HTTPS to protect client-server communication through TLS encryption. These improvements added multiple layers of security and helped reduce potential risks. 

In the future, I intend to use static code analysis, automated security testing, and dependency-checking tools to identify vulnerabilities and evaluate potential risks. These tools will help me determine which mitigation techniques are most appropriate based on the severity of each vulnerability and its potential impact on the application. By regularly testing the code and keeping dependencies up to date, I can address security issues early and maintain a more secure and reliable application.

## 5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I verified that the refactored code was functional and secure by running the application and manually testing to ensure that my changes did not change the functionality of the software. After updating the application and its dependencies, I ran another dependency check to identify any remaining known vulnerabilities. This reduced the number of reported vulnerabilities from 168 to just 2. Comparing the results before and after refactoring helped me evaluate the effectiveness of my changes and identify any remaining security concerns.

## 6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

This project introduced me to Java’s keytool system and the OWASP Dependency-Check tool. With all the challenges I encountered while working with legacy code, I intend to use the dependency check tool in the future to help me determine which updates were needed to improve the application’s security. Likewise, the experience I gained with using keytool to create certificates and enable HTTPS encryption will be used in future assignments to ensure those programs are also protecting communications with the TLS protocol. 

## 7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show future employers the Artemis Financial application and explain the security improvements I made during the refactoring process. In particular, I would highlight how I used OWASP Dependency-Check to reduce the number of reported vulnerabilities from 168 to 2 and configured HTTPS to secure communication between the client and server. I could also explain the challenges I encountered while working with legacy code and how I addressed them by updating the Java version and its dependencies. This project demonstrates my ability to identify security risks, apply appropriate solutions, and verify the results. It would be a valuable example of my problem-solving skills and my commitment to writing secure, reliable software.
