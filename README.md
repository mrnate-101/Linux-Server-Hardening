# Linux Server Hardening & Intrusion Prevention

Real Ubuntu Server secured with enterprise-grade controls.

**Attacker:** Kali Linux (192.168.64.4) 
**Target:** Ubuntu Server (192.168.64.3) 

**Defenses Implemented:**
- UFW firewall (only SSH & HTTP allowed)
- Fail2ban (auto-bans IPs after 5 failed SSH logins)

**Live Proof:** Kali attacker (192.168.64.4) got permanently banned after failed logins

## Screenshots
![Fail2ban Installed & Active](screenshots/fail2ban-installed.png)
![UFW Firewall Active](screenshots/firewall-enabled-on-Ubuntu-ports(except-Http,ssh-ports).png)
![Attacks failed](screenshots/first-3-attacks-from-Kali-failed.png)
![UFW Firewall Active](screenshots/kali-linux-permission-denied.png)
![Attacker IP banned by server](screenshots/Kali(attacker)IPbanned.png)
![Server Dispalying blocked IP](screenshots/my-ubuntu-(victim)-showing-the-banned-ip-address.png)


**Skills:** Linux hardening · Firewall management · Intrusion prevention · Defense validation


# Linux Server Hardening & Intrusion Prevention
I disabled the hardening systems for the ubuntu server and run attacks on Kali Linux.

There was nothing to detect and block my ip from brute-forcin my through. 
I tried more than 5 times and I was still going

## Screenshots
![Hardening on Server Disabled](screenshots/firewall-and-fail2ban-on-ubuntu-disabled.png)
![Vulnerability](screenshots/I-have-tried-to-attack-as-many-times-on-Kali-but-IP-wasn't-blocked.png)

