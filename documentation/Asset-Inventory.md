# Asset Inventory

## Overview

This asset inventory identifies, classifies, and documents the critical assets within the simulated VORTEX SECURE enterprise environment.

The inventory provides visibility into the organization's:

- Hardware infrastructure
- Software platforms
- Cloud infrastructure
- AI systems
- Information assets
- Network infrastructure
- Security infrastructure
- Identity infrastructure
- Backup and recovery infrastructure

The inventory supports cybersecurity risk management, security governance, control assessment, vulnerability management, and continuous security improvement.

The assessment is primarily aligned with the **NIST Cybersecurity Framework (CSF) 2.0**.

---

# Asset Classification

| Classification | Description |
|---|---|
| Critical | Assets whose compromise, destruction, or unavailability could cause severe business, security, legal, or operational consequences |
| High | Important assets that directly support business operations or security capabilities |
| Medium | Operational assets whose compromise could cause moderate business or operational impact |
| Low | Public or non-sensitive assets with limited impact if compromised |

Asset criticality should be periodically reassessed as the organization, technology environment, and business requirements evolve.

---

# Hardware Assets

| Asset | Description | Criticality |
|---|---|---|
| Domain Controllers | Enterprise identity and authentication infrastructure | Critical |
| Database Servers | Hosts critical business and customer databases | Critical |
| File Servers | Stores corporate files and internal information | High |
| SIEM Servers | Security monitoring and log-processing infrastructure | Critical |
| Backup Servers | Supports backup and recovery operations | Critical |
| Virtualization Cluster | Hosts enterprise virtual workloads | Critical |
| Git Servers | Hosts source code and development repositories | High |
| AI Compute Cluster | Provides computational resources for AI training and inference | Critical |
| GPU AI Servers | High-performance AI processing infrastructure | Critical |
| Enterprise Servers | Hosts internal enterprise services | High |
| Network Switches | Provides enterprise network connectivity | High |
| Routers | Provides internal and external network routing | High |
| NGFW Appliances | Provides perimeter network security | Critical |
| Load Balancers | Distributes traffic across enterprise services | High |
| Backup Storage Systems | Stores protected backup data | Critical |
| Employee Laptops | Corporate-managed employee endpoints | High |

---

# Software Assets

| Asset | Purpose | Criticality |
|---|---|---|
| Microsoft 365 | Enterprise productivity and collaboration | High |
| Microsoft Entra ID | Cloud identity and access management | Critical |
| Active Directory | Enterprise identity and authentication | Critical |
| GitHub Enterprise | Source code and repository management | Critical |
| Microsoft Sentinel | Security Information and Event Management (SIEM) | Critical |
| Microsoft Defender XDR | Extended Detection and Response | Critical |
| CrowdStrike Falcon | Endpoint Detection and Response | High |
| Docker | Containerization platform | High |
| Kubernetes | Container orchestration | High |
| Jira Software | Project and task management | Medium |
| Confluence | Internal documentation and knowledge management | Medium |
| Burp Suite Professional | Web application security testing | Medium |
| Wireshark | Network traffic analysis | Medium |

---

# Cloud Assets

VORTEX SECURE uses Microsoft Azure as a major cloud infrastructure platform.

| Asset | Description | Criticality |
|---|---|---|
| Microsoft Azure | Primary cloud infrastructure platform | Critical |
| Azure Virtual Machines | Hosts enterprise workloads | Critical |
| Azure Storage | Cloud storage infrastructure | High |
| Azure Key Vault | Secret and cryptographic key management | Critical |
| Azure Backup | Cloud backup and recovery capability | Critical |
| Azure Networking | Cloud networking infrastructure | High |
| Geo-Redundant Storage | Supports resilient backup and data availability | Critical |

### Cloud Regions

The simulated environment includes infrastructure distributed across:

- UK South
- UAE North
- East US

Geographic distribution supports resilience, business continuity, and international operations.

---

# AI Assets

AI represents a core business capability of VORTEX SECURE and therefore requires dedicated asset classification and protection.

| Asset | Description | Criticality |
|---|---|---|
| Foundation Models | Enterprise AI foundation models | Critical |
| Fine-Tuned Models | Organization-specific AI models | Critical |
| AI Agents | Autonomous or semi-autonomous AI systems | Critical |
| RAG Infrastructure | Retrieval-Augmented Generation environment | Critical |
| Training Datasets | Data used to train AI systems | Critical |
| Model Weights | Proprietary AI model parameters | Critical |
| AI APIs | Interfaces providing access to AI capabilities | High |
| AI Monitoring Systems | Security and performance monitoring of AI systems | High |
| AI Development Infrastructure | Systems used to develop and test AI systems | High |

