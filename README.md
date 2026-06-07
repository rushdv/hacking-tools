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
| **Nmap** | Network discovery and security scanning |
| **Masscan** | Asynchronous TCP port scanner |
| **Zmap** | Internet-wide network scanner |
| **RustScan** | Blazing-fast port scanner with service discovery |
| **Unicornscan** | Asynchronous TCP/UDP scan engine |
| **Netcat (nc)** | Networking utility for reading/writing network connections |
| **Socat** | Multipurpose relay tool for bidirectional data transfer |
| **dnsrecon** | DNS enumeration script |
| **dnsenum** | Multi-threaded DNS enumeration |
| **fierce** | DNS reconnaissance tool |
| **theHarvester** | Email, subdomain, and name enumeration |
| **Recon-ng** | Full-featured reconnaissance framework |
| **Amass** | Subdomain discovery and network mapping |
| **Sublist3r** | Fast subdomain enumeration |
| **Subfinder** | Subdomain discovery tool |
| **Findomain** | Cross-platform subdomain enumerator |
| **Shodan** | Search engine for internet-connected devices |
| **Censys** | Internet asset discovery and monitoring |
| **Whois** | Domain registration information lookup |
| **Dig** | DNS lookup utility |
| **Nslookup** | Name server lookup tool |
| **Aquatone** | Visual inspection of websites across subdomains |
| **EyeWitness** | Screenshot capture of web services |
| **gowitness** | Web screenshot utility in Go |
| **httpx** | HTTP probing toolkit |
| **Httprobe** | Probe for working HTTP/HTTPS URLs |
| **whatweb** | Website technology fingerprinting |
| **Wappalyzer** | Cross-platform technology profiler |
| **BuiltWith** | Website technology lookup |
| **WAFW00F** | Web application firewall fingerprinting |
| **Netcraft** | Web server and hosting provider detection |
| **Traceroute** | Network path discovery |
| **MTR** | Network diagnostic tool combining traceroute and ping |
| **XProbe** | Active OS fingerprinting tool |
| **p0f** | Passive OS fingerprinting |
| **SMBMap** | SMB share enumeration |
| **enum4linux** | Windows/SMB enumeration tool |
| **nbtscan** | NetBIOS name scanner |
| **Ostorobako** | Information gathering via OSINT |
| **CloudEnum** | Cloud service enumeration |
| **CDNStrip** | CDN detection and bypass tool |

---

## Vulnerability Analysis

Tools for scanning and identifying vulnerabilities.

| Tool | Description |
|------|-------------|
| **Nessus** | Industry-standard vulnerability scanner |
| **OpenVAS** | Open-source vulnerability assessment system |
| **Nexpose** | Vulnerability management framework (Rapid7) |
| **Qualys** | Cloud-based vulnerability management |
| **Nikto** | Web server vulnerability scanner |
| **WPScan** | WordPress vulnerability scanner |
| **JoomScan** | Joomla vulnerability scanner |
| **Droopescan** | Drupal vulnerability scanner |
| **Vuls** | Agentless vulnerability scanner for Linux/FreeBSD |
| **Trivy** | Comprehensive vulnerability scanner for containers |
| **Grype** | Container and filesystem vulnerability scanner |
| **Snyk** | Developer-first vulnerability scanning |
| **Clair** | Container vulnerability analysis |
| **Lynis** | Security auditing tool for Linux/Unix |
| **Tiger** | Security audit tool for Unix |
| **CIS-CAT** | CIS benchmark assessment tool |
| **Skipfish** | Active web application security scanner |
| **Arachni** | Web application security scanner framework |
| **W3AF** | Web application attack and audit framework |
| **Acunetix** | Automated web vulnerability scanner |
| **AppScan** | Dynamic application security testing (HCL) |
| **Burp Suite Pro Scanner** | Integrated vulnerability scanner |
| **ZAP** | Zed Attack Proxy - web application scanner |
| **BlackDuck** | Open-source dependency vulnerability scanner |
| **Dependency-Check** | OWASP dependency vulnerability scanner |
| **Safety** | Python dependency vulnerability scanner |
| **Retire.js** | JavaScript library vulnerability scanner |
| **Nuclei** | Fast, template-based vulnerability scanner |
| **PoC-in-GitHub** | Collection of proof-of-concept exploits |

---

## Exploitation Frameworks

Frameworks designed to develop and execute exploits.

| Tool | Description |
|------|-------------|
| **Metasploit Framework** | Premier exploitation framework (Rapid7) |
| **Core Impact** | Commercial penetration testing framework |
| **Canvas** | Commercial exploitation framework (Immunity) |
| **Cobalt Strike** | Adversary simulation and threat emulation |
| **Brute Ratel C4** | Adversary simulation and red team tool |
| **Sliver** | Adversary emulation framework |
| **Empire** | Post-exploitation framework (PowerShell) |
| **Starkiller** | Frontend for Covenant C2 |
| **Covenant** | .NET C2 framework |
| **BeEF** | Browser Exploitation Framework |
| **RouterSploit** | Router exploitation framework |
| **HackTheBox Exploit** | Exploit development and execution |
| **SearchSploit** | Local Exploit-DB search tool |
| **Exploit-DB** | Public exploit repository (Offensive Security) |
| **Rapid7 Exploit DB** | Comprehensive exploit database |
| **PwnKit** | Local privilege escalation exploit collection |
| **Linux Exploit Suggester** | Kernel exploit suggestion tool |
| **Windows Exploit Suggester** | Windows kernel exploit suggestion |
| **PEASS-ng** | Privilege escalation awesome scripts suite |
| **LinPEAS** | Linux privilege escalation auditing |
| **WinPEAS** | Windows privilege escalation auditing |

---

## Web Application Testing

Tools for testing web application security.

