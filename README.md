 Task 3 - Vulnerability Scan on Local Machine

🔍 Objective
As part of Cyber Security Internship Task 3, I performed a basic vulnerability scan on my local machine using OpenVAS Community Edition.
 🛠 Tools Used
- OpenVAS Community Edition

 🖥️ Target
- Localhost (127.0.0.1)
## 📋 Steps I Followed
1. OpenVAS ko install kiya.
2. Target IP set kiya: 127.0.0.1 (Localhost).
3. Full vulnerability scan run kiya.
4. Scan complete hone me approx 45 mins lage.
5. Report export ki and screenshots le liye.
6. Most critical vulnerabilities ko study kiya aur unke fixes bhi note kiye.

📄 Deliverables
- `Vulnerability_Scan_Report.pdf` – contains scan result
- `/screenshots/` folder – contains images of scan steps and result

 🛡️ Top Vulnerabilities Found
| CVE ID        | Description                             | Severity  |
|---------------|-----------------------------------------|-----------|
| CVE-2022-1388 | F5 BIG-IP iControl REST Vulnerability   | Critical  |
| CVE-2021-44228| Apache Log4j Remote Code Execution      | High      |
| CVE-2017-0144 | EternalBlue SMBv1 Vulnerability         | High      |
| CVE-2020-0601 | Windows CryptoAPI Spoofing              | Medium    |
| CVE-2019-0708 | BlueKeep RDP Vulnerability              | Critical  |

 ❓ Interview Questions & Answers

 1. What is vulnerability scanning?
It is an automated process to identify security weaknesses in systems and software.

 2. Difference between vulnerability scanning and penetration testing?
Vulnerability scanning finds possible issues automatically. Penetration testing is manual and actually tries to exploit the weaknesses.

 3. Common vulnerabilities in personal computers?
- Outdated OS or software
- Weak passwords
- Open/Unused ports
- No firewall or antivirus

 4. How do scanners detect vulnerabilities?
They compare your system's software and settings with a known database of issues (CVE).

 5. What is CVSS?
Common Vulnerability Scoring System — It gives a severity score (0–10) to each vulnerability.

6. How often should scans be done?
Monthly or after any major software updates or changes.

 7. What is a false positive?
When a scan reports an issue that actually doesn't exist.

8. How to prioritize vulnerabilities?
Based on severity score (CVSS), system criticality, and exposure level.



 ✅ Outcome
Task complete with hands-on understanding of vulnerability scanners and real-world risks to personal computers.
