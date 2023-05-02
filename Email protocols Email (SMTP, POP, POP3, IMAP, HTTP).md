
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
user agent is what your computer used to composed sent email interface to create email 
## mail server 
is like a mail box contains incoming messages for user 
- message queue of out going (to be sent) mail messages 
SMTP  protocol between mail servers to send email messages 
![[kinship.PNG]]
to sumarize the information above alice first compose the email then send it to alice server the server then sent the email to a server that bob used using a tcp protocol 
![[smtp.PNG]]

pop and imap :https://www.youtube.com/watch?v=SBaARws0hy4
## pop
is used for retreiving email ofrm an email server 
the only thing that pop3 does , is download the email to your device from a mail server 
only download what in your inbox folder 
it does not have synconization :
meaning that if one computer want to download your email in the email server using pop , the email will be remove from the server without leaving a copy , so if another computer wanted to download the same email it will not be downloaded 
### advantage and disadvantages

## Imap 
imap allow you to view your email , that on the server from multiple devices 
imap caches local copies of the email onto all of your devices meaning that if you want to view your email in a different computer you imap can synchronized it with the other computer 
so every computer phone or devieces you have will be synch with all computer 

![[pop.PNG]]




