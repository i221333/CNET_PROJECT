# CNET_PROJECT
Streamlined Network Design for Small Businesses

## Project Overview

The objective of this project is to design an efficient, secure, and scalable network for a small business, enabling clear communication and easy access across various departments. The project demonstrates the application of networking concepts such as IP addressing, routing, and DHCP configuration using Cisco devices, with OSPF (Open Shortest Path First) as the primary routing protocol.

## Tools & Technologies

- **Cisco Packet Tracer:** For network design and simulation.
- **OSPF (Open Shortest Path First):** Dynamic routing between routers.
- **DHCP (Dynamic Host Configuration Protocol):** Dynamic IP allocation to network devices.

## Implementation Details

### Description

- **Departments:**  
  The network includes 5 departments, each equipped with routers(2811), switches(2960-24TT), and other end devices, all attached to a central router for their segment.
- **IP Addressing:**  
  Each department is assigned a unique subnet for external access and several internal subnets for organized IP deployment.
- **Routing:**  
  OSPF is configured for dynamic routing, ensuring seamless inter-department communication.
- **DHCP:**  
  A centralized DHCP server dynamically assigns IP addresses to all devices within the network.

### Explanation

The network was set up in Cisco Packet Tracer by configuring routers, switches, and PCs:
- Router interfaces were assigned IP addresses based on departmental subnets.
- OSPF was implemented for dynamic routing between routers to enable communication across all departments.
- DHCP was configured on routers to automatically provide IP addresses to connected devices, ensuring efficient IP management and reducing manual configuration.

### Snippets
![Screenshot 2024-12-04 233139](https://github.com/user-attachments/assets/9fe02761-f8ee-4e5f-bf27-3e54fad946b5)

## Getting Started

1. **Launch** `CNET_PROJ.pkt` in Cisco Packet Tracer and allow a few minutes for the setup process to complete.
2. **Validate the network topology** by sending test packets between two end devices. First, select the closed envelope icon from the right panel, then choose the sender followed by the receiver. The bottom-right corner of the interface will display confirmation messages for both successful and failed transmissions.
