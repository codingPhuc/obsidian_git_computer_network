host name 
```
r1(config)# hostname R1
```
mật khẩu enable password 
```
r1(config)# line console 0
r1(line console)# password "the password"
R1 # login 

```

[

### Encrypting Passwords

](https://www.oreilly.com/library/view/cisco-ios-cookbook/0596527225/ch03s03.html)
```
Router1# configure terminal Router1(config)# enable password oreilly Router1(config-line)# line vty 0 4 Router1(config-line)# password cookbook Router1(config)# service password-encryption
```