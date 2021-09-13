# Day 53 -  SQL Injection

## Daily Questions

- What is SQL injection?
  - A type of database attack that is someone putting arbitrary SQL code into a database query.
- What are 3 methods SQL injection can be done by?
  - User Input, Website cookies, and  Http Headers.
- How can we detect and sanitize SQL injection attacks?
  - Firewalls and IDS can detect injections. Whitelisting input validation, use statements with parameterized queries, escape all user-supplied input, and limit account privileges.