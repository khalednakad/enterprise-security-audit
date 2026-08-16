# Audit Scope

## VORTEX SECURE Security Audit

**Assessment Type:** Enterprise Security Audit  
**Assessment Environment:** Simulated Enterprise Environment  
**Primary Assessment Framework:** NIST Cybersecurity Framework (CSF) 2.0

---

## Audit Objectives

The primary objective of this security audit is to evaluate the current cybersecurity posture and security maturity of VORTEX SECURE by identifying security risks, vulnerabilities, control weaknesses, and compliance considerations across the organization's critical assets.

The assessment aims to provide actionable recommendations that:

- Strengthen existing security controls
- Reduce cybersecurity risk
- Improve regulatory and legal compliance
- Protect critical business and customer information
- Improve security monitoring and incident response capabilities
- Strengthen AI security
- Support continuous security improvement
- Maintain an appropriate level of security maturity as the organization grows

The assessment follows a risk-based approach and uses the **NIST Cybersecurity Framework (CSF) 2.0** as the primary framework for organizing the assessment.

---

## Scope of Assessment

This security assessment covers VORTEX SECURE's enterprise technology and cybersecurity environment, including:

- Corporate infrastructure
- Internal network architecture
- Cloud infrastructure
- Identity and access management
- Security operations
- Endpoint security
- Web applications and APIs
- Data protection
- AI engineering and AI infrastructure
- Security monitoring
- Incident response
- Governance and compliance
- Third-party security considerations

The assessment considers both internal and external attack surfaces from an architectural, risk, and control perspective.

The assessment is intended to evaluate the organization's security posture and control effectiveness within the defined simulated environment. It is not a destructive penetration test against production systems.

---

## In-Scope Assets

The assessment includes the following assets and technologies.

### Identity and Access Infrastructure

- Active Directory
- Domain Controllers
- Microsoft Entra ID
- Authentication Systems
- Multi-Factor Authentication (MFA)
- Role-Based Access Control (RBAC)
- Privileged Access Management (PAM)
- Network Access Control (NAC)

### Enterprise Infrastructure

- File Servers
- Database Servers
- Backup Servers
- SIEM Servers
- Git Servers
- Virtualization Cluster
- Internal enterprise servers
- Data center infrastructure

### Cloud Infrastructure

- Microsoft Azure Cloud Environment
- Azure Virtual Machines
- Azure Storage
- Azure Key Management
- Azure Backup
- Cloud Identity and Access Management
- Cloud Logging and Monitoring

### Business and Collaboration Platforms

- Microsoft 365
- GitHub Enterprise
- Internal business applications
- Collaboration platforms
- Business-critical services

### Web and Application Infrastructure

- Public-facing Web Applications
- Internal Web Applications
- APIs
- Web Application Firewall (WAF)
- Load Balancers
- Application infrastructure

### Network Security Infrastructure

- ISP connectivity
- DDoS Protection
- Next-Generation Firewalls (NGFWs)
- Web Application Firewall (WAF)
- IDS/IPS
- VPN Infrastructure
- Network Segmentation
- DMZ
- Internal Network
- Data Center Network

### Security Operations

- Security Information and Event Management (SIEM)
- Security Orchestration, Automation and Response (SOAR)
- Threat Intelligence
- Threat Hunting
- Security Monitoring
- Incident Response
- Digital Forensics
- Case Management
- Security Logging and Alerting

### Endpoint Security

- Corporate Employee Endpoints
- Endpoint Detection and Response (EDR)
- Extended Detection and Response (XDR)
- Endpoint Monitoring
- Endpoint Protection
- Patch Management

### Data and Information Assets

- Customer Database
- Customer Data
- Employee Information
- Personally Identifiable Information (PII)
- Sensitive Personally Identifiable Information (SPII)
- Intellectual Property
- Source Code
- Security Logs
- Business-Critical Information
- Backup Data

### Artificial Intelligence Assets

- AI Compute Cluster
- Foundation Models
- Fine-Tuned Models
- AI Agents
- Retrieval-Augmented Generation (RAG) Infrastructure
- AI Training Datasets
- Model Weights
- AI-Related Intellectual Property

