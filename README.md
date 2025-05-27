# Task-2
Analyze a Phishing Email Sample
#  Phishing Email Analysis

This project is a part of a cybersecurity learning exercise, where the objective is to analyze a suspicious phishing email and identify key indicators of phishing attacks.

## Objective
Analyze a sample phishing email and identify red flags such as:
- Spoofed sender information
- Mismatched URLs
- Suspicious attachments
- Failed email authentication (SPF, DKIM, DMARC)
- Urgent or threatening language

## Tools Used
- Sample phishing email (text or .eml format)
- [MxToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Basic text editor and web browser

##  Files Included
| File | Description |
|------|-------------|
| `phishing_sample.eml` | The raw phishing email file |
| `email_headers.txt` | Copied raw email headers |
| `header_analysis_result.txt` | Results from MxToolbox  |
| `phishing_indicators_report.md` | Report identifying phishing signs |
| `screenshots/` | (Optional) Screenshots of header analysis or phishing links |

##  Summary of Findings
- Fake sender domain (`secure-m1crosoft.com`)
- SPF, DKIM, and DMARC failed
- Suspicious link: `https://m1crosoft-verification-support.com/verify-now`
- Urgent message threatening account lock
- Poor spelling and grammar
- Malicious HTML attachment attempting credential theft

##  Learnings
This exercise improved my skills in spotting phishing techniques by dissecting real-world malicious emails. It also taught me how to use email header analysis tools effectively.



