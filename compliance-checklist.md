# StateRAMP Compliance Checklist

A detailed, actionable checklist for organizations pursuing StateRAMP authorization. Organized by NIST SP 800-53 control families and tailored to StateRAMP-specific requirements.

Last Reviewed: March 2026

## How to Use This Checklist

1. Identify your target StateRAMP category (1, 2, or 3).
2. Work through each section, marking controls as implemented, partially implemented, or not implemented.
3. For partially implemented or not implemented controls, document the gap and add to your Plan of Action and Milestones (POA&M).
4. Engage a 3PAO for independent validation once you believe controls are substantially implemented.

Categories are indicated as follows:
- **[C1]** = Required for Category 1 (Low Impact)
- **[C2]** = Required for Category 2 (Moderate Impact)
- **[C3]** = Required for Category 3 (High Impact)

If no category is specified, the control applies to all categories.

---

## 1. Pre-Authorization Readiness

- [ ] Identify target StateRAMP category based on data sensitivity
- [ ] Define the system boundary (network diagrams, data flow diagrams, interconnections)
- [ ] Inventory all system components, services, and third-party integrations
- [ ] Identify applicable NIST SP 800-53 Rev. 5 control baseline
- [ ] Conduct initial gap assessment against the control baseline
- [ ] Develop remediation roadmap with timelines, owners, and cost estimates
- [ ] Assign StateRAMP project lead and establish governance structure
- [ ] Identify and engage a 3PAO accredited by A2LA under ISO/IEC 17020
- [ ] Establish budget for authorization and continuous monitoring

## 2. Governance and Documentation

- [ ] Develop or update System Security Plan (SSP) using StateRAMP template
- [ ] Document all control implementations with sufficient detail for 3PAO validation
- [ ] Identify and document inherited controls from infrastructure providers
- [ ] Create or update configuration management plan
- [ ] Develop risk assessment methodology and document risk register
- [ ] Establish change management board and procedures
- [ ] Document roles and responsibilities for all security functions
- [ ] Create rules of behavior / acceptable use policy
- [ ] Develop privacy impact assessment (if processing PII)
- [ ] Establish document version control and review cadence

## 3. Access Control (AC)

- [ ] **[C1/C2/C3]** AC-1: Develop access control policy and procedures
- [ ] **[C1/C2/C3]** AC-2: Implement account management (creation, modification, disabling, removal)
- [ ] **[C2/C3]** AC-2(1): Automate account management activities
- [ ] **[C2/C3]** AC-2(2): Automatically remove/disable temporary and emergency accounts
- [ ] **[C2/C3]** AC-2(3): Disable inactive accounts after 90 days
- [ ] **[C3]** AC-2(4): Automate audit of account creation, modification, enabling, disabling, removal
- [ ] **[C1/C2/C3]** AC-3: Enforce approved authorizations for logical access
- [ ] **[C2/C3]** AC-4: Enforce information flow control policies
- [ ] **[C1/C2/C3]** AC-5: Implement separation of duties
- [ ] **[C1/C2/C3]** AC-6: Enforce least privilege
- [ ] **[C2/C3]** AC-6(1): Authorize access to security functions for specific personnel only
- [ ] **[C2/C3]** AC-6(2): Restrict privileged access to non-security functions
- [ ] **[C2/C3]** AC-6(5): Restrict privileged accounts to specific personnel
- [ ] **[C2/C3]** AC-6(9): Log execution of privileged functions
- [ ] **[C2/C3]** AC-6(10): Prevent non-privileged users from executing privileged functions
- [ ] **[C1/C2/C3]** AC-7: Limit unsuccessful logon attempts (lock after defined threshold)
- [ ] **[C1/C2/C3]** AC-8: Display system use notification / login banner
- [ ] **[C2/C3]** AC-10: Limit concurrent sessions per user
- [ ] **[C1/C2/C3]** AC-11: Session lock after defined inactivity period
- [ ] **[C2/C3]** AC-12: Terminate sessions after defined conditions
- [ ] **[C1/C2/C3]** AC-14: Identify permitted actions without identification/authentication
- [ ] **[C1/C2/C3]** AC-17: Manage and restrict remote access
- [ ] **[C2/C3]** AC-17(1): Monitor and control remote access with automated mechanisms
- [ ] **[C2/C3]** AC-17(2): Protect confidentiality/integrity of remote access using encryption
- [ ] **[C2/C3]** AC-17(3): Route remote access through managed access control points
- [ ] **[C2/C3]** AC-17(4): Authorize and monitor privileged commands via remote access
- [ ] **[C1/C2/C3]** AC-18: Manage and restrict wireless access
- [ ] **[C2/C3]** AC-18(1): Protect wireless access using authentication and encryption
- [ ] **[C1/C2/C3]** AC-19: Manage and restrict mobile device access
- [ ] **[C1/C2/C3]** AC-20: Manage use of external information systems
- [ ] **[C2/C3]** AC-21: Implement information sharing controls
- [ ] **[C1/C2/C3]** AC-22: Manage publicly accessible content

