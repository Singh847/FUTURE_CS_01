# 🔐 API Security Risk Analysis

### Cyber Security Task 3 (2026) — Future Interns

![Security](https://img.shields.io/badge/Security-API%20Audit-red?style=flat-square)
![OWASP](https://img.shields.io/badge/Framework-OWASP%20API%20Top%2010-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-green?style=flat-square)

---

## 👤 Author

**Sumeer Singh Rana**

---

## 📋 Overview

This task demonstrates API security testing using public demo APIs.

APIs tested:

* JSONPlaceholder
* ReqRes.in

The analysis follows **OWASP API Top 10 (2023)** and focuses on identifying authentication issues, data exposure, and misconfigurations.

---

## 📁 Files Included

* 📄 API_Security_Risk_Analysis_Report.pdf
* 📸 API testing screenshots

---

## 📸 Evidence

### 🔴 Unauthenticated Access (GET /users)

![Users](01_GET_users.png)

### 🟠 IDOR Test (GET /users/{id})

![IDOR](02_GET_users_id.png)

### 🟠 Weak Token Authentication

![Token](03_POST_login_token.png)

### 🟡 Verbose Error Message

![Error](04_POST_login_error.png)

### 🔴 No Authentication (GET /posts)

![Posts](05_GET_posts.png)

### 🔴 Missing Rate Limiting

![RateLimit](06_rate_limit.png)

---

## 🔍 Key Risks Identified

* Unauthenticated API access
* Excessive data exposure
* Missing rate limiting
* IDOR (Insecure Direct Object Reference)
* Weak authentication tokens
* Verbose error messages
* Missing security headers

---

## 📊 Summary

* Total Risks: 9
* High: 3
* Medium: 4
* Low: 2

---

## 🛡️ Recommendations

* Implement authentication (JWT / OAuth)
* Apply rate limiting
* Restrict data exposure
* Validate input data
* Use secure headers
* Avoid verbose error messages

---

## 📄 Full Report

👉 See detailed report:
**API_Security_Risk_Analysis_Report.pdf**

---

## 🎯 Conclusion

API security is critical in modern applications.
This task demonstrates real-world API vulnerabilities and how they can impact security if not properly handled.

---

