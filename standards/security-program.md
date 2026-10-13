# Security Program (v2019)

Referência oficial: https://apps.us.jupiterone.io/policies

## Controles e Domínios (23)

### Security Program Overview

- **cp-ism-scope**: The organization has an established security program with appropriate controls that are aligned to the organization's objectives and risk posture.
- **cp-ism-policies**: The organization's security program maintains documentation of high level policies and lower level controls and procedures. The policies and procedures cover the design, development, implementation, operation, maintenance and monitoring of in-scope systems.
- **cp-ism-reporting**: Metrics are defined to measure the effectiveness of controls and they are reported to/reviewed by senior management.

### Security Architecture and Operating Model

- **cp-model-principles**: The organization incorporates best practices such as least-privilege or zero-trust in its security operating model.
- **cp-model-architecture**: Security architecture is documented, including system and infrastructure security diagrams.
- **cp-model-metrics**: Metrics are defined to measure the effectiveness of controls and they are continuously monitored.
- **cp-model-quality**: The organization communicates its commitment to quality of service to its users and customers.

### Roles, Responsibilities and Training

- **cp-role-assignment**: Security and compliance roles and responsibilities are clearly defined to ensure segregation of duties.
- **cp-training-policy**: Employees and contractors receive training on the organization's security policies and procedures.
- **cp-training-awareness**: Employees and contractors receive ongoing security awareness training at least annually.
- **cp-training-hipaa**: Employees and contractors working with patient data and protected health information (PHI) are required to take HIPAA awareness training within 30 days of onboarding and annually thereafter.
- **cp-internal-comms**: Management and each individual department/team holds regular company-wide / departmental / team meetings to review and discuss various aspects of business performance and objectives.

### Policy Management

- **cp-policy-mgmt**: A formal process is in place to maintain and update security policies, controls and procedures. Policies, controls and procedures are reviewed at least annually.

### Risk Management and Risk Assessment Process

- **cp-risk-mgmt**: The organization has a risk management policy and defined process for managing risks - including risk identification, mitigation, monitoring, review and approval.
- **cp-risk-assess**: Risk assessments are conducted annually using a defined methodology that identifies the threat, impact, probability, actor and assets targeted/impacted.
- **cp-risk-mitigation**: A process is defined to guide the prioritization and implementation of risk mitigating controls including but not limited to controls over technology, and to evaluate residual risk.
- **cp-risk-registry**: Risks identified from each risk assessment are documented and maintained.
- **cp-risk-insurance**: The organization holds cyber liability insurance with sufficient coverage based on its risk profile
- **cp-risk-fraud**: The organization considers both financial and IT fraud risks as part of its risk assessment process, including the pressures/incentives, opportunities and rationalities of people and/or department to commit fraud.

### Compliance Audits and External Communications

- **cp-compliance-mgmt**: The organization has a program and defined process to manage compliance to applicable regulatory requirements and contractual obligations.
- **cp-compliance-requests**: Process and channels are established to communicate the compliance status to external stakeholders.
- **cp-compliance-monitor**: Compliance status is tracked and monitored using an enterprise compliance tool.

### System Audits, Monitoring and Assessments

- **cp-audit-types**: The organization has defined auditing processes including system configuration monitoring, activity monitoring, access review, and controls compliance audit.
- **cp-events-analysis**: The security team monitors system security events and logs via a combination of automated tools and manual reviews.
- **cp-audit-internal**: The organization performs manual testing and reviews of systems, accounts and controls as needed. The audit may be performed by internal teams or external auditors.
- **cp-audit-request**: A process and channels have been established for internal teams and external entities (such as a customer) to request security reviews or audits.
- **cp-audit-review**: Results of each security assessment or audit are reviewed by security team, senior management, and other designated personnel.
- **cp-audit-control-deficiency**: Identified control deficiencies are communicated to parties responsible for taking corrective action. Remediation plans are proposed and monitored through resolution.
- **cp-audit-trails**: Security events and logs from production systems and applications are captured as audit trails. Audit trails include sufficient data such as timestamp, user id, action taken to establish who did what, when, how.
- **cp-audit-trails-integrity**: Audit trails are protected against modification and unauthorized access.
- **cp-audit-customers**: The organization implements security monitors for customers and partners on its hosted software platform and/or connected environments according to terms and agreements.
- **cp-audit-tools**: A set of tools are made available for the security and compliance personnel to conduct assessments, system scans, security testing and audits.
- **cp-audit-training**: Employees and contractors are informed and trained on the organization's monitoring and auditing process.

