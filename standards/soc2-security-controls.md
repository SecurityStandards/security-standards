# SOC 2 Security (vAICPA 2017)

Referência oficial: https://www.aicpa.org/content/dam/aicpa/interestareas/frc/assuranceadvisoryservices/downloadabledocuments/trust-services-criteria.pdf

## Controles e Domínios (33)

### § Control Environment
【CC1.1】 The entity demonstrates a commitment to integrity and ethical values.

- **cp-employee-acceptable-use**: Acceptable use policy is in place to guide the organization's personnel on the proper use of information assets and their roles and responsibilities.
- **cp-employee-onboarding**: Employee onboarding is coordinated between HR, IT and Security to ensure the appropriate training, access provisioning and system configurations are in place for each new hire.
- **cp-employee-screening**: Interviews and background checks are conducted prior to hiring to ensure qualification and security.
- **cp-policy-mgmt**: A formal process is in place to maintain and update security policies, controls and procedures. Policies, controls and procedures are reviewed at least annually.
- **cp-sanctions**: Policies and processes are in place to investigate and take appropriate actions on any non-compliance to the organization's policies and procedures.
- **cp-training-policy**: Employees and contractors receive training on the organization's security policies and procedures.

### § Control Environment
【CC1.2】 The board of directors demonstrates independence from management and exercises oversight of the development and performance of internal control.


### § Control Environment
【CC1.3】 Management establishes, with board oversight, structures, reporting lines, and appropriate authorities and responsibilities in the pursuit of objectives.

- **cp-ism-scope**: The organization has an established security program with appropriate controls that are aligned to the organization's objectives and risk posture.
- **cp-ism-policies**: The organization's security program maintains documentation of high level policies and lower level controls and procedures. The policies and procedures cover the design, development, implementation, operation, maintenance and monitoring of in-scope systems.
- **cp-ism-reporting**: Metrics are defined to measure the effectiveness of controls and they are reported to/reviewed by senior management.
- **cp-role-assignment**: Security and compliance roles and responsibilities are clearly defined to ensure segregation of duties.
- **cp-hr-mgmt**: Organizational structure as well as individual job functions are established and communicated to all employees.
- **cp-vendor-vtr**: Risk assessments are conducted prior to engaging a new technology vendor.
- **cp-vendor-contracts**: Third party vendors are required to sign applicable contractual agreements, such as BAA (for HIPAA), DPA (for GDPR), SLA (for service providers), accepting their responsibilities to meet applicable data protection and privacy requirements.

### § Control Environment
【CC1.4】 The entity demonstrates a commitment to attract, develop, and retain competent individuals in alignment with objectives.

- **cp-employee-onboarding**: Employee onboarding is coordinated between HR, IT and Security to ensure the appropriate training, access provisioning and system configurations are in place for each new hire.
- **cp-employee-screening**: Interviews and background checks are conducted prior to hiring to ensure qualification and security.
- **cp-employee-development**: The organization provides employees the opportunity to attend conferences, trade shows, and access to training courses and studies to maintain and further advance their skills relevant to their job functions and business objectives.
- **cp-employee-recognition**: Employees receive regular peer recognition, feedback and rewards for positive behavior and impact.
- **cp-training-awareness**: Employees and contractors receive ongoing security awareness training at least annually.
- **cp-training-hipaa**: Employees and contractors working with patient data and protected health information (PHI) are required to take HIPAA awareness training within 30 days of onboarding and annually thereafter.
- **cp-training-policy**: Employees and contractors receive training on the organization's security policies and procedures.
- **cp-bcdr**: Management team develops contingency plans for assignment of responsibility for internal controls with clear objectives and roles.

### § Control Environment
【CC1.5】 The entity holds individuals accountable for their internal control responsibilities in the pursuit of objectives.

- **cp-hr-mgmt**: Organizational structure as well as individual job functions are established and communicated to all employees.
- **cp-role-assignment**: Security and compliance roles and responsibilities are clearly defined to ensure segregation of duties.
- **cp-employee-performance**: Performance reviews are conducted annually to evaluate performance of employees against expected levels.
- **cp-internal-comms**: Management and each individual department/team holds regular company-wide / departmental / team meetings to review and discuss various aspects of business performance and objectives.

### § Communication And Information
【CC2.1】 The entity obtains or generates and uses relevant, quality information to support the functioning of internal control.

