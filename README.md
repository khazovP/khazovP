# Hello, I'm Pavlo Khazov
<a href="https://linkedin.com/in/pavlo-khazov"><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

Greetings! I’m a cybersecurity analyst with 3 years of experience in 24x7 SOC environments. I’m passionate about cybersecurity and technology and I’m willing to continue my career. I am constantly learning new things - both theory and by working on hands-on projects, focusing on network securty. This portfolio showcases my work and contributions to the field of cybersecurity.

## Skills & Projects

| Project                                      | Skills                                         |
|----------------------------------------------|-----------------------------------------------|
| Sigma Command & Control Framework            | Programming, Red teaming, Scripting & Automation |
| Azure Mini SOC                   | Network Architecture, Cloud, Log Management, Firewall, EDR, SIEM, Troubleshooting, Problem Solving |

## Tools

<img src="https://img.shields.io/badge/-Microsoft_Azure-0089D6?&style=for-the-badge&logo=Microsoft-Azure&logoColor=white" /> <img src="https://img.shields.io/badge/-Palo_Alto_Networks-FF6F00?&style=for-the-badge&logo=Palo-Alto-Networks&logoColor=white" /> <img src="https://img.shields.io/badge/-Wazuh-EE0000?&style=for-the-badge&logo=Wazuh&logoColor=white" /> <img src="https://img.shields.io/badge/-Microsoft_Sentinel-0078D4?&style=for-the-badge&logo=Microsoft&logoColor=white" /> <img src="https://img.shields.io/badge/-Linux-FCC624?&style=for-the-badge&logo=Linux&logoColor=black" />

## 🚀 Projects  

## **Sigma C2 – Custom Command & Control Framework**  
Offensive security meets hands-on development. Sigma C2 is a custom-built Command & Control (C2) framework designed for red team operations. The goal? To dive into offensive security and pushing myself to learn coding fundamentals. 
Project implements: 
* C2 architecture
* Secure communication (TLS and DNS listeners)
* Automation
* Dynamic payload generation
* Data exfiltration
* Sandbox detection
* Remote command execution

🔗More details: [GitHub Repository](https://github.com/khazovP/Sigma-C2)

# Azure Mini SOC – Cybersecurity Lab in the Cloud

A cloud-based Mini Security Operations Center simulation designed for threat detection, monitoring and analysis within the Azure environment. This Mini SOC operates on a segmented network protected by enterprise-grade firewall, dedicated honeypot, target host with EDR agent, centralized EDR management server and log collector, controlled attack surface, integrated SIEM and Automation.

## Phase 1: Foundation

Established a robust security infrastructure serving as the foundation for advanced defensive operations:

- Implemented strategic network segmentation creating distinct security zones
- Deployed and configured Palo Alto firewall with granular traffic control policies
- Engineered seamless Azure networking architecture ensuring proper communication
- Overcame Azure networking challenges

This phase layed the foundation for deployment of advanced security monitoring capabilities.

**[Full Documentation →](https://github.com/khazovP/Mini-SOC-Phase1)**

## Phase 2: Logging & Visibility

Building upon the core infrastructure, this phase focused on log aggregation, threat visibility and security insights through Microsoft Sentinel SIEM:

- Implemented centralized log forwarding
- Integrated honeypot for real-time capture and analysis of SSH brute force attacks
- Developed parsing logic and Sentinel dashboards to visualize data

The Mini SOC now actively harvests threat and visualizes collected intelligence.

**[Full Documentation →](https://github.com/khazovP/Mini-SOC-Phase2)**

## Phase 3: Threat Detection & Automated Response

This phase elevated the environment with EDR and automated threat mitigation capabilities:

- Successfully deployed EDR Solution
- Implemented automated incident Response playbook for dynamic threat containment
- Developed correlation rules to extract real attacker's IP from multi-source logs
- Integrated automated threat blocking through firewall's API
- Resolved complex integration challenges across the security stack

The Mini SOC now functions as a completely autonomous defense system capable of detecting, analyzing, and neutralizing threats without human intervention.

**[Full Documentation →](https://github.com/khazovP/Mini-SOC-Phase3)**
