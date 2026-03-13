# SQL Injection Authentication Bypass

Lab Source:
PortSwigger Web Security Academy

Vulnerability:
SQL Injection

Description:

The login functionality was vulnerable to SQL Injection which allowed authentication bypass.

Payload Used:

' OR 1=1 --

Steps to Reproduce:

1 Go to login page
2 Enter payload in username field
3 Login successful

Impact:

Attacker can login without valid credentials.

Recommendation:

Use parameterized queries.
