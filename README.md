# CampusScale Network Simulation with OSPF, EIGRP, and RIP

A scalable campus network simulation built using **Cisco Packet Tracer** that integrates multiple dynamic routing protocols, IP subnetting, and network services to replicate a realistic enterprise-level network environment.

---

# Project Overview

This project demonstrates the design and implementation of a **large-scale campus network** using **multiple routing protocols and network services**. The topology integrates **OSPF, EIGRP, and RIP** across different network zones while enabling communication between them through **routing redistribution**.

The network is designed using **VLSM (Variable Length Subnet Masking)** to efficiently allocate IP addresses and includes key services such as **DHCP, NAT, ACLs, and a Mail Server**.

The goal of the simulation is to demonstrate how different routing protocols can coexist and interoperate in a real-world enterprise network.

---

# Key Features

### VLSM Subnetting
Efficient IP address allocation using Variable Length Subnet Masking to support networks with different host requirements.

### Dynamic Routing Protocols
Implementation of multiple routing protocols across the topology:

- **EIGRP**
- **OSPF (Area 1 and Area 2)**
- **RIP**

### Routing Redistribution
Configured redistribution between routing domains to ensure full connectivity between networks using different protocols.

### Centralized DHCP
A centralized **DHCP server** automatically assigns IP addresses to devices across the network.

### NAT Configuration
Network Address Translation is configured on:

- **Router20**
- **Router8**

This allows private networks to communicate with external networks.

### Access Control Lists (ACLs)
ACLs are implemented to:

- Restrict web access for selected PCs
- Block specific smartphones
- Restrict access for entire networks when required

### Mail Server
A configured **mail server** allows internal communication between devices within the simulated campus network.

### Realistic Network Topology
The simulation includes multiple devices such as:

- Routers
- Switches
- PCs
- Smartphones
- Servers

---

# Learning Outcomes

Through this project the following networking skills were developed:

- Advanced **routing protocol configuration**
- **Interoperability between multiple routing protocols**
- **Subnet planning and VLSM design**
- DHCP and NAT configuration
- Network security using **ACLs**
- Network troubleshooting and connectivity testing

---

# Tools & Technologies

- Cisco Packet Tracer
- OSPF
- EIGRP
- RIP
- NAT
- DHCP
- ACLs
- VLSM
- Mail Server
- Network Simulation

---

# Project Structure

```
CampusScale-Network-Simulation
│
├── topology.pkt
├── README.md
└── documentation (optional)
```

- `topology.pkt` → Cisco Packet Tracer simulation file  
- `README.md` → Project documentation

---

# Network Architecture

The campus network is divided into multiple routing domains:

- **EIGRP domain**
- **OSPF domain (Area 1 & Area 2)**
- **RIP domain**

Redistribution points are configured to ensure communication between all domains.

Additional services include:

- DHCP server for IP assignment
- NAT for external communication
- ACLs for traffic filtering
- Mail server for internal communication

---

# Challenges Faced

During the development of this simulation, several challenges were encountered:

- Designing **efficient subnet allocation** using VLSM
- Configuring correct **routing redistribution points**
- Implementing **ACL rules** without blocking legitimate traffic
- Ensuring **end-to-end connectivity** across different routing protocols

---

# Applications

This type of network architecture can be applied in:

- University campus networks
- Enterprise office networks
- Multi-department organizations
- Training environments for networking students

---

# Author

Developed as part of coursework at:

**National University of Computer and Emerging Sciences (FAST-NUCES)**

---

# Skills Demonstrated

- Computer Networking
- Routing Protocol Configuration
- Access Control Lists (ACL)
- Network Security
- Subnetting (VLSM)
- Network Troubleshooting
