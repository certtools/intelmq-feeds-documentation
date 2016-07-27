Cyber Threat Intelligence Feeds (CTIFeeds)
==========================================
@(Information Security)[resource, links, security]

----------

[TOC]

----------

Open Source Intelligence
========================

## Abuse.ch

A swiss guy fighting Cybercrime.

### Feodo Botnet

Feodo (also known as Cridex or Bugat) is a Trojan used to commit ebanking fraud 
and steal sensitive information from the victims computer, 
such as credit card details or credentials. 

At the moment, Feodo Tracker is tracking four versions of Feodo, 
and they are labeled by Feodo Tracker as:

* Version A: Hosted on compromised webservers running an nginx proxy on port 8080 TCP forwarding all botnet traffic to a tier 2 proxy node. Botnet traffic usually directly hits these hosts on port 8080 TCP without using a domain name.
* Version B: Hosted on servers rented and operated by cybercriminals for the exclusive purpose of hosting a Feodo botnet controller. Usually taking advantage of a domain name within ccTLD .ru. Botnet traffic usually hits these domain names using port 80 TCP.
* Version C: Successor of Feodo, completely different code. Hosted on the same botnet infrastructure as Version A (compromised webservers, nginx on port 8080 TCP or port 7779 TCP, no domain names) but using a different URL structure. This Version is also known as Geodo and Emotet.
* Version D: Successor of Cridex. This version is also known as Dridex

#### Domain Blacklist
>
* Website
 - `https://feodotracker.abuse.ch/`
* Source
 - `https://feodotracker.abuse.ch/blocklist/?download=domainblocklist`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No present data.

#### IP Blacklist
>
* Website
 - `https://feodotracker.abuse.ch/`
* Source
 - `https://feodotracker.abuse.ch/blocklist/?download=ipblocklist`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### Palevo Worm

#### Domain Blacklist
>
* Website
 - `https://palevotracker.abuse.ch/`
* Source
 - `https://palevotracker.abuse.ch/blocklists.php?download=domainblocklist`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Palevo Tracker has been discontinued.

#### IP Blacklist
>
* Website
 - `https://palevotracker.abuse.ch/`
* Source
 - `https://palevotracker.abuse.ch/blocklists.php?download=ipblocklist`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Palevo Tracker has been discontinued.

### Zeus Botnet

#### Domain Blacklist
>
* Website
 - `https://zeustracker.abuse.ch/`
* Source
 - `https://zeustracker.abuse.ch/blocklist.php?download=baddomains`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

#### IP Blacklist
>
* Website
 - `https://zeustracker.abuse.ch/`
* Source
 - `https://zeustracker.abuse.ch/blocklist.php?download=badips`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Alien Vault

### Miscellaneous

#### IP Blacklist
>
* Website
 - `https://www.alienvault.com/`
* Source
 - `https://reputation.alienvault.com/reputation.data`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Arbor

### Distributed SSH Brute Force Attacks

#### IP Blacklist
>
* Website
 - `https://atlas.arbor.net/`
* Source
 - `http://atlas-public.ec2.arbor.net/public/ssh_attackers`
* Data
 - IP Address
* Format
 - XML
* API/Token
 - None
* Status
 - Error
* Comments
 - 403 Forbidden


## Blocklist.de

### Attacks on the service Apache

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/apache.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### REG-Bots, IRC-Bots or BadBots (Spamming)

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/bots.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - ok
* Comments
 - No comment

### Brute-Force Website Logins

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/bruteforcelogin.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - ok
* Comments
 - No comment

### Attacks on the service FTP

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/ftp.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - ok
* Comments
 - No comment

### Attacks on the service IMAP, SASL, POP3

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/imap.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - ok
* Comments
 - No comment

### IRC Botnet

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/ircbot.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No present data.

### Attacks on the service Mail, Postfix

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/mail.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### Brute-Force SIP-, VOIP- or Asterisk-Server Logins Attacks

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/sip.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### Attacks on the service SSH

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/ssh.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### All IPs which are older then 2 month and have more then 5,000 attacks (Strong IPs).

#### IP Blacklist
>
* Website
 - `http://www.blocklist.de/`
* Source
 - `https://lists.blocklist.de/lists/strongips.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## The CINS Score

### The CI Army List

#### IP Blacklist
>
* Website
 - `http://cinsscore.com/`
* Source
 - `http://cinsscore.com/list/ci-badguys.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - NCCST IP address can not access the link.


## CleanMX.de

### Various Malware

#### Events
>
* Website
 - `http://support.clean-mx.de/clean-mx/viruses.php`
