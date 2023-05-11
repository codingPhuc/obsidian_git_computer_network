SOURCE : https://www.cloudflare.com/learning/network-layer/internet-protocol/ https://www.youtube.com/watch?v=tOj8MSEIbfA
#sumarization  
**Network Protocols** are a set of guidelines governing the exchange of information in a simple, dependable and secure way. Network protocols are formal standards and policies comprised of rules, methodology, and configurations that define communication between two or more devices over a network. To effectively send and receive information, devices on the two sides of a communication exchange must follow protocols.

 DHCP, FTP, IP, DNS 
## DHCP 
#sumarization  
**DHCP:** it’s a protocol for network management and it’s used for the method of automating the process of configuring devices on IP networks. A DHCP server automatically assigns an IP address and various other configurational changes to devices on a network so they can communicate with other IP networks. it also allows devices to use various services such as NTP, DNS, or any other protocol based on TCP or UDP.
a dhcp server automatically assigns a computer an : 
- ip address 
- subnet mask 
- default gateway 
- Dns server 
when you seleact a atomatic ip address in the  window 
![[atomic.PNG]]
you will be given an atomatic ip address by the dns server 
![[scope.PNG]]
scope of the ip address is the number of unique ip address that the DHCP server can obtain 
![[lease.PNG]] 
when an ip address is created using dhcp method the computer will not own the ip address but it is a least that the dhcp will give 
 
![[reservation.PNG]]
the ip address on the reservation mean that the devices in the resivation will aways receive the same ip address this is usally used by router and switches as appose to host end devices 

## FTP (file transfer Protocol )
standard protocol that is used to transfer file 
between computer and servers over a network 
you can also used your computer as a server 

IF someone in  the world want to share their file they can send file into the ftp servers , then people that want to download that file will download the file 
## 
somethime ftp can be anonymous or they need you to have acount 
give the ability of website designner to upload to the server 
data is send in clear text so it is not very secure 
tftp : 
very simple transfer protocol 
not used to transfer files over the internet 
mainly used for network protocol is a connecttionless protocol 
does not provide any security over tranfer 

## IP PROTOCOL 
The Internet Protocol (IP) is a [protocol](https://www.cloudflare.com/learning/network-layer/what-is-a-protocol/), or set of rules, for routing and addressing [packets](https://www.cloudflare.com/learning/network-layer/what-is-a-packet/) of data so that they can travel across networks and arrive at the correct destination. Data traversing the Internet is divided into smaller pieces, called packets. IP information is attached to each packet, and this information helps [routers](https://www.cloudflare.com/learning/network-layer/what-is-a-router/) to send packets to the right place. Every device or [domain](https://www.cloudflare.com/learning/dns/glossary/what-is-a-domain-name/) that connects to the Internet is assigned an [IP address](https://www.cloudflare.com/learning/dns/glossary/what-is-my-ip-address/), and as packets are directed to the IP address attached to them, data arrives where it is needed.
## WHAT IS AN IP 
An IP address is a unique identifier assigned to a device or domain that connects to the Internet. Each IP address is a series of characters, such as '192.168.1.1'. Via [DNS](https://www.cloudflare.com/learning/dns/what-is-dns/) resolvers, which translate human-readable domain names into IP addresses, users are able to access websites without memorizing this complex series of characters. Each IP packet will contain both the IP address of the device or domain sending the packet and the IP address of the intended recipient, much like how both the destination address and the return address are included on a piece of mail.