## 4. Awareness and Training (AT)

- [ ] **[C1/C2/C3]** AT-1: Develop security awareness and training policy
- [ ] **[C1/C2/C3]** AT-2: Provide security awareness training to all users
- [ ] **[C2/C3]** AT-2(2): Include insider threat awareness training
- [ ] **[C1/C2/C3]** AT-3: Provide role-based security training
- [ ] **[C1/C2/C3]** AT-4: Maintain security training records

## 5. Audit and Accountability (AU)

- [ ] **[C1/C2/C3]** AU-1: Develop audit and accountability policy
- [ ] **[C1/C2/C3]** AU-2: Define auditable events
- [ ] **[C2/C3]** AU-2(3): Review and update auditable events annually
- [ ] **[C1/C2/C3]** AU-3: Ensure audit records contain sufficient detail
- [ ] **[C2/C3]** AU-3(1): Generate audit records with additional detail
- [ ] **[C1/C2/C3]** AU-4: Allocate sufficient audit record storage
- [ ] **[C1/C2/C3]** AU-5: Alert on audit processing failures
- [ ] **[C1/C2/C3]** AU-6: Review and analyze audit records regularly
- [ ] **[C2/C3]** AU-6(1): Integrate audit review with automated mechanisms
- [ ] **[C2/C3]** AU-6(3): Correlate audit records from multiple sources
- [ ] **[C2/C3]** AU-7: Provide audit reduction and report generation
- [ ] **[C2/C3]** AU-7(1): Enable automatic processing of audit records
- [ ] **[C1/C2/C3]** AU-8: Use internal system clocks synchronized to authoritative time source
- [ ] **[C2/C3]** AU-8(1): Synchronize clocks with defined time source
- [ ] **[C1/C2/C3]** AU-9: Protect audit information from unauthorized access
- [ ] **[C2/C3]** AU-9(4): Authorize access to audit management by subset of privileged users
- [ ] **[C2/C3]** AU-11: Retain audit records for defined period (minimum 1 year)
- [ ] **[C1/C2/C3]** AU-12: Generate audit records for defined events

## 6. Security Assessment and Authorization (CA)

- [ ] **[C1/C2/C3]** CA-1: Develop security assessment and authorization policy
- [ ] **[C1/C2/C3]** CA-2: Develop and execute security assessment plan
- [ ] **[C2/C3]** CA-2(1): Employ independent assessors
- [ ] **[C1/C2/C3]** CA-3: Authorize and document system interconnections
- [ ] **[C1/C2/C3]** CA-5: Develop and maintain Plan of Action and Milestones (POA&M)
- [ ] **[C1/C2/C3]** CA-6: Designate authorizing official
- [ ] **[C1/C2/C3]** CA-7: Implement continuous monitoring program
- [ ] **[C2/C3]** CA-7(1): Employ independent assessors for continuous monitoring
- [ ] **[C1/C2/C3]** CA-9: Document and authorize internal system connections

