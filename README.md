# hacking-tools

A comprehensive collection of cybersecurity utility tools for penetration testing, vulnerability assessment, security research, and defensive operations.

---

## Table of Contents

- [Information Gathering (Reconnaissance)](#information-gathering-reconnaissance)
- [Vulnerability Analysis](#vulnerability-analysis)
- [Exploitation Frameworks](#exploitation-frameworks)
- [Web Application Testing](#web-application-testing)
- [Network Analysis & Sniffing](#network-analysis--sniffing)
- [Password Attacks](#password-attacks)
- [Wireless Attacks](#wireless-attacks)
- [Bluetooth & RFID Attacks](#bluetooth--rfid-attacks)
- [Reverse Engineering](#reverse-engineering)
- [Forensics](#forensics)
- [Post-Exploitation](#post-exploitation)
- [Command & Control (C2) Frameworks](#command--control-c2-frameworks)
- [Mobile Security Testing](#mobile-security-testing)
- [Malware Analysis](#malware-analysis)
- [OSINT (Open Source Intelligence)](#osint-open-source-intelligence)
- [Anonymity & Privacy](#anonymity--privacy)
- [Social Engineering](#social-engineering)
- [Fuzzing Tools](#fuzzing-tools)
- [Cloud Security](#cloud-security)
- [IoT & Hardware Security](#iot--hardware-security)
- [DDoS Testing](#ddos-testing)
- [Steganography](#steganography)
- [Database Security](#database-security)
- [Windows & Active Directory](#windows--active-directory)
- [Docker & Container Security](#docker--container-security)
- [Reporting & Collaboration](#reporting--collaboration)

---

## Information Gathering (Reconnaissance)

Tools used to collect initial information about a target.

| Tool | Description |
|------|-------------|
| [**Nmap**](https://nmap.org) | Network discovery and security scanning |
| [**Masscan**](https://github.com/robertdavidgraham/masscan) | Asynchronous TCP port scanner |
| [**Zmap**](https://zmap.io) | Internet-wide network scanner |
| [**RustScan**](https://github.com/RustScan/RustScan) | Blazing-fast port scanner with service discovery |
| [**Unicornscan**](https://github.com/dankamongmen/unicornscan) | Asynchronous TCP/UDP scan engine |
| [**Netcat (nc)**](https://nc110.sourceforge.io) | Networking utility for reading/writing network connections |
| [**Socat**](http://www.dest-unreach.org/socat) | Multipurpose relay tool for bidirectional data transfer |
| [**dnsrecon**](https://github.com/darkoperator/dnsrecon) | DNS enumeration script |
| [**dnsenum**](https://github.com/fwaeytens/dnsenum) | Multi-threaded DNS enumeration |
| [**fierce**](https://github.com/mschwager/fierce) | DNS reconnaissance tool |
| [**theHarvester**](https://github.com/laramies/theHarvester) | Email, subdomain, and name enumeration |
| [**Recon-ng**](https://github.com/lanmaster53/recon-ng) | Full-featured reconnaissance framework |
| [**Amass**](https://github.com/owasp-amass/amass) | Subdomain discovery and network mapping |
| [**Sublist3r**](https://github.com/aboul3la/Sublist3r) | Fast subdomain enumeration |
| [**Subfinder**](https://github.com/projectdiscovery/subfinder) | Subdomain discovery tool |
| [**Findomain**](https://github.com/Findomain/Findomain) | Cross-platform subdomain enumerator |
| [**Shodan**](https://www.shodan.io) | Search engine for internet-connected devices |
| [**Censys**](https://censys.io) | Internet asset discovery and monitoring |
| [**Whois**](https://github.com/rfc1036/whois) | Domain registration information lookup |
| [**Dig**](https://www.isc.org/bind) | DNS lookup utility |
| [**Nslookup**](https://www.isc.org/bind) | Name server lookup tool |
| [**Aquatone**](https://github.com/michenriksen/aquatone) | Visual inspection of websites across subdomains |
| [**EyeWitness**](https://github.com/FortyNorthSecurity/EyeWitness) | Screenshot capture of web services |
| [**gowitness**](https://github.com/sensepost/gowitness) | Web screenshot utility in Go |
| [**httpx**](https://github.com/projectdiscovery/httpx) | HTTP probing toolkit |
| [**Httprobe**](https://github.com/tomnomnom/httprobe) | Probe for working HTTP/HTTPS URLs |
| [**whatweb**](https://github.com/urbanadventurer/WhatWeb) | Website technology fingerprinting |
| [**Wappalyzer**](https://www.wappalyzer.com) | Cross-platform technology profiler |
| [**BuiltWith**](https://builtwith.com) | Website technology lookup |
| [**WAFW00F**](https://github.com/EnableSecurity/wafw00f) | Web application firewall fingerprinting |
| [**Netcraft**](https://www.netcraft.com) | Web server and hosting provider detection |
| [**Traceroute**](https://linux.die.net/man/8/traceroute) | Network path discovery |
| [**MTR**](https://www.bitwizard.nl/mtr) | Network diagnostic tool combining traceroute and ping |
| [**XProbe**](https://github.com/pat0n/xprobe2) | Active OS fingerprinting tool |
| [**p0f**](https://github.com/p0f/p0f) | Passive OS fingerprinting |
| [**SMBMap**](https://github.com/ShawnDEvans/smbmap) | SMB share enumeration |
| [**enum4linux**](https://github.com/portcullislabs/enum4linux) | Windows/SMB enumeration tool |
| [**nbtscan**](https://github.com/lifenjoiner/nbtscan) | NetBIOS name scanner |
| [**Ostorobako**](https://github.com/bitbrute/ostorobako) | Information gathering via OSINT |
| [**CloudEnum**](https://github.com/initstring/cloud_enum) | Cloud service enumeration |
| [**CDNStrip**](https://github.com/jaykali/cdnstrip) | CDN detection and bypass tool |

---

## Vulnerability Analysis

Tools for scanning and identifying vulnerabilities.

| Tool | Description |
|------|-------------|
| [**Nessus**](https://www.tenable.com/products/nessus) | Industry-standard vulnerability scanner |
| [**OpenVAS**](https://www.greenbone.net) | Open-source vulnerability assessment system |
| [**Nexpose**](https://www.rapid7.com/products/nexpose) | Vulnerability management framework (Rapid7) |
| [**Qualys**](https://www.qualys.com) | Cloud-based vulnerability management |
| [**Nikto**](https://github.com/sullo/nikto) | Web server vulnerability scanner |
| [**WPScan**](https://wpscan.com) | WordPress vulnerability scanner |
| [**JoomScan**](https://github.com/OWASP/joomscan) | Joomla vulnerability scanner |
| [**Droopescan**](https://github.com/droope/droopescan) | Drupal vulnerability scanner |
| [**Vuls**](https://github.com/future-architect/vuls) | Agentless vulnerability scanner for Linux/FreeBSD |
| [**Trivy**](https://github.com/aquasecurity/trivy) | Comprehensive vulnerability scanner for containers |
| [**Grype**](https://github.com/anchore/grype) | Container and filesystem vulnerability scanner |
| [**Snyk**](https://snyk.io) | Developer-first vulnerability scanning |
| [**Clair**](https://github.com/quay/clair) | Container vulnerability analysis |
| [**Lynis**](https://cisofy.com/lynis) | Security auditing tool for Linux/Unix |
| [**Tiger**](https://www.nongnu.org/tiger) | Security audit tool for Unix |
| [**CIS-CAT**](https://www.cisecurity.org/cybersecurity-tools/cis-cat-pro) | CIS benchmark assessment tool |
| [**Skipfish**](https://github.com/spinkham/skipfish) | Active web application security scanner |
| [**Arachni**](https://github.com/Arachni/arachni) | Web application security scanner framework |
| [**W3AF**](https://github.com/andresriancho/w3af) | Web application attack and audit framework |
| [**Acunetix**](https://www.acunetix.com) | Automated web vulnerability scanner |
| [**AppScan**](https://www.hcltechsw.com/appscan) | Dynamic application security testing (HCL) |
| [**Burp Suite Pro Scanner**](https://portswigger.net/burp/pro) | Integrated vulnerability scanner |
| [**ZAP**](https://www.zaproxy.org) | Zed Attack Proxy - web application scanner |
| [**BlackDuck**](https://www.blackducksoftware.com) | Open-source dependency vulnerability scanner |
| [**Dependency-Check**](https://owasp.org/www-project-dependency-check) | OWASP dependency vulnerability scanner |
| [**Safety**](https://github.com/pyupio/safety) | Python dependency vulnerability scanner |
| [**Retire.js**](https://retirejs.github.io/retire.js) | JavaScript library vulnerability scanner |
| [**Nuclei**](https://github.com/projectdiscovery/nuclei) | Fast, template-based vulnerability scanner |
| [**PoC-in-GitHub**](https://github.com/nomi-sec/PoC-in-GitHub) | Collection of proof-of-concept exploits |

---

## Exploitation Frameworks

Frameworks designed to develop and execute exploits.

| Tool | Description |
|------|-------------|
| [**Metasploit Framework**](https://www.metasploit.com) | Premier exploitation framework (Rapid7) |
| [**Core Impact**](https://www.coresecurity.com/core-impact) | Commercial penetration testing framework |
| [**Canvas**](https://www.immunityinc.com/products/canvas) | Commercial exploitation framework (Immunity) |
| [**Cobalt Strike**](https://www.cobaltstrike.com) | Adversary simulation and threat emulation |
| [**Brute Ratel C4**](https://bruteratel.com) | Adversary simulation and red team tool |
| [**Sliver**](https://github.com/BishopFox/sliver) | Adversary emulation framework |
| [**Empire**](https://github.com/BC-SECURITY/Empire) | Post-exploitation framework (PowerShell) |
| [**Starkiller**](https://github.com/BC-SECURITY/Starkiller) | Frontend for Covenant C2 |
| [**Covenant**](https://github.com/cobbr/Covenant) | .NET C2 framework |
| [**BeEF**](https://beefproject.com) | Browser Exploitation Framework |
| [**RouterSploit**](https://github.com/threat9/routersploit) | Router exploitation framework |
| [**HackTheBox Exploit**](https://www.hackthebox.com) | Exploit development and execution |
| [**SearchSploit**](https://www.exploit-db.com/searchsploit) | Local Exploit-DB search tool |
| [**Exploit-DB**](https://www.exploit-db.com) | Public exploit repository (Offensive Security) |
| [**Rapid7 Exploit DB**](https://www.rapid7.com/db) | Comprehensive exploit database |
| [**PwnKit**](https://github.com/ly4k/PwnKit) | Local privilege escalation exploit collection |
| [**Linux Exploit Suggester**](https://github.com/mzet-/linux-exploit-suggester) | Kernel exploit suggestion tool |
| [**Windows Exploit Suggester**](https://github.com/AonCyberLabs/Windows-Exploit-Suggester) | Windows kernel exploit suggestion |
| [**PEASS-ng**](https://github.com/peass-ng/PEASS-ng) | Privilege escalation awesome scripts suite |
| [**LinPEAS**](https://github.com/peass-ng/PEASS-ng/tree/master/linPEAS) | Linux privilege escalation auditing |
| [**WinPEAS**](https://github.com/peass-ng/PEASS-ng/tree/master/winPEAS) | Windows privilege escalation auditing |

---

## Web Application Testing

Tools for testing web application security.

| Tool | Description |
|------|-------------|
| [**Burp Suite**](https://portswigger.net/burp) | Web application security testing proxy |
| [**OWASP ZAP**](https://www.zaproxy.org) | Open-source web app scanner and proxy |
| [**SQLMap**](https://sqlmap.org) | Automated SQL injection tool |
| [**NoSQLMap**](https://github.com/codingo/NoSQLMap) | NoSQL injection and exploitation |
| [**XSSer**](https://github.com/epsylon/xsser) | Cross-site scripting detection and exploitation |
| [**XSStrike**](https://github.com/s0md3v/XSStrike) | Advanced XSS detection and exploitation |
| [**Commix**](https://github.com/commixproject/commix) | Command injection exploitation |
| [**LFISuite**](https://github.com/D35m0nd142/LFISuite) | Local file inclusion exploitation |
| [**tplmap**](https://github.com/epinna/tplmap) | Server-side template injection exploitation |
| [**Jinja2 SSTI**](https://github.com/vladko312/SSTImap) | Jinja2 template injection exploitation |
| [**Dirb**](https://github.com/v0s/dirb) | Web directory scanner |
| [**Dirbuster**](https://github.com/KajanM/DirBuster) | Directory brute-forcing tool (OWASP) |
| [**Gobuster**](https://github.com/OJ/gobuster) | Directory/file/DNS/VHost brute-forcing |
| [**Dirsearch**](https://github.com/maurosoria/dirsearch) | Web directory scanner |
| [**FFUF**](https://github.com/ffuf/ffuf) | Fastest web fuzzer |
| [**wfuzz**](https://github.com/xmendez/wfuzz) | Web application bruteforcer |
| [**Hydra**](https://github.com/vanhauser-thc/thc-hydra) | Network login cracker |
| [**Patator**](https://github.com/lanjelot/patator) | Multi-purpose bruteforcer |
| [**Medusa**](https://github.com/jmk-foofus/medusa) | Parallel network login auditor |
| [**Cewl**](https://github.com/digininja/CeWL) | Custom wordlist generator |
| [**John the Ripper**](https://www.openwall.com/john) | Password security auditing |
| [**Hashcat**](https://hashcat.net/hashcat) | Advanced password recovery |
| [**CrackStation**](https://crackstation.net) | Password hash cracking service |
| [**JWT_Tool**](https://github.com/ticarpi/jwt_tool) | JSON Web Token attack toolkit |
| [**JWT Cracker**](https://github.com/lmammino/jwt-cracker) | JWT signing key brute-force |
| [**JWT_Payload**](https://github.com/ticarpi/jwt_tool) | JWT payload manipulation |
| [**CSRFTester**](https://owasp.org/www-project-csrftester) | Cross-site request forgery testing (OWASP) |
| [**CSP Evaluator**](https://csp-evaluator.withgoogle.com) | Content Security Policy evaluation |
| [**CORS Scanner**](https://github.com/tomnomnom/hacks/tree/master/cors-scanner) | Cross-origin resource sharing scanner |
| [**OpenRedireX**](https://github.com/devanshbatham/openredirex) | Open redirect vulnerability scanner |
| [**SSRFmap**](https://github.com/swisskyrepo/SSRFmap) | Server-side request forgery exploitation |
| [**Gopherus**](https://github.com/tarunkant/Gopherus) | SSRF exploitation via Gopher protocol |
| [**S3Scanner**](https://github.com/sa7mon/S3Scanner) | Amazon S3 bucket enumeration |
| [**Bucket Stream**](https://github.com/eth0izzle/bucket-stream) | S3 bucket discovery and enumeration |
| [**AWSBucketDump**](https://github.com/jordanpotti/AWSBucketDump) | AWS S3 bucket discovery |
| [**GraphQLmap**](https://github.com/swisskyrepo/GraphQLmap) | GraphQL vulnerability testing |
| [**InQL**](https://github.com/doyensec/inql) | GraphQL security testing (intrusive) |
| [**SwaggerSpy**](https://github.com/UndeadSec/SwaggerSpy) | Swagger/OpenAPI endpoint discovery |

---

## Network Analysis & Sniffing

Tools for capturing and analyzing network traffic.

| Tool | Description |
|------|-------------|
| [**Wireshark**](https://www.wireshark.org) | Network protocol analyzer |
| [**TShark**](https://www.wireshark.org/docs/man-pages/tshark.html) | CLI network protocol analyzer |
| [**tcpdump**](https://www.tcpdump.org) | Packet capture and analysis |
| [**Tcpick**](https://github.com/iphelix/tcpick) | TCP stream reassembly |
| [**Ngrep**](https://github.com/jpr5/ngrep) | Network grep - packet matching |
| [**BetterCAP**](https://www.bettercap.org) | MITM framework and network monitor |
| [**Ettercap**](https://www.ettercap-project.org) | Comprehensive MITM framework |
| [**Cain & Abel**](https://oxid.it/cain.html) | Password recovery and sniffing (Windows) |
| [**Responder**](https://github.com/lgandx/Responder) | LLMNR/NBT-NS/mDNS poisoning |
| [**Inveigh**](https://github.com/Kevin-Robertson/Inveigh) | Windows LLMNR/NBNS/mDNS/DNS spoofing |
| [**MITMf**](https://github.com/byt3bl33d3r/MITMf) | Man-in-the-middle framework |
| [**MITMProxy**](https://mitmproxy.org) | Interactive HTTPS proxy |
| [**sslstrip**](https://github.com/moxie0/sslstrip) | HTTPS stripping attack tool |
| [**SSLsplit**](https://github.com/droe/sslsplit) | SSL/TLS interception and MITM |
| [**Dsniff**](https://github.com/da-439/dsniff) | Collection of network auditing tools |
| [**Arpspoof**](https://github.com/sam-github/dsniff) | ARP spoofing utility |
| [**Macof**](https://github.com/robertdavidgraham/macof) | MAC flooding tool |
| [**Yersinia**](https://github.com/tomac/yersinia) | Layer 2 attack framework |
| [**Scapy**](https://scapy.net) | Packet manipulation library |
| [**Hping3**](https://github.com/antirez/hping) | Network packet crafting and analysis |
| [**Nemesis**](https://github.com/troglobit/nemesis) | Packet injection tool |
| [**Packit**](https://github.com/reset/packit) | Network packet generator |
| [**NetFlow Analyzer**](https://www.manageengine.com/netflow) | Network traffic analysis |
| [**nTop**](https://www.ntop.org) | Network traffic monitoring |
| [**Bro/Zeek**](https://zeek.org) | Network security monitoring framework |
| [**Suricata**](https://suricata.io) | Network threat detection engine |
| [**Snort**](https://www.snort.org) | Network intrusion detection/prevention |
| [**Moloch/Arkime**](https://arkime.com) | Large-scale PCAP indexing and search |
| [**ChaosReader**](https://github.com/chaosreader/chaosreader) | PCAP session reconstruction |
| [**NetworkMiner**](https://www.netresec.com/?page=NetworkMiner) | Network forensic analysis |
| [**PRTG**](https://www.paessler.com/prtg) | Network monitoring and bandwidth analysis |
| [**Zabbix**](https://www.zabbix.com) | Enterprise network monitoring |

---

## Password Attacks

Tools for password cracking, recovery, and authentication testing.

| Tool | Description |
|------|-------------|
| [**Hashcat**](https://hashcat.net/hashcat) | World's fastest password cracker |
| [**John the Ripper**](https://www.openwall.com/john) | Password security auditing tool |
| [**Johnny**](https://github.com/reimashi/johnny) | GUI for John the Ripper |
| [**Hash-Identifier**](https://github.com/psypanda/hashID) | Hash type identification |
| [**HashID**](https://github.com/psypanda/hashID) | Hash algorithm identification |
| [**ophcrack**](https://ophcrack.sourceforge.io) | Windows password cracker using LM/NTLM |
| [**chntpw**](https://github.com/Tody-Guo/chntpw) | Windows registry password reset utility |
| [**SamInside**](https://www.insidepro.com) | Windows password recovery |
| [**L0phtCrack**](https://www.l0phtcrack.com) | Windows password auditing |
| [**CrackMapExec**](https://github.com/Porchetta-Industries/CrackMapExec) | Post-exploitation password testing |
| [**Hydra**](https://github.com/vanhauser-thc/thc-hydra) | Parallel network login cracker |
| [**Medusa**](https://github.com/jmk-foofus/medusa) | Parallel network login auditor |
| [**NCrack**](https://nmap.org/ncrack) | Network authentication cracking |
| [**Patator**](https://github.com/lanjelot/patator) | Multi-service bruteforce tool |
| [**CeWL**](https://github.com/digininja/CeWL) | Custom wordlist generator by crawling |
| [**Crunch**](https://github.com/crunchsec/crunch) | Wordlist generator |
| [**WordlistCtrl**](https://github.com/NotSoSecure/wordlistctrl) | Wordlist manipulation toolkit |
| [**SecLists**](https://github.com/danielmiessler/SecLists) | Collection of security-related wordlists |
| [**Probable Wordlists**](https://github.com/berzerk0/Probable-Wordlists) | Real-world password wordlists |
| [**RockYou**](https://github.com/brannondorsey/naive-hashcat/releases) | Famous leaked password wordlist |
| [**KeeFarce**](https://github.com/denandz/KeeFarce) | KeePass extraction tool |
| [**KeeThief**](https://github.com/HarmJ0y/KeeThief) | KeePass credential extraction |
| [**Mimikatz**](https://github.com/gentilkiwi/mimikatz) | Windows credential extraction |
| [**LaZagne**](https://github.com/AlessandroZ/LaZagne) | Credential recovery from installed apps |
| [**BrowserGather**](https://github.com/sekirkity/BrowserGather) | Browser credential extraction |
| [**WebBrowserPassView**](https://www.nirsoft.net/utils/web_browser_password.html) | Browser password viewer (NirSoft) |
| [**RDPassSpray**](https://github.com/dafthack/RDPassSpray) | RDP password spraying tool |
| [**DomainPasswordSpray**](https://github.com/dafthack/DomainPasswordSpray) | Active Directory password spraying |
| [**Spray**](https://github.com/Greenwolf/Spray) | Password spray tool for multiple services |
| [**BruteSpray**](https://github.com/x90skysn3k/brutespray) | Mass bruteforce from Nmap output |
| [**Turbo Intruder**](https://github.com/PortSwigger/turbo-intruder) | HTTP bruteforce tool (PortSwigger) |

---

## Wireless Attacks

Tools for attacking wireless networks and protocols.

| Tool | Description |
|------|-------------|
| [**Aircrack-ng**](https://www.aircrack-ng.org) | 802.11 WEP/WPA-PSK cracking suite |
| [**Airodump-ng**](https://www.aircrack-ng.org/doku.php?id=airodump-ng) | Wireless packet capture |
| [**Aireplay-ng**](https://www.aircrack-ng.org/doku.php?id=aireplay-ng) | Wireless packet injection |
| [**Airmon-ng**](https://www.aircrack-ng.org/doku.php?id=airmon-ng) | Wireless interface monitor mode |
| [**Airbase-ng**](https://www.aircrack-ng.org/doku.php?id=airbase-ng) | Rogue AP / fake access point |
| [**Airgeddon**](https://github.com/v1s1t0r1sh3r3/airgeddon) | Wireless security auditing script |
| [**Wifite**](https://github.com/derv82/wifite2) | Automated wireless attack tool |
| [**Wifiphisher**](https://github.com/wifiphisher/wifiphisher) | Rogue AP phishing framework |
| [**Fluxion**](https://github.com/FluxionNetwork/fluxion) | WPA/WPA2 handshake capture and evil twin |
| [**BetterCAP**](https://www.bettercap.org) | Wireless MITM and monitoring |
| [**Kismet**](https://www.kismetwireless.net) | Wireless network detector and sniffer |
| [**Reaver**](https://github.com/t6x/reaver-wps-fork-t6x) | WPS brute-force attack |
| [**Bully**](https://github.com/aanarchyy/bully) | WPS brute-force attack (implementation) |
| [**PixieWPS**](https://github.com/wiire/pixiewps) | WPS offline bruteforce attack |
| [**Wash**](https://github.com/t6x/reaver-wps-fork-t6x) | WPS scan tool |
| [**Cowpatty**](https://github.com/jimstorch/cowpatty) | WPA-PSK cracking |
| [**Pyrit**](https://github.com/JPaulMora/Pyrit) | WPA/WPA2 precomputed attack |
| [**hashcat**](https://hashcat.net/hashcat) | GPU-accelerated WPA cracking |
| [**EWSA**](https://www.elcomsoft.com/ewsa.html) | Elcomsoft Wireless Security Auditor |
| [**MDK3**](https://github.com/wi-fi-analyzer/mdk3-master) | Wireless DoS and exploitation |
| [**MDK4**](https://github.com/aircrack-ng/mdk4) | Wireless exploitation framework (MDK3 successor) |
| [**MFC**](https://github.com/aircrack-ng/mfc) | Multi-function card for wireless attacks |
| [**Hostapd-wpe**](https://github.com/OpenSecurityResearch/hostapd-wpe) | WPA Enterprise authentication bypass |
| [**EAPHammer**](https://github.com/s0lst1c3/eaphammer) | Evil twin attack against WPA2-Enterprise |
| [**AirSnort**](https://airsnort.shmoo.com) | WEP key recovery |
| [**WEPCrack**](https://github.com/aircrack-ng/wepcrack) | WEP key cracker |
| [**WPA_sycophant**](https://github.com/exploiting/wpa_sycophant) | WPA EAP relay attack tool |
| [**Horst**](https://github.com/br101/horst) | Wireless spectrum analyzer |
| [**WiFi Pineapple**](https://shop.hak5.org/products/wifi-pineapple) | Rogue AP and MITM device (Hak5) |
| [**WiFi Pumpkin**](https://github.com/P0cL4bs/wifipumpkin3) | Rogue AP framework for MITM |

---

## Bluetooth & RFID Attacks

Tools for Bluetooth and RFID/NFC security testing.

| Tool | Description |
|------|-------------|
| [**BlueZ**](https://github.com/bluez/bluez) | Official Linux Bluetooth protocol stack |
| [**Bluetoothctl**](https://github.com/bluez/bluez) | Bluetooth control utility |
| [**BlueHydra**](https://github.com/pwnieexpress/blue_hydra) | Bluetooth device discovery |
| [**BlueRanger**](https://github.com/bigbrowser/blueranger) | Bluetooth device discovery |
| [**BlueMaho**](https://github.com/zenofex/bluemaho) | Bluetooth hacking tool suite |
| [**BTcrack**](https://github.com/mikeryan/btcrack) | Bluetooth passkey cracking |
| [**CarWhisperer**](https://github.com/aanarchyy/carwhisperer) | Bluetooth car audio exploitation |
| [**Bluesnarfer**](https://www.s0ftpj.eu/bf) | Bluetooth OBEX push exploitation |
| [**Btscanner**](https://github.com/mk-fg/btscanner) | Bluetooth device scanner |
| [**HCIDump**](https://github.com/bluez/bluez) | Bluetooth HCI packet dump |
| [**Hcitool**](https://github.com/bluez/bluez) | Bluetooth device configuration |
| [**Sdptool**](https://github.com/bluez/bluez) | Bluetooth service discovery |
| [**L2ping**](https://github.com/bluez/bluez) | Bluetooth L2CAP ping |
| [**Redfang**](https://github.com/tomydng/redfang) | Bluetooth device discovery |
| [**Ubertooth**](https://github.com/greatscottgadgets/ubertooth) | Bluetooth development and sniffing platform |
| [**NRF24-BTLE**](https://github.com/danielkuc/btle-sniffer) | Bluetooth Low Energy Sniffer |
| [**BTLEJack**](https://github.com/virtualsecureplatform/btlejack) | Bluetooth LE exploitation |
| [**GATTack**](https://github.com/secworks/gattack) | Bluetooth GATT fuzzer |
| [**BetterCAP BLE**](https://www.bettercap.org) | Bluetooth LE framework |
| [**MFCUK**](https://github.com/nfc-tools/mfcuk) | Mifare Classic RFID tool |
| [**MFOC**](https://github.com/nfc-tools/mfoc) | Mifare Classic offline cracker |
| [**Crapto1**](https://github.com/aczid/crapto1) | Mifare Classic encryption crack |
| [**libnfc**](https://github.com/nfc-tools/libnfc) | NFC library and tools |
| [**NFC-Tools**](https://github.com/nfc-tools/nfc-tools) | NFC tag manipulation |
| [**Proxmark3**](https://github.com/RfidResearchGroup/proxmark3) | RFID research and attack platform |
| [**ChameleonMini**](https://github.com/emsec/ChameleonMini) | RFID emulation platform |
| [**OpenPCD**](https://github.com/OpenPCD/OpenPCD) | RFID reader/writer |
| [**OpenPICC**](https://github.com/OpenPCD/OpenPICC) | RFID tag emulator |

---

## Reverse Engineering

Tools for analyzing and understanding binary code.

| Tool | Description |
|------|-------------|
| [**Ghidra**](https://ghidra-sre.org) | Reverse engineering framework (NSA) |
| [**IDA Pro**](https://hex-rays.com/ida-pro) | Interactive disassembler and debugger |
| [**IDA Freeware**](https://hex-rays.com/ida-free) | Free version of IDA Pro |
| [**Radare2**](https://rada.re) | Open-source reverse engineering framework |
| [**Rizin**](https://rizin.re) | Unix-based reverse engineering framework |
| [**Binary Ninja**](https://binary.ninja) | Binary analysis platform (Vector 35) |
| [**x64dbg**](https://x64dbg.com) | Windows debugger (x64/x86) |
| [**OllyDbg**](https://www.ollydbg.de) | 32-bit Windows debugger |
| [**Immunity Debugger**](https://www.immunityinc.com/products/debugger) | Windows debugger with Python API |
| [**WinDbg**](https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger) | Windows kernel/user-mode debugger (Microsoft) |
| [**GDB**](https://www.gnu.org/software/gdb) | GNU debugger |
| [**LLDB**](https://lldb.llvm.org) | LLVM debugger |
| [**Hopper**](https://www.hopperapp.com) | Reverse engineering tool for macOS |
| [**dnSpy**](https://github.com/dnSpy/dnSpy) | .NET assembly editor and debugger |
| [**ILSpy**](https://github.com/icsharpcode/ILSpy) | .NET assembly browser and decompiler |
| [**dotPeek**](https://www.jetbrains.com/decompiler) | .NET decompiler (JetBrains) |
| [**JD-GUI**](https://github.com/java-decompiler/jd-gui) | Java decompiler GUI |
| [**JADX**](https://github.com/skylot/jadx) | Android Dex-to-Java decompiler |
| [**APKTool**](https://apktool.org) | Android APK reverse engineering |
| [**Smali/Baksmali**](https://github.com/JesusFreke/smali) | Android Dalvik assembler/disassembler |
| [**Bytecode Viewer**](https://github.com/Konloch/bytecode-viewer) | Multi-feature Java/Android reverse engineering |
| [**Procyon**](https://github.com/mstrobel/procyon) | Java decompiler |
| [**CFR**](https://github.com/leibnitz/cfr) | Java decompiler |
| [**Fernflower**](https://github.com/fesh0r/fernflower) | Java decompiler (Kotlin compatible) |
| [**Uncompyle6**](https://github.com/rocky/python-uncompyle6) | Python bytecode decompiler |
| [**Decompyle++**](https://github.com/zrax/pycdc) | Python decompiler |
| [**ILdasm**](https://learn.microsoft.com/en-us/dotnet/framework/tools/ildasm-exe-il-disassembler) | .NET IL disassembler |
| [**Objdump**](https://www.gnu.org/software/binutils) | GNU object file analysis |
| [**Readelf**](https://www.gnu.org/software/binutils) | ELF file analysis |
| [**Strings**](https://www.gnu.org/software/binutils) | Extract printable strings from binaries |
| [**Hexdump**](https://linux.die.net/man/1/hexdump) | Binary file hex viewer |
| [**HxD**](https://mh-nexus.de/en/hxd) | Hex editor (Windows) |
| [**010 Editor**](https://www.sweetscape.com/010editor) | Professional hex editor |
| [**ImHex**](https://imhex.werwolv.net) | Modern hex editor for reverse engineers |
| [**FLOSS**](https://github.com/mandiant/flare-floss) | Obfuscated string extraction (Mandiant) |
| [**Detect It Easy (DiE)**](https://github.com/horsicq/Detect-It-Easy) | File type and packer detection |
| [**PEiD**](https://www.aldeid.com/wiki/PEiD) | PE file packer detector |
| [**CFF Explorer**](https://ntcore.com/explorer-suite) | PE file editor |
| [**LordPE**](https://www.aldeid.com/wiki/LordPE) | PE file analysis |
| [**Resource Hacker**](https://www.angusj.com/resourcehacker) | Windows resource editor |
| [**UPX**](https://upx.github.io) | Ultimate Packer for eXecutables |
| [**VMProtect**](https://vmpsoft.com) | Software protection (analysis) |
| [**Themida**](https://www.oreans.com/themida.php) | Software protection (analysis) |
| [**Angr**](https://angr.io) | Binary analysis framework (UCSB) |
| [**Triton**](https://triton.quarkslab.com) | Dynamic binary analysis framework |
| [**BAP**](https://github.com/binaryanalysisplatform/bap) | Binary Analysis Platform |
| [**Manticore**](https://github.com/trailofbits/manticore) | Symbolic execution tool (Trail of Bits) |
| [**Frida**](https://frida.re) | Dynamic instrumentation toolkit |
| [**Unicorn**](https://www.unicorn-engine.org) | CPU emulator framework |
| [**QEMU**](https://www.qemu.org) | Open-source machine emulator |
| [**Panda**](https://github.com/panda-re/panda) | Platform for architecture-neutral dynamic analysis |

---

## Forensics

Tools for digital forensic investigation and incident response.

| Tool | Description |
|------|-------------|
| [**Autopsy**](https://www.autopsy.com) | Digital forensics platform (Sleuth Kit GUI) |
| [**Sleuth Kit**](https://www.sleuthkit.org) | CLI forensic analysis tool collection |
| [**FTK Imager**](https://www.exterro.com/ftk-imager) | Forensic disk imaging (AccessData) |
| [**EnCase**](https://www.opentext.com/products/encase-forensic) | Enterprise forensic investigation (OpenText) |
| [**Volatility**](https://www.volatilityfoundation.org) | Memory forensics framework |
| [**Rekall**](https://github.com/google/rekall) | Memory forensics analysis |
| [**MemProcFS**](https://github.com/ufrisk/MemProcFS) | Memory process file system |
| [**Redline**](https://www.mandiant.com/resources/redline) | Memory and file analysis (FireEye/Mandiant) |
| [**KAPE**](https://www.kroll.com/en/services/cyber-risk/kroll-artifact-parser-extractor-kape) | Kroll Artifact Parser and Extractor |
| [**CyLR**](https://github.com/orlikoski/CyLR) | Live response data collection |
| [**Velociraptor**](https://github.com/Velocidex/velociraptor) | Endpoint visibility and collection |
| [**GRR**](https://github.com/google/grr) | Incident response framework (Google) |
| [**OSQuery**](https://osquery.io) | SQL-based endpoint instrumentation (Facebook) |
| [**DFIR-Oracle**](https://github.com/0x6d69636b/dfir-oracle) | DFIR data collection tool |
| [**Foremost**](https://github.com/korczis/foremost) | File carving utility |
| [**Scalpel**](https://github.com/sleuthkit/scalpel) | File carving and recovery |
| [**PhotoRec**](https://www.cgsecurity.org/wiki/PhotoRec) | File recovery software |
| [**TestDisk**](https://www.cgsecurity.org/wiki/TestDisk) | Partition recovery and data recovery |
| [**dd/dcfldd**](https://dcfldd.sourceforge.io) | Disk imaging and duplication |
| [**Guymager**](https://guymager.sourceforge.io) | Forensic disk imager |
| [**DC3DD**](https://github.com/adulau/dc3dd) | DoD-compliant disk imaging |
| [**Bulk Extractor**](https://github.com/simsong/bulk_extractor) | Fast file scanning and extraction |
| [**Strings**](https://www.gnu.org/software/binutils) | String extraction from binaries |
| [**Binwalk**](https://github.com/ReFirmLabs/binwalk) | Firmware extraction and analysis |
| [**Plaso**](https://github.com/log2timeline/plaso) | Timeline generator (log2timeline) |
| [**Timeline Explorer**](https://github.com/EricZimmerman/TimelineExplorer) | Windows forensic timeline (EZTools) |
| [**Log2Timeline**](https://github.com/log2timeline/plaso) | Timeline creation framework |
| [**Wireshark**](https://www.wireshark.org) | Network forensic analysis |
| [**NetworkMiner**](https://www.netresec.com/?page=NetworkMiner) | Network forensic analysis |
| [**Xplico**](https://www.xplico.org) | Network forensic analysis tool |
| [**CAINE**](https://www.caine-live.net) | Forensic analysis environment |
| [**SIFT**](https://www.sans.org/tools/sift-workstation) | SANS Investigative Forensics Toolkit |
| [**Kali Linux Forensics Mode**](https://www.kali.org) | Debian-based forensic distro |
| [**PALADIN**](https://sumuri.com/software/paladin) | Forensic Linux distribution |
| [**DEFT**](https://www.deftlinux.net) | Digital Evidence & Forensics Toolkit |
| [**Rifiuti2**](https://github.com/abelcheung/rifiuti2) | Windows Recycle Bin analysis |
| [**LECmd**](https://github.com/EricZimmerman/LECmd) | Windows LNK file analysis (EZTools) |
| [**PECmd**](https://github.com/EricZimmerman/PECmd) | Windows prefetch analysis (EZTools) |
| [**JumpList**](https://github.com/EricZimmerman/JumpList) | Windows Jump List analysis |
| [**SBECmd**](https://github.com/EricZimmerman/SBECmd) | Windows ShellBags analysis |
| [**RECmd**](https://github.com/EricZimmerman/RECmd) | Windows Registry analysis (EZTools) |
| [**Registry Explorer**](https://github.com/EricZimmerman/RegistryExplorer) | Windows Registry viewer (EZTools) |
| [**Chromagnon**](https://github.com/0xebef/chromagnon) | Chrome browser forensics |
| [**ChromeAnalysis**](https://github.com/iarange/ChromeAnalysis) | Chrome forensics tool |
| [**Browser History Examiner**](https://www.forensicmag.com/2943-Browser-History-Examiner/) | Browser forensics |
| [**SQLite Browser**](https://sqlitebrowser.org) | SQLite database viewer |
| [**HstEx**](https://www.nist.gov/document/hstex4zip) | Browser history recovery |
| [**Belkasoft Evidence Center**](https://belkasoft.com/ec) | Digital forensics platform |
| [**X-Ways Forensics**](https://www.x-ways.net/forensics) | Advanced forensics environment |
| [**Magnet AXIOM**](https://www.magnetforensics.com/products/magnet-axiom) | Digital investigation platform |

---

## Post-Exploitation

Tools used after gaining initial access to a system.

| Tool | Description |
|------|-------------|
| [**Mimikatz**](https://github.com/gentilkiwi/mimikatz) | Windows credential extraction |
| [**PowerShell Empire**](https://github.com/BC-SECURITY/Empire) | Post-exploitation PowerShell agent |
| [**PowerSploit**](https://github.com/PowerShellMafia/PowerSploit) | PowerShell post-exploitation framework |
| [**Nishang**](https://github.com/samratashok/nishang) | PowerShell for exploitation and post-exploitation |
| [**PoshC2**](https://github.com/nettitude/PoshC2) | C2 framework with PowerShell implants |
| [**CrackMapExec**](https://github.com/Porchetta-Industries/CrackMapExec) | Active Directory post-exploitation |
| [**Impacket**](https://github.com/fortra/impacket) | Collection of Python network protocols |
| [**Impacket wmiexec**](https://github.com/fortra/impacket) | WMI command execution |
| [**Impacket psexec**](https://github.com/fortra/impacket) | PSExec-style execution |
| [**Impacket smbexec**](https://github.com/fortra/impacket) | SMB command execution |
| [**Impacket wmiquery**](https://github.com/fortra/impacket) | WMI query tool |
| [**Impacket secretsdump**](https://github.com/fortra/impacket) | Windows secret extraction |
| [**BloodHound**](https://github.com/BloodHoundAD/BloodHound) | Active Directory relationship mapping |
| [**SharpHound**](https://github.com/BloodHoundAD/SharpHound) | BloodHound data collector (C#) |
| [**PlumHound**](https://github.com/PlumHound/PlumHound) | AD risk assessment with BloodHound |
| [**ADExplorer**](https://learn.microsoft.com/en-us/sysinternals/downloads/adexplorer) | Active Directory explorer (Sysinternals) |
| [**ADRecon**](https://github.com/sense-of-security/ADRecon) | Active Directory reconnaissance |
| [**ADAttackSuite**](https://github.com/samratashok/ADAttackSuite) | Active Directory attack toolkit |
| [**Rubeus**](https://github.com/GhostPack/Rubeus) | Kerberos abuse toolkit (C#) |
| [**Kerbrute**](https://github.com/ropnop/kerbrute) | Kerberos brute-force tool |
| [**ASRepRoTool**](https://github.com/yanncam/ASRepRoTool) | AS-REP roast attack tool |
| [**Impacket GetNPUsers**](https://github.com/fortra/impacket) | AS-REP roasting |
| [**Impacket GetUserSPNs**](https://github.com/fortra/impacket) | Kerberoasting |
| [**Impacket ticketer**](https://github.com/fortra/impacket) | Silver/Golden ticket creation |
| [**Impacket goldenPac**](https://github.com/fortra/impacket) | Golden ticket + PSExec |
| [**LAPSToolkit**](https://github.com/leoloobeek/LAPSToolkit) | LAPS abuse and enumeration |
| [**PowerUp**](https://github.com/PowerShellMafia/PowerSploit) | Windows privilege escalation |
| [**PowerView**](https://github.com/PowerShellMafia/PowerSploit) | Windows domain enumeration |
| [**SharPersist**](https://github.com/fireeye/SharPersist) | Windows persistence toolkit |
| [**SharPivot**](https://github.com/nettitude/SharPivot) | AD lateral movement |
| [**SpoolSample**](https://github.com/leechristensen/SpoolSample) | MS-PRN printer bug exploitation |
| [**Coercer**](https://github.com/p0dalirius/Coercer) | Windows authentication coercion |
| [**PetitPotam**](https://github.com/topotam/PetitPotam) | MS-EFSR abuse for relay |
| [**ntlmrelayx**](https://github.com/fortra/impacket) | NTLM relay attacks |
| [**MultiRelay**](https://github.com/lgandx/MultiRelay) | NTLM relay chaining |
| [**Chisel**](https://github.com/jpillora/chisel) | Fast TCP/UDP tunnel over HTTP |
| [**ligolo-ng**](https://github.com/nicocha30/ligolo-ng) | Advanced SOCKS5 proxy tunneling |
| [**FRP**](https://github.com/fatedier/frp) | Fast Reverse Proxy |
| [**Netsh**](https://learn.microsoft.com/en-us/windows-server/networking/technologies/netsh) | Windows port forwarding |
| [**SSH Tunneling**](https://www.ssh.com/academy/ssh/tunneling) | Secure shell port forwarding |
| [**Stowaway**](https://github.com/ph4ntonn/Stowaway) | Multi-hop proxy tool |
| [**Venom**](https://github.com/Dliv3/Venom) | Multi-hop proxy for penetration testing |
| [**EarthWorm**](https://github.com/ffay/lanproxy) | SOCKS5 proxy and port forwarding |
| [**Proxychains**](https://github.com/rofl0r/proxychains-ng) | Force traffic through proxy chains |
| [**socat**](http://www.dest-unreach.org/socat) | Multipurpose relay and tunneling |

---

## Command & Control (C2) Frameworks

Frameworks for managing compromised systems.

| Tool | Description |
|------|-------------|
| [**Cobalt Strike**](https://www.cobaltstrike.com) | Adversary simulation and C2 |
| [**Metasploit**](https://www.metasploit.com) | Exploitation and C2 capabilities |
| [**Empire**](https://github.com/BC-SECURITY/Empire) | PowerShell/Python post-exploitation |
| [**Covenant**](https://github.com/cobbr/Covenant) | .NET C2 framework |
| [**Sliver**](https://github.com/BishopFox/sliver) | Implant-based C2 (BishopFox) |
| [**Brute Ratel C4**](https://bruteratel.com) | Adversary simulation C2 |
| [**Nighthawk**](https://www.mdsec.co.uk/nighthawk) | Advanced C2 framework (MDSec) |
| [**Merlin**](https://github.com/Ne0nd0g/merlin) | Go-based C2 server |
| [**Havoc C2**](https://github.com/HavocFramework/Havoc) | Modern C2 framework |
| [**DeimosC2**](https://github.com/DeimosC2/DeimosC2) | C2 framework using gRPC |
| [**Faction C2**](https://github.com/FactionC2/Faction) | .NET C2 framework |
| [**Shad0w C2**](https://github.com/bats3c/shad0w) | .NET C2 with Beacon compatibility |
| [**C3**](https://github.com/FSecureLABS/C3) | Custom Command and Control (C3) |
| [**PoshC2**](https://github.com/nettitude/PoshC2) | PowerShell C2 server |
| [**Koadic**](https://github.com/zerosum0x0/koadic) | COM Command & Control |
| [**Pupy**](https://github.com/n1nj4sec/pupy) | Cross-platform C2 (Python) |
| [**TrevorC2**](https://github.com/trustedsec/trevorc2) | Deceptive C2 mechanism |
| [**Mythic**](https://github.com/its-a-feature/Mythic) | Multi-agent C2 framework |
| [**Apfell**](https://github.com/its-a-feature/Apfell) | macOS post-exploitation (Mythic) |
| [**Athena**](https://github.com/MythicAgents/Athena) | Windows agent for Mythic |
| [**Poseidon**](https://github.com/MythicAgents/Poseidon) | macOS agent for Mythic |
| [**SilentTrinity**](https://github.com/byt3bl33d3r/SILENTTRINITY) | Python-based C2 agent |
| [**Phoenix C2**](https://github.com/passthehashbrowns/phoenix) | C2 framework with multiple agents |
| [**AsyncRAT**](https://github.com/NYAN-x-CAT/AsyncRAT-C-Sharp) | Open-source remote administration tool |
| [**Quasar RAT**](https://github.com/quasar/QuasarRAT) | Remote administration tool (C#) |
| [**Empire**](https://github.com/BC-SECURITY/Empire) | Post-exploitation C2 framework |
| [**Cobalt Strike Malleable C2**](https://www.cobaltstrike.com/help-malleable-c2) | Custom C2 profile generation |

---

## Mobile Security Testing

Tools for testing mobile application security.

| Tool | Description |
|------|-------------|
| [**MobSF**](https://github.com/MobSF/Mobile-Security-Framework-MobSF) | Mobile Security Framework - static/dynamic analysis |
| [**APKTool**](https://apktool.org) | APK reverse engineering tool |
| [**JADX**](https://github.com/skylot/jadx) | Dex-to-Java decompiler |
| [**JD-GUI**](https://github.com/java-decompiler/jd-gui) | Java decompiler |
| [**Bytecode Viewer**](https://github.com/Konloch/bytecode-viewer) | Multi-feature Java/Android decompiler |
| [**Dex2Jar**](https://github.com/pxb1988/dex2jar) | Convert Dex to Jar |
| [**Frida**](https://frida.re) | Dynamic instrumentation for mobile apps |
| [**Objection**](https://github.com/sensepost/objection) | Runtime mobile exploration |
| [**Xposed Framework**](https://github.com/rovo89/Xposed) | Android module framework |
| [**Cydia Substrate**](https://cydia.saurik.com/substrate) | Android/iOS runtime modification |
| [**Magisk**](https://github.com/topjohnwu/Magisk) | Android systemless root |
| [**iNalyzer**](https://github.com/appknox/iNalyzer) | iOS application analysis |
| [**iRET**](https://github.com/S3Jensen/iRET) | iOS reverse engineering toolkit |
| [**Needle**](https://github.com/mwrlabs/needle) | iOS security testing framework |
| [**Objection**](https://github.com/sensepost/objection) | Mobile exploration (iOS/Android) |
| [**Drozer**](https://github.com/WithSecureLabs/drozer) | Android security testing framework |
| [**QARK**](https://github.com/linkedin/qark) | Quick Android Review Kit |
| [**Android Studio**](https://developer.android.com/studio) | Android development and testing |
| [**ADB**](https://developer.android.com/studio/command-line/adb) | Android Debug Bridge |
| [**Xcode**](https://developer.apple.com/xcode) | iOS development and testing |
| [**Class-Dump**](https://github.com/nygard/class-dump) | Objective-C class dump |
| [**Theos**](https://theos.dev) | iOS development and tweak creation |
| [**Cycript**](https://cycript.org) | Objective-C and JavaScript runtime |
| [**iFunBox**](https://www.i-funbox.com) | iOS file manager |
| [**FileZilla**](https://filezilla-project.org) | iOS file transfer |
| [**ios-deploy**](https://github.com/ios-control/ios-deploy) | iOS app deployment |
| [**Idb**](https://github.com/dmayer/idb) | iOS testing utility |
| [**Hopper**](https://www.hopperapp.com) | iOS/macOS disassembler |
| [**Burp Suite**](https://portswigger.net/burp) | Mobile web traffic interception |
| [**MITMProxy**](https://mitmproxy.org) | Mobile HTTPS interception |
| [**Objection**](https://github.com/sensepost/objection) | Bypass SSL pinning |

---

## Malware Analysis

Tools for analyzing malicious software.

| Tool | Description |
|------|-------------|
| [**Cuckoo Sandbox**](https://github.com/cuckoosandbox/cuckoo) | Automated malware analysis system |
| [**CAPE**](https://github.com/kevoreilly/CAPEv2) | Malware analysis and extraction (Cuckoo fork) |
| [**VMRay**](https://www.vmray.com) | Advanced malware analysis platform |
| [**Joe Sandbox**](https://www.joesandbox.com) | Deep malware analysis |
| [**Any.Run**](https://any.run) | Interactive malware analysis |
| [**Hybrid Analysis**](https://www.hybrid-analysis.com) | Crowd-sourced malware analysis (Falcon) |
| [**FireEye Malware Analysis**](https://www.fireeye.com/products/malware-analysis.html) | Enterprise sandbox |
| [**REMnux**](https://remnux.org) | Linux distribution for reverse engineering |
| [**FLOSS**](https://github.com/mandiant/flare-floss) | Obfuscated string extractor (Mandiant) |
| [**YARA**](https://virustotal.github.io/yara) | Malware identification and classification |
| [**YARA-Gen**](https://github.com/Neo23x0/yaragen) | YARA rule generator |
| [**YAYA**](https://github.com/EFForg/yaya) | YARA Yet Another ruleset |
| [**CapTipper**](https://github.com/omriher/CapTipper) | HTTP malicious traffic analysis |
| [**Volatility**](https://www.volatilityfoundation.org) | Memory malware analysis |
| [**Process Hacker**](https://processhacker.sourceforge.io) | Process analysis (Windows) |
| [**Process Monitor**](https://learn.microsoft.com/en-us/sysinternals/downloads/procmon) | Real-time process monitoring (Sysinternals) |
| [**Process Explorer**](https://learn.microsoft.com/en-us/sysinternals/downloads/process-explorer) | Process exploration (Sysinternals) |
| [**Autoruns**](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns) | Startup program analysis (Sysinternals) |
| [**Regshot**](https://github.com/Seabreg/Regshot) | Registry snapshot and comparison |
| [**API Monitor**](https://www.rohitab.com/apimonitor) | API call monitoring |
| [**SpyStudio**](https://www.spy-studio.com) | API hooking and monitoring |
| [**Noriben**](https://github.com/Rurik/Noriben) | Portable malware analysis sandbox |
| [**FakeNet-NG**](https://github.com/mandiant/flare-fakenet-ng) | Network simulation for malware analysis |
| [**INetSim**](https://www.inetsim.org) | Internet service simulation |
| [**TCPView**](https://learn.microsoft.com/en-us/sysinternals/downloads/tcpview) | Network connection viewer (Sysinternals) |
| [**Wireshark**](https://www.wireshark.org) | Network traffic analysis |
| [**ProcDOT**](https://www.procdot.com) | Process monitoring visualization |
| [**Hollows Hunter**](https://github.com/hasherezade/hollows_hunter) | Process hollowing detection (hacker) |
| [**PEStudio**](https://www.winitor.com) | PE file analysis without execution |
| [**Detect It Easy**](https://github.com/horsicq/Detect-It-Easy) | File type and packer detection |
| [**ExeInfoPE**](https://github.com/horsicq/ExeInfoPE) | PE file analysis and unpacking |
| [**OLE Tools**](https://github.com/decalage2/oletools) | OLE/Office file analysis (Didier Stevens) |
| [**PDF Tools**](https://blog.didierstevens.com/programs/pdf-tools) | PDF file analysis (Didier Stevens) |
| [**Origami**](https://github.com/coldwind/origami-pdf) | PDF file analysis framework |
| [**peepdf**](https://github.com/jesparza/peepdf) | PDF file analysis tool |
| [**Viper**](https://github.com/viper-analysis/viper) | Binary management and analysis framework |
| [**MISP**](https://www.misp-project.org) | Malware information sharing platform |
| [**ThreatConnect**](https://threatconnect.com) | Threat intelligence platform |
| [**Phantom**](https://www.splunk.com/en_us/software/splunk-security-orchestration-and-automation.html) | SOAR platform (Splunk) |

---

## OSINT (Open Source Intelligence)

Tools for gathering intelligence from public sources.

| Tool | Description |
|------|-------------|
| [**Maltego**](https://www.maltego.com) | Link analysis and data mining |
| [**theHarvester**](https://github.com/laramies/theHarvester) | Email, subdomain, and name enumeration |
| [**Recon-ng**](https://github.com/lanmaster53/recon-ng) | Web reconnaissance framework |
| [**SpiderFoot**](https://www.spiderfoot.net) | OSINT automation tool |
| [**SpiderFoot HX**](https://github.com/smicallef/spiderfoot) | OSINT automation (community edition) |
| [**Shodan**](https://www.shodan.io) | IoT and device search engine |
| [**Censys**](https://censys.io) | Internet asset search |
| [**ZoomEye**](https://www.zoomeye.org) | Cyberspace search engine |
| [**Fofa**](https://fofa.info) | Cyberspace asset search |
| [**Google Dorks**](https://www.exploit-db.com/google-hacking-database) | Advanced Google search operators |
| [**GHDB**](https://www.exploit-db.com/google-hacking-database) | Google Hacking Database |
| [**Pagine**](https://github.com/isaacJG/pagine) | Google dorking tool |
| [**Dork-Scanner**](https://github.com/NullArray/Dork-Scanner) | Google dork scanning tool |
| [**GooFuzz**](https://github.com/m3n0sd0n4ld/GooFuzz) | Google dork fuzzing |
| [**Wayback Machine**](https://archive.org/web) | Web archive (archive.org) |
| [**WaybackURLs**](https://github.com/tomnomnom/waybackurls) | Wayback URL extraction |
| [**Gau**](https://github.com/lc/gau) | Get All URLs (TomNomNom) |
| [**Hakrawler**](https://github.com/hakluke/hakrawler) | Web crawler for endpoints |
| [**Katana**](https://github.com/projectdiscovery/katana) | Web crawling and URL extraction |
| [**Social Mapper**](https://github.com/SpiderLabs/social_mapper) | Social media profile mapping |
| [**Twint**](https://github.com/twintproject/twint) | Twitter scraping tool |
| [**Tweets Analyzer**](https://github.com/x0rz/tweets_analyzer) | Twitter data analysis |
| [**Instagram Scraper**](https://github.com/realsirjoe/instagram-scraper) | Instagram data extraction |
| [**Facebook Scraper**](https://github.com/kevinzg/facebook-scraper) | Facebook data extraction |
| [**LinkedIn Scraper**](https://github.com/joeyism/linkedin_scraper) | LinkedIn data extraction |
| [**GitDorker**](https://github.com/obheda12/GitDorker) | GitHub dorking tool |
| [**GitHound**](https://github.com/tillson/git-hound) | GitHub data mining |
| [**TruffleHog**](https://github.com/trufflesecurity/trufflehog) | Git secrets scanning |
| [**GitLeaks**](https://github.com/gitleaks/gitleaks) | Git repository secrets detection |
| [**GitRob**](https://github.com/michenriksen/gitrober) | GitHub sensitive data scanning |
| [**Sherlock**](https://github.com/sherlock-project/sherlock) | Username search across networks |
| [**Holehe**](https://github.com/megadose/holehe) | Email-to-account verification |
| [**Infoga**](https://github.com/m4ll0k/Infoga) | Email information gathering |
| [**MailSniper**](https://github.com/dafthack/MailSniper) | Email enumeration and search |
| [**Have I Been Pwned**](https://haveibeenpwned.com) | Breached account search |
| [**DeHashed**](https://dehashed.com) | Credential leak search |
| [**LeakCheck**](https://leakcheck.io) | Data leak search engine |
| [**Sn0int**](https://github.com/kpcyrd/sn0int) | Semi-automatic OSINT framework |
| [**Little Brother**](https://github.com/lulz3xploit/LittleBrother) | OSINT reconnaissance tool |
| [**SkipTraces**](https://github.com/n0tr00t/SkipTrace) | OSINT investigation framework |
| [**MAT**](https://0xacab.org/jvoisin/mat2) | Metadata Anonymisation Toolkit |
| [**ExifTool**](https://exiftool.org) | Metadata reading and writing |
| [**GeoIP**](https://www.maxmind.com/en/geoip2-databases) | IP geolocation lookup |
| [**IPinfo**](https://ipinfo.io) | IP address information |
| [**DNSDumpster**](https://dnsdumpster.com) | DNS reconnaissance |
| [**SecurityTrails**](https://securitytrails.com) | DNS and IP history |

---

## Anonymity & Privacy

Tools for maintaining anonymity and privacy during testing.

| Tool | Description |
|------|-------------|
| [**Tor**](https://www.torproject.org) | Anonymous communication network |
| [**Tor Browser**](https://www.torproject.org) | Anonymized web browser |
| [**Tails**](https://tails.net) | Privacy-focused Linux distribution |
| [**Whonix**](https://www.whonix.org) | Anonymity-focused operating system |
| [**Qubes OS**](https://www.qubes-os.org) | Security-focused desktop OS |
| [**VPN**](https://en.wikipedia.org/wiki/Virtual_private_network) | Virtual Private Network services |
| [**Proxychains**](https://github.com/rofl0r/proxychains-ng) | Proxy routing for CLI tools |
| [**Proxifier**](https://www.proxifier.com) | Global proxy forcing |
| [**ProxyChains-NG**](https://github.com/rofl0r/proxychains-ng) | Next-gen proxy chain tool |
| [**Stunnel**](https://www.stunnel.org) | SSL tunneling |
| [**OpenVPN**](https://openvpn.net) | Open-source VPN solution |
| [**WireGuard**](https://www.wireguard.com) | Modern VPN protocol |
| [**I2P**](https://geti2p.net) | Anonymous peer-to-peer network |
| [**Freenet**](https://freenetproject.org) | Decentralized censorship-resistant network |
| [**Psiphon**](https://psiphon.ca) | Circumvention tool |
| [**Lantern**](https://getlantern.org) | Internet access circumvention |
| [**DNSCrypt**](https://dnscrypt.info) | DNS traffic encryption |
| [**DNSCrypt-Proxy**](https://github.com/DNSCrypt/dnscrypt-proxy) | Local DNS proxy with encryption |
| [**Unbound**](https://nlnetlabs.nl/projects/unbound) | Validating DNS resolver |
| [**Torify**](https://gitlab.com/sganimals/torify) | Route traffic through Tor |
| [**Torsocks**](https://gitweb.torproject.org/torsocks.git) | SOCKS wrapper for Tor |
| [**Zeronet**](https://zeronet.io) | Decentralized web using Bitcoin crypto |
| [**MAC Changer**](https://github.com/alobbs/macchanger) | MAC address spoofing |
| [**SecureDelete**](https://linux.die.net/man/1/srm) | Secure file deletion |
| [**DBAN**](https://dban.org) | Hard drive data destruction |
| [**CCleaner**](https://www.ccleaner.com) | Privacy cleaning tool |
| [**BleachBit**](https://www.bleachbit.org) | System cleaner for privacy |

---

## Social Engineering

Tools for social engineering assessments.

| Tool | Description |
|------|-------------|
| [**SET**](https://github.com/trustedsec/social-engineer-toolkit) | Social Engineering Toolkit (TrustedSec) |
| [**Gophish**](https://getgophish.com) | Open-source phishing framework |
| [**Evilginx2**](https://github.com/kgretzky/evilginx2) | Phishing reverse proxy with 2FA bypass |
| [**Modlishka**](https://github.com/drk1wi/Modlishka) | Transparent phishing reverse proxy |
| [**CredSniper**](https://github.com/ustayready/CredSniper) | Phishing framework with 2FA bypass |
| [**King Phisher**](https://github.com/rsmusllp/king-phisher) | Phishing campaign toolkit |
| [**Phish Shell**](https://github.com/trustedsec/phish-shell) | Phishing framework with OTP bypass |
| [**SocialFish**](https://github.com/UndeadSec/SocialFish) | Phishing framework (credential harvesting) |
| [**HiddenEye**](https://github.com/DarkSecDevelopers/HiddenEye) | Phishing framework with Telegram integration |
| [**ZPhisher**](https://github.com/htr-tech/zphisher) | Advanced phishing tool |
| [**BlackEye**](https://github.com/TheTeamCoding/BlackEye) | Phishing tool for credential harvesting |
| [**ShellPhish**](https://github.com/An0nUD4Y/shellphish) | Phishing tool for social media |
| [**Nevul**](https://github.com/Nevul/nevul) | Phishing framework with OTP capture |
| [**BeEF**](https://beefproject.com) | Browser Exploitation Framework |
| [**Catphish**](https://github.com/ring0lab/catphish) | Social engineering URL crafting |
| [**Artichoke**](https://github.com/tdrnky/artichoke) | Phishing handler |
| [**FiercePhish**](https://github.com/Raikia/FiercePhish) | Phishing awareness training |
| [**Lucy**](https://www.lucysecurity.com) | Phishing simulation and awareness |
| [**PhishTank**](https://www.phishtank.com) | Phishing data sharing |
| [**USB Rubber Ducky**](https://shop.hak5.org/products/usb-rubber-ducky) | Keystroke injection tool (Hak5) |
| [**Bash Bunny**](https://shop.hak5.org/products/bash-bunny) | Multi-vector USB attack (Hak5) |
| [**LAN Turtle**](https://shop.hak5.org/products/lan-turtle) | Network attack and MITM device (Hak5) |
| [**WiFi Pineapple**](https://shop.hak5.org/products/wifi-pineapple) | Wireless auditing and phishing (Hak5) |
| [**Key Croc**](https://shop.hak5.org/products/key-croc) | Keystroke logging device (Hak5) |

---

## Fuzzing Tools

Tools for discovering vulnerabilities through input fuzzing.

| Tool | Description |
|------|-------------|
| [**AFL**](https://github.com/google/AFL) | American Fuzzy Lop - coverage-guided fuzzer |
| [**AFL++**](https://github.com/AFLplusplus/AFLplusplus) | Community-driven AFL fork with enhancements |
| [**LibFuzzer**](https://llvm.org/docs/LibFuzzer.html) | In-process coverage-guided fuzzer (LLVM) |
| [**Honggfuzz**](https://github.com/google/honggfuzz) | Coverage-guided fuzzer with hardware feedback |
| [**OSS-Fuzz**](https://github.com/google/oss-fuzz) | Continuous fuzzing service (Google) |
| [**Peach Fuzzer**](https://www.peach.tech) | Smart fuzzing framework |
| [**Peach Pit**](https://www.peach.tech) | Industrial fuzzing framework |
| [**Syzkaller**](https://github.com/google/syzkaller) | Kernel fuzzer (Google) |
| [**TriforceAFL**](https://github.com/nccgroup/triforceafl) | AFL for full-system fuzzing with QEMU |
| [**BooFuzz**](https://github.com/jtpereyda/boofuzz) | Network protocol fuzzing framework |
| [**Ffuf**](https://github.com/ffuf/ffuf) | Fast web fuzzer |
| [**Wfuzz**](https://github.com/xmendez/wfuzz) | Web application bruteforcer |
| [**Burp Intruder**](https://portswigger.net/burp/documentation/desktop/tools/intruder) | Built-in fuzzer in Burp Suite |
| [**Radamsa**](https://gitlab.com/akihe/radamsa) | General-purpose test case fuzzer |
| [**Sulley**](https://github.com/OpenRCE/sulley) | Fuzzing framework |
| [**Kitty**](https://github.com/cisco-sas/kitty) | Python fuzzing framework |
| [**CERT BFF**](https://resources.sei.cmu.edu/library/asset-view.cfm?assetid=507530) | Basic Fuzzing Framework (CERT/CC) |
| [**Zzuf**](https://github.com/samhocevar/zzuf) | Transparent application fuzzer |
| [**GPF**](https://github.com/fooinator/gpf) | General Purpose Fuzzer |
| [**FileFuzz**](https://github.com/google/FileFuzz) | File format fuzzer |
| [**Spike**](https://github.com/guelfoweb/peekaboo) | Protocol fuzzing toolkit (Immunity) |
| [**Mutational Fuzzer**](https://github.com/originate/fuzzer) | Mutation-based fuzzing |
| [**CrossFuzz**](https://github.com/mozilla/CrossFuzz) | Cross-browser DOM fuzzer |
| [**FrameForge**](https://github.com/peternguyen/FrameForge) | IE/Office fuzzer |
| [**ProxyFuzz**](https://github.com/nicholasasimov/proxyfuzz) | Network protocol fuzzing proxy |
| [**SocketFuzz**](https://github.com/jtpereyda/socketfuzz) | Network socket fuzzer |
| [**FuzzDB**](https://github.com/fuzzdb-project/fuzzdb) | Attack pattern and fuzzing dictionary |
| [**JBroFuzz**](https://github.com/OWASP/JBroFuzz) | Web application fuzzer (OWASP) |

---

## Cloud Security

Tools for assessing cloud infrastructure security.

| Tool | Description |
|------|-------------|
| [**ScoutSuite**](https://github.com/nccgroup/ScoutSuite) | Multi-cloud security auditing tool |
| [**Prowler**](https://github.com/prowler-cloud/prowler) | AWS security assessment tool |
| [**CloudSploit**](https://cloudsploit.com) | Cloud security scanning |
| [**CloudMapper**](https://github.com/duo-labs/cloudmapper) | AWS network visualization and security |
| [**CloudTracker**](https://github.com/duo-labs/cloudtracker) | AWS IAM credential tracking |
| [**AWS-Inventory**](https://github.com/nccgroup/aws-inventory) | AWS resource inventory |
| [**PMapper**](https://github.com/nccgroup/PMapper) | AWS IAM privilege escalation mapper |
| [**Principal Mapper**](https://github.com/nccgroup/PMapper) | AWS IAM path analysis |
| [**S3Scanner**](https://github.com/sa7mon/S3Scanner) | AWS S3 bucket enumeration |
| [**Bucket Stream**](https://github.com/eth0izzle/bucket-stream) | AWS S3 bucket discovery |
| [**S3 Bucket Finder**](https://github.com/securitum/s3-bucket-finder) | S3 bucket discovery |
| [**CloudBrute**](https://github.com/0xsha/CloudBrute) | Cloud infrastructure enumeration |
| [**GCPBucketBrute**](https://github.com/RhinoSecurityLabs/GCPBucketBrute) | Google Cloud Storage enumeration |
| [**AzureBrute**](https://github.com/ChrisSkipp/AzureBrute) | Azure resource enumeration |
| [**Azurite**](https://github.com/Azure/Azurite) | Azure storage emulator |
| [**MicroBurst**](https://github.com/NetSPI/MicroBurst) | Azure security testing toolkit |
| [**Stormspotter**](https://github.com/Azure/Stormspotter) | Azure graph visualization |
| [**BloodHound for Azure**](https://github.com/BloodHoundAD/BloodHound) | Azure AD relationship mapping |
| [**AzureHound**](https://github.com/BloodHoundAD/AzureHound) | Azure AD data collector |
| [**ROADtools**](https://github.com/dirkjanm/ROADtools) | Azure AD attack toolkit |
| [**AADInternals**](https://github.com/Gerenios/AADInternals) | Azure AD administration |
| [**Terraform**](https://www.terraform.io) | Infrastructure-as-code / misconfiguration testing |
| [**Checkov**](https://www.checkov.io) | IaC security scanning |
| [**tfsec**](https://github.com/aquasecurity/tfsec) | Terraform security scanner |
| [**kics**](https://github.com/Checkmarx/kics) | Infrastructure-as-code scanning (Checkmarx) |
| [**Cloud Custodian**](https://cloudcustodian.io) | Cloud governance and security |
| [**Falco**](https://falco.org) | Container runtime security (Sysdig) |
| [**Aqua Security**](https://www.aquasec.com) | Container security platform |
| [**Twistlock**](https://www.paloaltonetworks.com/prisma/cloud) | Container security (Prisma Cloud) |
| [**Sysdig Secure**](https://sysdig.com) | Container security and forensics |

---

## IoT & Hardware Security

Tools for testing IoT devices and embedded systems.

| Tool | Description |
|------|-------------|
| [**Firmwalker**](https://github.com/craigz28/firmwalker) | Firmware extraction and analysis |
| [**Binwalk**](https://github.com/ReFirmLabs/binwalk) | Firmware reverse engineering |
| [**Firmadyne**](https://github.com/firmadyne/firmadyne) | Firmware emulation and analysis |
| [**QEMU**](https://www.qemu.org) | Full-system emulator for firmware |
| [**QEMU-AFL**](https://github.com/andreafioraldi/qemu-afl) | Fuzzing firmware with QEMU |
| [**AVR Fuse Breaker**](https://github.com/tom-kun/avr-fuse) | AVR fuse bit reset |
| [**AVRDUDE**](https://github.com/avrdudes/avrdude) | AVR microcontroller programming |
| [**Flashrom**](https://flashrom.org) | BIOS/ROM flashing utility |
| [**JTAGulator**](https://www.jtagulator.com) | JTAG/SWD pin identification |
| [**OpenOCD**](https://openocd.org) | On-chip debugger |
| [**UrJTAG**](https://urjtag.sourceforge.io) | JTAG boundary scan tool |
| [**Bus Pirate**](https://buspirate.com) | Bus analysis and hacking tool |
| [**Logic Analyzer**](https://www.saleae.com) | Digital signal analysis (Saleae) |
| [**Saleae Logic**](https://www.saleae.com) | Logic analyzer software |
| [**PulseView**](https://sigrok.org/wiki/PulseView) | Logic analyzer software (sigrok) |
| [**sigrok-cli**](https://sigrok.org) | Signal analysis CLI tool |
| [**Oscilloscope**](https://en.wikipedia.org/wiki/Oscilloscope) | Analog signal analysis |
| [**HackRF One**](https://greatscottgadgets.com/hackrf) | Software-defined radio platform |
| [**RTL-SDR**](https://www.rtl-sdr.com) | Software-defined radio receiver |
| [**GNU Radio**](https://www.gnuradio.org) | SDR signal processing framework |
| [**Universal Radio Hacker**](https://github.com/jopohl/urh) | Wireless protocol analysis |
| [**LTE-Cell-Scanner**](https://github.com/Evrytania/LTE-Cell-Scanner) | LTE base station scanning |
| [**IMSI Catcher**](https://en.wikipedia.org/wiki/IMSI-catcher) | IMSI capturing device identification |
| [**YateBTS**](https://yatebts.com) | Open-source BTS (base transceiver station) |
| [**OpenBTS**](https://github.com/RangeNetworks/openbts) | Base station software for GSM |
| [**Airprobe**](https://github.com/mikeryan/airprobe) | GSM air interface analysis |
| [**GR-GSM**](https://github.com/osmocom/gr-gsm) | GNU Radio GSM receiver |
| [**KillerBee**](https://github.com/riverloopsec/killerbee) | ZigBee security analysis |
| [**ZigDiggity**](https://github.com/BishopFox/zigdiggity) | ZigBee exploitation framework |
| [**MQTT-PWN**](https://github.com/akamai-threat-research/mqtt-pwn) | MQTT IoT protocol exploitation |
| [**Exploit IoT**](https://github.com/leonjza/exploit-iot) | IoT vulnerability scanner |
| [**IoT Inspector**](https://www.iot-inspector.com) | IoT device traffic analysis |
| [**Shodan**](https://www.shodan.io) | IoT device search engine |

---

## DDoS Testing

Tools for testing denial-of-service resilience.

| Tool | Description |
|------|-------------|
| [**LOIC**](https://github.com/NewEraCracker/LOIC) | Low Orbit Ion Cannon - DoS testing |
| [**HOIC**](https://github.com/NewEraCracker/HOIC) | High Orbit Ion Cannon - DoS testing |
| [**Slowloris**](https://github.com/gkbrk/slowloris) | Slow HTTP DoS attack |
| [**SlowHTTPTest**](https://github.com/shekyan/slowhttptest) | Slow HTTP DoS testing |
| [**Hping3**](https://github.com/antirez/hping) | Network stress testing |
| [**GoldenEye**](https://github.com/jseidl/GoldenEye) | HTTP DoS testing tool |
| [**Torshammer**](https://github.com/cyberspaceau/torshammer) | Slow rate DoS via Tor |
| [**R.U.D.Y**](https://github.com/mschwager/rudy) | R-U-Dead-Yet slow DoS tool |
| [**PyLoris**](https://github.com/gregorynicholas/pyloris) | Slow HTTP DoS testing |
| [**DHCPig**](https://github.com/kamorin/DHCPig) | DHCP exhaustion attack tool |
| [**Macof**](https://github.com/robertdavidgraham/macof) | MAC flooding for switch DoS |
| [**MDK3**](https://github.com/wi-fi-analyzer/mdk3-master) | Wireless DoS testing |
| [**Airplay-ng**](https://www.aircrack-ng.org) | Wireless packet injection |
| [**WFuzz**](https://github.com/xmendez/wfuzz) | Web stress testing |
| [**Siege**](https://www.joedog.org/siege-home) | HTTP load testing |
| [**Apache Bench (ab)**](https://httpd.apache.org/docs/2.4/programs/ab.html) | HTTP server benchmarking |
| [**WRK**](https://github.com/wg/wrk) | HTTP benchmarking tool |
| [**Vegeta**](https://github.com/tsenart/vegeta) | HTTP load testing tool (Go) |
| [**SlowLoris**](https://github.com/gkbrk/slowloris) | Apache HTTP server DoS |
| [**Sockstress**](https://github.com/defuse/sockstress) | TCP stack DoS analysis |
| [**Nemesis**](https://github.com/troglobit/nemesis) | Packet injection for DoS testing |
| [**Bonesi**](https://github.com/Markus-Go/bonesi) | Botnet simulation DoS tool |

---

## Steganography

Tools for hiding data within other data.

| Tool | Description |
|------|-------------|
| [**Steghide**](https://github.com/Steghide/steghide) | Image/audio steganography |
| [**OpenStego**](https://www.openstego.com) | Steganography and watermarking |
| [**StegSolve**](https://github.com/zardus/ctf-tools/blob/master/stegsolve) | Image steganalysis |
| [**StegDetect**](https://github.com/abelcheung/stegdetect) | Steganography detection |
| [**StirMark**](https://github.com/Behrang/stirmark) | Image watermarking robustness test |
| [**OutGuess**](https://github.com/resurrecting-open-source-projects/outguess) | Universal steganography tool |
| [**JPHS**](https://github.com/h3xx/jphs) | JPEG steganography |
| [**F5**](https://github.com/paiv/aes67-steganography) | JPEG steganography algorithm |
| [**MP3Stego**](https://www.petitcolas.net/steganography/mp3stego) | MP3 audio steganography |
| [**DeepSound**](https://jpinsoft.net/deepsound) | Audio steganography |
| [**Snow**](https://darkside.com.au/snow) | Whitespace steganography |
| [**Coagula**](https://www.abc.se/~re/Coagula/Coagula.html) | Image-to-sound steganography |
| [**Spectrology**](https://github.com/solusipse/spectrology) | Audio spectrogram steganography |
| [**Zsteg**](https://github.com/zed-0xff/zsteg) | PNG/BMP/GIF steganography detection |
| [**PngCheck**](https://github.com/sigurn/pngcheck) | PNG file analysis |
| [**ExifTool**](https://exiftool.org) | Metadata extraction and manipulation |
| [**Binwalk**](https://github.com/ReFirmLabs/binwalk) | File carving and data hiding detection |
| [**Stegbreak**](https://github.com/Paradoxis/StegCracker) | Steganography brute-force detection |
| [**Virtual Steganography**](https://github.com/msrkp/virtual-steganography) | Text-based steganography |
| [**Steganography Studio**](https://github.com/bozokopic/Steganography-Studio) | Image steganography analysis |

---

## Database Security

Tools for database security assessment.

| Tool | Description |
|------|-------------|
| [**SQLMap**](https://sqlmap.org) | Automated SQL injection detection/exploitation |
| [**jSQL Injection**](https://github.com/ron190/jsql-injection) | Java-based SQL injection tool |
| [**BBQSQL**](https://github.com/Neohapsis/bbqsql) | Blind SQL injection framework |
| [**NoSQLMap**](https://github.com/codingo/NoSQLMap) | NoSQL injection and exploitation |
| [**MongoSploit**](https://github.com/botherder/mongosploit) | MongoDB exploitation |
| [**Redis-rogue-server**](https://github.com/n0b0dyCN/Redis-rogue-server) | Redis RCE framework |
| [**RedisExploit**](https://github.com/jonas-koeritz/redis-exploit) | Redis exploitation |
| [**ElasticSearch**](https://www.elastic.co) | ES testing and exploitation |
| [**MSSQL Brute**](https://github.com/linuz/Stupid) | SQL Server brute-force |
| [**MYSQL Brute**](https://github.com/Chris01s/MySQL-Brute-Force) | MySQL brute-force |
| [**OracleDB Brute**](https://github.com/RedTeamPentesting/oracle-brute) | Oracle database brute-force |
| [**SQL-Server-Query**](https://github.com/NetSPI/SQL-Server-Query) | MSSQL query and enumeration |
| [**DBeaver**](https://dbeaver.io) | Universal database manager |
| [**HeidiSQL**](https://www.heidisql.com) | Database administration (Windows) |
| [**psql**](https://www.postgresql.org) | PostgreSQL CLI |
| [**mysql CLI**](https://dev.mysql.com/doc/refman/en/mysql.html) | MySQL CLI |
| [**MongoDB Shell**](https://www.mongodb.com/products/shell) | MongoDB CLI |
| [**Redis CLI**](https://redis.io) | Redis CLI |
| [**Sqlninja**](https://github.com/xxgrunge/sqlninja) | MSSQL injection and exploitation |
| [**SQLBrute**](https://github.com/udonmai/SQLBrute) | SQL injection brute-force |

---

## Windows & Active Directory

Tools specific to Windows and AD security assessment.

| Tool | Description |
|------|-------------|
| [**PowerShell**](https://learn.microsoft.com/en-us/powershell) | Windows scripting and automation |
| [**PowerView**](https://github.com/PowerShellMafia/PowerSploit) | AD domain enumeration |
| [**BloodHound**](https://github.com/BloodHoundAD/BloodHound) | AD privilege escalation visualization |
| [**SharpHound**](https://github.com/BloodHoundAD/SharpHound) | BloodHound data collector |
| [**Impacket**](https://github.com/fortra/impacket) | Python AD protocol toolkit |
| [**Mimikatz**](https://github.com/gentilkiwi/mimikatz) | Windows credential extraction |
| [**Rubeus**](https://github.com/GhostPack/Rubeus) | Kerberos toolkit |
| [**Kerbrute**](https://github.com/ropnop/kerbrute) | Kerberos brute-force |
| [**LAPSToolkit**](https://github.com/leoloobeek/LAPSToolkit) | LAPS abuse |
| [**PowerUp**](https://github.com/PowerShellMafia/PowerSploit) | Windows privilege escalation |
| [**BeRoot**](https://github.com/AlessandroZ/BeRoot) | Windows privilege escalation |
| [**PrivescCheck**](https://github.com/itm4n/PrivescCheck) | Windows privilege escalation enumeration |
| [**Seatbelt**](https://github.com/GhostPack/Seatbelt) | Windows security configuration enumeration |
| [**SharpUp**](https://github.com/GhostPack/SharpUp) | C# privilege escalation enumeration |
| [**Watson**](https://github.com/rasta-mouse/Watson) | Windows kernel exploit suggestion |
| [**Sherlock**](https://github.com/sherlock-project/sherlock) | Windows kernel exploit enumeration |
| [**GhostPack**](https://github.com/GhostPack/GhostPack) | Windows security toolkit collection |
| [**SharpCollection**](https://github.com/Flangvik/SharpCollection) | Compiled Sharp tools |
| [**SharpBlocks**](https://github.com/S3cur3Th1sSh1t/SharpBlocks) | Windows event log manipulation |
| [**SharpEventLog**](https://github.com/S3cur3Th1sSh1t/SharpEventLog) | Windows event log querying |
| [**SharpDPAPI**](https://github.com/GhostPack/SharpDPAPI) | Windows DPAPI abuse |
| [**SharpChrome**](https://github.com/GhostPack/SharpChrome) | Chrome credential extraction |
| [**SharpCloud**](https://github.com/chrismaddalena/SharpCloud) | Cloud credential enumeration |
| [**SharpSQL**](https://github.com/NetSPI/SQL-Server-Query) | SQL Server enumeration |
| [**StandIn**](https://github.com/FuzzySecurity/StandIn) | AD post-exploitation toolkit |
| [**ADAPE**](https://github.com/hausec/ADAPE) | AD privilege escalation script |
| [**PersistenceSniper**](https://github.com/last-byte/PersistenceSniper) | Windows persistence enumeration |
| [**Kekeo**](https://github.com/gentilkiwi/kekeo) | Windows Kerberos exploitation |
| [**DPAPIck**](https://github.com/gentilkiwi/dpapick) | Windows DPAPI extraction |
| [**gpp-decrypt**](https://github.com/t0thkr1s/gpp-decrypt) | Group Policy Password decryption |
| [**Klist**](https://learn.microsoft.com/en-us/windows-server/administration/windows-commands/klist) | Kerberos ticket list |
| [**WMI**](https://learn.microsoft.com/en-us/windows/win32/wmisdk/wmi-start-page) | Windows Management Instrumentation |
| [**WinRM**](https://learn.microsoft.com/en-us/windows/win32/winrm/portal) | Windows Remote Management |
| [**PsExec**](https://learn.microsoft.com/en-us/sysinternals/downloads/psexec) | Remote process execution (Sysinternals) |
| [**Remote Desktop**](https://learn.microsoft.com/en-us/windows-server/remote/remote-desktop-services/clients/remote-desktop-clients) | Remote desktop protocol client |
| [**RDPCheck**](https://github.com/zerosum0x0/CVE-2019-0708) | RDP vulnerability testing |
| [**BlueKeep Scanner**](https://github.com/nccgroup/BLUEKEEP) | CVE-2019-0708 vulnerability scanner |
| [**SMBGhost Scanner**](https://github.com/ioncodes/SMBGhost) | CVE-2020-0796 vulnerability scanner |

---

## Docker & Container Security

Tools for container security assessment.

| Tool | Description |
|------|-------------|
| [**Trivy**](https://github.com/aquasecurity/trivy) | Container vulnerability scanner (Aqua) |
| [**Grype**](https://github.com/anchore/grype) | Container vulnerability scanner (Anchore) |
| [**Clair**](https://github.com/quay/clair) | Container vulnerability analysis (Red Hat) |
| [**Docker-Bench-Security**](https://github.com/docker/docker-bench-security) | CIS Docker benchmark automation |
| [**Kube-Bench**](https://github.com/aquasecurity/kube-bench) | CIS Kubernetes benchmark automation |
| [**Kube-Hunter**](https://github.com/aquasecurity/kube-hunter) | Kubernetes penetration testing |
| [**Kube-Scanner**](https://github.com/aquasecurity/kube-scanner) | Kubernetes vulnerability scanner |
| [**Popeye**](https://github.com/derailed/popeye) | Kubernetes cluster resource sanitizer |
| [**kapp**](https://github.com/k14s/kapp) | Kubernetes application security |
| [**Kubescape**](https://github.com/kubescape/kubescape) | Kubernetes security platform (ARMO) |
| [**Falco**](https://falco.org) | Container runtime security (Sysdig) |
| [**Aqua Security**](https://www.aquasec.com) | Container security platform |
| [**Twistlock**](https://www.paloaltonetworks.com/prisma/cloud) | Container security (Prisma Cloud) |
| [**Sysdig Secure**](https://sysdig.com) | Container forensics and security |
| [**Caps**](https://github.com/genuinetools/caps) | Container capability analysis |
| [**Deepfence**](https://github.com/deepfence/ThreatMapper) | Container threat detection |
| [**Dockle**](https://github.com/goodwithtech/dockle) | Container image linter |
| [**Hadolint**](https://github.com/hadolint/hadolint) | Dockerfile linter |
| [**Anchore**](https://anchore.com) | Container security analysis |
| [**Sysbox**](https://github.com/nestybox/sysbox) | Container runtime with enhanced isolation |
| [**gVisor**](https://gvisor.dev) | Container sandboxed runtime (Google) |
| [**Kata Containers**](https://katacontainers.io) | Container runtime with VM isolation |
| [**Firecracker**](https://firecracker-microvm.github.io) | MicroVM for containers (AWS) |
| [**Dive**](https://github.com/wagoodman/dive) | Container layer analysis |
| [**Container Diff**](https://github.com/GoogleContainerTools/container-diff) | Image comparison tool (Google) |
| [**BinScope**](https://github.com/GoogleCloudPlatform/binscope) | Container image analysis |
| [**Riscv-brute**](https://github.com/bitdefender/container-escape) | Container escape testing |

---

## Reporting & Collaboration

Tools for generating penetration testing reports.

| Tool | Description |
|------|-------------|
| [**Dradis**](https://dradisframework.com) | Collaboration and reporting platform |
| [**Serpico**](https://github.com/SerpicoProject/Serpico) | Penetration testing report generator |
| [**Faraday**](https://www.faradaysec.com) | Collaborative pentest platform |
| [**MagicTree**](https://www.gremwell.com) | Data management for pentests |
| [**CherryTree**](https://www.giuspen.com/cherrytree) | Hierarchical note-taking |
| [**Joplin**](https://joplinapp.org) | Markdown note-taking application |
| [**KeepNote**](https://keepnote.org) | Note-taking for pentesting |
| [**Pwndoc**](https://github.com/pwndoc/pwndoc) | Pentest report generation |
| [**Lair**](https://github.com/lair-framework/lair) | Collaborative pentest framework |
| [**Recon-ng Workspaces**](https://github.com/lanmaster53/recon-ng) | Recon data management |
| [**Pentest Collaborator**](https://github.com/nccgroup/pentest-collaborator) | Burp Collaborator alternative |
| [**Interactsh**](https://github.com/projectdiscovery/interactsh) | OOB interaction client (ProjectDiscovery) |
| [**Burp Collaborator**](https://portswigger.net/burp/documentation/collaborator) | OOB detection (PortSwigger) |
| [**OVAL**](https://oval.cisecurity.org) | Open Vulnerability and Assessment Language |
| [**X-Force**](https://exchange.xforce.ibmcloud.com) | Security issue tracking |
| [**Jira**](https://www.atlassian.com/software/jira) | Issue and project tracking |
| [**Confluence**](https://www.atlassian.com/software/confluence) | Documentation and collaboration |
| [**Obsidian**](https://obsidian.md) | Knowledge base and documentation |

| [**Sysmon**](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon) |Windows system monitoring and logging (Sysinternals) |

| [**Sigma**](https://github.com/SigmaHQ/sigma) |Generic SIEM rule format |

| [**HELK**](https://github.com/Cyb3rWard0g/HELK) |Hunting ELK logging platform |

| [**RQ**](https://github.com/rq/rq) |Python job queue for task processing |

| [**Celery**](https://github.com/celery/celery) |Distributed task queue |

| [**Redis**](https://redis.io) |In-memory data structure store |

| [**RabbitMQ**](https://www.rabbitmq.com) |Message broker for security pipelines |

| [**Kafka**](https://kafka.apache.org) |Distributed event streaming platform |

| [**MinIO**](https://min.io) |S3-compatible object storage |

| [**Caddy**](https://caddyserver.com) |Web server with automatic HTTPS |

| [**Nginx**](https://nginx.org) |High-performance web server and reverse proxy |

| [**Apache**](https://httpd.apache.org) |HTTP server and reverse proxy |

| [**HAProxy**](https://www.haproxy.org) |TCP/HTTP load balancer |

| [**Traefik**](https://traefik.io) |Cloud-native reverse proxy |

| [**Envoy**](https://www.envoyproxy.io) |Edge and service proxy (Lyft) |

| [**Istio**](https://istio.io) |Service mesh for Kubernetes |

| [**Linkerd**](https://linkerd.io) |Service mesh for Kubernetes |

| [**Consul**](https://www.consul.io) |Service mesh and discovery (HashiCorp) |

| [**Vault**](https://www.vaultproject.io) |Secrets management (HashiCorp) |

| [**Boundary**](https://www.boundaryproject.io) |Identity-based access management |

| [**Waypoint**](https://www.waypointproject.io) |Build and deployment platform |

| [**Packer**](https://www.packer.io) |Machine image builder (HashiCorp) |

| [**Vagrant**](https://www.vagrantup.com) |Development environment management |

| [**Nomad**](https://www.nomadproject.io) |Cluster scheduler (HashiCorp) |

| [**Raft**](https://raft.github.io) |Distributed consensus protocol implementation |

| [**etcd**](https://etcd.io) |Distributed key-value store (CoreOS) |

| [**ZooKeeper**](https://zookeeper.apache.org) |Distributed coordination service (Apache) |

| [**Consul Template**](https://github.com/hashicorp/consul-template) |Dynamic configuration rendering |

| [**Envconsul**](https://github.com/hashicorp/envconsul) |Environment variable management with Consul |

| [**Sentinel**](https://docs.hashicorp.com/sentinel) |Policy-as-code framework (HashiCorp) |

| [**OPA**](https://www.openpolicyagent.org) |Open Policy Agent - policy engine |

| [**Kyverno**](https://kyverno.io) |Kubernative policy management |

| [**Cert-Manager**](https://cert-manager.io) |Certificate management for Kubernetes |

| [**ExternalDNS**](https://github.com/kubernetes-sigs/external-dns) |DNS record management for K8s |

| [**Kustomize**](https://kustomize.io) |Kuberbetes config customization |

| [**Helm**](https://helm.sh) |Kuberbetes package manager |

| [**Skaffold**](https://skaffold.dev) |Development workflow for K8s |

| [**Tilt**](https://tilt.dev) |Development environment for K8s |

| [**K9s**](https://k9scli.io) |Terminal UI for Kubernetes |

| [**kubectx**](https://github.com/ahmetb/kubectx) |Switch Kubernetes contexts quickly |

| [**kubens**](https://github.com/ahmetb/kubens) |Switch Kubernetes namespaces quickly |

| [**stern**](https://github.com/stern/stern) |Multi-pod log tailing for K8s |

| [**Kubetail**](https://github.com/johanhaleby/kubetail) |Aggregate pod logs for Kubernetes |

| [**Kube-Forward**](https://github.com/kube-forward/kube-forward) |Forward ports to Kubernetes pods |

| [**Telepresence**](https://www.telepresence.io) |Local development for K8s |

| [**Octant**](https://octant.dev) |Web dashboard for Kubernetes (VMware) |

| [**Kubernetic**](https://kubernetic.com) |Desktop client for Kubernetes |

| [**Lens**](https://k8slens.dev) |Kuberbetes IDE (Mirantis) |

| [**Kui**](https://github.com/IBM/kui) |Terminal + GUI for Kubernetes |

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Disclaimer

These tools are intended for authorized security testing and educational purposes only. Unauthorized use against systems you do not own or have explicit permission to test is illegal. The authors assume no liability for misuse or damage caused by these tools.
