# FedRAMP (v(Low) NIST 800-53r4)

Referência oficial: https://www.fedramp.gov/assets/resources/documents/FedRAMP_Security_Controls_Baseline.xlsx

## Controles e Domínios (17)

### ACCESS CONTROL

- **AC-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. An access control policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the access control policy and associated access controls; and
 b. Reviews and updates the current:
   1. Access control policy **at least every 3 years**; and
   2. Access control procedures **at least annually**.
- **AC-2**: The organization:
 a. Identifies and selects the following types of information system accounts to support organizational missions/business functions: [Assignment: organization-defined information system account types];
 b. Assigns account managers for information system accounts;
 c. Establishes conditions for group and role membership;
 d. Specifies authorized users of the information system, group and role membership, and access authorizations (i.e., privileges) and other attributes (as required) for each account;
 e. Requires approvals by [Assignment: organization-defined personnel or roles] for requests to create information system accounts;
 f. Creates, enables, modifies, disables, and removes information system accounts in accordance with [Assignment: organization-defined procedures or conditions];
 g. Monitors the use of, information system accounts;
 h. Notifies account managers:
   1. When accounts are no longer required;
   2. When users are terminated or transferred; and
   3. When individual information system usage or need-to-know changes;
 i. Authorizes access to the information system based on:
   1. A valid access authorization;
   2. Intended system usage; and
   3. Other attributes as required by the organization or associated missions/business functions;
 j. Reviews accounts for compliance with account management requirements **at least annually**; and
 k. Establishes a process for reissuing shared/group account credentials (if deployed) when individuals are removed from the group.
- **AC-3**: The information system enforces approved authorizations for logical access to information and system resources in accordance with applicable access control policies.
- **AC-7**: The information system:
 a. Enforces a limit of **not more than three (3)** consecutive invalid logon attempts by a user during a **fifteen (15) minutes**; and
 b. Automatically [Selection: locks the account/node for an **locks the account/node for thirty minutes**; locks the account/node until released by an administrator; delays next logon prompt according to [Assignment: organization-defined delay algorithm]] when the maximum number of unsuccessful attempts is exceeded.
- **AC-8**: The information system:
 a. Displays to users **see additional Requirements and Guidance** before granting access to the system that provides privacy and security notices consistent with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance and states that:
   1. Users are accessing a U.S. Government information system;
   2. Information system usage may be monitored, recorded, and subject to audit;
   3. Unauthorized use of the information system is prohibited and subject to criminal and civil penalties; and
   4. Use of the information system indicates consent to monitoring and recording;
 b. Retains the notification message or banner on the screen until users acknowledge the usage conditions and take explicit actions to log on to or further access the information system; and 
 c. For publicly accessible systems:
   1. Displays system use information [Assignment: organization-defined conditions], before granting further access;
   2. Displays references, if any, to monitoring, recording, or auditing that are consistent with privacy accommodations for such systems that generally prohibit those activities; and
   3. Includes a description of the authorized uses of the system.
- **AC-14**: The organization:
 a. Identifies [Assignment: organization-defined user actions] that can be performed on the information system without identification or authentication consistent with organizational missions/business functions; and
 b. Documents and provides supporting rationale in the security plan for the information system, user actions not requiring identification or authentication.
- **AC-17**: The organization:
 a. Establishes and documents usage restrictions, configuration/connection requirements, and implementation guidance for each type of remote access allowed; and
 b. Authorizes remote access to the information system prior to allowing such connections.
- **AC-18**: The organization:
 a. Establishes usage restrictions, configuration/connection requirements, and implementation guidance for wireless access; and
 b. Authorizes wireless access to the information system prior to allowing such connections.
- **AC-19**: The organization:
 a. Establishes usage restrictions, configuration requirements, connection requirements, and implementation guidance for organization-controlled mobile devices; and
 b. Authorizes the connection of mobile devices to organizational information systems.
- **AC-20**: The organization establishes terms and conditions, consistent with any trust relationships established with other organizations owning, operating, and/or maintaining external information systems, allowing authorized individuals to:
 a. Access the information system from external information systems; and
 b. Process, store, or transmit organization-controlled information using external information systems.
- **AC-22**: The organization:
 a. Designates individuals authorized to post information onto a publicly accessible information system;
 b. Trains authorized individuals to ensure that publicly accessible information does not contain nonpublic information;
 c. Reviews the proposed content of information prior to posting onto the publicly accessible information system to ensure that nonpublic information is not included; and
 d. Reviews the content on the publicly accessible information system for nonpublic information **at least quarterly** and removes such information, if discovered.

### AWARENESS AND TRAINING

- **AT-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A security awareness and training policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2.  Procedures to facilitate the implementation of the security awareness and training policy and associated security awareness and training controls; and
 b. Reviews and updates the current:
   1. Security awareness and training policy **at least every 3 years**; and
   2.  Security awareness and training procedures **at least annually**.
- **AT-2**: The organization provides basic security awareness training to information system users (including managers, senior executives, and contractors):
 a. As part of initial training for new users;
 b. When required by information system changes; and
 c. **at least annually** thereafter.
- **AT-3**: The organization provides role-based security training to personnel with assigned security roles and responsibilities:
a. Before authorizing access to the information system or performing assigned duties;
b. When required by information system changes; and
c. **at least annually** thereafter.
- **AT-4**: The organization:
 a. Documents and monitors individual information system security training activities including basic security awareness training and specific information system security training; and
 b. Retains individual training records for **At least one year**.

