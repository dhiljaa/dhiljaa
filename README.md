# 👨‍💻 Ahmad Fadhil | Cyber Security Enthusiast

```bash
┌──(root㉿kali)-[~/portfolio]
└─$ whoami && echo "Welcome to my digital realm"
ahmad_fadhil
Welcome to my digital realm

┌──(root㉿kali)-[~/portfolio] 
└─$ cat /etc/passwd | grep ahmad_fadhil
ahmad_fadhil:x:1000:1000:Full Stack Developer & Penetration Tester:/home/ahmad_fadhil:/bin/bash
```

<div align="center">

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=700&size=24&pause=1000&color=00FF41&center=true&vCenter=true&width=600&lines=%3E+FULL+STACK+DEVELOPER;%3E+PENETRATION+TESTER;%3E+CYBERSECURITY+RESEARCHER;%3E+DIGITAL+FORENSICS;%3E+RED+TEAM+OPERATIONS;%3E+THREAT+HUNTER)](https://git.io/typing-svg)

</div>

---

## 🎯 **CURRENT STATUS**

```yaml
name: "Ahmad Fadhil"
location: "Bandung, West Java, Indonesia"
current_focus: 
  - "Advanced Web Penetration Testing"
  - "Red Team Operations"
  - "Secure Code Development"
learning:
  - "OWASP Testing Guide"
  - "Advanced Exploitation Techniques"
  - "Malware Analysis & Reverse Engineering"
certifications_in_progress:
  - "CEH (Certified Ethical Hacker)"
  - "eWPT (eLearnSecurity Web Penetration Tester)"
  - "OSCP (Offensive Security Certified Professional)"
```

---

## ⚡ **TECHNICAL ARSENAL**

### 🔴 **OFFENSIVE SECURITY TOOLKIT**

<details>
<summary>🎯 <b>RECONNAISSANCE & ENUMERATION</b></summary>

```bash
# Network Discovery & Port Scanning
nmap -sS -sV -O --script vuln target.com
masscan -p1-65535 --rate=10000 target.com
rustscan -a target.com -- -A -sC

# Web Application Discovery  
gobuster dir -u https://target.com -w /usr/share/wordlists/dirb/common.txt
ffuf -w /usr/share/wordlists/SecLists/Discovery/Web-Content/common.txt -u https://target.com/FUZZ
nikto -h https://target.com

# DNS Enumeration
dig axfr @ns1.target.com target.com
dnsrecon -d target.com -t axfr
amass enum -d target.com
```

**Tools:** `nmap` • `masscan` • `gobuster` • `ffuf` • `nikto` • `amass` • `subfinder` • `httpx`

</details>

<details>
<summary>🕷️ <b>WEB APPLICATION TESTING</b></summary>

```bash
# SQL Injection Testing
sqlmap -u "https://target.com/page?id=1" --batch --dbs
sqlmap -u "https://target.com/page?id=1" --dump-all

# XSS Testing
echo "https://target.com" | waybackurls | gf xss | qsreplace '"><script>alert(1)</script>' | freq

# Directory Traversal
curl -s "https://target.com/page?file=../../../etc/passwd"

# Parameter Discovery
paramspider -d target.com
arjun -u https://target.com/page
```

**Tools:** `Burp Suite Professional` • `OWASP ZAP` • `sqlmap` • `xsstrike` • `commix` • `wfuzz`

</details>

<details>
<summary>💀 <b>EXPLOITATION & POST-EXPLOITATION</b></summary>

```bash
# Metasploit Framework
msfconsole
use exploit/multi/handler
set payload windows/x64/meterpreter/reverse_tcp
exploit -j

# Privilege Escalation
./linpeas.sh
./winpeas.exe
python3 -m http.server 8000

# Persistence & Lateral Movement
crackmapexec smb 192.168.1.0/24 -u admin -p password
impacket-secretsdump domain/user:password@target
```

**Tools:** `Metasploit` • `Cobalt Strike` • `Empire` • `BloodHound` • `mimikatz` • `impacket`

</details>

### 🟢 **DEVELOPMENT STACK**

<div align="center">

| **Frontend** | **Backend** | **Security** | **DevOps** |
|:---:|:---:|:---:|:---:|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) | ![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white) | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) | ![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white) | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white) | ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) | ![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logoColor=white) | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

