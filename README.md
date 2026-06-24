# CS305: Software Security

## Overview
This project involved securing a web application for Artemis Financial, a company that builds personalized financial plans for its clients, including investments, retirement planning, and insurance. The goal was to modernize the application while ensuring all client data stayed protected, both in transit and at rest.

## Approach
Security was layered in through HTTPS for encrypted client-server communication, SHA-256 hashing to verify data integrity, and a self-signed certificate to enable a secure connection on port 8443. The OWASP Dependency Check tool was used to scan for known CVE vulnerabilities, and any flagged dependencies were addressed before final delivery.

## Reflection
Secure coding protects an application from common exploits like remote code execution and injection attacks, which also helps build client trust. The most challenging part of the project was tracking down and addressing every vulnerability, since the process can be tedious, while the most rewarding part was learning how to create and apply a signed certificate. Verifying the application over port 8443 and rerunning the dependency check confirmed the encryption and security measures were working as intended.

## Skills Demonstrated
- Secure coding and vulnerability remediation
- HTTPS and SHA-256 implementation
- Dependency vulnerability scanning (OWASP)
- Certificate creation and management
