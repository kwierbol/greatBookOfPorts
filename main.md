#The Great Book of Ports

a.k.a. what I wish were there when I was writing my first penetration testing reports. No subpages, no ads, no shitty paragraphs pretending they contain a lot of useful information. Just one page and CTRL+F!

This is a list-in-progress of the usual usage of TCP/UDP ports and their description. Note that it doesn't have to necessarily apply to your system. The purpose is to gather knowledge about less-known ports, so if you happen to know more about ports that lack of description, please let me know (or feel free to contribute).


## Ports

Port 	| Protocol 	|Services 		| Description
-------	| ---------	| ------------	| -----------
`20`	| TCP 		| `FTP`			| File Transfer Protocol - data
`21`	| TCP 		| `FTP`			| File Transfer Protocol - commands
`22`	| TCP 		| `SSH`			| Secure Shell
`23`	| TCP 		| `Telnet`		| Virtual terminal connection
`25`	| TCP 		| `SMTP`		| Simple Mail Transfer Protocol
`53`	| TCP		| `DNS, domain`	|
`67`	| TCP 		| `DHCP`		| Dynamic Host Configuration Protocol - server
`68`	| TCP 		| `DHCP`		| Dynamic Host Configuration Protocol - client
`69`	| UDP 		| `TFTP`		| Trivial File Transfer Protocol
`80` 	| TCP 		| `HTTP`  		| Web pages
`143`	| TCP 		| `IMAP`		| Interet Message Access Protocol
`443`	| TCP 		| `HTTPS`		| HTTP over SSL
`548`	| TCP 		| afp `Netatalk` | ...
`555`	| TCP 		| `dsf`			| Distributed File System
`2068` 	| TCP		| `avocentkvm` 	| Avocent KVM is a protocol used to control switches
`2105`	| TCP 		| `eklogin`		| Kerberos encrypted login
`3263`	| TCP 		| `ecolor-imager` | *E-Color Enterprise Imager - description wanted* 
`3264` 	| TCP		| `ccmail`		| *description wanted*
`3975` 	| TCP 		| `airshot` 	| *Air Shot - description wanted*
`4369`	| TCP 		| `epmd`		| Erlang Port Mapper Deamon
`5672` 	| TCP		| `amqp`		| Advanced Message Queue Protocol
`6690` 	| TCP		| `cleverdetect` | CLEVERDetect Message - used in IDS
`7689` 	| TCP		| `collaber` 	| *description wanted*
`8040` 	| TCP		| `ampify`		| *description wanted*
`8889` 	| TCP		| `ddi-tcp-2` 	| Desktop Data TCP 1
`17500`	| TCP 		| `db-lsp`		| Dropbox LAN Sync Protocol
