# networking-lab


- R0 ↔ R1 ↔ R2 ↔ R3 (main router chain)
- R1 connects to LAN1
- R2 connects to LAN2
- R3 connects to LAN3

---

## Technologies Used

- IPv4 Addressing
- OSPF (Open Shortest Path First)
- DHCP (Dynamic Host Configuration Protocol)
- ACL (Access Control Lists)
- Cisco Packet Tracer

---

## Features

- Dynamic routing configured using OSPF across all routers
- DHCP configured on routers to automatically assign IP addresses to end devices
- Three separate LANs connected to different routers
- ACL implemented to restrict traffic between networks
- LAN3 is blocked from accessing LAN2 for security purposes
- End-to-end connectivity verified using ping tests

---

## DHCP Configuration

Routers were configured as DHCP servers to automatically assign IPv4 addresses to devices in each LAN.  
This removes the need for manual IP configuration on end devices and simplifies network management.

---

## Security (ACL)

An Access Control List was configured to block traffic from LAN3 to LAN2 while allowing other permitted communications.

This demonstrates basic network security and traffic filtering between different subnets.

---

## Results

- All routers successfully exchange routing information using OSPF
- Devices in all LANs receive correct IP addresses via DHCP
- LAN1, LAN2, and LAN3 can communicate where allowed
- LAN3 is successfully restricted from accessing LAN2 using ACL rules

---

## Files Included

- `.pkt` Cisco Packet Tracer project file
- Router configuration files
- Screenshots of topology and tests

---

## Author

Network simulation project created for learning and portfolio development.
