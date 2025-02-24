# Hello, I'm Pavlo Khazov
<a href="https://linkedin.com/in/pavlo-khazov"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

Greetings! I’m a cybersecurity analyst with 3 years of experience in 24x7 SOC environments. I’m passionate about cybersecurity and technology and I’m willing to continue my career after participating in war in Ukraine. I am constantly learning new things by working on hands-on projects, focusing on threat detection, security automation, and incident response. This portfolio showcases my work and contributions to the field of cybersecurity.

## Skills & Projects

| Project                                      | Skills                                         |
|----------------------------------------------|-----------------------------------------------|
| Sigma C2                                    | Command & Control (C2) Development, Red teaming, Scripting & Automation |
| Azure Mini SOC                              | Network Architecture and Security, Firewall Configuration, Cloud Security |

## Tools

<img src="https://img.shields.io/badge/-Microsoft_Azure-0089D6?&style=for-the-badge&logo=Microsoft-Azure&logoColor=white" />
<img src="https://img.shields.io/badge/-Palo_Alto_Networks-FF6F00?&style=for-the-badge&logo=Palo-Alto-Networks&logoColor=white" />
<img src="https://img.shields.io/badge/-Wazuh-EE0000?&style=for-the-badge&logo=Wazuh&logoColor=white" />
<img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" />
<img src="https://img.shields.io/badge/-Linux-FCC624?&style=for-the-badge&logo=Linux&logoColor=black" />

## 🚀 Projects  

### **Sigma C2 – Custom Command & Control Framework**  
**Offensive security meets hands-on development.** Sigma C2 is a custom-built **Command & Control (C2) framework** designed for **red team operations**. The goal? To dive into **offensive security** and pushing myself to learn coding fundamentals. 
Project implements: 
* C2 architecture
* Secure communication
* Automation
* Payload generation
* Remote command execution

🔗**More details:** [GitHub Repository](https://github.com/khazovP/Sigma-C2)

### **Azure Mini SOC – Cybersecurity Lab in the Cloud**  
A **cloud-based Security Operations Center (SOC) simulation** for **threat detection, monitoring, and analysis** in Azure. The **Mini SOC** is built on a **segmented, firewall-protected network** featuring a **Palo Alto firewall, honeypot, target host with EDR, EDR server, attacker machine, and SIEM**.  

#### **Phase 1: Laying the Foundation**  
The first step was to **build a secure and scalable network** to serve as the backbone for future cybersecurity operations:  
✅ **Network segmentation** to isolate security zones.  
✅ **Palo Alto firewall integration** for traffic control, policies, and routing.  
✅ **Seamless Azure networking** to ensure proper communication between components.  

This phase **set the stage for advanced security monitoring** in later phases.  
🔗**Detailed documentation:** [GitHub Repository](https://github.com/khazovP/Mini-SOC)  

#### **Phase 2: Threat Detection & SIEM Integration**  
With the foundation in place, the focus shifted to **log collection, threat visibility, and security insights** through **Microsoft Sentinel SIEM**:  
🔥 **Log Collector deployment** to centralize logs from the **firewall and Cowrie honeypot**.  
🔥 **Firewall log forwarding in CEF format** for structured event ingestion.  
🔥 **Honeypot attack capture** – tracking SSH brute force attempts in real time.  
🔥 **Custom log parsing & Sentinel dashboards** for actionable threat intelligence.  
🔥 **Azure troubleshooting deep dive**, solving NAT/SNAT challenges and ingress/egress quirks.  

Now, the **Mini SOC** is actively **detecting threats, correlating attack data, and visualizing insights** with **custom security dashboards**.  
🔗**Detailed documentation:** [GitHub Repository](https://github.com/khazovP/Mini-SOC-Phase2)  
