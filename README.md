# 🛡️ Home Network Security Assessment Using Kali Linux and Nmap

## 📖 Project Overview

This project demonstrates a basic home network security assessment performed in a controlled laboratory environment using Oracle VirtualBox, Kali Linux, and Nmap. The objective was to identify active network services, analyze open ports, evaluate potential security risks, and provide recommendations to improve the security posture of the target Windows system.

---

## 🎯 Objectives

- Build a cybersecurity lab using Oracle VirtualBox and Kali Linux.
- Verify network connectivity between systems.
- Perform network reconnaissance using Nmap.
- Identify open ports and active services.
- Analyze network services and assess potential risks.
- Document findings and recommend security improvements.

---

## 🧪 Lab Environment

**Host Operating System**
- Windows 11

**Assessment Machine**
- Kali Linux (Oracle VirtualBox)

**Network**
- Home Local Area Network (LAN)

---

## 🛠️ Tools Used

- Oracle VirtualBox
- Kali Linux
- Nmap
- Windows Command Prompt
- ipconfig
- ping
- netstat
- tasklist

---

## 🔍 Methodology

1. Configured a Kali Linux virtual machine in Oracle VirtualBox.
2. Identified the Windows host IP address using `ipconfig`.
3. Verified connectivity using `ping`.
4. Performed a basic Nmap scan.
5. Performed service version detection using `nmap -sV`.
6. Verified active connections using `netstat -ano`.
7. Examined running processes using `tasklist`.
8. Evaluated risks and documented recommendations.

---

## 📊 Findings

The assessment identified the following active services:

| Port | Service |
|------|---------|
| 135 | Microsoft Windows RPC |
| 139 | NetBIOS Session Service |
| 445 | Microsoft SMB |
| 12345 | ElevationService.exe |

---

## ⚠️ Risk Assessment

- Port 135 – Medium Risk
- Port 139 – Medium Risk
- Port 445 – Medium–High Risk
- Port 12345 – Low–Medium Risk

---

## 💡 Recommendations

- Keep Windows updated.
- Enable Windows Firewall.
- Disable unnecessary services.
- Regularly review open ports.
- Verify unknown services.
- Perform periodic security assessments.

---

## 📁 Repository Structure

```
Home-Network-Security-Assessment/
│
├── README.md
├── Report/
│   └── Home_Network_Security_Assessment_Report.pdf
│
└── Images/
    ├── VirtualBox_Manager.png
    └── Kali_Linux_VM.png
```

---


## 📄 Project Report

The complete project documentation is available in the **Report** folder.

## 📷 Project Images

### Oracle VirtualBox Environment

![Oracle VirtualBox](Oracle%20Virtual%20Box.png)

---

### Kali Linux Virtual Machine

![Kali Linux](kali%20linux.png)
---

## 🎓 Skills Demonstrated

- Virtualization
- Kali Linux
- Nmap
- Network Reconnaissance
- Port Scanning
- Service Enumeration
- Risk Assessment
- Technical Documentation

---

## 🚀 Future Improvements

Future enhancements may include:

- Wireshark traffic analysis
- Vulnerability scanning
- Firewall analysis
- Security log analysis
- Incident response

---

## 📌 Disclaimer

This project was conducted exclusively within an authorized home laboratory environment for educational purposes. No unauthorized systems or networks were accessed.