### AUDIT AND ACCOUNTABILITY

- **AU-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. An audit and accountability policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2.  Procedures to facilitate the implementation of the audit and accountability policy and associated audit and accountability controls; and
 b. Reviews and updates the current:
   1. Audit and accountability policy **at least every 3 years**; and
   2. Audit and accountability procedures **at least annually**.
- **AU-2**: The organization:
 a. Determines that the information system is capable of auditing the following events: **successful and unsuccessful account logon events, account management events, object access, policy change, privilege functions, process tracking, and system events For Web applications: all administrator activity, authentication checks, authorization checks, data deletions, data access, data changes, and permission changes**;
 b. Coordinates the security audit function with other organizational entities requiring audit- related information to enhance mutual support and to help guide the selection of auditable events;
 c. Provides a rationale for why the auditable events are deemed to be adequate to support after- the-fact investigations of security incidents; and
 d. Determines that the following events are to be audited within the information system: **organization-defined subset of the auditable events defined in AU-2 a to be audited continually for each identified event**.
- **AU-3**: The information system generates audit records containing information that establishes what type of event occurred, when the event occurred, where the event occurred, the source of the event, the outcome of the event, and the identity of any individuals or subjects associated with the event.
- **AU-4**: The organization allocates audit record storage capacity in accordance with [Assignment:
organization-defined audit record storage requirements].
- **AU-5**: The information system:
 a. Alerts [Assignment: organization-defined personnel or roles] in the event of an audit processing failure; and
 b. Takes the following additional actions: [Assignment: organization-defined actions to be taken (e.g., shut down information system, overwrite oldest audit records, stop generating audit records)].
- **AU-6**: The organization:
 a. Reviews and analyzes information system audit records **at least weekly** for indications of [Assignment: organization-defined inappropriate or unusual activity]; and
 b. Reports findings to [Assignment: organization-defined personnel or roles].
- **AU-8**: The information system:
 a. Uses internal system clocks to generate time stamps for audit records; and
 b. Records time stamps for audit records that can be mapped to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT) and meets [Assignment: organization-defined granularity of time measurement].
- **AU-9**: The information system protects audit information and audit tools from unauthorized access, modification, and deletion.
- **AU-11**: The organization retains audit records for **at least ninety days** to provide support for after-the-fact investigations of security incidents and to meet regulatory and organizational information retention requirements.
- **AU-12**: The information system:
 a. Provides audit record generation capability for the auditable events defined in AU-2 a. at **all information system and network components where audit capability is deployed/available**;
 b. Allows [Assignment: organization-defined personnel or roles] to select which auditable events are to be audited by specific components of the information system; and
 c.    Generates audit records for the events defined in AU-2 d. with the content defined in AU-3.

### SECURITY ASSESSMENT AND AUTHORIZATION

- **CA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A security assessment and authorization policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the security assessment and authorization policy and associated security assessment and authorization controls; and
 b. Reviews and updates the current:
   1. Security assessment and authorization policy **at least every 3 years**; and
   2. Security assessment and authorization procedures **at least annually**.
- **CA-2**: The organization:
 a. Develops a security assessment plan that describes the scope of the assessment including:
   1. Security controls and control enhancements under assessment;
   2. Assessment procedures to be used to determine security control effectiveness; and
   3. Assessment environment, assessment team, and assessment roles and responsibilities;
 b. Assesses the security controls in the information system and its environment of operation **at least annually** to determine the extent to which the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security requirements;
 c. Produces a security assessment report that documents the results of the assessment; and
 d. Provides the results of the security control assessment to **individuals or roles to include FedRAMP PMO**.
- **CA-2 (1)**: The organization employs assessors or assessment teams with [Assignment: organization-defined level of independence] to conduct security control assessments.
- **CA-3**: The organization:
 a. Authorizes connections from the information system to other information systems through the use of Interconnection Security Agreements;
 b. Documents, for each interconnection, the interface characteristics, security requirements, and the nature of the information communicated; and
 c. Reviews and updates Interconnection Security Agreements **at least annually and on input from FedRAMP**.
- **CA-5**: The organization:
 a. Develops a plan of action and milestones for the information system to document the organization’s planned remedial actions to correct weaknesses or deficiencies noted during
the assessment of the security controls and to reduce or eliminate known vulnerabilities in the system; and
 b. Updates existing plan of action and milestones **at least monthly** based on the findings from security controls assessments, security impact analyses, and continuous monitoring activities.
- **CA-6**: The organization:
 a. Assigns a senior-level executive or manager as the authorizing official for the information system;
 b. Ensures that the authorizing official authorizes the information system for processing before commencing operations; and
 c. Updates the security authorization **at least every three years or when a significant change occurs**.
- **CA-7**: The organization develops a continuous monitoring strategy and implements a continuous monitoring program that includes:
 a. Establishment of [Assignment: organization-defined metrics] to be monitored;
 b. Establishment of [Assignment: organization-defined frequencies] for monitoring and [Assignment: organization-defined frequencies] for assessments supporting such monitoring;
 c. Ongoing security control assessments in accordance with the organizational continuous monitoring strategy;
 d. Ongoing security status monitoring of organization-defined metrics in accordance with the organizational continuous monitoring strategy;
 e. Correlation and analysis of security-related information generated by assessments and monitoring;
 f. Response actions to address results of the analysis of security-related information; and
 g. Reporting the security status of organization and the information system to **to meet Federal and FedRAMP requirements** [Assignment: organization-defined frequency].
