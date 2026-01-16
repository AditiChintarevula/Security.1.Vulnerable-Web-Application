# 🌐 Vulnerable Web Application – Security Analysis
# 📌 Overview

This project focuses on the security analysis of a deliberately vulnerable web application using static code analysis and manual testing. The assessment aligns findings with the OWASP Top 10 (2021) and demonstrates exploitation techniques alongside secure remediation strategies.

# 🎯 Objectives

Identify insecure coding patterns

Map vulnerabilities to OWASP Top 10 categories

Demonstrate exploitation impact

Recommend secure coding fixes

# 🔎 Assessment Approach
Static Code Scan Findings

Hardcoded credentials

Insecure cryptographic hashing (MD5)

Unsafe XML parsing (XXE risk)

Command injection via subprocess calls

XSS risks using unsafe rendering

Manual Security Testing

Broken authentication (brute-force login)

Broken access control via cookie manipulation

SQL injection via API path parameters

Reflected XSS attempts

# ⚠️ Severity Highlights

Critical: SQL Injection, Broken Access Control

High: Broken Authentication, Weak Cryptography, XSS

# 🛠️ Mitigations Implemented

Parameterized queries for database access

Server-side authorization enforcement

Secure password hashing (bcrypt/Argon2)

Input validation and output encoding

Rate limiting and account lockout mechanisms

# 📚 Standards & References

OWASP Top 10 (2021)

Secure Coding Best Practices

# 🧠 Key Takeaways

This project demonstrates strong foundations in web application security, vulnerability analysis, and secure development practices.

