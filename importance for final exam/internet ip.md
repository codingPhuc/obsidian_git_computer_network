
# CLI  Prompts 
- different prompts you’ll encounter when confi guring a switch or router 
- knowing them well will really help you orient yourself and recognize exactly where you are at any given time while in confi guration mode. 
to make chang to a interface you must first find out about all the interfaces 
when you enter into the configuration mode 
```
switch(config)# interface ? 
<<show list of interface >>
```
then pick an interface to config 
```
Switch(config)#interface fastEthernet 0/1
Switch(config-if)#
```
line commands 
To configure user-mode passwords, use the line command. The prompt then becomes
```
Switch(config-line)#:
Switch(config)#line ?
<0-15> First Line number
console Primary terminal line
vty Virtual terminal
Switch(config)#line console 0
Switch(config-line)#
```
the line console 0 in the config section is the global command  
the command line in config line is the subcommand line 
## routing protocol
