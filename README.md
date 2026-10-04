# Secure Infrastructure Deployment & Centralized Security Monitoring Lab

This repository contains my final practical assignment from **Vilnius CODING School** (200 hours Cybersecurity course under NIS2 requirements).

## 🚀 Project Overview
Designed and deployed a secure virtual enterprise network infrastructure to simulate a real-world corporate environment for vulnerability assessment and centralized security monitoring.

## 🛠️ Infrastructure & Topology
The environment consists of 5 virtual nodes deployed via Oracle VirtualBox on Ubuntu Server:
* **Wazuh SIEM (Monitor):** Centralized security monitoring, threat detection, and log analysis.
* **OpenVAS (Scanner):** Network-wide vulnerability scanning.
* **Monitored Hosts:** 3 Ubuntu client machines with configured Wazuh agents.

## 📈 Key Achievements & Skills Demonstrated
* **Virtualization & Networking:** Configured private host-to-host networking and secure communication channels.
* **SIEM Deployment:** Implemented centralized monitoring to capture and analyze system logs.
* **Vulnerability Management:** Conducted network scanning (/24 network) to identify and document system risks.
* **System Hardening:** Performed manual SSH configurations and firewall rule management to mitigate threats.

## 📂 Project Files
* You can view the full detailed report with step-by-step screenshots in the attached **baigiamasis darbas.pdf** file above.

## 🔮 Future Improvements
* Automate SSH hardening and firewall configuration using **Ansible Playbooks** for scale (100+ servers).
* Implement automated alerting and custom remediation scripts for detected vulnerabilities.
