# Penetration Testing Tools

A single repo containing all the latest [pen testing](https://www.aptive.co.uk/penetration-testing/) tools. The purpose of this project is to make a single repo for all the commonly used penetration testing tools, often tools that are out of date in Kali or have not found their way into Kali (or other pen testing repos). In some cases it's nice to have a the latest version of a tool seperate to your distro installed binaries or scripts, allowing for easy transportation (from one kali machine to another).

## Installation Instructions

1. Fork repo (allows you to make changes to your tools and or push to this repo) 
2. Git clone repo: 
```bash
git clone https://github.com/Arr0way/penetration-testing-tools.git
``` 

In some cases further installation will be required, e.g. building binaries / installing configuring tools to suit your requirements. 

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

To contribute, fork the repo and send a push request. 

## Included Penetration Testing Tools

### SSL Testing Tools

Location: [/ssl-testing-tools](/ssl-testing-tools) 

* [testssl](https://github.com/drwetter/testssl.sh) - ssl testing

### Infrastructure Pen Testing Tools

Location: [/infra](/infra) 

Intrastructure pen testing tools: 

* [Metasploit Framework](https://github.com/rapid7/metasploit-framework) - metasploit framework
* [proxychains-ng](https://github.com/rofl0r/proxychains-ng) - pivoting
* [dnsftp](https://github.com/breenmachine/dnsftp.git) - Use only DNS queries to download a file, and then execute it
* [reGeorg](https://github.com/sensepost/reGeorg) - pivoting via socks proxies
* [sonar.js](https://github.com/mandatoryprogrammer/sonar.js.git) - A framework for identifying and launching exploits against internal network hosts.
* [NMAP](https://github.com/nmap/nmap.git) - NMAP the network mapper
* [Port Scan Automation](https://github.com/commonexploits/port-scan-automation.git) - Automate NMAP scans and custom Nessus polices.

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

### Source Code Audit

Location: [/source-code-audit](/source-code-audit) 

* [grAudit](https://github.com/wireghoul/graudit) - simple script and signature sets that allows you to find potential
security flaws in source code using grep

### Bruteforce Tools

Location: [/bruteforce](/bruteforce) 

* [Pator](https://github.com/lanjelot/patator) - Patator is a multi-purpose brute-forcer
* [Crowbar](https://github.com/galkan/crowbar) - Bruteforcer - supports protocols not supported by THC-Hydra

### Windows Tools

Location: [/windows](/windows) 

* [UAC Script](https://github.com/Vozzie/uacscript) - UAC Bypass Vulnerability in Windows Script Host

### Powershell

Location: [/powershell](/powershell) 

* [Badadook](https://github.com/jseidl/Babadook) - Connection-less Powershell Persistent and Resilient Backdoor
* [PowerShellEmpire](https://github.com/PowerShellEmpire/Empire) - Empire is a pure PowerShell post-exploitation agent

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
* [NullSecurity Tools](https://github.com/nullsecuritynet/tools) - security and hacking tools, exploits, proof of concepts, shellcodes, scripts
