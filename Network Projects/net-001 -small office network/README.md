# NET-001: Small Office Network

## Project Overview
This project demonstrates the design and implementation of a secure small office network using Cisco Packet Tracer. The network was designed to provide connectivity for multiple departments while improving security, scalability, and network management through VLAN segmentation and inter-VLAN routing.

## Client Scenario
TechSolutions Ltd required a network for a small office consisting of Reception, Management, Accounts, IT, and a Meeting Room. The client requested secure communication, automatic IP addressing, wireless connectivity, and centralized routing.

## Objectives

- Design a professional office network.
- Separate departments using VLANs.
- Configure trunk links between networking devices.
- Implement Router-on-a-Stick for Inter-VLAN Routing.
- Configure DHCP for automatic IP address allocation.
- Provide wireless connectivity for laptops.
- Verify communication between all departments.

## Network Devices

- 1 Cisco 2911 Router
- 2 Cisco 2960 Switches
- 10 Desktop PCs
- 2 Laptops
- 1 Network Printer
- 1 Wireless Access Point

## Technologies Used

- Cisco Packet Tracer
- VLANs
- Trunking (802.1Q)
- Router-on-a-Stick
- DHCP
- Inter-VLAN Routing
- Wireless Networking

## VLAN Design

| VLAN | Department |
|------|------------|
|10|Reception|
|20|Management|
|30|Accounts|
|40|IT|
|50|Meeting Room|

## Skills Demonstrated

- Network Design
- VLAN Configuration
- Access Port Configuration
- Trunk Configuration
- Router-on-a-Stick
- DHCP Configuration
- Wireless Configuration
- Network Troubleshooting
- Documentation

## Testing

The following tests were successfully completed:

- DHCP address assignment
- Wireless connectivity
- Inter-VLAN communication
- End-to-end Ping tests

## Troubleshooting

### Problem

DHCP requests failed for client devices.

### Cause

The switch port connected to the router was configured as an access port instead of a trunk port.

### Solution

The router-facing switch port was reconfigured as a trunk, allowing VLAN-tagged traffic to reach the router.

## Lessons Learned

This project strengthened my understanding of VLAN segmentation, trunking, Router-on-a-Stick, DHCP, and network troubleshooting. It also reinforced the importance of verifying configurations during deployment.

## Project Status

✅ Completed

Version: 1.0

Author: Jerome Armah