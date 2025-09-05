# ASVS Index

## Table of Contents
- [Objective](#objective)
- [V1: Architecture, Design and Threat Modeling Requirements](#v1-architecture-design-and-threat-modeling-requirements)
- [V2: Authentication Verification Requirements](#v2-authentication-verification-requirements)
- [V3: Session Management Verification Requirements](#v3-session-management-verification-requirements)
- [V4: Access Control Verification Requirements](#v4-access-control-verification-requirements)
- [V5: Validation, Sanitization and Encoding Verification Requirements](#v5-validation-sanitization-and-encoding-verification-requirements)
- [V6: Stored Cryptography Verification Requirements](#v6-stored-cryptography-verification-requirements)
- [V7: Error Handling and Logging Verification Requirements](#v7-error-handling-and-logging-verification-requirements)
- [V8: Data Protection Verification Requirements](#v8-data-protection-verification-requirements)
- [V9: Communications Verification Requirements](#v9-communications-verification-requirements)
- [V10: Malicious Code Verification Requirements](#v10-malicious-code-verification-requirements)
- [V11: Business Logic Verification Requirements](#v11-business-logic-verification-requirements)
- [V12: File and Resources Verification Requirements](#v12-file-and-resources-verification-requirements)
- [V13: API and Web Service Verification Requirements](#v13-api-and-web-service-verification-requirements)
- [V14: Configuration Verification Requirements](#v14-configuration-verification-requirements)

## Objective
The objective of this index is to help an OWASP [Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/) (ASVS) user quickly identify relevant cheat sheets for each section. This index is based on **version 5.0** of ASVS.

---

## V1: Architecture, Design and Threat Modeling Requirements
- **V1.1 Secure SDLC**: Threat Modeling, Abuse Case, Attack Surface Analysis  
- **V1.2 Authentication Architecture**: Authentication  
- **V1.3 Session Management Architecture**: Session Management  
- **V1.4 Access Control Architecture**: Access Control  
- **V1.5 Input & Output Architecture**: Input Validation, Deserialization  
- **V1.6 Cryptographic Architecture**: Cryptographic Storage, Key Management  
- **V1.7 Errors, Logging & Auditing Architecture**: Logging, Error Handling  
- **V1.8 Data Protection & Privacy Architecture**: User Privacy Protection  
- **V1.9 Communications Architecture**: Transport Layer Security  
- **V1.10 Malicious Software Architecture**: Third Party JS Management, Virtual Patching  
- **V1.11 Business Logic Architecture**: Abuse Case  
- **V1.12 Secure File Upload Architecture**: File Upload  
- **V1.13 API Architecture**: REST Security, Web Service Security  
- **V1.14 Configuration Architecture**: Docker Security, Vulnerable Dependency Management, Content Security Policy  

---

## V2: Authentication Verification Requirements
- **V2.1 Password Security**: Choosing/Using Security Questions, Forgot Password, Credential Stuffing Prevention, Password Storage  
- **V2.2 General Authenticator**: Authentication, Transport Layer Security  
- **V2.3 Authenticator Lifecycle**: None  
- **V2.4 Credential Storage**: Password Storage  
- **V2.5 Credential Recovery**: Forgot Password, Choosing/Using Security Questions  
- **V2.6 Look-up Secret Verifier**: None  
- **V2.7 Out-of-Band Verifier**: Forgot Password  
- **V2.8 Single/Multi-Factor OTP**: None  
- **V2.9 Cryptographic Software & Devices**: Cryptographic Storage, Key Management  
- **V2.10 Service Authentication**: None  

---

## V3: Session Management Verification Requirements
- **V3.1 Fundamentals**: None  
- **V3.2 Session Binding**: Session Management, Transport Layer Security  
- **V3.3 Logout & Timeout**: Session Management  
- **V3.4 Cookie-Based Session**: Session Management, CSRF Prevention  
- **V3.5 Token-Based Session**: JWT for Java, REST Security  
- **V3.6 Federation/Re-authentication**: None  
- **V3.7 Defenses Against Exploits**: Session Management, Transaction Authorization  

---

## V4: Access Control Verification Requirements
- **V4.1 General Access Control**: Access Control, Authorization Testing Automation  
- **V4.2 Operation Level Access**: IDOR Prevention, CSRF Prevention, Authorization Testing Automation  
- **V4.3 Other Considerations**: REST Assessment, Multifactor Authentication  

---

## V5: Validation, Sanitization and Encoding Verification Requirements
- **V5.1 Input Validation**: Mass Assignment, Input Validation  
- **V5.2 Sanitization & Sandboxing**: SSRF Prevention, XSS Prevention, DOM-based XSS, Unvalidated Redirects/Forwards  
- **V5.3 Output Encoding & Injection Prevention**: XSS Prevention, DOM-based XSS, HTML5 Security, Injection Prevention (general & Java), LDAP Injection, OS Command Injection, File Upload Protection, Query Parameterization, SQL Injection, Bean Validation, XML Security, XXE Prevention  
- **V5.4 Memory/String/Unmanaged Code**: None  
- **V5.5 Deserialization Prevention**: Deserialization, XXE Prevention, XML Security  

---

## V6: Stored Cryptography Verification Requirements
- **V6.1 Data at Rest**: Cryptographic Storage, Key Management  
- **V6.2 Key Management**: Key Management, Cryptographic Storage  
- **V6.3 Random Number Generation**: Cryptographic Storage  

---

## V7: Error Handling and Logging Verification Requirements
- **V7.1 Error Handling**: Error Handling  
- **V7.2 Logging**: Logging  
- **V7.3 Auditing**: Logging  

---

## V8: Data Protection Verification Requirements
- **V8.1 Data Classification**: User Privacy Protection  
- **V8.2 Data Retention/Disposal**: User Privacy Protection  
- **V8.3 Data Minimization**: User Privacy Protection  

---

## V9: Communications Verification Requirements
- **V9.1 Secure Transport**: Transport Layer Security  
- **V9.2 API Communications**: REST Security, Web Service Security  

---

## V10: Malicious Code Verification Requirements
- **V10.1 Third-Party Code**: Third Party JS Management  
- **V10.2 Anti-Tampering**: Virtual Patching  

---

## V11: Business Logic Verification Requirements
- **V11.1 Abuse Case**: Abuse Case  
- **V11.2 Process Logic**: Abuse Case  

---

## V12: File and Resources Verification Requirements
- **V12.1 Secure File Upload**: File Upload  
- **V12.2 Resource Access**: Access Control  

---

## V13: API and Web Service Verification Requirements
- **V13.1 REST API Security**: REST Security  
- **V13.2 SOAP/Web Service Security**: Web Service Security  
- **V13.3 API Auth & Authorization**: Authentication, Access Control  

---

## V14: Configuration Verification Requirements
- **V14.1 Environment & Deployment**: Docker Security  
- **V14.2 Dependency & Patch Management**: Vulnerable Dependency Management  
- **V14.3 Security Headers**: Content Security Policy  
- **V14.4 Web Server & App Configuration**: Docker Security, Vulnerable Dependency Management

