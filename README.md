<div align="center">

<!-- ANIMATED HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:ffd166,50:e07a3f,100:0d1117&height=200&section=header&text=Mohamed%20Reda%20Karrach&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=I%20build%20labs%2C%20then%20I%20detect%20what%20I%20attack.&descAlignY=58&descSize=18" />

<!-- TYPING ANIMATION -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=FFD166&center=true&vCenter=true&width=820&lines=Cybersecurity+Engineering+Student+%40+EMSI+Casablanca;SOC+%7C+Detection+Engineering+%7C+Incident+Response;Developer+first%2C+defender+by+choice;Open+to+a+PFE+internship+from+early+2027)](https://git.io/typing-svg)

<a href="https://redakarrach.github.io"><img src="https://img.shields.io/badge/Portfolio-redakarrach.github.io-ffd166?style=for-the-badge&logo=githubpages&logoColor=black" /></a>
<a href="https://www.linkedin.com/in/reda-karrach-a2a52730b"><img src="https://img.shields.io/badge/LinkedIn-Reda%20Karrach-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:redanb136@gmail.com"><img src="https://img.shields.io/badge/Email-redanb136%40gmail.com-e07a3f?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Casablanca%2C%20Morocco-0d1117?style=for-the-badge&logo=googlemaps&logoColor=ffd166" />

</div>

---

# 🧑‍💻 About Me

I am a **5th-year cybersecurity and network infrastructure engineering student at EMSI Casablanca**. I started as a developer (C, C++, Java, Django, PHP), which is why, when I study an attack, I end up building the thing that detects it.

- 🛡️ SOC engineering: Wazuh, TheHive, Cortex, Shuffle, end-to-end response playbooks
- 🔎 Detection engineering: Sigma rules, MITRE ATT&CK mapping, tested and version-controlled like code
- 🚨 Incident response: CloudTrail forensics, timeline reconstruction, containment that does not make things worse
- 🧪 Offensive work in the lab only: OWASP Top 10, Burp Suite, Atomic Red Team, network attacks against my own machines
- 🏗️ Full-stack builder: Python, Django and DRF, React, Next.js, Node.js, Solidity

🎯 **Looking for a PFE internship from early 2027**, 4 to 6 months, in SOC, detection engineering or incident response. Casablanca or remote.

---

# 🧠 Tech Stack

## 🛡️ Defend
<p>
<img src="https://skillicons.dev/icons?i=linux,bash,docker,grafana,prometheus,sklearn,aws" />
</p>

Wazuh · Shuffle · TheHive · Cortex · MITRE ATT&CK · Atomic Red Team · Sigma · Scapy · Wireshark · Zabbix

## 🗡️ Attack (lab only)
<p>
<img src="https://skillicons.dev/icons?i=kali,postman" />
</p>

Kali Linux · Burp Suite · Nmap · Hydra · OWASP Top 10

## 💻 Build
<p>
<img src="https://skillicons.dev/icons?i=py,django,fastapi,js,ts,react,nextjs,nodejs,express,c,cpp,java,php,dotnet,solidity" />
</p>

## ⚙️ Run
<p>
<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,sqlite,git,github,githubactions,vscode,latex" />
</p>

Linux · TCP/IP · GNS3 · Docker

📚 **Studying now:** digital forensics, cloud security, GRC (ISO 27001, NIST CSF), cryptanalysis

---

# 🚀 Featured Projects

---

## 🔑 keyleak — AWS leaked-key incident response
🔗 https://github.com/RedaKarrach/keyleak &nbsp;·&nbsp; 📖 https://redakarrach.github.io/keyleak/

Your AWS key ended up on GitHub. keyleak reads your own CloudTrail logs and answers "what did the attacker do, and what is still running", in one command, without ever touching the stolen key.
- Timeline of the attacker's actions across every region, flagged by category (persistence, cryptomining, SES and Bedrock abuse, discovery)
- **The pivot:** automatically investigates every user and key the attacker created, because deleting the leaked key is not enough
- Read-only by default; one `--confirm` command to deactivate the key; HTML report with a ready-to-send AWS Support message
- Python, boto3, click, rich. Tests run with botocore Stubber, no AWS account needed

---

## 🏢 Distributed SOC lab
🔗 https://github.com/RedaKarrach/distributed-soc-lab

A working security operations centre on two machines.
- Wazuh watches the endpoints, Shuffle runs the response playbook
- Cortex enriches each alert with threat intelligence, TheHive opens the incident case
- Validated end to end with Atomic Red Team attacks, from the simulated intrusion to the classified case

---

## 🧪 detforge — unit tests and CI for Sigma detection rules
🔗 https://github.com/RedaKarrach/detforge

Detection rules treated like code.
- Lint, true-positive / true-negative / baseline tests in SQLite
- Conversion to Splunk and Elastic queries
- MITRE ATT&CK coverage report

---

## 📡 ReconTool — real-time network intrusion detection
🔗 https://github.com/RedaKarrach/NetworkReconnaissanceTool

- Python agents on each machine spot port sweeps, SYN floods and ARP spoofing, and block the source
- Alerts stream to a live React SOC dashboard with a risk score per host
- MITRE ATT&CK mapping and PDF reports

---

## 🎣 URLPhishingDetector — explainable phishing URL triage
🔗 https://github.com/RedaKarrach/URLPhishingDetector

- Decision tree (scikit-learn) plus analyst rules: typosquatting, homoglyphs, brand abuse
- `.eml` triage with explainable verdicts, fully offline
- Try it in the browser

---

## ⛓️ ChainShop Nexus — trustless e-commerce on Ethereum
🔗 https://github.com/RedaKarrach/chainshop-nexus

- Solidity escrow contracts with Hardhat tests
- Express API, ethers.js indexer, Next.js 14 front end

---

Also: a web penetration test with documented SQLi and XSS findings, and the SOC team of **Exercice KASBAH** (EMSI × CyberSup), a three-day ransomware crisis simulation.

---

# 💼 Experience

**Application security intern**
- Built a deliberately vulnerable Django REST application, then broke it and fixed it
- OWASP findings reproduced with Burp Suite (SQL injection, XSS, broken access control), with proofs of concept
- Remediation shipped: parameterised queries, RBAC, output escaping, Content Security Policy
- CVE monitoring on Django and first steps in DevSecOps
- A short geomatics mission on the side (QGIS, PyQGIS, PostGIS)

---

# 📊 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=RedaKarrach&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffd166&icon_color=e07a3f" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RedaKarrach&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=ffd166&langs_count=8" />
</div>

---

# 🤝 Open Source

Issues and pull requests are welcome on every repository above, especially:

- 🐛 Bug reports with a way to reproduce
- 🔎 New detection ideas for keyleak and detforge
- 📖 Documentation that makes a tool easier to use when someone is panicking

<sub>Every offensive tool in these repositories is built and used in isolated lab networks only.</sub>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:e07a3f,100:ffd166&height=120&section=footer" />
</div>
