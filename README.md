
# 🏥 SriLanka-HealthNet-Topology

A secure, multi-site network topology designed for the **Sri Lankan Ministry of Health**, built using **Cisco Packet Tracer**.

This project simulates real-world healthcare infrastructure—connecting headquarters, regional hospitals, and mobile clinics—with a focus on **security, scalability, and remote access**.

---

## 📌 Project Overview

This network design includes:

- 🏢 **Headquarters (Colombo)** with VLANs for Admin, Doctors, and IT staff
- 🏥 **Branch Hospitals** in Kandy, Matale, and Nuwara Eliya
- 🚐 **Mobile Clinic** with secure VPN access
- 🌐 **ISP Gateway Router** for internet and remote access
- 🔐 **VPN Tunnels** for site-to-site and remote encrypted communication
- 🧠 **Centralized EMR Server** for Electronic Medical Records
- 🔧 **DHCP, DNS, and Web Servers** for internal services
- 📶 **OSPF Routing**, **ACLs**, and **Port Security**

---

## 🧱 Topology Highlights

- 🔄 **Multilayer Switching (Layer 3)** at HQ for inter-VLAN routing
- 🔒 **ACLs** to control communication between departments
- 🛡️ **VPN Gateway Routers** for secure remote access
- 📡 **DHCP Relay Agent** from HQ to branches
- 📊 **Syslog and SNMP** for centralized monitoring
- 🔁 **Redundant HQ Routers** for high availability and failover

---

## 🧪 Technologies Used

- Cisco Packet Tracer
- VLANs & Trunking
- OSPF Dynamic Routing
- Site-to-Site & Remote VPN
- DHCP & DNS
- Access Control Lists (ACLs)
- Port Security
- SNMP & Syslog Logging

---

## 🚀 How to Use

1. Open the `.pkt` file using **Cisco Packet Tracer (version 8.2 or higher)**.
2. Review the **network topology** and **device labels**.
3. Check the configurations on **routers**, **switches**, and **servers**.
4. Use the simulation tab to test:
   - VLAN segmentation
   - VPN tunnels
   - DHCP leases
   - ACL restrictions
   - Internet connectivity
5. Modify or extend the topology for your own learning.

---

## 📂 File Structure

```

SriLanka-HealthNet-Topology/
├── Topology Diagram.png        # Network diagram (HQ + Branches + VPN)
├── HealthNet.pkt               # Cisco Packet Tracer project file
├── configs/                    # Router and switch config files (optional)
│   ├── R\_HQ.cfg
│   ├── R\_Kandy.cfg
│   └── ...
├── README.md

```

---

## 📚 Design Justification

> This design follows **department-wise delegation** and **decentralized server control**, improving performance and management. Site-to-site VPN ensures **secure communication** between hospitals while maintaining **local autonomy** for each region's services.

---

Let me know if you want me to help generate the `.pkt` file, config backups, or add a license/badge to your GitHub repository!
```
