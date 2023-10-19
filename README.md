# Modern_Hotel_Networking_Small_Project



Based on the case study provided, I completed a small modern hotel networking project.




I employ the ideas of routers, switches, LANs, VLANs, IP addressing, subnetting, DHCP, port security, OSPF routing algorithm, Secure Shell (SSH) remote access, and wireless access points.



Case Study :-



As a part of your end year networking project , you are required to design and implement Vic Modern Hotel Network. The hotel has three floors, in the first floor there are three departments (Reception,Store and Logistics), in the second floor there are three departments(Finance, HR and Sales/Marketing), while the third floor hosts the IT and Admin. Therefore, the following are part of the considerations during the design and implementation.




1) There should be three routers connecting each floor (all placed in the server room in IT department).




2) All routers should be connected to each other using serial DCE cable.




3) The network between the routers will be 10.10.10.0/30 , 10.10.10.4/30 , 10.10.10.8/30.





4) Each floor is expected to have one switch (placed in the rrspective floor).





5) Each floor is expexted to have WIFI networks connected to laptops and phones.





6) Each department is expected to have a printer.





7) Each department is expected to be in different VLAN with the following details :-


 
 
 1st Floor :

 
 
 
 a) Reception - VLAN 80, Network of 192.168.8.0/24 
	
 
 
 
 b) Store - VLAN 70, Network of 192.168.7.0/24 	
	
 
 
 
 c) Logistics - VLAN 60, Network of 192.168.6.0/24 



 
 
 
 2nd Floor :
	
 
 
 
 a) Finance - VLAN 50, Network of 192.168.5.0/24 
	
 
 
 
 b) HR - VLAN 40, Network of 192.168.4.0/24 
	
 
 
 
 
 c) Sales - VLAN 30, Network of 192.168.3.0/24 


 
 
 
 3rd Floor :
	
 
 
 
 a) Admin - VLAN 20, Network of 192.168.2.0/24 
	
 
 
 
 b) IT - VLAN 10, Network of 192.168.1.0/24 





8) Use OSPF as the routing protocol to advertise routes.





9) All devices in the network are expected to obtain IP address dynamically with their respective router configures as the DHCP server.





10) All the devices in the network are expected to communicate with each other.





11) Configure SSH in all routers for remote login.






12) In IT departement, add PC called Test-PC to port fa0/1 and use it to test remote login.






13) Configure port security to IT-department switch to allow only Test-PC to access port fa0/1 (use sticky method to obtain mac-address with violation mode of shutdown).
