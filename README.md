This is a hands-on Networking and Security project where I am building a corporate network from scratch using Cisco Packet Tracer.

Instead of just reading about CCNA concepts, I am literally laying down the cables, configuring the switches, and setting up strict security VLANs to segment network traffic.

Project Goals:
Network Segmentation: Creating secure, VLANs 10 & 20 so sensitive traffic stays isolated.

Switch Configuration: Programming access ports to be strict for specific VLANs.

Trunking (802.1Q): Building a Trunk Link so data can travel across the network without losing its security tags.

Security Verification: Proving that devices in different VLANs cannot snoop on each other without a router.

Tools Used:
Cisco Packet Tracer

Switching & Routing Logic



Sprint 3, 4 & 5 Complete!  (Project Finished)

IP Addressing: Assigned static IPv4 addresses to all End Devices (192.168.10.x for Red Zone, 192.168.20.x for Blue Zone).

Access Ports: Configured specific switch ports (fa0/1 and fa0/2) to switchport mode access and assigned them to their respective VLANs.

802.1Q Trunking: Connected the two switches via a Gigabit crossover cable and configured the ports to switchport mode trunk, allowing tagged frames from multiple VLANs to cross the inter-switch link.

Security & Connectivity Verification: Conducted ICMP Ping tests.

✅ Success: End devices in the same VLAN could successfully ping each other across the trunk link.

Secured: End devices in different VLANs resulted in "Request timed out", proving network isolation and security boundaries are fully operational.
