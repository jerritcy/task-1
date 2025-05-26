Task 1 – Local Network Port Scanning

Objective
Use Nmap to scan local network and identify open ports.

Tools
- Nmap
- (Optional) Wireshark

Result 
Saved as scan_result. (included in this repo).

 Observations
Discovered active devices and open ports.

Common services found include:

Port 80 (HTTP)
Port 443 (HTTPS)
Port 135 (msrpc)
Port 139 (netbios-ssn)
Port 445 (microsoft-ds)

 Command Used
```bash
nmap -sS -T4 192.168.1.0/24 -oN scan_result.txt