### HR and Personnel Security

- **cp-hr-mgmt**: Organizational structure as well as individual job functions are established and communicated to all employees.
- **cp-employee-acceptable-use**: Acceptable use policy is in place to guide the organization's personnel on the proper use of information assets and their roles and responsibilities.
- **cp-employee-screening**: Interviews and background checks are conducted prior to hiring to ensure qualification and security.
- **cp-employee-onboarding**: Employee onboarding is coordinated between HR, IT and Security to ensure the appropriate training, access provisioning and system configurations are in place for each new hire.
- **cp-employee-exiting**: Employee exiting is coordinated between HR, IT and Security to ensure proper access termination and return of equipment.
- **cp-employee-escalation**: Employees are provided a safe channel and process to escalate workplace issues to HR and/or senior management if needed.
- **cp-employee-whistleblower**: Employees are provided a safe channel and process to report concerns and violations with respect to standards of business and personal ethics and conduct.
- **cp-employee-performance**: Performance reviews are conducted annually to evaluate performance of employees against expected levels.
- **cp-employee-recognition**: Employees receive regular peer recognition, feedback and rewards for positive behavior and impact.
- **cp-employee-development**: The organization provides employees the opportunity to attend conferences, trade shows, and access to training courses and studies to maintain and further advance their skills relevant to their job functions and business objectives.
- **cp-sanctions**: Policies and processes are in place to investigate and take appropriate actions on any non-compliance to the organization's policies and procedures.

### Access

- **cp-access-standards**: The organization incorporates security best practices and standards for provisioning access including unqiue user identification, automatic logoff, and least-privileged access.
- **cp-access-password**: Strong password management policy is in place.
- **cp-access-sso**: Access to business systems and applications is centrally managed via single sign on (SSO) when possible.
- **cp-access-mfa**: Multi-factor authentication (MFA) is required for all users with access to business critical systems.
- **cp-access-rbac**: Access to systems and applications are provisioned based on a user's role / group.
- **cp-access-aws**: Access to AWS cloud infrastructure is configured single sign on roles and temporary trusts. No persistent end-user access is configured.
- **cp-access-vpn**: Remote access to private and internal systems are configured via encrypted VPN channels.
- **cp-access-phi**: Access to PHI/ePHI is restricted to only individuals with business need and protected by strong access control.
- **cp-access-customer**: Customers are granted access to their accounts and data only after successful authentication and authorization through the appropriate applications, either through the web interface or API.
- **cp-access-change**: Changes to pre-established access (configured as part of onboarding) must be requested and approved by the employee's manager or security team prior to granting access. Non-standard access is revoked when no longer needed.
- **cp-access-review**: User access permissions are reviewed as part of ongoing security monitoring and whenever an employee's role changes.
- **cp-access-privileged**: Privileged access to production systems and/or data must be requested, reviewed, and approved each time. Privileged access is granted on a temporary basis, typically no more than 24 hours.
- **cp-access-service**: Service accounts and application credentials are securely managed.
- **cp-access-endpoints**: The organization provides standard endpoint computing devices to employees that are configured according to company security standards, including disk encryption, host firewall, malware protection, and malicious activity detection.
- **cp-access-wifi**: Office networks, including wireless access, are protected for internal business use only. Guest wireless access is provided on a separate logical network.
- **cp-access-prod**: Production keys and secrets are securely stored and protected.
- **cp-access-prod-data**: Access to production data is highly restricted. Access is reviewed and approved on a case-by-case basis. MFA is required.
- **cp-access-reset**: Users are provided a self-service mechanism for account access resets, and a channel to open an internal IT support request if needed.

### Facility Access and Physical Security

- **cp-physical**: 
- **cp-physical-datacenter**: Data center security is ensured by the cloud service provider.

### Asset Inventory Management

- **cp-asset-physical**: All physical computing and information processing assets, such as laptops and workstations, are maintained in an asset inventory system.
- **cp-asset-digital**: All digital and software-defined assets, such as virtual instances and code repositories, are discovered and maintained in an asset inventory system.
- **cp-asset-paper**: All records are kept electronically, no physical paper records are kept as part of core business operations.

### Data Management

