Multiarea OSPF configuration

This lab has been build using using the GNS3 network emulator

The goal of this lab is to configure Multiarea OSPF using the 3 routers in the topology provided

- Configure IP addressing and OSPF as per diagram
- On router R2 create a prefix list which is going to be referenced by a filter list to filter all loopback addresses from area 1 to being injected into the routing table on area 0
- On router R1 create a prefix list which is going to be referenced by a distribute list to prevent the 10.2.2.0/24 network from being advertised by OSPF into the IP routing table of R1.

Result:

Router R1 does not know any route to 10.2.2.0/24, 2.2.2.2/32 and 3.3.3.3/32 networks