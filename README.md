# Secure Hotel Enterprise Network

A hands-on enterprise networking and cybersecurity project built using Cisco Packet Tracer and complemented with a separate Kali Linux practice lab.

This project demonstrates how to design, secure, validate, and document a small enterprise hotel network using industry-standard networking concepts and security best practices.

> Note: The Cisco Packet Tracer network and the Kali Linux lab were developed as separate learning environments. Kali Linux was used for cybersecurity practice and documentation, not as a direct attack against the Packet Tracer network.

## Network Topology

![Network Topology](screenshots/topology/Network-Topology.png)
---

# Project Overview

The objective of this project was to simulate a secure hotel enterprise network by implementing network segmentation, secure communication, and Layer 2 security features while documenting the entire implementation professionally.

---

# Project Objectives

- Design an enterprise hotel network
- Implement VLAN segmentation
- Configure Inter-VLAN Routing
- Secure the network using Cisco security features
- Validate the implemented security controls
- Practice basic cybersecurity tools using Kali Linux
- Document the project professionally using GitHub

---

# Network Topology

The complete network topology is available in:
screenshots/topology/

The topology includes:

- Hotel Router
- Core Switch
- Floor Switch
- Hotel Server
- Management Network
- Reception Network
- Staff Network
- Guest Wi-Fi Network

---

# VLAN Architecture

| VLAN | Department |
|-------|------------|
| 10 | Management |
| 20 | Reception |
| 30 | Staff |
| 40 | Guest Wi-Fi |
| 50 | Servers |

---

# Implemented Security Features

### VLAN Segmentation

Separated departments into isolated VLANs to improve security and reduce unnecessary broadcast traffic.

---

### Access Control Lists (ACL)

Implemented Extended ACLs to restrict Guest Wi-Fi users from accessing internal enterprise resources while allowing legitimate traffic.

---

### DHCP Snooping

Configured DHCP Snooping to protect the network against rogue DHCP servers.

---

### Port Security

Implemented Port Security on access ports to restrict unauthorized devices.

---

# Validation

The implemented security controls were successfully validated.

Validation included:

- ACL blocking unauthorized access
- DHCP Snooping verification
- Port Security verification
- Network connectivity testing

### ACL Validation

![ACL Validation](screenshots/Validation/ACL-Blocking-Access.png)

### Network Connectivity

![Network Connectivity](screenshots/Validation/Network-Connectivity.png)

---

# Kali Linux Lab

A separate Kali Linux lab was used to practice fundamental cybersecurity techniques including:

- Host Discovery
- Service Enumeration
- Packet Analysis using Wireshark

The purpose of the lab was to strengthen practical cybersecurity skills alongside the Cisco networking project.

### Nmap Host Discovery

![Nmap Host Discovery](screenshots/Kali/Nmap-Host-Discovery.png)

### Service Enumeration

![Service Enumeration](screenshots/Kali/Service-Enumeration.png)

---
# Wireshark Analysis

Wireshark was used to observe and analyze network traffic during the lab exercises.

### ICMP Traffic

![ICMP Analysis](screenshots/Wireshark/ICMP-Traffic-Analysis.png)

### ARP Observation

![ARP Analysis](screenshots/wireshark/ARP-Traffic-Before-Attack.png)

# Repository Structure
Secure-Hotel-Enterprise-Network
│
├── docs
├── packet-tracer
├── kali-lab
└── screenshots

---

# Technologies Used

### Networking

- Cisco Packet Tracer
- Cisco IOS
- VLANs
- Router-on-a-Stick
- DHCP

### Security

- Access Control Lists (ACL)
- DHCP Snooping
- Port Security

### Cybersecurity

- Kali Linux
- Nmap
- Wireshark

---

# Skills Demonstrated

- Enterprise Network Design
- Network Segmentation
- Cisco Switching
- Cisco Routing
- VLAN Configuration
- ACL Configuration
- DHCP Snooping
- Port Security
- Network Validation
- Basic Network Reconnaissance
- Packet Analysis
- Technical Documentation

---

# Future Improvements

Future versions of this project may include:

- Dynamic ARP Inspection (DAI)
- Active Directory Integration
- pfSense Firewall
- IDS / IPS
- SIEM Integration
- Vulnerability Assessment Lab

---

# Author

This project was developed as part of my personal networking and cybersecurity learning journey and is included in my professional portfolio.
