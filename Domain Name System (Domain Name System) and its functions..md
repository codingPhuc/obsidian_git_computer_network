video :https://www.youtube.com/watch?v=6lRcMh5Yphg&t=50s

#sumarization 
the role of the dns is to map between ip address and name and vice versa 
meaning that it will translate the domain name of system into a ip address 
dns is a distributed database implemented in hierarchy of many name servers 
appliacation-layer protocol : host , DNS  servers communicate to resolve names (address/ name translation)
- note : core internet function implemented as application-layer protocol 
- complexity at network "edge"
## DNS SERVICES 
host name to ip address translation 
host aliansing 
- canonical ,alias names 
mail server aliasing 
load distribution 
- replicated webservers : many ip addresses correspond to one name 
### dns a distributed hierarchical database 
root dns servers 
![[root.PNG]]
if let say that the client want to ip address for www.amazon.com 
1. the client queries root server to find th