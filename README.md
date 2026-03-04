# ISO/IEC 27001:2022 ISMS Implementation Portfolio  
## Fintech Governance & Risk Case Study

---

## Executive Governance Overview

This repository presents a structured implementation of an Information Security Management System (ISMS) aligned to ISO/IEC 27001:2022, developed for a simulated fintech organisation, XY Innovate, as part of an MSc Cybersecurity programme.

The portfolio demonstrates the practical design and documentation of an ISMS covering scope definition, risk assessment using OCTAVE Allegro, Annex A control mapping through a Statement of Applicability, and the development of operational security policies.

The objective of this implementation was to establish a certification-oriented ISMS framework capable of:

- Protecting digital wallet infrastructure and customer financial data
- Addressing regulatory obligations including GDPR
- Strengthening governance maturity following cyber risk exposure
- Aligning security controls with identified organisational risks
- Supporting ISO/IEC 27001:2022 audit readiness

All documentation contained within this repository reflects a structured, risk-based approach to information security governance.

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
