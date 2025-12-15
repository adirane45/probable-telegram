![Abstract Cybersecurity Concept](https://images.unsplash.com/photo-1550751827-4bd374c3f58b?q=80&w=1470&auto=format&fit=crop)

# Hi there, I'm Aditya Rane! 👋

### 🔐 Cybersecurity Analyst | 🎓 MCA Student

I am a dedicated **Cybersecurity Analyst** based in **Jalgaon, India** with 2+ years of experience in analyzing, defending, and securing digital infrastructures. I am passionate about protecting systems from emerging threats, participating in CTF competitions, and building resilient digital defenses.

---

### 🧐 About Me

- 🛡️ **Current Role:** Cybersecurity Analyst protecting data and preventing breaches.
- 🎓 **Education:** Master of Computer Applications (MCA).
- 🔭 **Working On:** Vulnerability analysis and robust security protocols.
- ⚡ **Interests:** Network Protocols, Cryptography, and Open Source Security Tools.
- 🌍 **Location:** Jalgaon, Maharashtra, India.
- 🌐 **Portfolio:** [justadi.dpdns.org](https://justadi.dpdns.org)
- 📫 **Contact:** [adityrane45@gmail.com](mailto:adityrane45@gmail.com)

---

### 💻 A Taste of My Code

Here is a simple Python snippet for scanning ports, essential for vulnerability assessment:

```python
import socket

target = "127.0.0.1" 

def port_scan(port):
    try:
        sock = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
        sock.settimeout(0.5)
        result = sock.connect_ex((target, port))
        if result == 0:
            print(f"[+] Port {port} is OPEN")
        sock.close()
    except:
        pass

# Scanning the first 1024 ports
for port in range(1, 1025):
    port_scan(port)
```

---

### 🛠️ Tech Stack & Tools

**Languages:**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Security & Analysis:**
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-MOD-blue?style=for-the-badge&logo=nmap&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-333333?style=for-the-badge&logo=metasploit&logoColor=white)

**Other Tools:**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=adirane45&show_icons=true&theme=radical" alt="Aditya's Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=adirane45&layout=compact&theme=radical" alt="Top Languages" />
</p>

---

### 🤝 Connect with Me

[<img align="left" alt="Website" width="22px" src="https://img.icons8.com/ios-filled/50/ffffff/internet.png" />][website]
[<img align="left" alt="LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]

[website]: https://justadi.dpdns.org
[linkedin]: https://linkedin.com/in/aditya-rane-a912004r





### 🎯 My Goals & Tasks

- [x] Learn Python Basics
- [x] Set up Kali Linux environment
- [ ] Master Network Penetration Testing
- [ ] Earn CEH (Certified Ethical Hacker) Certification
- [ ] Contribute to an Open Source Security Tool


