# Penetration Testing Tools Repo

The purpose of this project is to make a single repository for all the commonly used penetration testing tools, typically tools that don't exist within Kali or other penetration testing distros. In some cases, it makes sense to have the latest version of a tool separate to your distro installed stable binaries or scripts. Installing from GitHub allows you to grab the latest tools specific to your style of pen testing, tools that could be too niche to ever make it into your favorite security distro. Additionally, a seperate self-contained tool set within your home directory or /opt also allows for easy transportation from one (identical) machine to another.

## Installation Instructions

1. Fork repo (allows you to make changes to your tools and or push to this repo) 
2. Git clone repo: 
```bash
git clone --recursive https://github.com/Aptive/penetration-testing-tools.git
``` 

For some tools further installation will be required, e.g. building binaries / installing configuring tools to suit your requirements, below are links to each distro managers page with installation instructions for each.

## Update Instructions 

### Update a single tool 

The following example uses nmap:

```bash
cd penetration-testing-tools/infra/nmap/
git pull
```

### Update all the pen test tools 

```bash
cd penetration-testing-tools/
git submodule foreach git pull
```

## Contributing to the repo 

To contribute, send a pull request.

## Included Penetration Testing Tools

### SSL Testing Tools

Location: [/ssl-testing-tools](/ssl-testing-tools) 

