# ISO/IEC 27001:2022 Information Security Management System Implementation  
## Governance Portfolio – Fintech Case Study

---

## Executive Overview

This repository presents a comprehensive ISO/IEC 27001:2022-aligned Information Security Management System (ISMS) implementation developed as part of an MSc Cybersecurity programme at the University of Bradford.

The project simulates the structured design, risk modelling, and control implementation of an ISMS for a fintech organisation, *XY Innovate*. The portfolio demonstrates the practical application of risk assessment methodologies, Annex A control selection, governance documentation development, and regulatory alignment within a certification-oriented security framework.

The implementation reflects structured alignment with:

- ISO/IEC 27001:2022 (ISMS Requirements)
- ISO/IEC 27002:2022 (Control Guidance)
- GDPR (notably Article 33 breach notification)
- Cross-framework considerations including NIST and PCI-DSS

---

## Organisational Context

**Organisation:** XY Innovate (Simulated Fintech Entity)  
**Operational Model:** Hybrid workforce with centralised headquarters in Newcastle  
**Business Scope:**  
- Digital wallet infrastructure  
- Backend financial transaction systems  
- Customer Personally Identifiable Information (PII)  
- Remote engineering and support teams  

The ISMS scope was intentionally constrained to defined operational boundaries in accordance with Clause 4.3 of ISO/IEC 27001:2022, ensuring clear asset accountability and governance applicability.

---

## ISMS Scope Definition

**File:** `scope.pdf`

This document defines:

- Organisational boundaries and physical locations
- Information assets and processing environments
- Stakeholder identification
- Regulatory drivers influencing scope
- Justification for inclusion and exclusion of assets

The scope aligns directly with Clause 4.3 requirements and establishes the contextual foundation upon which risk treatment decisions are based.

---

## Risk Assessment & Treatment Methodology

**File:** `Risk_Assessment_Portfolio.pdf`

Risk identification and evaluation were conducted using the OCTAVE Allegro methodology. This structured approach enabled:

- Asset-based risk identification
- Threat scenario modelling
- Impact analysis (operational, financial, reputational, regulatory)
- Likelihood assessment
- Formalised risk treatment planning

Real-world breach analogues (e.g., major financial data compromise cases) were incorporated to strengthen scenario realism and threat modelling relevance.

The output supports Clause 6.1 (Actions to Address Risks and Opportunities) and provides documented justification for subsequent control selection.

---

## Statement of Applicability (SoA)

**File:** `Statement_of_Applicability.xlsx`

The Statement of Applicability (SoA) provides:

- Full Annex A control mapping
- Inclusion/exclusion justification
- Risk linkage references
- Implementation status tracking
- Control ownership allocation

This artefact demonstrates lifecycle governance by explicitly linking identified risks to selected security controls, ensuring traceability and audit defensibility.

The SoA functions as the central governance anchor of the ISMS.

---

## Policy & Procedural Framework

The following documents collectively demonstrate operationalisation of selected Annex A controls:

### Remote Access Policy  
**File:** `Remote_Access_Policy.pdf`

Defines secure remote access requirements including:

- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- VPN usage standards
- Device compliance requirements
- Monitoring and logging expectations

Supports Annex A access control and secure authentication controls.

---

### Incident Response Process  
**File:** `Incident_Response_Process.pdf`

Establishes:

- Structured detection and classification workflows
- Escalation pathways
- Communication protocols
- Containment and eradication phases
- Post-incident review procedures

Aligned with Annex A incident management controls and Clause 10 (Improvement).

---

### Data Breach Procedure  
**File:** `Data_Breach_Procedure.pdf`

Outlines:

- Breach identification criteria
- Regulatory notification timelines
- GDPR Article 33 compliance measures
- Forensic preservation requirements
- Stakeholder communication standards

Demonstrates regulatory integration within ISMS governance architecture.

---

### Data Access Control Record  
**File:** `Data_Access_control_record.pdf`

Implements:

- Formal approval workflows for privileged access
- Logging and traceability of access decisions
- Accountability mechanisms
- Periodic review procedures

Supports least privilege enforcement and audit trail integrity.

---

## Governance Architecture Summary

The portfolio demonstrates the following ISMS lifecycle stages:

1. Organisational Context Definition  
2. Scope Determination  
3. Risk Assessment (OCTAVE Allegro)  
4. Risk Treatment Planning  
5. Annex A Control Selection  
6. Statement of Applicability Development  
7. Policy & Procedure Implementation  
8. Audit Readiness Preparation  

This structured progression reflects a certification-oriented governance approach rather than isolated policy drafting.

---

## Compliance & Regulatory Integration

The ISMS implementation integrates cross-framework considerations, including:

- GDPR breach notification requirements
- PCI-DSS influence on financial transaction security
- NIST-aligned risk conceptualisation for comparative governance modelling

This demonstrates multi-framework literacy and regulatory awareness within a fintech risk environment.

---

## Professional Competencies Demonstrated

- Structured ISMS design aligned to ISO/IEC 27001:2022
- Formal risk modelling using OCTAVE Allegro
- Annex A control justification and traceability
- Governance documentation drafting at audit-ready standard
- Regulatory integration within security architecture
- Policy operationalisation and procedural design

---

## Purpose of This Repository

This repository serves as demonstrable evidence of practical ISMS implementation capability, suitable for:

- GRC (Governance, Risk & Compliance) roles  
- Information Security Analyst positions  
- Risk & Control Assurance functions  
- ISO 27001 audit preparation environments  

It reflects applied governance engineering rather than theoretical compliance study.
