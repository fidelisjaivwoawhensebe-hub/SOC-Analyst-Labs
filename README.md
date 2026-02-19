# SOC Analyst Labs 🔐

This repository documents my hands-on cybersecurity lab exercises focused on SIEM monitoring, threat detection, and log analysis.

---

## 🧪 Lab 1: Brute Force Attack Detection

### 🎯 Objective
Detect repeated failed login attempts indicating a brute-force attack.

### 🛠 Tools Used
- Splunk
- Authentication Logs
- Linux Log Files

### 🔎 Investigation Steps
1. Filtered failed login events.
2. Grouped results by source IP address.
3. Identified abnormal login failure frequency.
4. Analyzed timestamps for attack patterns.

### 🚨 Findings
Multiple failed login attempts were detected from a single IP address within a short time frame, indicating potential brute-force activity.

### 🛡 Response Recommendation
- Temporarily block suspicious IP
- Enforce account lockout policy
- Enable multi-factor authentication (MFA)

---

More labs will be added as I continue building real-world cybersecurity skills.
---

## 🧪 Lab 2: Phishing Email Analysis

### 🎯 Objective
Analyze suspicious email indicators to determine phishing attempt.

### 🛠 Tools Used
- Email header analysis
- VirusTotal (for link checking)
- Basic OSINT techniques

### 🔎 Investigation Steps
1. Examined sender email address.
2. Analyzed email headers for spoofing.
3. Checked embedded links using reputation tools.
4. Reviewed language and urgency indicators.

### 🚨 Findings
Email contained spoofed domain and malicious link designed to capture user credentials.

### 🛡 Response Recommendation
- Block sender domain
- Report to security team
- Educate users on phishing awareness
