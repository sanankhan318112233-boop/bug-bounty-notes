# OSI Model - 7 Layers Explained

> Day 2 of my Bug Bounty Journey | Peshawar, Pakistan

## What is OSI Model?
OSI (Open Systems Interconnection) explains how data travels from one device to another over a network. It has 7 layers.

## The 7 Layers (Top to Bottom)

| Layer No | Name | What it Does | Example |
|----------|------|--------------|---------|
| 7 | Application | Where user interacts | WhatsApp, Chrome, Gmail |
| 6 | Presentation | Encryption & Formatting | SSL, JPEG, MP4 |
| 5 | Session | Manages connections | Keeps login session alive |
| 4 | Transport | Reliable delivery | TCP, UDP, Port Numbers |
| 3 | Network | Routing - IP Address | Router, IP (192.168.1.1) |
| 2 | Data Link | Local delivery - MAC | Switch, MAC Address |
| 1 | Physical | Hardware & Signals | Cables, WiFi waves |

## Real Life Example: Sending WhatsApp Message

1. **You type "Salam" (L7)**
2. **Encrypted (L6)**
3. **Session kept open (L5)**
4. **Port 443 added (L4)**
5. **IP Address added - where to send (L3)**
6. **MAC Address - which router (L2)**
7. **WiFi signal sent (L1)**

## Why Important for Bug Bounty?
- **L7 (Application):** 90% bugs here - XSS, SQLi, IDOR - This is our main target
- **L4 (Transport):** Port scanning with Nmap to find open doors
- **L3 (Network):** IP enumeration

## Key Takeaway
If you understand OSI, you understand WHERE to look for bugs.

---
*Learning in public - Day 2/30 | #BugBounty #Networking*
