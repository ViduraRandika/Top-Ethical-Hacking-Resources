# Top-Ethical-Hacking-Resources
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-6-orange.svg?style=flat-square)](#contributors-)
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

#### Hybrid Dictionary Attack

| Tool  | Description | Example / Tutorial (link) |
| ----- | ----------- |---------------------------|
| [hashcat](https://hashcat.net/hashcat/) | Hashcat, which supports five separate attack modes for over 200 highly optimized hashing algorithms, is the world's best and most advanced password recovery utility. Hashcat currently supports Linux, Windows, and OSX CPUs, GPUs, and other hardware accelerators, and has facilities to allow distributed password cracking.| [How to use HashCat](https://www.youtube.com/watch?v=m0AGSO1LDJs)|
| [windows_password_recovery_hybrid_dictionary_attack](https://www.passcape.com/windows_password_recovery_hybrid_dictionary_attack) | Windows Password Recovery distribution kit comes with extended sets of password mutation rules:<ul><li>hybrid_rules/english_words.ini file contains basic rules for English passwords.</li><li>hybrid_rules/nonenglish_words.ini holds common rules for non-Eglish passwords.</li><li>hybrid_rules/simple_dates.ini - a lot of rules with dates, months, seasons, etc.</li><li>hybrid_rules/l33t.ini - rules to freak words (based on the leet dictionary).</li></ul> For example, password->p@$$w0rd|  [Tutorial in passcape official website](https://www.passcape.com/windows_password_recovery_hybrid_dictionary_attack)|

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
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

