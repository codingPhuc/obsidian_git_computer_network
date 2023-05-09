**

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are both transport layer protocols used for data transfer over IP networks. However, they differ in terms of their roles and functions:

TCP:

-   Provides reliable, ordered, and error-checked delivery of data
    
-   Uses a three-way handshake to establish a connection between sender and receiver
    
-   Uses sequence numbers and acknowledgments to ensure reliable data transfer
    
-   Allows for flow control and congestion control to optimize network performance
    
-   Includes a checksum field to ensure data integrity
    
-   Uses sliding window protocol to manage the flow of data
    
-   Header includes fields such as source and destination port numbers, sequence and acknowledgment numbers, flags (SYN, ACK, FIN, PSH), window size, checksum, and length
    

UDP:

-   Provides connectionless, unreliable data transfer
    
-   Does not guarantee delivery or order of data packets
    
-   Does not include flow control or congestion control
    
-   Does not include error checking or correction mechanisms
    
-   Does not establish a connection before sending data
    
-   Header includes fields such as source and destination port numbers, length, checksum
    

Here are the answers to the questions:

Which protocol is used for real-time applications such as video and audio streaming?

-   UDP is typically used for real-time applications such as video and audio streaming because it has lower overhead and faster transmission speed, which is more suitable for real-time data transfer where speed is more important than reliability.
    

Which protocol is used for connectionless data transfer?

-   UDP is used for connectionless data transfer. It does not establish a connection before sending data, and does not guarantee delivery or order of data packets.
    