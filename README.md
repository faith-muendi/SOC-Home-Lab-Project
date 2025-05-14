# SOC Home Lab Simulation

## 🔧 Project Overview
Simulated a basic Security Operations Center (SOC) environment using virtual machines and open-source tools. Focused on threat detection, log analysis, and alert configuration for brute-force and port scan attacks.

## 🛠 Tools & Technologies
- Splunk (Free)
- ELK Stack (Elasticsearch, Logstash, Kibana)
- Security Onion
- Ubuntu VMs (VirtualBox)
- Zeek / Suricata

## 🧪 Simulated Attacks
- SSH Brute Force (Hydra, simple bash script)
- Nmap Port Scanning
- Failed Login Attempts

## 📊 What I Did
- Set up a Windows and Linux VM and forwarded logs to Splunk & ELK.
- Created detection rules for brute force and scanning behavior.
- Investigated alerts and documented the source IPs and affected machines.
- Tuned alerts to reduce false positives.

## 📝 Key Learnings
- Understanding of log parsing and analysis (Syslog, Zeek logs).
- Writing Splunk search queries (SPL) for threat hunting.
- Visualizing alerts using Kibana dashboards.

## 📸 Screenshots
(Add screenshots of your dashboards, alerts, or terminal output here)

## 📁 Folder Structure
- `/splunk_alerts/` – saved SPL queries
- `/logs/` – sample log files
- `/docs/` – investigation report & analysis

## 🚀 Future Improvements
- Add Suricata IDS to detect malware traffic.
- Simulate lateral movement and persistence.