- **CA-9**: The organization:
 a. Authorizes internal connections of [Assignment: organization-defined information system components or classes of components] to the information system; and
 b. Documents, for each internal connection, the interface characteristics, security requirements, and the nature of the information communicated.

### CONFIGURATION MANAGEMENT

- **CM-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A configuration management policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the configuration management policy and associated configuration management controls; and
 b. Reviews and updates the current:
   1. Configuration management policy **at least every 3 years**; and
   2. Configuration management procedures **at least annually**.
- **CM-2**: The organization develops, documents, and maintains under configuration control, a current baseline configuration of the information system.
- **CM-4**: The organization analyzes changes to the information system to determine potential security impacts prior to change implementation.
- **CM-6**: The organization:
 a. Establishes and documents configuration settings for information technology products employed within the information system using **United States Government Configuration Baseline (USGCB)** that reflect the most restrictive mode consistent with operational requirements;
 b. Implements the configuration settings;
 c. Identifies, documents, and approves any deviations from established configuration settings for [Assignment: organization-defined information system components] based on [Assignment: organization-defined operational requirements]; and
 d. Monitors and controls changes to the configuration settings in accordance with organizational policies and procedures.
- **CM-7**: The organization:
 a. Configures the information system to provide only essential capabilities; and
 b. Prohibits or restricts the use of the following functions, ports, protocols, and/or services: **United States Government Configuration Baseline (USGCB)**.
- **CM-8**: The organization:
 a. Develops and documents an inventory of information system components that:
   1. Accurately reflects the current information system;
   2. Includes all components within the authorization boundary of the information system;
   3. Is at the level of granularity deemed necessary for tracking and reporting; and
   4. Includes [Assignment: organization-defined information deemed necessary to achieve effective information system component accountability]; and
 b. Reviews and updates the information system component inventory **at least monthly**.
- **CM-10**: The organization:
a. Uses software and associated documentation in accordance with contract agreements and copyright laws;
b. Tracks the use of software and associated documentation protected by quantity licenses to control copying and distribution; and
c. Controls and documents the use of peer-to-peer file sharing technology to ensure that this capability is not used for the unauthorized distribution, display, performance, or reproduction of copyrighted work.
- **CM-11**: The organization:
 a. Establishes [Assignment: organization-defined policies] governing the installation of software by users;
 b. Enforces software installation policies through [Assignment: organization-defined methods]; and
 c. Monitors policy compliance at **Continuously (via CM-7 (5))**.

### CONTINGENCY PLANNING

- **CP-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A contingency planning policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the contingency planning policy and associated contingency planning controls; and
 b. Reviews and updates the current:
   1. Contingency planning policy **at least every 3 years**; and
   2. Contingency planning procedures **at least annually**.
- **CP-2**: The organization:
 a. Develops a contingency plan for the information system that:
   1. Identifies essential missions and business functions and associated contingency requirements;
   2. Provides recovery objectives, restoration priorities, and metrics;
   3. Addresses contingency roles, responsibilities, assigned individuals with contact information;
   4. Addresses maintaining essential missions and business functions despite an information system disruption, compromise, or failure;
   5. Addresses eventual, full information system restoration without deterioration of the security safeguards originally planned and implemented; and
   6. Is reviewed and approved by [Assignment: organization-defined personnel or roles];
 b. Distributes copies of the contingency plan to [Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements];
 c. Coordinates contingency planning activities with incident handling activities;
 d. Reviews the contingency plan for the information system **at least annually**;
 e. Updates the contingency plan to address changes to the organization, information system, or environment of operation and problems encountered during contingency plan implementation, execution, or testing;
 f. Communicates contingency plan changes to [Assignment: organization-defined key contingency personnel (identified by name and/or by role) and organizational elements]; and
 g. Protects the contingency plan from unauthorized disclosure and modification.
- **CP-3**: The organization provides contingency training to information system users consistent with assigned roles and responsibilities:
 a. Within **ten (10) days** of assuming a contingency role or responsibility;
 b. When required by information system changes; and
 c. **at least annually** thereafter.
- **CP-4**: The organization:
 a. Tests the contingency plan for the information system **at least annually for moderate impact systems; at least every three years for low impact systems** using **functional exercises for moderate impact systems; classroom exercises/table top written tests for low impact systems** to determine the effectiveness of the plan and the organizational readiness to execute the plan;
 b. Reviews the contingency plan test results; and
 c. Initiates corrective actions, if needed.
- **CP-9**: The organization:
a. Conducts backups of user-level information contained in the information system **daily incremental; weekly full**;
b. Conducts backups of system-level information contained in the information system **daily incremental; weekly full**;
c. Conducts backups of information system documentation including security-related documentation **daily incremental; weekly full**; and
d. Protects the confidentiality, integrity, and availability of backup information at storage locations.
- **CP-10**: The organization provides for the recovery and reconstitution of the information system to a known state after a disruption, compromise, or failure.

### IDENTIFICATION AND AUTHENTICATION