* Source
 - `http://support.clean-mx.de/clean-mx/xmlviruses?response=alive&format=csv&domain=`
* Data
 - URL, Domain Name, IP Address, ASN, Country Code, Contact Mail, etc.
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### Phishing

#### Events
>
* Website
 - `http://support.clean-mx.com/clean-mx/phishing.php`
* Source
 - `http://support.clean-mx.de/clean-mx/xmlphishing?response=alive&format=csv&domain=`
* Data
 - URL, Domain Name, IP Address, ASN, Country Code, Contact Mail, etc.
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Team Cymru

### Bogons IP List

#### IP Blacklist
>
* Website
 - `https://www.team-cymru.org/bogon-reference.html`
* Source
 - `https://www.team-cymru.org/Services/Bogons/fullbogons-ipv4.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## DShield: Internet Storm Center

### AS Report

#### IP Blacklist
>
* Website
 - `https://www.dshield.org/`
* Source
 - `https://www.dshield.org/asdetailsascii.html?as=4782`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### Top 20 attacking class C

#### IP Blacklist
>
* Website
 - `https://www.dshield.org/`
* Source
 - `https://www.dshield.org/block.txt`
* Data
 - Net Block
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### Suspicious Domains

#### Domain Blacklist
>
* Website
 - `https://www.dshield.org/suspicious_domains.html`
* Source
 - `https://www.dshield.org/feeds/suspiciousdomains_High.txt`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Danger.rulez.sk

### Brute Force Attack (Firewall)

#### IP Blacklist
>
* Website
 - `http://danger.rulez.sk/`
* Source
 - `http://danger.rulez.sk/projects/bruteforceblocker/blist.php`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Dragon Research Group

### SSH Brute Force Attack

#### IP Blacklist
>
* Website
 - `https://dragonresearchgroup.org/insight/`
* Source
 - `https://dragonresearchgroup.org/insight/sshpwauth.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

### VNC Brute Force Attack

#### IP Blacklist
>
* Website
 - `https://dragonresearchgroup.org/insight/`
* Source
 - `https://dragonresearchgroup.org/insight/vncprobe.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Security Research

### Ponmocup Botnet

#### Domain Blacklist
>
* Website
 - `http://security-research.dyndns.org/pub/malware-feeds/ponmocup-infected-domains-CIF-latest.txt`
* Source
 - `http://security-research.dyndns.org/pub/malware-feeds/ponmocup-infected-domains-CIF-latest.txt`
* Data
 - URL, Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Malwarebytes hpHosts

### Miscellaneous

#### Domain Blacklist
>
* Website
 - `https://www.hosts-file.net/`
* Source
 - `http://hosts-file.net/download/hosts.txt`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Malc0de

### Various Malware

#### Domain Blacklist
>
* Website
 - `http://malc0de.com/bl/`
* Source
 - `http://malc0de.com/bl/BOOT`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

#### IP Blacklist
>
* Website
 - `http://malc0de.com/bl/`
* Source
 - `https://malc0de.com/bl/IP_Blacklist.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Malware Domain List

### Miscellaneous

#### Domain Blacklist
>
* Website
 - `http://www.malwaredomainlist.com/`
* Source
 - `http://www.malwaredomainlist.com/updatescsv.php`
* Data
 - Domain Name
* Format
 - CSV
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Malware Domains

### Miscellaneous

#### Domain Blacklist
>
* Website
 - `http://www.malwaredomains.com/`
* Source
 - `http://mirror2.malwaredomains.com/files/domains.txt`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment


## Malware Group

### Unknown

#### Domain Blacklist
>
* Website
 - `http://www.malwaregroup.com/`
* Source
 - `http://www.malwaregroup.com/domains`
* Data
 - Domain Name
* Format
 - Not Available
* API/Token
 - None
* Status
 - Error
* Comments
 - Not Available

#### IP Blacklist
>
* Website
 - `http://www.malwaregroup.com/`
* Source
 - `http://www.malwaregroup.com/ipaddresses`
* Data
 - IP Address
* Format
 - Not Available
* API/Token
 - None
* Status
 - Error
* Comments
 - Not Available

### Proxy

#### IP Blacklist
>
* Website
 - `http://www.malwaregroup.com/`
* Source
 - `http://www.malwaregroup.com/proxies`
* Data
 - IP Address
* Format
 - Not Aavailable
* API/Token
 - None
* Status
 - Error
* Comments
 - Not Available


## OpenBL.org

