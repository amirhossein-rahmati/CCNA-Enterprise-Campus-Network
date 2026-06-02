# CCNA Enterprise Campus Network

## Overview

This project simulates a small enterprise campus network using Cisco Packet Tracer.

The network is divided into multiple departments using VLANs and implements Router-on-a-Stick for inter-VLAN communication. Additional security and management features such as VTP, DHCP, Port Security, BPDU Guard, and PortFast are also configured.

---

## Network Topology

![Network Topology](topology.png)

---

## Network Departments

| VLAN | Department | Network |
|--------|------------|------------|
| VLAN 10 | IT | 192.168.10.0/24 |
| VLAN 20 | Marketing | 192.168.20.0/24 |
| VLAN 30 | Managers | 192.168.30.0/24 |
| VLAN 40 | Security | 192.168.40.0/24 |
| VLAN 50 | Servers | 192.168.50.0/24 |

---

## Technologies Used

- VLAN Segmentation
- VTP (VLAN Trunking Protocol)
- Router-on-a-Stick
- DHCP
- Port Security
- Sticky MAC Addresses
- BPDU Guard
- PortFast
- Trunk Links
- Inter-VLAN Communication

---

## Devices Used

### Router
- Cisco 2811 Router

### Switches
- Cisco 3560 Switches
- Cisco 2960 Switches

### End Devices
- PCs
- Laptops
- Printers
- Servers

---

## Configuration Highlights

### VLAN Segmentation
Different departments are separated into dedicated VLANs to improve network organization and security.

### Router-on-a-Stick
A single router interface with subinterfaces is used to provide communication between VLANs.

### DHCP
Automatic IP address assignment is configured for all departments.

### VTP
VLAN information is distributed efficiently between switches using VTP.

### Port Security
Port Security with Sticky MAC Address learning is configured to prevent unauthorized access.

### STP Protection
PortFast and BPDU Guard are enabled on access ports to improve stability and protect against accidental loops.

---

## Verification

### DHCP Test
- All hosts successfully receive IP addresses automatically.

### Router-on-a-Stick Test
- Devices in different VLANs can communicate successfully.

### Trunk Verification
- VLAN traffic is carried correctly across trunk links.

### Port Security Test
- Unauthorized devices are restricted according to configured policies.

### STP Protection Test
- PortFast and BPDU Guard operate correctly on access ports.

---

## Skills Demonstrated

- Cisco Switching
- VLAN Design
- Router-on-a-Stick Configuration
- DHCP Deployment
- Network Segmentation
- Network Security Fundamentals
- Enterprise Network Design
- Cisco IOS Configuration
- Troubleshooting

---

## Files Included

- `CCNA-Enterprise-Campus-Network.pkt`
- `README.md`
- `topology.png`

---

## Author

**Amirhossein Rahmati**

Aspiring Network Engineer | CCNA Student | IT Infrastructure Enthusiast
