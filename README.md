🛡️ SIEM–NAC Integration Project

## 🚀 Overview

This project demonstrates an automated cybersecurity system that integrates a SIEM platform with a Network Access Control (NAC) solution to detect and respond to threats in real time.
The system follows a **Detect → Analyze → Respond** workflow to automatically isolate compromised devices and reduce incident response time.

---
## 🧠 Architecture

The system consists of three main components:

### 🔹 1. SIEM (Security Onion)

* Monitors network traffic
* Detects malicious activities
* Generates security alerts

### 🔹 2. Integration Service (Python)

* Processes alerts from SIEM
* Determines the severity of threats
* Decides the appropriate response

### 🔹 3. NAC (PacketFence)

* Enforces security policies
* Isolates compromised devices
* Applies VLAN-based quarantine

---
## 🔄 Workflow

1. SIEM detects suspicious or malicious activity
2. Alerts are sent to the Python integration service
3. The system analyzes the alert
4. NAC enforces the response (e.g., device isolation)

📌 **Automation reduces response time and limits attack spread**

---
## 🧪 Use Cases

### 🦠 Malware Detection

* Threat detected by SIEM
* Device is immediately isolated

### 🔐 Brute Force Attack

* Suspicious login attempts detected
* Device is temporarily isolated

---
## 🛠️ Technologies Used

* Security Onion (SIEM)
* PacketFence (NAC)
* Python
* VLAN Segmentation
* REST API

---
## 📸 Project Screenshots

*(<img width="962" height="983" alt="overview" src="https://github.com/user-attachments/assets/03ddc67e-5733-40ae-9368-1cb48207588d" />
<img width="1200" height="1600" alt="siem-monitoring" src="https://github.com/user-attachments/assets/91242e55-9a01-4317-be58-c0def078da7a" />
<img width="1600" height="1200" alt="attack-response" src="https://github.com/user-attachments/assets/557cb0ab-afb4-439a-b38c-5dab69f62e3b" />
<img width="1200" height="1600" alt="packetfence-dashboard" src="https://github.com/user-attachments/assets/2e27c811-124d-4b4d-8760-a43859f3920c" />
)*

* System overview
* Security Onion monitoring
* PacketFence dashboard
* Attack response results

---
## 🎯 Key Achievements

* Built an automated incident response system
* Integrated SIEM with NAC using Python
* Implemented real-time threat detection and response
* Applied network segmentation for security enforcement

---
## 💡 What I Learned

* SIEM architecture and threat detection
* Network Access Control (NAC) systems
* Security automation and orchestration
* Real-world SOC workflows

---
## 📌 Future Improvements

* Add more advanced detection rules
* Integrate threat intelligence feeds
* Improve automation logic using AI

---
## 👨‍💻 Author

**Abdallah Elgamasy**
Software Engineering Student 
