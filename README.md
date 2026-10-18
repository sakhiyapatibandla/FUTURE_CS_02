Phishing Detection & Awareness System — FUTURE_CS_02

"Cybersecurity" (https://img.shields.io/badge/Domain-Cybersecurity-blue)
"Internship" (https://img.shields.io/badge/Program-Future%20Interns-purple)
"Task" (https://img.shields.io/badge/Task-FUTURE__CS__02-orange)

📌 Project Overview

This project was completed as part of the Future Interns Cyber Security Internship Program — Task 2 (FUTURE_CS_02).

The project focuses on analyzing phishing email scenarios, identifying suspicious email characteristics, classifying email risk, and recommending preventive security measures.

The report demonstrates a structured approach to phishing investigation and security awareness, covering techniques relevant to Security Operations Center (SOC) workflows.

🎯 Objectives

- Understand common phishing attacks and social engineering techniques.
- Identify suspicious email headers and sender information.
- Understand SPF, DKIM, and DMARC email authentication.
- Identify phishing indicators and potential Indicators of Compromise (IOCs).
- Classify email threats according to risk levels.
- Recommend appropriate security responses.
- Develop employee phishing awareness guidelines.

🛠️ Tools and Technologies

The report identifies the following tools and utilities for the investigation workflow:

- Google Admin Toolbox — Messageheader: Email header analysis.
- MXToolbox: Email authentication and header inspection.
- Browser Developer Tools: URL inspection.
- Link Safety Analyzers: Link and destination analysis.
- File Inspection and Text Decoders: Attachment and suspicious-text examination.
- Custom SOC Risk Matrix: Email risk classification.

These tools are documented as part of the investigation approach; their individual execution is not independently demonstrated by this README.

🔍 Investigation Methodology

1. Email Header Analysis

Examine email headers to identify suspicious sender information and authentication results.

Key indicators:

- Mismatched "From" and "Return-Path" addresses.
- SPF authentication or alignment failures.
- DKIM signature or alignment issues.
- DMARC authentication or alignment failures.

2. URL and Link Inspection

Review suspicious links and their destinations.

Key indicators:

- Lookalike or misspelled domains.
- Mismatched displayed links and destinations.
- Unauthorized authentication portals.
- Suspicious domain characteristics.

3. Attachment and Payload Analysis

Examine attachment characteristics and message content for potential warning signs.

Key indicators:

- Unexpected attachments.
- Double file extensions.
- Macro-enabled documents.
- Obfuscated text or scripts.

4. Risk Classification

Classify email messages according to their indicators and potential risk, then determine appropriate defensive responses.

📧 Phishing Scenarios Analyzed

Scenario 1: Credential Harvesting

Attack: An attacker impersonates an IT helpdesk and claims that a user's password is expiring.

Indicators:

- Sender and return-path mismatch.
- SPF alignment failure or DKIM signature mismatch.
- Urgent language.
- A link to an unauthorized login portal.

Prevention: Verify account-related requests through official channels and report suspicious emails.

Scenario 2: Fake Vendor Invoice

Attack: An attacker impersonates a vendor and requests an invoice update or urgent payment.

Indicators:

- Unverified vendor domain.
- Suspicious Reply-To address.
- DMARC softfail.
- Unexpected macro-enabled attachment.
- Pressure to make an urgent payment.

Prevention: Independently verify vendor details and payment instructions before taking action.

Scenario 3: Executive Impersonation

Attack: An attacker impersonates an executive and pressures employees to transfer money or purchase gift cards.

Indicators:

- Executive display-name spoofing.
- Unfamiliar external email address.
- Urgent financial requests.
- Attempts to bypass normal approval procedures.

Prevention: Verify requests through an independent communication channel and follow established approval procedures.

These are phishing scenarios documented in the report, not claims of independently collected live phishing emails.

🚩 Phishing Indicators Framework

Indicator| Description| Verification
Header Anomaly| "From" and "Return-Path" mismatch| Inspect raw email headers
Authentication Failure| SPF, DKIM, or DMARC failure| Review authentication results
Domain Typosquatting| Lookalike domain names| Inspect domain spelling and registration information
URL Manipulation| Displayed link differs from destination| Examine the destination URL safely
Suspicious Attachment| Unexpected files or misleading extensions| Review file properties
Social Engineering| Artificial urgency or financial pressure| Verify the request independently

A single indicator does not necessarily prove an email is malicious. Multiple indicators and the surrounding context should be considered.

⚖️ Email Risk Classification

Risk Level| Typical Indicators| Recommended Response
Low — Safe| Expected communication and consistent authentication results| Deliver according to normal security controls
Medium — Suspicious| Unverified sender, minor discrepancies, or suspicious links| Flag or quarantine for review
High — Malicious| Strong evidence of spoofing, unauthorized login links, or dangerous attachments| Block or quarantine, investigate, and document findings

🛡️ Prevention and Security Awareness

The SLAM Rule

- S — Sender: Verify the complete sender address.
- L — Links: Check link destinations before interacting with them.
- A — Attachments: Be cautious of unexpected attachments.
- M — Message: Recognize artificial urgency and unusual financial requests.

Recommended Security Measures

- Configure appropriate SPF, DKIM, and DMARC policies.
- Implement multi-factor authentication (MFA).
- Use email filtering and attachment security controls.
- Conduct regular employee security awareness training.
- Establish a clear phishing-reporting process.
- Independently verify sensitive financial requests.

📂 Repository Contents

This repository is intended to contain the following project deliverables:

- "README.md" — Project overview, methodology, and findings.
- "Phishing_Detection_and_Awareness_Report.pdf" — Detailed project report.
- Supporting email samples or evidence, if available.
- Analysis documents or utilities, if implemented.

Only files that have actually been uploaded or implemented should be described as completed repository contents.

📚 Key Learnings

- Understanding phishing and social engineering techniques.
- Recognizing suspicious email headers and authentication results.
- Identifying suspicious links, domains, and attachments.
- Applying risk classification to phishing scenarios.
- Recommending defensive security measures.
- Documenting findings in a structured cybersecurity report.

🔐 Ethical Considerations

This project is intended for educational purposes, defensive security analysis, and phishing awareness.

- Analyze only authorized email samples.
- Avoid opening suspicious links or attachments unnecessarily.
- Protect sensitive information.
- Use safe inspection methods.
- Follow applicable laws and security policies.

🏢 Internship Information

- Program: Future Interns Cyber Security Internship
- Task ID: FUTURE_CS_02
- Project: Phishing Detection & Awareness
- Focus Areas: Email Threat Analysis, SOC Fundamentals, Risk Classification, and Security Awareness

Task Reference: "Future Interns — Cyber Security Task 2 (2026)" (https://futureinterns.com/cyber-security-task-2-2026/)

👩‍💻 Author

Cybersecurity Student | Aspiring Security Analyst

- GitHub: "@sakhiyapatibandla" (https://github.com/sakhiyapatibandla/)
- LinkedIn: "Connect with me" (https://www.linkedin.com/in/sakhiyapatibandla/)

---

Part of my cybersecurity learning journey, focused on developing practical security analysis, threat identification, and technical reporting skills.
