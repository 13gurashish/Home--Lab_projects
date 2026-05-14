Enterprise Network Lab — Cisco Packet Tracer

Project Overview
Designed and built a complete multi-department 
enterprise network simulating a real company 
environment with 3 VLANs, inter-VLAN routing, 
and trunk ports.

Network Topology
![Full Topology](screenshots/01-full-topology.png)

What I Configured
- ✅ 3 VLANs (HR, Finance, Sales)
- ✅ Trunk ports between all switches
- ✅ Inter-VLAN routing (Router on a Stick)
- ✅ End-to-end connectivity verified

Network Details
| Device | Role | VLAN |
|--------|------|------|
| R1 | Router | All VLANs |
| Core-SW | Core Switch | Trunk |
| SW1-HR | Access Switch | VLAN 10 |
| SW2-Finance | Access Switch | VLAN 20 |
| SW3-Sales | Access Switch | VLAN 30 |

IP Addressing
| Department | VLAN | Network | Gateway |
|------------|------|---------|---------|
| HR | 10 | 192.168.10.0/24 | 192.168.10.1 |
| Finance | 20 | 192.168.20.0/24 | 192.168.20.1 |
| Sales | 30 | 192.168.30.0/24 | 192.168.30.1 |

Verification Screenshots

VLAN Configuration
![VLANs](screenshots/02-vlan-brief.png)

Trunk Ports
![Trunks](screenshots/03-trunk-ports.png)

Router Interfaces
![Router](screenshots/04-router-interfaces.png)

Successful Ping Test
![Ping](screenshots/05-ping-test.png)

What I Learned
- How VLANs segment network traffic
- How trunk ports carry multiple VLANs
- How Router on a Stick enables inter-VLAN routing
- How to verify network configs with show commands

Tools Used
- Cisco Packet Tracer
- draw.io (network diagram)

Certifications
- ✅ CompTIA A+
- 🔄 CCNA In Progress
