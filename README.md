# IT-Support-Incident-Troubleshooting-Lab

## Project Overview
This project simulates real-world IT support incidents and demonstrates troubleshooting techniques used to resolve common technical issues in a business environment.

---

## Incident Scenario
A user reported the following issues:
- Unable to connect to network services
- Printer not responding / printing jobs failing

---

## Tools & Technologies
- Windows OS
- Command Prompt (CMD)
- Network diagnostic tools
- Print Spooler Service

---

## Troubleshooting Process

### 1. Network Diagnosis
- Ran `ipconfig` to check IP configuration
- Used `ping` to test connectivity
- Used `nslookup` to verify DNS resolution
- Used `netstat` to analyze active connections

### 2. Printer Issue Diagnosis
- Identified that printer jobs were not processing
- Investigated print queue behavior
- Discovered issue with Print Spooler service

---

## Resolution Steps

### Network Issue
- Restored connectivity by verifying network adapter status and connection

### Printer Issue
- Restarted Print Spooler service using:
- net stop spooler
- net start spooler
Confirmed successfully printing after service restart 

---

## Skills Demonstrated
- Network troubleshooting
- COmmand-line diagnostics
- Windows system administration
- Problem-solving under presure
- Incident documentation

---

## Real-World Relevance 
This project reflects tasks performed by IT Support Specialists and Helpdesk Technicians in diagnosing and resolving user issues efficiently.

---

## Author
Nthabiseng Mkhehlani
