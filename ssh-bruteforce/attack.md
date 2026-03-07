# What is brute force

## A Brute Force Attack occurs when an attacker continuously tries multiple username and password combinations to gain unauthorized access to a system.

##  The attacker automates this process using tools that rapidly attempt many login combinations until the correct credentials are found. .

Attack tool used (Hydra)

## Hydra is a fast network login cracker used by attackers to perform brute force attacks against multiple protocols.

Supported protocols include:

SSH

FTP

HTTP

RDP

Telnet

SMB

Commands used
 ## hydra -l root -P passwords.txt ssh://192.168.1.10

 | Option             | Meaning            |
| ------------------ | ------------------ |
| -l root            | Username to attack |
| -P passwords.txt   | Password wordlist  |
| ssh://192.168.1.10 | Target SSH server  |


MITRE: T1110
T1110 – Brute Force

This technique involves attackers attempting many passwords or passphrases to gain access.

Sub-techniques include:

T1110.001 – Password Guessing

T1110.002 – Password Cracking

T1110.003 – Password Spraying
