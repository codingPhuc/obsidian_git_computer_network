
source :https://www.youtube.com/watch?v=E0S19bRzr6g


Layer 1

Physical Layer

In this layer, PDU is **bits** (1s or 0s) for the transmission of data on the network.

Layer 2

Data Link Layer

In this layer, PDU comprises- 

-   Original data with TCP/UDP header
-   Network layer header and 
-   Data Link Layer header contains MAC (Medium Access Control) addresses or physical addresses of sender and receiver. The trailer is also added to this layer.

PDU is called a **frame** in the Data Link Layer.

Layer 3

Network Layer 

In this layer, PDU comprises- 

-   Data with TCP/UDP headers
-   The network layer header contains Logical Addresses or IP Addresses of the sender and receiver.

PDU is called a **packet** in Network Layer.

Layer 4

 Transport Layer

In this layer, PDU comprises- 

-   Data with TCP/UDP headers having sender’s and receiver’s TCP/UDP port numbers.

PDU is called **segment or datagram** in Transport Layer depending upon the protocol used. For TCP (connection-oriented protocol), it is segmented and for UDP (connectionless protocol) it is a datagram.

Layer 5

Session Layer

In this layer, PDU is data.

Layer 6

Presentation Layer

In this layer, PDU is data.

Layer 7

Application Layer

In this layer, PDU contains original data made from a network application.