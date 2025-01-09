# Cybersecurity
I started my project by taking ( Juice Shop ) as my mock based web application https://github.com/juice-shop/juice-shop.git
Using command prompt I cloned the file in my local machine and installed npm [Uploading My work.txt…]() . After which I ran the program on http://localhost:3000
Once online i ran the link in OWASP ZAP and located vulnerabilities https://github.com/user-attachments/files/18360785/My.work.txt

Security Improvement Focus Areas
 1. Cross-Site Scripting (XSS)
Mitigate XSS by validating and encoding user inputs. Regularly review code to ensure all input fields are secure.
 2. Weak Password Storage
Enhance password storage with strong hashing algorithms like bcrypt, implement salting, and enforce robust password policies.
 3. Simple Security Misconfigurations
Address misconfigurations by setting essential security headers (e.g., CSP, X-Frame-Options), securing access controls, and removing default credentials.
 4. Cloud Security
Secure cloud metadata to prevent exposure and unauthorized access.
 5. Database Security
Prevent SQL Injection through parameterized queries and input validation.
 6. Content Security Policy (CSP)
Enforce a CSP to protect against XSS and other injection attacks.
 7. Cross-Domain Configuration
Fix cross-domain misconfigurations to secure data sharing between domains.
 8. Anti-clickjacking
Implement the X-Frame-Options header to defend against clickjacking.
 9. Session Management
Secure sessions by using cookies instead of URL-based session IDs.
 10. JavaScript Security
Update vulnerable JS libraries to prevent exploitation.
 11. Network Security
Protect private IP addresses to avoid exposing internal networks.