- **IA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. An identification and authentication policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the identification and authentication policy and associated identification and authentication controls; and
 b. Reviews and updates the current:
   1. Identification and authentication policy **at least every 3 years**; and
   2. Identification and authentication procedures **at least annually**.
- **IA-2**: The information system uniquely identifies and authenticates organizational users (or processes acting on behalf of organizational users).
- **IA-2 (1)**: The information system implements multifactor authentication for network access to privileged accounts.
- **IA-2 (12)**: The information system accepts and electronically verifies Personal Identity Verification (PIV)
credentials.
- **IA-4**: The organization manages information system identifiers by:
 a. Receiving authorization from [Assignment: organization-defined personnel or roles] to assign an individual, group, role, or device identifier;
 b. Selecting an identifier that identifies an individual, group, role, or device;
 c. Assigning the identifier to the intended individual, group, role, or device;
 d. Preventing reuse of identifiers for **at least two years**; and
 e. Disabling the identifier after **ninety days for user identifiers**.
- **IA-5**: The organization manages information system authenticators by:
  a. Verifying, as part of the initial authenticator distribution, the identity of the individual, group, role, or device receiving the authenticator;
  b. Establishing initial authenticator content for authenticators defined by the organization;
  c. Ensuring that authenticators have sufficient strength of mechanism for their intended use;
  d. Establishing and implementing administrative procedures for initial authenticator distribution, for lost/compromised or damaged authenticators, and for revoking authenticators;
  e. Changing default content of authenticators prior to information system installation;
  f. Establishing minimum and maximum lifetime restrictions and reuse conditions for authenticators;
  g. Changing/refreshing authenticators [Assignment: organization-defined time period by authenticator type];
  h. Protecting authenticator content from unauthorized disclosure and modification;
  i. Requiring individuals to take, and having devices implement, specific security safeguards to protect authenticators; and
  j. Changing authenticators for group/role accounts when membership to those accounts changes.
- **IA-5 (1)**: The information system, for password-based authentication:
 (a)   Enforces minimum password complexity of [Assignment: organization-defined requirements for case sensitivity, number of characters, mix of upper-case letters, lower-case letters, numbers, and special characters, including minimum requirements for each type];
 (b)   Enforces at least the following number of changed characters when new passwords are created: [Assignment: organization-defined number];
 (c)   Stores and transmits only encrypted representations of passwords;
 (d)   Enforces password minimum and maximum lifetime restrictions of [Assignment: organization- defined numbers for lifetime minimum, lifetime maximum];
 (e)   Prohibits password reuse for [Assignment: organization-defined number] generations; and
 (f) Allows the use of a temporary password for system logons with an immediate change to a permanent password.
- **IA-5 (11)**: The information system, for hardware token-based authentication, employs mechanisms that satisfy [Assignment: organization-defined token quality requirements].
- **IA-6**: The information system obscures feedback of authentication information during the authentication process to protect the information from possible exploitation/use by unauthorized individuals.
- **IA-7**: The information system implements mechanisms for authentication to a cryptographic module that meet the requirements of applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance for such authentication.
- **IA-8**: The information system uniquely identifies and authenticates non-organizational users (or processes acting on behalf of non-organizational users).
- **IA-8 (1)**: The information system accepts and electronically verifies Personal Identity Verification (PIV) credentials from other federal agencies.
- **IA-8 (2)**: The information system accepts only FICAM-approved third-party credentials.
- **IA-8 (3)**: The organization employs only FICAM-approved information system components in [Assignment:
organization-defined information systems] to accept third-party credentials.
- **IA-8 (4)**: The information system conforms to FICAM-issued profiles.

### INCIDENT RESPONSE

- **IR-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. An incident response policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the incident response policy and associated incident response controls; and
 b. Reviews and updates the current:
   1. Incident response policy **at least every 3 years**; and
   2. Incident response procedures **at least annually**.
- **IR-2**: The organization provides incident response training to information system users consistent with assigned roles and responsibilities:
 a. Within [Assignment: organization-defined time period] of assuming an incident response role or responsibility;
 b. When required by information system changes; and
 c. **at least annually** thereafter.
- **IR-4**: The organization:
a. Implements an incident handling capability for security incidents that includes preparation, detection and analysis, containment, eradication, and recovery;
b. Coordinates incident handling activities with contingency planning activities; and
c. Incorporates lessons learned from ongoing incident handling activities into incident response procedures, training, and testing/exercises, and implements the resulting changes accordingly.
- **IR-5**: The organization tracks and documents information system security incidents.
- **IR-6**: The organization:
 a. Requires personnel to report suspected security incidents to the organizational incident response capability within **US-CERT incident reporting timelines as specified in NIST Special Publication 800-61 (as amended)**; and
 b. Reports security incident information to [Assignment: organization-defined authorities].
- **IR-7**: The organization provides an incident response support resource, integral to the organizational incident response capability that offers advice and assistance to users of the information system for the handling and reporting of security incidents.
- **IR-8**: The organization:
 a. Develops an incident response plan that:
   1. Provides the organization with a roadmap for implementing its incident response capability;
   2. Describes the structure and organization of the incident response capability;
   3. Provides a high-level approach for how the incident response capability fits into the overall organization;
   4. Meets the unique requirements of the organization, which relate to mission, size, structure, and functions;
   5. Defines reportable incidents;
   6. Provides metrics for measuring the incident response capability within the organization;
   7. Defines the resources and management support needed to effectively maintain and mature an incident response capability; and
   8. Is reviewed and approved by [Assignment: organization-defined personnel or roles];
 b. Distributes copies of the incident response plan to **see additional FedRAMP Requirements and Guidance**;
 c. Reviews the incident response plan **at least annually**;
 d. Updates the incident response plan to address system/organizational changes or problems encountered during plan implementation, execution, or testing;
  e. Communicates incident response plan changes to **see additional FedRAMP Requirements and Guidance**; and
