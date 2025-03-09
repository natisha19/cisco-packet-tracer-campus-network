# Campus Network Infrastructure with VLAN, DHCP, and RIP

## Overview
This project designs and implements a **campus-wide network** using **Cisco networking devices**, ensuring proper communication between different departments and campuses. The setup includes VLAN segmentation, dynamic IP allocation via DHCP, and inter-campus connectivity using RIP.

## Features
- **VLANs for Network Segmentation**  
- **DHCP Configuration for Automatic IP Assignment**  
- **RIP Routing for Inter-VLAN Communication**  
- **2911 Routers and 3650 Multilayer Switches** for advanced networking  
- **2960 Switches for Access Layer Connectivity**  
- **WAN Connection for Branch Campus Communication**  
- **Servers (FTP, Web, Email) for Network Services**  

## Network Topology
The network is divided into **three main areas**:
1. **Main Campus** (Admin, HR, Finance, Business, Engineering, Arts, Student Labs, IT)  
2. **Branch Campus** (Health & Science Labs, Student & Staff Labs)  
3. **Cloud Connectivity** (Email Server)  

## Technologies Used
- **Routing & Switching:** Cisco 2911 Routers, 3650 & 2960 Switches  
- **Networking Protocols:** RIP, VLAN, DHCP  
- **WAN Connectivity:** Connecting different campuses  
- **Servers:** FTP, Web, and Email services  

## How It Works
- **Each department operates within its own VLAN.**  
- **DHCP assigns IP addresses dynamically to devices.**  
- **RIP enables inter-VLAN and inter-campus communication.**  
- **Multilayer switches facilitate efficient data traffic management.**  
- **A WAN connection links the main and branch campuses.**  
