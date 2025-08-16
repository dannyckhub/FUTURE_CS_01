# FUTURE_CS_01
Web Application Security Testing

🛡️ Web Security Testing on DVWA

This project involves penetration testing on DVWA (Damn Vulnerable Web Application) to identify and exploit common web application vulnerabilities.
The goal was to simulate real-world attacks, analyze weaknesses, and document security risks along with remediation strategies.

🎯 Objectives

Understand how attackers exploit web vulnerabilities

Practice offensive security techniques in a safe environment

Gain hands-on experience with web penetration testing tools

Document findings and propose security mitigations

🔧 Tools & Technologies Used

DVWA → Target web application

Burp Suite → Proxy & traffic interception for testing

SQLMap → Automated SQL Injection testing

Kali Linux / Windows → Testing environments

Web Browser + FoxyProxy → Proxying requests through Burp Suite

🕵️ Vulnerabilities Tested

SQL Injection (SQLi)

Used SQLMap and manual payloads to bypass login forms and extract database info.

Cross-Site Scripting (XSS)

Injected malicious JavaScript into vulnerable input fields.

Demonstrated stored and reflected XSS attacks.

Broken Authentication & Session Management

Tested weak login forms.

Intercepted cookies via Burp Suite to hijack sessions.

File Upload Vulnerabilities

Uploaded malicious files (with bypass techniques).

Verified execution of payloads on the server.

📊 Highlights & Results

Successfully intercepted and modified requests using Burp Suite

Exploited SQL injection to extract database contents

Demonstrated XSS attacks with JavaScript payloads

Simulated session hijacking by manipulating cookies

Identified improper file upload handling

🛠️ Skills Gained

Web application penetration testing

Exploit development and payload crafting

Traffic interception and request manipulation

Vulnerability analysis & documentation

Using Burp Suite, SQLMap, and manual testing techniques

🛡️ Mitigation Recommendations

Use parameterized queries / prepared statements

Implement proper input validation and sanitization

Use secure session management practices (HttpOnly, Secure cookies)

Enforce strict file upload restrictions (MIME/type check, file extensions)

Apply Web Application Firewall (WAF) and continuous monitoring
