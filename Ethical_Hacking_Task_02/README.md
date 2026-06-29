# Ethical Hacking Task 02 - Network Scanning & Service Enumeration

## Objective

The objective of this task is to understand the scanning and enumeration phase of ethical hacking by identifying active hosts, open ports, running services, and operating system information using Nmap.

## Target Information

* **Target System:** Localhost (127.0.0.1)
* **Operating System:** Kali Linux
* **Assessment Type:** Local Network Scan

## Activities Performed

* Nmap Installation Verification
* Localhost Port Scanning
* Service Version Detection
* Operating System Detection
* Common Port Research
* Scan Analysis

## Tools Used

* Nmap 7.98

## Commands Used

```bash
nmap --version
nmap localhost
nmap -sV localhost
sudo nmap -O localhost
```

## Files Included

* Nmap Scan Report (PDF/DOCX)
* Screenshots
* Research Notes

## Key Findings

* The localhost system was reachable and responsive.
* No open TCP ports were detected during the scan.
* No active network services were identified.
* Operating system fingerprinting was performed successfully.

## Recommendations

* Continue disabling unnecessary services.
* Keep the operating system updated.
* Regularly monitor exposed services using network scanning tools.
* Follow secure configuration practices.

## Learning Outcomes

This task provided hands-on experience with Nmap and demonstrated the importance of network scanning and service enumeration during the initial stages of penetration testing.

## Author

**Modi Manan Kirankumar**
