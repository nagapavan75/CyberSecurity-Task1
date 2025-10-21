# CyberSecurity-Task1
##Objective 
To scan My Local Network and identify open ports using Nmap.
## Steps Performed
1. Installed Nmap
2. Found my local IP range using ipconfig
3. Ran nmap -sS 192.168.55.104/24
4. Saved results in on scan_results.txt
5. Analyzed open ports and their services

## Findings
- Device 192.168.55.104 → Ports 135, 139, 445 open
- Device 192.168.55.104 → Port 6881 open

## Learnings
- Understood how port scanning reveals running services
- Learned about TCP SYN scan
- Identified how open ports can expose security risks
