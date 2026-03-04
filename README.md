# ISO/IEC 27001:2022 ISMS Implementation Portfolio  
## Fintech Governance & Risk Case Study

---

## Executive Governance Overview

# ISO/IEC 27001:2022 Information Security Management System (ISMS) Portfolio  

## Executive Overview  

This repository presents a structured ISO/IEC 27001:2022-aligned Information Security Management System (ISMS) designed for a digital wallet organisation (XY Innovate).  

The project demonstrates the design and documentation of a risk-based governance framework tailored to a financial technology environment handling sensitive customer data, financial transactions, and cloud-hosted infrastructure.  

The ISMS was developed in accordance with ISO/IEC 27001 requirements, integrating:  

- Organisational context and defined scope  
- Structured risk assessment and treatment methodology  
- Statement of Applicability (SoA) with control justification  
- Operational security policies (remote access, incident response)  
- GDPR-aligned data breach governance procedures  
- Formal access control lifecycle management  
- Continuous improvement integration via the PDCA model  

The objective of this portfolio is to demonstrate applied understanding of ISO 27001 governance principles, regulatory alignment, and operational control implementation within a realistic fintech context.  

This repository reflects structured ISMS design, risk-based decision-making, and audit-aware documentation practice at postgraduate level.

---

## Organisational Context & ISMS Scope Architecture  
**(Reference: scope.pdf)**

The document `scope.pdf` formally defines the boundaries, applicability, and structural intent of the ISMS in accordance with Clause 4 of ISO/IEC 27001:2022.

This section establishes the governance foundation upon which all subsequent risk assessment, control selection, and policy development activities are based.

---

### 1. Organisational Context (Clause 4.1)

XY Innovate operates within the fintech sector, delivering digital wallet services that process sensitive financial transactions and customer personally identifiable information (PII).

The organisational context influencing the ISMS includes:

- Regulatory obligations (GDPR and financial data protection requirements)
- Exposure to cyber threats targeting digital payment platforms
- Dependence on secure software development lifecycle practices
- Hybrid workforce operations across Newcastle and London offices
- Reputational sensitivity following cyberattack exposure

The defined ISMS scope reflects these contextual drivers and prioritises assets directly linked to the confidentiality, integrity, and availability of digital wallet services.

---

### 2. Interested Parties (Clause 4.2)

The scope implicitly recognises key interested parties whose requirements shape ISMS implementation:

- Customers and data subjects
- Payment partners and financial institutions
- Regulatory authorities
- Executive management
- Employees and software development teams
- Certification bodies and auditors

Their expectations influence regulatory compliance alignment, control implementation decisions, and governance accountability structures.

---

### 3. Scope Definition (Clause 4.3)

The ISMS applies specifically to the digital wallet services and related software development activities conducted at the Newcastle office, with administrative and governance oversight from the London head office.

The scope includes protection of:

- Digital wallet software architecture and source code
- Customer financial data and PII
- Transaction logs and accounting records
- Human resources data
- Internal network infrastructure
- VPN solutions for secure remote access
- Windows 11 operating environments
- Centralised and file server systems
- Supporting cloud infrastructure

This limited and clearly defined scope reflects a risk-based certification strategy, focusing governance resources on critical systems directly supporting financial transaction processing.

---

### 4. Organisational Boundaries

The scope identifies defined role accountability across:

- Executive oversight
- Software development leadership
- Information security supervision
- IT infrastructure management
- Network operations
- Finance and compliance functions
- Human resources management

This demonstrates governance ownership and control accountability — a critical element in ISMS maturity and audit defensibility.

---

### 5. Information System Boundaries

The ISMS encompasses the technological environment directly supporting digital wallet services, including:

- Application servers
- Central transaction processing systems
- Dedicated file servers
- Internal network infrastructure
- Remote access VPN controls
- Endpoint operating systems
- Cloud-hosted storage and infrastructure components

This clearly delineated technical boundary supports effective risk modelling and control traceability.

---

### 6. Physical Boundaries

The physical scope includes:

- Newcastle office (primary digital wallet development and infrastructure operations)
- London head office (administrative and governance oversight)

Physical security considerations apply to server environments, employee workspaces, and secure documentation storage within these locations.

---

### 7. Included & Excluded Assets

The scope document explicitly defines included assets critical to digital wallet operations, such as:

- Software architecture and source code
- Customer PII and financial transaction records
- Cloud infrastructure components
- HR and compliance documentation

