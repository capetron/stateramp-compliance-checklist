# StateRAMP Compliance Checklist

A comprehensive compliance checklist, readiness guide, and control mapping for organizations pursuing StateRAMP authorization. This repository covers StateRAMP Categories 1 through 3, Third-Party Assessment Organization (3PAO) requirements, FedRAMP reciprocity pathways, and Authorized Product List qualification.

Last Reviewed: March 2026

## Table of Contents

- [What Is StateRAMP?](#what-is-stateramp)
- [Why StateRAMP Matters for Cloud Service Providers](#why-stateramp-matters-for-cloud-service-providers)
- [StateRAMP Categories Explained](#stateramp-categories-explained)
- [Relationship to NIST SP 800-53 and FedRAMP](#relationship-to-nist-sp-800-53-and-fedramp)
- [StateRAMP Authorization Process](#stateramp-authorization-process)
- [Third-Party Assessment Organization (3PAO) Requirements](#third-party-assessment-organization-3pao-requirements)
- [FedRAMP Reciprocity](#fedramp-reciprocity)
- [Authorized Product List](#authorized-product-list)
- [StateRAMP Compliance Checklist](#stateramp-compliance-checklist-1)
- [Common Compliance Gaps](#common-compliance-gaps)
- [How PTG Helps with StateRAMP Compliance](#how-ptg-helps-with-stateramp-compliance)
- [Frequently Asked Questions](#frequently-asked-questions)
- [Additional Resources](#additional-resources)

## What Is StateRAMP?

StateRAMP (State Risk and Authorization Management Program) is a nonprofit membership organization that provides a standardized approach to verifying the cybersecurity posture of cloud service providers (CSPs) serving state and local government agencies. Modeled after the federal FedRAMP program, StateRAMP establishes a common security baseline so that state, local, tribal, and territorial (SLTT) government entities can confidently adopt cloud solutions without each agency performing its own independent security assessment.

StateRAMP was officially launched in 2021 to address a critical gap: while federal agencies had FedRAMP to validate cloud security, state and local governments lacked an equivalent standardized framework. This resulted in inconsistent security evaluations, duplicated audit efforts across jurisdictions, and CSPs facing dozens of different security questionnaires from different government customers.

The program maintains an Authorized Product List that catalogs cloud products and services that have met StateRAMP security requirements. Government agencies across the country reference this list when making procurement decisions, making StateRAMP authorization a significant competitive advantage for CSPs targeting the public sector market.

StateRAMP verification is built on NIST SP 800-53 security controls, the same master control catalog that underpins FedRAMP, FISMA, and numerous other federal and state compliance frameworks. This alignment means organizations already pursuing NIST-based compliance can leverage their existing security investments toward StateRAMP authorization.

## Why StateRAMP Matters for Cloud Service Providers

The state and local government IT market represents over $120 billion in annual spending, with cloud adoption accelerating rapidly. StateRAMP authorization directly impacts a CSP's ability to compete for this market:

**Market Access.** A growing number of state governments, including Texas, Indiana, Minnesota, and Arizona, either require or strongly prefer StateRAMP-verified products for cloud procurements. Without authorization, CSPs are effectively locked out of these opportunities.

**Reduced Sales Friction.** Instead of responding to unique security questionnaires from every state agency, a single StateRAMP authorization satisfies security due diligence across all participating states.

**Competitive Differentiation.** As of March 2026, fewer than 350 products appear on the StateRAMP Authorized Product List. Early authorization creates a meaningful competitive moat.

**FedRAMP Alignment.** Because StateRAMP is built on the same NIST control framework as FedRAMP, pursuing StateRAMP authorization simultaneously advances a CSP's readiness for federal markets.

**Trust Signal.** StateRAMP authorization demonstrates to all customers, not just government, that an organization takes security seriously and has been independently validated.

## StateRAMP Categories Explained

StateRAMP organizes cloud products into three impact categories based on the sensitivity of the data they process. Each category maps to a corresponding set of NIST SP 800-53 security controls:

### Category 1 (Low Impact)

Category 1 applies to cloud products that process data where unauthorized disclosure, modification, or disruption would have limited adverse effects. This category aligns with the FedRAMP Low baseline and requires implementation of approximately 156 NIST SP 800-53 controls.

Typical Category 1 products include public-facing websites, general productivity tools, and systems that handle non-sensitive public information.

### Category 2 (Moderate Impact)

Category 2 covers cloud products processing data where compromise could result in serious adverse effects on organizational operations, assets, or individuals. This is the most commonly pursued StateRAMP category and aligns with the FedRAMP Moderate baseline, requiring approximately 323 NIST SP 800-53 controls.

Category 2 products typically include financial systems, personnel management tools, procurement platforms, and systems handling Personally Identifiable Information (PII).

### Category 3 (High Impact)

Category 3 addresses cloud products processing data where compromise could cause severe or catastrophic adverse effects. This aligns with the FedRAMP High baseline and requires approximately 421 NIST SP 800-53 controls.

Category 3 products include systems handling law enforcement data, healthcare records, critical infrastructure management systems, and other high-sensitivity government data.

### Category Selection

Choosing the correct category is a critical early decision. Selecting too low a category means the authorization will not cover the data types customers need to process. Selecting too high wastes resources on unnecessary controls. The data types processed by the cloud product, not the product's function, determine the appropriate category.

## Relationship to NIST SP 800-53 and FedRAMP

StateRAMP is built directly on NIST SP 800-53 Rev. 5, the comprehensive catalog of over 1,000 security and privacy controls published by the National Institute of Standards and Technology. Understanding this relationship is essential for efficient compliance:

**NIST SP 800-53** serves as the master control catalog. It defines the universe of possible security controls organized into 20 families covering access control, audit and accountability, incident response, system and communications protection, and more.

**FedRAMP** selects subsets of NIST SP 800-53 controls at Low, Moderate, and High baselines and adds FedRAMP-specific parameters and requirements for federal cloud deployments.

**StateRAMP** adopts the FedRAMP baselines (and therefore NIST SP 800-53 controls) but tailors them for state and local government contexts. StateRAMP Categories 1, 2, and 3 correspond to FedRAMP Low, Moderate, and High respectively.

This layered relationship means:

1. Organizations with existing NIST SP 800-53 implementations have a direct path to StateRAMP.
2. FedRAMP-authorized products can leverage their existing authorization for StateRAMP through the reciprocity pathway.
3. StateRAMP work simultaneously advances readiness for CMMC, FISMA, and other NIST-derived frameworks.
4. Control implementations are reusable across frameworks, reducing overall compliance burden.

For a detailed mapping of NIST SP 800-53 controls, visit [https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final).

## StateRAMP Authorization Process

The StateRAMP authorization process follows a structured lifecycle:

### Step 1: Readiness Assessment

Before pursuing full authorization, CSPs should conduct a readiness assessment to identify gaps between their current security posture and StateRAMP requirements. This includes:

- Selecting the appropriate impact category (1, 2, or 3)
- Performing a gap analysis against the relevant NIST SP 800-53 control baseline
- Developing a remediation plan with timelines and resource estimates
- Preparing the System Security Plan (SSP)

### Step 2: Engage a 3PAO

CSPs must engage an accredited Third-Party Assessment Organization to conduct the independent security assessment. The 3PAO performs:

- Review of the System Security Plan and supporting documentation
- Security testing and evaluation of control implementations
- Vulnerability scanning and penetration testing
- Compilation of the Security Assessment Report (SAR)

### Step 3: Submit Authorization Package

The complete authorization package submitted to StateRAMP includes:

- System Security Plan (SSP)
- Security Assessment Report (SAR)
- Plan of Action and Milestones (POA&M)
- Continuous monitoring documentation
- Supporting artifacts and evidence

### Step 4: StateRAMP Review

The StateRAMP Program Management Office (PMO) reviews the authorization package, may request additional information or clarification, and makes the authorization decision.

### Step 5: Continuous Monitoring

Authorization is not a one-time event. CSPs must maintain ongoing compliance through:

- Monthly vulnerability scanning
- Annual security assessments
- Continuous monitoring reporting
- Timely remediation of identified vulnerabilities
- Incident reporting within required timeframes

### Authorization Statuses

StateRAMP assigns products one of several statuses:

- **Authorized**: Product has met all security requirements for its category
- **Provisional**: Product has completed assessment and is under PMO review
- **Ready**: Product has completed a readiness assessment, demonstrating intent and capability
- **In Process**: Product is actively pursuing authorization
- **Not Authorized**: Product has not met requirements

## Third-Party Assessment Organization (3PAO) Requirements

3PAOs play a critical role in the StateRAMP process. Key requirements:

- Must be accredited by the American Association for Laboratory Accreditation (A2LA) under ISO/IEC 17020
- Must demonstrate competence in assessing cloud service provider security
- Must maintain independence from the CSP being assessed
- Assessors must hold relevant certifications (CISSP, CISA, or equivalent)
- Must follow StateRAMP assessment guidance and templates

Selecting the right 3PAO is important. Consider their experience with your technology stack, their familiarity with your impact category, their availability and timeline, and their communication style during the assessment process.

## FedRAMP Reciprocity

One of StateRAMP's most valuable features is its reciprocity with FedRAMP. CSPs that already hold a FedRAMP Authorization to Operate (ATO) can leverage that authorization to achieve StateRAMP status through an expedited process:

**Full Reciprocity.** Products with an active FedRAMP ATO at the Moderate or High baseline can qualify for StateRAMP Authorized status at the corresponding category with minimal additional work.

**Expedited Review.** Instead of a full assessment, FedRAMP-authorized products undergo a streamlined review focused on state-specific requirements and continuous monitoring compliance.

**Shared Continuous Monitoring.** Ongoing monitoring activities performed for FedRAMP can satisfy StateRAMP continuous monitoring requirements.

**Cost Savings.** Reciprocity can reduce StateRAMP authorization costs by 60% to 80% compared to pursuing a standalone authorization.

For CSPs considering both federal and state government markets, this reciprocity pathway makes it strategically advantageous to pursue FedRAMP first and then leverage that investment for StateRAMP authorization.

## Authorized Product List

The StateRAMP Authorized Product List is the public-facing registry of cloud products that have achieved StateRAMP authorization. The list is available at [https://stateramp.org/authorized-product-list/](https://stateramp.org/authorized-product-list/) and includes:

- Product name and version
- Cloud Service Provider name
- Authorization status (Authorized, Provisional, Ready, In Process)
- Impact category (1, 2, or 3)
- Service model (IaaS, PaaS, SaaS)
- Authorization date

Government agencies across the country reference this list during procurement. Appearing on it signals that a product has been independently validated against rigorous security standards, significantly reducing procurement friction and accelerating sales cycles.

## StateRAMP Compliance Checklist

See the full detailed checklist in [compliance-checklist.md](compliance-checklist.md).

A summary of the major compliance areas:

### Governance and Documentation
- [ ] Define system boundary and data flows
- [ ] Complete System Security Plan (SSP)
- [ ] Document policies for all 20 NIST SP 800-53 control families
- [ ] Establish change management procedures
- [ ] Create incident response plan
- [ ] Develop contingency/disaster recovery plan

### Access Control
- [ ] Implement role-based access control (RBAC)
- [ ] Enforce multi-factor authentication (MFA)
- [ ] Implement least-privilege access principles
- [ ] Document account management procedures
- [ ] Configure session timeout and lockout policies

### Audit and Accountability
- [ ] Enable comprehensive audit logging
- [ ] Protect audit logs from tampering
- [ ] Configure log retention (minimum 1 year)
- [ ] Implement automated audit log review
- [ ] Establish audit reduction and report generation

### Vulnerability Management
- [ ] Conduct monthly vulnerability scans
- [ ] Perform annual penetration testing
- [ ] Establish remediation timelines (30/90/180 days by severity)
- [ ] Maintain POA&M for all findings
- [ ] Implement automated patch management

### Continuous Monitoring
- [ ] Deploy intrusion detection/prevention systems
- [ ] Implement Security Information and Event Management (SIEM)
- [ ] Establish continuous monitoring plan
- [ ] Submit monthly monitoring reports to StateRAMP
- [ ] Conduct annual reassessment

## Common Compliance Gaps

Based on 23+ years of compliance consulting experience, these are the most frequently encountered gaps when organizations pursue StateRAMP authorization:

1. **Incomplete System Security Plans.** SSPs that lack sufficient detail on control implementations, particularly for inherited controls from underlying infrastructure providers.

2. **Weak Continuous Monitoring.** Organizations that treat authorization as a one-time event rather than an ongoing process. StateRAMP requires active, documented continuous monitoring.

3. **Insufficient Separation of Duties.** Small development teams where the same individuals handle development, deployment, and security, violating separation of duties requirements.

4. **Missing POA&M Management.** Failure to track, prioritize, and remediate Plan of Action and Milestones items within required timeframes.

5. **Inadequate Incident Response Testing.** Having an incident response plan on paper but never testing it through tabletop exercises or simulated incidents.

6. **Encryption Gaps.** Data not encrypted at rest and in transit using FIPS 140-2 validated cryptographic modules, a common requirement that trips up many organizations.

7. **Third-Party Risk Management.** Insufficient documentation of security controls implemented by subservice providers and supply chain partners.

## How PTG Helps with StateRAMP Compliance

Petronella Technology Group, Inc. (PTG) brings a unique combination of capabilities to StateRAMP compliance engagements:

### Craig Petronella's Credentials

Every PTG engagement is led by Craig Petronella, whose qualifications include:

- **CMMC Registered Practitioner**, qualified to conduct CMMC assessments for defense contractors
- **Licensed Digital Forensic Examiner #604180**, providing forensic investigation capabilities when security incidents occur
- **Cisco CCNA and CWNE**, demonstrating deep networking and wireless security expertise
- **MIT Artificial Intelligence Certificate**, combining AI knowledge with cybersecurity
- **Amazon #1 Best-Selling Author** of 14+ cybersecurity books
- **23+ years in cybersecurity**, with hands-on experience across compliance frameworks

### What Makes PTG Different

**AI-Powered Compliance.** PTG uses its own private AI fleet, including on-premise large language models and custom GPU infrastructure, to accelerate compliance assessments, automate control mapping, and continuously monitor security posture. No other firm in the Research Triangle has this capability.

**Patented Technology Stack.** PTG's proprietary, patented security and compliance tools automate what competitors do manually, reducing assessment timelines and improving accuracy.

**Licensed Digital Forensic Examiner.** When compliance fails and a breach occurs, PTG has the forensic expertise to investigate, preserve evidence, and support legal proceedings. Most compliance firms cannot offer this.

**AI + Cybersecurity Combined.** PTG is one of the only firms that combines AI development (custom AI agents, private LLMs, GPU hosting) with cybersecurity and compliance. StateRAMP compliance is not just about checking boxes; it is about building a security posture that adapts to emerging threats, including AI-driven attacks.

**Fleet Infrastructure.** PTG's on-premise AI infrastructure (GPU clusters, private cloud) proves PTG practices what it preaches about data sovereignty and private AI.

**SMB Focus.** PTG makes enterprise-grade compliance accessible to small and mid-size businesses, providing the same level of rigor that large enterprises receive but at a scale and price point that works for growing organizations.

### Services for StateRAMP

PTG provides end-to-end StateRAMP compliance services:

- **Gap Assessment**: Comprehensive evaluation of current security posture against StateRAMP requirements
- **Remediation Planning**: Prioritized roadmap to close identified gaps
- **SSP Development**: Complete System Security Plan authoring and documentation
- **3PAO Preparation**: Readiness activities to ensure a successful third-party assessment
- **Continuous Monitoring**: Ongoing monitoring services using PTG's AI-powered tools
- **Incident Response**: 24/7 incident response capabilities backed by forensic expertise

**Ready to start your StateRAMP journey?** Call 919-348-4912 or visit [https://www.petronellatech.com/compliance/stateramp/](https://www.petronellatech.com/compliance/stateramp/) to schedule a free compliance assessment.

See also: [PTG Compliance Packages](https://www.petronellatech.com/compliance/packages/)

## Frequently Asked Questions

**Q: How long does StateRAMP authorization take?**
A: The timeline varies by category and organizational readiness. Category 1 authorizations typically take 3 to 6 months, Category 2 takes 6 to 12 months, and Category 3 takes 9 to 18 months. Organizations with existing FedRAMP authorization can achieve StateRAMP status in as little as 4 to 8 weeks through the reciprocity pathway.

**Q: How much does StateRAMP authorization cost?**
A: Costs depend on the impact category, current security maturity, and scope of the system. Category 1 authorizations typically range from $50,000 to $150,000 including 3PAO assessment fees. Category 2 ranges from $150,000 to $400,000. Category 3 can exceed $500,000. These estimates include gap assessment, remediation, documentation, and assessment fees.

**Q: Is StateRAMP mandatory?**
A: StateRAMP is not universally mandatory, but a growing number of states require or strongly prefer StateRAMP-verified products. Texas, Indiana, Minnesota, and Arizona are among states that have adopted StateRAMP requirements in their procurement processes. Even where not required, StateRAMP authorization provides a significant competitive advantage.

**Q: Can I use my FedRAMP authorization for StateRAMP?**
A: Yes. FedRAMP reciprocity is a core feature of StateRAMP. Products with an active FedRAMP ATO can achieve StateRAMP Authorized status through an expedited review process, typically saving 60% to 80% on cost and time.

**Q: What is the difference between StateRAMP and FedRAMP?**
A: Both are based on NIST SP 800-53 controls. FedRAMP is the federal program for cloud products used by federal agencies. StateRAMP is for state and local government. While they share the same control framework, StateRAMP includes additional considerations for state-specific requirements and offers its own Authorized Product List. FedRAMP authorization can be leveraged for StateRAMP through reciprocity.

**Q: Do I need a 3PAO for StateRAMP?**
A: Yes. Independent assessment by an accredited Third-Party Assessment Organization is required for all StateRAMP authorization categories. The 3PAO must be accredited by A2LA under ISO/IEC 17020.

**Q: What happens after I get authorized?**
A: Authorization is the beginning, not the end. CSPs must maintain continuous monitoring, submit monthly reports, remediate vulnerabilities within prescribed timeframes, and undergo annual reassessments. Failure to maintain continuous monitoring can result in loss of authorization status.

**Q: How does StateRAMP relate to other compliance frameworks?**
A: StateRAMP is built on NIST SP 800-53, the same master control catalog that underpins FedRAMP, FISMA, CMMC, HIPAA (via NIST SP 800-66), and numerous other frameworks. Achieving StateRAMP authorization simultaneously advances readiness for these related frameworks, and vice versa.

## Additional Resources

- [StateRAMP Official Website](https://stateramp.org/)
- [StateRAMP Authorized Product List](https://stateramp.org/authorized-product-list/)
- [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [FedRAMP Official Website](https://www.fedramp.gov/)
- [PTG Compliance Services](https://www.petronellatech.com/compliance/)
- [PTG NIST Compliance](https://www.petronellatech.com/nist/)
- [PTG AI Services](https://www.petronellatech.com/ai/)
- [PTG Cybersecurity Services](https://www.petronellatech.com/cybersecurity/)
- [PTG Managed IT Services](https://www.petronellatech.com/managed-it/)

## About Petronella Technology Group, Inc.

Petronella Technology Group, Inc. (PTG) provides AI-powered cybersecurity and compliance services for small and mid-size businesses. Led by Craig Petronella, a CMMC Registered Practitioner, Licensed Digital Forensic Examiner (#604180), and Amazon #1 Best-Selling Author of 14+ cybersecurity books, PTG combines 23+ years of cybersecurity experience with cutting-edge AI technology to make enterprise-grade compliance accessible to organizations of all sizes.

**Petronella Technology Group, Inc.**
5540 Centerview Dr. Suite 200
Raleigh, NC 27606
Phone: 919-348-4912

[https://www.petronellatech.com](https://www.petronellatech.com)

## License

This checklist is provided under the MIT License. See [LICENSE](LICENSE) for details.