- **cp-data-classification**: Data classification model is defined to differentiate public, non-public, confidential/sensitive and critical data or information asset.
- **cp-data-handling**: Data is handled according to its classification, including defined requirements for labeling, encryption, access control, retention and other applicable processes.
- **cp-data-lifecycle**: Data is tagged according to its classification, and its lifecycle is defined. Transient and temporary data (or cache) is purged immediately after use.
- **cp-data-protection**: Data is protected according to its classification and storage capability, including encryption, access control, partitioning/separation, backup/recovery, and monitoring.
- **cp-audit-trails**: Security events and logs from production systems and applications are captured as audit trails. Audit trails include sufficient data such as timestamp, user id, action taken to establish who did what, when, how.
- **cp-audit-trails-integrity**: Audit trails are protected against modification and unauthorized access.
- **cp-audit-types**: The organization has defined auditing processes including system configuration monitoring, activity monitoring, access review, and controls compliance audit.
- **cp-events-analysis**: The security team monitors system security events and logs via a combination of automated tools and manual reviews.
- **cp-threat-intel**: The security team subscribes to news, feeds, forums and special interests groups to receive updates on threat intel and updates on applicable regulations and compliance.
- **cp-threat-siem**: Security events are logged and alerts are centrally aggregated for review and remediation.
- **cp-risk-assess**: Risk assessments are conducted annually using a defined methodology that identifies the threat, impact, probability, actor and assets targeted/impacted.
- **cp-ccm-config**: Configuration management processes are in place to provision systems and environments according to approved security standards.
- **cp-vuln-scan**: Vulnerability scan is performed at least quarterly for all production systems.
- **cp-vuln-remediation**: All security vulnerability and findings (for both infrastructure and software) are prioritized and remediated based on its severity and impact, with a defined SLA.
- **cp-sdlc-pentest**: Penetration testing is performed for each product at least annually and with major feature changes.
- **cp-sdlc-bugbounty**: Security team maintains an external/public bug bounty program to enable continuous security testing and vulnerability reporting across major external facing products.
- **cp-model-metrics**: Metrics are defined to measure the effectiveness of controls and they are continuously monitored.

### § Communication And Information
【CC2.2】 The entity internally communicates information, including objectives and responsibilities for internal control, necessary to support the functioning of internal control.

- **cp-employee-onboarding**: Employee onboarding is coordinated between HR, IT and Security to ensure the appropriate training, access provisioning and system configurations are in place for each new hire.
- **cp-model-architecture**: Security architecture is documented, including system and infrastructure security diagrams.
- **cp-model-principles**: The organization incorporates best practices such as least-privilege or zero-trust in its security operating model.
- **cp-model-quality**: The organization communicates its commitment to quality of service to its users and customers.
- **cp-policy-mgmt**: A formal process is in place to maintain and update security policies, controls and procedures. Policies, controls and procedures are reviewed at least annually.
- **cp-risk-mgmt**: The organization has a risk management policy and defined process for managing risks - including risk identification, mitigation, monitoring, review and approval.
- **cp-risk-mitigation**: A process is defined to guide the prioritization and implementation of risk mitigating controls including but not limited to controls over technology, and to evaluate residual risk.
- **cp-role-assignment**: Security and compliance roles and responsibilities are clearly defined to ensure segregation of duties.
- **cp-internal-comms**: Management and each individual department/team holds regular company-wide / departmental / team meetings to review and discuss various aspects of business performance and objectives.
- **cp-training-awareness**: Employees and contractors receive ongoing security awareness training at least annually.
- **cp-training-hipaa**: Employees and contractors working with patient data and protected health information (PHI) are required to take HIPAA awareness training within 30 days of onboarding and annually thereafter.
- **cp-training-policy**: Employees and contractors receive training on the organization's security policies and procedures.
- **cp-ir-playbook**: Incident playbooks are created with detailed technical procedures to guide personnel in incident handling according to the incident classification and severity.
- **cp-ir-process**: Incident response / escalation policies and processes are in place for incident reporting, triage, eradication, recovery, and postmortem analysis.
- **cp-ir-sirt**: Incident response team is established and assigned corresponding responsibilities.

### § Communication And Information
【CC2.3】 The entity communicates with external parties regarding matters affecting the functioning of internal control.

- **cp-model-quality**: The organization communicates its commitment to quality of service to its users and customers.
- **cp-compliance-mgmt**: The organization has a program and defined process to manage compliance to applicable regulatory requirements and contractual obligations.
- **cp-compliance-requests**: Process and channels are established to communicate the compliance status to external stakeholders.
- **cp-breach-investigate**: Investigation and notification process is in place to handle suspected and/or confirmed data breaches.
- **cp-privacy-notices**: The organization has published privacy policy and established user consent process for data processing, in line with applicable regulations.
- **cp-vendor-contracts**: Third party vendors are required to sign applicable contractual agreements, such as BAA (for HIPAA), DPA (for GDPR), SLA (for service providers), accepting their responsibilities to meet applicable data protection and privacy requirements.