| Tool | Description |
|------|-------------|
| **Burp Suite** | Web application security testing proxy |
| **OWASP ZAP** | Open-source web app scanner and proxy |
| **SQLMap** | Automated SQL injection tool |
| **NoSQLMap** | NoSQL injection and exploitation |
| **XSSer** | Cross-site scripting detection and exploitation |
| **XSStrike** | Advanced XSS detection and exploitation |
| **Commix** | Command injection exploitation |
| **LFISuite** | Local file inclusion exploitation |
| **tplmap** | Server-side template injection exploitation |
| **Jinja2 SSTI** | Jinja2 template injection exploitation |
| **Dirb** | Web directory scanner |
| **Dirbuster** | Directory brute-forcing tool (OWASP) |
| **Gobuster** | Directory/file/DNS/VHost brute-forcing |
| **Dirsearch** | Web directory scanner |
| **FFUF** | Fastest web fuzzer |
| **wfuzz** | Web application bruteforcer |
| **Hydra** | Network login cracker |
| **Patator** | Multi-purpose bruteforcer |
| **Medusa** | Parallel network login auditor |
| **Cewl** | Custom wordlist generator |
| **John the Ripper** | Password security auditing |
| **Hashcat** | Advanced password recovery |
| **CrackStation** | Password hash cracking service |
| **JWT_Tool** | JSON Web Token attack toolkit |
| **JWT Cracker** | JWT signing key brute-force |
| **JWT_Payload** | JWT payload manipulation |
| **CSRFTester** | Cross-site request forgery testing (OWASP) |
| **CSP Evaluator** | Content Security Policy evaluation |
| **CORS Scanner** | Cross-origin resource sharing scanner |
| **OpenRedireX** | Open redirect vulnerability scanner |
| **SSRFmap** | Server-side request forgery exploitation |
| **Gopherus** | SSRF exploitation via Gopher protocol |
| **S3Scanner** | Amazon S3 bucket enumeration |
| **Bucket Stream** | S3 bucket discovery and enumeration |
| **AWSBucketDump** | AWS S3 bucket discovery |
| **GraphQLmap** | GraphQL vulnerability testing |
| **InQL** | GraphQL security testing (intrusive) |
| **SwaggerSpy** | Swagger/OpenAPI endpoint discovery |

---

## Network Analysis & Sniffing

Tools for capturing and analyzing network traffic.

| Tool | Description |
|------|-------------|
| **Wireshark** | Network protocol analyzer |
| **TShark** | CLI network protocol analyzer |
| **tcpdump** | Packet capture and analysis |
| **Tcpick** | TCP stream reassembly |
| **Ngrep** | Network grep - packet matching |
| **BetterCAP** | MITM framework and network monitor |
| **Ettercap** | Comprehensive MITM framework |
| **Cain & Abel** | Password recovery and sniffing (Windows) |
| **Responder** | LLMNR/NBT-NS/mDNS poisoning |
| **Inveigh** | Windows LLMNR/NBNS/mDNS/DNS spoofing |
| **MITMf** | Man-in-the-middle framework |
| **MITMProxy** | Interactive HTTPS proxy |
| **sslstrip** | HTTPS stripping attack tool |
| **SSLsplit** | SSL/TLS interception and MITM |
| **Dsniff** | Collection of network auditing tools |
| **Arpspoof** | ARP spoofing utility |
| **Macof** | MAC flooding tool |
| **Yersinia** | Layer 2 attack framework |
| **Scapy** | Packet manipulation library |
| **Hping3** | Network packet crafting and analysis |
| **Nemesis** | Packet injection tool |
| **Packit** | Network packet generator |
| **NetFlow Analyzer** | Network traffic analysis |
| **nTop** | Network traffic monitoring |
| **Bro/Zeek** | Network security monitoring framework |
| **Suricata** | Network threat detection engine |
| **Snort** | Network intrusion detection/prevention |
| **Moloch/Arkime** | Large-scale PCAP indexing and search |
| **ChaosReader** | PCAP session reconstruction |
| **NetworkMiner** | Network forensic analysis |
| **PRTG** | Network monitoring and bandwidth analysis |
| **Zabbix** | Enterprise network monitoring |

---

## Password Attacks

Tools for password cracking, recovery, and authentication testing.

| Tool | Description |
|------|-------------|
| **Hashcat** | World's fastest password cracker |
| **John the Ripper** | Password security auditing tool |
| **Johnny** | GUI for John the Ripper |
| **Hash-Identifier** | Hash type identification |
| **HashID** | Hash algorithm identification |
| **ophcrack** | Windows password cracker using LM/NTLM |
| **chntpw** | Windows registry password reset utility |
| **SamInside** | Windows password recovery |
| **L0phtCrack** | Windows password auditing |
| **CrackMapExec** | Post-exploitation password testing |
| **Hydra** | Parallel network login cracker |
| **Medusa** | Parallel network login auditor |
| **NCrack** | Network authentication cracking |
| **Patator** | Multi-service bruteforce tool |
| **CeWL** | Custom wordlist generator by crawling |
| **Crunch** | Wordlist generator |
| **WordlistCtrl** | Wordlist manipulation toolkit |
| **SecLists** | Collection of security-related wordlists |
| **Probable Wordlists** | Real-world password wordlists |
| **RockYou** | Famous leaked password wordlist |
| **KeeFarce** | KeePass extraction tool |
| **KeeThief** | KeePass credential extraction |
| **Mimikatz** | Windows credential extraction |
| **LaZagne** | Credential recovery from installed apps |
| **BrowserGather** | Browser credential extraction |
| **WebBrowserPassView** | Browser password viewer (NirSoft) |
| **RDPassSpray** | RDP password spraying tool |
| **DomainPasswordSpray** | Active Directory password spraying |
| **Spray** | Password spray tool for multiple services |
| **BruteSpray** | Mass bruteforce from Nmap output |
| **Turbo Intruder** | HTTP bruteforce tool (PortSwigger) |

---

## Wireless Attacks

Tools for attacking wireless networks and protocols.

