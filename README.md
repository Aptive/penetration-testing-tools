# Penetration Testing Tools

One handy repo containing all the latest bleeding edge [penetration testing](https://www.aptive.co.uk/penetration-testing/) tools, if you want a tool added to this repo - I accept push requests or you can leave me a comment and I'll add it. 

I appreciate Kali Linux has most of the penetration testing tools available within this repo, however I often have a subset of pen testing tools that live under **~/Tools** used in addition for bleeding edge version or tools that have not yest found their way into Kali.   

## Installation 

git clone https://github.com/Arr0way/penetration-testing-tools.git

## Included Penetration Testing Tools

### ssl-testing-tools

* [testssl](/drwetter/testssl.sh) - ssl testing

### infra

* [Metasploit Framework](/rapid7/metasploit-framework) - metasploit framework
https://github.com/rofl0r/proxychains-ng.git - pivoting
git submodule add https://github.com/breenmachine/dnsftp.git - Use only DNS queries to download a file, and then execute it
git submodule add https://github.com/sensepost/reGeorg.git - pivoting via socks proxies
git submodule add https://github.com/mandatoryprogrammer/sonar.js.git - A framework for identifying and launching exploits against internal network hosts.
git submodule add https://github.com/nmap/nmap.git - NMAP the network mapper
git submodule add https://github.com/commonexploits/port-scan-automation.git - Automate NMAP scans and custom Nessus polices.

shells

git submodule add https://github.com/NetSPI/cmdsql.git - Command execution, web.config parsing, and SQL query execution
git submodule add https://github.com/BlackArch/webshells.git - web shells
git submodule add https://github.com/b374k/b374k.git - web shell
git submodule add https://github.com/infodox/python-pty-shells.git - python pty shells
git submodule add https://github.com/xillwillx/MiniReverse_Shell_With_Parameters.git - mini reverse shell

wordlists

git submodule add https://github.com/fuzzdb-project/fuzzdb.git - wordlist
git submodule add https://github.com/danielmiessler/SecLists.git - wordlist

web-app-pen-testing-tools

git submodule add https://github.com/sqlmapproject/sqlmap.git - sql injection automation
git submodule add https://github.com/sandrogauci/wafw00f.git - identify and fingerprint Web Application Firewall (WAF)
git submodule add https://github.com/inquisb/icmpsh.git - Simple reverse ICMP shell
git submodule add https://github.com/anestisb/WeBaCoo.git - Web Backdoor Cookie Script-Kit
git submodule add https://github.com/stasinopoulos/commix.git - Commix, automated injection based web vulnerability scanner
git submodule add https://github.com/jekyc/wig.git  - WebApp Information Gatherer
git submodule add https://github.com/Dionach/CMSmap.git - CMS vulnerability scanner
git submodule add https://github.com/droope/droopescan.git - A CMS vulnerability scanner for Drupal, Wordpress, SilverStripe
git submodule add https://github.com/wpscanteam/wpscan.git - WPScan is a black box WordPress vulnerability scanner

source-code-audit

git submodule add https://github.com/wireghoul/graudit.git - simple script and signature sets that allows you to find potential
security flaws in source code using grep

bruteforce

git submodule add https://github.com/lanjelot/patator.git - Patator is a multi-purpose brute-forcer
git submodule add https://github.com/galkan/crowbar.git - Bruteforcer - supports protocols not supported by THC-Hydra

windows

git submodule add https://github.com/Vozzie/uacscript.git - UAC Bypass Vulnerability in Windows Script Host

powershell

git submodule add https://github.com/jseidl/Babadook.git - Connection-less Powershell Persistent and Resilient Backdoor
https://github.com/PowerShellEmpire/Empire - Empire is a pure PowerShell post-exploitation agent

rootkit

git submodule add https://github.com/chokepoint/azazel.git - Azazel is a userland rootkit based off of the original LD_PRELOAD technique from Jynx rootkit

misc

git submodule add https://github.com/nullmode/gnmap-parser.git - Gnmap-Parser takes multiple Nmap scans exported in greppable (.gnmap) format and parses them into various types of plain-text files for easy analysis.
git submodule add https://github.com/nullsecuritynet/tools.git - security and hacking tools, exploits, proof of concepts, shellcodes, scripts

scripting

git submodule add https://github.com/attackdebris/babel-sf.git - Babel Scripting Framework - a collection of custom scripts to facilitate useful pentest related functions via scripting languages

exploit-dev

git submodule add https://github.com/longld/peda.git - PEDA - Python Exploit Development Assistance for GDB
git submodule add https://github.com/packz/ropeme.git - ROPEME - ROP Exploit Made Easy
git submodule add https://github.com/sashs/Ropper.git - ROP tool
git submodule add https://github.com/hasherezade/shellconv.git - Small tool for disassembling shellcode (using objdump)
git submodule add https://github.com/Gallopsled/pwntools.git - CTF framework and exploit development library
