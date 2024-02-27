*Juan Miguel Cano*

*February 26, 2024*

# Readings: XSS with w3af, DVWA

## Reading 36
[Cross-site scripting](https://portswigger.net/web-security/cross-site-scripting)

1. Explain how a cross-site scripting attack works in non-technical terms.
    - XSS attacks let attackers inject malicious code into web pages viewed by other users.
2. What are the three types of XSS attacks?
    - Stored XXSS
    - Reflected XSS
    - DOM-based XSS
3. If an attacker successfully exploits a XSS vulnerability, what malicious actions would they be able to perform?
    - Steal sensitive data like login credentials or session tokens.
    - Hijack user sessions, impersonating them.
    - Deface websites by modifying content or layout.
    - Redirect users to malicious sites.
    - Execute unauthorized actions on behalf of users.
4. What are some security controls that can be implemented to prevent XSS attacks?
    - Input validation to filter out malicious scripts.
    - Output encoding to ensure user input is treated as data, not code.
    - Implement Content Security Policy (CSP) to restrict resource loading.
    - Set HTTPOnly and Secure flags for cookies to prevent script access.
## Bookmark and Review
- [Security Report for In-Production Web Applications](https://www.rapid7.com/globalassets/_pdfs/whitepaperguide/rapid7-tcell-application-security-report.pdf)