# DNS Spoofing with Ettercap

**Course:** Cybersecurity  
**Student:** Oumar Leyti Ndiaye | A00228981

## Overview
Demonstration of a DNS Spoofing attack combined with ARP Poisoning
using Ettercap in a controlled local network environment.

## Topics Covered
- ARP Poisoning (Man-in-the-Middle setup)
- DNS Spoofing via Ettercap dns_spoof plugin
- Fake web page hosting with Apache2
- DNS redirection to real external server (Google)
- Ettercap command-line mode (-T -q)
- iptables configuration for traffic interception
- Counter-measures: DNSSEC, HTTPS/HSTS, DoH, DoT, VPN

## Tools Used
- Ettercap (graphical & command-line)
- Apache2
- Kali Linux
- Windows 10 (victim)

## Key Results
- DNS requests for microsoft.com successfully intercepted
- Victim redirected to attacker machine (192.168.2.25)
- Redirection to Google also demonstrated
- HTTPS/HSTS browser protection observed and analyzed

## Incident Response (Task 2)
- Patch deployed without testing (rollback procedure)
- Infected SD card scenario (endpoint isolation)
- Hacktivist threat response methodology

## Report
[View PDF](./DNS_Spoofing_Ettercap.pdf)
