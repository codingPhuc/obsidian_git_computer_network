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
