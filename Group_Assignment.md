# Group Assignment

## Lab 1

Assignment link : [Lab1](https://drive.google.com/drive/folders/12igTDyQwVWYtyPYPUFp_X_8hRi_3XuIe?usp=sharing)

This lab documents the configuration and verification of a basic local area network (LAN) consisting of a router, a switch, and two PCs using Packet Tracer. It focuses on analyzing network protocols like ARP and ICMP through connectivity tests and troubleshooting scenarios involving subnet masks and default gateways.

## Lab 2

Assignment link : [Lab2](https://drive.google.com/drive/folders/1M2oyONDqAgAM3O3NShCe0fuCJn_DTRtc?usp=sharing)

This lab focuses on Inter-VLAN routing and VLAN management configurations, utilizing sub-interfaces and trunking to enable communication between different network segments. It features several troubleshooting scenarios, including incorrect VLAN assignments, trunking misconfigurations, and gateway errors, to demonstrate robust network security practices like the use of a management VLAN and blackhole VLANs for unused ports.

## Lab 3

Assignment link : [Lab3](https://docs.google.com/document/d/1VNp8npP7U2oHTbFInu2mMqLKZAhu4DMrg3glnVcItkI/edit?usp=sharing)

This lab focuses on configuring Router-on-a-Stick inter-VLAN routing to facilitate a MIME-based file transfer between a client and server in different broadcast domains. By combining network layer configurations with application-layer engineering, it demonstrates how 802.1Q tagging, TCP reliability, and JSON metadata interact to preserve data meaning across the OSI stack.

## Lab 4

Assignment link : [Lab4](https://drive.google.com/drive/folders/1-37542pOfWwcTbrW8RJKtGT57pNXccm-?usp=sharing)

This lab focuses on the implementation of a simulated internet architecture connecting two private LANs through Static Routing and NAT (PAT overload). It demonstrates the deployment of stateful and stateless services using containerized mockup infrastructure, allowing for a comparative analysis of session persistence and application behavior across simulated public and private network segments.

## New Network

Assignment link : [New Network](https://drive.google.com/drive/folders/1efLgvRvZgSj4z_xfi4NvnZRvThgi01-t?usp=sharing)

# What I have learned from these labs

## 1. Network Connectivity & Protocol Fundamentals (Lab 1)

**Address Resolution**: Mastered how **ARP (Address Resolution Protocol)** must resolve a destination MAC address before **ICMP (Ping)** can begin data transmission
**Device Roles**: Verified that a **Switch** functions at Layer 2 by learning MAC addresses, while a **Router** operates at Layer 3 to forward packets between interfaces
**Troubleshooting**: Identified that mismatched subnet masks or administrative shutdowns are primary causes for connectivity failure

## 2. VLAN Management & Network Security (Lab 2)

**Inter-VLAN Routing**: Implemented communication between different subnets using a Router with sub-interfaces
**802.1Q Trunking**: Configured trunk links to allow multiple VLANs to share a single physical connection between devices
**Security Posture**: Applied **Management VLANs** (VLAN 99) for system isolation and **Blackhole VLANs** (VLAN 999) to secure unused ports against unauthorized access

## 3. Router-on-a-Stick & Application Semantics (Lab 3)

Blends classical networking with application-layer engineering using custom protocols
**Router-on-a-Stick**: Configured sub-interfaces with specific 802.1Q encapsulation to manage multiple broadcast domains over a single link
**MIME & Metadata**: Deployed a **MIME-aware** socket server that uses **JSON headers** to provide semantic meaning (file type and size) to binary payloads
**Encapsulation Analysis**: Utilized **Wireshark** to observe the **TCP Three-Way Handshake** and analyze how application data survives multiple layers of encapsulation

## 4. Distributed Systems & NAT Simulation (Lab 4)

**Network Address Translation (NAT)**: Implemented **PAT (Port Address Translation)** to allow private 192.168.x.x traffic to reach the simulated internet
**Service Architecture**: Compared the behavior of **Stateless** vs. **Stateful** APIs, verifying that stateful services require persistent **Session-IDs** to maintain identity across NAT
**Infrastructure-as-Code (IaC)**: Mastered modern DevOps workflows by deploying containerized services using automated scripts and environment configuration files

---
**Technical Keywords**: `Cisco Packet Tracer` `CLI` `Inter-VLAN Routing` `Router-on-a-Stick` `802.1Q Trunking` `NAT Overload` `Static Routing` `MIME Protocol` `JSON Metadata` `Wireshark Analysis` `TCP/UDP` `Stateless/Stateful APIs` `Infrastructure-as-Code` `Containerization` `Blackhole VLAN`