### Abuse Reporting and Blacklisting

#### IP Blacklist
>
* Website
 - `https://www.openbl.org/`
* Source
 - `https://www.openbl.org/lists/date_all.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Error
* Comments
 - Not Available


## OpenPhish

### Phishing

#### Domain Blacklist
>
* Website
 - `https://www.openphish.com/`
* Source
 - `https://www.openphish.com/feed.txt`
* Data
 - URL
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## Spamhaus

### Don't Route Or Peer Lists

#### IP Blacklist
>
* Website
 - `https://www.spamhaus.org/drop/`
* Source
 - `https://www.spamhaus.org/drop/drop.txt`
* Data
 - Net Block
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## Taichung C&C List

### Miscellaneous

#### IP Blacklist
>
* Website
 - `https://www.tc.edu.tw/net/netflow/lkout/recent/30`
* Source
 - `https://www.tc.edu.tw/net/netflow/lkout/recent/30`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## Turris Greylist

### Scanning Attack

#### IP Blacklist
>
* Website
 - `https://www.turris.cz/en/greylist`
* Source
 - `https://www.turris.cz/greylist-data/greylist-latest.csv`
* Data
 - IP Address
* Format
 - CSV
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## URLVir

### Various Malware

#### Domain Blacklist
>
* Website
 - `http://www.urlvir.com/`
* Source
 - `http://www.urlvir.com/export-hosts/`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available

#### IP Blacklist
>
* Website
 - `http://www.urlvir.com/`
* Source
 - `http://www.urlvir.com/export-ip-addresses/`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


## VXVault

### Various Malware

#### Domain Blacklist
>
* Website
 - `http://vxvault.net/`
* Source
 - `http://vxvault.net/URL_List.php`
* Data
 - URL
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - Not Available


Community or Closed Source Intelligence
=======================================


## Alien Vault OTX (Open Threat Exchange)

### Miscellaneous

#### Events
>
* Website
 - `https://otx.alienvault.com/`
* Source
 - `None`
* Data
 - URL, Domain Name, IP Address, etc.
* Format
 - Not Available
* API/Token
 - `TBD`
* Status
 - Ok
* Comments
 - No comment


## Autoshun shunlist

### Miscellaneous

#### IP Blacklist
>
* Website
 - `https://www.autoshun.org/`
* Source
 - `https://www.autoshun.org/download/?api_key=< API KEY >&format=csv`
* Data
 - IP Address
* Format
 - CSV
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - URL Changed


## Blueliv

### Miscellaneous

#### Events
>
* Website
 - `https://community.blueliv.com/`
* Source
 - `None`
* Data
 - Domain Name, IP Address, etc.
* Format
 - CSV
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - URL Changed


## Bitsight

### Unknown

#### Events
>
* Website
 - `https://www.bitsighttech.com/`
* Source
 - `http://alerts.bitsighttech.com:8080/stream?key=< api >`
* Data
 - Not Available
* Format
 - Not available
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - No API Key


## DGArchive

### Various Malware

#### Domain Blacklist
>
* Website
 - `https://dgarchive.caad.fkie.fraunhofer.de/site/`
* Source
 - `None`
* Data
 - Domain Name
* Format
 - JSON
* API/Token
 - `TBD`
* Status
 - Ok
* Comments
 - No comment


## Malware Patrol

### Miscellaneous

#### Domain Blacklist
>
* Website
 - `https://dgarchive.caad.fkie.fraunhofer.de/site/`
* Source
 - `https://lists.malwarepatrol.net/cgi/getfile?receipt=< API KEY >&product=8&list=dansguardian`
* Data
 - URL, Domain Name, IP Address
* Format
 - Text
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - Parsing Error


## Phistank

### Phishing

#### Domain Blacklist
>
* Website
 - `https://www.phishtank.com`
* Source
 - `https://data.phishtank.com/data/< API KEY >/online-valid.csv`
* Data
 - URL
* Format
 - CSV
* API/Token
 - `TBD`
* Status
 - Ok
* Comments
 - No comment


## n6stomp

### Unknown

#### Events
>
* Website
 - `http://n6.cert.pl/`
* Source
 - `None`
* Data
 - Not Available
* Format
 - Not available
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - No API Key


## Spamhaus CERT Insight Portal

### Unknown

#### Events
>
* Website
 - `https://www.spamhaus.org/`
* Source
 - `None`
* Data
 - IP Address
* Format
 - Not available
* API/Token
 - `TBD`
* Status
 - Error
* Comments
 - No API Key
