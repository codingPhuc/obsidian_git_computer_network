
## what is an ip address 
it is an identifier in an address 
usally meaning ipv4 
192.168.1.0 each number in between the . is call an octec 
ip address consist of 2 part netword address 
second part is host address is the for each device in host 
# computer subnet mask 
the subnet mask is use for identifiying the network the host is in , the ip address for the network host is usally some thing like 255.x.x.x , with x can mean that the bit can be bettween 0 too 255 
| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 0   | 0   | 0   | 0   | 0   | 0   | 0   | 0   |
this wil mean that the ip address in an octec is 0 
sub net map binary concersion 
let us see 255.255.255.0 
| 128 | 64  | 32  | 16  | 8   | 4   | 2   | 1   |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1   | 1   | 1   | 1   | 1   | 1   | 1   | 1   |
this will give the sum of bit being 255 

example 
let say that we have an ip address of 192.168.1.0 and subnet mask of 255.255.255.0 

![[subnet mask.PNG]]
we can see that by using the and operation on each bit in the of the ip address and the sub netmask we will get the true ip address with the three of the first octer being network address and the last being the host address
example 
an subnet mask of 255.255.224.0 
ip address of 172.16.1.0 
![[subnet.PNG]]
we will see that the first two octec and the first three bit in the third octec being the network ip address and the last bieng the host ip address 
## why does the network need subnet mask 
let say that we have a large organization 
the problem if we dont use subnet is that it will create a slower network sometime this can cause the network to slow down 
so to subnet the network we will use router 
the computer will send out a board cast that only the computer on the subnet work can see 

### the way too break down subnet 
![[what is subneting.PNG]]

let borow one bit from the subnet protion you will have 1111111.1111111.1111111.1000000