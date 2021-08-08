# Hack Tools

## Legenda

* Estado
  * :white_circle: No se ah usado
  * :heavy_check_mark: Probado y testeado
  * :whale: Con Imagen Docker
  * :x: Dead
  * :small_orange_diamond: Error: no se usar la herramienta o no se instalarla o tiene mucho errores.
  * :star: Favorito
* Typo
  * :earth_americas: Web site
  * :moyai: Devices
  * :floppy_disk: Command Line
  * :notebook: Xamples
  * :books: Docs
* Sistemas Operativos (S.O)
  * :apple: Apple
  * :penguin: Linux
  * :control_knobs: Windows
  * :alien: Android

## Syntax

/Estado/ | /S.O atacante/ | /S.O victima/ |

## nav

* [Remote Access Tools](#remote-access-tools)
* [Net Scaner](#net-scaner)
* [uncategorized](#uncategorized)
* [Penetration](#penetration)
* [Password finder](#password-finder)
* [Fishing](#fishing)
* [Sniff](#sniff)
* [Trojan](#trojan)
* [Spy](#spy)
* [Pass the hash attack](#pass-the-hash-attack)
* [brute froce & post explotation](#brute-froce-&-post-explotation)
* [Meta Exploit](#meta-exploit)
* [Craking](#craking)
* [ONSIT](#onsit)
* [VPN](#vpn)

## uncategorized

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* D Invoke :white_circle:
* [Wfuzz](https://github.com/xmendez/wfuzz) :white_circle:  
   Es para usar fuerza bruta para logearse en una pagina y para encontrar vulnerabildades.
* [Antipwny](https://github.com/rvazarkar/antipwny) :white_circle:  
    Ni idea
* [Bleah](https://github.com/evilsocket/bleah) :x:
* [Volatility](https://github.com/volatilityfoundation/volatility) :white_circle:  
    Analiza imagenes de sistema operativos, no se si analize el sistema operativo actual. seria logico no?
* [Evil-Droid](https://github.com/M4sc3r4n0/Evil-Droid) :white_circle:
* [SessionGopher](https://github.com/Arvanaghi/SessionGopher) :white_circle:  
    Guarda los archivos de autentificacion de PuTTY, WinSCP, FileZilla, SuperPuTTY, and RDP.
* aireplay-ng :white_circle:  
* [WAIDPS](https://github.com/SYWorks/waidps) :white_circle:  
    Wireless Auditing, Intrusion Detection & Prevention System.
* [Pythem](https://github.com/m4n3dw0lf/pythem) :white_circle:  
    pythem is a multi-purpose pentest framework written in Python. It has been developed to be used by security researchers and security professionals.
* [WiFi-Pumpkin](https://github.com/P0cL4bs/WiFi-Pumpkin) :x:  
    The WiFi-Pumpkin is a rogue AP framework to easily create these fake networks, all while forwarding legitimate traffic to and from the unsuspecting target. It comes stuffed with features, including rogue Wi-Fi access points, deauth attacks on client APs, a probe request and credentials monitor, transparent proxy, Windows update attack, phishing manager, ARP Poisoning, DNS Spoofing, Pumpkin-Proxy, and image capture on the fly. moreover, the WiFi-Pumpkin is a very complete framework for auditing Wi-Fi security check the list of features is quite broad.
* [wifipumpkin3](https://github.com/P0cL4bs/wifipumpkin3) :white_circle:  
     wifipumpkin3 is powerful framework for rogue access point attack, written in Python, that allow and offer to security researchers, red teamers and reverse engineers to mount a wireless network to conduct a man-in-the-middle attack.
* [jSQL Injection](https://github.com/ron190/jsql-injection) :white_circle:  
     jSQL Injection is a lightweight application used to find database information from a distant server.
* [Hcitool & Gatttool](https://github.com/aguedes/bluez) :white_circle:
* [Blue Hydra](https://github.com/pwnieexpress/blue_hydra) :white_circle:  
     BlueHydra is a Bluetooth device discovery service built on top of the bluez library. BlueHydra makes use of ubertooth where available and attempts to track both classic and low energy (LE) bluetooth devices over time.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) :white_circle:  
     sqlmap is an open source penetration testing tool that automates the process of detecting and exploiting SQL injection flaws and taking over of database servers. It comes with a powerful detection engine, many niche features for the ultimate penetration tester, and a broad range of switches including database fingerprinting, over data fetching from the database, accessing the underlying file system, and executing commands on the operating system via out-of-band connections.
* [wifiphisher](https://github.com/wifiphisher/wifiphisher) :white_circle:  
     Wifiphisher is a rogue Access Point framework for conducting red team engagements or Wi-Fi security testing. Using Wifiphisher, penetration testers can easily achieve a man-in-the-middle position against wireless clients by performing targeted Wi-Fi association attacks. Wifiphisher can be further used to mount victim-customized web phishing attacks against the connected clients in order to capture credentials (e.g. from third party login pages or WPA/WPA2 Pre-Shared Keys) or infect the victim stations with malwares.
* [Wifite2](https://github.com/derv82/wifite2) :white_circle:  
     This repo is a complete re-write of wifite, a Python script for auditing wireless networks. Wifite runs existing wireless-auditing tools for you. Stop memorizing command arguments & switches!. Wifite is designed to use all known methods for retrieving the password of a wireless access point (router).
* [Ncrack](https://github.com/nmap/ncrack) :white_circle:  
     Ncrack is a high-speed network authentication cracking tool. It was built to help companies secure their networks by proactively testing all their hosts and networking devices for poor passwords. Security professionals also rely on Ncrack when auditing their clients. Ncrack was designed using a modular approach, a command-line syntax similar to Nmap and a dynamic engine that can adapt its behaviour based on network feedback. It allows for rapid, yet reliable large-scale auditing of multiple hosts.
* [Commix](https://github.com/commixproject/commix) :white_circle:  
     Commix (short for [comm]and [i]njection e[x]ploiter) is an open source penetration testing tool, written by Anastasios Stasinopoulos (@ancst), that automates the detection and exploitation of command injection vulnerabilities.
* [BloodHound](https://github.com/BloodHoundAD/BloodHound) :white_circle:  
     BloodHound uses graph theory to reveal the hidden and often unintended relationships within an Active Directory environment. Attackers can use BloodHound to easily identify highly complex attack paths that would otherwise be impossible to quickly identify. Defenders can use BloodHound to identify and eliminate those same attack paths. Both blue and red teams can use BloodHound to easily gain a deeper understanding of privilege relationships in an Active Directory environment.
* [Autowasp](https://github.com/GovTechCSG/Autowasp) :white_circle:
* [goca](https://github.com/gocaio/goca) :white_circle:  
     Goca is a FOCA fork written in Go, which is a tool used mainly to find metadata and hidden information in the documents its scans. These documents may be on web pages, and can be downloaded and analyzed with Goca.

:earth_americas: _**webs**

* [exploit-db](https://www.exploit-db.com/) :white_circle:
* [cyberforensics](http://www.cyberforensics.in/AccessDenied.aspx?ReturnUrl=%2fProducts%2fCybercheck.aspx) :white_circle:
* [gmx](https://www.gmx.com/)   :white_circle:
    Para crear correos falsos. :white_circle:
* [virustotal](https://www.virustotal.com/gui/)   :white_circle:
    Para verificar si un archivo tiene un virus. :white_circle:

## Penetration

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [BruteSpray](https://github.com/x90skysn3k/brutespray) :white_circle:  
    BruteSpray takes nmap GNMAP/XML output or newline separated JSONS and automatically brute-forces services with default credentials using Medusa. BruteSpray can even find non-standard ports by using the -sV inside Nmap.

## Password finder

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Cr3dOv3r](https://github.com/D4Vinci/Cr3dOv3r) :white_circle:  
     Check if the targeted email is in any leaks and then use the leaked password to check it against the websites.

:earth_americas: _**webs**  

* [Google Hacking Database](https://www.exploit-db.com/)

## fishing

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Trape](https://github.com/boxug/trape) :white_circle:  
     Trape is an OSINT analysis and research tool, which allows people to track and execute intelligent social engineering attacks in real time. It was created with the aim of teaching the world how large Internet companies could obtain confidential information such as the status of sessions of their websites or services and control their users through their browser, without their knowledge, but It evolves with the aim of helping government organizations, companies and researchers to track the cybercriminals.
* [Phishery](https://github.com/ryhanson/phishery) :white_circle:  
     Phishery is a Simple SSL Enabled HTTP server with the primary purpose of phishing credentials via Basic Authentication. Phishery also provides the ability easily to inject the URL into a .docx Word document.

## Sniff

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [NetRipper](https://github.com/NytroRST/NetRipper) :white_circle:  
    NetRipper is a post exploitation tool targeting Windows systems which uses API hooking in order to intercept network traffic and encryption related functions from a low privileged user, being able to capture both plain-text traffic and encrypted traffic before encryption/after decryption.
* [Net-Creds](https://github.com/DanMcInerney/net-creds) :white_circle:  
    Busca credenciales como user y contrasenas, en protocolos como: HTTP,FTP,SMTP,SMB.
* [Airodump Scan Visualizer](https://github.com/pentesteracademy/airodump-scan-visualizer) :white_circle:  
    Airodump Scan Visualizer is a tool to present the Airodump-ng WiFi scan results in better organized, searchable, sortable manner with visualization support.
* [PCredz](https://github.com/lgandx/PCredz) :white_circle:  
    This tool extracts Credit card numbers, NTLM(DCE-RPC, HTTP, SQL, LDAP, etc), Kerberos (AS-REQ Pre-Auth etype 23), HTTP Basic, SNMP, POP, SMTP, FTP, IMAP, etc from a pcap file or from a live interface.
* [QRLJacking](https://github.com/OWASP/QRLJacking) :white_circle:  
    QRLJacking or Quick Response Code Login Jacking is a simple social engineering attack vector capable of session hijacking affecting all applications that rely on the “Login with QR code” feature as a secure way to login into accounts. In a nutshell, the victim scans the attacker’s QR code which results in session hijacking.
* [Wirespy](https://github.com/AresS31/wirespy) :white_circle:  
    WireSpy allows attackers to set up quick honeypots to carry out MITMAs. Monitoring and logging functionality is implemented in order to keep records of the victims' traffic/activities. Other tools can be used together with Wirespy to conduct more advanced attacks.
* [xerosploit](https://github.com/LionSec/xerosploit) :white_circle:  
    Xerosploit is a penetration testing toolkit whose goal is to perform man in the middle attacks for testing purposes. It brings various modules that allow to realise efficient attacks, and also allows to carry out denial of service attacks and port scanning. Powered by bettercap and nmap.
* [SniffAir](https://github.com/Tylous/SniffAir) :white_circle:  
    SniffAir is an open-source wireless security framework which provides the ability to easily parse passively collected wireless data as well as launch sophisticated wireless attacks. SniffAir takes care of the hassle associated with managing large or multiple pcap files while thoroughly cross-examining and analyzing the traffic, looking for potential security flaws. Along with the prebuilt queries, SniffAir allows users to create custom queries for analyzing the wireless data stored in the backend SQL database. SniffAir is built on the concept of using these queries to extract data for wireless penetration test reports. The data can also be leveraged in setting up sophisticated wireless attacks included in SniffAir as modules.
* [Evilginx](https://github.com/kgretzky/evilginx) :white_circle:  
    Evilginx is a man-in-the-middle attack framework used for phishing credentials and session cookies of any web service. It's core runs on Nginx HTTP server, which utilizes proxy_pass and sub_filter to proxy and modify HTTP content, while intercepting traffic between client and server.
* [BetterCAP](https://github.com/bettercap/bettercap) :heavy_check_mark: :star:  
    bettercap is a powerful, easily extensible and portable framework written in Go which aims to offer to security researchers, red teamers and reverse engineers an easy to use, all-in-one solution with all the features they might possibly need for performing reconnaissance and attacking WiFi networks, Bluetooth Low Energy devices, wireless HID devices and Ethernet networks. 
* [arpspoof](https://github.com/pentesteracademy/airodump-scan-visualizer) :white_circle:  
    Airodump Scan Visualizer is a tool to present the Airodump-ng WiFi scan results in better organized, searchable, sortable manner with visualization support.
* [MITMf](https://github.com/byt3bl33d3r/MITMf) :x:
* [Fluxion](https://github.com/FluxionNetwork/fluxion) :white_circle:  
      Fluxion is a security auditing and social-engineering research tool. It is a remake of linset by vk496 with (hopefully) fewer bugs and more functionality. The script attempts to retrieve the WPA/WPA2 key from a target access point by means of a social engineering (phishing) attack. It's compatible with the latest release of Kali (rolling). Fluxion's attacks' setup is mostly manual, but experimental auto-mode handles some of the attacks' setup parameters. Read the FAQ before requesting issues.

:earth_americas: _**webs**  

## Spy

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [OSXChromeDecrypt](https://github.com/thanatoskira/OSXChromeDecrypt) :white_circle:  
     Decrypt Google Chrome and Chromium Passwords on Mac OS X. No dependencies, quick, fast.
* [(s)AINT](https://github.com/tiagorlampert/sAINT) :x:

## Trojan

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Trojanizer](https://github.com/r00t-3xp10it/trojanizer) :white_circle:  
     The Trojanizer tool uses WinRAR (SFX) to compress the two files input by user,
and transforms it into an SFX executable(.exe) archive. The sfx archive when
executed it will run both files (our payload and the legit appl at the same time). To make the archive less suspicious to target at execution time, trojanizer will
try to replace the default icon(.ico) of the sfx file with a user-selected one,
and supress all SFX archive sandbox msgs (Silent=1 | Overwrite=1).
* [Macro Pack](https://github.com/sevagas/macro_pack) :white_circle:  
     The macro_pack is a tool used to automatize obfuscation and generation of retro formats such as MS Office documents or VBS like format. Now it also handles various shortcuts formats.
This tool can be used for redteaming, pentests, demos, and social engineering assessments. macro_pack will simplify antimalware solutions bypass and automatize the process from vb source to final Office document or other payload type.
* [Veil-Framework](https://github.com/Veil-Framework/Veil) :white_circle:  
    Veil is a tool designed to generate metasploit payloads that bypass common anti-virus solutions.

## Pass the hash attack

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Ketshash](https://github.com/cyberark/ketshash) :white_circle:  
    little tool for detecting suspicious privileged NTLM connections, in particular Pass-The-Hash attack, based on event viewer logs.

## brute froce & post explotation

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Enumdb](https://github.com/m8r0wn/enumdb) :white_circle:  
     Enumdb is a relational database brute force and post exploitation tool for MySQL and MSSQL. When provided a list of usernames and/or passwords, it will cycle through each host looking for valid credentials. By default, enumdb will use newly discovered credentials to automatically search for sensitive data fields via keyword searches on table or column names. This information can then be extracted and reported to a .csv or .xlsx output file.
* [Hydra](https://github.com/vanhauser-thc/thc-hydra) :white_circle:  
    Number one of the biggest security holes are passwords, as every password
security study shows.
This tool is a proof of concept code, to give researchers and security
consultants the possibility to show how easy it would be to gain unauthorized
access from remote to a system.
* [Blazy](https://github.com/s0md3v/Blazy) :white_circle:  
    Blazy is a modern login page bruteforcer.

## meta exploit

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Vulnerable OS Collection: Command Injection](https://github.com/pentesteracademy/vulnoscollection) :white_circle:  
     Vulnerable OS Collection is a collection of four Ubuntu based OSes which contain real world vulnerable web applications. The motive behind this project was to enable the pentesters to learn by doing practical attacks. The OSes comes in OVF format and can be imported into Oracle VirtualBox or VMware Workstation Player/Pro. This enables the pentesters to get these ready in less time and start practicing.

## Craking

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [hashcat](https://github.com/hashcat/hashcat) :white_circle:  
     hashcat is the world's fastest and most advanced password recovery utility, supporting five unique modes of attack for over 300 highly-optimized hashing algorithms. hashcat currently supports CPUs, GPUs, and other hardware accelerators on Linux, Windows, and macOS, and has facilities to help enable distributed password cracking.
* John the Ripper :white_circle:

## ONSIT

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [OSRFramework](https://github.com/i3visio/osrframework) :heavy_check_mark:  
    OSRFramework is a GNU AGPLv3+ set of libraries developed by i3visio to perform Open Source Intelligence collection tasks. They include references to a bunch of different applications related to username checking, DNS lookups, information leaks research, deep web search, regular expressions extraction and many others. At the same time, by means of ad-hoc Maltego transforms, OSRFramework provides a way of making these queries graphically as well as several interfaces to interact with like OSRFConsole or a Web interface.
* [Iky](https://gitlab.com/kennbroorg/iKy.git) :white_circle:  
    Project iKy is a tool that collects information from an email and shows results in a nice visual interface.
* [Sublist3r](https://github.com/aboul3la/Sublist3r) :heavy_check_mark: :whale:    
    Sublist3r is a python tool designed to enumerate subdomains of websites using OSINT. It helps penetration testers and bug hunters collect and gather subdomains for the domain they are targeting. Sublist3r enumerates subdomains using many search engines such as Google, Yahoo, Bing, Baidu and Ask. Sublist3r also enumerates subdomains using Netcraft, Virustotal, ThreatCrowd, DNSdumpster and ReverseDNS.
  * [:whale:](https://hub.docker.com/repository/docker/capitanalgosa/sherlock) capitanalgosa
* [theHarvester](https://github.com/laramies/theHarvester) :heavy_check_mark: [:whale:](https://github.com/Capitanalgosa/theharvester)  
      theHarvester is a very simple to use, yet powerful and effective tool designed to be used in the early stages of a
penetration test or red team engagement. Use it for open source intelligence (OSINT) gathering to help determine a
company's external threat landscape on the internet. The tool gathers emails, names, subdomains, IPs and URLs using
multiple public data sources that include:
* [twint](https://github.com/twintproject/twint) :white_circle:  
      Twint is an advanced Twitter scraping tool written in Python that allows for scraping Tweets from Twitter profiles without using Twitter's API.
* [Osintgram](https://github.com/Datalux/Osintgram) :heavy_check_mark: [:whale:](https://hub.docker.com/repository/docker/capitanalgosa/osintgram)  
     Osintgram is a OSINT tool on Instagram to collect, analyze, and run reconnaissance.
* [phoneinfoga](https://github.com/sundowndev/phoneinfoga) :white_circle: [:whale:](https://hub.docker.com/repository/docker/capitanalgosa/phoneinfoga "Capitanalgosa") [:whale:](https://hub.docker.com/r/sundowndev/phoneinfoga "Officical")  
     PhoneInfoga is one of the most advanced tools to scan international phone numbers using only free resources. It allows you to first gather standard information such as country, area, carrier and line type on any international phone number. Then search for footprints on search engines to try to find the VoIP provider or identify the owner.
* [sherlock](https://github.com/sherlock-project/sherlock) :heavy_check_mark: :star: [:whale:](https://hub.docker.com/repository/docker/capitanalgosa/sherlock)
     Hunt down social media accounts by username across social networks.
* [skiptracer](https://gitlab.com/illwill/skiptracer) :white_circle:  
    Initial attack vectors for recon usually involve utilizing pay-for-data/API (Recon-NG), or paying to utilize transforms (Maltego) to get data mining results. Skiptracer utilizes some basic python webscraping (BeautifulSoup) of PII paywall sites to compile passive information on a target on a ramen noodle budget.
* [fb-sleep-stats](https://github.com/sqren/fb-sleep-stats) :white_circle:  
    A small tool to show the potential privacy implications modern social media have. By tracking online/offline status of people on Facebook, it is possible to get an accurate image of their sleep pattern.
* [GHunt](https://github.com/mxrch/GHunt) :heavy_check_mark:  
    GHunt is a modulable OSINT tool designed to evolve over the years, and incorporates many techniques to investigate Google accounts, or objects.
* [InstagramOSINT](https://github.com/sc1341/InstagramOSINT)  :white_circle:  
    The Instagram OSINT Tool gets a range of information from an Instagram account that you normally wouldn't be able to get from just looking at their profile
* [mosint](https://github.com/alpkeskin/mosint) :white_circle:  
    MOSINT is an OSINT Tool for emails. It helps you gather information about the target email.

:earth_americas: _**webs**  

* Maltego
* [who.is](https://who.is/) :white_circle:
* [stalkface](https://stalkface.com/es/) :white_circle:
* [FB People Directory](https://www.facebook.com/directory/people/) :white_circle:
* [Search is Back](https://searchisback.com/) :white_circle:
* [Facebook Live Map](https://www.facebook.com/livemap#?rel=nofollow,noopener,noreferrer&target=_blank) :white_circle:
* [Facebook Email Search](https://www.facebook.com/search/top/?q=email%40gmail.com) :white_circle:
* [SecurityTrails](https://securitytrails.com) :white_circle:
* [hunter](https://hunter.io/verify/ricardo.torrejas@gmail.com) :white_circle:
* [mailtester](https://mailtester.com/en/single-email-verification) :white_circle:
* [centralops](https://centralops.net/co/emaildossier.aspx) :white_circle:
* [viewdns](https://viewdns.info/) :white_circle:
* [thatsthem](https://thatsthem.com/reverse-email-lookup) :white_circle:
* [domainbigdata](https://domainbigdata.com/) :white_circle:
* [whoxy](https://www.whoxy.com/) :white_circle:
* [haveibeenpwned](https://haveibeenpwned.com/) :white_circle:
* [dehashed](https://dehashed.com/?__cf_chl_jschl_tk__=3f81307f69c6a87eccb2dd3289991dd375a217c3-1624200797-0-ASa8RCZnzqinh8O5vIHHlQIGu28w1_Es5iT1Vdh8RaOpc4iytueZsVbZXO-Y7qLA87ZMBlRVdM_PaqMEX_sXi3TH-q8uHDK62nFfzKF9nqx-VBQhA_N_As9ylOd3egpJ01OGPIEsCm2tCA_RawGrpQiEbMbdyUHY3HTdyp4eM2rknjlEsdjmGyATM2eqhz1PtP00tvMIyYlBxE4VZgJFgeNaURqljJm6mLFA_6bIo1jwTkjROEkY6Kth0tP6Oe_6x6v2dZ3oWv4wIeiUwWeMR8ZXOp6jFqADQdJu3kHYKjjBWOYDyiMatrYoto4HoLFbGOfG-ElNiZGSadH8nLpw6o8iuMlC06KIwfcOKUkpV3qDHcpMkRHcoUfYJj09Yd0ufjuZzx2EDR06azB374I0F08) :white_circle:
* [metricsparrow](http://metricsparrow.com/toolkit/email-permutator/) :white_circle:
* [mxtoolbox](https://mxtoolbox.com/EmailHeaders.aspx) :white_circle:
* [whois.net](https://www.whois.net)
* [whois.icann.org](https://whois.icann.org/en)
* [whois.com](https://www.whois.com/whois/)
* [namecheap](https://www.namecheap.com/domains/who...)
* [register](http://www.register.com/whois.rcmx)
* [bbb](https://www.bbb.org/search)
* [manta](https://www.manta.com/)
* [homestars](https://homestars.com/bc/vancouver/categories)
* [donsearch](https://www.dobsearch.com/business-lookup/search-company-name.php)
* [sos.ca.gov](https://www.sos.ca.gov/business-programs/business-entities/)

## VPN

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [proxychains](https://github.com/haad/proxychains) :white_circle:  
ProxyChains is a UNIX program, that hooks network-related libc functions in dynamically linked programs via a preloaded DLL and redirects the connections through SOCKS4a/5 or HTTP proxies.

:earth_americas: _**webs**  

* [spy.one](https://spys.one/en/)
* [free-proxy-list](https://free-proxy-list.net/)
* [freeproxylist](http://www.freeproxylists.net/)
* [hidemy.name](https://hidemy.name/es/proxy-list/)
* [free.proxy](http://free-proxy.cz/es/)