</div>

---

## 📊 **PENETRATION TESTING PROGRESS**

<div align="center">

### 🎯 **SKILL MATRIX**

| **Domain** | **Level** | **Tools Mastered** | **Next Target** |
|:---|:---:|:---|:---|
| **Web App Security** | ![85%](https://progress-bar.dev/85) | Burp Suite, OWASP ZAP, SQLmap | Advanced WAF Bypass |
| **Network Penetration** | ![75%](https://progress-bar.dev/75) | Nmap, Metasploit, Nessus | Active Directory Attacks |
| **Social Engineering** | ![60%](https://progress-bar.dev/60) | SET, GoPhish, King Phisher | Physical Security |
| **Malware Analysis** | ![45%](https://progress-bar.dev/45) | Ghidra, x64dbg, Wireshark | Dynamic Analysis |
| **Digital Forensics** | ![40%](https://progress-bar.dev/40) | Autopsy, Volatility, FTK | Mobile Forensics |

### 🏆 **CERTIFICATION ROADMAP**

```mermaid
gantt
    title Cybersecurity Certification Journey
    dateFormat  YYYY-MM
    section 2024
    CEH                :active, ceh, 2024-01, 2024-06
    Security+          :sec, 2024-04, 2024-08
    section 2025  
    eWPT               :ewpt, 2024-09, 2025-02
    OSCP               :oscp, 2025-01, 2025-08
    section 2026
    CISSP              :cissp, 2025-06, 2026-02
    CISM               :cism, 2025-12, 2026-06
```

</div>

---

## 🎮 **TRAINING GROUNDS & ACHIEVEMENTS**

<div align="center">

### 🏴‍☠️ **CTF PLATFORMS**

[![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/dhiljaa)
[![Hack The Box](https://img.shields.io/badge/Hack_The_Box-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://app.hackthebox.com/profile/dhiljaa)
[![VulnHub](https://img.shields.io/badge/VulnHub-FF6B6B?style=for-the-badge&logoColor=white)](#)
[![OverTheWire](https://img.shields.io/badge/OverTheWire-000000?style=for-the-badge&logoColor=white)](#)

### 📈 **CURRENT RANKINGS**

| Platform | Rank | Points | Streak |
|:---:|:---:|:---:|:---:|
| **TryHackMe** | 🥇 Top 10% | 2,500+ | 30 days |
| **Hack The Box** | 🥈 Hacker | 1,200+ | Active |
| **VulnHub** | 🥉 Intermediate | 50+ VMs | Weekly |

</div>

---

## 🔥 **RECENT PROJECTS & EXPLOITS**

### 🎯 **WEB APPLICATION SECURITY**

<table>
<tr>
<td width="50%">

#### 🕷️ **Vulnerable Web App Scanner**
```bash
#!/bin/bash
# Custom vulnerability scanner
target=$1
echo "[+] Starting scan on $target"
nmap -sV --script vuln $target
gobuster dir -u $target -w /usr/share/wordlists/dirb/common.txt
```
**Stack:** `Python` • `Bash` • `Nmap` • `Custom Scripts`
**Features:** Automated scanning, Custom payloads, Report generation

</td>
<td width="50%">

#### 🔍 **OSINT Automation Tool** 
```python
import requests
import json
from shodan import Shodan

class OSINTFramework:
    def __init__(self, target):
        self.target = target
    
    def scan_subdomains(self):
        # Subdomain enumeration logic
        pass
```
**Stack:** `Python` • `APIs` • `Web Scraping`
**Features:** Domain intel, Social media analysis, Dark web monitoring

</td>
</tr>
</table>

### 🏢 **PROFESSIONAL DEVELOPMENT PROJECTS**

<div align="center">

| **Project** | **Type** | **Security Focus** | **Status** |
|:---|:---:|:---|:---:|
| **🎬 EH Film** | Media Platform | XSS Prevention, Input Validation | [Live](https://ehfilm.vercel.app/) |
| **📖 Al-Quran Digital** | Religious App | Secure API Integration, Data Protection | [Live](https://al-ikhsan-digital-quran.vercel.app/) |
| **☁️ Negantara Cloud** | Cloud Services | Infrastructure Security, Access Control | [Live](https://negantara-cloud.vercel.app/) |
| **🏠 EHF Residence** | Real Estate | SQL Injection Prevention, Session Security | [Live](https://ehf-residence.vercel.app/) |

</div>

---

## 📊 **GITHUB INTELLIGENCE**

<div align="center">

### 🔥 **DEVELOPMENT METRICS**

<img src="https://github-readme-stats.vercel.app/api?username=dhiljaa&show_icons=true&theme=chartreuse-dark&include_all_commits=true&count_private=true&hide_border=true" alt="GitHub Stats" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=dhiljaa&theme=chartreuse-dark&hide_border=true" alt="GitHub Streak" width="49%"/>

### 🎯 **CODE ANALYSIS**

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dhiljaa&layout=compact&theme=chartreuse-dark&hide_border=true" alt="Top Languages" width="49%"/>
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=dhiljaa&theme=chartreuse_dark" alt="Repos per Language" width="49%"/>

### 🏆 **ACHIEVEMENTS UNLOCKED**

<img src="https://github-profile-trophy.vercel.app/?username=dhiljaa&theme=matrix&no-frame=true&no-bg=true&margin-w=4&row=1&column=7" alt="GitHub Trophies"/>

</div>

---

## 🌐 **SECURE COMMUNICATION CHANNELS**

<div align="center">

### 📡 **PROFESSIONAL NETWORKS**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-fadhil-3594672a4/)
[![Portfolio](https://img.shields.io/badge/Portfolio-00FF41?style=for-the-badge&logo=google-chrome&logoColor=black)](https://ehfcreative.xyz/)
[![Email](https://img.shields.io/badge/ProtonMail-8B89CC?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:ahmadfadhil289@gmail.com)

### 🎨 **CONTENT CHANNELS**

[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://www.tiktok.com/@ehfcreative)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@ehfcreative)
[![Dev.to](https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=dev.to&logoColor=white)](https://dev.to/dhiljaa)

### 🔒 **SECURE CHANNELS**

[![Signal](https://img.shields.io/badge/Signal-3A76F0?style=for-the-badge&logo=signal&logoColor=white)](#)
[![Keybase](https://img.shields.io/badge/Keybase-33A0FF?style=for-the-badge&logo=keybase&logoColor=white)](#)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](#)

</div>

---

## 🎭 **ETHICAL HACKER'S CREED**

<div align="center">

```ascii
╔══════════════════════════════════════════════════════════════════╗
║                                                                  ║
║  "I am a guardian of the digital realm. I use my skills to       ║
║   protect, not to harm. I seek knowledge to strengthen           ║
║   defenses, not to exploit vulnerabilities for personal gain.    ║
║   I am committed to ethical practices, responsible disclosure,    ║
║   and making the internet a safer place for everyone."           ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
```

### 🎯 **MISSION STATEMENT**

> *Building secure applications by day, hunting vulnerabilities by night.*
> 
> *Always learning, always improving, always ethical.*

</div>

---

<div align="center">

```bash
┌──(root㉿kali)-[~/portfolio]
└─$ echo "Thanks for visiting my digital fortress!"
Thanks for visiting my digital fortress!

┌──(root㉿kali)-[~/portfolio]  
└─$ exit
logout
```

![Profile Views](https://komarev.com/ghpvc/?username=dhiljaa&color=brightgreen&style=for-the-badge&label=RECONNAISSANCE+COUNT)
[![GitHub followers](https://img.shields.io/github/followers/dhiljaa?style=for-the-badge&color=brightgreen&label=DIGITAL+ALLIES)](https://github.com/dhiljaa?tab=followers)

**⚡ Remember: With great power comes great responsibility ⚡**

</div>
