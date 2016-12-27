# ppdesnawsenv
##5. Creating a VPC
###3 Connecting to a VPC
Customer gateway -> VPN connection->VPN gateway  
Customer gateway -> AWS direct connect->VPN gateway  

####VPC peering
- private connections without gateways
- between two VPCs in same region
- could be different accounts
- no sharing of gateways or peered connections

###4 Securing Your VPC
####Bastion host
protocol source : inbound=public subnet 
private source: sg of bastion,port 22

####09:00
```
ssh-add -K keyname
ssh -A user@ip
```

single command
```
ssh -A -i key user@ip
```