| Tool | Description |
|------|-------------|
| **Aircrack-ng** | 802.11 WEP/WPA-PSK cracking suite |
| **Airodump-ng** | Wireless packet capture |
| **Aireplay-ng** | Wireless packet injection |
| **Airmon-ng** | Wireless interface monitor mode |
| **Airbase-ng** | Rogue AP / fake access point |
| **Airgeddon** | Wireless security auditing script |
| **Wifite** | Automated wireless attack tool |
| **Wifiphisher** | Rogue AP phishing framework |
| **Fluxion** | WPA/WPA2 handshake capture and evil twin |
| **BetterCAP** | Wireless MITM and monitoring |
| **Kismet** | Wireless network detector and sniffer |
| **Reaver** | WPS brute-force attack |
| **Bully** | WPS brute-force attack (implementation) |
| **PixieWPS** | WPS offline bruteforce attack |
| **Wash** | WPS scan tool |
| **Cowpatty** | WPA-PSK cracking |
| **Pyrit** | WPA/WPA2 precomputed attack |
| **hashcat** | GPU-accelerated WPA cracking |
| **EWSA** | Elcomsoft Wireless Security Auditor |
| **MDK3** | Wireless DoS and exploitation |
| **MDK4** | Wireless exploitation framework (MDK3 successor) |
| **MFC** | Multi-function card for wireless attacks |
| **Hostapd-wpe** | WPA Enterprise authentication bypass |
| **EAPHammer** | Evil twin attack against WPA2-Enterprise |
| **AirSnort** | WEP key recovery |
| **WEPCrack** | WEP key cracker |
| **WPA_sycophant** | WPA EAP relay attack tool |
| **Horst** | Wireless spectrum analyzer |
| **WiFi Pineapple** | Rogue AP and MITM device (Hak5) |
| **WiFi Pumpkin** | Rogue AP framework for MITM |

---

## Bluetooth & RFID Attacks

Tools for Bluetooth and RFID/NFC security testing.

| Tool | Description |
|------|-------------|
| **BlueZ** | Official Linux Bluetooth protocol stack |
| **Bluetoothctl** | Bluetooth control utility |
| **BlueHydra** | Bluetooth device discovery |
| **BlueRanger** | Bluetooth device discovery |
| **BlueMaho** | Bluetooth hacking tool suite |
| **BTcrack** | Bluetooth passkey cracking |
| **CarWhisperer** | Bluetooth car audio exploitation |
| **Bluesnarfer** | Bluetooth OBEX push exploitation |
| **Btscanner** | Bluetooth device scanner |
| **HCIDump** | Bluetooth HCI packet dump |
| **Hcitool** | Bluetooth device configuration |
| **Sdptool** | Bluetooth service discovery |
| **L2ping** | Bluetooth L2CAP ping |
| **Redfang** | Bluetooth device discovery |
| **Ubertooth** | Bluetooth development and sniffing platform |
| **NRF24-BTLE** | Bluetooth Low Energy Sniffer |
| **BTLEJack** | Bluetooth LE exploitation |
| **GATTack** | Bluetooth GATT fuzzer |
| **BetterCAP BLE** | Bluetooth LE framework |
| **MFCUK** | Mifare Classic RFID tool |
| **MFOC** | Mifare Classic offline cracker |
| **Crapto1** | Mifare Classic encryption crack |
| **libnfc** | NFC library and tools |
| **NFC-Tools** | NFC tag manipulation |
| **Proxmark3** | RFID research and attack platform |
| **ChameleonMini** | RFID emulation platform |
| **OpenPCD** | RFID reader/writer |
| **OpenPICC** | RFID tag emulator |

---

## Reverse Engineering

Tools for analyzing and understanding binary code.

| Tool | Description |
|------|-------------|
| **Ghidra** | Reverse engineering framework (NSA) |
| **IDA Pro** | Interactive disassembler and debugger |
| **IDA Freeware** | Free version of IDA Pro |
| **Radare2** | Open-source reverse engineering framework |
| **Rizin** | Unix-based reverse engineering framework |
| **Binary Ninja** | Binary analysis platform (Vector 35) |
| **x64dbg** | Windows debugger (x64/x86) |
| **OllyDbg** | 32-bit Windows debugger |
| **Immunity Debugger** | Windows debugger with Python API |
| **WinDbg** | Windows kernel/user-mode debugger (Microsoft) |
| **GDB** | GNU debugger |
| **LLDB** | LLVM debugger |
| **Hopper** | Reverse engineering tool for macOS |
| **dnSpy** | .NET assembly editor and debugger |
| **ILSpy** | .NET assembly browser and decompiler |
| **dotPeek** | .NET decompiler (JetBrains) |
| **JD-GUI** | Java decompiler GUI |
| **JADX** | Android Dex-to-Java decompiler |
| **APKTool** | Android APK reverse engineering |
| **Smali/Baksmali** | Android Dalvik assembler/disassembler |
| **Bytecode Viewer** | Multi-feature Java/Android reverse engineering |
| **Procyon** | Java decompiler |
| **CFR** | Java decompiler |
| **Fernflower** | Java decompiler (Kotlin compatible) |
| **Uncompyle6** | Python bytecode decompiler |
| **Decompyle++** | Python decompiler |
| **ILdasm** | .NET IL disassembler |
| **Objdump** | GNU object file analysis |
| **Readelf** | ELF file analysis |
| **Strings** | Extract printable strings from binaries |
| **Hexdump** | Binary file hex viewer |
| **HxD** | Hex editor (Windows) |
| **010 Editor** | Professional hex editor |
| **ImHex** | Modern hex editor for reverse engineers |
| **FLOSS** | Obfuscated string extraction (Mandiant) |
| **Detect It Easy (DiE)** | File type and packer detection |
| **PEiD** | PE file packer detector |
| **CFF Explorer** | PE file editor |
| **LordPE** | PE file analysis |
| **Resource Hacker** | Windows resource editor |
| **UPX** | Ultimate Packer for eXecutables |
| **VMProtect** | Software protection (analysis) |
| **Themida** | Software protection (analysis) |
| **Angr** | Binary analysis framework (UCSB) |
| **Triton** | Dynamic binary analysis framework |
| **BAP** | Binary Analysis Platform |
| **Manticore** | Symbolic execution tool (Trail of Bits) |
| **Frida** | Dynamic instrumentation toolkit |
| **Unicorn** | CPU emulator framework |
| **QEMU** | Open-source machine emulator |
| **Panda** | Platform for architecture-neutral dynamic analysis |

---

## Forensics

Tools for digital forensic investigation and incident response.

