# Project Orion: Enterprise Network Architecture

Designed and deployed a scalable enterprise network in Cisco Packet Tracer featuring VLAN segmentation, inter-VLAN routing, multilayer switching, static routing, and centralized network services.

> ### Implementation Documentation
> This section provides a chronological walkthrough of the enterprise network deployment, highlighting the configuration, verification, and testing performed at each stage of the project lifecycle.

---

### Initial Enterprise Network Topology
Initial network layout featuring a multilayer core switch, departmental access switches, enterprise routers, and a centralized server before configuration.

<img width="1912" height="1794" alt="screen2" src="https://github.com/user-attachments/assets/9fd4b8d4-b889-4be1-b997-a31292836665" />

### Initial Connectivity Testing
Validated physical connectivity using Packet Tracer PDUs before implementing VLANs, trunk links, and Layer 3 routing.

<img width="2913" height="1808" alt="Screen1" src="https://github.com/user-attachments/assets/4121ccb5-6c31-4701-b418-2496fd8fb121" />

## Router Interface Initialization
Enabled and verified router interfaces to establish connectivity between the enterprise network and upstream routers.
<img width="2558" height="1407" alt="02-Router-Interface-Enabled" src="https://github.com/user-attachments/assets/4a1c66f6-7c5f-4933-b0d9-d7fc8bd14788" />

## VLAN Creation and Segmentation
Created departmental VLANs (HR, IT, Sales, Servers, and Management) to logically segment network traffic.
<img width="2566" height="1440" alt="04-VLANs-Created" src="https://github.com/user-attachments/assets/c6fc4049-9a62-495e-8b9f-70a0fb481283" />

## Access Layer VLAN Assignment
Assigned access switch ports to their appropriate VLANs for departmental endpoint connectivity.
<img width="2548" height="1440" alt="06 - Access Layer VLAN and Trunk Configuration" src="https://github.com/user-attachments/assets/07caacc7-87fd-4ade-83e1-24eb09a36667" />

## Trunk Configuration Verification
Configured and verified 802.1Q trunk links between access switches and the multilayer switch.
<img width="2561" height="1440" alt="07 - Access Layer VLAN and Trunk Configuration" src="https://github.com/user-attachments/assets/37060201-681c-4114-ae85-0a4ff259d7fd" />

## Layer 3 Switch (SVI) Configuration
Configured Switch Virtual Interfaces (SVIs) to provide default gateways and enable inter-VLAN routing.
<img width="2555" height="1408" alt="08 - Layer 3 Switch Virtual Interface (SVI) Configuration" src="https://github.com/user-attachments/assets/1c0f29a2-4a77-429b-b280-7863cfdbe547" />

## Routing Table Verification
Verified that all enterprise VLAN networks were successfully installed in the routing table and directly connected through their corresponding Switch Virtual Interfaces (SVIs).
<img width="1511" height="901" alt="Physical Enterprise Network Topology" src="https://github.com/user-attachments/assets/a43ce9ba-fb2c-4e0c-8212-40f4528749f1" />

## Inter-VLAN Connectivity Testing
Validated successful communication between VLAN gateways, client devices, and the centralized server using ICMP connectivity testing across multiple VLANs.
<img width="2561" height="1406" alt="9 - Successful Inter-VLAN Connectivity Testing" src="https://github.com/user-attachments/assets/d7e8b484-77f4-4c6e-947f-fed1c1e45dec" />

## Final Enterprise Topology
Completed enterprise network after implementing VLAN segmentation, trunking, inter-VLAN routing, and end-to-end connectivity validation.
<img width="1512" height="900" alt="Final Enterprise Topology" src="https://github.com/user-attachments/assets/37869bd2-c2d1-4446-8d37-2b2975bd5738" />


