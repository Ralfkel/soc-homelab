# SOC Threat Detection Home Lab

## Objective
This repository demonstrates hands-on experience analyzing server logs and Windows security events to detect brute-force activity and authentication anomalies.

---

## Lab 1 – Apache Log Analysis

**Tools Used:** Linux (Ubuntu), Apache logs  

- Analyzed 5,000+ log entries  
- Identified repeated failed login attempts  
- Correlated suspicious IP behavior  
- Simulated incident response workflow  

---

## Lab 2 – Apache Log Analysis (HTTP Access Logs)

**Tools Used:** Linux (Ubuntu), Apache2, access.log, awk, grep, sort, uniq

- Verified Apache service status using systemctl  
- Reviewed /var/log/apache2/access.log  
- Identified top source IPs by request frequency  
- Filtered suspicious login-related requests (e.g., /login)  
- Counted repeated IP attempts to detect abnormal behavior  

[View Full Investigation →](./apache-log-analysis)
---

## Skills Demonstrated

- Linux log analysis (auth.log, access.log)
- Brute-force attack detection
- Suspicious IP correlation
- Command-line investigation (grep, awk, sort, uniq)
- Incident response fundamentals (containment & monitoring)