f. Protects the incident response plan from unauthorized disclosure and modification.

### MAINTENANCE

- **MA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A system maintenance policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the system maintenance policy and associated system maintenance controls; and
 b. Reviews and updates the current:
   1. System maintenance policy **at least every 3 years**; and
   2. System maintenance procedures **at least annually**.
- **MA-2**: The organization:
 a. Schedules, performs, documents, and reviews records of maintenance and repairs on information system components in accordance with manufacturer or vendor specifications and/or organizational requirements;
 b. Approves and monitors all maintenance activities, whether performed on site or remotely and whether the equipment is serviced on site or removed to another location;
 c. Requires that [Assignment: organization-defined personnel or roles] explicitly approve the removal of the information system or system components from organizational facilities for off-site maintenance or repairs;
 d. Sanitizes equipment to remove all information from associated media prior to removal from organizational facilities for off-site maintenance or repairs;
 e. Checks all potentially impacted security controls to verify that the controls are still functioning properly following maintenance or repair actions; and
 f. Includes [Assignment: organization-defined maintenance-related information] in organizational maintenance records.
- **MA-4**: The organization:
 a. Approves and monitors nonlocal maintenance and diagnostic activities;
 b. Allows the use of nonlocal maintenance and diagnostic tools only as consistent with organizational policy and documented in the security plan for the information system;
 c. Employs strong authenticators in the establishment of nonlocal maintenance and diagnostic sessions;
 d. Maintains records for nonlocal maintenance and diagnostic activities; and
 e. Terminates session and network connections when nonlocal maintenance is completed.
- **MA-5**: The organization:
 a. Establishes a process for maintenance personnel authorization and maintains a list of authorized maintenance organizations or personnel;
 b. Ensures that non-escorted personnel performing maintenance on the information system have required access authorizations; and
 c. Designates organizational personnel with required access authorizations and technical competence to supervise the maintenance activities of personnel who do not possess the required access authorizations.

### MEDIA PROTECTION

- **MP-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A media protection policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the media protection policy and associated media protection controls; and
 b. Reviews and updates the current:
   1. Media protection policy **at least every 3 years**; and
   2. Media protection procedures **at least annually**.
- **MP-2**: The organization restricts access to [Assignment: organization-defined types of digital and/or non-digital media] to [Assignment: organization-defined personnel or roles].
- **MP-6**: The organization:
 a. Sanitizes [Assignment: organization-defined information system media] prior to disposal, release out of organizational control, or release for reuse using [Assignment: organization- defined sanitization techniques and procedures] in accordance with applicable federal and organizational standards and policies; and
 b. Employs sanitization mechanisms with the strength and integrity commensurate with the security category or classification of the information.
- **MP-7**: The organization [Selection: restricts; prohibits] the use of [Assignment: organization- defined types of information system media] on [Assignment: organization-defined information systems or system components] using [Assignment: organization-defined security safeguards].

### PHYSICAL AND ENVIRONMENTAL PROTECTION

- **PE-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A physical and environmental protection policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the physical and environmental protection policy and associated physical and environmental protection controls; and
 b. Reviews and updates the current:
   1. Physical and environmental protection policy **at least every 3 years**; and
   2. Physical and environmental protection procedures **at least annually**.
- **PE-2**: The organization:
 a. Develops, approves, and maintains a list of individuals with authorized access to the facility where the information system resides;
 b. Issues authorization credentials for facility access;
 c. Reviews the access list detailing authorized facility access by individuals **at least annually**; and
 d. Removes individuals from the facility access list when access is no longer required.
- **PE-3**: The organization:
 a. Enforces physical access authorizations at [Assignment: organization-defined entry/exit points to the facility where the information system resides] by;
   1. Verifying individual access authorizations before granting access to the facility; and
   2. Controlling ingress/egress to the facility using [Selection (one or more): **CSP defined physical access control systems/devices AND guards**; guards];
 b. Maintains physical access audit logs for [Assignment: organization-defined entry/exit points];
 c. Provides [Assignment: organization-defined security safeguards] to control access to areas within the facility officially designated as publicly accessible;
 d. Escorts visitors and monitors visitor activity **in all circumstances within restricted access area where the information system resides**;
 e. Secures keys, combinations, and other physical access devices;
 f. Inventories **at least annually** every [Assignment: organization-defined frequency]; and
 g. Changes combinations and keys **at least annually** and/or when keys are lost, combinations are compromised, or individuals are transferred or terminated.
- **PE-6**: The organization:
 a. Monitors physical access to the facility where the information system resides to detect and respond to physical security incidents;
 b. Reviews physical access logs **at least monthly** and upon occurrence of [Assignment: organization-defined events or potential indications of events]; and
 c. Coordinates results of reviews and investigations with the organizational incident response capability.
