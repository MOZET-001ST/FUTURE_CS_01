FUTURE_CS_01 - Cyber Security Internship Task 1

Intern: Sandile Theron Lubisi  
Track: Cyber Security  
Task: Vulnerability Assessment Report  
Target: `demo.testfire.net` (Altoro Mutual)  

Task Overview
The objective of this task was to perform a black-box, non-destructive vulnerability assessment on a public-facing web application and document the findings in a professional, client-ready report. The assessment identified 14 vulnerabilities, including a Critical SQL Injection flaw and a High-risk Slowloris Denial of Service exposure.

Tools & Methodology Used
Nmap: Used via a remote AWS EC2 cloud instance for port scanning, service enumeration, and vulnerability scripting (NSE).
OWASP ZAP: Used for passive web traffic interception and HTTP header analysis.
Chrome DevTools: Used for manual verification of cookies, DOM elements, and basic SQL Injection testing.
Canva/HTML: Used for formatting the final executive report.

Repository Contents
 `Vulnerability Assessment Report — demo.testfire.net` - The final, executive-ready assessment report.
 `/Evidence` - A directory containing raw Nmap scan outputs and DevTools screenshots verifying the vulnerabilities.

Key Findings
1. Critical: Authentication Bypass via SQL Injection (Login Form)
2. High: Slowloris DoS Vulnerability (CVE-2007-6750)
3. Medium: Systemic absence of Content Security Policy and Anti-CSRF Tokens
4. Medium: Insecure Session Cookies (Missing Secure/HttpOnly flags)
