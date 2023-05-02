
http overview 
 HTTP : hypertext transfer protocol 
- web application layer protocol 
- clientserver model : 
	- client : browser that requests , receives ,(using HTTP PROTOCOL)  and "displays" web objec6t 
	- server : web server sends(using HTTP protocol ) objects in response to requests 
	- tcp connections closed 
 HTTP IS "stateless"
 - server maintains no information about past client requests the resond why is because protocol that maintain state are really complex 
	 - the resond on why this is , is because past history (state) must be maintaind 
	 - if server client crashes , thier view of the state will be inconsistent 
## http connect 
### no persistent HTTP 
1. TCP CONNECtion is oepend 
2. at most one object sent over tcp connection 
3. tcp connection closed 
this mean that for each object the whole connection need to start for that single object meaning that that more object the more connection the tcp need to do 
example 
![[tcp.PNG]]
![[tcpd.PNG]]



### persistent http 
1. tcp connection opened to a server 
2.  multiple objct can be send over single tcp connection between client , and that server 
3. tcp connection is closed 



# email 
## three major components 
- user agent the computer and devices that you used to send email 
- mail server equivaline to http server 
- simple mail transfer protocol : SMTP 
user agent is what your computer used to composed sent email 
## mail server 
is

 