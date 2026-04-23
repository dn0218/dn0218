# 👋 Hello, I'm Danny Hii Lu Hui
### Linux System Administrator & Network Engineer | RHCSA Candidate
📍 Kuala Lumpur, Malaysia 🇲🇾

---

## 🚀 About Me
I am a technical professional with experience in the telecommunications industry, specializing in **Network Engineering** and **Linux System Administration** on RHEL-based environments. Passionate about building secure, automated, and production-ready infrastructure, I am currently deepening my expertise through self-study for the **RHCSA** certification, with a strong focus on **Ansible automation** for infrastructure orchestration and **K3s** for lightweight Kubernetes deployment.

My recent focus lies in **modern container orchestration** using **rootless Podman** and **Systemd Quadlet**, combined with **LVM storage automation** — bridging traditional Linux administration with cloud-native practices.

- 🔭 **Currently working on**: Ansible-driven infrastructure automation, lightweight K3s cluster orchestration, and distributed container observability.

- 🌱 **Learning**: Advanced Ansible automation patterns, K3s high-availability cluster design with external datastores, and Prometheus/Grafana observability stack.
- 
- 💬 **Ask me about:** Rootless Podman, Quadlet, LVM automation, **Ansible IaC, K3s lightweight Kubernetes**, Zabbix multi-node monitoring, RHEL hardening, Networking (VLANs, VPNs, VoIP).
- ⭐ **Goal:** To become a cross-domain expert in secure, automated Infrastructure, Ansible-driven orchestration, K3s/Kubernetes, and Containerized Systems.
---

## 🔧 Skills & Tools
| Category              | Skills |
|-----------------------|--------|
| **Operating Systems** | RHEL 9 / Rocky Linux (RHCSA level), Ubuntu Server |
| **Containers**        | **Rootless Podman**, **Systemd Quadlet**, Podman Pods, Containerfile |
| **Storage**           | **LVM** (PV/VG/LV management, dynamic extension), XFS (`xfs_growfs`), SELinux container contexts |
| **Networking**        | Networking | VLANs, OpenVPN, Switching/Routing, FreePBX/VoIP, K3s Networking (Flannel VXLAN, Klipper ServiceLB)
| **Monitoring**        | **Zabbix 6.4** (Server + multi-node monitoring), Prometheus/Grafana (basic) |
| **Automation & Security** | Bash scripting, Systemd timers/services, firewalld, SSH hardening, Server hardening, SELinux |
| **Web & Services**    | Nginx, Apache (HTTPD), MariaDB/MySQL, rootless container deployment |

---

## 📂 Highlighted Projects (Showcasing RHCSA + Modern Container Skills)

### 1. 🛡️ Hardened Rootless Podman with Quadlet
**[Hardened-Rootless-Podman-with-Quadlet](https://github.com/dn0218/Hardened-Rootless-Podman-with-Quadlet)**  
Production-grade rootless Podman setup on RHEL 9 using **Systemd Quadlet** for declarative container management. Features automated image updates via systemd timers, immutable containers (`--new`), user namespaces, and PASTA networking. Demonstrates enterprise security and operational excellence.

### 2. 💾 RHEL Storage Orchestrator — LVM + Podman Quadlet Automation
**[RHEL-Storage-Orchestrator-LVM-Podman-Quadlet-Automation](https://github.com/dn0218/RHEL-Storage-Orchestrator-LVM-Podman-Quadlet-Automation)**  
Automated LVM storage provisioning that dynamically creates or extends logical volumes during Podman container startup (via `ExecStartPre` + Quadlet). Includes smart detection logic, XFS online growth, and SELinux compliance — solving "disk full" issues in containerized environments.

### 3. 📊 Containerized Zabbix 6.4 Stack with Multi-Node Monitoring
**[Containerized-Zabbix-6.4-Stack-with-Multi-Node-Monitoring](https://github.com/dn0218/Containerized-Zabbix-6.4-Stack-with-Multi-Node-Monitoring)**  
Full Zabbix 6.4 monitoring stack (Server + Web + DB) deployed using **rootless Podman Pods**. Supports cross-VM agent monitoring with proper SELinux and firewall configuration.

### 4. 🌐 Podman Containerized Web Stack with LVM Integration
**[Podman-Containerized-Web-Stack-with-LVM-Integration](https://github.com/dn0218/Podman-Containerized-Web-Stack-with-LVM-Integration)**  
Rootless Nginx web server with persistent LVM-backed storage, SELinux-aware volume mounts, custom Containerfile, and professional logging architecture.

### 5. 🚀 K3s Declarative Nginx Cluster — GitOps with SELinux Hardening
**[K3s-Declarative-Nginx-Cluster](https://github.com/dn0218/K3s-Declarative-Nginx-Cluster)**
High-availability Nginx deployment on a hybrid K3s cluster (RHEL 9.7 Master + Rocky 10.1 Worker). Features **zero-root privilege execution** (UID 101), **declarative GitOps workflow** (kubectl apply -f . --recursive), and full SELinux compliance in restricted environments. Demonstrates enterprise-grade K3s security and operational patterns.

### 6. ⚡ Lightweight K3s Cluster on RHEL9 with External PostgreSQL
**[Lightweight-K3s-Cluster-on-RHEL9-with-External-DB](https://github.com/dn0218/Lightweight-K3s-Cluster-on-RHEL9-with-External-DB)**
Production-hardened hybrid K3s cluster with external PostgreSQL datastore for control plane persistence. Maintains **SELinux (Enforcing)** and **Firewalld (Active)** throughout. Features Zabbix 7.0 monitoring stack deployed via Helm, Klipper ServiceLB for load balancing, and seamless RHEL 9/Rocky 10 cross-node communication.

### 7. 🤖 AutoStack-Monitor — Ansible-Powered WordPress HA Deployment
**[AutoStack-Monitor](https://github.com/dn0218/AutoStack-Monitor)**
Enterprise-grade **Ansible automation** solution enabling "one-click" fully automated deployment of a highly available WordPress container stack across RHEL/Rocky Linux 9 and Ubuntu 24.04. Highlights cross-distribution container orchestration using **Podman Quadlet** with rootless security, NFS-based distributed storage for persistence, and Zabbix/Grafana monitoring integration.

### 8. 📡 DRCOO — Distributed Rootless Container Orchestration & Observability
**[Distributed-Rootless-Container-Orchestration-Observability-DRCOO-](https://github.com/dn0218/Distributed-Rootless-Container-Orchestration-Observability-DRCOO-)**
Infrastructure-as-Code (IaC) project for enterprise-level container management. Leverages **Ansible**, **Podman Quadlet**, and **Prometheus/Grafana stack** to deploy a secure, rootless, and highly observable environment across RHEL 9 and Rocky Linux 10 nodes. Features automated SELinux labeling and one-click observability deployment.

*(Other projects including Linux Server Hardening Script、GlusterFS HA Storage for Oracle RMAN etc.，Focus on RHEL Practical project)*

---

## 🎓 Certifications (In Progress)
- 🔴 **RHCSA (Red Hat Certified System Administrator)**
- 🤖 Ansible Automation & K3s/Kubernetes (in progress)

---

## 📫 How to Reach Me
- **LinkedIn:** [linkedin.com/in/danny-hii-lu-hui-129938286](https://www.linkedin.com/in/danny-hii-lu-hui-129938286)
- **Email:** dn020218@gmail.com

---

**Always open to collaboration on RHEL, Podman, storage automation, or monitoring projects!** 🚀
