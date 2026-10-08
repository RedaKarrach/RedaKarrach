<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img alt="Mohamed Reda Karrach, cybersecurity engineering student. I build labs, then I detect what I attack." src="assets/banner-light.svg" width="100%">
</picture>

I'm a 5th-year **cybersecurity & network infrastructure engineering** student at EMSI Casablanca, graduating in 2027. I come from full-stack development, so when I study an attack I usually end up building the tool that detects it.

**Looking for:** a PFE (end-of-studies) internship in **SOC / detection engineering / incident response**, with an interest in cloud security.
*Je recherche un stage PFE en SOC / Blue Team (Casablanca, Rabat ou remote).*

---

### Featured work

**[ReconTool: real-time network intrusion detection platform](https://github.com/RedaKarrach/NetworkReconnaissanceTool)**
End-of-year project (PFA). Python/Scapy agents sniff traffic on lab endpoints, detect SYN floods, ARP spoofing and ICMP redirects, and can block the source with `iptables` / `netsh`. Alerts stream over WebSockets to a React SOC dashboard, mapped to MITRE ATT&CK (T1046, T1557, T1498), with per-host risk scoring, agent health monitoring and PDF session reports.
`Scapy` `Django Channels` `MongoDB` `React 18` `D3.js` `Docker Compose`

**[Automated incident response playbooks: distributed SOC lab](https://github.com/RedaKarrach/distributed-soc-lab)**
Two-machine SOC over a dedicated LAN: Wazuh (SIEM) and Shuffle (SOAR) on one node, TheHive (case management) and Cortex (enrichment) on the other, with Windows and Linux endpoints. Adversary behaviour is replayed with Atomic Red Team to test detections and response playbooks end to end.
`Wazuh` `Shuffle` `TheHive` `Cortex` `Atomic Red Team`

**[ChainShop Nexus: trustless e-commerce on Ethereum](https://github.com/RedaKarrach/chainshop-nexus)**
Monorepo with three Solidity contracts (escrow, order registry, reviews) tested with Hardhat, an Express API gateway, an ethers.js event indexer and a Next.js 14 front end.
`Solidity` `Hardhat` `ethers.js` `Express` `Next.js` `MongoDB`

---

### What I work with

| Area | Tools and skills |
|---|---|
| SOC / Blue Team | Wazuh (deployment, agents, active response), Shuffle, TheHive, Cortex, threat-intel APIs (VirusTotal, AbuseIPDB, URLScan.io), MITRE ATT&CK |
| Detection & network | Scapy, packet analysis, NIDS design, GNS3, Zabbix, SNMP, NetFlow, Prometheus / Grafana |
| Offensive (lab only) | Kali Linux, Hydra, Atomic Red Team, OWASP Top 10 labs (SQLi, XSS, IDOR, command injection) |
| Cryptography | RSA, ECC, Diffie-Hellman, ElGamal, OpenSSL, digital signatures |
| Development | Python, Django, JavaScript, React, Next.js, Node / Express, PHP, Solidity, Docker |

### Exercises

**Exercice KASBAH (EMSI × CyberSup).** Three-day cyber crisis simulation across four cities, built around a ransomware scenario against a fictional critical-infrastructure operator. I'm on the SOC / Detection team, responsible for the incident chronology.

### Currently studying

Digital forensics, cloud security, ethical hacking, AI for cybersecurity, risk management & GRC (ISO 27001, NIST CSF), security audit and cryptanalysis.

---

### Contact

[Email](mailto:redanb136@gmail.com)

<sub>All offensive tooling in my repositories is built and used in isolated lab networks only.</sub>
