<div align="center">

<!-- Animated Typing Header -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=1BA0D7¢er=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B%2C+I'm+Somphos+Thor;Network+Engineer+%F0%9F%8C%90;IT+Infrastructure+%26+Security+%F0%9F%94%90;Building+Reliable+Networks+%F0%9F%87%B0%F0%9F%87%AD" alt="Typing SVG" />
</a>

### 🌐 Network Engineer • IT Infrastructure • Network Security
**Cambodia 🇰🇭 | Designing, Securing & Automating Enterprise Networks**

<br/>

<!-- Profile & Social Badges -->
<p align="center">
  <a href="https://YOUR-WEBSITE.com">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:YOUR-EMAIL">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=YOUR-GITHUB-USERNAME&style=for-the-badge&color=1BA0D7" alt="Profile Views"/>
</p>

</div>

---

## 👨‍💻 `whoami`

```yaml
name: Somphos Thor
role: Network Engineer | IT Infrastructure Specialist
location: Cambodia 🇰🇭

core_competencies:
  networking: [Routing & Switching, OSPF, BGP, EIGRP, VLANs, STP/RSTP, EtherChannel]
  security: [Firewall Policies, Site-to-Site IPsec VPN, ACLs, Hardening, SSH]
  systems: [Windows Server (AD DS, DNS, DHCP), Linux (Ubuntu), Virtualization]
  monitoring_&_automation: [Zabbix, SNMP, Python, Bash, Git]

current_focus:
  - Advancing through Cisco CCNA / CCNP Enterprise tracks
  - Mastering MikroTik RouterOS & bandwidth engineering
  - Automating network provisioning & backups with Python
```

---

## 🛠️ Network Engineering Arsenal

<div align="center">

| Category | Technologies & Tools |
| :--- | :--- |
| **🌐 Vendors & Routing** | ![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white) ![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=flat-square&logo=mikrotik&logoColor=white) ![OSPF](https://img.shields.io/badge/OSPF-00599C?style=flat-square) ![BGP](https://img.shields.io/badge/BGP-FF6600?style=flat-square) ![EIGRP](https://img.shields.io/badge/EIGRP-1BA0D7?style=flat-square) ![VLAN](https://img.shields.io/badge/VLAN_/_STP-333333?style=flat-square) ![IPv4/IPv6](https://img.shields.io/badge/IPv4_/_IPv6-0078D6?style=flat-square) |
| **🔐 Network Security** | ![Firewall](https://img.shields.io/badge/Firewall-D40000?style=flat-square) ![IPsec VPN](https://img.shields.io/badge/IPsec_VPN-2E8B57?style=flat-square) ![ACL](https://img.shields.io/badge/ACL_Filtering-FF8C00?style=flat-square) ![NAT](https://img.shields.io/badge/NAT_/_PAT-4B0082?style=flat-square) ![SSH](https://img.shields.io/badge/SSH-181717?style=flat-square&logo=gnubash&logoColor=white) |
| **🖥️ Systems & Servers** | ![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) ![Active Directory](https://img.shields.io/badge/Active_Directory-0078D6?style=flat-square) ![DNS/DHCP](https://img.shields.io/badge/DNS_/_DHCP-293239?style=flat-square) |
| **🧪 Simulators & Tools** | ![EVE-NG](https://img.shields.io/badge/EVE--NG-FF6600?style=flat-square) ![GNS3](https://img.shields.io/badge/GNS3-2A2A2A?style=flat-square) ![Packet Tracer](https://img.shields.io/badge/Packet_Tracer-1BA0D7?style=flat-square&logo=cisco&logoColor=white) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) ![WinBox](https://img.shields.io/badge/WinBox-293239?style=flat-square) |
| **📊 Monitoring & Code** | ![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white) ![SNMP](https://img.shields.io/badge/SNMP-00A98F?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

</div>

---

## 🏗️ Enterprise Lab Architecture

GitHub natively renders the Mermaid diagram below to showcase a standard Dual-Site Enterprise Topology:

```mermaid
graph TD
    Internet((🌐 Internet)) --> ISP[☁️ ISP Edge]
    ISP --> HQR[🛡️ HQ Edge Router]
    ISP --> BR[🛡️ Branch Edge Router]

    HQR -. "🔐 IPsec Site-to-Site VPN" .- BR

    subgraph HQ ["🏢 Headquarters Network"]
        HQR --> CoreSW[🔀 Core Layer 3 Switch]
        CoreSW --> VLAN10[💻 VLAN 10: Staff]
        CoreSW --> VLAN20[📞 VLAN 20: Voice]
        CoreSW --> SRV[🖥️ Server Farm: AD / DNS / Zabbix]
    end

    subgraph Branch ["🏬 Branch Office Network"]
        BR --> BrSW[🔀 Branch Switch]
        BrSW --> Users[💻 Branch Users]
        BrSW --> AP[📡 Enterprise WLAN AP]
    end
```

---

## 🚀 Featured Network Projects

| Project | Tech Stack | Architecture & Scope |
| :--- | :--- | :--- |
| **🌐 Enterprise Campus Lab** | `Cisco IOS` `VLAN` `OSPF` `STP` | High-availability multi-VLAN campus network with L3 inter-VLAN routing and EtherChannel |
| **🔐 Site-to-Site IPsec VPN** | `Cisco` `IPsec` `IKEv2` `NAT` | Encrypted tunnel linking HQ and Branch networks over untrusted public WAN links |
| **🛡️ Edge Firewall & ACLs** | `Cisco IOS` `Extended ACLs` | Zone-based segmentation and granular packet filtering to isolate critical server subnets |
| **🌍 MikroTik ISP & Bandwidth** | `RouterOS` `WinBox` `Queues` | Dual-WAN failover, DHCP provisioning, firewall hardening, and QoS traffic shaping |
| **📊 Infrastructure Monitoring** | `Zabbix` `Ubuntu` `SNMPv3` | Real-time telemetry, interface bandwidth graphing, and automated outage alerting |
| **🐍 Network Config Automation** | `Python` `Netmiko` `Paramiko` | Automated CLI configuration backups and multi-vendor bulk VLAN deployment scripts |
| **🖥️ Windows Server Domain** | `Windows Server` `AD DS` `GPO` | Centralized domain controller setup with automated DHCP scopes, DNS, and Group Policy |
| **📡 Enterprise Wireless Lab** | `Cisco WLC` `LWAPP` `802.1Q` | Multi-SSID wireless deployment mapped to isolated guest and corporate VLANs |

---

## 🗺️ Certification & Learning Roadmap

```text
[✅ Networking Fundamentals] ➔ [⏳ Cisco CCNA] ➔ [🎯 CCNP Enterprise] ➔ [🔐 Network Security] ➔ [🤖 NetDevOps / Automation]
```

---

## 📊 GitHub Telemetry

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR-GITHUB-USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-GITHUB-USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=YOUR-GITHUB-USERNAME&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" />
</div>

---

<div align="center">

### 🌐 Connect • Configure • Secure • Automate
*"A good network is invisible — it simply works."*

</div>
