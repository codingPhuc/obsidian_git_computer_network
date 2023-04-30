
The OSI (Open Systems Interconnection) model is a conceptual framework used to standardize communication protocols and facilitate interoperability between different computer systems. It consists of seven layers, each with its own set of functions and responsibilities:

1.  Physical layer: Transmits raw bitstream over the physical medium, responsible for transmitting the data across the physical medium.
    
2.  Data link layer: Provides reliable transfer of data frames between two adjacent nodes, responsible for error detection and correction and providing a flow control mechanism.
    
3.  Network layer: Provides routing and addressing services to enable data transfer between different networks, responsible for logical addressing, routing, and packet forwarding.
    
4.  Transport layer: Provides reliable, end-to-end data transport services, responsible for segmentation and reassembly, error detection, and flow control.
    
5.  Session layer: Establishes and manages sessions between applications, responsible for establishing, managing and terminating connections.
    
6.  Presentation layer: Formats and presents data to the application layer, responsible for data compression, encryption, and decryption.
    
7.  Application layer: Provides services directly to the user, responsible for providing access to network resources and user interfaces.
    



##  TCP/IP Model 
a model designed to standardies computer networking 
### 5 Application 
application protocol 
http , ftp smtp 
### 4tranport 
tcp , udp 
### 3 network 
ip , routers 
### 2 data link 
ethernet  switches 
### 1 physical
cables , NIC(network interface card )


![[data.PNG]]
the application layer contain the data 
the  tranport layter will give it a tcp or destination address 
the network layer will then give it a ip destination address 
the data link layer will add both a header and a trailer the header will have the source mac address the trailer will have the error checking code 

when the data is in the appplication layer it will be call a segment 
when the data is in the network layer it is call a packet 
when the data is in the data link layer it is call a frame 

