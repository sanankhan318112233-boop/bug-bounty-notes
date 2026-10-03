   # Nmap Cheatsheet - My Pentesting Notes
   
   ## Basic Scans
   nmap -sV target.com - Check version
   nmap -sC target.com - Default scripts
   nmap -A target.com - Aggressive scan
   
   ## Important Ports
   21 FTP, 22 SSH, 80 HTTP, 443 HTTPS, 3306 MySQL
   
   ## My Method
   1. Scan all ports
   2. Check for open services
   3. Search exploits