### § Risk Assessment
【CC3.1】 The entity specifies objectives with sufficient clarity to enable the identification and assessment of risks relating to objectives.

- **cp-ism-scope**: The organization has an established security program with appropriate controls that are aligned to the organization's objectives and risk posture.
- **cp-risk-mgmt**: The organization has a risk management policy and defined process for managing risks - including risk identification, mitigation, monitoring, review and approval.
- **cp-risk-assess**: Risk assessments are conducted annually using a defined methodology that identifies the threat, impact, probability, actor and assets targeted/impacted.
- **cp-risk-mitigation**: A process is defined to guide the prioritization and implementation of risk mitigating controls including but not limited to controls over technology, and to evaluate residual risk.
- **cp-risk-registry**: Risks identified from each risk assessment are documented and maintained.

### § Risk Assessment
【CC3.2】 The entity identifies risks to the achievement of its objectives across the entity and analyzes risks as a basis for determining how the risks should be managed.

- **cp-risk-mgmt**: The organization has a risk management policy and defined process for managing risks - including risk identification, mitigation, monitoring, review and approval.
- **cp-risk-assess**: Risk assessments are conducted annually using a defined methodology that identifies the threat, impact, probability, actor and assets targeted/impacted.
- **cp-risk-mitigation**: A process is defined to guide the prioritization and implementation of risk mitigating controls including but not limited to controls over technology, and to evaluate residual risk.
- **cp-asset-physical**: All physical computing and information processing assets, such as laptops and workstations, are maintained in an asset inventory system.
- **cp-asset-digital**: All digital and software-defined assets, such as virtual instances and code repositories, are discovered and maintained in an asset inventory system.
- **cp-vendor-ssa**: A list of approved software applications and system vendors are in place, with approval process defined for additional acquisition requests.
- **cp-vendor-vtr**: Risk assessments are conducted prior to engaging a new technology vendor.

### § Risk Assessment
【CC3.3】 The entity considers the potential for fraud in assessing risks to the achievement of objectives.

- **cp-risk-fraud**: The organization considers both financial and IT fraud risks as part of its risk assessment process, including the pressures/incentives, opportunities and rationalities of people and/or department to commit fraud.

### § Risk Assessment
【CC3.4】 The entity identifies and assesses changes that could significantly impact the system of internal control.

- **cp-threat-intel**: The security team subscribes to news, feeds, forums and special interests groups to receive updates on threat intel and updates on applicable regulations and compliance.
- **cp-bcdr**: Management team develops contingency plans for assignment of responsibility for internal controls with clear objectives and roles.

### § Monitoring Activities
【CC4.1】 The entity selects, develops, and performs ongoing and/or separate evaluations to ascertain whether the components of internal control are present and functioning.

- **cp-ism-reporting**: Metrics are defined to measure the effectiveness of controls and they are reported to/reviewed by senior management.
- **cp-model-metrics**: Metrics are defined to measure the effectiveness of controls and they are continuously monitored.
- **cp-audit-internal**: The organization performs manual testing and reviews of systems, accounts and controls as needed. The audit may be performed by internal teams or external auditors.
- **cp-audit-request**: A process and channels have been established for internal teams and external entities (such as a customer) to request security reviews or audits.
- **cp-audit-review**: Results of each security assessment or audit are reviewed by security team, senior management, and other designated personnel.
- **cp-audit-tools**: A set of tools are made available for the security and compliance personnel to conduct assessments, system scans, security testing and audits.
- **cp-audit-trails**: Security events and logs from production systems and applications are captured as audit trails. Audit trails include sufficient data such as timestamp, user id, action taken to establish who did what, when, how.
- **cp-audit-trails-integrity**: Audit trails are protected against modification and unauthorized access.
- **cp-audit-training**: Employees and contractors are informed and trained on the organization's monitoring and auditing process.
- **cp-audit-types**: The organization has defined auditing processes including system configuration monitoring, activity monitoring, access review, and controls compliance audit.
- **cp-vuln-scan**: Vulnerability scan is performed at least quarterly for all production systems.
- **cp-sdlc-pentest**: Penetration testing is performed for each product at least annually and with major feature changes.
- **cp-sdlc-bugbounty**: Security team maintains an external/public bug bounty program to enable continuous security testing and vulnerability reporting across major external facing products.

