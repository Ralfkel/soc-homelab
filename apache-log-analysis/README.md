# Apache Log Analysis Investigation

## Scenario
Suspicious HTTP activity was observed on an Apache web server.  
The objective was to analyze access logs to identify abnormal request patterns and potential brute-force or enumeration behavior.

---

## Tools Used
- Ubuntu Linux
- Apache2
- /var/log/apache2/access.log
- systemctl
- grep
- awk
- sort
- uniq

---

## Investigation Steps
- Verified Apache service status using `systemctl status apache2`
- Reviewed access logs located at `/var/log/apache2/access.log`
- Identified top source IP addresses by request frequency
- Filtered login-related requests (e.g., `/login`)
- Counted repeated requests from the same IP

---

## Findings
- Repeated requests from specific IP addresses were identified
- High-frequency requests indicated abnormal behavior
- Login-related endpoints showed suspicious repetition patterns

---

## Evidence
### Evidence 1 – Apache Service Status

![Apache Service Status](evidence1.png)

### Evidence 2 – Top Source IP Requests

![Top Source IP Requests](evidence2.png)

### Evidence 3 – Suspicious Login Filtering

![Suspicious Login Filtering](evidence3.png)

