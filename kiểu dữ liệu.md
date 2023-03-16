/8 : 255.0.0.0 
/16  : 255.255.0.0 
/24 : 255.255.255.255 
/25 : 255.255.255.128 
/26 : 255.255.255.192 
subnetting 
đây là một địa chỉ private của class C  

vd: 192.168 .10.0/24( 192.168.10 là địa chỉ chung của tất cả ip trong mạng  )
địa chỉ trong máy tính ở mạng trên dược quyết định bởi  .0 cuối vậy có 8 bit với 2^8 -2 số địa chỉ mạng 
câu hỏi : để chia thành n subnet thì mình phải mượn ở host bao nhiêu bit sao cho 2^x >= n 
- vd : 4 subnet -> 2^x >= 4  X >= 2(x(min) =2)
- 3 subnet -> 2^x >=3 X >= 3 
192.168.19.0 /26 (192.168.19 là địa chỉ chung của tất cả ip trong mạng) ->block size = 2^6 

 subnet 1 : 192.168.10.0 / 26 (192.168.10.0-> 192.168.10.63)
			 2: 192.168.10.64/26 ()
			 3: 192.168.10.128/26 (192)
			 4: 192.169.010.192/26 () 



xem lại cách tính nhanh từ nhị phân sang thập phân 