AI-specific risks considered within the scope include:

- Training Data Poisoning
- Unauthorized Model Access
- Sensitive Data Exposure
- Model Manipulation
- AI Agent Abuse
- RAG Data Exposure
- AI Supply-Chain Risks
- Model Integrity Risks

---

## Out-of-Scope Assets and Activities

The following assets and activities are excluded from the direct assessment scope:

- Customer-owned systems
- Customer-owned endpoints
- Personal employee devices (BYOD)
- Third-party managed infrastructure outside VORTEX SECURE's administrative control
- External partner networks outside the organization's assessment authority
- Physical security controls
- Destructive or disruptive testing against production systems
- Activities that could intentionally cause service interruption
- Systems for which VORTEX SECURE does not have appropriate authorization to assess

Third-party services may still be evaluated from a **third-party risk management perspective** when they interact with VORTEX SECURE systems, applications, infrastructure, or sensitive information.

---

## Audit Methodology

The assessment follows a structured, risk-based security auditing methodology consisting of:

1. Documentation Review
2. Organizational and Business Context Review
3. Asset Identification and Classification
4. Security Architecture Review
5. Security Configuration Review
6. Identity and Access Management Review
7. Network Security Review
8. Data Protection Review
9. AI Security Assessment
10. Security Control Assessment
11. Threat Identification
12. Vulnerability and Weakness Identification
13. Risk Assessment
14. Compliance and Regulatory Considerations
15. Security Monitoring Review
16. Incident Response and Recovery Review
17. Findings Validation
18. Security Recommendations
19. Final Reporting

The assessment may include review and validation of documented controls and security capabilities within the simulated environment.

The methodology does not represent a live penetration test or destructive security testing against a real production organization.

---

## Risk Assessment Methodology

The assessment uses a risk-based approach to prioritize identified cybersecurity risks.

Risk is evaluated using:

**Risk = Likelihood × Impact**

Likelihood and Impact are assessed using defined qualitative levels to support consistent prioritization.

Risk evaluation considers factors including:

- Threat likelihood
- Vulnerabilities and weaknesses
- Existing security controls
- Asset criticality
- Data sensitivity
- Business impact
- Operational impact
- Regulatory and legal impact
- Financial impact
- Reputational impact

Risk is considered dynamic and should be reassessed continuously as the organization's technology, employees, customers, services, threats, and regulatory obligations change.

---

## Security Control Assessment

The assessment evaluates whether existing security controls are capable of:

- Preventing unauthorized access
- Reducing attack surface
- Protecting sensitive information
- Detecting suspicious activity
- Containing security incidents
- Supporting investigation and forensics
- Supporting incident response
- Supporting recovery
- Reducing business impact
- Maintaining compliance
- Supporting continuous security improvement

Security controls considered include:

- Zero Trust
- MFA
- RBAC
- PAM
- NAC
- EDR
- XDR
- DLP
- Encryption
- Key Management
- Backup
- NGFW
- WAF
- IDS
- IPS
- Network Segmentation
- SIEM
- SOAR
- Threat Intelligence
- Threat Hunting
- Incident Response
- Security Awareness
- Patch Management

---

## Assessment Standards and Frameworks

### Primary Assessment Framework

#### NIST Cybersecurity Framework (CSF) 2.0

NIST CSF 2.0 is the **primary framework** used throughout this security assessment.

The assessment is aligned with the six NIST CSF 2.0 Functions:

- **Govern**
- **Identify**
- **Protect**
- **Detect**
- **Respond**
- **Recover**

NIST CSF 2.0 provides the primary structure for evaluating cybersecurity governance, risk management, asset management, protective controls, detection capabilities, incident response, and recovery.

### Supporting References

The following recognized frameworks and standards are used as supporting references where relevant:

- **NIST Artificial Intelligence Risk Management Framework (AI RMF) 1.0**
- **NIST AI RMF Playbook**
- **ISO/IEC 27001:2022**

These supporting references complement the NIST CSF 2.0 assessment and are not presented as separate primary assessment frameworks.