### § Monitoring Activities
【CC4.2】 The entity evaluates and communicates internal control deficiencies in a timely manner to those parties responsible for taking corrective action, including senior management and the board of directors, as appropriate.

- **cp-ism-reporting**: Metrics are defined to measure the effectiveness of controls and they are reported to/reviewed by senior management.
- **cp-model-metrics**: Metrics are defined to measure the effectiveness of controls and they are continuously monitored.
- **cp-audit-review**: Results of each security assessment or audit are reviewed by security team, senior management, and other designated personnel.
- **cp-audit-control-deficiency**: Identified control deficiencies are communicated to parties responsible for taking corrective action. Remediation plans are proposed and monitored through resolution.
- **cp-vuln-remediation**: All security vulnerability and findings (for both infrastructure and software) are prioritized and remediated based on its severity and impact, with a defined SLA.
- **cp-model-metrics**: Metrics are defined to measure the effectiveness of controls and they are continuously monitored.
- **cp-ism-reporting**: Metrics are defined to measure the effectiveness of controls and they are reported to/reviewed by senior management.
- **cp-ccm-monitor**: Monitoring software is used to monitor infrastructure and software for noncompliance with established configuration standards and security best practices.
- **cp-sdlc-monitor**: On call teams are set up to receive pager notifications when a failure or error occurs in production.
- **cp-compliance-monitor**: Compliance status is tracked and monitored using an enterprise compliance tool.

### § Control Activities
【CC5.1】 The entity selects and develops control activities that contribute to the mitigation of risks to the achievement of objectives to acceptable levels.

- **cp-risk-assess**: Risk assessments are conducted annually using a defined methodology that identifies the threat, impact, probability, actor and assets targeted/impacted.
- **cp-risk-mgmt**: The organization has a risk management policy and defined process for managing risks - including risk identification, mitigation, monitoring, review and approval.
- **cp-risk-mitigation**: A process is defined to guide the prioritization and implementation of risk mitigating controls including but not limited to controls over technology, and to evaluate residual risk.
- **cp-risk-registry**: Risks identified from each risk assessment are documented and maintained.

### § Control Activities
【CC5.2】 The entity also selects and develops general control activities over technology to support the achievement of objectives.

- **cp-risk-assess**: Risk assessments are conducted annually using a defined methodology that identifies the threat, impact, probability, actor and assets targeted/impacted.
- **cp-risk-mgmt**: The organization has a risk management policy and defined process for managing risks - including risk identification, mitigation, monitoring, review and approval.
- **cp-risk-mitigation**: A process is defined to guide the prioritization and implementation of risk mitigating controls including but not limited to controls over technology, and to evaluate residual risk.
- **cp-risk-registry**: Risks identified from each risk assessment are documented and maintained.

### § Control Activities
【CC5.3】 The entity deploys control activities through policies that establish what is expected and in procedures that put policies into action.

- **cp-ism-scope**: The organization has an established security program with appropriate controls that are aligned to the organization's objectives and risk posture.
- **cp-ism-policies**: The organization's security program maintains documentation of high level policies and lower level controls and procedures. The policies and procedures cover the design, development, implementation, operation, maintenance and monitoring of in-scope systems.
- **cp-policy-mgmt**: A formal process is in place to maintain and update security policies, controls and procedures. Policies, controls and procedures are reviewed at least annually.

### § Logical And Physical Access Controls
【CC6.1】 The entity implements logical access security software, infrastructure, and architectures over protected information assets to protect them from security events to meet the entity's objectives.

