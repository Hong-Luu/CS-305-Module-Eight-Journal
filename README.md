# CS 305 Module Eight Journal

**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**

Artemis Financial is a consulting company specializing in personalized financial plans for their clients. They approached Global Rain, our software engineering company, to modernize their operations and enhance the security of their web-based software application. The main issue they wanted us to address was identifying and mitigating any security vulnerabilities in their system. Our task is to conduct a vulnerability assessment to identify potential threats and provide recommendations for strengthening the security of Artemis Financial’s software application.

**What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**

When identifying the client’s software security vulnerabilities, I conducted a comprehensive assessment of the application, analyzing different layers of the software, such as input validation, secure coding practices, authentication mechanisms, encryption, and secure data handling.
Coding securely is crucial because it helps protect sensitive data, prevent unauthorized access, and avoid potential breaches. Software security adds value to a company’s overall wellbeing by instilling customer trust, safeguarding the company’s reputation, mitigating financial losses from cyber attacks, and ensuring compliance with regulatory requirements.

**What part of the vulnerability assessment was challenging or helpful to you?**

The most challenging part of the vulnerability assessment was identifying and understanding the complex coding structures and system architecture of the software. It required deep analysis and technical expertise to uncover potential vulnerabilities and security weaknesses. However, this process was also helpful as it allowed us to gain a thorough understanding of the software’s security landscape and provided valuable insights for strengthening its defenses.

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

To increase layers of security, I implemented various measures such as input validation, secure coding practices, encryption of sensitive data, and secure API interactions. I also performed regular code reviews, architecture reviews, and utilized industry best practices for secure coding.

In the future, I would use a combination of automated tools and manual code reviews to assess vulnerabilities. Static code analysis tools like OWASP Dependency-Check Maven can help identify potential vulnerabilities in third-party dependencies. These assessments would help us prioritize and decide which mitigation techniques to use based on the severity and potential impact of the vulnerabilities discovered.

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

To ensure the code and software application were functional and secure, I went through thorough testing. I did functional testing to validate the desired functionality and security testing to identify vulnerabilities. After refactoring the code, I made a secondary review, using tools like OWASP Dependency-Check Maven, to check for newly introduced vulnerabilities and ensure the overall security of the application.

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

In this assignment, I utilized resources such as the OWASP Dependency-Check tool to perform static testing and ensure that the code complies with software security enhancements. I incorporated this tool by adding it as a plugin in the project's pom.xml file and running it to analyze the project's dependencies. By verifying the correct version and configuration of the dependency-check plugin in the pom.xml, I was able to effectively assess and address any potential security vulnerabilities in the project's dependencies. These practices and tools can be valuable resources in future assignments or tasks to enhance software security.

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

From this assignment, I can showcase the vulnerability assessment report that I prepared for Artemis Financial. This report demonstrates my ability to identify security vulnerabilities in a software application and provide mitigation strategies. Additionally, I can share the refactored code that incorporates secure coding practices and highlights my skills in implementing software security measures. These examples demonstrate my knowledge, experience, and ability to deliver secure software solutions.

