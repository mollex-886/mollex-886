<h1 align="center">Khin Myat Myat Cho</h1>
<h3 align="center">Cybersecurity Student · SOC & Blue Team Focus · CTF Player</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00F7FF&center=true&vCenter=true&width=500&lines=Cybersecurity+Student;Security+Operations+%26+Threat+Detection;Building+Practical+Blue+Team+Projects;Preparing+for+SOC+Internships" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/khin-myat-myat-cho-649621287/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/mollex-886">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  </a>
</p>

---

### About

Second-year Cybersecurity student focused on security operations, incident response, and applied defensive security. Comfortable moving between offensive tooling (CTFs, vulnerability assessment) and blue team fundamentals (log analysis, detection, forensics), with an interest in how attacker techniques should shape defensive design. Currently building a portfolio of hands-on labs and tools ahead of SOC-track internship applications.

**Current focus:** SOC operations, threat detection, digital forensics, and applied Python/C# tooling for security use cases.

---

### Featured Project

**[PasswordChecker](https://github.com/mollex-886/PasswordChecker)** — C#

Modular static analysis tool that evaluates password security using entropy calculation, NIST guidelines, and real-world breach intelligence, rather than outdated complexity rules.

- **Entropy calculation** — computes bits of entropy via `E = L × log2(R)` to quantify cryptographic unpredictability
- **Breach checking (HIBP API)** — queries Have I Been Pwned using k-Anonymity (SHA-1 partial hashing) so raw passwords never leave the client
- **Local dictionary matching** — `HashSet`-backed O(1) lookups against common password lists (e.g. `rockyou.txt`)
- **Strategy pattern architecture** — rules implement a shared `IPasswordRule` interface, so new checks can be added without touching the core engine

**Design:** `PasswordAnalyzer` (aggregation engine) orchestrates independent rule strategies — `EntropyRule`, `PwnedApiRule`, `DictionaryRule`, `LengthRule` — each isolated and independently testable.

---

### Other Projects

| Project | Description | Stack |
|---|---|---|
| Restaurant Management System | GUI-based system for managing orders and restaurant operations | C# |
| Hospital Management System | System for managing patient and hospital records | Python |
| Course Recovery System | Application for course registration and recovery workflows | Java |

---

### Technical Skills

**Security & Analysis**
![Kali Linux](https://img.shields.io/badge/Kali_Linux-268BEE?style=flat-square&logo=kalilinux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-004170?style=flat-square)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square)

**Systems & Networking**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cisco Packet Tracer](https://img.shields.io/badge/Cisco_Packet_Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Development**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

---

### Currently Learning

SOC analysis and threat hunting · Active Directory fundamentals · web exploitation · Python automation for security tooling

---

### GitHub Stats

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mollex-886&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=mollex-886&theme=tokyonight" />
</p>