- **cp-asset-digital**: All digital and software-defined assets, such as virtual instances and code repositories, are discovered and maintained in an asset inventory system.
- **cp-access-aws**: Access to AWS cloud infrastructure is configured single sign on roles and temporary trusts. No persistent end-user access is configured.
- **cp-access-customer**: Customers are granted access to their accounts and data only after successful authentication and authorization through the appropriate applications, either through the web interface or API.
- **cp-access-mfa**: Multi-factor authentication (MFA) is required for all users with access to business critical systems.
- **cp-access-password**: Strong password management policy is in place.
- **cp-access-phi**: Access to PHI/ePHI is restricted to only individuals with business need and protected by strong access control.
- **cp-access-rbac**: Access to systems and applications are provisioned based on a user's role / group.
- **cp-access-service**: Service accounts and application credentials are securely managed.
- **cp-access-sso**: Access to business systems and applications is centrally managed via single sign on (SSO) when possible.
- **cp-access-standards**: The organization incorporates security best practices and standards for provisioning access including unique user identification, automatic logoff, and least-privileged access.
- **cp-access-vpn**: Remote access to private and internal systems are configured via encrypted VPN channels.
- **cp-access-wifi**: Office networks, including wireless access, are protected for internal business use only. Guest wireless access is provided on a separate logical network.
- **cp-access-prod**: Production keys and secrets are securely stored and protected.
- **cp-access-prod-data**: Access to production data is highly restricted. Access is reviewed and approved on a case-by-case basis. MFA is required.
- **cp-threat-firewall**: Firewall protection is enabled across network, host, and application layer.
- **cp-threat-nids**: Network layer intrusion detection system is implemented.
- **cp-threat-hids**: Host intrusion detection and malicious activity monitoring agents are installed on endpoint hosts and servers.
- **cp-threat-webapp**: Web application firewall and denial-of-service protection is enabled for external facing applications.
- **cp-data-lifecycle**: Data is tagged according to its classification, and its lifecycle is defined. Transient and temporary data (or cache) is purged immediately after use.
- **cp-data-protection**: Data is protected according to its classification and storage capability, including encryption, access control, partitioning/separation, backup/recovery, and monitoring.
- **cp-data-protection-at-rest**: Sensitive and confidential data is encrypted when stored.
- **cp-data-protection-in-transit**: Sensitive and confidential data is encrypted when transmitted across networks.
- **cp-employee-acceptable-use**: Acceptable use policy is in place to guide the organization's personnel on the proper use of information assets and their roles and responsibilities.

### § Logical And Physical Access Controls
【CC6.2】 Prior to issuing system credentials and granting system access, the entity registers and authorizes new internal and external users whose access is administered by the entity. For those users whose access is administered by the entity, user system credentials are removed when user access is no longer authorized.

- **cp-access-change**: Changes to pre-established access (configured as part of onboarding) must be requested and approved by the employee's manager or security team prior to granting access. Non-standard access is revoked when no longer needed.
- **cp-access-review**: User access permissions are reviewed as part of ongoing security monitoring and whenever an employee's role changes.
- **cp-audit-internal**: The organization performs manual testing and reviews of systems, accounts and controls as needed. The audit may be performed by internal teams or external auditors.
- **cp-audit-types**: The organization has defined auditing processes including system configuration monitoring, activity monitoring, access review, and controls compliance audit.
- **cp-employee-exiting**: Employee exiting is coordinated between HR, IT and Security to ensure proper access termination and return of equipment.
- **cp-employee-onboarding**: Employee onboarding is coordinated between HR, IT and Security to ensure the appropriate training, access provisioning and system configurations are in place for each new hire.
- **cp-vendor-ssa**: A list of approved software applications and system vendors are in place, with approval process defined for additional acquisition requests.

### § Logical And Physical Access Controls
【CC6.3】 The entity authorizes, modifies, or removes access to data, software, functions, and other protected information assets based on roles, responsibilities, or the system design and changes, giving consideration to the concepts of least privilege and segregation of duties, to meet the entity’s objectives.

- **cp-access-standards**: The organization incorporates security best practices and standards for provisioning access including unique user identification, automatic logoff, and least-privileged access.
- **cp-access-change**: Changes to pre-established access (configured as part of onboarding) must be requested and approved by the employee's manager or security team prior to granting access. Non-standard access is revoked when no longer needed.
- **cp-access-phi**: Access to PHI/ePHI is restricted to only individuals with business need and protected by strong access control.
- **cp-access-rbac**: Access to systems and applications are provisioned based on a user's role / group.
- **cp-access-service**: Service accounts and application credentials are securely managed.
- **cp-access-prod-data**: Access to production data is highly restricted. Access is reviewed and approved on a case-by-case basis. MFA is required.
- **cp-ccm-aws**: AWS configuration is maintained as code and provisioned via automated code deploys.
- **cp-data-protection**: Data is protected according to its classification and storage capability, including encryption, access control, partitioning/separation, backup/recovery, and monitoring.
- **cp-employee-exiting**: Employee exiting is coordinated between HR, IT and Security to ensure proper access termination and return of equipment.
- **cp-model-principles**: The organization incorporates best practices such as least-privilege or zero-trust in its security operating model.
- **cp-sdlc-iaaa**: All external facing applications are required to have appropriate access control implementation to protect non-public user data.

### § Logical And Physical Access Controls
【CC6.4】 The entity restricts physical access to facilities and protected information assets (for example, data center facilities,  back-up media storage, and other sensitive locations) to authorized personnel to meet the entity’s objectives.