Excluded assets (e.g., routine administrative equipment) are justified on the basis that they do not materially influence the security posture of digital wallet processing systems.

This exclusion logic reflects proportionality and risk-based decision-making consistent with ISO/IEC 27001 principles.

---

### 8. Justification for Limited Scope Strategy

The ISMS is intentionally limited to critical digital wallet infrastructure and associated governance functions to:

- Enable focused resource allocation
- Maintain clarity of accountability
- Support certification feasibility
- Ensure effective risk monitoring and control implementation

This limited-scope approach aligns with risk prioritisation best practices and demonstrates strategic governance planning rather than blanket system inclusion.

---

## Risk Assessment & Risk Treatment Methodology  
**(Reference: Risk-Assesment-Portfolio.pdf)**

The document `Risk-Assesment-Portfolio.pdf` contains the formalised risk assessment and treatment methodology implemented in alignment with ISO/IEC 27001:2022 Clause 6.1.2 and 6.1.3.

This section represents the operational core of the ISMS and demonstrates structured risk-based decision making.

---

### 1. Risk Assessment Approach

A qualitative risk assessment methodology was adopted using structured likelihood and impact scoring.

Risk identification considered:

- Information assets defined within scope
- Threat sources (internal and external)
- Vulnerabilities across people, process, and technology domains
- Regulatory exposure (GDPR and financial data handling)
- Operational and reputational impact

Each identified risk was assessed using:

- Likelihood (probability of occurrence)
- Impact (business consequence severity)

These were combined to generate an overall risk rating.

This structured methodology ensures consistency, repeatability, and audit traceability.

---

### 2. Risk Evaluation Criteria

Risk severity was determined using a defined scoring matrix.

Impact considered:

- Financial loss
- Regulatory penalties
- Operational disruption
- Customer trust erosion
- Legal consequences

Likelihood considered:

- Historical occurrence patterns
- Known industry threat landscape
- Control environment maturity
- Exposure level of the asset

Risks were categorised into severity tiers to determine treatment priority.

This ensures resource allocation aligns with risk exposure.

---

### 3. Identified Risk Domains

The portfolio identifies and assesses material risks affecting digital wallet operations, including:

- Unauthorised access to financial transaction data
- Data breaches involving customer PII
- Malware or ransomware affecting infrastructure
- Insider misuse of privileged access
- Phishing attacks targeting staff
- Remote access compromise
- System downtime impacting transaction processing

Each risk is mapped to relevant assets and contextualised within the defined scope.

This demonstrates asset-based risk modelling rather than generic threat listing.

---

### 4. Risk Treatment Strategy

For each identified risk, one of the following treatment decisions was applied:

- Risk Mitigation (implement or strengthen controls)
- Risk Acceptance (within defined tolerance thresholds)
- Risk Transfer (where applicable)
- Risk Avoidance (where strategic redesign is required)

Control selection was aligned to ISO/IEC 27001:2022 Annex A.

Treatment decisions were documented with:

- Selected control references
- Responsible ownership
- Implementation status
- Residual risk evaluation

This ensures defensibility during certification audit.

---

### 5. Residual Risk Management

Following control application, residual risk levels were reassessed.

Residual risk acceptance requires:

- Management review
- Documented justification
- Alignment with defined risk appetite

This governance step demonstrates executive oversight and accountability rather than operational-only decision making.

---

### 6. Linkage to Statement of Applicability (SoA)

The risk assessment directly informs the Statement of Applicability.

Controls selected for mitigation are justified through:

- Risk linkage
- Applicability rationale
- Implementation evidence

This ensures:

Risk → Control → Justification → Implementation → Monitoring traceability.

This is a key maturity indicator within ISO 27001 governance.

---

### 7. Governance Strength Indicators

This portfolio demonstrates:

- Structured risk logic
- Clear scoring methodology
- Defined evaluation criteria
- Treatment transparency
- Residual risk governance
- Control justification alignment

The methodology reflects a risk-based ISMS rather than a documentation-driven one.

---

---

## Statement of Applicability  
**(Reference: Statement_of_Applicability.xlsx)**

The Statement of Applicability (SoA) defines the formal control selection and justification process under ISO/IEC 27001:2022 Annex A.

This document demonstrates control governance, implementation status, and risk-based justification.

---

### 1. Purpose of the SoA

The SoA serves to:

- Identify applicable Annex A controls
- Justify inclusion or exclusion
- Confirm implementation status
- Demonstrate linkage to identified risks
- Provide audit-traceable control rationale