AI assets are considered high-value intellectual property and are therefore subject to enhanced access control, monitoring, integrity validation, and security assessment.

---

# Information Assets

## Sensitive Information

VORTEX SECURE processes and maintains several categories of sensitive information, including:

- Personally Identifiable Information (PII)
- Sensitive Personal Information (SPII)
- Customer Financial Records
- Healthcare Records
- Employee Information
- Authentication Credentials
- Authentication Secrets
- Security Logs
- Incident Records
- AI Training Datasets
- Source Code
- Proprietary Technical Documentation

Sensitive information requires appropriate access controls, classification, encryption, monitoring, retention, and secure disposal.

---

# Intellectual Property Assets

The organization's intellectual property includes:

- AI Models
- Model Weights
- Training Datasets
- Proprietary Detection Algorithms
- Security Frameworks
- Security Playbooks
- Source Code
- Research Documentation
- Technical Designs
- Patents
- Company Trademarks
- Proprietary Security Technologies

These assets represent significant business value and require enhanced protection against unauthorized access, modification, disclosure, and theft.

---

# Identity and Access Assets

| Asset | Purpose | Criticality |
|---|---|---|
| Active Directory | Enterprise identity management | Critical |
| Microsoft Entra ID | Cloud identity management | Critical |
| Privileged Accounts | Administrative access | Critical |
| Service Accounts | Application and service authentication | High |
| MFA Infrastructure | Strong authentication | Critical |
| PAM Platform | Privileged access management | Critical |
| RBAC Configuration | Role-based authorization | High |

Identity infrastructure represents a critical security dependency because compromise of identity systems could provide attackers with broad access to enterprise resources.

---

# Network Assets

The enterprise network architecture includes:

- ISP 1
- ISP 2
- DDoS Protection
- Next-Generation Firewall (NGFW)
- Web Application Firewall (WAF)
- Load Balancers
- DMZ
- Internal Network
- Data Center Network
- Network Switches
- Routers
- VPN Infrastructure
- Network Access Control (NAC)
- IDS
- IPS
- Network Segmentation
- Secure DNS Infrastructure

The network architecture follows a layered defense model designed to reduce external exposure, limit lateral movement, and improve monitoring capabilities.

---

# Security Operations Assets

VORTEX SECURE maintains a dedicated security operations capability.

| Asset / Capability | Purpose | Criticality |
|---|---|---|
| SIEM | Centralized security monitoring and log analysis | Critical |
| SOAR | Security automation and response | High |
| Threat Intelligence | Threat intelligence collection and analysis | High |
| Threat Hunting | Proactive threat detection | High |
| Incident Response | Security incident handling | Critical |
| Digital Forensics | Investigation and evidence analysis | High |
| Case Management | Incident tracking and investigation management | High |
| EDR | Endpoint detection and response | Critical |
| XDR | Cross-domain threat detection | Critical |

---

# Backup and Recovery Assets

| Asset | Purpose | Criticality |
|---|---|---|
| Backup Servers | Central backup infrastructure | Critical |
| Backup Storage | Protected backup data | Critical |
| Azure Backup | Cloud backup capability | Critical |
| Geo-Redundant Storage | Geographic resilience | Critical |
| Disaster Recovery Infrastructure | Recovery of critical services | Critical |
| Business Continuity Systems | Supports continued business operations | High |

Backup and recovery infrastructure should be continuously tested to ensure that critical services and information can be restored following disruptive events.

---

# Security Control Infrastructure

Critical security technologies include:

- Zero Trust
- Multi-Factor Authentication (MFA)
- Endpoint Detection and Response (EDR)
- Extended Detection and Response (XDR)
- Network Access Control (NAC)
- Privileged Access Management (PAM)
- Role-Based Access Control (RBAC)
- Data Loss Prevention (DLP)
- Encryption
- Backup
- Intrusion Detection Systems (IDS)
- Intrusion Prevention Systems (IPS)
- Web Application Firewall (WAF)
- Next-Generation Firewall (NGFW)
- SIEM
- SOAR

These controls contribute to the protection, detection, response, and recovery capabilities of the enterprise environment.

---

# Asset Criticality

## Critical Assets

Critical assets include:

- Customer Database
- Domain Controllers
- Active Directory
- Microsoft Entra ID
- AI Models
- Model Weights
- AI Training Datasets
- AI Compute Cluster
- AI Agents
- RAG Infrastructure
- Microsoft Azure Infrastructure
- GitHub Enterprise
- Database Servers
- SIEM Infrastructure
- Backup Infrastructure
- Virtualization Cluster
- NGFW Infrastructure
- Identity Infrastructure
- Critical Intellectual Property

---

## High-Criticality Assets

