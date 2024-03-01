*Juan Miguel Cano*

*February 29, 2024*

# Readings: SQLi with Burp Suite, WebGoat

## Reading 39
[Understanding SQL Injection, Identification and Prevention](https://www.varonis.com/blog/sql-injection-identification-and-prevention-part-1/)

1. What is SQL injection?
    - SQL injection is a hacking technique where attackers insert malicious SQL code into a web application to maniputlate the database.
2. Can you give an example of how a hacker could use SQL injection to gain unauthorized access?
    - The attecker inputs`' OR '1'='1' into a login form, tricking the application into executing a query that always returns true, granting unauthorized access.
3. What are some ways to prevent SQL injection attacks on a web server?
    - 1. Use prepared statements and parameterized queries.
    - 2. Sanitize and validate user inputs.
    - 3. Apply least privilege access for database accounts.
    - 4. Keep software and databases updated.
    - 5. use web application firewalls (WAFs).