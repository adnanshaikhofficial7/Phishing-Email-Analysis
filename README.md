# 🔐 Phishing Email Analysis – Cyber Security Internship Task 2

## 📌 Project Overview
This project analyzes a suspected phishing email to identify malicious indicators, spoofing techniques, and social engineering tactics. The objective is to demonstrate email threat analysis and detection skills.

---

## 🎯 Objective
To identify phishing characteristics in a suspicious email sample using header analysis and content inspection.

---

## 🔍 Investigation Methodology

1. Examined sender email address for spoofing.
2. Analyzed email headers (SPF, DKIM, DMARC).
3. Inspected embedded hyperlinks.
4. Identified social engineering tactics.
5. Assessed potential impact and risk level.

---

## 🚩 Key Findings

- Spoofed sender domain (typosquatting).
- SPF authentication failure.
- DKIM signature missing.
- DMARC policy failure.
- Suspicious URL (non-official domain).
- Urgent and threatening language.
- Generic greeting ("Dear Customer").

---

## ⚠ Risk Assessment

- Threat Type: Phishing (Credential Harvesting)
- Risk Level: HIGH
- Potential Impact:
  - Account compromise
  - Financial fraud
  - Identity theft

---

## 🧩 Indicators of Compromise (IOC)

- Suspicious Domain: paypa1-security.com
- Malicious URL: http://paypal-security-check.com/login
- Originating IP: 185.xxx.xxx.xxx
- SPF/DKIM/DMARC failures

---

## 🗺 MITRE ATT&CK Mapping

Framework: MITRE ATT&CK  
- T1566 – Phishing  
- T1566.002 – Spearphishing Link  

---

## 🛡 Recommended Mitigation

- Block malicious domain and IP.
- Enable strict DMARC policy.
- Implement Multi-Factor Authentication (MFA).
- Conduct phishing awareness training.
- Deploy email security gateway.

---

## 🧠 Skills Demonstrated

- Email Header Analysis
- Phishing Detection
- Threat Documentation
- Social Engineering Identification
- Risk Assessment
- Security Reporting

---


## 👨‍💻 Author

Adnan Shaikh  
Cyber Security Enthusiast  
