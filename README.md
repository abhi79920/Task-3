# ✅ Cyber Security Internship – Task 3: Vulnerability Scan

## 🔍 Objective:
Use Nessus Essentials to perform a basic vulnerability scan on your own system.

## 🧰 Tool Used:
- Nessus Essentials (Free)
- Scan Type: Basic Network Scan
- Target: 127.0.0.1 (localhost)

## 📋 Findings Summary:
- **Medium:** SMB Signing not required (CVSS: 5.3)
- **Mixed/Info:** SSL, SMB, HTTP, TLS, Portscanner, OS Info

## 🔧 Fix Recommendations:
1. **Enable SMB signing** via Windows Group Policy
2. **Update SSL/TLS** protocols and disable weak ciphers
3. **Secure HTTP headers** and close unused ports

## 📸 Screenshots:
See `screenshots/` folder for real scan output.

## 📁 Files Included:
- `report/nessus_scan_report.pdf` – Written summary of findings
- `screenshots/` – Real scan screenshots
- `interview_questions.txt` – Internship interview Q&A
- `README.md` – GitHub project summary

## 🔗 Submission:
Upload this folder to GitHub and submit the repository link.
