# My Packet Tracer Labs

## 1. Corporate Network Design
![Topology View](assets/improved-network.png)

**Description**: A simulated enterprise network with VLANs, DHCP, and NAT.

FEATURES:
Router 1 – Primary Internal Network
Router 1 connects to three switches, forming the first internal
network segment.
CISCO Switch 1 and Switch 2 (Interconnected Access Layer)
Switch 1 and Switch 2 are directly connected to each other.
Together, they provide connectivity to the following devices:
1 × Wireless router
1 × Printer
1 × VoIP phone
2 × Desktop computers
Wireless Router (from Switch 1/2)
The wireless router provides Wi-Fi access to:
2 × Laptops
1 × Desktop computer
CISCO Switch 3 (Server Segment)
The third switch connected to Router 1 is dedicated to servers.
This switch provides wired connectivity to:
3 × Servers
This setup effectively separates user devices from server
infrastructure while remaining under the same router.
Router 2 – Secondary Internal Network
Router 2 connects to one switch, forming the second internal network
segment.
Switch (Access Layer)
This switch provides wired connectivity to:
2 × Desktop computers
1 × VoIP phone
1 × Printer
1 × Wireless router
Wireless Router (from Router 2 switch)
The wireless router provides Wi-Fi access to:
2 × Laptops


**Requirements**: Cisco Packet Tracer 8.2+
