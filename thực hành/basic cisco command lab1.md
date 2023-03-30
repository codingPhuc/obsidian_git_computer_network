## accessing the exec mode 
there are two mode for exec the user exec model and the private exec model : 
- user exec model allow you to access only basic monitoring command  
- privileged exec level allows you to access all router 
this is how to enable the privileged exec model 
```
switch> enable 
switch# config t
```
how to  config the host name 
let say we want to config the switch host name as S1 we do this 
```
switch(config)# hostname S1 
S1(config)# 
```
let say we want to config the console and privileged EXEC mode we do it like this 
```
S1 (config)# line console 0 
S1(config-line)# password cisco 
S1(config-line)# login 
S1(config_line)#exit 
```
you can encrypted the privileged Exec mode password like this 
```
S1(config)#enable secret "the password" 
```
## config the message of the day (MOTD)
```
S1(config)# banner motd "Authoried acces only , violators will be prosecuted to the full extend ot the law"
```
## save the configuration file to NVRAM 
```
S1# copy running-config startup-config 
```
# how to config the switch interface 
### config the switch ip address 
```
S1# config terminal 
S1(config)# interface vlan 1 
S1(config-if)# ip address 192.168.1.253 255.255.255.0
S1(config-if)# no shutdown
S1(config-if)# exit 
```
What does the no shutdown command? 
in the simples sense shutdown turn the interface off , no shutdown turn the interface on 