## 7. Configuration Management (CM)

- [ ] **[C1/C2/C3]** CM-1: Develop configuration management policy
- [ ] **[C1/C2/C3]** CM-2: Establish and maintain baseline configurations
- [ ] **[C2/C3]** CM-2(1): Review and update baselines annually
- [ ] **[C2/C3]** CM-2(3): Retain previous baselines for rollback
- [ ] **[C2/C3]** CM-2(7): Configure devices for high-risk areas with restrictive settings
- [ ] **[C2/C3]** CM-3: Implement configuration change control
- [ ] **[C2/C3]** CM-3(2): Test, validate, and document changes before implementation
- [ ] **[C1/C2/C3]** CM-4: Analyze security impact of changes
- [ ] **[C2/C3]** CM-5: Define and enforce access restrictions for changes
- [ ] **[C1/C2/C3]** CM-6: Establish and enforce configuration settings
- [ ] **[C2/C3]** CM-7: Restrict system functions, ports, protocols, and services
- [ ] **[C2/C3]** CM-7(1): Review system for unnecessary functions periodically
- [ ] **[C2/C3]** CM-7(2): Prevent program execution unless on approved list (or deny on block list)
- [ ] **[C2/C3]** CM-7(5): Review software allowlist/blocklist periodically
- [ ] **[C1/C2/C3]** CM-8: Maintain inventory of system components
- [ ] **[C2/C3]** CM-8(1): Update inventory as part of installations and removals
- [ ] **[C2/C3]** CM-8(3): Automate detection of unauthorized components
- [ ] **[C2/C3]** CM-8(5): Verify no duplicate components
- [ ] **[C2/C3]** CM-9: Develop and implement configuration management plan
- [ ] **[C1/C2/C3]** CM-10: Enforce software usage restrictions and licensing
- [ ] **[C1/C2/C3]** CM-11: Control user-installed software

## 8. Contingency Planning (CP)

- [ ] **[C1/C2/C3]** CP-1: Develop contingency planning policy
- [ ] **[C1/C2/C3]** CP-2: Develop contingency plan
- [ ] **[C2/C3]** CP-2(1): Coordinate contingency plan with related plans
- [ ] **[C2/C3]** CP-2(3): Plan for resumption of essential missions and business functions
- [ ] **[C2/C3]** CP-2(8): Identify critical assets
- [ ] **[C1/C2/C3]** CP-3: Conduct contingency training
- [ ] **[C1/C2/C3]** CP-4: Test contingency plan at least annually
- [ ] **[C2/C3]** CP-4(1): Coordinate testing with related plans
- [ ] **[C2/C3]** CP-6: Establish alternate storage site
- [ ] **[C2/C3]** CP-6(1): Separate alternate storage site from primary to reduce risk
- [ ] **[C2/C3]** CP-6(3): Ensure alternate storage site accessibility
- [ ] **[C2/C3]** CP-7: Establish alternate processing site
- [ ] **[C2/C3]** CP-7(1): Separate alternate processing site from primary
- [ ] **[C2/C3]** CP-7(2): Ensure alternate processing site accessibility
- [ ] **[C2/C3]** CP-7(3): Identify priority of service provisions
- [ ] **[C1/C2/C3]** CP-9: Conduct system backups
- [ ] **[C2/C3]** CP-9(1): Test backup reliability and integrity
- [ ] **[C1/C2/C3]** CP-10: Provide for system recovery and reconstitution
- [ ] **[C2/C3]** CP-10(2): Recover to known state using transaction recovery

## 9. Identification and Authentication (IA)

