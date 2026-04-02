# 🎣 Phishing Email Detection & Awareness Report
### Cyber Security Task 2 (2026) — Future Interns

![Security](https://img.shields.io/badge/Security-Phishing%20Analysis-purple?style=flat-square)
![OWASP](https://img.shields.io/badge/Type-Email%20Forensics-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-green?style=flat-square)
![Ethics](https://img.shields.io/badge/Scope-Educational%20%7C%20Ethical-orange?style=flat-square)

---

## 👤 Author
**Sumeer Singh Rana**  
Cyber Security Task 2 (2026) — Future Interns Mentorship Program

---

## 📋 Overview

This repository contains a professional **Phishing Email Detection & Awareness Report** analysing 5 real-world phishing email samples. The report is structured as a corporate-ready security awareness document, suitable for employee training and SOC analyst portfolios.

All email samples are from public/educational sources. No real systems were attacked.

---

## 📁 Repository Structure

```
phishing-detection-awareness/
│
├── 📄 Phishing_Detection_Awareness_Report.pdf  ← Full report (submit this)
│
├── 📸 screenshots/
│   ├── 01_EMAIL_AccountLocked_Phishing.png     ← Fake account lock phishing
│   ├── 02_EMAIL_PayPal_Phishing.png            ← PayPal brand impersonation
│   ├── 03_EMAIL_IT_PasswordReset_Phishing.png  ← IT department spear phishing
│   ├── 04_EMAIL_OneDrive_Phishing.png          ← Microsoft OneDrive credential theft
│   └── 05_EMAIL_PrizeScam_Suspicious.png       ← Prize scam / data harvesting
│
└── 📖 README.md                                ← This file
```

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Google Admin Toolbox — Message Header Analyzer** | Parse email headers, verify SPF/DKIM/DMARC |
| **MXToolbox Email Header Analyzer** | Sender domain reputation and mail server checks |
| **Browser DevTools** | Safely inspect links without clicking |
| **Public Phishing Repositories (GitHub)** | Source real phishing email samples for analysis |
| **Manual Pattern Analysis** | Social engineering and indicator identification |

---

## 🔍 Analysis Approach

The assessment followed a 7-step methodology:

1. **Sample Collection** — Gathered 5 phishing email samples from public repositories
2. **Header Analysis** — Verified SPF, DKIM, DMARC authentication results
3. **Sender Domain Inspection** — Checked for spoofing, typosquatting, fake domains
4. **Link Inspection** — Safely analysed embedded URLs without clicking
5. **Phishing Indicator Identification** — Mapped social engineering patterns
6. **Risk Classification** — Classified each email: Safe / Suspicious / Phishing
7. **Awareness Documentation** — Wrote prevention guidelines for employees

---

## 📊 Analysis Results

| Email ID | Subject | Classification | Indicators |
|----------|---------|----------------|------------|
| EMAIL-01 | Urgent: Your Account Will Be Locked | 🔴 PHISHING | 6 |
| EMAIL-02 | PayPal Account Has Been Limited | 🔴 PHISHING | 6 |
| EMAIL-03 | IT Dept: Mandatory Password Reset | 🔴 PHISHING | 6 |
| EMAIL-04 | Shared Document — Microsoft OneDrive | 🔴 PHISHING | 6 |
| EMAIL-05 | You've Been Selected for a Prize | 🟠 SUSPICIOUS | 5 |

**Total: 5 emails — 4 Phishing | 1 Suspicious | 29 indicators identified**

---

## ⚠️ Common Phishing Indicators Found

- 🔴 Fake / lookalike sender domains (typosquatting)
- 🔴 SPF / DKIM / DMARC authentication failures
- 🔴 Reply-To address mismatch
- 🔴 Urgency and fear-based language ("24 hours", "account locked")
- 🔴 Suspicious embedded links pointing to unrelated domains
- 🔴 Brand impersonation (Microsoft, PayPal)
- 🟠 Generic greetings ("Dear User", "Dear Customer")
- 🟠 Too-good-to-be-true offers (prize scams)

---

## 📚 References

- [Phishing Email Examples Repository](https://github.com/rf-peixoto/phishing_pot)
- [Phishing Mail Examples for Education](https://github.com/autinerd/phishing-mail-examples)
- [OWASP Phishing Resources](https://owasp.org)
- [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/)
- [MXToolbox Email Headers](https://mxtoolbox.com/EmailHeaders.aspx)

---

## 💼 About This Task

This task is part of the **Future Interns Cyber Security Mentorship Program (2026)**.  
Phishing detection and awareness is a critical skill for:
- SOC Analysts
- Security Analysts
- GRC & Security Awareness roles

---

*Report Date: 27 March 2026 | Classification: Educational / Security Awareness*
