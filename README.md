# The Great Book of Ports

a.k.a. what I wish were there when I was writing my first penetration testing reports. No subpages, no ads, no shitty paragraphs pretending they contain a lot of useful information. Just one page and CTRL+F!

This is a list-in-progress of the usual usage of TCP/UDP ports and their description. Note that it doesn't have to necessarily apply to your system. The purpose is to gather knowledge about less-known ports, so if you happen to know more about ports that lack of description, please let me know (or feel free to contribute).


## Ports

Port 	| Protocol 	|Services 		| Description
-------	| ---------	| ------------	| -----------
`20`	| TCP 		| `FTP`			| File Transfer Protocol - data
`21`	| TCP 		| `FTP`			| File Transfer Protocol - commands
`22`	| TCP 		| `SSH`			| Secure Shell - network protocol for operations in client-server architecture that encrypts the connection.
`23`	| TCP 		| `Telnet`		| Virtual terminal connection
`25`	| TCP 		| `SMTP`		| Simple Mail Transfer Protocol
`44` 	| TCP 		| `mpm-flags`	| *desciption wanted*
`53`	| TCP		| `DNS, domain`	|
`67`	| TCP 		| `DHCP`		| Dynamic Host Configuration Protocol - server
`68`	| TCP 		| `DHCP`		| Dynamic Host Configuration Protocol - client
`69`	| UDP 		| `TFTP`		| Trivial File Transfer Protocols
`80` 	| TCP 		| `HTTP`  		| HyperText Transfer Protocol
`99`	| TCP 		| `metagram`	| *Metagram Relay Protocol - description wanted*
`113`	| TCP 		| `ident`		| Identification Protocol used for IRC
`135`	| TCP 		| `msrpc`		| Microsoft RPC
`139`	| TCP 		| `netbios-ssn` | Microsoft Windows netbios-ssn + Samba - used for sharing local resources (including files and printers) with other hosts in the network
`143`	| TCP 		| `IMAP`		| Interet Message Access Protocol (IMAP4)
`443`	| TCP 		| `HTTPS`		| HTTP over SSL
`445`	| TCP 		| `netbios-ssn`	| See port `139`
`548`	| TCP 		| `afp` 		| Netatalk
`555`	| TCP 		| `dsf`			| Distributed File System
`631`	| TCP 		| `ipp` 		| Internet Printing Protocol
`993`	| TCP 		| `IMAPS` 		| Interet Message Access Protocol over SSL (IMAPS)
`1222`	| TCP 		| `nerv`		| NERV - network resource manager for virtualized environments
`1433`	| TCP 		| `ms-sql-s` 	| Microsoft SQL Server
`1801`	| TCP 		| `msmq`		| Microsoft Message Queueing
`2049`	| TCP 		| `nfs_acl`		| Access Control List type NFS
`2068` 	| TCP		| `avocentkvm` 	| Avocent KVM is a protocol used to control switches
`2105`	| TCP 		| `eklogin`		| Kerberos encrypted login
`2107`	| TCP 		| `msmq-mgmt`	| Microsoft Message Queueing Management
`2222`	| TCP 		| `EtherNetIP-1` | EtherNet/IP
`2233`	| TCP 		| `infocrypt`	| *description wanted*
`3128`	| TCP 		| `http-proxy`	| HTTP Proxy
`3260`	| TCP 		| `iscsi`		| Internet SCSI (Small Computer Interface)
`3263`	| TCP 		| `ecolor-imager` | *E-Color Enterprise Imager - description wanted*
`3264` 	| TCP		| `ccmail`		| *description wanted*
`3306` 	| TCP 		| `mysql`		| MySQL
`3389`	| TCP 		| `ms-wbt-server` | Microsoft Terminal Service (Windows Based Terminal)
`3975` 	| TCP 		| `airshot` 	| *Air Shot - description wanted*
`4369`	| TCP 		| `epmd`		| Erlang Port Mapper Deamon
`5123` 	| TCP 		| `ipmi-usb`	| *Intelligent Platform Management Interface; description wanted*
`5355` 	| TCP 		| `llmnr`		| Link-Local Multicast Name Resolution
`5672` 	| TCP		| `amqp`		| Advanced Message Queue Protocol
`5901`	| TCP 		| `ipmi-advertiserd` | *Intelligent Platform Management Interface; description wanted*
`6690` 	| TCP		| `cleverdetect` | CLEVERDetect Message - used in IDS
`7689` 	| TCP		| `collaber` 	| *description wanted*
`8040` 	| TCP		| `ampify`		| *description wanted*
`8080`	| TCP 		| `http-proxy`	| HTTP Proxy
`8889` 	| TCP		| `ddi-tcp-2` 	| *Desktop Data TCP 1 - description wanted*
`17500`	| TCP 		| `db-lsp`		| Dropbox LAN Sync Protocol
`17988` | TCP 		| `ilo`			| Integrated Lights-Out
`30000` | TCP 		| `ndmps`		| Secure Network Data Management Protocol - protocol used for transportation of data between NAS and backup devices.
`33509` | TCP 		| `mountd` 		| NFS mount daemon
