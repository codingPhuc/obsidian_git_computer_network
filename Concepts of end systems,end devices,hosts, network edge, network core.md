## concept of end systems 
device connected to a [computer network](https://en.wikipedia.org/wiki/Computer_network "Computer network") is sometimes referred to as an **end system** or **end station**, because it sits at the edge of the network. The [end user](https://en.wikipedia.org/wiki/End_user "End user") directly interacts with an end system that provides information or services
device connected to a [computer network](https://en.wikipedia.org/wiki/Computer_network "Computer network") is sometimes referred to as an **end system** or **end station**, because it sits at the edge of the network. The [end user](https://en.wikipedia.org/wiki/End_user "End user") directly interacts with an end system that provides information or services
End systems are generally connected to each other using switching devices known as [routers](https://en.wikipedia.org/wiki/Router_(computing) "Router (computing)") rather than using a single communication link

## concept of end devices
End network devices, also known as end-user devices or endpoints, are devices that serve as the final point of communication in a network. These devices facilitate direct interaction with users and enable them to access, create, and exchange information over the network. Examples of end network devices include:

1. Personal computers (desktops, laptops)  
2. Smartphones and tablets  
3. Network printers and scanners  
4. Internet of Things (IoT) devices, such as smart home appliances, wearables, and sensors

5. Servers hosting websites or applications for end-user access  
6. Teleconferencing equipment  
7. Gaming consoles and media streaming devices

End network devices connect to the network infrastructure through wired or wireless connections, such as Ethernet, Wi-Fi, or cellular networks. They interact with other devices and network resources, like switches, routers, and servers, to send and receive data, access services, and perform various tasks; ensuring the security and proper functioning of end network devices are crucial to maintain the overall performance and security of a network.
### the different between end system and end devices 
- end systems are generally connected to each oter using switching devices known as routers rather than using a  single communication link .
- end systems is able to connect to the internet while end devices only referee to devices that communicate in a network
### host concept computer network 
in computer network a host refers to a computer that can interated with other host in a network , host can be servers responsible for [for transmitting and receiving data, services, and applications](https://linuxsimply.com/what-is-host-in-computer-network/)
host have their unique ip address on a TCP or IP network 
## network edge computer network 
- the network edge refer to an area where the devices or the local network interfaces with the internet . The edge is close to the devices it is communicating meaning that it is in the same network as the devices or network and is an entry point to the internet or a different network 
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
as we can se the each path connected to each router  have 4 link and each link have 4 circus , the path from the first computer to the second is tranmisted to the second circus   in the first link then the 1 circus in the second link 
this will prevent packet loses , dedicated recourse no sharing ciscus link
the downside is it will make the circus unsable if to the other conputer if the computer is not dedicated to circus

### there are two way that circus switching 
FDM Frequency division multiplexing 
![[fdm.PNG]]
4 different circus will be assgin 4 different user for each circus  
TDM  Time division Multiplexing 
![[tdm.PNG]]
a single circus will tranmist each packet at different time frame 