#### NIST AI RMF

The NIST AI RMF supports the assessment of AI-related risks associated with:

- Training datasets
- Foundation models
- Fine-tuned models
- AI agents
- RAG systems
- AI infrastructure
- Model integrity
- AI security and governance

#### ISO/IEC 27001:2022

ISO/IEC 27001:2022 is used as a supporting reference for:

- Information security governance
- Risk management
- Security controls
- Organizational responsibilities
- Information protection
- Continual improvement

---

## NIST CSF 2.0 Alignment

The audit activities are aligned with the six NIST CSF 2.0 Functions as follows:

| NIST CSF 2.0 Function | Assessment Focus |
|---|---|
| Govern | Governance, policies, risk strategy, legal and regulatory considerations, third-party risk |
| Identify | Asset management, business context, threats, vulnerabilities, and cybersecurity risk |
| Protect | Identity, access control, data protection, security safeguards, and security awareness |
| Detect | Security monitoring, SIEM, EDR/XDR, threat intelligence, and threat hunting |
| Respond | Incident response, containment, investigation, communication, and escalation |
| Recover | Backup, recovery, resilience, restoration, and continuous improvement |

---

## Security Architecture Scope

The enterprise network architecture considered by the assessment follows a layered security model:

```text
Internet
    ↓
ISP 1 + ISP 2
    ↓
DDoS Protection
    ↓
NGFW
    ↓
WAF / IDS-IPS
    ↓
Load Balancer
    ↓
DMZ / External Services
    ↓
Internal Network
    ↓
Data Center
```
The architecture also considers:

Network Segmentation
Zero Trust principles
Identity and Access Management
Endpoint Security
Security Operations
Cloud Security
AI Security Infrastructure
Data Protection
Backup and Recovery

The diagram represents a logical security architecture and does not necessarily represent every physical traffic path or deployment configuration.

Governance and Compliance Scope

The assessment considers the organization's ability to maintain appropriate security and compliance as it grows.

This includes:

Security governance
Security policies
Risk management
Continuous auditing
Regulatory requirements
Legal requirements
Third-party risk
Employee security responsibilities
Security awareness
Security training
Security improvement processes

Particular attention is given to the organization's ability to adapt its security maturity as:

Employee numbers increase
Customer numbers increase
Services expand
New technologies are introduced
AI capabilities evolve
Operations expand into additional countries
Regulatory requirements change
Continuous Security Assessment

Cybersecurity risk is not considered static.

The organization should continuously reassess:

New vulnerabilities
Emerging threats
New attack techniques
New technologies
New AI capabilities
New employees
New customers
New services
New third-party relationships
New geographic markets
New legal and regulatory requirements

Continuous auditing, monitoring, training, remediation, and improvement are therefore considered essential components of the organization's long-term security strategy.

Audit Deliverables

The assessment produces the following primary deliverables:

Asset Inventory
Risk Assessment
Security Controls Assessment
Audit Findings
Security Recommendations
Audit Conclusion
Security Architecture Overview
Enterprise Network Diagram
Final Audit Report

Supporting project documentation and visual assets are maintained within the appropriate repository directories.

Assessment Limitations

This assessment is based on the defined simulated VORTEX SECURE enterprise environment and the assumptions documented throughout the project.

The assessment does not constitute:

A legal compliance certification
An ISO/IEC 27001 certification
A formal NIST certification
A production penetration test
A guarantee that all vulnerabilities have been identified
A guarantee that cybersecurity risk has been eliminated

The assessment provides a structured evaluation of the simulated organization's cybersecurity posture, security controls, risks, and improvement opportunities.

Assessment Disclaimer

VORTEX SECURE is a simulated enterprise environment created for portfolio and educational purposes.

The findings, controls, risks, architecture, assets, and organizational characteristics documented throughout this project represent the assumptions and assessment results of the simulated case study.

They should not be interpreted as evidence of a real-world security audit, certification, regulatory approval, or penetration test.

The project demonstrates the practical application of cybersecurity audit and risk assessment principles using NIST Cybersecurity Framework (CSF) 2.0 as its primary assessment framework.
