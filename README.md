# 🔍 Phishing Detection & Awareness Report
### Future Interns — Cyber Security Task 2 (2026)

---

## 📌 Overview

This repository contains a professional **Phishing Email Detection & Awareness Report** produced as part of the Future Interns Cyber Security Task 2 program.

The report analyses real-world phishing email patterns, identifies common attack techniques, classifies emails by risk level, and provides clear prevention guidelines for employees and organisations.

> This project covers **security education and analysis only** — no offensive or illegal activity is involved.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `phishing-awareness-report.pdf` | Full phishing detection & awareness report |
| `samples/sample1-account-verification.txt` | Phishing email sample 1 — credential harvesting |
| `samples/sample2-it-password-reset.txt` | Phishing email sample 2 — IT impersonation |
| `samples/sample3-invoice-bec.txt` | Phishing email sample 3 — BEC / finance fraud |
| `README.md` | This file |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/) | Email header analysis — SPF, DKIM, DMARC inspection |
| [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx) | Secondary header analyser and domain reputation |
| [VirusTotal](https://www.virustotal.com) | URL and attachment scanning |
| [WHOIS Lookup](https://whois.domaintools.com) | Domain registration and age verification |
| [PhishTank](https://www.phishtank.org) | URL reputation against phishing database |
| Google Docs / HTML | Report documentation and formatting |

---

## 🔎 Analysis Approach

Each email sample was examined using a structured 5-step methodology:

1. **Header Inspection** — Verified SPF/DKIM/DMARC status, identified true sending server, and checked for Reply-To mismatches
2. **Domain Verification** — Cross-referenced sender domain against WHOIS records and known legitimate domains
3. **Link Analysis** — Hover-inspected all URLs and submitted to VirusTotal and PhishTank without clicking
4. **Content Analysis** — Identified psychological manipulation tactics such as urgency, fear, and authority impersonation
5. **Risk Classification** — Scored indicators and assigned each email a risk level: Safe / Suspicious / Phishing

---

## 📊 Samples Analysed

| # | Sample | Attack Type | Risk Level |
|---|--------|-------------|------------|
| 1 | Account Verification Email | Credential harvesting via fake login page | ✖ Phishing |
| 2 | IT Password Reset | Display name spoofing + Reply-To harvesting | ✖ Phishing |
| 3 | Invoice / Finance Request | Business Email Compromise (BEC) | ⚠ Suspicious |

---

## 📚 Reference Repositories (Study Only)

The following public repositories were used for learning and reference:

- [rf-peixoto/phishing_pot](https://github.com/rf-peixoto/phishing_pot) — Real phishing email samples
- [autinerd/phishing-mail-examples](https://github.com/autinerd/phishing-mail-examples) — Header and body text examples
- [sadat1971/Phishing_Email](https://github.com/sadat1971/Phishing_Email) — Labelled phishing dataset

> ⚠️ These were used for study purposes only. No content was copied or reused.

---

## 👤 Author :Lizo Ndawana

**Future Interns — Cyber Security Task 2**  
April 2026