- **cp-data-classification**: Data classification model is defined to differentiate public, non-public, confidental/sensitive and critical data or information asset.
- **cp-data-handling**: Data is handled according to its classification, including defined requirements for labeling, encryption, access control, retention and other applicable processes.
- **cp-data-lifecycle**: Data is tagged according to its classification, and its lifecycle is defined. Transient and temporary data (or cache) is purged immediately after use.
- **cp-data-backup**: All data critical to business operations, including customer data, source codes, business records and documents are backed up and fully recoverable.
- **cp-data-deletion**: Data is retained for designated periods of time according to regulatory and/or contractual requirements, and deleted when the retention period expires.

### Data Protection

- **cp-data-protection**: Data is protected according to its classification and storage capability, including encryption, access control, partitioning/separation, backup/recovery, and monitoring.
- **cp-data-protection-at-rest**: Sensitive and confidential data is encrypted when stored.
- **cp-data-protection-in-transit**: Sensitive and confidential data is encrypted when transmitted across networks.
- **cp-data-protection-in-use**: Audit trail is enabled to monitor data access when in use.
- **cp-data-protection-kms**: Encryption key management process is implemented.
- **cp-data-protection-cert**: Certificate management process is in place to manage the lifecycle of web certificates (SSL/TLS) and application certificates.
- **cp-data-protection-integrity**: Data versioning, access control, auditing and deletion prevention is in place to protect the integrity of data, when appropriate.

### Secure Software Development and Product Security

- **cp-sdlc-dev**: A secure software development process, coding standards, and release strategy is established to ensure security is built-in to the products and applications.
- **cp-sdlc-scm**: Source code management system with version control is used to maintain software codes
- **cp-sdlc-appsec-req**: Application security requirements are defined following OWASP Top Ten best practices.
- **cp-sdlc-design**: Security considerations are mandatory as part of new system design and feature development. Threat modeling is jointly performed by security and development teams as needed.
- **cp-sdlc-iaaa**: All external facing applications are required to have appropriate access control implementation to protect non-public user data.
- **cp-sdlc-foss**: A code analysis tool is in place to analyze open source components for potential security vulnerabilities and licensing issues.
- **cp-sdlc-sast**: Static code scanning is performed automatically either as part of the DevOps pipeline or on a regular schedule to detect common flaws in code patterns, such as injection flaws, buffer overflows, and leaked secrets/credentials in code.
- **cp-sdlc-dast**: Dynamic application scanning is performed by the security team.
- **cp-sdlc-pentest**: Penetration testing is performed for each product at least annually and with major feature changes.
- **cp-sdlc-bugbounty**: Security team maintains an external/public bug bounty program to enable continuous security testing and vulnerability reporting across major external facing products.
- **cp-sdlc-outsourcing**: Software development performed by contractors or outsourced vendors follow the same secure development standards and requirements.
- **cp-sdlc-hipaa**: Developers are trained on requirements and best practices specific to HIPAA compliance and processing of sensitive health data.
- **cp-sdlc-monitor**: On call teams are set up to receive pager notifications when a failure or error occurs in production.

### Configuration and Change Management

- **cp-ccm-config**: Configuration management processes are in place to provision systems and environments according to approved security standards.
- **cp-ccm-monitor**: Monitoring software is used to monitor infrastructure and software for noncompliance with established configuration standards and security best practices.
- **cp-ccm-provision-prod**: Provisioning of any production system or resource requires a change request that is reviewed and approved by both engineering and security.
- **cp-ccm-provision-endpoint**: End-user computing systems are configured with required baseline security controls including disk encyrption, unique user account and strong password policy, host firewall, screenlock protection, auto-update of security patches, and endpoint security agent for configuration monitoring and malware protection.
- **cp-ccm-provision-server**: Server systems are provisioned using pre-approved configurations or images approved by the security team.
- **cp-ccm-provision-mgmt**: System management tools are provisioned following the same requirements and configurations as any production system.
- **cp-ccm-network**: Network devices are configured to remove vendor default security configurations. Network layer security controls are in place to enable traffic filtering/monitoring for applicable environments.
- **cp-ccm-aws**: AWS configuration is maintained as code and provisioned via automated code deploys.
- **cp-ccm-aws-deploy**: Cloud infrastructure changes and software code deploys follow a defined change request process with automated and/or manual reviews and approvals.
- **cp-ccm-patch**: Operating systems on both end-user computing devices and server systems are required to maintain up-to-date security patches in an automated process.
- **cp-ccm-prodcm**: Code deploys to production require an approved change ticket with sufficent details about the code change.
- **cp-ccm-emergency**: An emergency change process is in place for break-glass procedure. Details of any emergency change are retroactively documented and approved.

