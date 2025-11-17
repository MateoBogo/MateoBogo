<!-- BANNIÈRE HACKING / TERMINAL -->
<p align="center">
  <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="600" alt="Coding Terminal" />
</p>

<h1 align="center">root@Mateo:~# whoami</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=00FF00&center=true&vCenter=true&lines=Fullstack+Developer;Security+Enthusiast;Breaking+Things+to+Understand+Them;Always+Learning+New+Exploits" />
</p>

---

## 🔐 Root-Me & Hacking playground

<p align="center">
  <a href="https://www.root-me.org/Mateo-674005?lang=fr#d74a6ce754bc0254cd9b5ae31a29fe19">
    <img src="https://root-me-diff.vercel.app/rm-gh?gstats=show&style=dark&nickname=Mateo-674005" alt="Root-Me Stats" />
  </a>
</p>

---

## 👨‍💻 About me

```bash
root@Mateo:~# cat profile.txt
- 🧠 Fullstack developer (specialized in cybersecurity)
- 🎓 Student
- 🧪 CTFs · Red Teaming · pentesting · AI security research
- 🎯 Goal: ship scary-good, maintainable code that survives real abuse
```

### 🛠️ Tech stack
```
Frontend : React · Next.js · TypeScript · TailwindCSS
Backend  : Node.js · Express · NestJS · REST · GraphQL
Database : PostgreSQL · MongoDB · Redis
DevOps   : Docker · CI/CD · Linux · Nginx
Security : Root-Me · CTFs · basic pentesting · Burp Suite · nmap · Wireshark
Tools    : Git · GitHub · VSCode · tmux · Neovim
```

---

## 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MateoBogo&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MateoBogo&layout=compact&theme=radical&hide_border=true" alt="Top Langs" />
</p>

---

## 🔥 Red Team Operations Log

```bash
# === RECONNAISSANCE PHASE ===
root@Mateo:~# whois target.com | grep -E "Name Server|Registrar"
root@Mateo:~# subfinder -d target.com -silent | httpx -silent
root@Mateo:~# theHarvester -d target.com -b all -f scan_results

# === OSINT GATHERING ===
root@Mateo:~# sherlock username --timeout 10
root@Mateo:~# exiftool ./leaked_document.pdf | grep -i "author\|creator"
root@Mateo:~# python3 phoneinfoga.py scan -n "+33612345678"

# === CRYPTOGRAPHY & ANALYSIS ===
root@Mateo:~# hashcat -m 1000 hashes.txt rockyou.txt --force
root@Mateo:~# john --wordlist=rockyou.txt shadow.hash
root@Mateo:~# openssl enc -aes-256-cbc -d -in encrypted.bin -out decrypted.txt

# === WEB EXPLOITATION ===
root@Mateo:~# sqlmap -u "http://target.com?id=1" --dbs --batch
root@Mateo:~# ffuf -u https://target.com/FUZZ -w wordlist.txt -mc 200,301,302
root@Mateo:~# nuclei -t cves/ -u target.com -severity critical,high

# === POST-EXPLOITATION ===
root@Mateo:~# mimikatz.exe "sekurlsa::logonpasswords" exit
root@Mateo:~# bloodhound-python -u user -p pass -d domain.local -c All
root@Mateo:~# ./linpeas.sh | tee privesc_scan.log

[+] 147 vulnerabilities detected
[+] Privilege escalation path found
[+] Credentials harvested: 23 unique hashes
[!] Mission accomplished. Securing environment...
```

<p align="center">
  <img src="https://media.giphy.com/media/077i6AULCXc0FKTj9s/giphy.gif" width="500" alt="Cybersecurity" />
</p>
