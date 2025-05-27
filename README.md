# Task-2  
##  Analyze a Phishing Email Sample

###  Overview

This project is part of a cybersecurity learning exercise focused on identifying and documenting phishing indicators in a real-world email sample. The primary goal is to analyze the structure, headers, and content of a suspicious email and report red flags that indicate a phishing attempt.

---

###  Objective

Analyze a sample phishing email and identify key red flags such as:

- Spoofed sender information
- Mismatched or hidden URLs
- Suspicious attachments or links
- Failed authentication (SPF, DKIM, DMARC)
- Urgent or manipulative language

---

### 🛠 Tools Used

- Sample phishing email (.eml format)
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Basic text editor and web browser

---

###  Files Included

| File / Folder | Description |
|---------------|-------------|
| `phishing_sample.eml` | The raw phishing email file |
| `email_headers.txt` | Extracted raw email headers |
| `header_analysis_result.txt` | Output from MxToolbox or similar tool |
| `phishing_indicators_report.md` | Final written analysis of phishing indicators |
| `screenshots/` | Visuals including header details and fake email preview |


---

###  Summary of Findings

The phishing email analyzed impersonated **Lido Finance** and used a fake ETH airdrop offer to trick users. The message included:

- A spoofed sender address
- Urgency and scarcity tactics ("first come, first served")
- Poor grammar and formatting
- Generic greetings with no personalization
- A suspicious "Join Airdrop" button

Full details of the analysis can be found in [`phishing_indicators_report.md`](phishing_indicators_report.md).

---

### 📚 Learnings

This task enhanced my ability to:

- Spot and document phishing tactics
- Analyze raw email headers for forensic evidence
- Use tools like MxToolbox to verify email authentication
- Understand how attackers use social engineering in crypto-related scams
