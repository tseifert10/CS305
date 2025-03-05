# CS305
Artemis Financial Security Assessment - README
Client Summary and Software Requirements

Our client, Artemis Financial, is a financial services company that required a security assessment of its software. The company was concerned about potential security vulnerabilities in its existing system and wanted to ensure that its software adhered to best practices for secure coding. Specifically, they needed an assessment of their encryption and data integrity mechanisms to prevent unauthorized access and data tampering.

Identified Security Vulnerabilities and Importance of Secure Coding

During the assessment, I identified weaknesses in the system’s checksum verification process, potential risks associated with outdated dependencies, and missing security configurations. I improved these areas by implementing SHA-256 hashing for checksum verification, ensuring that sensitive data remains protected from unauthorized alterations.

Secure coding is critical because it protects sensitive financial data, prevents unauthorized access, and ensures regulatory compliance. A company’s reputation and financial stability depend on secure software, as vulnerabilities can lead to data breaches, financial loss, and legal consequences. By coding securely, businesses can safeguard client information, maintain trust, and reduce the risk of cyberattacks.

Challenges and Lessons Learned from the Vulnerability Assessment

One of the most challenging aspects was identifying and fixing hidden security vulnerabilities while ensuring that my changes did not disrupt application functionality. A helpful aspect was using Spring Boot’s built-in security features and dependency analysis tools like OWASP Dependency-Check, which flagged outdated libraries and suggested more secure versions.

Security Enhancements and Future Assessment Strategies
To increase security layers, I:

Implemented SHA-256 hashing for checksum validation.
Refactored the Spring Boot application to follow secure coding practices.
Ensured proper error handling to prevent exposure of sensitive system information.
Used Maven dependency management to eliminate outdated or vulnerable libraries.
In the future, I would use automated security testing tools like SonarQube, OWASP ZAP, and Snyk to identify vulnerabilities and select the best mitigation techniques. Regular security audits and penetration testing would further strengthen application security.

Ensuring Functionality and Security After Refactoring
After refactoring, I conducted thorough testing, including unit tests and integration tests, to verify that the application remained functional. I also re-ran security scans to check for new vulnerabilities introduced during the refactor. This ensured that the application maintained both performance and security integrity.

Useful Resources, Tools, and Best Practices
Spring Boot Security Best Practices (official Spring documentation)
OWASP Dependency-Check (for identifying outdated or vulnerable dependencies)
JUnit Testing (to validate functionality post-refactoring)
Maven and Dependency Management (to ensure libraries were up to date)
REST API Security Best Practices (to enforce authentication and data protection)
Showcasing This Work to Future Employers
This project demonstrates my ability to assess, identify, and mitigate security vulnerabilities in a real-world financial software system. Employers value secure coding expertise, and this project highlights my skills in:

Cryptographic security (SHA-256 hashing for checksum validation)
Spring Boot application development and security hardening
Vulnerability assessment using OWASP tools
Secure dependency management with Maven
I would present this project as an example of my secure coding knowledge, problem-solving skills, and ability to enhance application security while maintaining functionality.
