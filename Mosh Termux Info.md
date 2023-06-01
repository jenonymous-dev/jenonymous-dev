---
created: 2023-05-29T09:23:43-04:00
modified: 2023-05-29T09:26:01-04:00
---

# Mosh Termux Info

---
created: 2023-05-29T09:23:43-04:00
modified: 2023-05-29T09:23:43-04:00
---

# Mosh Termux Info

Welcome to Termux!

Docs:       https://termux.dev/docs
Donate:     https://termux.dev/donate
Community:  https://termux.dev/community

Working with packages:

 - Search:  pkg search <query>
 - Install: pkg install <package>
 - Upgrade: pkg upgrade

Subscribing to additional repositories:

 - Root:    pkg install root-repo
 - X11:     pkg install x11-repo

For fixing any repository issues,
try 'termux-change-repo' command.

Report issues at https://termux.dev/issues
~ $ apt-get install mosh
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  ldns libedit openssh openssh-sftp-server
  termux-auth
Suggested packages:
  mosh-perl
The following NEW packages will be installed:
  ldns libedit mosh openssh openssh-sftp-server
  termux-auth
0 upgraded, 6 newly installed, 0 to remove and 0 not upgraded.
Need to get 1343 kB of archives.
After this operation, 9466 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 https://ftp.fau.de/termux/termux-main stable/main aarch64 ldns aarch64 1.8.3-2 [303 kB]
Get:2 https://ftp.fau.de/termux/termux-main stable/main aarch64 libedit aarch64 20221030-3.1-0 [77.7 kB]
Err:3 https://ftp.fau.de/termux/termux-main stable/main aarch64 openssh-sftp-server aarch64 9.3p1
  404  Not Found [IP: 2001:638:a000:1021:21::1 443]
Get:4 https://ftp.fau.de/termux/termux-main stable/main aarch64 termux-auth aarch64 1.4-2 [6384 B]
Err:5 https://ftp.fau.de/termux/termux-main stable/main aarch64 openssh aarch64 9.3p1
  404  Not Found [IP: 2001:638:a000:1021:21::1 443]
Get:6 https://ftp.fau.de/termux/termux-main stable/main aarch64 mosh aarch64 1.4.0-4 [151 kB]
Fetched 538 kB in 1s (391 kB/s)
E: Failed to fetch https://ftp.fau.de/termux/termux-main/pool/main/o/openssh-sftp-server/openssh-sftp-server_9.3p1_aarch64.deb  404  Not Found [IP: 2001:638:a000:1021:21::1 443]
E: Failed to fetch https://ftp.fau.de/termux/termux-main/pool/main/o/openssh/openssh_9.3p1_aarch64.deb  404  Not Found [IP: 2001:638:a000:1021:21::1 443]
E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?
~ $ apt-get update --fix-missing
Get:1 https://ftp.fau.de/termux/termux-main stable InRelease [14.0 kB]
Hit:2 https://ftp.fau.de/termux/termux-root root InRelease
Get:3 https://ftp.fau.de/termux/termux-x11 x11 InRelease [14.0 kB]
Get:4 https://ftp.fau.de/termux/termux-main stable/main aarch64 Packages [502 kB]
Get:5 https://ftp.fau.de/termux/termux-main stable/main aarch64 Contents (deb) [2270 kB]
Get:6 https://ftp.fau.de/termux/termux-root root/stable aarch64 Contents (deb) [27.3 kB]
Get:7 https://ftp.fau.de/termux/termux-x11 x11/main aarch64 Packages [126 kB]
Get:8 https://ftp.fau.de/termux/termux-x11 x11/main aarch64 Contents (deb) [1535 kB]
Fetched 4488 kB in 3s (1579 kB/s)
Reading package lists... Done
~ $ apt-get install mosh
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  ldns libedit openssh openssh-sftp-server
  termux-auth
Suggested packages:
  mosh-perl
The following NEW packages will be installed:
  ldns libedit mosh openssh openssh-sftp-server
  termux-auth
