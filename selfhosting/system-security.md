---
title: "Improve system security"
created: 2021-01-14
keywords:
  - selfhosting
  - linux
  - security
---
# Improve your system security
*Don't be a fucking idiot and then some* 20210328203150

make sure you [set up your ssh correctly](./setup-ssh.md)

## Fail2ban
20210328203159

*Prevent spam, DDoS or Brute Force attacks*
> $ sudo apt install fail2ban
> $ sudo systemctl enable fail2ban
> $ sudo systemctl start fail2ban

## UFW Firewall
20210328204340
### Management
* ufw allow
* ufw deny
* ufw status
* ufw enable
* ufw default deny incoming
* ufw default allow outgoing
* ufw limit 

### Explizit Zugelassen
* 22/tcp SSH
* 25 SMTP
* 143 IMAP
* 420 SSH
* 443/tcp HTTPS
* 8000 etebase / etesync


### Explizit Verboten (außer temporär zu dev-zwecken)
* 80/tcp http <-- unsicher

Standard: deny incoming, allow outgoing

## Docker Security
can be found here:[[20210328203831]] in [container-apps-docker.md]