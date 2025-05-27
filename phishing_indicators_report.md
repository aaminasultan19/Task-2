# Phishing Indicators Report

This document contains analysis of phishing email samples, including extracted indicators, tactics used, and visual evidence to help identify malicious behavior.

---

##  Sample: Fake Lido ETH Airdrop Email

### Email Summary

This phishing email impersonates **Lido Finance**, claiming to offer an ETH airdrop. It uses urgency, impersonation, and poor formatting to trick users into clicking a potentially malicious link.

| Detail        | Value |
|---------------|-------|
| **From**      | `Airdrop@Lido-fi-AirdropLido-fi@ofrixiet.onmicrosoft.com` |
| **To**        | `rodrigofp` |
| **Subject**   | `ETH Airdrop is now Live!` |
| **Date**      | `Tue, August 15, 2023, 12:30 PM` |

---

###  Phishing Indicators

| Indicator | Description |
|----------|-------------|
| **Suspicious Sender Address** | Uses an unofficial domain (`ofrixiet.onmicrosoft.com`) that mimics Lido's name. |
| **Urgency/Scarcity** | Phrases like “limited supply” and “first come, first served” push the user to act without verifying. |
| **Poor Grammar and Typos** | Examples include: “hasben” instead of “has been”, “cla im”, and "youfor". |
| **Lack of Personalization** | Generic greeting — no user-specific data used. |
| **Deceptive Button** | The “Join Airdrop” button has no visible link in the message. Link destination is suspicious or hidden. |
| **Brand Impersonation** | Mentions “Lido Finance” but lacks official branding or security measures (e.g., DKIM, SPF). |

---

###  Screenshot

![Fake Lido ETH Airdrop Email](screenshots/phishing_sample_outlook.png)

> Screenshot of the phishing email received in Outlook.

---

###  Recommendations

- **Do not click** any buttons or links in unsolicited emails about crypto or airdrops.
- **Verify** claims through official websites or accounts (e.g., [https://lido.fi](https://lido.fi)).
- **Report** suspicious emails to your provider as phishing.
- **Educate users** on tactics such as spoofed domains, urgency tricks, and fake airdrops.

---

