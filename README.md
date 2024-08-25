# CS-305 Software Security: Module Eight Journal Entry
  
  This repository contains the Artemis Financial Vulnerability Assessment Report, completed as part of Project One in the CS-305 Software Security course. The report presents a detailed analysis of security vulnerabilities identified within Artemis Financial's software systems, along with strategic recommendations for mitigating these risks. This entry reflects on the work completed, the challenges encountered, and the lessons learned, as well as the significance of secure coding practices in professional software development.

## Reflection Questions and Responses

### Q: Briefly summarize Artemis Financial and its software requirements. What issue did the company want you to address?

**A:** Artemis Financial is a financial services company that required a comprehensive security assessment of its software applications. The main objective was to identify and mitigate potential vulnerabilities that could compromise the confidentiality, integrity, and availability of sensitive financial data. The focus was on defending against evolving external threats, including phishing attacks, ransomware, and zero-day exploits.

### Q: What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

**A:** During the vulnerability assessment, I effectively identified critical security flaws, such as hardcoded database credentials, insufficient input validation, and the use of outdated cryptographic libraries. Secure coding is paramount in preventing vulnerabilities like SQL injection and cross-site scripting, which can lead to severe data breaches. By ensuring software security, a company not only protects its assets but also maintains customer trust and complies with industry regulations, which are essential for its long-term success.

### Q: Which part of the vulnerability assessment was challenging or helpful to you?

**A:** A significant challenge was managing false positives during static testing. Initially, the number of false positives was overwhelming, which could have led to unnecessary remediation efforts. However, by fine-tuning the OWASP Dependency-Check tool and carefully suppressing these false positives, I was able to focus on genuine vulnerabilities, enhancing the accuracy and efficiency of the assessment.

### Q: How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

**A:** I increased security by implementing multiple layers of defense, including rigorous input validation, securing API interactions, updating cryptographic libraries, and enforcing HTTPS for all communications. Moving forward, I plan to continue using a combination of automated tools like OWASP Dependency-Check and manual code reviews to ensure a thorough assessment of vulnerabilities and the selection of appropriate mitigation strategies.

### Q: How did you make sure the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

**A:** To ensure both functionality and security, I integrated secure coding practices throughout the development process. After refactoring the code, I conducted comprehensive manual and static testing to verify that no new vulnerabilities were introduced. This approach ensured the application remained robust against potential threats while maintaining its functionality.

### Q: What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

**A:** I utilized several key resources and tools, including OWASP Dependency-Check for static testing, which helped identify and manage dependencies with known vulnerabilities. Additionally, I applied strong cryptographic algorithms like AES and RSA for securing data, and adhered to secure coding guidelines from OWASP and Java. These practices will undoubtedly be beneficial in future projects, providing a solid foundation for maintaining software security.

### Q: What might you show future employers from this assignment? Why?

**A:** This project showcases my ability to conduct thorough vulnerability assessments and implement secure coding practices, which are crucial skills in today’s cybersecurity landscape. By demonstrating my proficiency with industry-standard tools and techniques, I can provide potential employers with concrete examples of my technical capabilities and my commitment to developing secure software solutions.

