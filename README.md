```markdown
# 🏥 SriLanka-HealthNet-Topology

A secure multi-site network topology designed for the **Sri Lankan Ministry of Health**, built using **Cisco Packet Tracer**.
This project simulates real-world infrastructure connecting headquarters, branch hospitals, and mobile clinics with a focus on security, scalability, and remote access.

---

## 📌 Project Overview

This network design includes:

- 🏢 **Headquarters (Colombo)** with VLANs for Admin, Doctors, and IT
- 🏥 **Branch Hospitals** in Kandy, Matale, and Nuwara Eliya
- 🚐 **Mobile Clinic** with VPN access
- 🌐 **ISP Gateway** for internet and remote connectivity
- 🔐 **VPN Tunnels** for secure site-to-site and remote access
- 🧠 **Centralized EMR Server** for patient data
- 🔧 **DHCP, DNS, Web Servers** for internal services
- 📶 **OSPF Routing**, **ACLs**, and **Port Security**

---

## 🧱 Topology Highlights

- 🔄 **Multilayer Switching** at HQ for inter-VLAN routing
- 🔒 **ACLs** to restrict access between departments
- 🛡️ **VPN Gateway** for encrypted communication
- 📡 **DHCP Relay** from HQ to branches
- 📊 **Syslog & SNMP** for monitoring and logging
- ⚙️ **Redundant HQ Routers** for high availability

---

## 🧪 Technologies Used

- Cisco Packet Tracer
- VLANs & Trunking
- OSPF Routing
- VPN Tunnels
- DHCP & DNS
- ACLs & Port Security
- SNMP & Syslog

---

## 🚀 How to Use

1. Open the `.pkt` file in Cisco Packet Tracer.
2. Review the topology and device labels.
3. Explore configurations on routers, switches, and servers.
4. Test connectivity, VPN tunnels, and ACL restrictions.

---

## 📂 File Structure

```
SriLanka-HealthNet-Topology/
├── Topology Diagram.png
├── HealthNet.pkt
├── README.md
```

---
