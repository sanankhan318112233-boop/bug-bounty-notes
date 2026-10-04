# Networking for Hackers - My Notes
# From Cyber Mind Space 4 Hour Course

## 1. Why Networking is Important?
- Hacking = Communication between 2 computers
- Without networking, we cannot hack
- Every attack starts with IP and Port

## 2. OSI Model (7 Layers) - Simple
- Layer 7 - Application (HTTP, DNS)
- Layer 4 - Transport (TCP, UDP)
- Layer 3 - Network (IP Address)
- Layer 2 - Data Link (MAC Address)

## 3. TCP vs UDP
- TCP = Safe, Slow, Connection needed (Website)
- UDP = Fast, No connection (Video call, DNS)

## 4. Important Ports for Hacking
- 80 = HTTP (Website)
- 443 = HTTPS (Secure Website)
- 22 = SSH (Remote Login)
- 21 = FTP (File Transfer)
- 53 = DNS (Domain Name)
- 445 = SMB (Windows Sharing)

## 5. IP Address Types
- Public IP = Internet IP
- Private IP = 192.168.1.1 (Home/Office)
- 127.0.0.1 = Localhost (My own PC)

## 6. Nmap Commands I Learned
- nmap 192.168.1.1 = Basic scan
- nmap -sV 192.168.1.1 = Find version/service
- nmap -A 192.168.1.1 = Full details (OS, version)
- nmap -p 80 192.168.1.1 = Scan only port 80

## 7. Wireshark
- Used to see network packets
- Can capture passwords in HTTP

## My Progress
- Understood IP, Ports, TCP/UDP, Nmap
- My personal learning notes
  
- Next Topic: Reconnaissance (Footprinting)

---
Created by: Hamza | Peshawar | Learning Ethical Hacking
Date: Oct 2026
