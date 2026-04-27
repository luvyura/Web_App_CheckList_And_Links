# Web_App_CheckList_And_Links


## Injection Vulnerabilities
1. Cross-Site Scripting (XSS) – Reflected, Stored, DOM-based
2. SQL Injection (SQLi)
3. Command Injection – https://gist.github.com/joswr1ght/22f40787de19d80d110b37fb79ac3985
4. HTML Injection (Low)
5. CSS Injection (Low)
6. Iframe Injection (Low)
7. Server-Side Template Injection (SSTI)
8. XML External Entity (XXE) Injection
9. LDAP Injection
10. NoSQL Injection 

## Authentication & Account Security
1. Weak Password Policy
2. Password Reuse Allowed
3. Username Enumeration
4. Insufficient Email Verification Process
5. Weak Registration Implementation
6. Pre-Account Takeover
7. CAPTCHA Reuse / Bypass
8. OTP Bypass
9. OTP Brute Force
10. Long Password DoS Attack
11. Account Lockout DoS
12. Remember Me Function Issues
13. Auto-complete Enabled on Sensitive Fields
14. Multi-Factor Authentication (MFA) Issues 

## Authorization & Access Control
1. Insecure Direct Object Reference (IDOR)
2. Broken Role-Based Access Control (RBAC)
3. Privilege Escalation (Vertical/Horizontal)
4. Missing Access Controls on APIs / Endpoints
5. Forced Browsing / Direct Access to Restricted Pages

## Session Management Issues
1. Session Fixation
2. Session ID Predictability
3. Session Not Expiring After Logout
4. Session Not Invalidated After Password Change
5. Insecure Transmission of Session Tokens
6. Missing HttpOnly and Secure Cookie Flags
7. Improper Cookie Expiration Time
8. Session Hijacking Possibilities
9. Concurrent Session Handling Issues 

## Token & JWT Issues
1. JWT Weak Signature / alg=none
2. JWT Token Manipulation
3. Token Predictability
4. Insecure Token Storage (LocalStorage / SessionStorage)
5. Missing Token Expiration / Revocation

## Security Misconfigurations
1. Missing Security Headers
2. Content-Security-Policy (CSP)
3. X-Frame-Options
4. X-Content-Type-Options
5. Strict-Transport-Security (HSTS)
6. Improper Cache Control
7. Browser Cache Storing Sensitive Data
8. Verbose Error Messages / Stack Traces
9. Directory Listing Enabled 

## Network & Transport Security
1. Unencrypted Communication (HTTP instead of HTTPS)
2. SSL/TLS Misconfiguration (Weak Ciphers, Old Protocols)
3. HTTPS Downgrade Attack
4. Mixed Content Issues 

## Input Validation & Business Logic
1. Improper Input Validation (accepting special characters without encoding)
2. Response Tampering
3. Business Logic Flaws
4. Mass Assignment Vulnerability
5. Parameter Pollution 

## Rate Limiting & Abuse
1. No Rate Limiting
2. API Abuse / Resource Exhaustion
3. Brute Force Attacks
4. CAPTCHA Bypass

## Data Exposure & Privacy
1. PII Information Disclosure
2. Sensitive Data Exposure in Responses
3. Data Leakage via APIs
4. Backup File Exposure (.bak, .old, etc.) 

## Host & Header Attacks
1. Host Header Injection
2. HTTP Header Injection / CRLF Injection
3. Open Redirect 

## Account & Functionality Issues
1. Delete Account Without Confirmation
2. Missing Email Confirmation on Critical Actions
3. Improper Password Reset Flow
4. Account Takeover via Logic Flaws

## File Upload & Handling
1. Unrestricted File Upload
2. Malicious File Upload (RCE, XSS)
3. MIME Type Bypass
4. File Path Traversal (../) 

## Advanced / Modern Checks
1. Cross-Origin Resource Sharing (CORS) Misconfiguration
2. Clickjacking
3. Web Cache Poisoning
4. Subdomain Takeover
5. SSRF (Server-Side Request Forgery)

   
++++++++++++++++++++++++++++++++++Few Random+++++++++++++++++++++++++

1. Cross-Site Scripting (XSS)
3. SQL Injection (SQLi)
4. Command Injection - https://gist.github.com/joswr1ght/22f40787de19d80d110b37fb79ac3985
5. Html Injection - Low  
6. CSS injection - Low
7. Iframe Injection - Low
8. Security Headers - Checks for the if all security Headers are present or not 
9. Improper input validation - Check if application is aceepting any special character without enconding
10. IDOR
11. No Rate Limiting
12. Delete account without confirmation
13. Long Paaword Dos Attack
14. Account lockout application dos
15. Host header attack
16. Username Enumeration
17. Weak password policy
18. Password Reuse
19. ​Insufficient email verification process
20. Weak registration implementation
21. Pre account takeover
22. Capcha reuse
23. Remember me function bug
24. Auto-complete
25. Unencrypted Communication - if application is working in http if working in https downgrade it like remove "S" from http
26. Test response tampering
27. OTP bypas
28. OTP bruteforce
29. JWT, check common flaws
30. Browser cache
31. PII information Disclosure
32. RBAC
33. Improper Cache Controle
34. TLS
35. Lucky13

    
______________________________Session related Bugs______________________________
1. Session handling
2. Session Fixation
3. Test tokens for predictability
4. Insecure transmission of tokens
5. Session does not expire after password change
6. Session did not expired after logout
7. Cookie expiration time
8. Check HTTPOnly and Secure flags
9. Access controls


