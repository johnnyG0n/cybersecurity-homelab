# Cybersecurity Home Lab

This is my cybersecurity home lab project! This lab is designed to simulated a real-world enterprise environment using virtual machines, allowing me to explore topics like Active Directory, SIEM, threat detection, and attack simulation.

---

### ⚙️ Lab Overview

**Main Goals:**
- Set up an Active Directory domain
- Forward logs to a SIEM (Wazuh + ELK Stack)
- Simulate attacks using Kali Linux and detect them
- Practice vulnerability scanning and response

**Virtual Machines:**
| VM Name    | OS              | Role                        |
|-----------|------------------|-----------------------------|
| DC01       | Windows Server   | Domain Controller + DNS     |
| WIN10CL01  | Windows 10       | Domain-joined client        |
| KALI       | Kali Linux       | Attacker machine            |
| SIEM01     | Ubuntu Linux     | Wazuh server + ELK stack    |

---

## 🛠️ Tools Used

- [VirtualBox](https://www.virtualbox.org/)
- [Kali Linux](https://www.kali.org/)
- [Wazuh SIEM](https://wazuh.com/)
- [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)
- [BloodHound](https://github.com/BloodHoundAD/BloodHound)
- [Splunk Forwarder](https://www.splunk.com/en_us/download/universal-forwarder.html)

---

## 🧱 Network Architecture

_📌 Add a diagram here once built (use draw.io or Excalidraw)_

---

## 🔍 Detection & Logging

- Implemented Windows Event Forwarding
- Collected logs via Sysmon
- Detected:
  - Failed logins
  - Lateral movement
  - Kerberoasting
  - Suspicious PowerShell usage

---

## 📸 Screenshots

_📂 Screenshots of lab setup, attacks, detections, dashboards go here._

---

## 📜 Findings & Takeaways

- Documented each attack with:
  - Steps taken
  - Commands used
  - What the logs showed
  - How I detected it in SIEM
- Practiced Blue Team response steps

---

