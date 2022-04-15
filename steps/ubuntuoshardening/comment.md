# Ubuntu OS Hardening

This procedure is for the Ubuntu OS hardening to improve the system security.

This has been tested on Raspberry Pi 4 with Ubuntu Server 20.04.2 LTS 64-bit.

## Replace the Default Account

Create a new account then delete the default Ubuntu account.

## Secure SSH and SUDO

Disable the SSH root login and force SUDO to require a password.

## Patching and Unattended Upgrades

Patch the device with the latest packages and enable unattended upgrades.

## Fail2Ban

[Fail2ban](https://en.wikipedia.org/wiki/Fail2ban) is intrusion prevention 
software that protects servers from brute force attacks.

## Firewall

The [Uncomplicated Firewall](https://wiki.ubuntu.com/UncomplicatedFirewall) (ufw) is a frontend for iptables.