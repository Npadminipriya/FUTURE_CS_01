# FUTURE_CS_01
Internship Task – Web Security Testing
# Web Application Vulnerability Assessment Report – 2026

## 📌 Project Overview

This repository contains a **read-only Web Application Vulnerability Assessment** conducted as part of the **Future Interns – Cyber Security Task 1 (2026)** program.

The objective of this assessment was to identify publicly observable security misconfigurations and classify associated risks without performing exploitation or intrusive testing.

---

## 🎯 Target Application

http://testphp.vulnweb.com

> This website is an intentionally vulnerable test environment designed for educational and security testing purposes.

---

## 🔎 Assessment Scope

### ✅ In Scope
- Public-facing web pages
- Passive reconnaissance
- HTTP response header inspection
- Service version detection

### ❌ Out of Scope
- Exploitation of vulnerabilities
- Brute force attacks
- SQL injection or XSS exploitation
- Denial-of-Service (DoS)
- Credential attacks

This assessment strictly followed ethical guidelines and did not attempt to harm or disrupt the target system.

---

## 🛠 Tools Used

- Nmap 7.95 (`-sV -Pn`)
- Kali Linux
- Browser Developer Tools
- SecurityHeaders.com

Only passive and non-intrusive techniques were used.

---

## 📊 Summary of Findings

| ID | Vulnerability | Severity |
|----|-------------------------------|----------|
| 01 | Website served over HTTP | High |
| 02 | Outdated PHP Version (5.6) | High |
| 03 | Missing Content Security Policy | Medium |
| 04 | Missing X-Frame-Options | Medium |
| 05 | Missing X-Content-Type-Options | Low-Medium |
| 06 | Server Version Disclosure | Low |

---

## 📁 Repository Structure