High-criticality assets include:

- File Servers
- Employee Devices
- Internal Applications
- Network Infrastructure
- Load Balancers
- VPN Infrastructure
- Security Operations Platforms
- Cloud Workloads
- AI Development Infrastructure
- Security Monitoring Systems
- Backup Management Systems

---

## Medium-Criticality Assets

Medium-criticality assets include:

- Documentation Platforms
- Development Tools
- Internal Knowledge Bases
- Project Management Systems
- Security Testing Tools

---

## Low-Criticality Assets

Low-criticality assets may include:

- Public Website Content
- Marketing Materials
- Public Documentation
- Non-sensitive Public Information

---

# Asset Ownership

| Asset | Responsible Owner |
|---|---|
| Cloud Infrastructure | Cloud Infrastructure Manager |
| AI Systems | Head of AI Engineering |
| Customer Database | Database Administrator |
| Enterprise Network | Network Security Manager |
| GitHub Enterprise | DevSecOps Manager |
| SIEM Platform | SOC Manager |
| Employee Devices | IT Operations Manager |
| Identity Systems | Identity and Access Management Lead |
| Backup Infrastructure | Infrastructure Manager |
| Security Architecture | CISO / Security Architecture Team |
| Third-Party Security | Third-Party Risk Management Team |

Asset owners are responsible for ensuring that appropriate security requirements, access controls, monitoring, and risk-management activities are applied to the assets under their responsibility.

---

# Existing Security Controls

Critical assets are protected through layered security controls including:

- Multi-Factor Authentication (MFA)
- Role-Based Access Control (RBAC)
- Privileged Access Management (PAM)
- Encryption at Rest
- Encryption in Transit
- Data Loss Prevention (DLP)
- Microsoft Sentinel (SIEM)
- Endpoint Detection and Response (EDR)
- Extended Detection and Response (XDR)
- Network Segmentation
- Next-Generation Firewall (NGFW)
- Web Application Firewall (WAF)
- IDS / IPS
- Network Access Control (NAC)
- Patch Management
- Vulnerability Management
- Security Monitoring
- Threat Intelligence
- Threat Hunting
- Incident Response Playbooks
- Backup and Disaster Recovery
- Security Awareness Training
- AI Security Testing
- AI Monitoring
- Dataset Integrity Validation

---

# Asset Lifecycle Management

VORTEX SECURE should maintain asset lifecycle management throughout the entire asset lifecycle.

The lifecycle includes:

1. Asset identification
2. Asset registration
3. Ownership assignment
4. Classification
5. Security assessment
6. Deployment
7. Monitoring
8. Maintenance
9. Security review
10. Decommissioning
11. Secure disposal

Assets should be reassessed whenever significant changes occur.

---

# Continuous Asset Review

The asset inventory should not be considered static.

VORTEX SECURE should continuously review the inventory when:

- New systems are deployed
- New employees join
- New customers are onboarded
- New services are introduced
- New AI systems are developed
- Cloud infrastructure changes
- New third-party relationships are established
- Infrastructure is expanded
- New geographic locations are introduced
- Security incidents occur
- Major technology changes occur

Continuous asset visibility supports accurate risk assessment and improves the organization's ability to identify previously unknown or unmanaged assets.

---

# NIST CSF 2.0 Alignment

The asset inventory supports all six NIST CSF 2.0 Functions.

| NIST CSF 2.0 Function | Asset Inventory Contribution |
|---|---|
| Govern | Asset ownership, accountability, security governance |
| Identify | Asset discovery, classification, criticality, risk identification |
| Protect | Security controls applied to critical assets |
| Detect | Asset monitoring and security telemetry |
| Respond | Identification of affected assets during incidents |
| Recover | Identification of assets required for recovery and business continuity |

The **Identify** function is particularly important because accurate asset visibility provides the foundation for effective cybersecurity risk management.

---

# Asset Inventory Summary

The VORTEX SECURE enterprise environment contains a broad combination of on-premises infrastructure, cloud services, identity systems, security operations platforms, AI infrastructure, information assets, and network security technologies.

Critical assets include sensitive customer information, intellectual property, AI models and datasets, identity infrastructure, enterprise databases, cloud infrastructure, source-code repositories, security monitoring systems, and backup infrastructure.

These assets are protected through layered technical, administrative, and organizational controls.

However, asset security is a continuous process. Asset ownership, classification, criticality, exposure, and security requirements should be periodically reassessed as VORTEX SECURE grows and introduces new technologies, services, customers, employees, and AI capabilities.

The inventory therefore serves as a foundational component of the organization's cybersecurity risk management program and supports the continuous application of the **NIST Cybersecurity Framework (CSF) 2.0**.
