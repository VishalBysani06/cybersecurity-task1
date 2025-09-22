# cybersecurity-task1
Cybersecurity Internship Task 1: Conducted a network scan of a local WiFi network using Nmap to identify active devices, open ports, and potential security risks. Includes scan results, screenshots, and analysis.

Cyber Security Internship — Task 1

Name: Vishal B M  
Date: 22-09-2025  

 Objective
Scan my local WiFi network (192.168.1.0/24) using Nmap to identify devices and open ports.

Tools Used
- Windows 10  
- Nmap 7.98  

 Command Run

Results (Summary)
- **192.168.1.1 (Router)**  
  - Open ports: 53 (DNS), 80 (HTTP), 443 (HTTPS)  
- **192.168.1.2** — All ports closed  
- **192.168.1.6** — All ports closed  
- **192.168.1.7 (My PC)**  
  - Open ports: 135 (MSRPC), 139 (NetBIOS), 445 (SMB), 902, 912, 3306 (MySQL)  

 Risks & Notes
- Router has web admin ports open → must use strong password and disable remote admin.  
- My PC exposes SMB and MySQL → should block in firewall or disable if not needed.  

Files in Repo
- `nmap_scan_results.txt` → raw scan output  
- `screenshots/` → screenshots of scan and text file  
- `README.md` → explanation of task  

 Learning
- Learned how to run a TCP SYN scan with Nmap.  
- Understood how open ports show possible vulnerabilities.