### Threat Detection and Prevention

- **cp-threat-malware**: Malware protection agent is installed and activated at all times on endpoint devices.
- **cp-threat-firewall**: Firewall protection is enabled across network, host, and application layer.
- **cp-threat-nids**: Network layer intrusion detection system is implemented.
- **cp-threat-hids**: Host instrusion detection and malicious activity monitoring agents are installed on endpoint hosts and servers.
- **cp-threat-webapp**: Web application firewall and denial-of-service protection is enabled for external facing applications.
- **cp-threat-siem**: Security events are logged and alerts are centrally aggregated for review and remediation.
- **cp-threat-intel**: The security team subscribes to news, feeds, forums and special interests groups to receive updates on threat intel and updates on applicable regulations and compliance.

### Vulnerability Management

- **cp-vuln-scan**: Vulnerability scan is performed at least quarterly for all production systems.
- **cp-vuln-remediation**: All security vulnerability and findings (for both infrastructure and software) are prioritized and remediated based on its severity and impact, with a defined SLA.

### Mobile Device Security and Media Management

- **cp-mdm-disposal**: Media containing critical / sensitive data (such as PII or ePHI) is disposed securely.
- **cp-mdm-usb**: Use of USB flash drive or similar removable storage device to store sensitive and critical data is prohibited and must be handled on an exception basis approved by security.
- **cp-mdm-byod**: BYOD devices are not allowed to connect to production environments containing critical data.

### Business Continuity and Disaster Recovery

- **cp-bcdr**: Management team develops contingency plans for assignment of responsibility for internal controls with clear objectives and roles.
- **cp-bcdr-recovery**: Disaster recovery procedures are defined to cover activation, recovery and reconstitution of critical controls and resources.
- **cp-bcdr-test**: Disaster recovery is tested annually via tabletop exercise and/or simulated tests.
- **cp-bcdr-site**: Remote working arrangements are in place.
- **cp-bcdr-app**: External applications are monitored for service interruptions or outages, and handled according to the impact and downtime of such events. Status page is set up for communicating any outage to customers.
- **cp-bcdr-data**: All resources and data from production environments are able to be reconstructed from code and recovered from backup.

### Incident Response

- **cp-ir-sirt**: Incident response team is established and assigned corresponding responsibilities.
- **cp-ir-process**: Incident response / escalation policies and processes are in place for incident reporting, triage, eradication, recovery, and postmortem analysis.
- **cp-ir-playbook**: Incident playbooks are created with detailed technical procedures to guide personnel in incident handling according to the incident classification and severity.
- **cp-ir-emergency**: Emergency operation procedure is in place to enable temporary break-glass operations when necessary.
- **cp-ir-tabletop**: Tabletop exercises and/or simulated incident drills are performed at least annually to validate and update the incident response process.
- **cp-ir-records**: Each incident is tracked with applicable attributes and notes, and the incident records are stored in an approved ticketing system.

### Breach Investigation and Notification

- **cp-breach-investigate**: Investigation and notification process is in place to handle suspected and/or confirmed data breaches.
- **cp-breach-customer**: Customer responsibilities are defined in the case of a breach related to or resulted from customer activities.
- **cp-breach-letter**: Communication template is in place for external notification of a breach.
- **cp-breach-authorities**: Data protection and privacy regulatory authority contacts are documented for timely response.

### Third Party Security and Vendor Risk Management

- **cp-vendor-vtr**: Risk assessments are conducted prior to engaging a new technology vendor.
- **cp-vendor-contracts**: Third party vendors are required to sign applicale contractual agreements, such as BAA (for HIPAA), DPA (for GDPR), SLA (for service providers), accepting their responsibilities to meet applicable data protection and privacy requirements.
- **cp-vendor-monitor**: Security and DevOps teams continue to monitor the risk levels and service status of applicable vendors, such as service providers and vendors with access to sensitive data.
- **cp-vendor-ssa**: A list of approved software applications and system vendors are in place, with approval process defined for additional acquisition requests.

### Privacy Practice and Consent

- **cp-privacy-notices**: The organization has published privacy policy and established user consent process for data processing, in line with applicable regulations.

