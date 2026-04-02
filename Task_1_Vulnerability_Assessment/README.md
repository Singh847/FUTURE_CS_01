# 🔐 Vulnerability Assessment Report — DVWA (Localhost)

### Cyber Security Task 1 (2026) — Future Interns

![Security](https://img.shields.io/badge/Security-Vulnerability%20Assessment-blue?style=flat-square)
![OWASP](https://img.shields.io/badge/Framework-OWASP%20Top%2010%20\(2021\)-red?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-green?style=flat-square)
![Scope](https://img.shields.io/badge/Scope-Passive%20%7C%20Local%20Testing-orange?style=flat-square)

---

## 👤 Author

**Sumeer Singh Rana**
Cyber Security Task 1 (2026) — Future Interns Mentorship Program

---

## 📋 Overview

This repository contains a **Vulnerability Assessment Report** performed on a local instance of **Damn Vulnerable Web Application (DVWA)** hosted on:

```
http://127.0.0.1:42001
```

The assessment was conducted in a controlled lab environment using Kali Linux. The objective was to identify security misconfigurations, weak headers, exposed services, and common vulnerabilities aligned with **OWASP Top 10 (2021)**.

---

## 📁 Repository Structure

```
FUTURE_CS_01/
│
├── 📄 README.md
│
└── 📁 Task_1_Vulnerability_Assessment/
    ├──zap_scan.png
    ├── Curl.png
    ├── dvwa_login.png
    ├── dvwa_vulnerability.png
    ├── Nikto.png
    ├── Nmap.png
    ├── security_header.png
    ├── Whatweb.png
    ├── alert_report.jpeg
    ├── vulnerability.png
    └── Vulnerability_Assessment_Report_Task1.pdf
```

---

## 🌐 Target Environment

| Field           | Details                                |
| --------------- | -------------------------------------- |
| **Target**      | DVWA (Damn Vulnerable Web Application) |
| **URL**         | http://127.0.0.1:42001                 |
| **Environment** | Localhost (Kali Linux + VirtualBox)    |
| **Type**        | Intentionally vulnerable web app       |
| **Scope**       | Local testing only                     |

---

## 🛠️ Tools Used

| Tool                    | Purpose                                |
| ----------------------- | -------------------------------------- |
| **Nmap**                | Port scanning & service detection      |
| **Nikto**               | Web server vulnerability scanning      |
| **OWASP ZAP**           | Passive scan & vulnerability detection |
| **WhatWeb**             | Technology fingerprinting              |
| **curl**                | Header inspection                      |
| **Browser DevTools**    | Cookie & session analysis              |
| **SecurityHeaders.com** | Security header grading                |

---

## 🔍 Assessment Methodology

1. Reconnaissance (Nmap)
2. Web Server Scanning (Nikto)
3. Technology Detection (WhatWeb)
4. Header Analysis (curl + DevTools)
5. Passive Scan (OWASP ZAP)
6. Cookie & Session Analysis
7. Vulnerability Identification
8. Report Generation

---

## 📊 Key Findings

| Issue                           | Severity  |
| ------------------------------- | --------- |
| Missing Content-Security-Policy | 🔴 High   |
| Missing X-Frame-Options         | 🔴 High   |
| Missing Security Headers        | 🔴 High   |
| Cookie without SameSite         | 🟠 Medium |
| Server Information Disclosure   | 🟠 Medium |
| Weak Configuration              | 🟡 Low    |

---

## ⚠️ Ethical Notice

This project was conducted:

* ✅ On a local lab (DVWA)
* ✅ No real system targeted
* ✅ No illegal activity performed
* ✅ Educational purpose only

---

## 📄 Report

Full report available here:

👉 **Vulnerability_Assessment_Report_Task1.pdf**

---

## 📸 Evidence

Includes:

* Nmap scan results
* Nikto findings
* OWASP ZAP alerts
* Security headers analysis
* Cookie inspection
* DVWA vulnerabilities

---

## 📚 References

* https://owasp.org/www-project-top-ten/
* https://github.com/digininja/DVWA
* https://securityheaders.com
* https://nmap.org
* https://owasp.org/www-project-zap/

---

## 🎯 Conclusion

This assessment demonstrates practical skills in:

* Web security testing
* Vulnerability identification
* Security misconfiguration analysis
* Tool-based penetration testing

The project highlights common real-world vulnerabilities and their detection using industry-standard tools.

---

**📅 Date:** April 2026
**🔒 Classification:** Educational / Lab Environment
