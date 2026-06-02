# CCNA Enterprise Campus Network

## Overview

This project simulates a small enterprise campus network using Cisco Packet Tracer.

The network is divided into multiple departments using VLANs and includes security and management features commonly found in real-world environments.

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

## Features

- VLAN Segmentation
- VTP Configuration
- Router-on-a-Stick
- DHCP Configuration
- Port Security
- Sticky MAC Addresses
- BPDU Guard
- PortFast
- Trunk Links
- Inter-VLAN Communication

---

## Devices Used

- Cisco 2811 Router
- Cisco 3560 Layer 3 Switches
- Cisco 2960 Access Switches
- PCs, Laptops, Printers
- Servers


---

## Verification

### DHCP
All hosts automatically receive IP addresses from DHCP pools.

### Inter-VLAN Routing
Devices in different VLANs can communicate through Router-on-a-Stick configuration.

### Port Security
Unauthorized devices are restricted according to configured security policies.

### STP Protection
BPDU Guard and PortFast are enabled on access ports.

---

## Skills Demonstrated

- Network Segmentation
- Switching Technologies
- VLAN Management
- Network Security Basics
- Enterprise Network Design
- Cisco IOS Configuration

---

## Author

Amirhossein Rahmati