- [ ] **[C1/C2/C3]** IA-1: Develop identification and authentication policy
- [ ] **[C1/C2/C3]** IA-2: Uniquely identify and authenticate organizational users
- [ ] **[C1/C2/C3]** IA-2(1): Implement multi-factor authentication for privileged accounts
- [ ] **[C2/C3]** IA-2(2): Implement multi-factor authentication for non-privileged accounts
- [ ] **[C2/C3]** IA-2(8): Implement replay-resistant authentication mechanisms
- [ ] **[C2/C3]** IA-2(12): Accept and verify PIV credentials
- [ ] **[C1/C2/C3]** IA-4: Manage information system identifiers
- [ ] **[C1/C2/C3]** IA-5: Manage authenticators (passwords, tokens, certificates)
- [ ] **[C1/C2/C3]** IA-5(1): Enforce password complexity and rotation requirements
- [ ] **[C2/C3]** IA-5(2): Implement PKI-based authentication
- [ ] **[C2/C3]** IA-5(3): Register authenticators in person with identity verification
- [ ] **[C2/C3]** IA-5(11): Implement hardware token-based authentication
- [ ] **[C1/C2/C3]** IA-6: Obscure authenticator feedback
- [ ] **[C1/C2/C3]** IA-7: Use FIPS 140-2 validated cryptographic modules for authentication
- [ ] **[C1/C2/C3]** IA-8: Identify and authenticate non-organizational users
- [ ] **[C2/C3]** IA-8(1): Accept PIV credentials from other agencies
- [ ] **[C2/C3]** IA-8(2): Accept third-party credentials per established trust agreements
- [ ] **[C2/C3]** IA-8(4): Use defined profiles for identity solutions

## 10. Incident Response (IR)

- [ ] **[C1/C2/C3]** IR-1: Develop incident response policy and procedures
- [ ] **[C1/C2/C3]** IR-2: Provide incident response training
- [ ] **[C2/C3]** IR-2(1): Include simulated events in training
- [ ] **[C2/C3]** IR-2(2): Include automated training environments
- [ ] **[C1/C2/C3]** IR-3: Test incident response capability
- [ ] **[C2/C3]** IR-3(2): Coordinate testing with related plans
- [ ] **[C1/C2/C3]** IR-4: Handle incidents per defined procedures
- [ ] **[C2/C3]** IR-4(1): Automate incident handling processes
- [ ] **[C1/C2/C3]** IR-5: Track and document security incidents
- [ ] **[C1/C2/C3]** IR-6: Report incidents per defined procedures and timelines
- [ ] **[C2/C3]** IR-6(1): Automate incident reporting
- [ ] **[C1/C2/C3]** IR-7: Provide incident response assistance
- [ ] **[C2/C3]** IR-7(1): Automate support for availability of response information
- [ ] **[C1/C2/C3]** IR-8: Develop and maintain incident response plan
- [ ] Report security incidents to StateRAMP PMO within required timeframes

## 11. Maintenance (MA)

- [ ] **[C1/C2/C3]** MA-1: Develop maintenance policy
- [ ] **[C1/C2/C3]** MA-2: Perform controlled maintenance
- [ ] **[C2/C3]** MA-3: Control maintenance tools
- [ ] **[C2/C3]** MA-3(1): Inspect maintenance tools
- [ ] **[C2/C3]** MA-3(2): Check media for malicious code before use
- [ ] **[C1/C2/C3]** MA-4: Control remote maintenance
- [ ] **[C2/C3]** MA-4(2): Document remote maintenance activities
- [ ] **[C1/C2/C3]** MA-5: Authorize maintenance personnel

## 12. Media Protection (MP)

- [ ] **[C1/C2/C3]** MP-1: Develop media protection policy
- [ ] **[C1/C2/C3]** MP-2: Restrict access to defined types of digital and non-digital media
- [ ] **[C2/C3]** MP-3: Mark media with distribution limitations
- [ ] **[C2/C3]** MP-4: Control and store media
- [ ] **[C2/C3]** MP-5: Protect media during transport
- [ ] **[C2/C3]** MP-5(4): Use cryptographic mechanisms during transport
- [ ] **[C1/C2/C3]** MP-6: Sanitize or destroy media before disposal/release/reuse
- [ ] **[C2/C3]** MP-6(2): Test sanitization equipment and procedures
- [ ] **[C1/C2/C3]** MP-7: Restrict use of defined media types