0 upgraded, 6 newly installed, 0 to remove and 24 not upgraded.
Need to get 808 kB/1346 kB of archives.
After this operation, 9466 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 https://ftp.fau.de/termux/termux-main stable/main aarch64 openssh-sftp-server aarch64 9.3p1-2 [45.0 kB]
Get:2 https://ftp.fau.de/termux/termux-main stable/main aarch64 openssh aarch64 9.3p1-2 [763 kB]
Fetched 808 kB in 1s (625 kB/s)
Selecting previously unselected package ldns.
(Reading database ... 44466 files and directories currently installed.)
Preparing to unpack .../0-ldns_1.8.3-2_aarch64.deb ...
Unpacking ldns (1.8.3-2) ...
Selecting previously unselected package libedit.
Preparing to unpack .../1-libedit_20221030-3.1-0_aarch64.deb ...
Unpacking libedit (20221030-3.1-0) ...
Selecting previously unselected package openssh-sftp-server.
Preparing to unpack .../2-openssh-sftp-server_9.3p1-2_aarch64.deb ...
Unpacking openssh-sftp-server (9.3p1-2) ...
Selecting previously unselected package termux-auth.
Preparing to unpack .../3-termux-auth_1.4-2_aarch64.deb ...
Unpacking termux-auth (1.4-2) ...
Selecting previously unselected package openssh.
Preparing to unpack .../4-openssh_9.3p1-2_aarch64.deb ...
Unpacking openssh (9.3p1-2) ...
Selecting previously unselected package mosh.
Preparing to unpack .../5-mosh_1.4.0-4_aarch64.deb ...
Unpacking mosh (1.4.0-4) ...
Setting up libedit (20221030-3.1-0) ...
Setting up openssh-sftp-server (9.3p1-2) ...
Setting up ldns (1.8.3-2) ...
Setting up termux-auth (1.4-2) ...
Setting up openssh (9.3p1-2) ...
Generating public/private rsa key pair.
Your identification has been saved in /data/data/com.termux/files/usr/etc/ssh/ssh_host_rsa_key
Your public key has been saved in /data/data/com.termux/files/usr/etc/ssh/ssh_host_rsa_key.pub
The key fingerprint is:
SHA256:RkebJDsq+rmLehdP97Hr4uO/8HM0ivbXnUiKuSpW7HU u0_a1057@localhost
The key's randomart image is:
+---[RSA 3072]----+
|        . o      |
|         = o     |
|        + +      |
|       o o       |
|    . o S        |
|   ....+...Eo.   |
|  .  +o.oo+=oo...|
|  .o.+..===.o....|
|.o..*o.=+BO*     |
+----[SHA256]-----+
Generating public/private dsa key pair.
Your identification has been saved in /data/data/com.termux/files/usr/etc/ssh/ssh_host_dsa_key
Your public key has been saved in /data/data/com.termux/files/usr/etc/ssh/ssh_host_dsa_key.pub
The key fingerprint is:
SHA256:VzXRemS8i1pP+e9PPrNpgYY9TZAZvCgRi57/zmq26GY u0_a1057@localhost
The key's randomart image is:
+---[DSA 1024]----+
|         .. ..B+ |
|        ...  * .=|
|       . .. o o+.|
|      . .. o ..o.|
|       oS o o =.o|
|        .. . B * |
|         .  + + +|
|       E.oo.   Bo|
|      +ooo++  .+@|
+----[SHA256]-----+
Generating public/private ecdsa key pair.
Your identification has been saved in /data/data/com.termux/files/usr/etc/ssh/ssh_host_ecdsa_key
Your public key has been saved in /data/data/com.termux/files/usr/etc/ssh/ssh_host_ecdsa_key.pub
The key fingerprint is:
SHA256:Qxf/HxRTliyZPDy2GFA4TOLFpmkoiwiK33K/2zKpcZw u0_a1057@localhost
The key's randomart image is:
+---[ECDSA 256]---+
|       .++=.o +o=|
|      . o* + X +o|
|      ..= o = =. |
|.  . . = . . o.  |
|= . o . S     .. |
|+. . . . .     ..|
| . .. E.        .|
|  o oo+.         |
|   o.o+=.        |
+----[SHA256]-----+
Generating public/private ed25519 key pair.
Your identification has been saved in /data/data/com.termux/files/usr/etc/ssh/ssh_host_ed25519_key
Your public key has been saved in /data/data/com.termux/files/usr/etc/ssh/ssh_host_ed25519_key.pub
The key fingerprint is:
SHA256:D+MN3aUVlm3ydWLQAKJGJd4pdibscNEMvK8uqCYbAKo u0_a1057@localhost
The key's randomart image is:
+--[ED25519 256]--+
|     .==o ..o+oo |
|     +.=oo   .*.=|
|.   . X.=    .o=o|
|o    *.= . . +  .|
|o     ..S . o    |
|o      ..*       |
|E  .   .. o      |
|.o. . .          |
|=o   o.          |
+----[SHA256]-----+
Setting up mosh (1.4.0-4) ...
~ $
