# Web_App_CheckList_And_Links

1. Cross-Site Scripting (XSS)
   Command: <script>alert(1)</script>
          <script>alert(document.cookie)</script>
   Link : https://github.com/ihebski/XSS-Payloads
   
3. SQL Injection (SQLi)
   Command: ' OR 1=1--
          : '

4. Command Injection - Any file upload functionality
   Steps: upload a file with Extention of .php .html .phtml after that open the file which was uploaded in tab then enter command to check OS details whoami
   Link : https://gist.github.com/joswr1ght/22f40787de19d80d110b37fb79ac3985

5. Html Injection - Low
   Command : <h1>HTML</html>
   
6. CSS injection - Low
   Command : <style>*{background: red! important} </style>???

7. Iframe Injection - Low
   Command : <iframe src="https://www.w3schools.com" title="W3Schools Free Online Web Tutorials"></iframe>

8. Security Headers - Checks for the if all security Headers are present or not 
   Link : https://securityheaders.com/

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
_________________________________Session related Bugs______________________________
1. Session handling
2. Session Fixation
3. Test tokens for predictability
4. Insecure transmission of tokens
5. Session does not expire after password change
6. Session did not expired after logout
7. Cookie expiration time
8. Check HTTPOnly and Secure flags
9. Access controls


