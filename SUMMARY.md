# Table of Contents

* [Introduction](README.md)
* [Attack Categories Overview](Attack-and-Remediation.md#categories-of-attacks)

## Specific Attacks

### Web Application Attacks

* [1. SQL Injection (SQLi)](Attack-and-Remediation.md#1-sql-injection-sqli)
* [2. Cross-Site Scripting (XSS)](Attack-and-Remediation.md#2-cross-site-scripting-xss)
* [3. Cross-Site Request Forgery (CSRF)](Attack-and-Remediation.md#3-cross-site-request-forgery-csrf)
* [4. Directory Traversal](Attack-and-Remediation.md#4-directory-traversal)
* [12. XML External Entity (XXE)](Attack-and-Remediation.md#12-xml-external-entity-xxe)
* [13. Open Redirect](Attack-and-Remediation.md#13-open-redirect)
* [17. File Upload Vulnerability](Attack-and-Remediation.md#17-file-upload-vulnerability)
* [22. HTTP Parameter Pollution (HPP)](Attack-and-Remediation.md#22-http-parameter-pollution-hpp)
* [23. Open Redirects (Unvalidated Redirects)](Attack-and-Remediation.md#23-open-redirects-unvalidated-redirects-and-forwards)
* [24. XML Injection](Attack-and-Remediation.md#24-xml-injection)
* [26. HTTP Response Splitting](Attack-and-Remediation.md#26-http-response-splitting)
* [31. Cross-Site WebSocket Hijacking](Attack-and-Remediation.md#31-cross-site-websocket-hijacking)
* [32. Clickjacking](Attack-and-Remediation.md#32-clickjacking)
* [36. Cross-Site Script Inclusion (XSSI)](Attack-and-Remediation.md#36-cross-site-script-inclusion-xssi)
* [37. Cross-Site History Manipulation](Attack-and-Remediation.md#37-cross-site-history-manipulation)
* [38. Server-Side Template Injection (SSTI)](Attack-and-Remediation.md#38-server-side-template-injection-ssti)
* [39. CORS Misconfiguration](Attack-and-Remediation.md#39-cross-origin-resource-sharing-cors-misconfiguration)

### Code Execution & Injection Attacks

* [5. Remote Code Execution (RCE)](Attack-and-Remediation.md#5-remote-code-execution-rce)
* [8. Insecure Deserialization](Attack-and-Remediation.md#8-insecure-deserialization)
* [25. LDAP Injection](Attack-and-Remediation.md#25-ldap-injection)
* [27. Command Injection](Attack-and-Remediation.md#27-command-injection)

### Access Control & Authentication Attacks

* [6. Insecure Direct Object References (IDOR)](Attack-and-Remediation.md#6-insecure-direct-object-references-idor)
* [10. Password Attacks (Brute Force, Credential Stuffing)](Attack-and-Remediation.md#10-password-attacks-brute-force-credential-stuffing)
* [11. Broken Authentication and Session Management](Attack-and-Remediation.md#11-broken-authentication-and-session-management)
* [16. Privilege Escalation](Attack-and-Remediation.md#16-privilege-escalation)
* [28. Business Logic Vulnerability](Attack-and-Remediation.md#28-business-logic-vulnerability)
* [29. Session Fixation](Attack-and-Remediation.md#29-session-fixation)

### Cryptographic Attacks

* [18. Insecure Cryptographic Storage](Attack-and-Remediation.md#18-insecure-cryptographic-storage)
* [34. Padding Oracle Attack](Attack-and-Remediation.md#34-padding-oracle-attack)
* [41. Elliptic Curve Cryptography (ECC) Attack](Attack-and-Remediation.md#41-elliptic-curve-cryptography-ecc-attack)
* [42. Side-Channel Attack](Attack-and-Remediation.md#42-side-channel-attack)
* [43. Padding Oracle Attack (Advanced Variant)](Attack-and-Remediation.md#43-padding-oracle-attack-advanced-variant)
* [51. Cryptanalysis Techniques (Chosen Ciphertext Attack)](Attack-and-Remediation.md#51-cryptanalysis-techniques-chosen-ciphertext-attack)
* [65. Differential Cryptanalysis](Attack-and-Remediation.md#65-differential-cryptanalysis)
* [66. Lattice-Based Cryptography Attacks](Attack-and-Remediation.md#66-lattice-based-cryptography-attacks)

### Network & Infrastructure Attacks

* [7. Denial of Service (DoS/DDoS)](Attack-and-Remediation.md#7-denial-of-service-dos--distributed-denial-of-service-ddos)
* [19. Server-Side Request Forgery (SSRF)](Attack-and-Remediation.md#19-server-side-request-forgery-ssrf)
* [21. Insufficient Transport Layer Security (TLS)](Attack-and-Remediation.md#21-insufficient-transport-layer-security-tls)
* [35. Cache Poisoning](Attack-and-Remediation.md#35-cache-poisoning)
* [49. SSRF in Cloud Services](Attack-and-Remediation.md#49-server-side-request-forgery-ssrf-in-cloud-services)

### System & Memory Attacks

* [14. Buffer Overflow](Attack-and-Remediation.md#14-buffer-overflow)
* [15. Race Condition](Attack-and-Remediation.md#15-race-condition)
* [33. Race Conditions in Distributed Systems](Attack-and-Remediation.md#33-race-conditions-in-distributed-systems)
* [40. Race Condition in File Systems](Attack-and-Remediation.md#40-race-condition-in-file-systems)

### Configuration & Monitoring

* [9. Security Misconfiguration](Attack-and-Remediation.md#9-security-misconfiguration)
* [20. Insufficient Logging and Monitoring](Attack-and-Remediation.md#20-insufficient-logging-and-monitoring)
* [30. Sensitive Data Exposure](Attack-and-Remediation.md#30-sensitive-data-exposure)
* [60. Insecure Default Configurations in Cloud](Attack-and-Remediation.md#60-insecure-default-configurations-in-cloud-environments)

### API Security

* [45. API Misconfiguration](Attack-and-Remediation.md#45-api-misconfiguration)
* [47. API Rate Limiting Bypass](Attack-and-Remediation.md#47-api-rate-limiting-bypass)
* [48. API Key Leakage](Attack-and-Remediation.md#48-api-key-leakage)
* [58. Insecure API Gateway Configuration](Attack-and-Remediation.md#58-insecure-api-gateway-configuration)

### Cloud Security

* [44. Cloud Misconfiguration (S3 Bucket Exposure)](Attack-and-Remediation.md#44-cloud-misconfiguration-s3-bucket-exposure)
* [46. Cloud Privilege Escalation (AWS IAM Role Misuse)](Attack-and-Remediation.md#46-cloud-privilege-escalation-aws-iam-role-misuse)
* [52. GCP IAM Misconfigurations](Attack-and-Remediation.md#52-cloud-specific-vulnerability-gcp-iam-misconfigurations)
* [54. Azure AD Misconfigurations](Attack-and-Remediation.md#54-cloud-specific-vulnerability-azure-active-directory-aad-misconfigurations)
* [62. Misconfigured VPC in AWS](Attack-and-Remediation.md#62-misconfigured-virtual-private-cloud-vpc-in-aws)
* [63. Insecure Serverless Function Configurations](Attack-and-Remediation.md#63-insecure-serverless-function-configurations)
* [64. IAM Role Misconfigurations in AWS](Attack-and-Remediation.md#64-iam-role-misconfigurations-in-aws)
* [69. Misconfigured Google Cloud Functions](Attack-and-Remediation.md#69-cloud-specific-vulnerability-misconfigured-google-cloud-functions)
* [70. Misconfigured AWS Lambda Permissions](Attack-and-Remediation.md#70-misconfigured-aws-lambda-permissions)

### Container & Orchestration Security

* [53. Container Vulnerabilities (Docker Privilege Escalation)](Attack-and-Remediation.md#53-container-vulnerabilities-docker-privilege-escalation)
* [57. Insecure Docker Image Vulnerabilities](Attack-and-Remediation.md#57-insecure-docker-image-vulnerabilities)
* [59. Improper RBAC in Kubernetes](Attack-and-Remediation.md#59-improper-role-based-access-control-rbac-in-kubernetes)
* [61. Kubernetes Pod Security Policy Misconfiguration](Attack-and-Remediation.md#61-kubernetes-pod-security-policy-psp-misconfiguration)
* [67. Container Escape Vulnerability](Attack-and-Remediation.md#67-container-escape-vulnerability-docker-and-kubernetes)
* [68. Insecure Kubernetes Network Policies](Attack-and-Remediation.md#68-insecure-kubernetes-network-policies)

### DevOps & CI/CD Security

* [55. CI/CD Pipeline Vulnerabilities](Attack-and-Remediation.md#55-cicd-pipeline-vulnerabilities-insecure-artifacts-in-build-process)
* [56. Secret Management Vulnerabilities](Attack-and-Remediation.md#56-secret-management-vulnerabilities-exposed-secrets-in-code-repositories)

### Microservices Security

* [50. Microservices Communication Vulnerabilities](Attack-and-Remediation.md#50-microservices-communication-vulnerabilities)

---

## About This Guide

This comprehensive guide covers 70 specific security attacks with detailed code examples and remediation strategies. Each attack entry includes vulnerable code examples, secure implementations, and best practices for prevention.
