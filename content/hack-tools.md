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

## Remote Access Tools

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**


* [Pupy](https://github.com/n1nj4sec/pupy) :small_orange_diamond:
* [AhMyth](https://github.com/AhMyth/AhMyth-Android-RAT) :white_circle:
* [Empire](https://github.com/EmpireProject/Empire) :x:
* [SMBMap](https://github.com/ShawnDEvans/smbmap) :heavy_check_mark:   
    Funciona, puede cargar archivos a las rutas que la pc tenga desbloqueadas, funciona con algunas rutas, no ejecuta comandos y no se por que pero no me funciono en la Virtual machine.
* [RedSnarf](https://github.com/nccgroup/redsnarf) :small_orange_diamond:  
    Este necesita saver la contraseña de la victima.
* [smbexec](https://github.com/brav0hax/smbexec) :small_orange_diamond:
* [Koadic](https://github.com/zerosum0x0/koadic) :heavy_check_mark::whale:  
    Si funciona, puedes crear hasta sesiones de administrador. la vaina es que tienes que ejecutar un comando desde la terminal de la victima y siempre ejecuta una ventana en windows, cada vez  que ejcutas un comando desde la terminal remota. y en algunos casos activa el antivurus.
* [LFiFreak](https://github.com/OsandaMalith/LFiFreak) :small_orange_diamond:
* [Kwetza](https://github.com/sensepost/kwetza) :small_orange_diamond:  
    Para infestar una apk ya existente, y aprovecharse de los permisos.  
* [UACMe](https://github.com/hfiref0x/UACME) :small_orange_diamond:  
    Inicia una consola con privilegeos de administrador, creo que nada funciona con windows.
* [msfvenom](https://github.com/rapid7/metasploit-framework) :white_circle:
* [SpookFlare](https://github.com/hlldz/SpookFlare) :white_circle:  
    Para windwos, crea payload para acceso remoto y supuestamente es indetctabble para windows defender.

:moyai: _**devices**

* WiFi Duck

## Net Scaner

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* nmap :heavy_check_mark:

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
* [Net-Creds](https://github.com/DanMcInerney/net-creds) :white_circle:
    Busca credenciales como user y contrasenas, en protocolos como: HTTP,FTP,SMTP,SMB.
* [Airodump Scan Visualizer](https://github.com/pentesteracademy/airodump-scan-visualizer) :white_circle:
* [PCredz](https://github.com/lgandx/PCredz) :white_circle:
* [QRLJacking](https://github.com/OWASP/QRLJacking) :white_circle:
* [Wirespy](https://github.com/AresS31/wirespy) :white_circle:
    El mejor snifer que eh encontrado sin duda 
* [xerosploit](https://github.com/LionSec/xerosploit) :white_circle:
    Este tambien es bueno
* [SniffAir](https://github.com/Tylous/SniffAir) :white_circle:
* [Evilginx](https://github.com/kgretzky/evilginx) :white_circle:
* [BetterCAP](https://github.com/evilsocket/bettercap) :heavy_check_mark: :star:
* [mosint](https://github.com/alpkeskin/mosint) :white_circle:
    Busca informacion de un correo electronico, el detalle es que pide 3s apikeys de 3s lugares diferentes. y creo que son pagas.  
* [arpspoof](https://github.com/pentesteracademy/airodump-scan-visualizer) :white_circle:
* [MITMf](https://github.com/byt3bl33d3r/MITMf) :white_circle:
* [Fluxion](https://github.com/FluxionNetwork/fluxion) :white_circle:  
      Creo que captura el handchake.

:earth_americas: _**webs**  

## Spy

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [OSXChromeDecrypt](https://github.com/thanatoskira/OSXChromeDecrypt) :white_circle:
* [(s)AINT](https://github.com/tiagorlampert/sAINT) :white_circle:

## Trojan

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Trojanizer](https://github.com/r00t-3xp10it/trojanizer) :white_circle:
* [Macro Pack](https://github.com/sevagas/macro_pack) :white_circle:
* [Veil-Framework](https://github.com/Veil-Framework/Veil) :white_circle:

## Pass the hash attack

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Ketshash](https://github.com/cyberark/ketshash) :white_circle:

## brute froce & post explotation

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Enumdb](https://github.com/m8r0wn/enumdb) :white_circle:
* [Hydra](https://github.com/vanhauser-thc/thc-hydra) :white_circle:
* [Blazy](https://github.com/s0md3v/Blazy) :white_circle:

## meta exploit

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [Vulnerable OS Collection: Command Injection](https://github.com/pentesteracademy/vulnoscollection) :white_circle:

## Craking

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [hashcat](https://github.com/hashcat/hashcat) :white_circle:
* John the Ripper :white_circle:

## ONSIT

[:arrow_backward:](#nav) [back](#nav)  

:floppy_disk: _**command line**

* [OSRFramework](https://github.com/i3visio/osrframework) :heavy_check_mark:  
    No logro crear una imagen de docker
* [Iky](https://gitlab.com/kennbroorg/iKy.git) :white_circle:  
    Es parecido a sherlock, con la diferencia que tiene una UI que se crean en un servidor local. te deja buscar emails para saber en que red social se esta usando. (No se puede usar con docker)
* [Sublist3r](https://github.com/aboul3la/Sublist3r) :heavy_check_mark: :whale:  
    Sirve para enumerar los subdominios de un dominio.
  * [:whale:](https://hub.docker.com/repository/docker/capitanalgosa/sherlock) capitanalgosa
* [theHarvester](https://github.com/laramies/theHarvester) :heavy_check_mark: :whale:  
    Encuentra email en un dominio.  
  * [:whale:](https://github.com/Capitanalgosa/theharvester) capitanalgosa - official
* [twint](https://github.com/twintproject/twint) :white_circle:
* [Osintgram](https://github.com/Datalux/Osintgram) :heavy_check_mark: :whale:
  * [:whale:](https://hub.docker.com/repository/docker/capitanalgosa/osintgram) capitanalgosa, official
* [phoneinfoga](https://github.com/sundowndev/phoneinfoga) :white_circle:
  * [:whale:](https://hub.docker.com/repository/docker/capitanalgosa/phoneinfoga) capitanalgosa - official
  * [:whale:](https://hub.docker.com/r/sundowndev/phoneinfoga) official
* [sherlock](https://github.com/sherlock-project/sherlock) :heavy_check_mark: :star: :whale:
  * [:whale:](https://hub.docker.com/repository/docker/capitanalgosa/sherlock) capitanalgosa,official
* [skiptracer](https://gitlab.com/illwill/skiptracer) :white_circle:
* [fb-sleep-stats](https://github.com/sqren/fb-sleep-stats) :white_circle:
* [GHunt](https://github.com/mxrch/GHunt) :heavy_check_mark:
    Busca infromacion sobre cuentas gmail.
* [InstagramOSINT](https://github.com/sc1341/InstagramOSINT)

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

[proxychains](https://github.com/haad/proxychains) :white_circle:

:earth_americas: _**webs**  

* [spy.one](https://spys.one/en/)
* [free-proxy-list](https://free-proxy-list.net/)
* [freeproxylist](http://www.freeproxylists.net/)
* [hidemy.name](https://hidemy.name/es/proxy-list/)
* [free.proxy](http://free-proxy.cz/es/)
