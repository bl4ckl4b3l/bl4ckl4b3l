# Hi, I'm Kyle 👋

### Cybersecurity Professional & Systems Administrator

I am a cybersecurity professional and WGU graduate with a B.S. in Cybersecurity & Information Assurance. I specialize in defensive security architecture, enterprise network engineering, and system operations. I continuously refine my skill set through hands-on technical labs, real-world GRC integration, and industry certifications.

**Objective**  
Actively engineering defensive homelab infrastructure using Proxmox, Docker, Ubiquiti, Wazuh, Authentik, Traefik, and integrated SIEM platforms to master modern threat detection, network segmentation, and automated incident response. My focus is applying practical expertise in vulnerability management, secure network architecture, and defensive operations to strengthen security posture across both lab environments and enterprise production infrastructures.

---

### 🛠️ Technical Stack & Tools

**Network & Perimeter Security**  
![Ubiquiti](https://img.shields.io/badge/Ubiquiti-055348?style=flat&logo=ubiquiti&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1DE?style=flat&logo=traefik&logoColor=white)
![Pi-hole](https://img.shields.io/badge/Pi--Hole-96060C?style=flat&logo=pi-hole&logoColor=white)

**Endpoint, Detection & SIEM**  
![Wazuh](https://img.shields.io/badge/Wazuh-0052CC?style=flat&logo=wazuh&logoColor=white)
![Security Onion](https://img.shields.io/badge/Security_Onion-1D2B3A?style=flat&logo=linux&logoColor=white)
![CrowdSec](https://img.shields.io/badge/CrowdSec-FF6C37?style=flat&logo=crowdsec&logoColor=white)

**Identity, Virtualization & Orchestration**  
![Authentik](https://img.shields.io/badge/Authentik-FD4F00?style=flat&logo=authentik&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

---

### 📜 Certifications
* **CompTIA:** Security+ | CySA+ | Pentest+ | Network+ | A+ | Data+
* **LPI:** Linux Essentials

---

### 🛡️ Defensive Homelab Architecture

Enterprise-grade, blue-team-focused lab designed around zero-trust principles, active telemetry collection, and multi-layered defense:

* **Perimeter & Network Segmentation:** Multi-VLAN architecture routed via Ubiquiti UDM-Pro with strict inter-VLAN firewall rules and automated intrusion detection.
* **Endpoint Detection & Vulnerability Scanning:** Distributed Wazuh agents integrated with a central manager for real-time file integrity monitoring (FIM), audit logging, and vulnerability assessment.
* **Network Traffic Analysis:** Security Onion deployment utilizing Suricata for NIDS and Zeek for high-fidelity network metadata capture.
* **Identity & Access Management:** Authentik centralized SSO enforcement backed by automated TLS termination via Traefik reverse proxy.
* **Collaborative IPS & Threat Blocking:** CrowdSec integrated with perimeter firewalls for automated dynamic IP ban lists, complemented by Pi-hole for network-wide DNS filtering.
* **Observability:** Centralized logging, metric scraping with Prometheus, and visualization dashboards via Grafana.

---

### 📌 Highlighted Projects

* **[Homelab Distributed Wazuh SIEM](./)** — Multi-node deployment monitoring cross-VLAN Linux/Windows endpoints with custom alert routing.
* **[Homelab SSO & Zero-Trust Access](./)** — Unified identity management using Authentik, enforcing OIDC/SAML authentication and MFA across self-hosted services.
* **[Home Perimeter Network Security](./)** — VLAN-isolated network architecture separating trusted internal hosts, IoT traffic, and lab environments.
