this is how to config a router ip address 
```
enable 
config t
interface GigabitEthernet0/0 
ip address 192.168.0.1 255.255.255.192
no shutdown 
interface GigabitEthernet0/1 
ip address "the first ip" the subnetmask
```
this is how to config a switch 
```
enable 
config t
interface Vlan 1
ip address "the second ip address" "the subnet mask"
no shutdown 
```