# Linux Server Hardening & Intrusion Prevention

Real Ubuntu Server secured with enterprise-grade controls.

**Attacker:** Kali Linux (192.168.64.4) 
**Target:** Ubuntu Server (192.168.64.3) 

**Defenses Implemented:**
- UFW firewall (only SSH & HTTP allowed)
- Fail2ban (auto-bans IPs after 5 failed SSH logins)

**Live Proof:** Kali attacker (192.168.64.4) got permanently banned after failed logins

## Screenshots
![UFW Firewall](screenshots/ufw.png)
![Fail2ban Service Active](screenshots/fail2ban-active.png)
![Attacker IP Banned by Fail2ban](screenshots/fail2ban-ban.png)

**Skills:** Linux hardening · Firewall management · Intrusion prevention · Defense validation
