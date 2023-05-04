[Layers of OSI Model - GeeksforGeeks](https://www.geeksforgeeks.org/layers-of-osi-model/)
The OSI (Open Systems Interconnection) model is a conceptual framework used to standardize communication protocols and facilitate interoperability between different computer systems. It consists of seven layers, each with its own set of functions and responsibilities:

1.  Physical layer: Transmits raw bitstream over the physical medium, responsible for transmitting the data across the physical medium.
 - the data in this layer are call BITS 
 THE DATA IN THIS SECTION IS CALL FRAME
2.  Data link layer: Provides reliable transfer of data frames between two adjacent nodes, responsible for error detection and correction and providing a flow control mechanism. 
- the data in this layer is call frame 
4.  Network layer: Provides routing and addressing services to enable data transfer between different networks, responsible for logical addressing, routing, and packet forwarding. 
- the data unit in this layer are call packet 
4. Transport layer: Provides reliable, end-to-end data transport services, responsible for segmentation and reassembly, error detection, and flow control.
- the data in this layer are call segment 
TCP , UDP ,PORT NUMBERS 
THE DATA IN THIS SECTION ARE CALL SEGMENT
    
5.  Session layer: Establishes and manages sessions between applications, responsible for establishing, managing and terminating connections.
- the data in this layer is call message 
START  AND STOP SESSIIONS 
    
6.  Presentation layer: Formats and presents data to the application layer, responsible for data compression, encryption, and decryption.
FORMAT DATA, ENCRYPTION
- the data in this layer is call message 
    
7.  Application layer: Provides services directly to the user, responsible for providing access to network resources and user interfaces.
SMTP , FTP , TELNET
- the data in this layer is call message 
    


[OSI Model Explained | Real World Example - YouTube](https://www.youtube.com/watch?v=LANW3m7UgWs)
trouble shooting 
the error in each layer 
##  TCP/IP Model 
a model designed to standardies computer networking 
### 5 Application 
application protocol : http , ftp smtp 
data : message 
### 4 tranport 
application protocol : tcp , udp 
data  : segment
### 3 network 
application protocol : ip , routers 
data : packet 
### 2 data link 
application protocol : ethernet  switches 
data : frame 
### 1 physical
application protocol : cables , NIC(network interface card )
data : bits 


![[data.PNG]]


when the data is in the appplication layer it will be call a segment 
when the data is in the network layer it is call a packet 
when the data is in the data link layer it is call a frame 
### in depht about the layer 
1 physical layer 
it is a group of application that is responsible for the generation of data and requesting connection 
2 data link 
The packet’s network protocol type, in this case, TCP/IP, is identified by the data-link layer. Error prevention and “framing” are also provided by the data-link layer.
3 internet layer 
This layer parallels the functions of OSI’s Network layer. It defines the protocols which are responsible for the logical transmission of data over the entire network. The main protocols residing at this layer are as follows:

-   **IP:** [IP](https://www.geeksforgeeks.org/what-is-an-ip-address/) stands for Internet Protocol and it is responsible for delivering packets from the source host to the destination host by looking at the IP addresses in the packet headers. IP has 2 versions: IPv4 and IPv6. IPv4 is the one that most websites are using currently. But IPv6 is growing as the number of IPv4 addresses is limited in number when compared to the number of users.
-   **ICMP:** [ICMP](https://www.geeksforgeeks.org/difference-between-icmp-and-igmp/) stands for Internet Control Message Protocol. It is encapsulated within IP datagrams and is responsible for providing hosts with information about network problems.
-   **ARP:** [ARP](https://www.geeksforgeeks.org/how-address-resolution-protocol-arp-works/) stands for Address Resolution Protocol. Its job is to find the hardware address of a host from a known IP address. ARP has several types: Reverse ARP, Proxy ARP, Gratuitous ARP, and Inverse ARP.
### 4. Transport Layer

The TCP/IP transport layer protocols exchange data receipt acknowledgments and retransmit missing packets to ensure that packets arrive in order and without error. End-to-end communication is referred to as such. Transmission Control Protocol (TCP) and User Datagram Protocol are transport layer protocols at this level (UDP).

-   **TCP:** Applications can interact with one another using [TCP](https://www.geeksforgeeks.org/what-is-transmission-control-protocol-tcp/) as though they were physically connected by a circuit. TCP transmits data in a way that resembles character-by-character transmission rather than separate packets. A starting point that establishes the connection, the whole transmission in byte order, and an ending point that closes the connection make up this transmission.
-   **UDP:** The datagram delivery service is provided by [UDP](https://www.geeksforgeeks.org/user-datagram-protocol-udp/), the other transport layer protocol. Connections between receiving and sending hosts are not verified by UDP. Applications that transport little amounts of data use UDP rather than TCP because it eliminates the processes of establishing and validating connections.

### 5. Application Layer

This layer is analogous to the transport layer of the OSI model. It is responsible for end-to-end communication and error-free delivery of data. It shields the upper-layer applications from the complexities of data. The three main protocols present in this layer are:

-   **HTTP and HTTPS:** [HTTP](https://www.geeksforgeeks.org/difference-between-http-and-https-2/) stands for Hypertext transfer protocol. It is used by the World Wide Web to manage communications between web browsers and servers. HTTPS stands for HTTP-Secure. It is a combination of HTTP with SSL(Secure Socket Layer). It is efficient in cases where the browser needs to fill out forms, sign in, authenticate, and carry out bank transactions.
-   **SSH:** [SSH](https://www.geeksforgeeks.org/introduction-to-sshsecure-shell-keys/) stands for Secure Shell. It is a terminal emulations software similar to Telnet. The reason SSH is preferred is because of its ability to maintain the encrypted connection. It sets up a secure session over a TCP/IP connection.
-   **NTP:** [NTP](https://www.geeksforgeeks.org/network-time-protocol-ntp/) stands for Network Time Protocol. It is used to synchronize the clocks on our computer to one standard time source. It is very useful in situations like bank transactions. Assume the following situation without the presence of NTP. Suppose you carry out a transaction, where your computer reads the time at 2:30 PM while the server records it at 2:28 PM. The server can crash very badly if it’s out of sync.

The host-to-host layer is a layer in the OSI (Open Systems Interconnection) model that is responsible for providing communication between hosts (computers or other devices) on a network. It is also known as the transport layer.