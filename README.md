# 🔐 Web Application Security Testing – Internship Task

This repository contains the outcome of my first internship task under **Future Interns**, where I performed **Web Application Security Testing** using **DVWA (Damn Vulnerable Web Application)** and **Wapiti**, an open-source vulnerability scanner.

---

## ✅ Task Overview

**Objective:**  
Conduct security testing on a sample web application to identify vulnerabilities such as SQL Injection, XSS, and Command Injection. For this task, I focused on **Local File Inclusion (LFI)**.

---

## 🛠️ Tools & Environment

- **DVWA** – Damn Vulnerable Web Application (PHP-based)
- **XAMPP** – Local server stack (Apache, MySQL, PHP)
- **Wapiti** – Open-source vulnerability scanner
- **Command Prompt** – For executing scan commands
- **Apache Logs** – Used to validate inclusion errors
- **Browser** – Chrome for testing LFI and command injection

---

## 🧪 Key Vulnerabilities Tested

- ✅ **Local File Inclusion (LFI)**  
  Accessed: `C:/Windows/win.ini` via DVWA  
  Confirmed by output & Apache error logs

- ✅ **Command Injection**  
  Payloads like `127.0.0.1 && whoami` executed system commands in the response

- ✅ **Wapiti Findings**  
  - Missing CSP & X-Frame-Options  
  - Insecure cookies (no Secure flag)  
  - Directory listing & unprotected forms

---

## 📁 Contents

- `reports/`: Contains both DOCX and PDF versions of the full technical report and summary
- `screenshots/`: Visual documentation of testing steps and results
- `README.md`: This file summarizing the project and findings

---

## 📌 Learnings

- Manual LFI exploitation using traversal and absolute paths
- Using Apache error logs to debug and validate
- Automated vulnerability scanning with Wapiti
- Importance of input sanitization and security headers

---

## 📎 Related Tags

`#CyberSecurity` `#DVWA` `#Wapiti` `#WebSecurityTesting` `#FutureInterns` `#OWASP` `#InternshipProject` `#LFI` `#CommandInjection`

---

Feel free to explore the reports and reach out if you have feedback or suggestions!

