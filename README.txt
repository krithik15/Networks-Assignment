Team 10
Routing Information Protocol(RIP) version 2

1.Shobika K M	3122215001101
2.Vaidhegi D	3122215001118
3.Rajasekar S	3122215001076
4.Pranes S	3122215001309

Requirements:-
1.	Cisco packet tracer

Configuration:-

1.Access the router's command-line interface. 2.Configure the necessary interfaces with appropriate IP addresses. For example:
For Router 0:
interface Serial0/0
ip address 192.168.1.1 255.255.255.0
no shutdown exit
interface FastEthernet0/0
ip address 192.168.101.1 255.255.0.0
no shutdown exit
For Router 1:
interface Serial0/0
ip address 192.168.1.2 255.255.255.0
no shutdown exit
interface FastEthernet0/0
ip address 192.168.100.1 255.255.0.0
no shutdown exit


3.	Save the configuration.
 

Usage:-

Make sure the WIC-1T is attached, router is powered on and connected to the network. The RIP version 2 should now be in effect.

Connectivity Testing:-

To test the connectivity, initiate ping tests between devices:
1.	From PC0, ping another external device PC1
2.	From PC1, ping PC0.
