# Top-Ethical-Hacking-Resources
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-21-orange.svg?style=flat-square)](#contributors-)
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
|[Wifiphisher](https://wifiphisher.org/)|Wifiphisher is a tool designed to perform man-in-the-middle attacks by exploiting Wi-Fi association. By convincing wireless users to connect to the rogue access point, Wifiphisher provides an attacker with the ability to intercept and monitor or modify their wireless traffic.| [How to use Wifiphisher](https://youtu.be/ay-77C9ZZQM)|
|[inSSIDer](https://www.metageek.com/products/inssider/)|inSSIDer is a popular Wi-Fi scanner for Microsoft Windows and OS X operating systems. The inSSIDer wi-fi scanner can do various tasks, including finding open Wi-Fi access points, tracking signal strength and saving logs with GPS records.| [How to use inSSIDer](https://youtu.be/MLSITi0w0Bo)|
|[CoWPAtty](https://tools.kali.org/wireless-attacks/cowpatty)|CoWPAtty is an automated dictionary attack tool for WPA-PSK. It runs on Linux OS. This program has a command-line interface and runs on a word list that contains the password to use in the attack.|[How to use CoWPAtty](https://youtu.be/GAuiXr8mwOE)|
|[AirSnort](https://airsnort.soft112.com/)|AirSnort is free WiFi hacking software that captures the packets and tries to decrypt the keys. The monitoring is done in promiscuous mode and records enough packets to reliably decrypt the key. It is a simple tool and supports both Windows and Linux platforms.|[How to use AirSnort](https://www.youtube.com/watch?v=yTMaHf8byoo)|
|[Fern Wifi Cracker](https://www.securedyou.com/fern-wifi-cracker-pro-free-download/)|Fern WiFi Cracker is a python based tool that can be used for WEP/WPA/WPA2 cracking, session hijacking, ARP request replays, and performing brute force attacks. It is able to save the key in the database on a successful attack. It is compatible with various Linux OS and can also be run on Windows 10 using virtualization.|[How to use Fern Wifi Cracker](https://www.youtube.com/watch?v=P6V1udhKLCY)|
|[OmniPeek](https://www.bytesin.com/software/Download-OmniPeek-Personal/)|OmniPeek is a packet sniffer and a protocol analyzer tool. Developed by Savvis organization, It is available only for the Windows platform. The tool has a lot to offer if you have an understanding of the protocols.|[How to use OmniPeek](https://www.youtube.com/watch?v=Uhmv9rO_0fo)|
|[Airgeddon](https://securityonline.info/airgeddon-one-wireless-toolkit/)|Airgeddon is one of the latest and advanced wireless hacking tools. Similar to other hacking solutions it is capable of switching your interface mode from “Monitor” to “Managed”. Its core purpose is to audit wireless networks by using multi-use bash scripts for Linux systems.|[How to use Airgeddon](https://www.youtube.com/watch?v=MUVDkXO8v5Q)|
|[Yersinia](https://yersinia-multiattack-network-tool.soft112.com/)|Yersinia is an open-source wireless hacking software designed for Unix-like operating systems. This tool is capable of detecting susceptibilities in Layer 2 network protocols. It is a powerful tool for analyzing and testing the deployed wifi networks.|[How to use Yersinia](https://www.youtube.com/watch?v=dIPOXlUy7WE)|
|[Reaver](https://www.kali.org/tools/reaver/)|Reaver is an open-source password-cracking tool.  It performs a brute-force attack against WPS to break the security of Wi-Fi networks.Reaver has been designed to be a robust and practical attack against WPS, and has been tested against a wide variety of access points and WPS implementations.|[How to use Reaver](https://www.youtube.com/watch?v=Skv-mYPoIig)|




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
|[Ettercap](https://project-rainbowcrack.com/)|The Ettercap suite is designed to prevent man in the middle attacks. Using this application, you will be able to build the packets you want and perform specific tasks. The software can send invalid frames and complete techniques which are more difficult through other options.|[Ettercap and middle-attacks tutorial](https://pentestmag.com/ettercap-tutorial-for-windows/)|
|[Indusface WAS ](https://www.indusface.com/)|Indusface WAS provides both manual Penetration testing bundled with its own automated web application vulnerability scanner that detects and reports vulnerabilities based on OWASP top 10 and also includes a Website reputation check of links, malware and defacement checks of the website in every scan.|[How To Perform Web Application Security Testing Using AppTrana](https://www.softwaretestinghelp.com/apptrana-review-tutorial/)|
|[IBM (formerly Watchfire and Santum) Appscan](http://yamm.finance/wiki/Rational_AppScan.html)|IBM Security AppScan, previously known as IBM Rational AppScan, is a family of web security testing and monitoring tools from the Rational Software division of IBM. AppScan is intended to test Web applications for security vulnerabilities during the development process, when it is least expensive to fix such problems. The product learns the behavior of each application, whether an off-the-shelf application or internally developed, and develops a program intended to test all of its functions for both common and application-specific vulnerabilities.|[How to use IBM Security AppScan](https://www.youtube.com/watch?v=tAFVsI1URz8&ab_channel=MuhammadImran)|
|[Ranorex](https://www.ranorex.com/)|Ranorex Ranorex Studio is a commercial Windows platform that provides testing for desktop, web, and mobile applications. It was launched in 2007 by Ranorex GmbH, an Austria-based software development firm.Ranorex does not require any additional scripting programs. It is built on the Microsoft.NET platform. Ranorex is compatible with the industry-standard programming languages C# and VB.NET, allowing for the editing of recordings and the creation of custom tests.|[How To use Ranorex](https://www.youtube.com/watch?v=b1Ofv_TekbY&list=PLttK-VXRJYjYmfIfgmMsKFcK3JSltS5wM)|

#### White Box

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [Veracode](https://www.veracode.com/) | Veracode’s white box testing tools will help you in identifying and resolving the software flaws quickly and easily at a reduced cost. It supports several application languages like .NET, C++, JAVA etc and also enables you to test the security of desktop, web as well as mobile applications. | [Getting Started to use Veracode](https://help.veracode.com/reader/kJC1iOtXp8N~rCtV8P9jhw/iSZSa4HHNIlkYx3q9W08Xg)|
| [EclEmma](https://www.eclemma.org/) | EclEmma was initially designed for test runs and analysis within the Eclipse workbench. It is considered to be a free Java code coverage tool and has several features as well.| [Getting Started to use EclEmma](https://www.eclemma.org/index.html)|
| [RCUNIT](https://sourceforge.net/projects/rcunit/) | A framework which is used for testing C programs is known as RCUNIT. RCUNIT can be used accordingly based on the terms of the MIT License.| [Getting Started to use RCUNIT](https://github.com/jecklgamis/rcunit)|
| [cfix](https://sourceforge.net/projects/cfix/files/latest/download) | cfix is one of the unit testing frameworks for C/C++ which solely aims at making test suites development as simple and easy as possible. Meanwhile, cfix is typically specialized for NT Kernel mode and Win32.| [Getting Started to use cfix](https://github.com/jpassing/cfix)|

## SQL Injection

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
|[SQLmap](https://github.com/sqlmapproject/sqlmap)|SQLMap is the open source SQL injection tool and most popular among all SQL injection tools available. This tool makes it easy to exploit the SQL injection vulnerability of a web application and take over the database server. It comes with a powerful detection engine which can easily detect most of the SQL injection related vulnerabilities.|[SQLmap Tutorial](https://hackertarget.com/sqlmap-tutorial/)|
|[SQLninja](http://sqlninja.sourceforge.net/)|SQLninja is a SQL injection tool that exploits web applications that use a SQL server as a database server. This tool may not find the injection place at first. But if it is discovered, it can easily automate the exploitation process and extract the information from the database server.|[Sqlninja user manual](http://sqlninja.sourceforge.net/sqlninja-howto.html)|
|[whitewidow](https://github.com/WhitewidowScanner/whitewidow)|Whitewidow is an open source automated SQL vulnerability scanner, that is capable of running through a file list, or can scrape Google for potential vulnerable websites. It allows automatic file formatting, random user agents, IP addresses, server information, multiple SQL injection syntax, ability to launch sqlmap from the program, and a fun environment.|[whitewidow user manual](https://kalilinuxtutorials.com/whitewidow/)|
|[SQLSus](http://sqlsus.sourceforge.net/)|SQLSus is another open source SQL injection tool and is basically a MySQL injection and takeover tool. This tool is written in Perl and you can extend the functions by adding your own codes. This tool offers a command interface which lets you inject your own SQL queries and perform SQL injection attacks.|[SQLsus – MySql Injection Tutorial](https://www.ehacking.net/2011/11/sqlsus-mysql-injection-tutoria.html)|
|[explo](https://github.com/telekom-security/explo)|explo is a simple tool to describe web security issues in a human and machine readable format. By defining a request/condition workflow, explo is able to exploit security issues without the need of writing a script. This allows to share complex vulnerabilities in a simple readable and executable format.|[Telekom-security-explo Tutorial](https://github.com/telekom-security/explo)|
|[SQLSus](https://www.acunetix.com/websitesecurity/sql-injection/)|SQL Injection (SQLi) is a type of an injection attack that makes it possible to execute malicious SQL statements. These statements control a database server behind a web application. Attackers can use SQL Injection vulnerabilities to bypass application security measures. They can go around authentication and authorization of a web page or web application and retrieve the content of the entire SQL database.|[SQLsus – MySql Injection Tutorial](https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/)|
|[NoSQLMap](https://medium.com/rangeforce/nosqlmap-a67d76b88c48)|t NoSQLMap — a tool that is designed to find and exploit various NoSQL vulnerabilities. NoSQLMap is largely oriented towards testing MongoDB and CouchDB, but support for other NoSQL databases such as Redis and Cassandra is planned for future releases.|[NoSQLMap – MySql Injection Tutorial](https://www.youtube.com/watch?v=127BS4AmCuY)|
|[Blisqy](https://www.researchgate.net/publication/328880240_Time-Based_Blind_SQL_Injection_via_HTTP_Headers_Fuzzing_and_Exploitation)|Blisqy is a tool to aid Web Security researchers to find Time-based Blind SQL injection on HTTP Headers and also exploitation of the same vulnerability.The exploitation enables slow data siphon from a database (currently supports MySQL/MariaDB only) using bitwise operation on printable ASCII characters, via a blind-SQL injection. For interoperability with other Python tools and to enable other users utilise the features provided in Blisqy, the modules herein can be imported into other Python based scripts.|[Blisqy Injection Documentation](https://github.com/JohnTroony/Blisqy)|
|[BBQSQL](https://github.com/CiscoCXSecurity/bbqsql)|BBQSQL is a blind SQL injection framework written in Python. It is extremely useful when attacking tricky SQL injection vulnerabilities. BBQSQL is also a semi-automatic tool, allowing quite a bit of customization for those hard to trigger SQL injection findings. The tool is built to be database agnostic and is extremely versatile. It also has an intuitive UI to make setting up attacks much easier. Python gevent is also implemented, making BBQSQL extremely fast.|[BBQSQL Package Documentation](https://tools.kali.org/vulnerability-analysis/bbqsql)|
|[Mole](http://sourceforge.net/projects/themole/files/)|Mole, often known as (The Mole), is a free automatic SQL injection tool. This is a Sourceforge-hosted open source project. All you have to do now is discover the vulnerable URL and enter it into the program. Using Union-based or Boolean-based query techniques, this program can discover the vulnerability from the given URL. Although this utility has a command line interface, it is simple to use. Auto-completion is available for both commands and command arguments. As a result, this tool is simple to use.|[Mole Documentation](https://github.com/tiankonguse/themole)|
|[Safe3 SQL Injector](https://sourceforge.net/projects/safe3si/)|Another strong but simple to use SQL injection tool is Safe3 SQL Injector. It, like other SQL injection tools, automates the SQL injection process and aids attackers in exploiting the SQL injection vulnerability to obtain access to a remote SQL server. It features a strong AI engine that can quickly identify the database server, injection type, and the best strategy to exploit the flaw.|[Safe3 Package Documentation](https://sourceforge.net/projects/safe3si/)|
|[BSQL Hacker](https://www.darknet.org.uk/2008/09/bsql-hacker-automated-sql-injection-framework/)|BSQL Hacker is a useful SQL injection tool for performing SQL injection attacks on online sites. This solution is for individuals who need a SQL injection tool that works automatically. It's designed specifically for blind SQL injection. This program is quick and uses a multi-threaded approach to provide better and faster results.|[BSQL Hacker Download](http://resources.infosecinstitute.com/best-free-and-open-source-sql-injection-tools/#download)|
|[jSQL Injection](https://sourceforge.net/projects/jsqlinjection/)|Java Tool For Automatic SQL Database Injection. A lightweight application used to find database information from a distant server. It is free, open source and cross-platform.|[How to use jSQL Injection](https://www.youtube.com/watch?v=q7t9hirU9m8)|


## DDOS Attacks

#### Volume-based Attacks

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [LOIC](https://www.imperva.com/learn/ddos/low-orbit-ion-cannon/) | Low Orbit Ion Cannon (LOIC) is a widely available, open-source application developed by Praetox Technologies used for network stress testing, as well as denial of service (DoS) and distributed denial of service (DDoS) attacks.It works by flooding a target server with TCP, UDP, or HTTP packets with the goal of disrupting service. | [Guide to use LOIC](https://vk9-sec.com/loic-dos-attacking-tool-guide/)|
| [SYN flood](https://www.cloudflare.com/en-gb/learning/ddos/what-is-a-ddos-attack/) | LA SYN Flood is analogous to a worker in a supply room receiving requests from the front of the store.The worker receives a request, goes and gets the package, and waits for confirmation before bringing the package out front. The worker then gets many more package requests without confirmation until they can’t carry any more packages, become overwhelmed, and requests start going unanswered. | [Guide to use SYN flood](https://www.youtube.com/watch?v=tClcCMrXzek)|


#### Protocol Attacks

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
|[aSYNCrone](https://github.com/fatihsnsy/aSYNcrone)| aSYNCrone is a tool fro making TCP SYN Flooding attack. A denial-of - service attack that exploits the three-way handshake used by TCP / IP to create a link is SYN flooding. Basically, by generating several half-open links, SYN flooding disables a targeted scheme. |[How To Perform TCP SYN Flood DOS Attack using Kali Linux](https://www.crackitdown.com/2019/12/perform-syn-flood-dos-attack-using-kali-linux.html)|
|[HULK](https://github.com/grafov/hulk)| HULK stands for HTTP Unbearable Load King. It is a DoS attack tool for the web server. It is created for research purposes. This tool targeted for stress testing and may really down badly configured server or badly made app. |[How to use HULK](https://allabouttesting.org/hulk-ddos-tool-complete-installation-usage-with-examples/)|

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
|[ Watering hole](https://searchsecurity.techtarget.com/definition/watering-hole-attack)| A watering hole attack involves launching or downloading malicious code from a legitimate website, which is commonly visited by the targets of the attack. For example, attackers might compromise a financial industry news site, knowing that individuals who work in finance and thus represent an attractive target, are likely to visit this site. The compromised site typically installs a backdoor trojan that allows the attacker to compromise and remotely control the victim’s device.. |[infecting websites with malware that the targeted victims were likely to visit.](https://www.jigsawacademy.com/blogs/cyber-security/watering-hole-attack/)|
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
| [Dirsearch](https://github.com/maurosoria/dirsearch) | Dirsearch is an advanced brute force tool based on a command line. It’s an AKA web path scanner and can brute force directories and files in webservers.Dirsearch recently becomes part of the official Kali Linux packages, but it also runs on Windows, Linux, and macOS. It’s written in Python to be easily compatible with existing projects and scripts.It’s also much faster than the traditional DIRB tool and contains many more features.|  [Brute force attack with Dirsearch](https://asciinema.org/a/380112)|
| [Mask attack](https://hashcat.net/wiki/doku.php?id=mask_attack) | By incorporating part of the password that a hacker already knows in the attack, a mask attack minimizes the burden of a brute force attack. If a hacker knows your password is 10 characters long, for example, they can narrow down the assault to only those passwords. Mask attacks can be used to filter passwords based on specific words, numbers within a specified range, the user's preferred special characters, or any other password features the hacker is confident in. If any of your data is exposed, you become more vulnerable to a full-fledged data breach. | [Hachcat Mask Attack Tutorial](https://www.youtube.com%2Fwatch%3Fv%3DRiX0zfWHS9k&usg=AOvVaw0TcfmD3whLNgrcOj6eknBQ) |

#### Hybrid Dictionary Attack

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [hashcat](https://hashcat.net/hashcat/) | Hashcat, which supports five separate attack modes for over 200 highly optimized hashing algorithms, is the world's best and most advanced password recovery utility. Hashcat currently supports Linux, Windows, and OSX CPUs, GPUs, and other hardware accelerators, and has facilities to allow distributed password cracking.| [How to use HashCat](https://www.youtube.com/watch?v=m0AGSO1LDJs)|
| [windows_password_recovery_hybrid_dictionary_attack](https://www.passcape.com/windows_password_recovery_hybrid_dictionary_attack) | Windows Password Recovery distribution kit comes with extended sets of password mutation rules:<ul><li>hybrid_rules/english_words.ini file contains basic rules for English passwords.</li><li>hybrid_rules/nonenglish_words.ini holds common rules for non-Eglish passwords.</li><li>hybrid_rules/simple_dates.ini - a lot of rules with dates, months, seasons, etc.</li><li>hybrid_rules/l33t.ini - rules to freak words (based on the leet dictionary).</li></ul> For example, password->p@$$w0rd|  [Tutorial in passcape official website](https://www.passcape.com/windows_password_recovery_hybrid_dictionary_attack)|


#### Rainbow Tables

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [Ophcrack](https://ophcrack.sourceforge.io/) | Ophcrack is a free Windows password cracker based on rainbow tables. It is a very efficient implementation of rainbow tables done by the inventors of the method. It comes with a Graphical User Interface and runs on multiple platforms.| [How to Use Ophcrack](https://www.youtube.com/watch?v=Xka-0mQas64&ab_channel=SourceForge)|
| [RainbowCrack](https://project-rainbowcrack.com/) | RainbowCrack is a general propose implementation of Philippe Oechslin’s faster time-memory trade-off technique. It crack hashes with rainbow tables.| [How to Use RainbowCrack](https://tools.kali.org/password-attacks/rainbowcrack)|

## TCP/IP Hijacking

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [Ettercap](https://www.ettercap-project.org/) | Ettercap is a comprehensive suite for man in the middle attacks.It features sniffing of live connections, content filtering on the fly and many other interesting tricks. It supports active and passive dissection of many protocols and includes many features for network and host analysis. | [Ettercap user mannual](https://miloserdov.org/?p=1772)|

## Trojan Attacks

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [trojan-banker](https://www.kismetwireless.net/) | Trojan-Banker applications are designed to steal information from consumer accounts linked to internet banking, e-payment and plastic card schemes.| [How to create Undetectable Trojan Using a Domain Name](https://null-byte.wonderhowto.com/how-to/create-undetectable-trojan-using-domain-name-0171563/)|
| [metasploit](https://www.metasploit.com/) | Metasploit is a program that is pre-installed on all Kali Linux devices that allows you to produce custom payloads from the victim's device that will connect back to your device. The payload is our RAT in this situation. A hacker will build a payload using metasploit, save it to a file, and trick some innocent user by social engineering into clicking on it.| [How to Create a Trojan Virus in Kali Linux](https://livelinuxusb.com/create-trojan-virus-kali-linux/)|
| [ArcBombs](https://www.prosense.net/en/products/calorimetry/arc-bombs/) | These Trojans represent special archives that are designed to behave abnormally when users try to unpack them. ArcBomb archives either freeze or seriously slow the system. Malicious archives use different techniques to achieve their goal. They may use malcrafted headers or corrupt data that lead to a malfunction of an archiver or an unpacking algorithm. They may also contain a heavyweight object that consists of identical, repeating data that can be packed into a small archive. For example, 10 GB of data is packed into a 400 KB archive.| [TROJAN-ARCBOMB](https://threats.kaspersky.com/en/class/Trojan-ArcBomb/)|



## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/ViduraRandika"><img src="https://avatars2.githubusercontent.com/u/56796456?v=4?s=100" width="100px;" alt=""/><br /><sub><b>ViduraRandika</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=ViduraRandika" title="Documentation">📖</a> <a href="#tutorial-ViduraRandika" title="Tutorials">✅</a> <a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/pulls?q=is%3Apr+reviewed-by%3AViduraRandika" title="Reviewed Pull Requests">👀</a> <a href="#example-ViduraRandika" title="Examples">💡</a> <a href="#ideas-ViduraRandika" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/lucifer955"><img src="https://avatars2.githubusercontent.com/u/37404014?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nadeera Hashan Kuruppu</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=lucifer955" title="Documentation">📖</a> <a href="#example-lucifer955" title="Examples">💡</a> <a href="#tutorial-lucifer955" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/RandilCPiumantha"><img src="https://avatars1.githubusercontent.com/u/56807975?v=4?s=100" width="100px;" alt=""/><br /><sub><b>RandilCPiumantha</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=RandilCPiumantha" title="Documentation">📖</a> <a href="#example-RandilCPiumantha" title="Examples">💡</a> <a href="#tutorial-RandilCPiumantha" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/Achiraisuru"><img src="https://avatars1.githubusercontent.com/u/55431705?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Isuru Bandara</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Achiraisuru" title="Documentation">📖</a> <a href="#example-Achiraisuru" title="Examples">💡</a> <a href="#tutorial-Achiraisuru" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/DilshanUdawaththa"><img src="https://avatars2.githubusercontent.com/u/37608891?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dilshan Udawaththa</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=DilshanUdawaththa" title="Documentation">📖</a> <a href="#example-DilshanUdawaththa" title="Examples">💡</a> <a href="#tutorial-DilshanUdawaththa" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/Prabath03Dot"><img src="https://avatars1.githubusercontent.com/u/48862955?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Prabath96</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Prabath03Dot" title="Documentation">📖</a> <a href="#example-Prabath03Dot" title="Examples">💡</a> <a href="#tutorial-Prabath03Dot" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/Hansajith98"><img src="https://avatars3.githubusercontent.com/u/54827047?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Hansajith</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Hansajith98" title="Documentation">📖</a> <a href="#tutorial-Hansajith98" title="Tutorials">✅</a> <a href="#example-Hansajith98" title="Examples">💡</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/amaRanaweera"><img src="https://avatars1.githubusercontent.com/u/73416084?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Amasha Ranaweera</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=amaRanaweera" title="Documentation">📖</a> <a href="#tutorial-amaRanaweera" title="Tutorials">✅</a> <a href="#example-amaRanaweera" title="Examples">💡</a></td>
    <td align="center"><a href="https://github.com/charithroshan"><img src="https://avatars2.githubusercontent.com/u/43004672?v=4?s=100" width="100px;" alt=""/><br /><sub><b>charithroshan</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=charithroshan" title="Documentation">📖</a> <a href="#tutorial-charithroshan" title="Tutorials">✅</a> <a href="#example-charithroshan" title="Examples">💡</a></td>
    <td align="center"><a href="https://github.com/PiyumiThathsarani"><img src="https://avatars1.githubusercontent.com/u/58032088?v=4?s=100" width="100px;" alt=""/><br /><sub><b>PiyumiThathsarani</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=PiyumiThathsarani" title="Documentation">📖</a> <a href="#example-PiyumiThathsarani" title="Examples">💡</a> <a href="#tutorial-PiyumiThathsarani" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/MS14-dev"><img src="https://avatars1.githubusercontent.com/u/54228656?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Malindu Shamalka</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=MS14-dev" title="Documentation">📖</a> <a href="#tutorial-MS14-dev" title="Tutorials">✅</a> <a href="#example-MS14-dev" title="Examples">💡</a></td>
    <td align="center"><a href="https://github.com/Anne-98"><img src="https://avatars0.githubusercontent.com/u/58288067?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Anne Sudari</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Anne-98" title="Documentation">📖</a> <a href="#tutorial-Anne-98" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/smartsupun"><img src="https://avatars.githubusercontent.com/u/59835161?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Supun Lakshan</b></sub></a><br /><a href="#design-smartsupun" title="Design">🎨</a> <a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=smartsupun" title="Documentation">📖</a> <a href="#tutorial-smartsupun" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/deshitha98"><img src="https://avatars.githubusercontent.com/u/91746010?v=4?s=100" width="100px;" alt=""/><br /><sub><b>deshitha98</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=deshitha98" title="Documentation">📖</a> <a href="#tutorial-deshitha98" title="Tutorials">✅</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/amila01"><img src="https://avatars.githubusercontent.com/u/57836010?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Amila de silva</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=amila01" title="Documentation">📖</a> <a href="#tutorial-amila01" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/Dimuthu-10"><img src="https://avatars.githubusercontent.com/u/58289018?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dimuthu Lakshan</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Dimuthu-10" title="Documentation">📖</a> <a href="#tutorial-Dimuthu-10" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/Dilshan1997"><img src="https://avatars.githubusercontent.com/u/48722230?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Dilshan Madhuranga</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=Dilshan1997" title="Documentation">📖</a> <a href="#tutorial-Dilshan1997" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/banuka2001"><img src="https://avatars.githubusercontent.com/u/91893782?v=4?s=100" width="100px;" alt=""/><br /><sub><b>banuka2001</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=banuka2001" title="Documentation">📖</a> <a href="#tutorial-banuka2001" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/nirmani-1997"><img src="https://avatars.githubusercontent.com/u/67091419?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nirmani - 1997</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=nirmani-1997" title="Documentation">📖</a> <a href="#tutorial-nirmani-1997" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/MEKSankalpa"><img src="https://avatars.githubusercontent.com/u/66584748?v=4?s=100" width="100px;" alt=""/><br /><sub><b>MEKSankalpa</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=MEKSankalpa" title="Documentation">📖</a> <a href="#tutorial-MEKSankalpa" title="Tutorials">✅</a></td>
    <td align="center"><a href="https://github.com/ThiliniErandi"><img src="https://avatars.githubusercontent.com/u/58288054?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Thilini Kumarawadu</b></sub></a><br /><a href="https://github.com/ViduraRandika/Top-Ethical-Hacking-Resources/commits?author=ThiliniErandi" title="Documentation">📖</a> <a href="#tutorial-ThiliniErandi" title="Tutorials">✅</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

##What is Buffer Overflow Attack?
Buffers are memory storage regions that temporarily hold data while it is being transferred from one location to another. A buffer overflow (or buffer overrun) occurs when the volume of data exceeds the storage capacity of the memory buffer. As a result, the program attempting to write the data to the buffer overwrites adjacent memory locations.

Attackers exploit buffer overflow issues by overwriting the memory of an application. This changes the execution path of the program, triggering a response that damages files or exposes private information. For example, an attacker may introduce extra code, sending new instructions to the application to gain access to IT systems.

<!-- ALL-CONTRIBUTORS-LIST:END -->