## 13. Physical and Environmental Protection (PE)

- [ ] **[C1/C2/C3]** PE-1: Develop physical and environmental protection policy
- [ ] **[C1/C2/C3]** PE-2: Authorize physical access
- [ ] **[C1/C2/C3]** PE-3: Control physical access with authentication devices
- [ ] **[C1/C2/C3]** PE-4: Control physical access to transmission medium
- [ ] **[C2/C3]** PE-5: Control physical access to output devices
- [ ] **[C1/C2/C3]** PE-6: Monitor physical access
- [ ] **[C2/C3]** PE-6(1): Monitor intrusion alarms and surveillance equipment
- [ ] **[C1/C2/C3]** PE-8: Maintain visitor access records
- [ ] **[C2/C3]** PE-9: Protect power equipment and cabling
- [ ] **[C2/C3]** PE-10: Provide emergency shutoff capability
- [ ] **[C2/C3]** PE-11: Provide emergency power
- [ ] **[C1/C2/C3]** PE-12: Provide emergency lighting
- [ ] **[C1/C2/C3]** PE-13: Provide fire protection
- [ ] **[C2/C3]** PE-13(2): Employ fire suppression systems with automatic activation
- [ ] **[C2/C3]** PE-13(3): Employ automatic fire suppression in areas not staffed continuously
- [ ] **[C1/C2/C3]** PE-14: Control temperature and humidity
- [ ] **[C1/C2/C3]** PE-15: Protect against water damage
- [ ] **[C1/C2/C3]** PE-16: Control delivery and removal of equipment
- [ ] **[C2/C3]** PE-17: Provide alternate work site security

## 14. Planning (PL)

- [ ] **[C1/C2/C3]** PL-1: Develop security planning policy
- [ ] **[C1/C2/C3]** PL-2: Develop and maintain System Security Plan (SSP)
- [ ] **[C2/C3]** PL-2(3): Plan and coordinate security-related activities
- [ ] **[C1/C2/C3]** PL-4: Develop and distribute rules of behavior
- [ ] **[C2/C3]** PL-4(1): Include social media and networking restrictions
- [ ] **[C2/C3]** PL-8: Develop information security architecture

## 15. Personnel Security (PS)

- [ ] **[C1/C2/C3]** PS-1: Develop personnel security policy
- [ ] **[C1/C2/C3]** PS-2: Assign risk designations to positions
- [ ] **[C1/C2/C3]** PS-3: Screen individuals prior to granting access
- [ ] **[C1/C2/C3]** PS-4: Terminate access upon personnel termination
- [ ] **[C2/C3]** PS-4(2): Automate account/access actions upon termination notification
- [ ] **[C1/C2/C3]** PS-5: Manage access during personnel transfers
- [ ] **[C1/C2/C3]** PS-6: Establish access agreements
- [ ] **[C1/C2/C3]** PS-7: Manage third-party personnel security
- [ ] **[C1/C2/C3]** PS-8: Implement personnel sanctions process

## 16. Risk Assessment (RA)

- [ ] **[C1/C2/C3]** RA-1: Develop risk assessment policy
- [ ] **[C1/C2/C3]** RA-2: Categorize information and system
- [ ] **[C1/C2/C3]** RA-3: Conduct risk assessments
- [ ] **[C1/C2/C3]** RA-5: Perform vulnerability monitoring and scanning
- [ ] **[C2/C3]** RA-5(1): Employ automated scanning tools with update capability
- [ ] **[C2/C3]** RA-5(2): Update vulnerability scan information
- [ ] **[C2/C3]** RA-5(5): Identify and authorize privileged access for scanning
- [ ] **[C2/C3]** RA-5(8): Review historic audit logs for identified vulnerabilities

## 17. System and Services Acquisition (SA)

