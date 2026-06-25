# Enterprise-MultiSite-Network-Design
Designed and implemented a multi-site enterprise network using Cisco Packet Tracer, featuring VLAN segmentation, VTP, OSPF routing, EtherChannel, SSH management, and network security controls to support secure communication between headquarters and branch offices.

# Multi-Site Enterprise Network Design and Implementation

## Project Overview

This project involved designing and implementing a multi-site enterprise network for a fictional organization, TechBridge Solutions Ltd. The network connected headquarters in Northshore (Auckland) and a branch office in Hamilton using Cisco networking technologies.

The objective was to create a secure, scalable, and reliable network infrastructure capable of supporting multiple departments while maintaining efficient communication between locations.

## Technologies Used

* Cisco Packet Tracer
* Cisco IOS
* VLANs
* VTP
* Inter-VLAN Routing
* OSPF Dynamic Routing
* EtherChannel
* Port Security
* SSH Remote Management
* Trunking (802.1Q)
* Network Troubleshooting

## Network Design

The network consisted of:

### Headquarters (Northshore)

* Three Layer 2 switches
* One Cisco router
* Multiple departmental VLANs
* Secure management access

### Branch Office (Hamilton)

* Three Layer 2 switches
* One Cisco router
* Department-based VLAN segmentation
* Secure remote administration

The sites were interconnected through routed links, enabling communication between users located at different offices.

## Key Features Implemented

### VLAN Segmentation

Created multiple VLANs to separate departmental traffic and improve security:

* VLAN 10 – Staff
* VLAN 20 – Customer Services
* VLAN 30 – Finance
* VLAN 40 – IT Department

Each VLAN was assigned its own subnet to reduce broadcast traffic and improve network performance.

### VTP Deployment

Implemented VTP to simplify VLAN management across multiple switches and ensure configuration consistency throughout the network.

### Inter-VLAN Routing

Configured router interfaces to allow communication between different VLANs while maintaining logical separation of departments.

### Dynamic Routing

Implemented OSPF routing between sites to provide automatic route exchange and support future network scalability.

### EtherChannel

Configured EtherChannel links between switches to increase bandwidth and provide link redundancy.

### Network Security

Implemented security measures including:

* Port Security
* Secure SSH management access
* Access port restrictions
* Administrative device management

### Remote Management

Configured SSH access on network devices to enable secure remote administration and eliminate the need for unsecured Telnet connections.

## Testing and Verification

Comprehensive testing was performed to verify:

* VLAN connectivity
* Inter-VLAN communication
* Routing functionality
* OSPF route exchange
* SSH access
* Port Security enforcement
* End-to-end connectivity between sites

All devices successfully communicated according to design requirements.

## Skills Demonstrated

* Enterprise Network Design
* Cisco Routing and Switching
* VLAN Implementation
* Dynamic Routing Protocols
* Network Security
* Network Troubleshooting
* Infrastructure Documentation
* Network Testing and Validation

## Project Outcome

The final solution successfully provided secure communication between multiple departments and branch locations while maintaining network segmentation, scalability, and fault tolerance. The project demonstrates practical implementation of enterprise networking concepts commonly used in production environments.
