# FUTURE_CS_02
# Web Application Security Testing – OWASP ZAP

<html><head> project <itle> web </itle> </head> <body> <b>📌 Project Overview <html><head> project <itle> web </itle> </head> <body> <b>
This project demonstrates basic <html><head> project <itle> web </itle> </head> <body> <b>web application security testing </b> </body> </html> performed on a deliberately vulnerable web application using **OWASP ZAP**.  
The goal was to identify common security issues and understand their impact and mitigation.

## 🎯 Target Application
- **Name:** OWASP Juice Shop  
- **Type:** Intentionally vulnerable web application  
- **Purpose:** Security learning and practice

## 🛠 Tools Used
- OWASP ZAP (Automated Scan)

## 🔍 Testing Method
- Automated security scan using OWASP ZAP
- Analysis of identified alerts
- Focus on medium and low-risk vulnerabilities

## 🚨 Vulnerabilities Identified
- Content Security Policy (CSP) Header Not Set
- Strict-Transport-Security (HSTS) Header Not Set
- Information Disclosure – Suspicious Comments

## 🛡 Mitigation Summary
- Implement proper security headers (CSP, HSTS)
- Remove sensitive or unnecessary comments from production code
- Follow secure coding best practices

## ⚠ Disclaimer
This testing was performed **only on an intentionally vulnerable application** for educational purposes.  
No real-world systems were harmed or targeted.
