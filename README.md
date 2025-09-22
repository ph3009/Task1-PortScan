# Task 1 — Local Network Port Scan

## Objective
Discover devices and open ports in the local network using Nmap. Learn about port scanning and network exposure.

## Steps I Followed
1. Identified my local network range (`192.168.29.134/24`).
2. Ran a TCP SYN scan through Nmap for common ports.
3. Saved the result in a file with the name "SYNscan.txt".
4. Picked one host and ran a detailed scan with service + OS detection and saved the result in a file with the name "detailed_scan.txt".
5. Captured packets in Wireshark and saved as "synscan_wireshark.pcapng".

## Findings
- Found 6 devices in my network.
- Open ports:
 - 80 -> HTTP
 - 443 -> HTTPS
 - 1900 -> UPNP
 - 7443 -> ORACLE-HTTPS
 - 8080 -> HTTP-PROXY
 - 8443 -> HTTPS-ALT
 
## Extra work I did
- Did a detailed service + OS detection scan on one host.  
- Captured packets in Wireshark (SYN/SYN-ACK handshake).

## Files in this Repo
- 'SYNscan.txt' - Basic SYN scan
- 'detailed_scan.txt' - service + OS detection for one host
- 'synscan_wireshark.pcapng' - Wireshark packet capture
- 'security_risks.txt' - Potential Security Risks from open ports 























 