- **PE-8**: The organization:
 a. Maintains visitor access records to the facility where the information system resides for **for a minimum of one (1) year**; and
 b. Reviews visitor access records **at least monthly**.
- **PE-12**: The organization employs and maintains automatic emergency lighting for the information system that activates in the event of a power outage or disruption and that covers emergency exits and evacuation routes within the facility.
- **PE-13**: The organization employs and maintains fire suppression and detection devices/systems for the information system that are supported by an independent energy source.
- **PE-14**: The organization:
 a. Maintains temperature and humidity levels within the facility where the information system resides at **consistent with American Society of Heating, Refrigerating and Air-conditioning Engineers (ASHRAE) document entitled Thermal Guidelines for Data Processing Environments**; and
 b. Monitors temperature and humidity levels **continuously**.
- **PE-15**: The organization protects the information system from damage resulting from water leakage by providing master shutoff or isolation valves that are accessible, working properly, and known to key personnel.
- **PE-16**: The organization authorizes, monitors, and controls **all information system components** entering and exiting the facility and maintains records of those items.

### PLANNING

- **PL-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A security planning policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the security planning policy and associated security planning controls; and
 b. Reviews and updates the current:
   1. Security planning policy **at least every 3 years**; and
   2. Security planning procedures **at least annually**.
- **PL-2**: The organization:
 a. Develops a security plan for the information system that:
   1. Is consistent with the organization’s enterprise architecture;
   2. Explicitly defines the authorization boundary for the system;
   3. Describes the operational context of the information system in terms of missions and business processes;
   4. Provides the security categorization of the information system including supporting rationale;
   5. Describes the operational environment for the information system and relationships with or connections to other information systems;
   6. Provides an overview of the security requirements for the system;
   7. Identifies any relevant overlays, if applicable;
   8. Describes the security controls in place or planned for meeting those requirements including a rationale for the tailoring and supplementation decisions; and
   9. Is reviewed and approved by the authorizing official or designated representative prior to plan implementation;
 b. Distributes copies of the security plan and communicates subsequent changes to the plan to [Assignment: organization-defined personnel or roles];
 c. Reviews the security plan for the information system **at least annually**;
 d. Updates the plan to address changes to the information system/environment of operation or problems identified during plan implementation or security control assessments; and
 e. Protects the security plan from unauthorized disclosure and modification.
- **PL-4**: The organization:
 a. Establishes and makes readily available to individuals requiring access to the information system, the rules that describe their responsibilities and expected behavior with regard to information and information system usage;
 b. Receives a signed acknowledgment from such individuals, indicating that they have read, understand, and agree to abide by the rules of behavior, before authorizing access to information and the information system;
 c. Reviews and updates the rules of behavior **At least every 3 years**; and d. Requires individuals who have signed a previous version of the rules of behavior to read and
resign when the rules of behavior are revised/updated.

### PERSONNEL SECURITY

- **PS-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A personnel security policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the personnel security policy and associated personnel security controls; and
 b. Reviews and updates the current:
   1. Personnel security policy **at least every 3 years**; and
   2. Personnel security procedures **at least annually**.
- **PS-2**: The organization:
 a. Assigns a risk designation to all organizational positions;
 b. Establishes screening criteria for individuals filling those positions; and
 c. Reviews and updates position risk designations **at least every three years**.
- **PS-3**: The organization:
 a. Screens individuals prior to authorizing access to the information system; and
 b. Rescreens individuals according to [Assignment: organization-defined conditions requiring rescreening and, where rescreening is so indicated, the frequency of such rescreening].
- **PS-4**: The organization, upon termination of individual employment:
 a. Disables information system access within **same day**;
 b. Terminates/revokes any authenticators/credentials associated with the individual;
 c. Conducts exit interviews that include a discussion of [Assignment: organization-defined information security topics];
 d. Retrieves all security-related organizational information system-related property;
 e. Retains access to organizational information and information systems formerly controlled by terminated individual; and
 f. Notifies [Assignment: organization-defined personnel or roles] within [Assignment: organization-defined time period].
- **PS-5**: The organization:
 a. Reviews and confirms ongoing operational need for current logical and physical access authorizations to information systems/facilities when individuals are reassigned or transferred to other positions within the organization;
 b. Initiates [Assignment: organization-defined transfer or reassignment actions] within [Assignment: organization-defined time period following the formal transfer action];
 c. Modifies access authorization as needed to correspond with any changes in operational need due to reassignment or transfer; and
 d. Notifies **five days of the time period following the formal transfer action (DoD 24 hours)** within [Assignment: organization-defined time period].
- **PS-6**: The organization:
 a. Develops and documents access agreements for organizational information systems;
 b. Reviews and updates the access agreements **at least annually**; and
 c. Ensures that individuals requiring access to organizational information and information systems:
   1. Sign appropriate access agreements prior to being granted access; and
   2. Re-sign access agreements to maintain access to organizational information systems when access agreements have been updated or **at least annually**.
- **PS-7**: The organization:
 a. Establishes personnel security requirements including security roles and responsibilities for third-party providers;
 b. Requires third-party providers to comply with personnel security policies and procedures established by the organization;
 c. Documents personnel security requirements;
 d. Requires third-party providers to notify **organization-defined time period – same day** of any personnel transfers or terminations of third-party personnel who possess organizational credentials and/or badges, or who have information system privileges within [Assignment: organization-defined time period]; and
 e. Monitors provider compliance.
