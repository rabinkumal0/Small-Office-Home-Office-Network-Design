# Small-Office-Home-Office-Network-Design
# 🌐 XYZ Company — Small Office Network Design

Cisco Packet Tracer SOHO network for 3 departments using VLANs, Router-on-a-Stick inter-VLAN routing, VLSM subnetting (/26), centralised DHCP, and wireless access per department — all on a single router and switch.

## 📋 What I Built
- **3 VLANs** — Admin/IT (VLAN 10), Finance/HR (VLAN 20), CS/Reception (VLAN 30)
- **Router-on-a-Stick** — sub-interfaces on R1 for inter-VLAN routing
- **VLSM** — 192.168.1.0 split into three /26 subnets (62 hosts each)
- **DHCP** — centralised on router, one pool per VLAN
- **Wireless** — one AP per department with WPA2-PSK
- **Security** — enable secret, encrypted passwords, MOTD banner, native VLAN 1000

## 🌐 IP Addressing

| VLAN | Department | Subnet | Gateway |
|------|-----------|--------|---------|
| 10 | Admin / IT | 192.168.1.0/26 | 192.168.1.1 |
| 20 | Finance / HR | 192.168.1.64/26 | 192.168.1.65 |
| 30 | CS / Reception | 192.168.1.128/26 | 192.168.1.129 |

## 🛠️ Technologies
`Cisco Packet Tracer` `VLANs` `Router-on-a-Stick` `802.1Q` `DHCP` `VLSM` `WPA2`
