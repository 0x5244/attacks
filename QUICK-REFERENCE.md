# Quick Reference Guide

## Common Attack Categories

### Top 10 Most Critical Attacks

1. **SQL Injection** - Injecting malicious SQL queries to access/modify database data
2. **Cross-Site Scripting (XSS)** - Injecting malicious scripts into web pages
3. **Remote Code Execution (RCE)** - Executing arbitrary code on a target system
4. **Broken Authentication** - Exploiting weak authentication mechanisms
5. **CSRF** - Forcing users to execute unwanted actions on authenticated sessions
6. **Insecure Deserialization** - Exploiting object deserialization vulnerabilities
7. **SSRF** - Making server perform requests to unintended locations
8. **Security Misconfiguration** - Exploiting improperly configured security settings
9. **Privilege Escalation** - Gaining higher access levels than authorized
10. **IDOR** - Accessing objects by manipulating identifiers

### Attack Categories Quick Reference

| Category | Common Attacks | Primary Risk |
|----------|---------------|--------------|
| **Web Application** | SQLi, XSS, CSRF | Data theft, site defacement |
| **API Security** | API misconfiguration, rate limiting bypass | Unauthorized access, data exposure |
| **Authentication** | Brute force, session hijacking | Account takeover |
| **Cloud Security** | IAM misconfiguration, S3 exposure | Data breaches, resource abuse |
| **Code Execution** | RCE, command injection | Full system compromise |
| **Cryptographic** | Weak encryption, padding oracle | Data decryption, integrity loss |
| **Container/K8s** | Container escape, RBAC issues | Infrastructure compromise |
| **DevOps/CI-CD** | Pipeline attacks, secret exposure | Supply chain compromise |

### OWASP Top 10 Mapping

This guide covers attacks from the OWASP Top 10:

1. **A01:2021 - Broken Access Control**
   - IDOR, Privilege Escalation, CORS Misconfiguration

2. **A02:2021 - Cryptographic Failures**
   - Insecure Cryptographic Storage, Weak TLS

3. **A03:2021 - Injection**
   - SQL Injection, Command Injection, LDAP Injection, XXE

4. **A04:2021 - Insecure Design**
   - Business Logic Vulnerabilities

5. **A05:2021 - Security Misconfiguration**
   - Security Misconfiguration, Default Credentials

6. **A06:2021 - Vulnerable and Outdated Components**
   - Insecure Docker Images, Dependency Vulnerabilities

7. **A07:2021 - Identification and Authentication Failures**
   - Broken Authentication, Session Fixation, Brute Force

8. **A08:2021 - Software and Data Integrity Failures**
   - Insecure Deserialization, CI/CD Pipeline Attacks

9. **A09:2021 - Security Logging and Monitoring Failures**
   - Insufficient Logging and Monitoring

10. **A10:2021 - Server-Side Request Forgery (SSRF)**
    - SSRF, SSRF in Cloud Services

### Severity Levels

- **Critical**: RCE, SQLi, Authentication Bypass
- **High**: XSS, CSRF, Privilege Escalation, IDOR
- **Medium**: Information Disclosure, DoS, Misconfiguration
- **Low**: Open Redirects (context-dependent)

### Common Remediation Patterns

1. **Input Validation**
   - Whitelist acceptable input
   - Sanitize and escape output
   - Use parameterized queries

2. **Authentication & Authorization**
   - Implement MFA
   - Use strong session management
   - Apply least privilege principle

3. **Configuration Hardening**
   - Disable unnecessary features
   - Use security headers
   - Keep systems updated

4. **Encryption**
   - Use TLS 1.2+
   - Implement proper key management
   - Use modern, strong algorithms

5. **Monitoring & Logging**
   - Log security events
   - Implement anomaly detection
   - Set up alerting

---

**Quick Navigation**: Use the table of contents to jump to specific attacks or browse by category.
