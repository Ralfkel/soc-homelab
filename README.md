# SOC Homelab – Security Operations Practice Environment

This repository documents hands-on cybersecurity investigations performed in a controlled Ubuntu homelab environment.

The objective is to simulate real-world SOC (Security Operations Center) workflows including log analysis, brute-force detection, and anomaly investigation using Linux-based systems.

---

## Lab 1 – Apache HTTP Log Investigation

**Environment**
- Ubuntu Linux
- Apache2
- /var/log/apache2/access.log

**Investigation Focus**
- Verified Apache service health
- Reviewed raw HTTP access logs
- Identified top source IPs by request frequency
- Filtered login-related activity
- Detected suspicious repeated requests

**Skills Demonstrated**
- Log analysis
- Threat pattern detection
- IP frequency correlation
- Command-line investigation (grep, awk, sort, uniq)

---

## Lab 2 – SSH Brute Force Detection

**Environment**
- Ubuntu Linux
- OpenSSH
- /var/log/auth.log

**Investigation Focus**
- Generated failed SSH login attempts
- Parsed authentication logs
- Counted repeated failures by IP
- Identified brute-force behavior patterns
- Documented findings

**Skills Demonstrated**
- Authentication log analysis
- Brute-force detection
- Incident investigation workflow
- Linux security fundamentals

---

## Purpose

This project demonstrates foundational SOC Analyst skills including manual log review, anomaly identification, and structured investigation documentation prior to using SIEM platforms.