- **PS-8**: The organization:
 a. Employs a formal sanctions process for individuals failing to comply with established information security policies and procedures; and
 b. Notifies [Assignment: organization-defined personnel or roles] within [Assignment: organization-defined time period] when a formal employee sanctions process is initiated, identifying the individual sanctioned and the reason for the sanction.

### RISK ASSESSMENT

- **RA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A risk assessment policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the risk assessment policy and associated risk assessment controls; and
 b. Reviews and updates the current:
   1. Risk assessment policy **at least every 3 years**; and
   2. Risk assessment procedures **at least annually**.
- **RA-2**: The organization:
 a. Categorizes information and the information system in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance;
 b. Documents the security categorization results (including supporting rationale) in the security plan for the information system; and
 c. Ensures that the security categorization decision is reviewed and approved by the authorizing official or authorizing official designated representative.
- **RA-3**: The organization:
 a. Conducts an assessment of risk, including the likelihood and magnitude of harm, from the unauthorized access, use, disclosure, disruption, modification, or destruction of the information system and the information it processes, stores, or transmits;
 b. Documents risk assessment results in [Selection: security plan; risk assessment report; **security assessment report**];
 c. Reviews risk assessment results **at least every three (3) years or when a significant change occurs**;
 d. Disseminates risk assessment results to [Assignment: organization-defined personnel or roles]; and
 e. Updates the risk assessment **at least every three (3) years or when a significant change occurs** or whenever there are significant changes to the information system or environment of operation (including the identification of new threats and vulnerabilities), or other conditions that may impact the security state of the system.
- **RA-5**: The organization:
 a. Scans for vulnerabilities in the information system and hosted applications **monthly operating system/infrastructure; monthly web applications and databases** and when new vulnerabilities potentially affecting the system/applications are identified and reported;
 b. Employs vulnerability scanning tools and techniques that facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:
   1. Enumerating platforms, software flaws, and improper configurations;
   2. Formatting checklists and test procedures; and
   3. Measuring vulnerability impact;
 c. Analyzes vulnerability scan reports and results from security control assessments;
 d. Remediates legitimate vulnerabilities **high-risk vulnerabilities mitigated within thirty days from date of discovery; moderate-risk vulnerabilities mitigated within ninety days from date of discovery; low risk vulnerabilities mitigated within one hundred and eighty (180) days from date of discovery**, in accordance with an organizational assessment of risk; and
 e. Shares information obtained from the vulnerability scanning process and security control assessments with [Assignment: organization-defined personnel or roles] to help eliminate similar vulnerabilities in other information systems (i.e., systemic weaknesses or deficiencies).

### SYSTEM AND SERVICES ACQUISITION

- **SA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A system and services acquisition policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the system and services acquisition policy and associated system and services acquisition controls; and
 b. Reviews and updates the current:
   1. System and services acquisition policy **at least every 3 years**; and
   2.  System and services acquisition procedures **at least annually**.
- **SA-2**: The organization:
 a. Determines information security requirements for the information system or information system service in mission/business process planning;
 b. Determines, documents, and allocates the resources required to protect the information system or information system service as part of its capital planning and investment control process; and
 c. Establishes a discrete line item for information security in organizational programming and budgeting documentation.
- **SA-3**: The organization:
 a. Manages the information system using [Assignment: organization-defined system development life cycle] that incorporates information security considerations;
 b. Defines and documents information security roles and responsibilities throughout the system development life cycle;
 c. Identifies individuals having information security roles and responsibilities; and
 d. Integrates the organizational information security risk management process into system development life cycle activities.
- **SA-4**: The organization includes the following requirements, descriptions, and criteria, explicitly or by reference, in the acquisition contract for the information system, system component, or information system service in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, guidelines, and organizational mission/business needs:
  a. Security functional requirements;
 b. Security strength requirements;
 c. Security assurance requirements;
 d. Security-related documentation requirements;
 e. Requirements for protecting security-related documentation;
 f. Description of the information system development environment and environment in which the system is intended to operate; and
 g. Acceptance criteria.
- **SA-5**: The organization:
 a. Obtains administrator documentation for the information system, system component, or information system service that describes:
   1. Secure configuration, installation, and operation of the system, component, or service;
   2. Effective use and maintenance of security functions/mechanisms; and
   3. Known vulnerabilities regarding configuration and use of administrative (i.e., privileged) functions;
 b. Obtains user documentation for the information system, system component, or information system service that describes:
   1. User-accessible security functions/mechanisms and how to effectively use those security functions/mechanisms;
   2. Methods for user interaction, which enables individuals to use the system, component, or service in a more secure manner; and
   3. User responsibilities in maintaining the security of the system, component, or service;
 c. Documents attempts to obtain information system, system component, or information system service documentation when such documentation is either unavailable or nonexistent and [Assignment: organization-defined actions] in response;
 d. Protects documentation as required, in accordance with the risk management strategy; and e. Distributes documentation to [Assignment: organization-defined personnel or roles].
- **SA-9**: The organization:
 a. Requires that providers of external information system services comply with organizational information security requirements and employ **FedRAMP Security Controls Baseline(s) if Federal information is processed or stored within the external system** in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance;
 b. Defines and documents government oversight and user roles and responsibilities with regard to external information system services; and
 c. Employs **Federal/FedRAMP Continuous Monitoring requirements must be met for external systems where Federal information is processed or stored** to monitor security control compliance by external service providers on an ongoing basis.

