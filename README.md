# FUTURE_CS_01
# OWASP ZAP Vulnerability Assessment Report

This project was part of a cybersecurity training and hands-on learning experience focused on vulnerability scanning and secure coding best practices.
This repository contains a web application vulnerability assessment report created using OWASP ZAP as part of an internship project.

##  Project Overview

- Intern Name: Shreya Sharma  
- Target Application: [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/)  
- Host OS: Kali Linux  
- Security Tool Used: OWASP ZAP  

The purpose of this project was to conduct an automated security scan against a deliberately vulnerable web application and identify risks aligned with the [OWASP Top 10](https://owasp.org/www-project-top-ten/).

##  Report Summary

The assessment revealed multiple vulnerabilities:

1. SQL Injection (SQLite)
   - Risk: High
   - Fix: Use parameterized queries and input validation

2. Missing Content Security Policy (CSP)
   - Risk: Medium
   - Fix: Add a secure CSP header

3. Session ID in URL
   - Risk: Medium
   - Fix: Switch to cookie-based sessions with secure flags

4. Vulnerable JS Library
   - Risk: Medium
   - Fix: Upgrade jQuery to the latest secure version

5. Missing Anti-Clickjacking Header
   - Risk: Medium
   - Fix: Add `X-Frame-Options` header

> See the full PDF report [here](./FUTURE_CS_01-1.pdf)

##  Files

- `FUTURE_CS_01-1.pdf` — Final security report generated after the OWASP ZAP scan.


##  Conclusion

The assessment successfully identified key security flaws in the application that map to OWASP Top 10 categories. Timely mitigation of these issues will significantly strengthen the security posture of the target system.

---



