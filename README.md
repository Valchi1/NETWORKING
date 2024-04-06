# NETWORKING

Task 1 -

The first task is to build the network pictured below and ensure the services and features following the diagram are fully implemented and tested.  Please submit as a single Packet Tracer file please.

network.png file uploaded.

Configuration Checklist:

Ensure that every Area makes use of HSRP for router redundancy.
Ensure that Etherchannel is added to each area to provide switch redundancy using the Etherchannel Protocol indicated.
Ensure that all routing devices within the local area networks are running the OSPFv2 routing protocol.
Ensure that routers R1, R2, R5 and R6 have default routes pointing into the ISP area and that these are redistributed within OSPF.
On the ISP layer 3 switches, give the higher number VLAN the ports 1-12 and the lower number VLAN the ports 13 -24.
All the black routing devices in the ISP area should be running BGP using the supplied AS numbers.
R1, R2, R5 and should be running dynamic NAT using the outside interface as the NAT address with PAT set up too.
These same routers should also have static NAT set up to cater for the local area server.
OSPF should be protected with passwords provided to prevent the unauthorised introduction of OSPF routing hardware.
All serial interfaces should use PPP encapsulation and should use either PAP or CHAP authentication as directed.
All PCs should receive their addressing information via DHCP from their border router.
HSRP routers/switches should assist DHCP by employing IP Helper as appropriate. 
All PCs should be able to ping the 11.0.0.2 and 11.0.0.6 servers as well as the static NAT addresses of servers in the other areas.

PART 2

Pick any two of the network areas from the original diagram, then, using the wireless networking knowledge you have gained so far, convert the "client" areas of those two network areas into wireless networks.

diagram file also imcluded.