This document is mandatory under ISO 27001 Clause 6.1.3(d).

---

### 2. Control Selection Methodology

Control applicability was determined through:

- Risk assessment outputs
- Asset exposure level
- Regulatory obligations (GDPR)
- Operational risk tolerance
- Business continuity requirements

Controls were selected strictly on risk relevance, not blanket inclusion.

This reflects a risk-based ISMS rather than checklist compliance.

---

### 3. Control Status Classification

Each control within the SoA is categorised as:

- Implemented
- Partially Implemented
- Planned
- Not Applicable (with justification)

Exclusions are formally justified and documented to ensure audit defensibility.

---

### 4. Risk-to-Control Traceability

Each applicable control is mapped to:

- Identified risk(s)
- Treatment decision
- Implementation owner
- Residual risk consideration

This ensures structured traceability:

Risk → Control → Implementation → Residual Risk

---

### 5. Governance Maturity Indicators

The SoA demonstrates:

- Formal control governance
- Evidence-based inclusion/exclusion decisions
- Management visibility of control posture
- Structured alignment with risk appetite
- Audit readiness under ISO 27001 certification assessment

---

### 6. Operational Significance

The SoA is not treated as a static document.

It is:

- Reviewed following risk reassessment
- Updated upon significant infrastructure changes
- Revalidated during management review cycles

This ensures the ISMS remains dynamic and risk-aligned.

---

---

## Operational Security & Incident Governance  

This section consolidates four interrelated governance documents that define operational security control, incident handling maturity, and data governance accountability.

The following documents form an integrated operational control layer within the ISMS:

1. Remote Access Policy  
2. Incident Response Process  
3. Data Breach Procedure  
4. Data Access Control Record  

Together, these demonstrate control implementation beyond risk assessment and into active enforcement and response capability.

---

### 1. Remote Access Policy  
**(Reference: Remote_Access_Policy.pdf)**

This policy defines the governance, control mechanisms, and accountability structure surrounding remote access to organisational systems.

It aligns directly with ISO/IEC 27001:2022 Annex A control 6.7 (Remote Working).

---

#### Policy Objectives

- Mitigate risks associated with remote access
- Protect financial transaction data and customer PII
- Enforce encryption and secure communication protocols
- Ensure GDPR compliance
- Maintain operational flexibility without weakening security posture

---

#### Scope Coverage

Applies to:

- Employees requiring off-site access (developers, database engineers)
- Contractors and third-party vendors
- Cloud-hosted digital wallet infrastructure
- Devices used to access corporate systems

Explicit Exclusions:

- Backend financial management systems
- Encryption key management systems
- Highly sensitive systems identified through risk assessment

This demonstrates risk-based exclusion rather than blanket restriction.

---

#### Core Control Requirements

The policy enforces:

- Mandatory Multi-Factor Authentication (MFA)
- Role-Based Access Control (RBAC)
- VPN usage with SSL/TLS encryption
- IP whitelisting for API access
- Secure endpoint device compliance (anti-malware, updates)
- Log monitoring and audit oversight

These controls directly mitigate unauthorised access, interception, and privilege misuse risks.

---

#### Accountability Structure

Responsibilities are distributed across:

- Employees (secure usage & incident reporting)
- IT & Digital Wallet Teams (control implementation & monitoring)
- Management (oversight, resource allocation, audit coordination)
- Designated Digital Wallet Software Manager (operational authority)

This demonstrates governance layering rather than single-point dependency.

---

#### Risk Mitigation Strength Indicators

The policy shows:

- Control alignment with risk assessment outputs
- Explicit high-risk asset exclusion
- Technical + procedural enforcement
- GDPR-aware access restriction logic
- Monitoring and audit considerations

This elevates the policy beyond theory into enforceable governance practice.

---
---

### 2. Incident Response Process  
**(Reference: Incident_Response_Process.pdf)**

The Incident Response Process defines the structured framework for identifying, managing, containing, and recovering from security incidents affecting XY Innovate’s digital wallet operations.

This process aligns with:

- ISO/IEC 27001:2022 Clause 10.1 (Improvement)
- ISO/IEC 27035 (Incident Management principles)
- ISO/IEC 27031 (ICT Readiness for Business Continuity)
- GDPR Article 33 (Breach Notification Requirements)

It demonstrates operational security maturity beyond preventative controls.

---