| Tool | Description |
|------|-------------|
| **Autopsy** | Digital forensics platform (Sleuth Kit GUI) |
| **Sleuth Kit** | CLI forensic analysis tool collection |
| **FTK Imager** | Forensic disk imaging (AccessData) |
| **EnCase** | Enterprise forensic investigation (OpenText) |
| **Volatility** | Memory forensics framework |
| **Rekall** | Memory forensics analysis |
| **MemProcFS** | Memory process file system |
| **Redline** | Memory and file analysis (FireEye/Mandiant) |
| **KAPE** | Kroll Artifact Parser and Extractor |
| **CyLR** | Live response data collection |
| **Velociraptor** | Endpoint visibility and collection |
| **GRR** | Incident response framework (Google) |
| **OSQuery** | SQL-based endpoint instrumentation (Facebook) |
| **DFIR-Oracle** | DFIR data collection tool |
| **Foremost** | File carving utility |
| **Scalpel** | File carving and recovery |
| **PhotoRec** | File recovery software |
| **TestDisk** | Partition recovery and data recovery |
| **dd/dcfldd** | Disk imaging and duplication |
| **Guymager** | Forensic disk imager |
| **DC3DD** | DoD-compliant disk imaging |
| **Bulk Extractor** | Fast file scanning and extraction |
| **Strings** | String extraction from binaries |
| **Binwalk** | Firmware extraction and analysis |
| **Plaso** | Timeline generator (log2timeline) |
| **Timeline Explorer** | Windows forensic timeline (EZTools) |
| **Log2Timeline** | Timeline creation framework |
| **Wireshark** | Network forensic analysis |
| **NetworkMiner** | Network forensic analysis |
| **Xplico** | Network forensic analysis tool |
| **CAINE** | Forensic analysis environment |
| **SIFT** | SANS Investigative Forensics Toolkit |
| **Kali Linux Forensics Mode** | Debian-based forensic distro |
| **PALADIN** | Forensic Linux distribution |
| **DEFT** | Digital Evidence & Forensics Toolkit |
| **Rifiuti2** | Windows Recycle Bin analysis |
| **LECmd** | Windows LNK file analysis (EZTools) |
| **PECmd** | Windows prefetch analysis (EZTools) |
| **JumpList** | Windows Jump List analysis |
| **SBECmd** | Windows ShellBags analysis |
| **RECmd** | Windows Registry analysis (EZTools) |
| **Registry Explorer** | Windows Registry viewer (EZTools) |
| **Chromagnon** | Chrome browser forensics |
| **ChromeAnalysis** | Chrome forensics tool |
| **Browser History Examiner** | Browser forensics |
| **SQLite Browser** | SQLite database viewer |
| **HstEx** | Browser history recovery |
| **Belkasoft Evidence Center** | Digital forensics platform |
| **X-Ways Forensics** | Advanced forensics environment |
| **Magnet AXIOM** | Digital investigation platform |

---

## Post-Exploitation

Tools used after gaining initial access to a system.

