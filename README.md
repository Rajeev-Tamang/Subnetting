# Subnetting

**1. How many /26 subnets can you create from 10.0.0.0/22?**
> /22 network provides 1024 IP addresses (because 2^(32 - 22) = 1024).
>
> /26 subnet gives 64 IP addresses (because 2^(32 - 26) = 64).
>
> So, you can create:
> 
> 1024 / 64 = 16subnets


***kati ota subnet form hunxa vanha yaad garnu parne kura , hamle kati bit borrow garheko xam. vanna le cop /22 to /26 , then yesma hamle 4 bit borrow garhim 2^4=16 so 16 subnets hami create garnu sakxam. and for /26 ko address pool (32-26)=6 , 2^6=64 , euta pool ma 64 ip , 10.0.0.0/26 , vanhesi /26 vanheko 4th octect so change in 4th octet mai hunxa, 10.0.0.0-10.0.0.63, i.e total 64 address and next subne starts form 10.0.0.64/26***