* [testssl](https://github.com/drwetter/testssl.sh) - ssl testing

### Infrastructure Pen Testing Tools

Location: [/infra](/infra) 

Intrastructure pen testing tools: 

* [Metasploit Framework](https://github.com/rapid7/metasploit-framework) - metasploit framework
* [Responder](https://github.com/SpiderLabs/Responder) - LLMNR and NBT-NS Poisoning - capture passwords from typo'd smb \\server-addresses on the network
* [proxychains-ng](https://github.com/rofl0r/proxychains-ng) - pivoting
* [Net-creds](https://github.com/DanMcInerney/net-creds) - Sniffs sensitive data from interface or pcap
* [smbexec](https://github.com/pentestgeek/smbexec) - A rapid psexec style attack with samba tools
* [dnsftp](https://github.com/breenmachine/dnsftp.git) - Use only DNS queries to download a file, and then execute it
* [reGeorg](https://github.com/sensepost/reGeorg) - pivoting via socks proxies
* [sonar.js](https://github.com/mandatoryprogrammer/sonar.js.git) - A framework for identifying and launching exploits against internal network hosts
* [sonar.js](https://github.com/mandatoryprogrammer/sonar.js) -  A framework for identifying and launching exploits against internal network hosts.
* [The Backdoor Factory](https://github.com/secretsquirrel/the-backdoor-factory) -  Patch PE, ELF, Mach-O binaries with shellcode - backdoor binaries so they continue to work normally
* [NMAP](https://github.com/nmap/nmap.git) - NMAP the network mapper
* [Port Scan Automation](https://github.com/commonexploits/port-scan-automation.git) - Automate NMAP scans and custom Nessus polices.

### Redteam 

Location: [/redteam](/redteam)

* [Veil Framework](https://github.com/Veil-Framework/Veil) - a red team toolkit focused on evading detection (AV evasion & target delivery) 
* [Phising Frenzy](https://github.com/pentestgeek/phishing-frenzy) - Ruby on Rails Phishing Framework

### Recon 

Location: [/recon](/recon) 

* [EyeWitness](https://github.com/ChrisTruncer/EyeWitness) - Take screenshots of websites, provide some server header info, and identify default credentials if possible
* [Gitrob](https://github.com/michenriksen/gitrob) - Helps security professionals find sensitive information lingering in publicly available files on GitHub
* [recon-ng](https://github.com/open-security/recon-ng) - Recon-ng is a full-featured Web Reconnaissance framework written in Python.
* [SpiderFoot](https://github.com/smicallef/spiderfoot) - open source footprinting and intelligence-gathering tool.
* [SimplyEmail](https://github.com/killswitch-GUI/SimplyEmail) - Email recon
  made fast and easy

### Shells 

Location: [/shells](/shells) 

* [cmdsql](https://github.com/NetSPI/cmdsql) - Command execution, web.config parsing, and SQL query execution
* [BlackArch Webshells](https://github.com/BlackArch/webshells) - BlackArch web shells
* [b374k](https://github.com/b374k/b374k) - Web shell
* [Python PTY Shells](https://github.com/infodox/python-pty-shells) - python pty shells
* [MiniReverse Shell](https://github.com/xillwillx/MiniReverse_Shell_With_Parameters) - mini reverse shell

### Wordlists

Location: [/wordlists](/wordlists) 

* [FuzzDB](https://github.com/fuzzdb-project/fuzzdb) - wordlist
* [SecLists](https://github.com/danielmiessler/SecLists) - wordlist

### Web App Penetration testing Tools

Location: [/web-app](/web-app) 

* [SQLMap](https://github.com/sqlmapproject/sqlmap) - sql injection automation
* [WafW00f](https://github.com/sandrogauci/wafw00f) - identify and fingerprint Web Application Firewall (WAF)
* [ICMP Reverse Shell](https://github.com/inquisb/icmpsh) - Simple reverse ICMP shell
* [WeBaCoo](https://github.com/anestisb/WeBaCoo) - Web Backdoor Cookie Script-Kit
* [Commix](https://github.com/stasinopoulos/commix) - Commix, automated injection based web vulnerability scanner
* [WIG](https://github.com/jekyc/wig)  - WebApp Information Gatherer
* [CMSmap](https://github.com/Dionach/CMSmap) - CMS vulnerability scanner
* [Droop Scan](https://github.com/droope/droopescan) - A CMS vulnerability scanner for Drupal, Wordpress, SilverStripe
* [WPScan](https://github.com/wpscanteam/wpscan) - WPScan is a black box WordPress vulnerability scanner
* [NoSQLMap](https://github.com/tcstool/NoSQLMap) - Automated Mongo database and NoSQL web application exploitation tool
* [HTTPScreenShot](https://github.com/breenmachine/httpscreenshot) - HTTPScreenshot is a tool for grabbing screenshots and HTML of large numbers of websites

### Source Code Audit

SAST - SCR - Static Analysis 

Location: [/source-code-audit](/source-code-audit) 

* [grAudit](https://github.com/wireghoul/graudit) - simple script and signature sets that allows you to find potential
security flaws in source code using grep
* [Brakeman](https://github.com/presidentbeef/brakeman) - A static analysis security vulnerability scanner for Ruby on Rails applications 

### Bruteforce Tools

Location: [/bruteforce](/bruteforce) 

* [Pator](https://github.com/lanjelot/patator) - Patator is a multi-purpose brute-forcer
* [Crowbar](https://github.com/galkan/crowbar) - Bruteforcer - supports protocols not supported by THC-Hydra

### Windows Tools

Location: [/windows](/windows) 

* [Mimikatz](https://github.com/gentilkiwi/mimikatz) - Extract plaintexts passwords, hash, PIN code and kerberos tickets from memory. mimikatz can also perform pass-the-hash, pass-the-ticket or build Golden tickets.
* [UAC Script](https://github.com/Vozzie/uacscript) - UAC Bypass Vulnerability in Windows Script Host

### Linux Scripts 

Location: [linux](/linux) 

* [Linux Local Enumeration Script](https://github.com/Arr0way/linux-local-enumeration-script) - Linux local enumeration script 

### Powershell

Location: [/powershell](/powershell) 

* [Badadook](https://github.com/jseidl/Babadook) - Connection-less Powershell Persistent and Resilient Backdoor
* [PowerShellEmpire](https://github.com/PowerShellEmpire/Empire) - Empire is a pure PowerShell post-exploitation agent
* [PowerSploit](https://github.com/PowerShellMafia/PowerSploit) -  PowerSploit - A PowerShell Post-Exploitation Framework
* [Nishang](https://github.com/samratashok/nishang) - PowerShell for penetration testing and offensive security
* [BloodHound](https://github.com/adaptivethreat/BloodHound) - BloodHound uses
  graph theory to reveal the hidden and often unintended relationships within
  an Active Directory environment

### Rootkits

Location: [/rootkits](/rootkits) 

* [Azael](https://github.com/chokepoint/azazel) - Azazel is a userland rootkit based off of the original LD_PRELOAD technique from Jynx rootkit

### Scripting Tools

Location: [/scripting](/scripting) 

* [Babel SF](https://github.com/attackdebris/babel-sf) - Babel Scripting Framework - a collection of custom scripts to facilitate useful pentest related functions via scripting languages

### Exploit Development 

Location: [/exploit-dev](/exploit-dev) 

* [PEDA](https://github.com/longld/peda) - PEDA - Python Exploit Development Assistance for GDB
* [ROPEME](https://github.com/packz/ropeme) - ROPEME - ROP Exploit Made Easy
* [Ropper](https://github.com/sashs/Ropper) - ROP tool
* [Shellconv](https://github.com/hasherezade/shellconv) - Small tool for disassembling shellcode (using objdump)
* [PWNTools](https://github.com/Gallopsled/pwntools) - CTF framework and exploit development library

### Misc

Location: [/misc](/misc) 

* [Gnmap-Parser](https://github.com/nullmode/gnmap-parser) - Gnmap-Parser takes multiple Nmap scans exported in greppable (.gnmap) format and parses them into various types of plain-text files for easy analysis.
* [NullSecurity Tools](https://github.com/nullsecuritynet/tools) - pen testing and security tools, exploits, proof of concepts, shellcodes, scripts