#### Purpose

The process exists to:

- Mitigate operational disruption
- Protect financial transaction integrity
- Reduce reputational damage
- Preserve customer trust
- Ensure regulatory compliance
- Support continual ISMS improvement (PDCA cycle)

Incident handling is treated as a governance function, not merely a technical activity.

---

#### Scope

This process applies to:

- Digital wallet application infrastructure
- Cloud-hosted systems (e.g., Digital Ocean environment)
- Third-party service integrations
- Internal staff and contractors
- Customer financial and personal data assets

This ensures full organisational coverage rather than isolated technical scope.

---

#### Structured Incident Lifecycle

The process follows eight defined phases:

1. Detection & Identification  
2. Initial Response  
3. Analysis & Risk-Based Prioritisation  
4. Nonconformity Review  
5. Containment & Eradication  
6. Recovery  
7. External Reporting  
8. Post-Incident Evaluation & Improvement  

This demonstrates a formal lifecycle model consistent with ISO best practice.

---

#### Detection & Identification

Security monitoring mechanisms include:

- SIEM systems
- Intrusion Detection Systems (IDS)
- Endpoint monitoring tools
- Log anomaly analysis

Incidents are categorised based on:

- Severity
- Data sensitivity
- Compliance exposure
- Operational impact

This ensures prioritised escalation rather than reactive handling.

---

#### Containment & Technical Response

Immediate actions may include:

- System isolation
- Credential revocation
- Firewall rule enforcement
- Malware removal
- Patch implementation
- Configuration correction

Containment is designed to minimise lateral movement and data exposure.

---

#### Risk-Based Analysis

Root cause analysis is conducted to determine:

- Access control weaknesses
- Credential mismanagement
- Configuration failures
- Control breakdowns

Impact is assessed against the CIA triad:

- Confidentiality
- Integrity
- Availability

This reinforces linkage between incident handling and risk management.

---

#### Regulatory & External Reporting

Where personal data is affected:

- Notification to the Information Commissioner’s Office (ICO) within 72 hours (GDPR Article 33)
- Communication to affected data subjects where required

This ensures statutory compliance and transparency.

---

#### Governance & Responsibility Structure

Oversight responsibility: Chief Information Security Officer (CISO)

Operational execution:  
- IT Team  
- Digital Wallet Team  
- Security Operations (SOC)  
- Incident Response Team  

Employees are obligated to report suspected incidents immediately.

This layered accountability model demonstrates governance maturity.

---

#### Post-Incident Review & Continuous Improvement

Following stabilisation:

- Lessons learned review conducted
- Control gaps identified
- ISMS documentation updated
- Training reinforced
- Policies revised where necessary

Findings are fed into the Plan–Do–Check–Act (PDCA) cycle.

This ensures continual improvement in alignment with ISO 27001 Clause 10.

---

#### Maturity Indicators Demonstrated

- Formal lifecycle methodology
- Risk-integrated response handling
- Regulatory awareness (GDPR alignment)
- Defined governance ownership
- Continuous improvement integration
- Business continuity consideration (ISO 27031)

This reflects a structured and auditable incident management capability.

---

---

### 3. Data Breach Procedure  
**(Reference: Data_Breach_Procedure.pdf)**

The Data Breach Procedure defines the formalised response framework for managing personal data and financial information breaches affecting XY Innovate’s digital wallet operations.

This procedure aligns with:

- GDPR Article 33 (72-hour notification requirement)
- ISO/IEC 27001 Incident Management principles
- ISO/IEC 27035 (Information Security Incident Handling)
- ISO/IEC 27031 (ICT Readiness & Business Continuity)

It demonstrates regulatory alignment and structured breach governance.

---

#### Purpose

This procedure exists to:

- Safeguard customer PII and financial data
- Ensure regulatory compliance (GDPR)
- Mitigate organisational and reputational damage
- Provide structured breach escalation
- Maintain transparency and accountability

The focus is both technical containment and regulatory defensibility.

---

#### Scope

Applies to:

- Digital wallet application infrastructure
- HR management systems
- Cloud-hosted platforms (e.g., Digital Ocean)
- Physical data servers
- Employees, contractors, and third parties handling sensitive data

This reflects comprehensive coverage of internal and external exposure points.

---

#### Structured Data Breach Lifecycle

The procedure follows eight defined steps:

1. Incident Detection  
2. Immediate Notification  
3. Initial Assessment  
4. Containment Measures  
5. Root Cause Analysis  
6. Regulatory Notification  
7. Remediation & Recovery  
8. Post-Breach Review  

This demonstrates lifecycle-based governance rather than reactive action.

---

#### Detection & Monitoring Controls

Breaches are identified using:

- SIEM platforms  
- Log monitoring systems  
- Automated anomaly detection  
- Credential misuse alerts  

Oversight responsibility: IT Department & Digital Wallet Services Team.

This ensures continuous monitoring rather than reliance on manual reporting.

---

#### Immediate Escalation Protocol

Once identified:

- Incident is reported through a secure internal reporting system
- Encrypted communication channels are used
- Incident Response Team is activated

Employees are trained to escalate suspicious behaviour immediately.

This reinforces security awareness integration.

---

#### Assessment & Containment

Initial assessment includes:

- Data classification impact review (PII, financial records)
- Threat actor identification
- Scope determination
- Credential revocation
- System isolation
- Failover activation where required

Backup systems are utilised to maintain operational continuity.

---

#### Regulatory Notification Requirements

Where personal data is compromised:

- The CISO must notify the relevant supervisory authority within 72 hours (GDPR Article 33)
- Affected individuals are informed where legally required
- Communication is transparent and documented

This demonstrates legal compliance awareness and governance maturity.

---

#### Remediation & Recovery

Following containment:

- Affected systems are restored from secure backups
- Integrity validation is performed
- Vulnerabilities are patched
- Security configurations strengthened

Recovery aligns with ISO/IEC 27031 business continuity principles.

---

#### Post-Breach Review & ISMS Improvement

After stabilisation:

- Full incident documentation is completed
- Control gaps are identified
- Policies and procedures updated
- Training refreshed where weaknesses were identified
- Findings fed into the PDCA improvement cycle

This ensures the breach strengthens the ISMS rather than weakens it.

---

#### Governance Strength Indicators

This procedure demonstrates:

- Regulatory awareness (GDPR integration)
- Clear executive accountability (CISO oversight)
- Structured lifecycle methodology
- Technical + procedural containment balance
- Business continuity integration
- Continuous improvement alignment

This reflects mature breach governance capability.

---

---

### 4. Data Access Control Record  
**(Reference: Data_Access_Control_Record.pdf)**

The Data Access Control Record is a centralised governance document used to formally track, approve, monitor, and review access permissions across XY Innovate’s systems and data environments.

This record supports:

- ISO/IEC 27001 access control governance requirements  
- GDPR accountability principles  
- Least privilege enforcement  
- Audit traceability and review obligations  

It demonstrates structured access lifecycle management rather than informal permission allocation.

---

#### Purpose

The record exists to:

- Maintain visibility over system and data access
- Enforce least privilege principles
- Ensure formal approval authority
- Support audit readiness
- Demonstrate regulatory compliance

Access management is treated as a documented governance control.

---

#### Scope

Applies to:

- Digital wallet service (cloud-hosted infrastructure)
- Customer financial databases
- HR management systems
- On-premise data servers
- Employees, contractors, and third-party personnel

This ensures organisation-wide access governance coverage.

---

#### Core Record Fields

The document includes structured tracking elements:

1. **Asset Name**  
   Identifies the specific system, database, or infrastructure component.

2. **User Role**  
   Defines the authority level and functional responsibility of the requesting individual.

3. **Access Level**  
   Specifies permission type (e.g., read-only, edit, full administrative access).

4. **Justification**  
   Documents the business or compliance rationale for granting access.

5. **Approval Authority**  
   Senior management or Digital Wallet Service Manager sign-off.

6. **Access Expiry Date**  
   Time-bound access enforcement to prevent permission creep.

7. **Monitoring Logs**  
   Integration with SIEM and log monitoring systems to track activity.

This demonstrates structured access lifecycle control.

---

#### Maintenance & Review Protocol

Access governance includes:

- Manager-level request review
- CISO approval authority
- Quarterly access rights review
- Escalation of anomalies or unauthorised activity
- Technical log analysis for behavioural monitoring

This aligns with ISO/IEC 27001 requirements for periodic access review and monitoring.

---

#### Governance Strength Indicators

This control demonstrates:

- Formalised access approval workflow
- Separation of duties (request vs approval)
- Time-bound privilege management
- Centralised documentation
- Log-based monitoring integration
- Escalation protocol for irregular activity

It reflects mature identity and access governance rather than ad hoc provisioning.

---

