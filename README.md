# Cybersecurity Case Study: Phishing Analysis & Incident Response

## 📌 Project Overview
This repository documents my identification and mitigation of a sophisticated phishing attack disguised as a remote "Help Desk Technician" job offer. This project demonstrates my ability to apply a security-first mindset to real-world scenarios, perform threat intelligence gathering, and follow formal incident response protocols.

## 🔍 The "Founder" Red Flag
While the attacker impersonated "Matthew Pincus," my OSINT (Open Source Intelligence) research on LinkedIn revealed that the real Matthew Pincus is the **Founder of Helpt**. In a professional corporate structure, it is highly improbable for a Founder to conduct initial HR outreach for junior-level positions. This discrepancy was a primary indicator of the scam.

## 🛠️ Key Indicators of Compromise (IoCs)
* **Domain Spoofing:** Use of `hrcareersgethelpt@gmail.com` instead of an official `@helpt.com` domain.
* **Financial Fraud:** A request to issue a check for workstation equipment (Advance Fee Scam).
* **Market Inconsistency:** A junior-level offer of $45/hour, which is significantly above market standard.
* **Social Engineering:** Use of "kindly" and manufactured urgency to bypass due diligence.

## 📂 Repository Contents
* `Incident-Report.md`: Full technical breakdown and response timeline.
* `/evidence/`: Annotated screenshots of the phishing email and reporting confirmations.