### SYSTEM AND COMMUNICATIONS PROTECTION

- **SC-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A system and communications protection policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the system and communications protection policy and associated system and communications protection controls; and
 b. Reviews and updates the current:
   1. System and communications protection policy **at least every 3 years**; and
   2. System and communications protection procedures **at least annually**.
- **SC-5**: The information system protects against or limits the effects of the following types of denial of service attacks: [Assignment: organization-defined types of denial of service attacks or reference to source for such information] by employing [Assignment: organization-defined security safeguards].
- **SC-7**: The information system:
 a. Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system;
 b. Implements subnetworks for publicly accessible system components that are [Selection: physically; logically] separated from internal organizational networks; and
 c. Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security architecture.
- **SC-12**: The organization establishes and manages cryptographic keys for required cryptography employed within the information system in accordance with [Assignment: organization-defined requirements for key generation, distribution, storage, access, and destruction].
- **SC-13**: The information system implements **FIPS-validated or NSA-approved cryptography** in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, and standards.
- **SC-15**: The information system:
 a. Prohibits remote activation of collaborative computing devices with the following exceptions: **no exceptions**; and
 b. Provides an explicit indication of use to users physically present at the devices.
- **SC-20**: The information system:
 a. Provides additional data origin and integrity artifacts along with the authoritative name resolution data the system returns in response to external name/address resolution queries; and
 b. Provides the means to indicate the security status of child zones and (if the child supports secure resolution services) to enable verification of a chain of trust among parent and child domains, when operating as part of a distributed, hierarchical namespace.
- **SC-21**: The information system requests and performs data origin authentication and data integrity verification on the name/address resolution responses the system receives from authoritative sources.
- **SC-22**: The information systems that collectively provide name/address resolution service for an organization are fault-tolerant and implement internal/external role separation.
- **SC-39**: The information system maintains a separate execution domain for each executing process.

### SYSTEM AND INFORMATION INTEGRITY

- **SI-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A system and information integrity policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the system and information integrity policy and associated system and information integrity controls; and
 b. Reviews and updates the current:
   1. System and information integrity policy **at least every 3 years**; and
   2.  System and information integrity procedures **at least annually**.
- **SI-2**: The organization:
a. Identifies, reports, and corrects information system flaws;
b. Tests software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;
c. Installs security-relevant software and firmware updates within **thirty (30) days of release of updates** of the release of the updates; and
d. Incorporates flaw remediation into the organizational configuration management process.
- **SI-3**: The organization:
 a. Employs malicious code protection mechanisms at information system entry and exit points to detect and eradicate malicious code;
 b. Updates malicious code protection mechanisms whenever new releases are available in accordance with organizational configuration management policy and procedures;
 c. Configures malicious code protection mechanisms to:
   1. Perform periodic scans of the information system **at least weekly** and real-time scans of files from external sources at [Selection (one or more); endpoint; network entry/exit points] as the files are downloaded, opened, or executed in accordance with organizational security policy; and
   2. [Selection (one or more): block malicious code; quarantine malicious code; send alert to administrator; [Assignment: organization-defined action, **to include alerting administrator or defined security personnel**]] in response to malicious code detection; and
 d. Addresses the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the information system.
- **SI-4**: The organization:
 a. Monitors the information system to detect:
   1. Attacks and indicators of potential attacks in accordance with [Assignment: organization- defined monitoring objectives]; and
   2. Unauthorized local, network, and remote connections;
 b. Identifies unauthorized use of the information system through [Assignment: organization- defined techniques and methods];
 c. Deploys monitoring devices: (i) strategically within the information system to collect organization-determined essential information; and (ii) at ad hoc locations within the system to track specific types of transactions of interest to the organization;
 d. Protects information obtained from intrusion-monitoring tools from unauthorized access, modification, and deletion;
 e. Heightens the level of information system monitoring activity whenever there is an indication of increased risk to organizational operations and assets, individuals, other organizations, or the Nation based on law enforcement information, intelligence information, or other credible sources of information;
 f. Obtains legal opinion with regard to information system monitoring activities in accordance with applicable federal laws, Executive Orders, directives, policies, or regulations; and
 g. Provides [Assignment: or ganization-defined information system monitoring information] to [Assignment: organization-defined personnel or roles] [Selection (one or more): as needed; [Assignment: organization-defined frequency]].
- **SI-5**: The organization:
 a. Receives information system security alerts, advisories, and directives from [Assignment: organization-defined external organizations, **to include US-CERT**] on an ongoing basis;
 b. Generates internal security alerts, advisories, and directives as deemed necessary;
 c. Disseminates security alerts, advisories, and directives to: [Selection (one or more): [Assignment: organization-defined personnel or roles, **to include system security personnel and administrators with configuration/patch-management responsibilities**]; [Assignment: organization-defined elements within the organization]; [Assignment: organization-defined external organizations]]; and
 d. Implements security directives in accordance with established time frames, or notifies the issuing organization of the degree of noncompliance.
- **SI-12**: The organization handles and retains information within the information system and information output from the system in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and operational requirements.
- **SI-16**: The information system implements [Assignment: organization-defined security safeguards] to protect its memory from unauthorized code execution.

