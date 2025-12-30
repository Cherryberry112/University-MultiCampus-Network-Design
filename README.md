
# 🌐 University of Scholars: Enterprise Network Design

This repository contains the complete design and implementation of a full-fledged, multi-campus network for the **University of Scholars**. The project focuses on scalability, redundancy, and efficient resource management using **Cisco Packet Tracer**.

###  Project Overview

The network is designed to connect multiple university campuses through a centralized modular architecture. It implements a robust IP addressing scheme and dynamic routing to ensure seamless connectivity for students, faculty, and administrative services.

###  Key Features

* **Multi-Campus Connectivity**: Integrated modular design allowing for future campus expansion.
* **Dynamic Routing (OSPF)**: Implemented Open Shortest Path First (OSPF) for efficient, automated path selection and rapid convergence.
* **Network Automation (DHCP)**: Centralized and distributed DHCP configuration to automate IP assignment for end-devices.
* **Core Services**: Functional implementation of **DNS** and **Web Servers** to simulate a real-world university intranet.
* **VLAN Segmentation**: Logical separation of departments to enhance security and reduce broadcast traffic.

### 📂 Repository Structure

* **`Project.pkt`**: The primary Cisco Packet Tracer simulation file containing the full logical and physical topology.
* **`Project report.pdf`**: Detailed technical documentation including IP subnetting tables, router configuration commands, and OSPF area designs.

###  Technical Specifications

* **Routing Protocol**: OSPF (Open Shortest Path First)
* **IP Version**: IPv4 with custom Subnetting
* **Key Devices**: Cisco Routers (Series 2811/2911), Layer 2 & 3 Switches, Generic Servers.
* **Services**: HTTP/HTTPS, DNS, DHCP.

###  How to View the Project

1. **Download** and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. **Clone** this repository or download the `.pkt` file.
3. **Open** `University_Network_Design.pkt` in Packet Tracer.
4. **Test Connectivity**: Use the "Simple PDU" tool or the "Ping" command in the desktop terminal of any PC to verify end-to-end communication across campuses.