| Tool | Description |
|------|-------------|
| **Mimikatz** | Windows credential extraction |
| **PowerShell Empire** | Post-exploitation PowerShell agent |
| **PowerSploit** | PowerShell post-exploitation framework |
| **Nishang** | PowerShell for exploitation and post-exploitation |
| **PoshC2** | C2 framework with PowerShell implants |
| **CrackMapExec** | Active Directory post-exploitation |
| **Impacket** | Collection of Python network protocols |
| **Impacket wmiexec** | WMI command execution |
| **Impacket psexec** | PSExec-style execution |
| **Impacket smbexec** | SMB command execution |
| **Impacket wmiquery** | WMI query tool |
| **Impacket secretsdump** | Windows secret extraction |
| **BloodHound** | Active Directory relationship mapping |
| **SharpHound** | BloodHound data collector (C#) |
| **PlumHound** | AD risk assessment with BloodHound |
| **ADExplorer** | Active Directory explorer (Sysinternals) |
| **ADRecon** | Active Directory reconnaissance |
| **ADAttackSuite** | Active Directory attack toolkit |
| **Rubeus** | Kerberos abuse toolkit (C#) |
| **Kerbrute** | Kerberos brute-force tool |
| **ASRepRoTool** | AS-REP roast attack tool |
| **Impacket GetNPUsers** | AS-REP roasting |
| **Impacket GetUserSPNs** | Kerberoasting |
| **Impacket ticketer** | Silver/Golden ticket creation |
| **Impacket goldenPac** | Golden ticket + PSExec |
| **LAPSToolkit** | LAPS abuse and enumeration |
| **PowerUp** | Windows privilege escalation |
| **PowerView** | Windows domain enumeration |
| **SharPersist** | Windows persistence toolkit |
| **SharPivot** | AD lateral movement |
| **SpoolSample** | MS-PRN printer bug exploitation |
| **Coercer** | Windows authentication coercion |
| **PetitPotam** | MS-EFSR abuse for relay |
| **ntlmrelayx** | NTLM relay attacks |
| **MultiRelay** | NTLM relay chaining |
| **Chisel** | Fast TCP/UDP tunnel over HTTP |
| **ligolo-ng** | Advanced SOCKS5 proxy tunneling |
| **FRP** | Fast Reverse Proxy |
| **Netsh** | Windows port forwarding |
| **SSH Tunneling** | Secure shell port forwarding |
| **Stowaway** | Multi-hop proxy tool |
| **Venom** | Multi-hop proxy for penetration testing |
| **EarthWorm** | SOCKS5 proxy and port forwarding |
| **Proxychains** | Force traffic through proxy chains |
| **socat** | Multipurpose relay and tunneling |

---

## Command & Control (C2) Frameworks

Frameworks for managing compromised systems.

| Tool | Description |
|------|-------------|
| **Cobalt Strike** | Adversary simulation and C2 |
| **Metasploit** | Exploitation and C2 capabilities |
| **Empire** | PowerShell/Python post-exploitation |
| **Covenant** | .NET C2 framework |
| **Sliver** | Implant-based C2 (BishopFox) |
| **Brute Ratel C4** | Adversary simulation C2 |
| **Nighthawk** | Advanced C2 framework (MDSec) |
| **Merlin** | Go-based C2 server |
| **Havoc C2** | Modern C2 framework |
| **DeimosC2** | C2 framework using gRPC |
| **Faction C2** | .NET C2 framework |
| **Shad0w C2** | .NET C2 with Beacon compatibility |
| **C3** | Custom Command and Control (C3) |
| **PoshC2** | PowerShell C2 server |
| **Koadic** | COM Command & Control |
| **Pupy** | Cross-platform C2 (Python) |
| **TrevorC2** | Deceptive C2 mechanism |
| **Mythic** | Multi-agent C2 framework |
| **Apfell** | macOS post-exploitation (Mythic) |
| **Athena** | Windows agent for Mythic |
| **Poseidon** | macOS agent for Mythic |
| **SilentTrinity** | Python-based C2 agent |
| **Phoenix C2** | C2 framework with multiple agents |
| **AsyncRAT** | Open-source remote administration tool |
| **Quasar RAT** | Remote administration tool (C#) |
| **Empire** | Post-exploitation C2 framework |
| **Cobalt Strike Malleable C2** | Custom C2 profile generation |

---

## Mobile Security Testing

Tools for testing mobile application security.

| Tool | Description |
|------|-------------|
| **MobSF** | Mobile Security Framework - static/dynamic analysis |
| **APKTool** | APK reverse engineering tool |
| **JADX** | Dex-to-Java decompiler |
| **JD-GUI** | Java decompiler |
| **Bytecode Viewer** | Multi-feature Java/Android decompiler |
| **Dex2Jar** | Convert Dex to Jar |
| **Frida** | Dynamic instrumentation for mobile apps |
| **Objection** | Runtime mobile exploration |
| **Xposed Framework** | Android module framework |
| **Cydia Substrate** | Android/iOS runtime modification |
| **Magisk** | Android systemless root |
| **iNalyzer** | iOS application analysis |
| **iRET** | iOS reverse engineering toolkit |
| **Needle** | iOS security testing framework |
| **Objection** | Mobile exploration (iOS/Android) |
| **Drozer** | Android security testing framework |
| **QARK** | Quick Android Review Kit |
| **Android Studio** | Android development and testing |
| **ADB** | Android Debug Bridge |
| **Xcode** | iOS development and testing |
| **Class-Dump** | Objective-C class dump |
| **Theos** | iOS development and tweak creation |
| **Cycript** | Objective-C and JavaScript runtime |
| **iFunBox** | iOS file manager |
| **FileZilla** | iOS file transfer |
| **ios-deploy** | iOS app deployment |
| **Idb** | iOS testing utility |
| **Hopper** | iOS/macOS disassembler |
| **Burp Suite** | Mobile web traffic interception |
| **MITMProxy** | Mobile HTTPS interception |
| **Objection** | Bypass SSL pinning |

---

## Malware Analysis

Tools for analyzing malicious software.

| Tool | Description |
|------|-------------|
| **Cuckoo Sandbox** | Automated malware analysis system |
| **CAPE** | Malware analysis and extraction (Cuckoo fork) |
| **VMRay** | Advanced malware analysis platform |
| **Joe Sandbox** | Deep malware analysis |
| **Any.Run** | Interactive malware analysis |
| **Hybrid Analysis** | Crowd-sourced malware analysis (Falcon) |
| **FireEye Malware Analysis** | Enterprise sandbox |
| **REMnux** | Linux distribution for reverse engineering |
| **FLOSS** | Obfuscated string extractor (Mandiant) |
| **YARA** | Malware identification and classification |
| **YARA-Gen** | YARA rule generator |
| **YAYA** | YARA Yet Another ruleset |
| **CapTipper** | HTTP malicious traffic analysis |
| **Volatility** | Memory malware analysis |
| **Process Hacker** | Process analysis (Windows) |
| **Process Monitor** | Real-time process monitoring (Sysinternals) |
| **Process Explorer** | Process exploration (Sysinternals) |
| **Autoruns** | Startup program analysis (Sysinternals) |
| **Regshot** | Registry snapshot and comparison |
| **API Monitor** | API call monitoring |
| **SpyStudio** | API hooking and monitoring |
| **Noriben** | Portable malware analysis sandbox |
| **FakeNet-NG** | Network simulation for malware analysis |
| **INetSim** | Internet service simulation |
| **TCPView** | Network connection viewer (Sysinternals) |
| **Wireshark** | Network traffic analysis |
| **ProcDOT** | Process monitoring visualization |
| **Hollows Hunter** | Process hollowing detection (hacker) |
| **PEStudio** | PE file analysis without execution |
| **Detect It Easy** | File type and packer detection |
| **ExeInfoPE** | PE file analysis and unpacking |
| **OLE Tools** | OLE/Office file analysis (Didier Stevens) |
| **PDF Tools** | PDF file analysis (Didier Stevens) |
| **Origami** | PDF file analysis framework |
| **peepdf** | PDF file analysis tool |
| **Viper** | Binary management and analysis framework |
| **MISP** | Malware information sharing platform |
| **ThreatConnect** | Threat intelligence platform |
| **Phantom** | SOAR platform (Splunk) |

---

## OSINT (Open Source Intelligence)

Tools for gathering intelligence from public sources.

| Tool | Description |
|------|-------------|
| **Maltego** | Link analysis and data mining |
| **theHarvester** | Email, subdomain, and name enumeration |
| **Recon-ng** | Web reconnaissance framework |
| **SpiderFoot** | OSINT automation tool |
| **SpiderFoot HX** | OSINT automation (community edition) |
| **Shodan** | IoT and device search engine |
| **Censys** | Internet asset search |
| **ZoomEye** | Cyberspace search engine |
| **Fofa** | Cyberspace asset search |
| **Google Dorks** | Advanced Google search operators |
| **GHDB** | Google Hacking Database |
| **Pagine** | Google dorking tool |
| **Dork-Scanner** | Google dork scanning tool |
| **GooFuzz** | Google dork fuzzing |
| **Wayback Machine** | Web archive (archive.org) |
| **WaybackURLs** | Wayback URL extraction |
| **Gau** | Get All URLs (TomNomNom) |
| **Hakrawler** | Web crawler for endpoints |
| **Katana** | Web crawling and URL extraction |
| **Social Mapper** | Social media profile mapping |
| **Twint** | Twitter scraping tool |
| **Tweets Analyzer** | Twitter data analysis |
| **Instagram Scraper** | Instagram data extraction |
| **Facebook Scraper** | Facebook data extraction |
| **LinkedIn Scraper** | LinkedIn data extraction |
| **GitDorker** | GitHub dorking tool |
| **GitHound** | GitHub data mining |
| **TruffleHog** | Git secrets scanning |
| **GitLeaks** | Git repository secrets detection |
| **GitRob** | GitHub sensitive data scanning |
| **Sherlock** | Username search across networks |
| **Holehe** | Email-to-account verification |
| **Infoga** | Email information gathering |
| **MailSniper** | Email enumeration and search |
| **Have I Been Pwned** | Breached account search |
| **DeHashed** | Credential leak search |
| **LeakCheck** | Data leak search engine |
| **Sn0int** | Semi-automatic OSINT framework |
| **Little Brother** | OSINT reconnaissance tool |
| **SkipTraces** | OSINT investigation framework |
| **MAT** | Metadata Anonymisation Toolkit |
| **ExifTool** | Metadata reading and writing |
| **GeoIP** | IP geolocation lookup |
| **IPinfo** | IP address information |
| **DNSDumpster** | DNS reconnaissance |
| **SecurityTrails** | DNS and IP history |

---

## Anonymity & Privacy

Tools for maintaining anonymity and privacy during testing.

| Tool | Description |
|------|-------------|
| **Tor** | Anonymous communication network |
| **Tor Browser** | Anonymized web browser |
| **Tails** | Privacy-focused Linux distribution |
| **Whonix** | Anonymity-focused operating system |
| **Qubes OS** | Security-focused desktop OS |
| **VPN** | Virtual Private Network services |
| **Proxychains** | Proxy routing for CLI tools |
| **Proxifier** | Global proxy forcing |
| **ProxyChains-NG** | Next-gen proxy chain tool |
| **Stunnel** | SSL tunneling |
| **OpenVPN** | Open-source VPN solution |
| **WireGuard** | Modern VPN protocol |
| **I2P** | Anonymous peer-to-peer network |
| **Freenet** | Decentralized censorship-resistant network |
| **Psiphon** | Circumvention tool |
| **Lantern** | Internet access circumvention |
| **DNSCrypt** | DNS traffic encryption |
| **DNSCrypt-Proxy** | Local DNS proxy with encryption |
| **Unbound** | Validating DNS resolver |
| **Torify** | Route traffic through Tor |
| **Torsocks** | SOCKS wrapper for Tor |
| **Zeronet** | Decentralized web using Bitcoin crypto |
| **MAC Changer** | MAC address spoofing |
| **SecureDelete** | Secure file deletion |
| **DBAN** | Hard drive data destruction |
| **CCleaner** | Privacy cleaning tool |
| **BleachBit** | System cleaner for privacy |

---

## Social Engineering

Tools for social engineering assessments.

| Tool | Description |
|------|-------------|
| **SET** | Social Engineering Toolkit (TrustedSec) |
| **Gophish** | Open-source phishing framework |
| **Evilginx2** | Phishing reverse proxy with 2FA bypass |
| **Modlishka** | Transparent phishing reverse proxy |
| **CredSniper** | Phishing framework with 2FA bypass |
| **King Phisher** | Phishing campaign toolkit |
| **Phish Shell** | Phishing framework with OTP bypass |
| **SocialFish** | Phishing framework (credential harvesting) |
| **HiddenEye** | Phishing framework with Telegram integration |
| **ZPhisher** | Advanced phishing tool |
| **BlackEye** | Phishing tool for credential harvesting |
| **ShellPhish** | Phishing tool for social media |
| **Nevul** | Phishing framework with OTP capture |
| **BeEF** | Browser Exploitation Framework |
| **Catphish** | Social engineering URL crafting |
| **Artichoke** | Phishing handler |
| **FiercePhish** | Phishing awareness training |
| **Lucy** | Phishing simulation and awareness |
| **PhishTank** | Phishing data sharing |
| **USB Rubber Ducky** | Keystroke injection tool (Hak5) |
| **Bash Bunny** | Multi-vector USB attack (Hak5) |
| **LAN Turtle** | Network attack and MITM device (Hak5) |
| **WiFi Pineapple** | Wireless auditing and phishing (Hak5) |
| **Key Croc** | Keystroke logging device (Hak5) |

---

## Fuzzing Tools

Tools for discovering vulnerabilities through input fuzzing.

| Tool | Description |
|------|-------------|
| **AFL** | American Fuzzy Lop - coverage-guided fuzzer |
| **AFL++** | Community-driven AFL fork with enhancements |
| **LibFuzzer** | In-process coverage-guided fuzzer (LLVM) |
| **Honggfuzz** | Coverage-guided fuzzer with hardware feedback |
| **OSS-Fuzz** | Continuous fuzzing service (Google) |
| **Peach Fuzzer** | Smart fuzzing framework |
| **Peach Pit** | Industrial fuzzing framework |
| **Syzkaller** | Kernel fuzzer (Google) |
| **TriforceAFL** | AFL for full-system fuzzing with QEMU |
| **BooFuzz** | Network protocol fuzzing framework |
| **Ffuf** | Fast web fuzzer |
| **Wfuzz** | Web application bruteforcer |
| **Burp Intruder** | Built-in fuzzer in Burp Suite |
| **Radamsa** | General-purpose test case fuzzer |
| **Sulley** | Fuzzing framework |
| **Kitty** | Python fuzzing framework |
| **CERT BFF** | Basic Fuzzing Framework (CERT/CC) |
| **Zzuf** | Transparent application fuzzer |
| **GPF** | General Purpose Fuzzer |
| **FileFuzz** | File format fuzzer |
| **Spike** | Protocol fuzzing toolkit (Immunity) |
| **Mutational Fuzzer** | Mutation-based fuzzing |
| **CrossFuzz** | Cross-browser DOM fuzzer |
| **FrameForge** | IE/Office fuzzer |
| **ProxyFuzz** | Network protocol fuzzing proxy |
| **SocketFuzz** | Network socket fuzzer |
| **FuzzDB** | Attack pattern and fuzzing dictionary |
| **JBroFuzz** | Web application fuzzer (OWASP) |

---

## Cloud Security

Tools for assessing cloud infrastructure security.

| Tool | Description |
|------|-------------|
| **ScoutSuite** | Multi-cloud security auditing tool |
| **Prowler** | AWS security assessment tool |
| **CloudSploit** | Cloud security scanning |
| **CloudMapper** | AWS network visualization and security |
| **CloudTracker** | AWS IAM credential tracking |
| **AWS-Inventory** | AWS resource inventory |
| **PMapper** | AWS IAM privilege escalation mapper |
| **Principal Mapper** | AWS IAM path analysis |
| **S3Scanner** | AWS S3 bucket enumeration |
| **Bucket Stream** | AWS S3 bucket discovery |
| **S3 Bucket Finder** | S3 bucket discovery |
| **CloudBrute** | Cloud infrastructure enumeration |
| **GCPBucketBrute** | Google Cloud Storage enumeration |
| **AzureBrute** | Azure resource enumeration |
| **Azurite** | Azure storage emulator |
| **MicroBurst** | Azure security testing toolkit |
| **Stormspotter** | Azure graph visualization |
| **BloodHound for Azure** | Azure AD relationship mapping |
| **AzureHound** | Azure AD data collector |
| **ROADtools** | Azure AD attack toolkit |
| **AADInternals** | Azure AD administration |
| **Terraform** | Infrastructure-as-code / misconfiguration testing |
| **Checkov** | IaC security scanning |
| **tfsec** | Terraform security scanner |
| **kics** | Infrastructure-as-code scanning (Checkmarx) |
| **Cloud Custodian** | Cloud governance and security |
| **Falco** | Container runtime security (Sysdig) |
| **Aqua Security** | Container security platform |
| **Twistlock** | Container security (Prisma Cloud) |
| **Sysdig Secure** | Container security and forensics |

---

## IoT & Hardware Security

Tools for testing IoT devices and embedded systems.

| Tool | Description |
|------|-------------|
| **Firmwalker** | Firmware extraction and analysis |
| **Binwalk** | Firmware reverse engineering |
| **Firmadyne** | Firmware emulation and analysis |
| **QEMU** | Full-system emulator for firmware |
| **QEMU-AFL** | Fuzzing firmware with QEMU |
| **AVR Fuse Breaker** | AVR fuse bit reset |
| **AVRDUDE** | AVR microcontroller programming |
| **Flashrom** | BIOS/ROM flashing utility |
| **JTAGulator** | JTAG/SWD pin identification |
| **OpenOCD** | On-chip debugger |
| **UrJTAG** | JTAG boundary scan tool |
| **Bus Pirate** | Bus analysis and hacking tool |
| **Logic Analyzer** | Digital signal analysis (Saleae) |
| **Saleae Logic** | Logic analyzer software |
| **PulseView** | Logic analyzer software (sigrok) |
| **sigrok-cli** | Signal analysis CLI tool |
| **Oscilloscope** | Analog signal analysis |
| **HackRF One** | Software-defined radio platform |
| **RTL-SDR** | Software-defined radio receiver |
| **GNU Radio** | SDR signal processing framework |
| **Universal Radio Hacker** | Wireless protocol analysis |
| **LTE-Cell-Scanner** | LTE base station scanning |
| **IMSI Catcher** | IMSI capturing device identification |
| **YateBTS** | Open-source BTS (base transceiver station) |
| **OpenBTS** | Base station software for GSM |
| **Airprobe** | GSM air interface analysis |
| **GR-GSM** | GNU Radio GSM receiver |
| **KillerBee** | ZigBee security analysis |
| **ZigDiggity** | ZigBee exploitation framework |
| **MQTT-PWN** | MQTT IoT protocol exploitation |
| **Exploit IoT** | IoT vulnerability scanner |
| **IoT Inspector** | IoT device traffic analysis |
| **Shodan** | IoT device search engine |

---

## DDoS Testing

Tools for testing denial-of-service resilience.

| Tool | Description |
|------|-------------|
| **LOIC** | Low Orbit Ion Cannon - DoS testing |
| **HOIC** | High Orbit Ion Cannon - DoS testing |
| **Slowloris** | Slow HTTP DoS attack |
| **SlowHTTPTest** | Slow HTTP DoS testing |
| **Hping3** | Network stress testing |
| **GoldenEye** | HTTP DoS testing tool |
| **Torshammer** | Slow rate DoS via Tor |
| **R.U.D.Y** | R-U-Dead-Yet slow DoS tool |
| **PyLoris** | Slow HTTP DoS testing |
| **DHCPig** | DHCP exhaustion attack tool |
| **Macof** | MAC flooding for switch DoS |
| **MDK3** | Wireless DoS testing |
| **Airplay-ng** | Wireless packet injection |
| **WFuzz** | Web stress testing |
| **Siege** | HTTP load testing |
| **Apache Bench (ab)** | HTTP server benchmarking |
| **WRK** | HTTP benchmarking tool |
| **Vegeta** | HTTP load testing tool (Go) |
| **SlowLoris** | Apache HTTP server DoS |
| **Sockstress** | TCP stack DoS analysis |
| **Nemesis** | Packet injection for DoS testing |
| **Bonesi** | Botnet simulation DoS tool |

---

## Steganography

Tools for hiding data within other data.

| Tool | Description |
|------|-------------|
| **Steghide** | Image/audio steganography |
| **OpenStego** | Steganography and watermarking |
| **StegSolve** | Image steganalysis |
| **StegDetect** | Steganography detection |
| **StirMark** | Image watermarking robustness test |
| **OutGuess** | Universal steganography tool |
| **JPHS** | JPEG steganography |
| **F5** | JPEG steganography algorithm |
| **MP3Stego** | MP3 audio steganography |
| **DeepSound** | Audio steganography |
| **Snow** | Whitespace steganography |
| **Coagula** | Image-to-sound steganography |
| **Spectrology** | Audio spectrogram steganography |
| **Zsteg** | PNG/BMP/GIF steganography detection |
| **PngCheck** | PNG file analysis |
| **ExifTool** | Metadata extraction and manipulation |
| **Binwalk** | File carving and data hiding detection |
| **Stegbreak** | Steganography brute-force detection |
| **Virtual Steganography** | Text-based steganography |
| **Steganography Studio** | Image steganography analysis |

---

## Database Security

Tools for database security assessment.

| Tool | Description |
|------|-------------|
| **SQLMap** | Automated SQL injection detection/exploitation |
| **jSQL Injection** | Java-based SQL injection tool |
| **BBQSQL** | Blind SQL injection framework |
| **NoSQLMap** | NoSQL injection and exploitation |
| **MongoSploit** | MongoDB exploitation |
| **Redis-rogue-server** | Redis RCE framework |
| **RedisExploit** | Redis exploitation |
| **ElasticSearch** | ES testing and exploitation |
| **MSSQL Brute** | SQL Server brute-force |
| **MYSQL Brute** | MySQL brute-force |
| **OracleDB Brute** | Oracle database brute-force |
| **SQL-Server-Query** | MSSQL query and enumeration |
| **DBeaver** | Universal database manager |
| **HeidiSQL** | Database administration (Windows) |
| **psql** | PostgreSQL CLI |
| **mysql CLI** | MySQL CLI |
| **MongoDB Shell** | MongoDB CLI |
| **Redis CLI** | Redis CLI |
| **Sqlninja** | MSSQL injection and exploitation |
| **SQLBrute** | SQL injection brute-force |

---

## Windows & Active Directory

Tools specific to Windows and AD security assessment.

| Tool | Description |
|------|-------------|
| **PowerShell** | Windows scripting and automation |
| **PowerView** | AD domain enumeration |
| **BloodHound** | AD privilege escalation visualization |
| **SharpHound** | BloodHound data collector |
| **Impacket** | Python AD protocol toolkit |
| **Mimikatz** | Windows credential extraction |
| **Rubeus** | Kerberos toolkit |
| **Kerbrute** | Kerberos brute-force |
| **LAPSToolkit** | LAPS abuse |
| **PowerUp** | Windows privilege escalation |
| **BeRoot** | Windows privilege escalation |
| **PrivescCheck** | Windows privilege escalation enumeration |
| **Seatbelt** | Windows security configuration enumeration |
| **SharpUp** | C# privilege escalation enumeration |
| **Watson** | Windows kernel exploit suggestion |
| **Sherlock** | Windows kernel exploit enumeration |
| **GhostPack** | Windows security toolkit collection |
| **SharpCollection** | Compiled Sharp tools |
| **SharpBlocks** | Windows event log manipulation |
| **SharpEventLog** | Windows event log querying |
| **SharpDPAPI** | Windows DPAPI abuse |
| **SharpChrome** | Chrome credential extraction |
| **SharpCloud** | Cloud credential enumeration |
| **SharpSQL** | SQL Server enumeration |
| **StandIn** | AD post-exploitation toolkit |
| **ADAPE** | AD privilege escalation script |
| **PersistenceSniper** | Windows persistence enumeration |
| **Kekeo** | Windows Kerberos exploitation |
| **DPAPIck** | Windows DPAPI extraction |
| **gpp-decrypt** | Group Policy Password decryption |
| **Klist** | Kerberos ticket list |
| **WMI** | Windows Management Instrumentation |
| **WinRM** | Windows Remote Management |
| **PsExec** | Remote process execution (Sysinternals) |
| **Remote Desktop** | Remote desktop protocol client |
| **RDPCheck** | RDP vulnerability testing |
| **BlueKeep Scanner** | CVE-2019-0708 vulnerability scanner |
| **SMBGhost Scanner** | CVE-2020-0796 vulnerability scanner |

---

## Docker & Container Security

Tools for container security assessment.

| Tool | Description |
|------|-------------|
| **Trivy** | Container vulnerability scanner (Aqua) |
| **Grype** | Container vulnerability scanner (Anchore) |
| **Clair** | Container vulnerability analysis (Red Hat) |
| **Docker-Bench-Security** | CIS Docker benchmark automation |
| **Kube-Bench** | CIS Kubernetes benchmark automation |
| **Kube-Hunter** | Kubernetes penetration testing |
| **Kube-Scanner** | Kubernetes vulnerability scanner |
| **Popeye** | Kubernetes cluster resource sanitizer |
| **kapp** | Kubernetes application security |
| **Kubescape** | Kubernetes security platform (ARMO) |
| **Falco** | Container runtime security (Sysdig) |
| **Aqua Security** | Container security platform |
| **Twistlock** | Container security (Prisma Cloud) |
| **Sysdig Secure** | Container forensics and security |
| **Caps** | Container capability analysis |
| **Deepfence** | Container threat detection |
| **Dockle** | Container image linter |
| **Hadolint** | Dockerfile linter |
| **Anchore** | Container security analysis |
| **Sysbox** | Container runtime with enhanced isolation |
| **gVisor** | Container sandboxed runtime (Google) |
| **Kata Containers** | Container runtime with VM isolation |
| **Firecracker** | MicroVM for containers (AWS) |
| **Dive** | Container layer analysis |
| **Container Diff** | Image comparison tool (Google) |
| **BinScope** | Container image analysis |
| **Riscv-brute** | Container escape testing |

---

## Reporting & Collaboration

Tools for generating penetration testing reports.

| Tool | Description |
|------|-------------|
| **Dradis** | Collaboration and reporting platform |
| **Serpico** | Penetration testing report generator |
| **Faraday** | Collaborative pentest platform |
| **MagicTree** | Data management for pentests |
| **CherryTree** | Hierarchical note-taking |
| **Joplin** | Markdown note-taking application |
| **KeepNote** | Note-taking for pentesting |
| **Pwndoc** | Pentest report generation |
| **Lair** | Collaborative pentest framework |
| **Recon-ng Workspaces** | Recon data management |
| **Pentest Collaborator** | Burp Collaborator alternative |
| **Interactsh** | OOB interaction client (ProjectDiscovery) |
| **Burp Collaborator** | OOB detection (PortSwigger) |
| **OVAL** | Open Vulnerability and Assessment Language |
| **X-Force** | Security issue tracking |
| **Jira** | Issue and project tracking |
| **Confluence** | Documentation and collaboration |
| **Obsidian** | Knowledge base and documentation |

| **Sysmon**|Windows system monitoring and logging (Sysinternals) |

| **Sigma**|Generic SIEM rule format |

| **HELK**|Hunting ELK logging platform |

| **RQ**|Python job queue for task processing |

| **Celery**|Distributed task queue |

| **Redis**|In-memory data structure store |

| **RabbitMQ**|Message broker for security pipelines |

| **Kafka**|Distributed event streaming platform |

| **MinIO**|S3-compatible object storage |

| **Caddy**|Web server with automatic HTTPS |

| **Nginx**|High-performance web server and reverse proxy |

| **Apache**|HTTP server and reverse proxy |

| **HAProxy**|TCP/HTTP load balancer |

| **Traefik**|Cloud-native reverse proxy |

| **Envoy**|Edge and service proxy (Lyft) |

| **Istio**|Service mesh for Kubernetes |

| **Linkerd**|Service mesh for Kubernetes |

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Disclaimer

These tools are intended for authorized security testing and educational purposes only. Unauthorized use against systems you do not own or have explicit permission to test is illegal. The authors assume no liability for misuse or damage caused by these tools.
