# dns-server
first part of hostname creat
hostname:- keval

pakages install
pakages:- bind bind-utils 

modify configuration file
file name:- named.confg

set type ip adress 
set ip address is serverv ip address and any ip address alloow query 

systemctl status
system status activate

firewall command
firewall rules set 53/tcp and 53/udp
and firewall reload

named config file select
examle:- server.example.com, forward.example.com,  reverse.example.com 

chenge directory
To write a command is cd /var/named/
And copy to named,localhost forewrd.example.com

Aftre going to forewrd.example.com
domain name change and ip address specify 

copy rverse.exampel.com
To write a server.example.com and ptr select this server and desktop 

And ls -ll command type 

permision
chown in root forewrd & reverse 

Then chechk-confg 

service start
firewall reload
