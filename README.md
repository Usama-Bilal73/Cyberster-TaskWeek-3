# Network Protocol Abuse: Purple Team Lab (Week 3)

## Project Overview
[cite_start]This repository contains technical documentation and simulation results for the **Purple Team Week 3 Lab** focused on infrastructure and protocol analysis[cite: 338, 345]. [cite_start]The primary goal is to identify points of failure in network protocols when subjected to stress or exploitation[cite: 349, 351].

## Key Features
* [cite_start]**DoS Simulations:** Practical execution of TCP SYN Floods and ICMP Floods using `hping3` to overwhelm target services[cite: 346, 354].
* [cite_start]**MITM Analysis:** Demonstrating interceptive capabilities through ARP spoofing and "Unified Sniffing" using Ettercap[cite: 348, 496, 584].
* [cite_start]**Traffic Monitoring:** Detailed packet analysis via Wireshark to identify abnormal patterns and protocol vulnerabilities (TCP, ICMP, ARP)[cite: 347, 351, 565].
* [cite_start]**Security Hardening:** Comparative analysis of plain-text HTTP vs. encrypted VPN tunneling, highlighting the necessity of end-to-end encryption[cite: 566, 567, 606].

## Lab Outcomes
* [cite_start]**Vulnerability Assessment:** Confirmed the inherent "trust-by-default" flaw in the ARP protocol[cite: 663, 664].
* [cite_start]**Defense Strategies:** Documented mitigation techniques including HSTS enforcement, static ARP configuration, and VPN utilization[cite: 669, 670, 672].
* [cite_start]**Future Threat Outlook:** Evaluated the persistence of DDoS threats in 2026 and strategies for large-scale organizational defense[cite: 349].

## Tools Used
* [cite_start]Kali Linux [cite: 353]
* [cite_start]hping3 [cite: 353]
* [cite_start]Ettercap [cite: 496]
* [cite_start]Wireshark [cite: 347]
* [cite_start]Nmap [cite: 608]

---
**Author:** Muhammad Usama Bilal  
**Course:** Purple Team Infrastructure & Protocol Analysis  
[cite_start]**Date:** March 2026 [cite: 342]
