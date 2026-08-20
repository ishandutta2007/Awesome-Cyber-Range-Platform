# Awesome-Cyber-Range-Platform

Markdown
## Top Cyber Range Platforms Ecosystem


**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Cybersecurity Training, Cyber Ranges, SOC Simulation, Red/Blue Team Exercises, Attack Simulation & Cyber Readiness*  
**Last updated: August 2026**


This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Cyber Range Platforms**. These platforms provide realistic, hands-on environments for cybersecurity education, workforce development, SOC training, incident response, red-team/blue-team exercises, adversary emulation, cyber-defense exercises, CTFs, and organizational cyber-readiness assessments.


**Examples** include RangeForce, Immersive Labs, Cyberbit, AttackIQ Academy, Hack The Box Enterprise, TryHackMe Business, Blue Team Labs Online, SimSpace, CyberQ Group, and SafeBreach Academy.


Modern cyber ranges increasingly combine **virtualized infrastructure, cloud environments, vulnerable systems, SIEM/SOC tooling, attack simulation, threat emulation, MITRE ATT&CK mapping, automated scoring, instructor management, multiplayer exercises, purple teaming, and real-world enterprise technologies**.


**Open-source emphasis**: This repository is heavily expanded with open-source projects that can be used to construct self-hosted cyber ranges — including complete cyber-range platforms, orchestration engines, training environments, CTF platforms, vulnerable infrastructure, attack-defense labs, SOC simulation environments, adversary emulation frameworks, scoring systems, and infrastructure-as-code components.


The open-source ecosystem is particularly interesting because a cyber range is fundamentally a **composable infrastructure problem**. A complete platform can often be assembled from virtualization/cloud infrastructure, orchestration, vulnerable machines, attack tooling, defensive tooling, exercise content, and scoring components.


Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or GitHub repositories.


## Table of Contents


- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Additional Strong Open-Source Options](#additional-strong-open-source-options)
- [Open-Source Cyber Range Stack](#open-source-cyber-range-stack)
- [Cyber Range Building Blocks](#cyber-range-building-blocks)
- [Important Cyber Range Concepts](#important-cyber-range-concepts)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)


## SaaS/Hosted Platforms

| Platform | Description | Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- |
| **[RangeForce](https://www.rangeforce.com/)** | Enterprise cyber-readiness and hands-on training platform providing technical labs, team exercises, and cyber-defense readiness capabilities (part of Cyberbit). | Starting at ~$11,000–$12,000/year (enterprise contract benchmark; private offer on AWS Marketplace) | **Free Solo Labs:** Access to select introductory defensive modules and hands-on skill labs at no cost; 6-month RSAC member preview. |
| **[Cyberbit](https://www.cyberbit.com/)** | Enterprise cyber-range and SOC training platform focused on realistic team-based cyber-defense exercises, incident response, and operational readiness. | Starting at ~$7,200/year (~$1,200–$1,500/user/year, typically 5-seat minimum) | **Cyberbit Free Edition:** Access to select foundational solo hands-on labs and theory modules; 1 live team exercise via PoC evaluation. |
| **[Immersive Labs](https://www.immersivelabs.com/)** | Cyber workforce resilience platform providing hands-on technical exercises, threat simulations, and role-based learning paths. | Starting at ~$6,000–$10,000/year (Core tier for small teams, min 5 users) | **Cyber Million Program:** 100% free access for individuals (aged 16+) to foundational defensive security learning pathways and entry-level labs. |
| **[AttackIQ Academy](https://www.attackiq.com/)** | Security validation and adversary-emulation training ecosystem focused on MITRE ATT&CK, Purple Teaming, and Breach & Attack Simulation. | **Free ($0)** (100% free community initiative sponsored by AttackIQ) | **Free Forever:** Unlimited access to all on-demand courses, hands-on lab environments, credentials, digital badges, and (ISC)² CPE credits. |
| **[Hack The Box Enterprise](https://www.hackthebox.com/business)** | Enterprise cybersecurity training and skills-development platform providing guided learning, dedicated labs, realistic environments, and team management. | Starting at $250/seat/month ($2,500/seat/year billed annually, Build Tier) | **14-day Free Trial:** Up to 5 seats with access to Professional Labs, team management, and executive reporting features. |
| **[Hack The Box Academy for Business](https://academy.hackthebox.com/academy-for-business)** | Enterprise cybersecurity upskilling platform combining guided learning paths, interactive content, dedicated labs, and corporate training management. | Starting at $250/user/month ($2,500/user/year, Build Tier; individual modules unlockable via Cubes starting from $8/bundle) | **14-day Free Business Trial;** Individual free tier includes permanent access to Tier 0 foundational modules and guided materials. |
| **[TryHackMe Business](https://tryhackme.com/business/landing/overview)** | Enterprise hands-on cybersecurity training platform offering SOC simulations, threat-hunting exercises, tabletop exercises, and live-breach simulations. | Starting at $99/seat/month ($1,188/seat/year, min 5 seats; EDU licensing from $25/month) | **14-day Free Business Trial;** Individual Free tier includes 100+ free introductory rooms and 1 hour/day of browser-based AttackBox compute. |
| **[Blue Team Labs Online](https://blueteamlabs.online/)** | Hands-on defensive cybersecurity training platform focused on blue-team challenges, investigations, digital forensics, and incident response. | Starting at £15/month (~$19/month) or £144/year (~$185/year) for PRO tier (also offers 3-month at £40.50 and 6-month at £76.50) | **Free Forever Plan:** Limited to 10 hours of lab time per month, access to 15 active investigation labs, and standard downloadable challenges. |
| **[SimSpace](https://www.simspace.com/)** | Enterprise cyber-range platform for realistic cyber exercises, cyber-defense training, network digital twins, and operational readiness. | Starting at ~$25,000/year (modular subscription based on range fidelity, user seats, and training scenarios) | **Interactive PoC / Sandbox Demo:** Guided test environment access with customized scenario evaluation on request (no public self-serve tier). |
| **[CyberQ Group](https://www.cyberqgroup.com/)** | Cybersecurity training and simulation provider delivering cyber-range environments, exercises, and professional cybersecurity training. | Starting at ~$1,500–$3,000/exercise or ~$15,000/year (pay-as-you-use cloud model / tailored corporate packages) | **Guided Live Evaluation:** Single guided scenario simulation and risk-assessment demonstration upon consultation. |

Recommended Open-Source Combinations

Open-Source Cyber Range

CyberRangeCZ + OpenStack + Terraform + Ansible + Kali + Vulnerable VMs

This provides a strong foundation for creating repeatable, isolated cyber-training environments. CyberRangeCZ specifically supports dynamic sandbox provisioning and OpenStack/AWS infrastructure. (github.com
)

University Cybersecurity Training Range

CyberRangeCZ + CTFd + OWASP Juice Shop + WebGoat + Moodle

Use CyberRangeCZ for infrastructure, CTFd for scoring, vulnerable applications for hands-on exercises, and Moodle for curriculum management.

Enterprise SOC Training Range

CyberRangeCZ/Orion Range + Windows AD + Security Onion + Wazuh + Zeek + TheHive

Create realistic enterprise networks and simulate attacks while giving defenders access to SIEM, network telemetry, endpoint data, and incident-response tooling.

Red-vs-Blue Cyber Range

OpenStack/Proxmox + Caldera + Atomic Red Team + Security Onion + Wazuh + CTFd

Use Caldera and Atomic Red Team to generate adversary activity, then measure whether the defensive stack detects and responds to the activity.

Cloud Cyber Range

Terraform + AWS/Azure/GCP + CloudGoat + Stratus Red Team + Wazuh + OpenSearch

Create isolated cloud environments containing intentionally vulnerable configurations and realistic cloud attack scenarios.

Web Application Security Range

Docker + OWASP Juice Shop + WebGoat + DVWA + Burp Suite + CTFd

Useful for application-security education, penetration testing, secure coding, and CTF-style exercises.

Detection Engineering Range

Splunk Attack Range + Atomic Red Team + Sigma + Zeek + Suricata + Wazuh

Generate realistic attack telemetry, develop detections, and measure detection coverage against MITRE ATT&CK techniques.

Full Open-Source Cyber Range

CyberRangeCZ → OpenStack/Proxmox → Terraform/Ansible → Vulnerable Infrastructure → Caldera/Atomic Red Team → Security Onion/Wazuh → CTFd → Grafana/OpenSearch

This architecture can reproduce a substantial portion of the technical functionality associated with commercial cyber-range platforms while retaining control over the underlying infrastructure and exercise content.

Cyber Range Building Blocks
Infrastructure Layer

OpenStack — Private cloud infrastructure.

Proxmox VE — Virtualization and container platform.

KVM/QEMU — Open-source virtualization.

VMware-compatible environments — Enterprise virtualization environments.

Terraform — Infrastructure-as-code.

Ansible — Configuration automation.

Packer — Automated VM-image creation.

Vagrant — Reproducible virtual environments.

Kubernetes — Container orchestration.

Docker — Containerized exercise environments.

Range Orchestration Layer

CyberRangeCZ — Full cyber-range orchestration.

KYPO CRP — Legacy open-source cyber-range.

Orion Range — Lab-as-code orchestration.

Open Cyber Range — Self-hosted training platform.

AWS CyberRange — Cloud-based range blueprint.

Exercise Content Layer

CTFd — CTF management.

Mellivora — CTF platform.

RootTheBox — Gamified training.

picoCTF — Cybersecurity challenges.

OWASP Juice Shop — Web security.

WebGoat — Web security.

DVWA — Web vulnerability training.

Vulhub — Vulnerable containers.

VulnHub — Vulnerable machines.

Attack Layer

MITRE Caldera — Adversary emulation.

Atomic Red Team — Atomic ATT&CK tests.

Metasploit — Exploitation.

Sliver — Red-team operations.

Mythic — C2 and adversary emulation.

Impacket — Windows/network attack tooling.

BloodHound — Active Directory attack-path analysis.

Stratus Red Team — Cloud attack simulation.

CloudGoat — AWS security scenarios.

Defense Layer

Security Onion — SOC platform.

Wazuh — SIEM/XDR.

Zeek — Network security monitoring.

Suricata — IDS/IPS.

Snort — IDS/IPS.

Velociraptor — Endpoint investigation.

TheHive — Incident response.

Arkime — Network traffic analysis.

Intelligence Layer

MISP — Threat intelligence.

OpenCTI — CTI knowledge graph.

Sigma — Detection rules.

YARA — Malware detection.

OpenBAS — Breach-and-attack simulation.

Measurement Layer

CTFd — Challenge scoring.

Grafana — Dashboards.

Prometheus — Metrics.

OpenSearch — Search/analytics.

Kibana — Security visualization.

MITRE ATT&CK — Technique mapping.

Custom scoring engines — Exercise-specific performance metrics.

Important Cyber Range Concepts

Cyber Range — Controlled environment for realistic cybersecurity training, testing, and exercises.

Cyber Training Range — Cyber range specifically designed for workforce education.

Virtual Cyber Range — Cyber range built using virtualized infrastructure.

Cloud Cyber Range — Cyber range hosted on cloud infrastructure.

Hybrid Cyber Range — Combination of physical, virtual, and cloud infrastructure.

Physical Cyber Range — Range containing physical networking and computing equipment.

Cyber Range-as-a-Service — Hosted cyber-range environment.

Range Orchestration — Automated creation and management of range environments.

Range Automation — Automated provisioning and configuration of exercises.

Lab-as-Code — Defining training environments as code.

Infrastructure-as-Code — Programmatic infrastructure provisioning.

Scenario-as-Code — Programmatic definition of cyber scenarios.

Exercise-as-Code — Reproducible definition of complete exercises.

Cyber Digital Twin — Digital representation of an organization's technology environment.

Network Digital Twin — Simulated representation of an enterprise network.

Enterprise Network Simulation — Reproduction of enterprise network architecture.

Network Emulation — Reproduction of network behavior.

System Emulation — Simulation of computing environments.

Sandbox — Isolated environment for executing potentially dangerous activity.

Training Sandbox — Isolated environment for hands-on learning.

Scenario — Defined sequence of cyber events and objectives.

Exercise — Structured cybersecurity activity with objectives and evaluation.

Inject — Event introduced into an exercise to test participant response.

Exercise Control — Management of exercise activities.

White Team — Team responsible for exercise administration and control.

Red Team — Offensive team simulating attackers.

Blue Team — Defensive team protecting the environment.

Purple Team — Team coordinating offensive and defensive activities.

Green Team — Team responsible for range infrastructure and environment management.

Gold Team — Leadership/evaluation team in some exercise structures.

Adversary Emulation — Reproducing attacker behavior.

Attack Simulation — Simulating cyberattacks.

Breach Simulation — Simulating compromise and attacker activity.

Breach-and-Attack Simulation (BAS) — Automated validation of security controls.

Threat Emulation — Reproduction of realistic threats.

Threat Simulation — Controlled simulation of threat activity.

Attack Path Simulation — Simulation of multi-step attacker movement.

Lateral Movement Simulation — Simulation of attacker movement between systems.

Privilege Escalation Simulation — Simulation of gaining higher privileges.

Credential Attack Simulation — Simulation of credential compromise.

Phishing Simulation — Controlled simulation of phishing attacks.

Malware Simulation — Safe simulation of malware behavior.

Ransomware Simulation — Controlled ransomware exercise.

DDoS Simulation — Controlled denial-of-service exercise.

Cloud Attack Simulation — Simulation of attacks against cloud environments.

Container Attack Simulation — Simulation of attacks against containers.

Kubernetes Security Exercise — Hands-on Kubernetes attack-defense training.

Active Directory Exercise — Enterprise identity-security training.

OT/ICS Cyber Range — Range designed around operational technology.

IoT Cyber Range — Range focused on connected devices.

Web Security Lab — Environment for application-security training.

Mobile Security Lab — Environment for mobile security training.

API Security Lab — Environment for API security exercises.

Cloud Security Lab — Environment for cloud-security exercises.

SOC Simulator — Environment reproducing security operations.

SOC Training — Hands-on security operations training.

Threat Hunting Lab — Environment for threat-hunting exercises.

Incident Response Lab — Environment for incident-response practice.

Digital Forensics Lab — Environment for forensic investigation.

Malware Analysis Lab — Isolated malware-analysis environment.

Detection Engineering Lab — Environment for building and testing detections.

CTF — Capture The Flag cybersecurity competition.

Jeopardy CTF — Challenge-based CTF format.

Attack-Defense CTF — Competition combining offense and defense.

King of the Hill — Competition involving control of systems.

Gamification — Game mechanics applied to cybersecurity training.

Flag — Evidence of completing a cybersecurity challenge.

Scoring Engine — System calculating exercise performance.

Leaderboard — Ranking participants or teams.

Skill Assessment — Measurement of technical cybersecurity capability.

Skills Matrix — Mapping skills across individuals or teams.

Competency Mapping — Mapping exercises to required competencies.

Role-Based Training — Training tailored to specific cybersecurity roles.

Adaptive Learning — Training paths that change based on performance.

Personalized Learning — Individualized cybersecurity training.

Learning Path — Structured sequence of cybersecurity exercises.

Exercise Library — Collection of reusable scenarios.

Scenario Library — Collection of attack-defense scenarios.

Challenge Library — Collection of hands-on challenges.

Scenario Generator — Tool for automatically generating exercises.

Dynamic Provisioning — Automatically creating environments when needed.

On-Demand Labs — Labs created when users request them.

Ephemeral Labs — Temporary training environments.

Persistent Labs — Long-running training environments.

Environment Reset — Restoring an environment to its baseline state.

Snapshot Reset — Restoring VMs from snapshots.

Golden Image — Standardized base VM image.

Baseline Environment — Known-good initial state.

Environment Drift — Changes from the original environment state.

Multi-Tenant Range — Cyber range supporting multiple organizations or groups.

Multi-User Range — Range supporting concurrent participants.

Multiplayer Exercise — Collaborative exercise involving multiple participants.

Team Exercise — Training exercise performed by a team.

Collaborative Cyber Defense — Joint defensive activity.

Remote Cyber Range — Range accessible remotely.

Browser-Based Cyber Range — Range accessed through a browser.

Attack Box — Preconfigured environment used by a trainee to conduct exercises.

Jump Host — Controlled access system into a training network.

Bastion Host — Secure entry point into an environment.

Network Segmentation — Isolating portions of the training environment.

Air-Gapped Range — Range isolated from external networks.

Internet-Isolated Range — Range without direct Internet access.

Controlled Egress — Restricted outbound connectivity.

Range Firewall — Firewall controlling range traffic.

Traffic Generator — Generates realistic network traffic.

User Simulator — Simulates users and business activity.

Synthetic Data — Artificial data used in exercises.

Synthetic Users — Artificial users for realistic scenarios.

Synthetic Enterprise — Artificial enterprise environment.

Enterprise Emulation — Reproduction of enterprise technology stacks.

Digital Twin Range — Cyber range representing a real organization.

Live-Fire Exercise — Realistic exercise involving live systems or tools.

Tabletop Exercise — Discussion-based incident-response exercise.

Functional Exercise — Exercise testing specific organizational functions.

Full-Scale Exercise — Comprehensive operational cyber exercise.

Cyber Drill — Short, focused cyber exercise.

Cyber Defense Exercise (CDX) — Exercise centered on defensive capabilities.

Red Team Exercise — Offensive security exercise.

Blue Team Exercise — Defensive security exercise.

Purple Team Exercise — Coordinated offense-defense exercise.

Threat Hunting Exercise — Exercise focused on finding adversaries.

Incident Response Exercise — Exercise focused on responding to incidents.

Crisis Simulation — High-level organizational cyber crisis exercise.

Cyber Readiness — Organization's ability to respond effectively to cyber threats.

Operational Readiness — Ability of teams and technology to perform under realistic conditions.

Cyber Resilience — Ability to withstand and recover from cyberattacks.

SOC Maturity — Maturity of security operations capabilities.

Detection Coverage — Portion of attack techniques detectable by defenses.

MITRE ATT&CK Coverage — Mapping defensive capabilities to ATT&CK techniques.

Detection Rate — Percentage of simulated attacks detected.

False Positive Rate — Rate of incorrectly triggered detections.

Mean Time to Detect (MTTD) — Average time required to detect an attack.

Mean Time to Respond (MTTR) — Average time required to respond to an incident.

Mean Time to Contain (MTTC) — Average time required to contain an incident.

Response Quality — Quality of defensive response.

Analyst Performance — Measurement of SOC analyst performance.

Team Performance — Measurement of team-level cyber performance.

Cyber Skills Gap — Difference between required and available cybersecurity skills.

Skills Validation — Demonstrating practical cybersecurity capabilities.

Hands-On Training — Learning through practical exercises.

Experiential Learning — Learning through realistic experiences.

Cyber Muscle Memory — Repeated practice of incident-response actions.

Readiness Assessment — Evaluation of cyber operational readiness.

Security Control Validation — Testing whether security controls work as expected.

Detection Validation — Testing whether detections identify attacks.

Control Effectiveness — Measurement of security-control performance.

Purple Teaming — Collaborative testing between attackers and defenders.

Continuous Validation — Repeated automated security testing.

Continuous Threat Exposure Management — Continuous identification and validation of exposure.

Attack Surface Simulation — Simulation of attacks against exposed assets.

Adversary Simulation — Controlled reproduction of adversary behavior.

ATT&CK Mapping — Mapping activity to MITRE ATT&CK.

TTP Simulation — Simulation of tactics, techniques, and procedures.

Cyber Exercise Automation — Automated creation and execution of exercises.

Exercise Orchestration — Coordinating multiple systems during an exercise.

Range Telemetry — Data generated by the cyber range.

Exercise Telemetry — Data generated during exercises.

Security Telemetry — Logs and signals from security infrastructure.

PCAP Replay — Replaying captured network traffic.

Attack Replay — Reproducing historical attacks.

Incident Replay — Reconstructing previous incidents.

Scenario Replay — Re-running an exercise.

After-Action Review — Review performed after an exercise.

After-Action Report — Formal exercise results report.

Exercise Analytics — Analysis of participant performance.

Performance Dashboard — Visualization of exercise metrics.

Executive Cyber Dashboard — Management-level cyber-readiness dashboard.

Cyber Readiness Score — Aggregate measure of cyber readiness.

Security Validation Score — Measure of defensive effectiveness.

Exercise Fidelity — Realism of a cyber-range environment.

Simulation Fidelity — Accuracy of simulated systems and behavior.

Operational Realism — Similarity to real-world operating conditions.

Scenario Realism — Realism of attack and defense scenarios.

Environment Realism — Realism of the underlying infrastructure.

Enterprise Tool Integration — Integration with real enterprise security products.

SIEM Integration — Integration with security-information platforms.

EDR Integration — Integration with endpoint detection systems.

SOAR Integration — Integration with security orchestration systems.

Firewall Integration — Integration with network-security controls.

Identity Integration — Integration with enterprise identity infrastructure.

Cloud Integration — Integration with cloud environments.

Security Toolchain Simulation — Reproduction of enterprise security tooling.

Cyber Range Interoperability — Ability to integrate multiple range technologies.

Range Federation — Connecting multiple cyber ranges.

Distributed Cyber Range — Cyber range distributed across locations.

National Cyber Range — Large-scale range for national cyber exercises.

Academic Cyber Range — Range designed for universities and education.

Government Cyber Range — Range designed for government training and exercises.

Enterprise Cyber Range — Range designed for organizational training.

Military Cyber Range — Range designed for military cyber operations.

Research Cyber Range — Range designed for cybersecurity research.

Cybersecurity Workforce Development — Training and developing cybersecurity professionals.

Cyber Talent Development — Developing cybersecurity skills.

Cyber Workforce Readiness — Measuring workforce readiness.

Continuous Cyber Training — Ongoing practical cybersecurity training.

Cyber Range Platform — Software infrastructure for operating cyber ranges.

Cyber Range Management Platform — Administrative layer for managing cyber ranges.

Cyber Range Orchestrator — Software for automatically creating and controlling ranges.

Cyber Range Engine — Core runtime infrastructure for cyber-range environments.

Cyber Range Portal — User interface for accessing exercises.

Cyber Range Marketplace — Catalog of reusable training environments and exercises.

Cyber Range-as-Code — Complete cyber ranges represented programmatically.

Open-Source Cyber Range — Cyber range built primarily using open-source technologies.

Self-Hosted Cyber Range — Cyber range operated on privately controlled infrastructure.

Composable Cyber Range — Range assembled from independent infrastructure and security components.

Cyber Range Stack — Full collection of technologies required to operate a cyber range.

Cyber Range Infrastructure — Compute, network, storage, and virtualization infrastructure.

Cyber Range Content — Training scenarios, challenges, and exercises.

Cyber Range Automation — Automation of provisioning and exercise execution.

Cyber Range Analytics — Measurement of exercise and participant performance.

Cyber Range AI — AI used to generate scenarios, emulate users, or adapt exercises.

AI-Driven Cyber Range — Cyber range incorporating AI-driven simulation and training.

Adaptive Cyber Range — Range that dynamically changes based on participant behavior.

Autonomous Cyber Range — Range capable of automatically generating or adapting scenarios.

Agentic Cyber Range — Cyber range using AI agents to simulate attackers, defenders, users, or infrastructure.

AI Adversary Emulation — AI-driven simulation of attacker behavior.

AI SOC Simulation — AI-driven simulation of security operations.

Autonomous Red Teaming — Automated offensive security testing.

Autonomous Blue Teaming — Automated defensive response.

AI-Generated Scenarios — Automatically generated cybersecurity exercises.

AI Exercise Instructor — AI assistant supporting cybersecurity training.

AI Cyber Coach — AI-driven personalized cybersecurity instructor.

AI-Assisted Threat Hunting — AI assistance for identifying threats.

AI-Assisted Incident Response — AI assistance for responding to incidents.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow the existing format).

Include: name, official link or GitHub repository, 1–2 sentence description, and whether it is SaaS/hosted or open-source.

For open-source projects, identify the primary capability — cyber-range orchestration, CTF, vulnerable infrastructure, attack simulation, SOC simulation, detection engineering, threat intelligence, or infrastructure.

Clearly distinguish OSI-approved open source, source-available, open-core, and commercial hosted projects.

Verify the current license before adding an open-source entry.

Prefer actively maintained repositories with meaningful documentation and recent development.

Avoid describing a security tool as a complete cyber-range platform unless it actually provides range infrastructure, orchestration, or training capabilities.

Submit a PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

Commercial cyber-range platforms frequently combine infrastructure orchestration, training content, attack simulation, defensive tooling, scoring, analytics, and enterprise integrations.

The open-source ecosystem is considerably more fragmented and generally requires combining multiple projects.

A penetration-testing tool, vulnerable VM, SIEM, or CTF platform is not necessarily a complete cyber-range platform, but may be an important component of one.

Some projects may have multiple components or licensing models. Always verify the current license for the specific repository/component before deployment.

Cyber ranges should be isolated from production infrastructure unless the exercise is explicitly designed and authorized to test production systems.

Offensive-security tools should only be used against systems and environments for which you have explicit authorization.

Self-hosted cyber ranges require appropriate network isolation, access controls, monitoring, backups, resource management, and security hardening.

Vulnerable machines and intentionally insecure applications should never be exposed directly to the public Internet.

Cloud-based cyber ranges can incur significant infrastructure costs; use appropriate quotas, budgets, and automatic shutdown policies.

Training scenarios should be designed to prevent accidental impact to external systems or unauthorized targets.

Made for cybersecurity professionals, SOC teams, red teams, blue teams, purple teams, security engineers, CISOs, universities, government organizations, military cyber teams, researchers, and cybersecurity educators.
Let's make cyber-range training more open, realistic, reproducible, automated, scalable, and accessible.
