# Man-in-the-Middle (MITM) Attack on bWAPP

## Description

Because the application uses unencrypted HTTP communication, an attacker can intercept and modify sensitive login data during transmission.

In this test, I used **Burp Suite** to capture the HTTP login request, modified the parameters, and successfully gained access as a different user—demonstrating how insecure communication can lead to account takeover.

### Vulnerability Mapped To
- **OWASP Top 10 (2021):**  
  - A02: Cryptographic Failures  
  - A03: Sensitive Data Exposure

### Severity
- **Risk Level:** High  
- **bWAPP Setting:** Medium Security
