# cisco_alapok
alap cisco configok


en
conf t
username admin password 1234
ip domain-name wmszki.hu
enable secret cisco
line vty 0 15
login local
transport input ssh
password 1234
crypto key generate rsa 


int se0/0/0
ip address 172.20.100.0 255.255.255.252
no shutdown


router rip

version 2 

no auto-summary

network xxx.xxx.xx.x
network xxx.xxx.xx.x

