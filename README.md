It was project crearted by RKLIT.

Task:

1.Get access to all vlans

2.All vlans have access to all data transfer

3.All computers get DHCP addresses.

![image](https://github.com/RKLIT/Network_Project/assets/77961594/633a2f59-07c3-43d0-a225-1890e55314dd)

We have vlans:

VLAN2:192.168.1.0/28

VLAN3:192.168.2.0/28

VLAN4:192.168.3.0/28

VLAN5:192.168.4.0/29

VLAN6:192.168.5.0/28

VLAN7:192.168.6.0/30

Also we use L3 switches on the network, which are at vlan 6.
 
Vlan 2,3 was created at L3 switch with IP addresses

L3 Switch Number 1:

 Vlan 2: 192.168.1.1/28;
 
 Vlan 3: 192.168.2.1/28;
 
 Vlan 6: 192.168.5.1/28;
 
![image](https://github.com/RKLIT/Network_Project/assets/77961594/1cf0bf84-2120-4b6a-9825-e007f551676b)

![image](https://github.com/RKLIT/Network_Project/assets/77961594/b3066e7b-30a1-413a-aca7-36c089d48415)

L3 Switch Number 2:

 Vlan 4: 192.168.3.1/28;
 
 Vlan 5: 192.168.4.1/29;
 
 Vlan 6: 192.168.5.2/28;

![image](https://github.com/RKLIT/Network_Project/assets/77961594/d84cabb8-7d2f-47ea-8c4a-25ffd1f69b88)

![image](https://github.com/RKLIT/Network_Project/assets/77961594/e0a8c53b-1650-4e8b-97f1-a924cc211f21)

DHCP Server is at vlan 7. It's connecting with Router, which is at vlan 6 and 7.

DHCP Server:

 Vlan 7: 192.168.6.2/30;
 
 Gateway: 192.168.6.1/30;

![image](https://github.com/RKLIT/Network_Project/assets/77961594/61531e8c-dd81-4e04-8cd3-4556658af9c8)

![image](https://github.com/RKLIT/Network_Project/assets/77961594/594d99a0-cfaa-4bb3-be29-bd6c03cac102)

Router:

 Vlan 7: 192.168.6.1/30;
 
 Vlan 6: 192.168.5.3/28;

![image](https://github.com/RKLIT/Network_Project/assets/77961594/0216b558-d825-488f-8466-922ad4d0affe)

Check of work:

![image](https://github.com/RKLIT/Network_Project/assets/77961594/c34be620-aad7-46b9-b7e0-3f0e9450bbcb)

![image](https://github.com/RKLIT/Network_Project/assets/77961594/7b0c7d84-af67-4092-9223-b57b21a0ba32)

![image](https://github.com/RKLIT/Network_Project/assets/77961594/f2a1cfed-adcf-4600-a054-9983c5917073)

