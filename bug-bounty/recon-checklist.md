# My Bug Bounty Recon Checklist

## Subdomain Finding
subfinder -d target.com -o subs.txt
assetfinder --subs-only target.com

## Live Hosts
httpx -l subs.txt -o live.txt

## My Notes
- Check XSS on search box
- Check IDOR on user IDs
