Repository Contents
Document	Description
Cybersecurity_Evaluation_Report.pdf	Strategic evaluation of StarTrail Investment Bank's security posture, identifying weaknesses in server room security, cloud governance, training, and password policies with NIST-aligned recommendations.
Penetration_Testing_Preparation.pdf	Pre-engagement planning document defining grey-box testing scope, PTES methodology, Standard Operating Procedure (SOP), and attack tree for a Linux host assessment.
Penetration_Testing_Report.pdf	Black-box penetration test execution report against a live Linux target (192.168.3.56), detailing service enumeration, exploitation attempts, and mitigation strategies.
Key Findings Summary
Evaluation Report: Physical security gaps, outdated antivirus (signature-based only), missing MFA, insufficient staff training, and no social media policy.

Penetration Test (Preparation): Grey-box testing with PTES methodology; full SOP and attack tree for structured exploitation.

Penetration Test (Execution): Discovered outdated Apache/PHP, exposed phpMyAdmin (v2.10.1), directory listing on /true/, guest-enabled SMB shares, and MySQL exposure.

Tools Used
Nmap · Nikto · Gobuster · Metasploit · smbclient · curl

Standards Referenced
NIST SP 800-53 / 800-115 / 800-63B

ISO/IEC 27001

OWASP Testing Guide

PTES (Penetration Testing Execution Standard)

Status
✅ Complete – Submitted as part of academic requirements for CSS module.

Contact
Muhammad Hassan Ghaffar
