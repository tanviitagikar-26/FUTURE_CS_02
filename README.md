# FUTURE_CS_02
# Task 2: Phishing Email Detection & Awareness System
**Track:** Cyber Security (CS)  
**Target Samples:** Legitimate Marketing vs. Spoofed Bank Emails  

## Description
This project involves a technical deep-dive into email headers to identify phishing attempts. I performed a comparative analysis between a real marketing email and a spoofed phishing email by checking digital signatures like **SPF, DKIM, and DMARC** to detect domain impersonation and credential harvesting risks.

## Tools Used
- **Google Admin Toolbox (Messageheader):** For technical header analysis.
- **Raw Email Headers:** To identify Return-Path and Sender IP mismatch.
- **Browser Tools:** For inspecting destination URLs and link safety.

## Investigation Results
- **Sample 1 (HyugaLife):** Identified as **Legitimate but Clickbait**. Technical authentication (SPF/DKIM/DMARC) passed.
- **Sample 2 (Trusted Bank):** Identified as **Phishing (Critical Risk)**. Failed all authentication protocols (SPF/DMARC Fail).

