# FUTURE_CS_01
# Vulnerability Assessment Report 

## Overview :
This repository contains a read-only Vulnerability Assessment (VAPT) of a public test web application. 
* Identify common security weaknesses
* Classify risks as *High / Medium / Low*
* Conduct analysis ethically and non-intrusively

## 🌐 Target Website :
- Website Tested:

- Nmap &Devtool Scan ->http://testphp.vulnweb.com/
- ZAP Scan -> http://testhtml5.vulnweb.com/
- Assessment Type : Passive Security Assessment


## 🎯 Scope :
This assessment followed read-only and ethical testing only:
- No login pages tested  
- No brute force  
- No exploitation  
- No DoS  
- Only passive scanning and configuration analysis  

## 📂 Evidence Included :
- Nmap scan screenshots  
- OWASP ZAP screenshots  
- DevTools screenshots  

 ## 📝 Summary of Findings :  

| Tool Used | Issue Found | Risk Level |
|-----------|-------------|------------|
| Nmap | Open ports & server info exposed | Medium |
| OWASP ZAP | Missing security headers & insecure cookies | Medium |
| Browser DevTools | No CSP, weak cookie settings | Medium |

### 📄 Full Vulnerability Assessment Report (PDF) :
👉 https://drive.google.com/file/d/1RWadonBnhkItXGLktgTr_udHJzFE7imF/view

## ---------------------------⚠ Disclaimer--------------------------
This is a point-in-time assessment. New vulnerabilities may appear due to changes or updates. Periodic reassessment is recommended.
---------------------------------------------------------------------------------------------------


