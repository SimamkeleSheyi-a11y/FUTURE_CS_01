# FUTURE_CS_01

- Vulnerability Assessment Report

This repository contains a vulnerability assessment conducted using Nmap on a live test system as part of a Cyber Security internship.

**CIN:** FIT/APR26/CS7842  
**Task:** 1 of 3 (Minimum for Certificate Requirements)  
**Date: 22 April 2026  

---

## Target
scanme.nmap.org (45.33.32.156)

---

## Summary
A vulnerability assessment was conducted on scanme.nmap.org using Nmap. The scan identified six open ports, including two medium-risk vulnerabilities related to outdated SSH and Apache services, and four low-risk findings. No high-risk or critical vulnerabilities were identified during the assessment.

---

## Findings Overview

| Port | Service | Risk Level |
|------|---------|------------|
| 22 | OpenSSH 6.6.1p1 | Medium |
| 80 | Apache 2.4.7 | Medium |
| 2000 | tcpwrapped | Low |
| 5060 | tcpwrapped | Low |
| 9929 | nping-echo | Low |
| 31337 | tcpwrapped | Low |

---

## Report
[Download PDF](./Vulnerability_Assessment_Report_Simamkele_Sheyi.pdf)

---

## Tools Used

**Website tested:** scanme.nmap.org
**Scope:** Read-only, public-facing pages only. No exploitation or brute force.
**Tools used:** Nmap 7.99, Command Prompt, Canva
---

## Screenshot

![Nmap Scan](./screenshots/nmap_scan.png)

---

## Next Steps
- [ ] Task 2: Phishing Email Detection & Awareness System  
- [ ] Task 3: API Security Risk Analysis  

---

## Internship Info
- **Organization:** Future Interns  
- **Track:** Cyber Security (CS)  
- **Certificate eligibility:**  (2 tasks completed)  
- **LoR eligibility:**  (3 tasks required)
