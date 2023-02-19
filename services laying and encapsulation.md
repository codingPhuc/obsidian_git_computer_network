application <-  M -> application (ps the application layer have two different sub layer)
transport<-  ht , M -> transport 
network <- Hn , Ht , M -> network 
link <- Hl , Hn , Ht ,M  -> link 
	- link layer protocol transfers datagram Hn | [Ht| M] form host to neighboring host ,using network -layer services 
	-  link layer protocol encapsulates network datagram Hn | [Ht , M] ,with link -layer header Hl to create a link layer frame 
 the tracert command in cmd trace 

 