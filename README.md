# Network Configuration Project (Cisco Packet Tracer)

## Overview
This project demonstrates the design and configuration of a small company network using Cisco Packet Tracer.
The network was built with multiple VLANs, inter-VLAN routing, and DHCP services.

## Network Topology
- 1 Router
- 1 Switch
- 3 VLANs (IT, Sales, HR)
- Multiple PCs

## VLANs and IP Addressing
- VLAN 10 (IT): 192.168.10.0/24
- VLAN 20 (Sales): 192.168.20.0/24
- VLAN 30 (HR): 192.168.30.0/24

Each VLAN has its own default gateway configured on the router.

## Configuration Details
- VLAN creation and access port assignment on the switch
- Trunk port configuration between switch and router
- Inter-VLAN routing using Router-on-a-Stick
- DHCP pools configured on the router for each VLAN
- Reserved gateway IP addresses excluded from DHCP

## Testing and Verification
- Verified connectivity within each VLAN
- Verified inter-VLAN communication using ping
- Verified automatic IP address assignment using DHCP

## Files Included
- PacketTracer/Company_Network_VLAN_DHCP.pkt
- commands.txt (main configuration commands)
- Diagram/company_network.png
- Screenshots/ (VLAN, DHCP, and ping tests)

## Tools Used
- Cisco Packet Tracer

## Author
Omar Nasr