- [ ] **[C1/C2/C3]** SA-1: Develop system and services acquisition policy
- [ ] **[C1/C2/C3]** SA-2: Allocate resources for security
- [ ] **[C1/C2/C3]** SA-3: Include security in system development life cycle
- [ ] **[C2/C3]** SA-4: Include security requirements in acquisition contracts
- [ ] **[C2/C3]** SA-4(1): Require functional properties of security controls documentation
- [ ] **[C2/C3]** SA-4(2): Require design/implementation information for security controls
- [ ] **[C2/C3]** SA-4(8): Implement continuous monitoring plan for security controls
- [ ] **[C2/C3]** SA-4(9): Require developer testing and evaluation of security controls
- [ ] **[C2/C3]** SA-4(10): Define acceptable use of approved PIV products
- [ ] **[C1/C2/C3]** SA-5: Maintain system documentation
- [ ] **[C2/C3]** SA-8: Apply security engineering principles
- [ ] **[C1/C2/C3]** SA-9: Control external system services
- [ ] **[C2/C3]** SA-9(2): Require dedicated functions for external providers
- [ ] **[C2/C3]** SA-10: Implement developer configuration management
- [ ] **[C2/C3]** SA-11: Perform developer security testing and evaluation

## 18. System and Communications Protection (SC)

- [ ] **[C1/C2/C3]** SC-1: Develop system and communications protection policy
- [ ] **[C2/C3]** SC-2: Separate application functionality from system management
- [ ] **[C1/C2/C3]** SC-5: Protect against denial of service attacks
- [ ] **[C1/C2/C3]** SC-7: Implement boundary protection
- [ ] **[C2/C3]** SC-7(3): Limit external network connections
- [ ] **[C2/C3]** SC-7(4): Allow external telecommunications only through managed interfaces
- [ ] **[C2/C3]** SC-7(5): Deny traffic by default; allow by exception
- [ ] **[C2/C3]** SC-7(7): Prevent remote devices from split tunneling
- [ ] **[C2/C3]** SC-7(8): Route traffic through managed interfaces for filtering
- [ ] **[C2/C3]** SC-7(12): Implement host-based boundary protection
- [ ] **[C2/C3]** SC-7(13): Isolate security tools from other internal components
- [ ] **[C2/C3]** SC-8: Protect confidentiality and integrity of transmitted information
- [ ] **[C2/C3]** SC-8(1): Implement cryptographic mechanisms for transmission protection
- [ ] **[C2/C3]** SC-10: Terminate network connections at end of session
- [ ] **[C2/C3]** SC-12: Establish and manage cryptographic keys
- [ ] **[C1/C2/C3]** SC-13: Use FIPS 140-2 validated cryptographic mechanisms
- [ ] **[C1/C2/C3]** SC-15: Control and restrict collaborative computing devices
- [ ] **[C2/C3]** SC-17: Issue public key certificates per certificate policy
- [ ] **[C2/C3]** SC-18: Restrict mobile code usage
- [ ] **[C2/C3]** SC-19: Control VoIP usage
- [ ] **[C1/C2/C3]** SC-20: Provide secure name/address resolution (DNSSEC)
- [ ] **[C1/C2/C3]** SC-21: Validate name/address resolution responses (DNSSEC)
- [ ] **[C1/C2/C3]** SC-22: Ensure architecture for name/address resolution is fault-tolerant
- [ ] **[C2/C3]** SC-23: Protect session authenticity
- [ ] **[C2/C3]** SC-28: Protect information at rest
- [ ] **[C2/C3]** SC-28(1): Use cryptographic mechanisms for data at rest
- [ ] **[C3]** SC-39: Process isolation

## 19. System and Information Integrity (SI)

