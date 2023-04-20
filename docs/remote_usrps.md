In the following, you can find instructions for remote connection to USRP N310 and USRP B210.

### USRP N310 
* You will first need to [get an account and SSH](./login.md) into the Nautilus machine.
* SSH into the USRP N310 from the Nautilus machine: `ssh root@192.168.10.2`\
This is the address (USRP side) of one of the two 10 GBe data interfaces connecting the USRP N310 and the Nautilus machine.
The other interface (USRP side) has address `192.168.20.2`

* Remote SSH into the USRP N310 (through management interface): `ssh root@172.24.113.222` (Requires connection to NYU VPN)


### USRP B210
* Remote SSH into the host computer with the USRP B210: `ssh lab@172.24.113.58`. The password is `1234`\
(Requires connection to NYU VPN)
