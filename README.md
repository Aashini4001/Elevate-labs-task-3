# Elevate-labs-task-3
Perform a Basic Vulnerability Scan on Your PC
# 🔍 Vulnerability Scan Task - Cybersecurity Internship

## 📌 Task Objective
To perform a basic vulnerability scan on my personal computer using a free vulnerability scanning tool (Nessus Essentials or OpenVAS) and identify any existing security issues.

---

## 🛠 Tool Used
**Nessus Essentials**  
(Nessus Essentials was chosen for its beginner-friendly interface and powerful scanning capabilities.)

---

## 💻 Scan Setup

- **Target:** My local machine (`127.0.0.1`)
- **Scan Type:** Basic Network Scan
- **Scan Duration:** ~45 minutes

---

## 📊 Summary of Findings

| Vulnerability Title               | Severity | CVE ID         | Description                                                                 | Suggested Fix                                     |
|----------------------------------|----------|----------------|-----------------------------------------------------------------------------|--------------------------------------------------|
| SSL Certificate Expiry Warning   | Medium   | -              | SSL certificate is nearing expiration.                                      | Renew the certificate.                           |
| SMB Signing Not Required         | High     | CVE-2017-0143  | Could allow remote attackers to exploit SMB.                               | Enable SMB signing or disable SMBv1.             |
| Outdated Software Detected       | Medium   | -              | Some applications were not up-to-date.                                     | Update all software to the latest versions.      |
| Open Ports Detected              | Info     | -              | Ports 135, 139, and 445 were open.                                          | Close unnecessary ports or restrict via firewall



## 📖 Key Concepts Covered

- Vulnerability scanning basics  
- Using Nessus Essentials  
- Understanding CVSS scores  
- Identifying critical system vulnerabilities  
- Planning basic remediation steps





