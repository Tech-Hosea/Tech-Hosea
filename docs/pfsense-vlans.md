---
layout: default
title: pfSense VLAN Setup
---

# 🌐 pfSense VLAN Setup

## Lab Overview
- pfSense VM running on VirtualBox
- Managed Cisco switch
- VLAN10 (Admin), VLAN20 (Guests)

## Steps
1. Created interfaces and assigned static IPs in pfSense
2. Configured switch trunk and access ports
3. Tested isolation and DHCP lease on each VLAN

## Results
- VLANs successfully isolated
- DHCP working independently per subnet

![VLAN Diagram](../images/vlan-diagram.png)
