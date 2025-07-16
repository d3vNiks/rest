# 60-Day Free Ethical Hacking Learning Path

Welcome to the **60-Day Ethical Hacking Learning Path**! This roadmap is designed for beginners who want to learn ethical hacking step-by-step with free resources. The plan includes theory, video tutorials, and hands-on labs — all achievable with just 2-3 hours per day.

---

## Why This Path?

Ethical hacking is a critical skill in cybersecurity. This path helps you build foundational knowledge and hands-on skills to become a proficient ethical hacker, using completely free and legal resources.

---

## How to Use This Roadmap?

- Study 2-3 hours daily.
- Follow the weekly topics in order.
- Watch the linked videos.
- Complete the hands-on labs and CTF challenges.
- Practice consistently and revisit tough topics.

---

## Weekly Breakdown

### Week 1-2: Networking & Operating Systems Basics
- Understand IP addresses, TCP/UDP, DNS, and ports.
- Learn the OSI Model layers.
- Basics of Windows and Linux operating systems.

**Videos:**
- [Professor Messer Network+ Playlist](https://www.youtube.com/playlist?list=PLG49S3nxzAnl_tQe3kvnmeMid0mjF8Le8)
- [TryHackMe Intro to Cybersecurity](https://tryhackme.com/room/introtoinfosec)

**Hands-on Labs:**
- [TryHackMe Intro to Networking](https://tryhackme.com/room/introtonetworking)
- Practice using Wireshark or Packet Tracer for network packet visualization.

---

### Week 3: Linux & Terminal Skills
- Master essential bash commands (`ls`, `cd`, `grep`, `chmod`, `ssh`).
- Understand file permissions and users.
- Learn basic shell scripting.

**Resources:**
- [OverTheWire Bandit Wargame](https://overthewire.org/wargames/bandit/)
- [TryHackMe Linux Fundamentals](https://tryhackme.com/room/linuxfundamentals1)

**Tools:**
- Use Kali Linux or Parrot OS VM for hands-on practice.

---

### Week 4: Reconnaissance & Scanning
- Passive and active information gathering.
- Port scanning and service detection.
- Tools: `nmap`, `whois`, `nslookup`.

**Labs:**
- [TryHackMe Nmap Room](https://tryhackme.com/room/nmap)
- [TryHackMe Intro to Networking](https://tryhackme.com/room/introtonetworking)

---

### Week 5: Web Hacking Basics
- Learn OWASP Top 10 vulnerabilities (XSS, SQL Injection, CSRF, etc.).
- Understand HTTP basics, cookies, and sessions.
- Use Burp Suite community edition.

**Practice:**
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)
- [TryHackMe OWASP Top 10 Room](https://tryhackme.com/room/owasptop10)

---

### Week 6: Exploitation & Privilege Escalation
- Exploit vulnerabilities with Metasploit and manual methods.
- Linux and Windows privilege escalation techniques.

**Labs:**
- [TryHackMe Metasploit Room](https://tryhackme.com/room/metasploit)
- [TryHackMe Linux Privilege Escalation](https://tryhackme.com/room/linuxprivesc)

---

### Week 7+: Practice with CTFs & Real-World Labs
- Join beginner-friendly CTF platforms.
- Learn from community writeups and solutions.

**CTF Platforms:**
- [TryHackMe Beginner Path](https://tryhackme.com/path/intro-to-pentesting)
- [Hack The Box Starting Point](https://www.hackthebox.com/starting-point)
- [PicoCTF](https://picoctf.org/)

---

## Bonus: Learn Python for Hacking
- [freeCodeCamp Python Full Course](https://www.youtube.com/watch?v=rfscVS0vtbw)

**Recommended Reading:**
- [The Web Application Hackers Handbook (PDF)](https://github.com/LabSEC/publications/blob/master/books/Web_Application_Hackers_Handbook_2.pdf)

---

## Tools You Should Know
- Nmap (network scanning)
- Gobuster (directory brute-forcing)
- Burp Suite (web attack proxy)
- Metasploit (exploitation framework)
- Wireshark (packet analyzer)
- LinPEAS (Linux privilege escalation script)

---

## After Mastery: What Next?
- Join bug bounty programs like [HackerOne](https://www.hackerone.com/) and [Bugcrowd](https://www.bugcrowd.com/)
- Consider certifications like CEH, OSCP, or eJPT
- Start freelancing or look for junior penetration testing roles

---

## Final Tips
- Stay consistent with daily practice.
- Participate in forums and cybersecurity communities.
- Keep up to date with the latest security news and exploits.

---

*Happy hacking and learning!*

---

*If you find this roadmap useful, feel free to ⭐ star this repo and share it with others.*

---

*





































# Learning Path to Understand & Build Your Own Hacking Tools

This roadmap guides you through the skills and knowledge needed to **understand how hacking tools work internally and create your own tools from scratch**. It covers programming, networking, OS internals, security concepts, reverse engineering, and tool development.

---

## Overview

| Step | Focus Area                       | What You Learn & Skills Gained                                    | Where to Learn (with What You Get)                  |
|-------|--------------------------------|------------------------------------------------------------------|-----------------------------------------------------|
| 1     | Programming Foundations         | Python & C basics, socket programming, multithreading, scripting | - [CS50 by Harvard](https://cs50.harvard.edu/x/2023/) (Full CS intro, programming fundamentals) <br> - [Learn Python the Hard Way](https://learnpythonthehardway.org/) (Python basics & exercises) <br> - [Beej’s Guide to Network Programming](https://beej.us/guide/bgnet/) (Sockets & networking) |
| 2     | Networking Deep Dive            | TCP/IP protocols, HTTP/HTTPS, DNS, packet structure, sniffing   | - [Computer Networking: A Top-Down Approach (Online Lectures)](https://gaia.cs.umass.edu/kurose_ross/online_lectures.htm) (Networking theory) <br> - Wireshark official tutorials ([Link](https://www.wireshark.org/docs/)) (Packet analysis) |
| 3     | Operating System Internals      | Linux & Windows OS internals, system calls, memory management    | - [Linux From Scratch](http://www.linuxfromscratch.org/) (Linux internals) <br> - [Windows Internals by Microsoft Docs](https://docs.microsoft.com/en-us/sysinternals/) (Windows architecture) |
| 4     | Security Concepts & Vulnerabilities | Buffer overflow, memory corruption, web vulnerabilities, crypto basics | - *Hacking: The Art of Exploitation* by Jon Erickson (Book - Exploitation & security) <br> - [OpenSecurityTraining.info](https://opensecuritytraining.info/) (Free security courses) |
| 5     | Reverse Engineering & Analysis | Static & dynamic analysis, binary reversing, malware analysis    | - *Practical Reverse Engineering* by Bruce Dang et al. (Book) <br> - [Ghidra Tutorials](https://ghidra-sre.org/) (Reverse engineering tool) |
| 6     | Tool Development: Networking   | Build network scanners, port scanners, custom packet tools       | - [Python Socket Programming Tutorials](https://realpython.com/python-sockets/) (Sockets & network programming) <br> - [Scapy Documentation](https://scapy.readthedocs.io/en/latest/) (Packet crafting) |
| 7     | Tool Development: Web & Proxies | Build web automation tools, proxies, browser exploit modules    | - [BeEF Project Wiki](https://github.com/beefproject/beef/wiki) (Browser Exploitation Framework) <br> - [Python Requests Library](https://realpython.com/python-requests/) (HTTP automation) <br> - [Selenium with Python](https://selenium-python.readthedocs.io/) (Browser automation) |
| 8     | Tool Development: Wireless     | Create WiFi sniffers, deauth tools, packet analyzers             | - [Aircrack-ng Documentation](https://www.aircrack-ng.org/documentation.html) (Wireless hacking tools) <br> - [Scapy Wireless Tutorials](https://scapy.readthedocs.io/en/latest/introduction.html#wifi-support) (Wireless packet manipulation) |
| 9     | Tool Development: Phishing & Social Engineering | Email sending tools, phishing proxy frameworks                    | - [Evilginx2 GitHub](https://github.com/kgretzky/evilginx2) (Phishing proxy source) <br> - [Python SMTP Tutorial](https://realpython.com/python-send-email/) (Email automation) |
| 10    | Exploitation & Automation      | Write exploit scripts, Metasploit scripting, shellcode basics    | - [Metasploit Unleashed](https://www.offensive-security.com/metasploit-unleashed/) (Free Metasploit training) <br> - [Shellcoding Tutorials](https://shell-storm.org/shellcode/) (Assembly shellcode basics) |

---

## Detailed Learning Breakdown with Where to Learn

### 1. Programming Foundations
- **What to learn:**  
  - Python syntax and basics  
  - C programming essentials  
  - Networking with sockets  
  - Multithreading and scripting basics  
- **Where to learn:**  
  - [CS50 by Harvard](https://cs50.harvard.edu/x/2023/) — Complete computer science and programming intro  
  - [Learn Python the Hard Way](https://learnpythonthehardway.org/) — Hands-on Python exercises  
  - [Beej’s Guide to Network Programming](https://beej.us/guide/bgnet/) — C socket programming tutorials  

---

### 2. Deep Networking Knowledge
- **What to learn:**  
  - TCP/IP, UDP, HTTP protocols  
  - DNS, SSL/TLS basics  
  - Packet capture and analysis  
- **Where to learn:**  
  - [Computer Networking: A Top-Down Approach (Lectures)](https://gaia.cs.umass.edu/kurose_ross/online_lectures.htm) — Excellent networking course  
  - [Wireshark Tutorials](https://www.wireshark.org/docs/) — Packet capture and analysis  

---

### 3. Operating System Internals
- **What to learn:**  
  - Linux system calls, processes, memory  
  - Windows internals and APIs  
- **Where to learn:**  
  - [Linux From Scratch](http://www.linuxfromscratch.org/) — Linux OS internals and building  
  - [Windows Internals (Sysinternals)](https://docs.microsoft.com/en-us/sysinternals/) — Windows OS deep dive  

---

### 4. Security Concepts & Vulnerabilities
- **What to learn:**  
  - Exploitation techniques (buffer overflow, etc.)  
  - Web security vulnerabilities (XSS, SQLi)  
  - Cryptography basics  
- **Where to learn:**  
  - *Hacking: The Art of Exploitation* by Jon Erickson — Classic book on exploitation  
  - [OpenSecurityTraining.info](https://opensecuritytraining.info/) — Free security courses  

---

### 5. Reverse Engineering & Malware Analysis
- **What to learn:**  
  - Disassembly and debugging  
  - Static and dynamic binary analysis  
- **Where to learn:**  
  - *Practical Reverse Engineering* (Book)  
  - [Ghidra Tutorials](https://ghidra-sre.org/) — NSA’s reverse engineering tool  

---

### 6. Tool Development: Networking
- **What to learn:**  
  - Writing network scanners and packet crafting tools  
- **Where to learn:**  
  - [Real Python Sockets Tutorial](https://realpython.com/python-sockets/)  
  - [Scapy Documentation](https://scapy.readthedocs.io/en/latest/)  

---

### 7. Tool Development: Web & Proxies
- **What to learn:**  
  - HTTP automation  
  - Writing proxy servers  
  - Browser hooking with JavaScript (BeEF)  
- **Where to learn:**  
  - [BeEF Wiki](https://github.com/beefproject/beef/wiki)  
  - [Python Requests Library](https://realpython.com/python-requests/)  
  - [Selenium with Python](https://selenium-python.readthedocs.io/)  

---

### 8. Tool Development: Wireless
- **What to learn:**  
  - WiFi packet capture and injection  
  - Writing wireless attack tools  
- **Where to learn:**  
  - [Aircrack-ng Documentation](https://www.aircrack-ng.org/documentation.html)  
  - [Scapy Wireless Support](https://scapy.readthedocs.io/en/latest/introduction.html#wifi-support)  

---

### 9. Tool Development: Phishing & Social Engineering
- **What to learn:**  
  - SMTP email sending automation  
  - Phishing proxy mechanics  
- **Where to learn:**  
  - [Evilginx2 GitHub](https://github.com/kgretzky/evilginx2)  
  - [Python SMTP Email Tutorial](https://realpython.com/python-send-email/)  

---

### 10. Exploitation & Automation
- **What to learn:**  
  - Writing Metasploit scripts and modules  
  - Shellcode creation basics  
- **Where to learn:**  
  - [Metasploit Unleashed](https://www.offensive-security.com/metasploit-unleashed/)  
  - [Shell-Storm Shellcode Database & Tutorials](https://shell-storm.org/shellcode/)  

---

## Final Notes

- **Prerequisites:** Basic programming knowledge and understanding of ethical hacking concepts.  
- **Practice:** Always use labs and legal environments to test your code and tools.  
- **Progress:** Start simple, then build complex multi-functional tools as you learn.

---

*If this roadmap helps you, please ⭐ star the repo and share with friends!*

*Created by [Your Name]*  
*Contact: your.email@example.com*  