- **cp-physical**: 
- **cp-physical-datacenter**: Data center security is ensured by the cloud service provider.
- **cp-employee-exiting**: Employee exiting is coordinated between HR, IT and Security to ensure proper access termination and return of equipment.

### § Logical And Physical Access Controls
【CC6.5】 The entity discontinues logical and physical protections over physical assets only after the ability to read or recover data and software from those assets has been diminished and is no longer required to meet the entity’s objectives.

- **cp-asset-physical**: All physical computing and information processing assets, such as laptops and workstations, are maintained in an asset inventory system.
- **cp-data-deletion**: Data is retained for designated periods of time according to regulatory and/or contractual requirements, and deleted when the retention period expires.
- **cp-data-handling**: Data is handled according to its classification, including defined requirements for labeling, encryption, access control, retention and other applicable processes.
- **cp-data-lifecycle**: Data is tagged according to its classification, and its lifecycle is defined. Transient and temporary data (or cache) is purged immediately after use.
- **cp-mdm-disposal**: Media containing critical / sensitive data (such as PII or ePHI) is disposed securely.
- **cp-mdm-usb**: Use of USB flash drive or similar removable storage device to store sensitive and critical data is prohibited and must be handled on an exception basis approved by security.

### § Logical And Physical Access Controls
【CC6.6】 The entity implements logical access security measures to protect against threats from sources outside its system boundaries.

- **cp-access-aws**: Access to AWS cloud infrastructure is configured single sign on roles and temporary trusts. No persistent end-user access is configured.
- **cp-access-mfa**: Multi-factor authentication (MFA) is required for all users with access to business critical systems.
- **cp-access-service**: Service accounts and application credentials are securely managed.
- **cp-access-standards**: The organization incorporates security best practices and standards for provisioning access including unique user identification, automatic logoff, and least-privileged access.
- **cp-access-vpn**: Remote access to private and internal systems are configured via encrypted VPN channels.
- **cp-access-wifi**: Office networks, including wireless access, are protected for internal business use only. Guest wireless access is provided on a separate logical network.
- **cp-data-protection-in-transit**: Sensitive and confidential data is encrypted when transmitted across networks.
- **cp-sdlc-iaaa**: All external facing applications are required to have appropriate access control implementation to protect non-public user data.
- **cp-threat-firewall**: Firewall protection is enabled across network, host, and application layer.
- **cp-threat-hids**: Host intrusion detection and malicious activity monitoring agents are installed on endpoint hosts and servers.
- **cp-threat-nids**: Network layer intrusion detection system is implemented.

### § Logical And Physical Access Controls
【CC6.7】 The entity restricts the transmission, movement, and removal of information to authorized internal and external users and processes, and protects it during transmission, movement, or removal to meet the entity’s objectives.

- **cp-access-vpn**: Remote access to private and internal systems are configured via encrypted VPN channels.
- **cp-access-prod-data**: Access to production data is highly restricted. Access is reviewed and approved on a case-by-case basis. MFA is required.
- **cp-data-classification**: Data classification model is defined to differentiate public, non-public, confidential/sensitive and critical data or information asset.
- **cp-data-handling**: Data is handled according to its classification, including defined requirements for labeling, encryption, access control, retention and other applicable processes.
- **cp-data-lifecycle**: Data is tagged according to its classification, and its lifecycle is defined. Transient and temporary data (or cache) is purged immediately after use.
- **cp-data-protection**: Data is protected according to its classification and storage capability, including encryption, access control, partitioning/separation, backup/recovery, and monitoring.
- **cp-data-protection-at-rest**: Sensitive and confidential data is encrypted when stored.
- **cp-data-protection-in-transit**: Sensitive and confidential data is encrypted when transmitted across networks.
- **cp-data-protection-in-use**: Audit trail is enabled to monitor data access when in use.
- **cp-employee-acceptable-use**: Acceptable use policy is in place to guide the organization's personnel on the proper use of information assets and their roles and responsibilities.
- **cp-mdm-byod**: BYOD devices are not allowed to connect to production environments containing critical data.
- **cp-mdm-disposal**: Media containing critical / sensitive data (such as PII or ePHI) is disposed securely.
- **cp-mdm-usb**: Use of USB flash drive or similar removable storage device to store sensitive and critical data is prohibited and must be handled on an exception basis approved by security.

### § Logical And Physical Access Controls
【CC6.8】 The entity implements controls to prevent or detect and act upon the introduction of unauthorized or malicious software to meet the entity’s objectives.