- [ ] **[C1/C2/C3]** SI-1: Develop system and information integrity policy
- [ ] **[C1/C2/C3]** SI-2: Remediate flaws within defined timeframes
- [ ] **[C2/C3]** SI-2(2): Automate flaw remediation status tracking
- [ ] **[C2/C3]** SI-2(3): Measure time between flaw identification and remediation
- [ ] **[C1/C2/C3]** SI-3: Implement malicious code protection
- [ ] **[C2/C3]** SI-3(1): Centrally manage malicious code protection
- [ ] **[C2/C3]** SI-3(2): Automate updates to malicious code protection
- [ ] **[C1/C2/C3]** SI-4: Monitor the information system
- [ ] **[C2/C3]** SI-4(1): Implement intrusion detection/prevention system
- [ ] **[C2/C3]** SI-4(2): Automate tools for real-time analysis
- [ ] **[C2/C3]** SI-4(4): Implement inbound and outbound traffic monitoring
- [ ] **[C2/C3]** SI-4(5): Generate system alerts on indicators of compromise
- [ ] **[C1/C2/C3]** SI-5: Receive and disseminate security alerts and advisories
- [ ] **[C2/C3]** SI-6: Verify security function integrity
- [ ] **[C2/C3]** SI-7: Detect unauthorized changes to software and information
- [ ] **[C2/C3]** SI-7(1): Perform integrity checks at startup, restart, and on demand
- [ ] **[C2/C3]** SI-7(7): Detect unauthorized changes and take automated action
- [ ] **[C2/C3]** SI-8: Implement spam protection
- [ ] **[C2/C3]** SI-8(1): Centrally manage spam protection
- [ ] **[C2/C3]** SI-8(2): Automate spam protection updates
- [ ] **[C2/C3]** SI-10: Validate information inputs
- [ ] **[C2/C3]** SI-11: Generate error messages that reveal minimal information
- [ ] **[C1/C2/C3]** SI-12: Handle and retain information per policy
- [ ] **[C2/C3]** SI-16: Implement memory protection mechanisms

## 20. Supply Chain Risk Management (SR) [C3]

- [ ] **[C3]** SR-1: Develop supply chain risk management policy
- [ ] **[C3]** SR-2: Establish supply chain risk management plan
- [ ] **[C3]** SR-3: Implement supply chain controls and processes
- [ ] **[C3]** SR-5: Perform acquisition strategies, tools, and methods analysis
- [ ] **[C3]** SR-6: Assess supplier and contractor risks
- [ ] **[C3]** SR-8: Conduct component notification and disposal procedures
- [ ] **[C3]** SR-11: Establish component authenticity verification

## 21. Continuous Monitoring Requirements

- [ ] Establish continuous monitoring program per StateRAMP guidance
- [ ] Submit monthly vulnerability scan results to StateRAMP PMO
- [ ] Submit monthly POA&M updates
- [ ] Conduct and report annual security assessments
- [ ] Report significant changes within required timeframes
- [ ] Maintain up-to-date SSP reflecting all changes
- [ ] Report security incidents within StateRAMP-defined timeframes
- [ ] Conduct annual contingency plan testing
- [ ] Maintain personnel training records and currency
- [ ] Review and update policies annually (at minimum)

## 22. StateRAMP-Specific Requirements

- [ ] Register with the StateRAMP PMO
- [ ] Use StateRAMP-approved templates for documentation
- [ ] Meet StateRAMP data residency requirements (if applicable)
- [ ] Comply with StateRAMP pricing transparency requirements
- [ ] Maintain authorization status through continuous compliance
- [ ] Respond to StateRAMP PMO inquiries within defined timeframes
- [ ] Participate in annual authorization reviews

---

## Resources

- [StateRAMP Official Website](https://stateramp.org/)
- [NIST SP 800-53 Rev. 5 Control Catalog](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [FedRAMP Security Assessment Framework](https://www.fedramp.gov/documents/)
- [PTG StateRAMP Compliance Services](https://www.petronellatech.com/compliance/stateramp/)
- [PTG Compliance Packages](https://www.petronellatech.com/compliance/packages/)

**Need help implementing these controls?** Call Petronella Technology Group at 919-348-4912 or visit [https://www.petronellatech.com/compliance/packages/](https://www.petronellatech.com/compliance/packages/) to schedule a free compliance assessment.
