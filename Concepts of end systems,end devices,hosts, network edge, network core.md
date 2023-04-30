## concept of end systems 
An end system is a device that facilitates Internet communications and can be used to access the Internet directly, such as personal computers and cameras, or indirectly, through servers for data like email and web pages. The interconnected network of end systems makes up the Internet architecture, allowing global information exchange via the Internet. However, end systems can be vulnerable to viruses, creating a weak point in security, which can be addressed through security measures such as data encoding, limited access and regular data backups.
## concept of end devices
an end device is a device that is connected to a network and participates directly in communication across that network . It can be a computer ,printer

### the different between end system and end devices 
- end systems are generally connected to each oter using switching devices known as routers rather than using a  single communication link .
- end systems is able to connect to the internet while end devices only referee to devices that communicate in a network
### host concept computer network 
in computer network a host refers to a computer that can interated with other host in a network , host can be servers responsible for [for transmitting and receiving data, services, and applications](https://linuxsimply.com/what-is-host-in-computer-network/)
host have their unique ip address on a TCP or IP network 
## network edge computer network 
- the network edge refer to an area where the devices or the local network interfaces with the internet . The edge si close to the devices it is communicating meaning that it is in the same network as the devices or network and is an entry point to the internet or a different network 
- network edge are crucial to security boundary that network administrators must provide solution for 

## network core 
mesh of interconnected router 
packet-switching : host break application layer messages into packets 
- network forwards packet from one router to the next , across links on path from source to destination 
### two key function 
forwading is a local action :
moving arriving packet form router input link 
to appropriate router output link 
![[forwarding.PNG]] 
when a router one to forward a packet into another adjacent router it will first look at the packet destination address then forward it on the path assgin by the forwarding table to another router 

### Routing : 
routing is the thing that created routing table 
is a global action : determine source destination path taken by packet , meanning that it will assign a path for the destination bases on the packet 
routing algorithms 
#### expample 
![[routing forward.PNG]]
routing will determind the forwaded road we will be taken on the each intersection 
### paket switching : store and forward 
packet trenasmission delay : takes L/R secodnd to transmit (push out) L-bit packet into link at R bps 
store and forward : entire packet must arrive at route before it can be transmitted on next link 
disadvantage of paket switching if the arrival rate of a packet exede the forwarding speed packet that arrive later will be force to queue and wait for the other packet to finish if the buffer of the router is full than the packet will be lost

## circus switching : 
mean that when a packet is send form one souce to the destination it will first be allocated the require link circus 
![[ciscus switch.PNG]]
as we can se the each path have 4 link circus the path from the first computer to the second is reserve 

