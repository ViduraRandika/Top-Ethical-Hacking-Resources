# Top-Ethical-Hacking-Resources
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-12-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
Stay up-to-date with the latest and greatest ethical hacking resources.

## Please read the [Guidelines for contributors](./contribution.md) first
## Table of contents
* [Wireless Hacking](#wireless-hacking)
* [Pen Testing](#pen-testing)
  * [Black Box](#black-box)
  * [Grey Box](#grey-box)
  * [White Box](#white-box)
  * [External Penetration Testing](#external-penetration-testing)
  * [Internal Penetration Testing](#internal-penetration-testing)
* [SQL Injection](#sql-injection)
* [DDOS Attacks](#ddos-attacks)
  * [Volume-based Attacks](#volume-based-attacks)
  * [Protocol Attacks](#protocol-attacks)
  * [Application Layer Attacks](#application-layer-attacks)
* [Social Engineering](#social-engineering)
* [Password Hacking](#password-hacking)
  * [Dictionary Attack](#dictionary-attack)
  * [Hybrid Dictionary Attack](#hybrid-dictionary-attack)
  * [Brute-Force Attack](#brute-force-attack)
  * [Rainbow Tables](#rainbow-tables)
* [TCP/IP Hijacking](#tcp/ip-hijacking)
* [Trojan Attacks](#trojan-attacks)
* [Other](#other)

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
=======

## Wireless Hacking

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [Kismet](https://www.kismetwireless.net/) | Kismet is a powerful tool for wireless sniffing that is found in Kali distribution | [How to use kismet](https://null-byte.wonderhowto.com/how-to/use-kismet-watch-wi-fi-user-activity-through-walls-0182214/)|
|[WireShark](https://www.wireshark.org/)|Wireshark is the world’s foremost and widely-used network protocol analyzer. It lets you see what’s happening on your network at a microscopic level |[How to use Wireshark](https://youtu.be/TkCSr30UojM)|
| [Aircrack](http://www.aircrack-ng.org/) | Aircrack is one of the most popular wireless passwords cracking tools which you can use for 802.11a/b/g WEP and WPA cracking. Aircrack uses the best algorithms to recover wireless passwords by capturing packets. | [How to use Aircrack](https://www.aircrack-ng.org/doku.php?id=cracking_wpa/)|
| [CloudCracker](https://crack.sh/) |CloudCracker is the online password cracking tool for cracking WPA protected wi-fi networks. This tool can also be used to crack different password hashes. | [How to use CloudCracker](https://crack.sh/get-cracking/)|
| [Wifite](https://github.com/derv82/wifite2) |This tool is fantastic and being able to attack multiple WEP, WPA, and WPS encrypted networks in a row. It’s fast becoming the industry’s favorite WiFi Hacking Tool for Pentesters. | [How to use Wifite](https://github.com/derv82/wifite2)|
| [KisMAC](https://kismac-ng.org/) |KisMac is tool very much similar to Kismet. It offers features similar to Kismet and is used as wireless network discovery hacking tool.This tool is only available for Mac. It scans for networks passively only on supported wireless cards and then try to crack WEP and WPA keys by using brute force or exploiting any flaw.| [How to use KisMAC](http://howto-onlinetutorial.blogspot.com/2012/12/how-to-use-kismac.html)|
| [NetStumbler](https://www.netstumbler.com/) |NetStumbler is a popular Windows tool to find open wireless access points. This tool is free and is available for Windows. A trimmed down version of the tool is also available. It is called MiniStumbler. Basically NetStumblet is used for wardriving, verifying network configurations, finding locations with a poor network, detecting unauthorized access points, | [How to use NetStumbler](https://www.nairaland.com/1254993/how-use-netstumbler-scanning-wireless)|


## Pen Testing

#### Black Box

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
|[Netsparker](https://www.netsparker.com/)|A common automated web program for black box and all penetration testing is the Netsparker Security Scanner. From cross-site scripting to SQL injection, the program can recognize anything from This tool can be used by developers on blogs , online servers, and web apps.|[How Netsparker Can Help](https://www.netsparker.com/external-vulnerability-scanner/black-box-scanner/)|
|[Wireshark](https://www.wireshark.org/)|Once known as Ethereal 0.2.0, with 600 contributors, Wireshark is an award-winning network analyzer. You can do BlackBox pen testing with wireshark easily. The tool is open-source and is available for Windows, Solaris, FreeBSD, and Debian, among other platforms.|[Black Box Network Penetration Testing Walkthrough](https://resources.infosecinstitute.com/blackbox-network-penetration-testing-walkthrough/)|
|[Metasploit framework](https://www.metasploit.com/)| The architecture for Metasploit is structured into modules. Exploit is the first sort of module. To take advantage of device vulnerabilities, Exploit modules are built. Buffer overload, program exploits and insertion of code are examples. Auxiliary modules carry out acts that do not take advantage of vulnerabilities explicitly.|[Introduction to Penetration Testing & Metasploit With Windows](https://blog.eduonix.com/networking-and-security/penetration-testing-metasploit-windows/)|
|[Selenium](https://www.selenium.dev/)|One of the well-known and popular tools among the testers is Selenium. It is an open-source tool that helps with browser automation. Selenium eases the pain to check whether an application works fine across the browsers and various versions.|[The Selenium Browser Automation Project](https://www.selenium.dev/documentation/en/)|
|[Appium](http://appium.io/)| Selenium doesn’t suffice mobile app testing, and thus Appium is present. It acts as a sweet companion to help extensive mobile testing. Appium works for cross platforms like iOS and Android.|[Getting Started Appium](http://appium.io/docs/en/about-appium/getting-started/index.html)|
|[Acunetix](https://www.acunetix.com/)| Acunetix is a fully automated web vulnerability scanner that detects and reports on over 4500 web application vulnerabilities including all variants of SQL Injection and XSS.It complements the role of a penetration tester by automating tasks that can take hours to test manually, delivering accurate results with no false positives at top speed. |[How to perform security testing using Acunetix](https://www.youtube.com/watch?v=vEAGPPANkVM)|
|[Hackerone](https://www.hackerone.com/)| Hackerone is one of the top security testing platforms. It can find and fix critical vulnerabilities. More and more Fortune 500 and Forbes Global 1000 companies choose HackerOne as it provides fast on-demand delivery. You can get started in just 7 days and get results in 4 weeks. |[From beginner to submitting 5 reports to HackerOne](https://dev.to/pirateducky/from-beginner-to-submitting-5-reports-to-hackerone-4goh)|
|[Intruder](https://www.intruder.io/internal-vulnerability-scanner)| Intruder is a powerful vulnerability scanner that finds cybersecurity weaknesses in your digital estate, and explains the risks & helps with their remediation before a breach can occur. It is the perfect tool to help automate your penetration testing efforts. |[Intruder Pricing, Features, Reviews & Comparison of Alternatives](https://www.getapp.com/security-software/a/intruder/)|
|[Core Impact](https://www.coresecurity.com/products/core-impact)| Core impact: With over 20 years in the market, Core Impact claims the largest range of exploits available in the market, they also let you run the free Metasploit exploits within their framework if they are missing one.  They automate a lot of processes with wizards, have a complete audit trail including PowerShell commands, and can re-test a client simply by re-playing the audit trail. |[Core Impact Tutorial](https://www.ethicalhacker.net/columns/jpeltier/core-impact-tutorial/)|
|[NMAP](https://nmap.org/)| This tool is used primarily for discovering just about kind of weaknesses or holes in the network environment of a business or a corporation. It can also be used for auditing purposes as well. NMAP can take the raw data packets.This tool can be used at any stage of the Pen Testing process, and even has built in scripting features available to help automate any testing process.|[How to Scan Your Network Using Nmap](https://www.youtube.com/watch?v=IoIsTrKrl-0)|
|[W3af](http://w3af.org/)|This Pen Testing suite has been created by the software developers at Metasploit, and its main purpose is to find, ascertain, and exploit any Security weaknesses or holes in Web based applications. The results of the Pen Test are displayed in both easy to understand graphical and text based formats.|[W3af walkthrough and tutorial](https://resources.infosecinstitute.com/w3af-tutorial/)|
|[Indusface WAS ](https://www.indusface.com/)|Indusface WAS provides both manual Penetration testing bundled with its own automated web application vulnerability scanner that detects and reports vulnerabilities based on OWASP top 10 and also includes a Website reputation check of links, malware and defacement checks of the website in every scan.|[How To Perform Web Application Security Testing Using AppTrana](https://www.softwaretestinghelp.com/apptrana-review-tutorial/)|

#### White Box

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [Veracode](https://www.veracode.com/) | Veracode’s white box testing tools will help you in identifying and resolving the software flaws quickly and easily at a reduced cost. It supports several application languages like .NET, C++, JAVA etc and also enables you to test the security of desktop, web as well as mobile applications. | [Getting Started to use Veracode](https://help.veracode.com/reader/kJC1iOtXp8N~rCtV8P9jhw/iSZSa4HHNIlkYx3q9W08Xg)|

## SQL Injection

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
|[SQLmap](https://github.com/sqlmapproject/sqlmap)|SQLMap is the open source SQL injection tool and most popular among all SQL injection tools available. This tool makes it easy to exploit the SQL injection vulnerability of a web application and take over the database server. It comes with a powerful detection engine which can easily detect most of the SQL injection related vulnerabilities.|[SQLmap Tutorial](https://hackertarget.com/sqlmap-tutorial/)|
|[SQLninja](http://sqlninja.sourceforge.net/)|SQLninja is a SQL injection tool that exploits web applications that use a SQL server as a database server. This tool may not find the injection place at first. But if it is discovered, it can easily automate the exploitation process and extract the information from the database server.|[Sqlninja user manual](http://sqlninja.sourceforge.net/sqlninja-howto.html)|

## DDOS Attacks

#### Volume-based Attacks

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [LOIC](https://www.imperva.com/learn/ddos/low-orbit-ion-cannon/) | Low Orbit Ion Cannon (LOIC) is a widely available, open-source application developed by Praetox Technologies used for network stress testing, as well as denial of service (DoS) and distributed denial of service (DDoS) attacks.It works by flooding a target server with TCP, UDP, or HTTP packets with the goal of disrupting service. | [Guide to use LOIC](https://vk9-sec.com/loic-dos-attacking-tool-guide/)|

#### Protocol Attacks

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
|[aSYNCrone](https://github.com/fatihsnsy/aSYNcrone)| aSYNCrone is a tool fro making TCP SYN Flooding attack. A denial-of - service attack that exploits the three-way handshake used by TCP / IP to create a link is SYN flooding. Basically, by generating several half-open links, SYN flooding disables a targeted scheme. |[How To Perform TCP SYN Flood DOS Attack using Kali Linux](https://www.crackitdown.com/2019/12/perform-syn-flood-dos-attack-using-kali-linux.html)|

#### Application Layer Attacks

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
|[Slowloris](https://github.com/gkbrk/slowloris)|Slowloris is basically an HTTP Denial of Service attack that affects threaded servers.This exhausts the servers thread pool and the server can't reply to other people.|[Performing a genuine slowloris attack ](https://ourcodeworld.com/articles/read/962/performing-a-genuine-slowloris-attack-slowhttp-of-indefinite-length-in-kali-linux)|


#### External Penetration Testing

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
|[Nmap](https://nmap.org/)| Nmap is the most popular method for network mapping in the world. It helps you to discover active hosts within any network and to gain other knowledge related to penetration testing (such as open ports).|[Penetration Testing for Beginners: Nmap](https://medium.com/@anuraagbaishya/penetration-testing-for-beginners-nmap-b3691682686d)|
|[NetCat](http://netcat.sourceforge.net/)| Netcat is a network discovery program that is common in the fields of network and device management, not just for those in the security industry. |[How to use netcat (nc), ncat - Ethical hacking and penetration](https://miloserdov.org/?p=2826)|
|[ Unicornscan](https://sectools.org/tool/unicornscan/)| Registered under a GPL license, Unicornscan is one of the best methods used for capturing information and correlating data. It provides advanced asynchronous scanning functionality for TCP and UDP, together with very helpful patterns of network exploration that will help you identify remote hosts. It will even disclose information about the program that each of them is using. |[Unicorn - Downgrade Attack & Inject Shellcode Into Memory](https://kalilinuxtutorials.com/unicorn-attack-inject-shellcode/)|

## Social Engineering
| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
|[social-engineer-toolkit](https://github.com/trustedsec/social-engineer-toolkit)|The Social-Engineer Toolkit (SET) is a social engineering open-source penetration testing platform. In a fraction of time, SET has a variety of custom attack vectors that allow you to make a credible attack. This kinds of instruments use human actions to lure the attack vectors into them.|[Let’s learn how to use the Social Engineer Toolkit.](https://www.tutorialspoint.com/kali_linux/kali_linux_social_engineering.htm)|

## Password Hacking

#### Dictionary Attack

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [Hydra](https://github.com/vanhauser-thc/thc-hydra) | Hydra is a parallelized network logon cracker. Hydra works by using different approaches of generating possible passwords, such as wordlist attacks, brute-force attacks and others. | [Brute force attack with Hydra](https://medium.com/@gtrekter/brute-force-attack-with-hydra-and-kali-linux-3c4ede55d119)|
| [Medusa](https://www.securedyou.com/medusa-free-download-parallel-password-cracker-tool/) | Medusa is an online password-cracking tool similar to THC Hydra. It claims to be a speedy parallel, modular and login brute-forcing tool. It supports HTTP, FTP, CVS, AFP, IMAP, MS SQL, MYSQL, NCP, NNTP, POP3, PostgreSQL, pcAnywhere, rlogin, SMB, rsh, SMTP, SNMP, SSH, SVN, VNC, VmAuthd and Telnet | [Medusa Parallel Network Login Auditor](http://foofus.net/goons/jmk/medusa/medusa.html)|

#### Brute-Force Attack

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [aircrack-ng](http://www.aircrack-ng.org/) | Aircrack-ng is a complete suite of tools to assess WiFi network security. All tools are command line which allows for heavy  scripting.A lot of GUIs have taken advantage of this feature. It works primarily Linux but also Windows, OS X,FreeBSD,OpenBSD,NetBSD as well as Solaris and even eComStation2.| [How to use aircrack-ng](https://www.aircrack-ng.org/doku.php?id=tutorial)|
| [John the Ripper](https://www.openwall.com/john/) | John the Ripper is an Open Source password security auditing and password recovery tool available for many operating systems. John the Ripper jumbo supports hundreds of hash and cipher types.|  [Brute force attack with John the Ripper](https://medium.com/@sc015020/how-to-crack-passwords-with-john-the-ripper-fdb98449ff1)|
| [L0phtCrack](https://www.l0phtcrack.com/) | L0phtCrack is a password audit and recovery program originally developed by Mudge from L0pht Heavy Industries. Using dictionaries, brute-force, hybrid attacks, and rainbow tables, it is used to test password strength and also to recover missing Microsoft Windows passwords.|  [Quick Start with the L0phtCrack 7](http://www.l0phtcrack.com/doc/QuickStartwiththeL0phtCrack7Wiza.html)|
| [Rainbowcrack](http://project-rainbowcrack.com/) | RainbowCrack is a computer program that creates a rainbow table that can be used to crack a password. RainbowCrack differs from "conventional" brute force crackers in that it uses huge pre-computed tables called rainbow tables to reduce the time required to crack a password significantly.|  [Brute force attack with Rainbowcrack](https://www.darknet.org.uk/2006/02/rainbowcrack-how-to-use-rainbow-crack-rainbow-tables/)|

#### Hybrid Dictionary Attack

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [hashcat](https://hashcat.net/hashcat/) | Hashcat, which supports five separate attack modes for over 200 highly optimized hashing algorithms, is the world's best and most advanced password recovery utility. Hashcat currently supports Linux, Windows, and OSX CPUs, GPUs, and other hardware accelerators, and has facilities to allow distributed password cracking.| [How to use HashCat](https://www.youtube.com/watch?v=m0AGSO1LDJs)|
| [windows_password_recovery_hybrid_dictionary_attack](https://www.passcape.com/windows_password_recovery_hybrid_dictionary_attack) | Windows Password Recovery distribution kit comes with extended sets of password mutation rules:<ul><li>hybrid_rules/english_words.ini file contains basic rules for English passwords.</li><li>hybrid_rules/nonenglish_words.ini holds common rules for non-Eglish passwords.</li><li>hybrid_rules/simple_dates.ini - a lot of rules with dates, months, seasons, etc.</li><li>hybrid_rules/l33t.ini - rules to freak words (based on the leet dictionary).</li></ul> For example, password->p@$$w0rd|  [Tutorial in passcape official website](https://www.passcape.com/windows_password_recovery_hybrid_dictionary_attack)|


#### Rainbow Tables

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [Ophcrack](https://ophcrack.sourceforge.io/) | Ophcrack is a free Windows password cracker based on rainbow tables. It is a very efficient implementation of rainbow tables done by the inventors of the method. It comes with a Graphical User Interface and runs on multiple platforms.| [How to Use Ophcrack](https://www.youtube.com/watch?v=Xka-0mQas64&ab_channel=SourceForge)|

## TCP/IP Hijacking

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [Ettercap](https://www.ettercap-project.org/) | Ettercap is a comprehensive suite for man in the middle attacks.It features sniffing of live connections, content filtering on the fly and many other interesting tricks. It supports active and passive dissection of many protocols and includes many features for network and host analysis. | [Ettercap user mannual](https://miloserdov.org/?p=1772)|

## Trojan Attacks

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [trojan-banker](https://www.kismetwireless.net/) | Trojan-Banker applications are designed to steal information from consumer accounts linked to internet banking, e-payment and plastic card schemes.| [How to create Undetectable Trojan Using a Domain Name](https://null-byte.wonderhowto.com/how-to/create-undetectable-trojan-using-domain-name-0171563/)|
| [metasploit](https://www.metasploit.com/) | Metasploit is a program that is pre-installed on all Kali Linux devices that allows you to produce custom payloads from the victim's device that will connect back to your device. The payload is our RAT in this situation. A hacker will build a payload using metasploit, save it to a file, and trick some innocent user by social engineering into clicking on it.| [How to Create a Trojan Virus in Kali Linux](https://livelinuxusb.com/create-trojan-virus-kali-linux/)|


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/ViduraRandika"><img src="https://avatars2.githubusercontent.com/u/56796456?v=4" width="100px;" alt=""/><br /><sub><b>ViduraRandika</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=ViduraRandika" title="Documentation">📖</a> <a href="#tutorial-ViduraRandika" title="Tutorials">✅</a> <a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/pulls?q=is%3Apr+reviewed-by%3AViduraRandika" title="Reviewed Pull Requests">👀</a> <a href="#example-ViduraRandika" title="Examples">💡</a> <a href="#ideas-ViduraRandika" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/lucifer955"><img src="https://avatars2.githubusercontent.com/u/37404014?v=4" width="100px;" alt=""/><br /><sub><b>Nadeera Hashan Kuruppu</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=lucifer955" title="Documentation">📖</a> <a href="#example-lucifer955" title="Examples">💡</a> <a href="#tutorial-lucifer955" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/RandilCPiumantha"><img src="https://avatars1.githubusercontent.com/u/56807975?v=4" width="100px;" alt=""/><br /><sub><b>RandilCPiumantha</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=RandilCPiumantha" title="Documentation">📖</a> <a href="#example-RandilCPiumantha" title="Examples">💡</a> <a href="#tutorial-RandilCPiumantha" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/Achiraisuru"><img src="https://avatars1.githubusercontent.com/u/55431705?v=4" width="100px;" alt=""/><br /><sub><b>Isuru Bandara</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Achiraisuru" title="Documentation">📖</a> <a href="#example-Achiraisuru" title="Examples">💡</a> <a href="#tutorial-Achiraisuru" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/DilshanUdawaththa"><img src="https://avatars2.githubusercontent.com/u/37608891?v=4" width="100px;" alt=""/><br /><sub><b>Dilshan Udawaththa</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=DilshanUdawaththa" title="Documentation">📖</a> <a href="#example-DilshanUdawaththa" title="Examples">💡</a> <a href="#tutorial-DilshanUdawaththa" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/Prabath03Dot"><img src="https://avatars1.githubusercontent.com/u/48862955?v=4" width="100px;" alt=""/><br /><sub><b>Prabath96</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Prabath03Dot" title="Documentation">📖</a> <a href="#example-Prabath03Dot" title="Examples">💡</a> <a href="#tutorial-Prabath03Dot" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/Hansajith98"><img src="https://avatars3.githubusercontent.com/u/54827047?v=4" width="100px;" alt=""/><br /><sub><b>Hansajith</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Hansajith98" title="Documentation">📖</a> <a href="#tutorial-Hansajith98" title="Tutorials">✅</a> <a href="#example-Hansajith98" title="Examples">💡</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/amaRanaweera"><img src="https://avatars1.githubusercontent.com/u/73416084?v=4" width="100px;" alt=""/><br /><sub><b>Amasha Ranaweera</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=amaRanaweera" title="Documentation">📖</a> <a href="#tutorial-amaRanaweera" title="Tutorials">✅</a> <a href="#example-amaRanaweera" title="Examples">💡</a></td>
    <td align="center"><a href="https://github.com/charithroshan"><img src="https://avatars2.githubusercontent.com/u/43004672?v=4" width="100px;" alt=""/><br /><sub><b>charithroshan</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=charithroshan" title="Documentation">📖</a> <a href="#tutorial-charithroshan" title="Tutorials">✅</a> <a href="#example-charithroshan" title="Examples">💡</a></td>
    <td align="center"><a href="https://github.com/PiyumiThathsarani"><img src="https://avatars1.githubusercontent.com/u/58032088?v=4" width="100px;" alt=""/><br /><sub><b>PiyumiThathsarani</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=PiyumiThathsarani" title="Documentation">📖</a> <a href="#example-PiyumiThathsarani" title="Examples">💡</a> <a href="#tutorial-PiyumiThathsarani" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/MS14-dev"><img src="https://avatars1.githubusercontent.com/u/54228656?v=4" width="100px;" alt=""/><br /><sub><b>Malindu Shamalka</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=MS14-dev" title="Documentation">📖</a> <a href="#tutorial-MS14-dev" title="Tutorials">✅</a> <a href="#example-MS14-dev" title="Examples">💡</a></td>
    <td align="center"><a href="https://github.com/Anne-98"><img src="https://avatars0.githubusercontent.com/u/58288067?v=4" width="100px;" alt=""/><br /><sub><b>Anne Sudari</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Anne-98" title="Documentation">📖</a> <a href="#tutorial-Anne-98" title="Tutorials">✅</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

