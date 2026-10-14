CS 305 Portfolio Reflection

Artemis Financial and Software Requirements

Artemis Financial is a financial consulting company that develops individualized financial plans for its customers. The company wanted to improve the security of its public web application and better protect sensitive client and financial information. The main objective was to identify vulnerabilities and implement secure communication mechanisms, including HTTPS, certificate management, checksum verification, and dependency analysis.

Security Vulnerabilities and Secure Coding

One thing I believe I did well was identifying software vulnerabilities through both manual code review and static testing. Using OWASP Dependency-Check helped identify vulnerable dependencies, while manual review helped identify hardcoded credentials, missing validation, and other security weaknesses. Secure coding is important because software vulnerabilities can expose sensitive information, damage customer trust, and create financial and legal risks for an organization. Software security helps protect company assets, customer data, and overall business operations.

Most Helpful or Challenging Part

The most challenging part of the vulnerability assessment process was determining the difference between legitimate vulnerabilities and false positives. Learning how to review dependency-check results and create suppression rules helped me better understand how security tools should be used in real-world environments. The most helpful part was seeing how automated security tools can identify risks that might otherwise be missed.

Increasing Layers of Security

I increased security by implementing HTTPS through a self-signed certificate, creating SHA-256 checksum verification, and using OWASP Dependency-Check to identify vulnerable dependencies. In the future, I would continue using static analysis tools, dependency checking, code reviews, vulnerability databases such as the National Vulnerability Database (NVD), and secure coding standards when deciding which mitigation techniques to use.

Ensuring the Application Was Functional and Secure

To make sure the software remained functional and secure, I tested the application after each modification. I verified that the HTTPS endpoint functioned correctly, confirmed the checksum generation worked as expected, reviewed dependency-check reports, and evaluated security findings before making configuration changes. Running security scans after refactoring helped verify that new vulnerabilities were not introduced.

Helpful Tools and Resources

Several tools and resources were valuable throughout this course, including Eclipse, Java Keytool, OWASP Dependency-Check, Maven, and Spring Boot. These tools helped me learn more about secure communications, certificate management, vulnerability assessment, and secure software development practices.

Work I Would Show Future Employers

The artifact I would most likely show future employers is my Artemis Financial secure software project. The project demonstrates my ability to implement HTTPS, generate and manage certificates, perform vulnerability assessments, configure dependency-check security testing, and implement cryptographic checksum verification using SHA-256. It demonstrates both secure coding practices and practical software security skills.