- **cp-ccm-config**: Configuration management processes are in place to provision systems and environments according to approved security standards.
- **cp-ccm-provision-endpoint**: End-user computing systems are configured with required baseline security controls including disk encryption, unique user account and strong password policy, host firewall, screenlock protection, auto-update of security patches, and endpoint security agent for configuration monitoring and malware protection.
- **cp-ccm-provision-server**: Server systems are provisioned using pre-approved configurations or images approved by the security team.
- **cp-mdm-byod**: BYOD devices are not allowed to connect to production environments containing critical data.
- **cp-sdlc-dev**: A secure software development process, coding standards, and release strategy is established to ensure security is built-in to the products and applications.
- **cp-sdlc-scm**: Source code management system with version control is used to maintain software codes
- **cp-sdlc-foss**: A code analysis tool is in place to analyze open source components for potential security vulnerabilities and licensing issues.
- **cp-threat-malware**: Malware protection agent is installed and activated at all times on endpoint devices.
- **cp-vendor-ssa**: A list of approved software applications and system vendors are in place, with approval process defined for additional acquisition requests.

### § System Operations
【CC7.1】 To meet its objectives, the entity uses detection and monitoring procedures to identify (1) changes to configurations that result in the introduction of new vulnerabilities, and (2) susceptibilities to newly discovered vulnerabilities.

- **cp-ccm-config**: Configuration management processes are in place to provision systems and environments according to approved security standards.
- **cp-ccm-monitor**: Monitoring software is used to monitor infrastructure and software for noncompliance with established configuration standards and security best practices.
- **cp-vuln-scan**: Vulnerability scan is performed at least quarterly for all production systems.
- **cp-sdlc-pentest**: Penetration testing is performed for each product at least annually and with major feature changes.
- **cp-sdlc-bugbounty**: Security team maintains an external/public bug bounty program to enable continuous security testing and vulnerability reporting across major external facing products.

### § System Operations
【CC7.2】 The entity monitors system components and the operation of those components for anomalies that are indicative of malicious acts, natural disasters, and errors affecting the entity's ability to meet its objectives; anomalies are analyzed to determine whether they represent security events.

- **cp-ccm-monitor**: Monitoring software is used to monitor infrastructure and software for noncompliance with established configuration standards and security best practices.
- **cp-audit-internal**: The organization performs manual testing and reviews of systems, accounts and controls as needed. The audit may be performed by internal teams or external auditors.
- **cp-audit-trails**: Security events and logs from production systems and applications are captured as audit trails. Audit trails include sufficient data such as timestamp, user id, action taken to establish who did what, when, how.
- **cp-audit-types**: The organization has defined auditing processes including system configuration monitoring, activity monitoring, access review, and controls compliance audit.
- **cp-events-analysis**: The security team monitors system security events and logs via a combination of automated tools and manual reviews.
- **cp-threat-nids**: Network layer intrusion detection system is implemented.
- **cp-threat-hids**: Host intrusion detection and malicious activity monitoring agents are installed on endpoint hosts and servers.
- **cp-threat-siem**: Security events are logged and alerts are centrally aggregated for review and remediation.

### § System Operations
【CC7.3】 The entity evaluates security events to determine whether they could or have resulted in a failure of the entity to meet its objectives (security incidents) and, if so, takes actions to prevent or address such failures.

- **cp-ir-sirt**: Incident response team is established and assigned corresponding responsibilities.
- **cp-ir-process**: Incident response / escalation policies and processes are in place for incident reporting, triage, eradication, recovery, and postmortem analysis.
- **cp-ir-playbook**: Incident playbooks are created with detailed technical procedures to guide personnel in incident handling according to the incident classification and severity.
- **cp-ir-records**: Each incident is tracked with applicable attributes and notes, and the incident records are stored in an approved ticketing system.
- **cp-vuln-remediation**: All security vulnerability and findings (for both infrastructure and software) are prioritized and remediated based on its severity and impact, with a defined SLA.

### § System Operations
【CC7.4】 The entity responds to identified security incidents by executing a defined incident response program to understand, contain, remediate, and communicate security incidents, as appropriate.

- **cp-ir-playbook**: Incident playbooks are created with detailed technical procedures to guide personnel in incident handling according to the incident classification and severity.
- **cp-ir-process**: Incident response / escalation policies and processes are in place for incident reporting, triage, eradication, recovery, and postmortem analysis.
- **cp-ir-sirt**: Incident response team is established and assigned corresponding responsibilities.
- **cp-breach-customer**: Customer responsibilities are defined in the case of a breach related to or resulted from customer activities.
- **cp-breach-investigate**: Investigation and notification process is in place to handle suspected and/or confirmed data breaches.
- **cp-breach-letter**: Communication template is in place for external notification of a breach.

