# Network-Security-Best-Practices
Yuva Intern Task 6 – Final Capstone Project: Research and practical assessment of network security practices using Kali Linux and Metasploitable, covering authentication, firewall rules, network monitoring, logging, Nmap scanning, packet analysis, and security best practices.
Network Security Best Practices

Yuva Intern – Task 6 | Final Capstone Project

Submitted by: Sai Akul
Project Domain: Cybersecurity / Network Security
Tools Used: Kali Linux, Metasploitable, Nmap, SSH, iptables, tcpdump

Project Overview

This project focuses on researching and understanding practical network security practices through a controlled virtual lab environment using Kali Linux and Metasploitable.

The project examines authentication security, network segmentation, firewall configurations, secure network practices, security monitoring, logging, and packet analysis.

Objectives

1. Research commonly recommended network security practices.
2. Understand the importance of network segmentation.
3. Study secure authentication and access-control practices.
4. Understand firewall, IDS, and IPS security concepts.
5. Research secure network configuration practices.
6. Understand the importance of monitoring and security logging.
7. Create a practical network security best-practices checklist.

Tools and Technologies

- Kali Linux: Security testing and network analysis environment.
- Metasploitable: Intentionally vulnerable virtual machine for controlled lab exercises.
- Nmap: Network and open-port scanning.
- SSH: Remote authentication testing.
- iptables: Firewall rule inspection.
- tcpdump: Network packet monitoring and analysis.
- Linux Authentication Logs: Monitoring failed authentication attempts.

Practical Work and Findings

1. SSH Authentication Monitoring

Performed controlled SSH login attempts using an invalid test username and incorrect passwords. Examined authentication logs to identify unsuccessful login attempts and their source IP address.

2. Firewall Rule Inspection

Inspected firewall rules using iptables and reviewed traffic-filtering policies.

3. Network Scanning

Used Nmap to identify selected open TCP ports and services on the Metasploitable virtual machine.

4. Packet Monitoring

Used tcpdump to inspect FTP control traffic and understand the security risks associated with transmitting credentials through unencrypted protocols.

5. Security Recommendations

Documented recommendations covering secure authentication, access control, network segmentation, firewall policies, encrypted communication, and security logging.

Key Findings

- Failed SSH authentication attempts were recorded in the target system's authentication logs.
- Nmap identified FTP (21/tcp), Telnet (23/tcp), and TCP port 1524 as open during the captured scan.
- Firewall rules were inspected using iptables.
- Packet analysis demonstrated the exposure risk of plaintext FTP authentication data.
- Network segmentation and IDS/IPS concepts were evaluated through security design and research.

Repository Structure

Network-Security-Best-Practices/
│
├── README.md
├── Sai_Akul_Yuva_Intern_Task_6_Network_Security_Report.docx
└── Screenshots/
    ├── SSH-Authentication/
    ├── Firewall-Rules/
    ├── Nmap-Scan/
    └── Packet-Analysis/

Conclusion

This project provided practical exposure to network security monitoring, authentication analysis, firewall inspection, network scanning, and packet analysis.

It also highlighted the importance of secure configurations, encrypted communication, access control, network segmentation, and continuous security monitoring.

Project completed as part of the Yuva Intern Final Capstone Project – Task 6.
