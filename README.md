# Network-Foundation-Homelab

## Overview
A 2-site enterprise network built in Cisco Packet Tracer demonstrating VLAN 
segmentation, inter-VLAN routing, and OSPF between two branch routers.

## Objectives
- Segment traffic using VLANs
- Configure router-on-a-stick for inter-VLAN routing
- Establish dynamic routing with OSPF
- Verify connectivity and troubleshoot using simulation mode

## Topology
! [Network Topology](./topologyhomelab.png)

## IP Addressing Plan
| Segment | Network | VLAN |
|---|---|---|
| Site A LAN | 192.168.10.0/24 | VLAN 10 |
| Site A Voice/Mgmt | 192.168.20.0/24 | VLAN 20 |
| Site B LAN | 192.168.30.0/24 | VLAN 10 |
| WAN link R1-R2 | 10.0.0.0/30 | — |

## Configuration
! [Switch Configuration](./switchconfig.png)
(this is where you add sections as you go — Switch Config, Router Config, OSPF, DHCP, etc.)

## Verification
(ping tests, show commands, screenshots — add as completed)

## What I Learned
(fill in at the end — good for interviews, shows reflection)