### § System Operations
【CC7.5】 The entity identifies, develops, and implements activities to recover from identified security incidents.

- **cp-ccm-emergency**: An emergency change process is in place for break-glass procedure. Details of any emergency change are retroactively documented and approved.
- **cp-ir-playbook**: Incident playbooks are created with detailed technical procedures to guide personnel in incident handling according to the incident classification and severity.
- **cp-ir-process**: Incident response / escalation policies and processes are in place for incident reporting, triage, eradication, recovery, and postmortem analysis.
- **cp-ir-tabletop**: Tabletop exercises and/or simulated incident drills are performed at least annually to validate and update the incident response process.

### § Change Management
【CC8.1】 The entity authorizes, designs, develops or acquires, configures, documents, tests, approves, and implements changes to infrastructure, data, software, and procedures to meet its objectives.

- **cp-ccm-aws**: AWS configuration is maintained as code and provisioned via automated code deploys.
- **cp-ccm-aws-deploy**: Cloud infrastructure changes and software code deploys follow a defined change request process with automated and/or manual reviews and approvals.
- **cp-ccm-config**: Configuration management processes are in place to provision systems and environments according to approved security standards.
- **cp-ccm-emergency**: An emergency change process is in place for break-glass procedure. Details of any emergency change are retroactively documented and approved.
- **cp-ccm-network**: Network devices are configured to remove vendor default security configurations. Network layer security controls are in place to enable traffic filtering/monitoring for applicable environments.
- **cp-ccm-patch**: Operating systems on both end-user computing devices and server systems are required to maintain up-to-date security patches in an automated process.
- **cp-ccm-prodcm**: Code deploys to production require an approved change ticket with sufficient details about the code change.
- **cp-ccm-provision-endpoint**: End-user computing systems are configured with required baseline security controls including disk encryption, unique user account and strong password policy, host firewall, screenlock protection, auto-update of security patches, and endpoint security agent for configuration monitoring and malware protection.
- **cp-ccm-provision-mgmt**: System management tools are provisioned following the same requirements and configurations as any production system.
- **cp-ccm-provision-prod**: Provisioning of any production system or resource requires a change request that is reviewed and approved by both engineering and security.
- **cp-ccm-provision-server**: Server systems are provisioned using pre-approved configurations or images approved by the security team.
- **cp-sdlc-appsec-req**: Application security requirements are defined following OWASP Top Ten best practices.
- **cp-sdlc-design**: Security considerations are mandatory as part of new system design and feature development. Threat modeling is jointly performed by security and development teams as needed.
- **cp-sdlc-dev**: A secure software development process, coding standards, and release strategy is established to ensure security is built-in to the products and applications.
- **cp-sdlc-scm**: Source code management system with version control is used to maintain software codes

### § Risk Mitigation
【CC9.1】 The entity identifies, selects, and develops risk mitigation activities for risks arising from potential business disruptions.

- **cp-risk-mgmt**: The organization has a risk management policy and defined process for managing risks - including risk identification, mitigation, monitoring, review and approval.
- **cp-risk-assess**: Risk assessments are conducted annually using a defined methodology that identifies the threat, impact, probability, actor and assets targeted/impacted.
- **cp-risk-mitigation**: A process is defined to guide the prioritization and implementation of risk mitigating controls including but not limited to controls over technology, and to evaluate residual risk.
- **cp-risk-registry**: Risks identified from each risk assessment are documented and maintained.
- **cp-risk-insurance**: The organization holds cyber liability insurance with sufficient coverage based on its risk profile
- **cp-bcdr**: Management team develops contingency plans for assignment of responsibility for internal controls with clear objectives and roles.

### § Risk Mitigation
【CC9.2】 The entity assesses and manages risks associated with vendors and business partners.

- **cp-compliance-mgmt**: The organization has a program and defined process to manage compliance to applicable regulatory requirements and contractual obligations.
- **cp-vendor-contracts**: Third party vendors are required to sign applicable contractual agreements, such as BAA (for HIPAA), DPA (for GDPR), SLA (for service providers), accepting their responsibilities to meet applicable data protection and privacy requirements.
- **cp-vendor-vtr**: Risk assessments are conducted prior to engaging a new technology vendor.
- **cp-sdlc-outsourcing**: Software development performed by contractors or outsourced vendors follow the same secure development standards and requirements.

