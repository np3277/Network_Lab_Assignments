Lab2: 
output:
![image](https://github.com/user-attachments/assets/f1df4c66-5253-423c-a486-1bd903927772)


lab 3 
![image](https://github.com/user-attachments/assets/31d7b7d9-c904-4b4a-ae84-bf1663cd20cf)
![image](https://github.com/user-attachments/assets/245340f6-7a83-4488-8bce-2b43e9b057ee)
![image](https://github.com/user-attachments/assets/d73eac96-077a-49e7-899d-7bec1b338f4b)

LAB5
![Config](https://github.com/user-attachments/assets/95aefb68-f41f-4890-bb1b-859776797278)
LAB 15 - TELNET CONFIG
![image](https://github.com/user-attachments/assets/18fd85a2-f61f-40d1-b198-b065335b2fe9)

Router>ENABLE
Router#CONFIG T
Enter configuration commands, one per line.  End with CNTL/Z.
Router(config)#INTERFACE FASTETHERNET0/0
Router(config-if)#IP ADDRESS 192.168.1.2 255.255.255.0
Router(config-if)#NO SHUTDOWN

Router(config-if)#
%LINK-5-CHANGED: Interface FastEthernet0/0, changed state to up

%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/0, changed state to up
%IP-4-DUPADDR: Duplicate address 192.168.1.2 on FastEthernet0/0, sourced by 00D0.D389.B53A

Router(config-if)#EXIT
Router(config)#LINE VTY 0 4
Router(config-line)#PASSWORD CISCO
Router(config-line)#LOGIN
Router(config-line)#EXIT
Router(config)#
Router#
%SYS-5-CONFIG_I: Configured from console by console

Router#
