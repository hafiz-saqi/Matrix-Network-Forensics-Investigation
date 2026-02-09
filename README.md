# Matrix Network Forensics Investigation

## 📌 Project Overview
This project presents a comprehensive network forensics investigation based on the analysis of a packet capture file (`matrix.pcapng`). The investigation focuses on reconstructing Telnet sessions, identifying unauthorized activities, evaluating access control policy violations, and determining the validity of Agent Smith’s claims within the Matrix environment.

---

## 🎯 Objectives
- Analyze Telnet traffic using Wireshark
- Reconstruct user commands and on-screen activity
- Identify privilege escalation and policy violations
- Determine whether company policies were breached
- Validate or refute Agent Smith’s statements using forensic evidence

---

## 🛠 Tools & Techniques Used
- **Wireshark** – Packet capture analysis
- **Telnet Protocol Analysis**
- **TCP Stream Reconstruction**
- **Linux Command & Permission Analysis**
- **Access Control Policy Evaluation**

---

## 📂 Dataset / Evidence
- `matrix.pcapng` – Network packet capture file used for forensic analysis

---

## 🔍 Key Findings
- Unauthorized privilege escalation was detected during the Telnet session
- Critical system files and user data were modified using elevated privileges
- Battery group users exceeded their authorized permissions
- Administrative actions attempted by Agent Smith failed, supporting claims of privilege escalation

---

## ⏱ Incident Timeline
A detailed timeline was reconstructed using packet numbers, timestamps, IP addresses, ports, and Telnet command sequences.  
All user keystrokes and system responses were recovered using the **Follow TCP Stream** feature in Wireshark.

---

## 📁 Repository Structure
