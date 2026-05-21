# 🌐 FCAI Network Infrastructure Project

> A comprehensive enterprise network design and implementation for the Faculty of Computers and Artificial Intelligence (FCAI), built using Cisco devices on Packet Tracer.

**Supervised by:** Dr. Issa Sabry & Eng. Karim Rabie  
**Department:** Information Technology — Computer Networks  
**Faculty:** Faculty of Computers and Artificial Intelligence (FCAI)

---

## 📋 Overview

This project documents the design, implementation, and configuration of a full enterprise network infrastructure spanning two main branches:

- **FCAI Branch** — Educational Labs (Floor 1 & Floor 2) using Three-Tier hierarchical design
- **HQ Branch** — Project Management & Administration using Two-Tier design

The network connects both branches via a Serial WAN link with OSPF dynamic routing, ensuring full connectivity across 8 VLANs.

### Key Technologies
- VLANs for logical traffic segmentation
- Router-on-a-Stick for Inter-VLAN Routing
- FLSM Subnetting (/27)
- DHCP Server + DNS Server
- OSPF Area 0 Dynamic Routing
- 802.1Q Trunking

---

## 📁 Repository Contents

```
├── FCAI_Network_Project.pkt   # Cisco Packet Tracer simulation file
├── CN_Project_Report.pdf      # Full technical report
└── README.md                  # Project documentation
```

---

## 🛠️ How to Open

1. Install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)
2. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/FCAI-Network-Project.git
```
3. Open `FCAI_Network_Project.pkt` in Packet Tracer
4. All configurations are pre-loaded and ready to test
