# 🛡️ Cyber Security Project  
## Bug Hunt 101 — Recon to Report

**Author:** Sahil Sahu  
**Domain:** Cyber Security / Bug Bounty  
**Project Type:** Hands-on Security Testing  
**Target Application:** OWASP Juice Shop / DVWA (Lab Environment)

---

## 📌 Project Overview

This project demonstrates the **end-to-end bug bounty workflow**, starting from reconnaissance to vulnerability identification and professional reporting.  
All testing was conducted in a **controlled lab environment** using intentionally vulnerable applications.

---

## 🎯 Objectives

- Understand real-world **bug bounty methodology**
- Perform **reconnaissance and enumeration**
- Identify common **web application vulnerabilities**
- Document findings using **industry-standard reports**

---

## ⚖️ Scope & Ethics

- **In Scope:** Local deployment of OWASP Juice Shop / DVWA
- **Out of Scope:** Any real-world or production systems
- **Ethical Note:** All testing was performed with authorization in a safe lab environment.

---

## 🧰 Tools Used

| Category | Tools |
|--------|------|
| OS | Kali Linux |
| Reconnaissance | Nmap, Amass, Sublist3r |
| Interception | Burp Suite |
| Vulnerability Testing | OWASP ZAP, SQLMap |
| Documentation | Markdown, Screenshots |

---

## 🧪 Methodology

### 🔍 Phase 1: Reconnaissance

- Identified open ports and services
- Enumerated application endpoints
- Analyzed response behavior

**Command Used:**
```bash
nmap -sV -O -sT <target-ip>
