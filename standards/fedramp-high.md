# FedRAMP (v(High) NIST 800-53r4)

Referência oficial: https://www.fedramp.gov/assets/resources/documents/FedRAMP_Security_Controls_Baseline.xlsx

## Controles e Domínios (17)

### ACCESS CONTROL

- **AC-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. An access control policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the access control policy and associated access controls; and
 b. Reviews and updates the current:
   1. Access control policy **at least annually**; and
   2. Access control procedures **at least annually or whenever a significant change occurs**.
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
 j. Reviews accounts for compliance with account management requirements **monthly for privileged accessed, every six (6) months for non-privileged access**; and
 k. Establishes a process for reissuing shared/group account credentials (if deployed) when individuals are removed from the group.
- **AC-2 (1)**: The organization employs automated mechanisms to support the management of information system accounts.
- **AC-2 (2)**: The information system automatically [Selection: removes; disables] temporary and emergency accounts after **Selection: disables**.
- **AC-2 (3)**: The information system automatically disables inactive accounts after **35 days for user accounts**.
- **AC-2 (4)**: The information system automatically audits account creation, modification, enabling, disabling, and removal actions, and notifies **organization and/or service provider system owner**.
- **AC-2 (5)**: The organization requires that users log out when **inactivity is anticipated to exceed Fifteen (15) minutes**.
- **AC-2 (7)**: The organization:
(a) Establishes and administers privileged user accounts in accordance with a role-based access scheme that organizes allowed information system access and privileges into roles;
(b) Monitors privileged role assignments; and
(c) Takes [Assignment: organization-defined actions] when privileged role assignments are no longer appropriate.
- **AC-2 (9)**: The organization only permits the use of shared/group accounts that meet **organization-defined need with justification statement that explains why such accounts are necessary**.
- **AC-2 (10)**: The information system terminates shared/group account credentials when members leave the group.
- **AC-2 (11)**: The information system enforces [Assignment: organization-defined circumstances and/or usage conditions] for [Assignment: organization-defined information system accounts].
- **AC-2 (12)**: The organization:
 (a) Monitors information system accounts for [Assignment: organization-defined atypical use]; and
 (b) Reports atypical usage of information system accounts to [Assignment: organization-defined personnel or roles].
- **AC-2 (13)**: The organization disables accounts of users posing a significant risk within **one (1) hour** of discovery of the risk.
- **AC-3**: The information system enforces approved authorizations for logical access to information and system resources in accordance with applicable access control policies.
- **AC-4**: The information system enforces approved authorizations for controlling the flow of information within the system and between interconnected systems based on [Assignment: organization-defined information flow control policies].
- **AC-4 (8)**: The information system enforces information flow control using [Assignment: organization-defined security policy filters] as a basis for flow control decisions for [Assignment: organization-defined information flows].
- **AC-4 (21)**: The information system separates information flows logically or physically using [Assignment: organization-defined mechanisms and/or techniques] to accomplish [Assignment: organization- defined required separations by types of information].
- **AC-5**: The organization:
 a. Separates [Assignment: organization-defined duties of individuals];
 b. Documents separation of duties of individuals; and
 c. Defines information system access authorizations to support separation of duties.
- **AC-6**: The organization employs the principle of least privilege, allowing only authorized accesses for users (or processes acting on behalf of users) which are necessary to accomplish assigned tasks in accordance with organizational missions and business functions.
- **AC-6 (1)**: The organization explicitly authorizes access to **all functions not publicly accessible and all security-relevant information not publicly available**.
- **AC-6 (2)**: The organization requires that users of information system accounts, or roles, with access to **all security functions**, use non- privileged accounts or roles, when accessing nonsecurity functions.
- **AC-6 (3)**: The organization authorizes network access to **all privileged commands** only for [Assignment: organization-defined compelling operational needs] and documents the rationale for such access in the security plan for the information system.
- **AC-6 (5)**: The organization restricts privileged accounts on the information system to [Assignment:
organization-defined personnel or roles].
- **AC-6 (7)**: The organization:
 (a)   Reviews [Assignment: organization-defined frequency] the privileges assigned to [Assignment: organization-defined roles or classes of users] to validate the need for such privileges; and
 (b)   Reassigns or removes privileges, if necessary, to correctly reflect organizational mission/business needs.
- **AC-6 (8)**: The information system prevents **any software except software explicitly documented** from executing at higher privilege levels than users executing the software.
- **AC-6 (9)**: The information system audits the execution of privileged functions.
- **AC-6 (10)**: The information system prevents non-privileged users from executing privileged functions to include disabling, circumventing, or altering implemented security safeguards/countermeasures.
- **AC-7**: The information system:
 a. Enforces a limit of **not more than three (3)** consecutive invalid logon attempts by a user during a **fifteen (15) minutes**; and
 b. Automatically [Selection: locks the account/node for an **locks the account/node for a minimum of three (3) hours or until unlocked by an administrator**; locks the account/node until released by an administrator; delays next logon prompt according to [Assignment: organization-defined delay algorithm]] when the maximum number of unsuccessful attempts is exceeded.
- **AC-7 (2)**: The information system purges/wipes information from **mobile devices as defined by organization policy** based on **three (3)** after [Assignment: organization-defined number] consecutive, unsuccessful device logon attempts.
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
- **AC-10**: The information system limits the number of concurrent sessions for each **three (3) sessions for privileged access and two (2) sessions for non-privileged access** to [Assignment: organization-defined number].
- **AC-11**: The information system:
 a. Prevents further access to the system by initiating a session lock after **fifteen (15) minutes** of inactivity or upon receiving a request from a user; and
 b. Retains the session lock until the user reestablishes access using established identification and authentication procedures.
- **AC-11 (1)**: The information system conceals, via the session lock, information previously visible on the display with a publicly viewable image.
- **AC-12**: The information system automatically terminates a user session after [Assignment: organization-defined conditions or trigger events requiring session disconnect].
- **AC-12 (1)**: The information system:
 (a)   Provides a logout capability for user-initiated communications sessions whenever authentication is used to gain access to [Assignment: organization-defined information resources]; and
 (b)   Displays an explicit logout message to users indicating the reliable termination of authenticated communications sessions.
- **AC-14**: The organization:
 a. Identifies [Assignment: organization-defined user actions] that can be performed on the information system without identification or authentication consistent with organizational missions/business functions; and
 b. Documents and provides supporting rationale in the security plan for the information system, user actions not requiring identification or authentication.
- **AC-17**: The organization:
 a. Establishes and documents usage restrictions, configuration/connection requirements, and implementation guidance for each type of remote access allowed; and
 b. Authorizes remote access to the information system prior to allowing such connections.
- **AC-17 (1)**: The information system monitors and controls remote access methods.
- **AC-17 (2)**: The information system implements cryptographic mechanisms to protect the confidentiality and integrity of remote access sessions.
- **AC-17 (3)**: The information system routes all remote accesses through [Assignment: organization-defined number] managed network access control points.
- **AC-17 (4)**: The organization:
 (a)   Authorizes the execution of privileged commands and access to security-relevant information via remote access only for [Assignment: organization-defined needs]; and
 (b)   Documents the rationale for such access in the security plan for the information system.
- **AC-17 (9)**: The organization provides the capability to expeditiously disconnect or disable remote access to the information system within **fifteen (15) minutes**.
- **AC-18**: The organization:
 a. Establishes usage restrictions, configuration/connection requirements, and implementation guidance for wireless access; and
 b. Authorizes wireless access to the information system prior to allowing such connections.
- **AC-18 (1)**: The information system protects wireless access to the system using authentication of [Selection
(one or more): users; devices] and encryption.
- **AC-18 (3)**: The organization disables, when not intended for use, wireless networking capabilities internally embedded within information system components prior to issuance and deployment.
- **AC-18 (4)**: The organization identifies and explicitly authorizes users allowed to independently configure wireless networking capabilities.
- **AC-18 (5)**: The organization selects radio antennas and calibrates transmission power levels to reduce the probability that usable signals can be received outside of organization-controlled boundaries.
- **AC-19**: The organization:
 a. Establishes usage restrictions, configuration requirements, connection requirements, and implementation guidance for organization-controlled mobile devices; and
 b. Authorizes the connection of mobile devices to organizational information systems.
- **AC-19 (5)**: The organization employs [Selection: full-device encryption; container encryption] to protect the confidentiality and integrity of information on [Assignment: organization-defined mobile devices].
- **AC-20**: The organization establishes terms and conditions, consistent with any trust relationships established with other organizations owning, operating, and/or maintaining external information systems, allowing authorized individuals to:
 a. Access the information system from external information systems; and
 b. Process, store, or transmit organization-controlled information using external information systems.
- **AC-20 (1)**: The organization permits authorized individuals to use an external information system to access the information system or to process, store, or transmit organization-controlled information only when the organization:
 (a)   Verifies the implementation of required security controls on the external system as specified in the organization’s information security policy and security plan; or
 (b)   Retains approved information system connection or processing agreements with the organizational entity hosting the external information system.
- **AC-20 (2)**: The organization [Selection: restricts; prohibits] the use of organization-controlled portable storage devices by authorized individuals on external information systems.
- **AC-21**: The organization:
a. Facilitates information sharing by enabling authorized users to determine whether access authorizations assigned to the sharing partner match the access restrictions on the information for [Assignment: organization-defined information sharing circumstances where user discretion is required]; and
b. Employs [Assignment: organization-defined automated mechanisms or manual processes] to assist users in making information sharing/collaboration decisions.
 
Supplemental Guidance: This control applies to information that may be restricted in some manner (e.g., privileged medical information, contract-sensitive information, proprietary information, personally identifiable information, classified information related to special access programs or compartments) based on some formal or administrative determination. Depending on the particular information-sharing circumstances, sharing partners may be defined at the individual, group, or organizational level. Information may be defined by content, type, security category, or special access program/compartment.
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
   1. Security awareness and training policy **at least annually or whenever a significant change occurs**; and
   2.  Security awareness and training procedures **at least annually or whenever a significant change occurs**.
- **AT-2**: The organization provides basic security awareness training to information system users (including managers, senior executives, and contractors):
 a. As part of initial training for new users;
 b. When required by information system changes; and
 c. **at least annually** thereafter.
- **AT-2 (2)**: The organization includes security awareness training on recognizing and reporting potential indicators of insider threat.
- **AT-3**: The organization provides role-based security training to personnel with assigned security roles and responsibilities:
a. Before authorizing access to the information system or performing assigned duties;
b. When required by information system changes; and
c. **at least annually** thereafter.
- **AT-3 (3)**: The organization includes practical exercises in security training that reinforce training objectives.
- **AT-3 (4)**: The organization provides training to its personnel on **malicious code indicators as defined by organization  incident policy/capability** to recognize suspicious communications and anomalous behavior in organizational information systems.
- **AT-4**: The organization:
 a. Documents and monitors individual information system security training activities including basic security awareness training and specific information system security training; and
 b. Retains individual training records for **five (5) years or 5 years after completion of a specific training program**.

### AUDIT AND ACCOUNTABILITY

- **AU-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. An audit and accountability policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2.  Procedures to facilitate the implementation of the audit and accountability policy and associated audit and accountability controls; and
 b. Reviews and updates the current:
   1. Audit and accountability policy **at least annually**; and
   2. Audit and accountability procedures **at least annually or whenever a significant change occurs**.
- **AU-2**: The organization:
 a. Determines that the information system is capable of auditing the following events: **successful and unsuccessful account logon events, account management events, object access, policy change, privilege functions, process tracking, and system events. For Web applications: all administrator activity, authentication checks, authorization checks, data deletions, data access, data changes, and permission changes**;
 b. Coordinates the security audit function with other organizational entities requiring audit- related information to enhance mutual support and to help guide the selection of auditable events;
 c. Provides a rationale for why the auditable events are deemed to be adequate to support after- the-fact investigations of security incidents; and
 d. Determines that the following events are to be audited within the information system: **organization-defined subset of the auditable events defined in AU-2a to be audited continually for each identified event**.
- **AU-2 (3)**: The organization reviews and updates the audited events **annually or whenever there is a change in the threat environment**.
- **AU-3**: The information system generates audit records containing information that establishes what type of event occurred, when the event occurred, where the event occurred, the source of the event, the outcome of the event, and the identity of any individuals or subjects associated with the event.
- **AU-3 (1)**: The information system generates audit records containing the following additional information: **session, connection, transaction, or activity duration; for client-server transactions, the number of bytes received and bytes sent; additional informational messages to diagnose or identify the event; characteristics that describe or identify the object or resource being acted upon; individual identities of group account users; full-text of privileged commands**.
- **AU-3 (2)**: The information system provides centralized management and configuration of the content to be captured in audit records generated by **all network, data storage, and computing devices**.
- **AU-4**: The organization allocates audit record storage capacity in accordance with [Assignment:
organization-defined audit record storage requirements].
- **AU-5**: The information system:
 a. Alerts [Assignment: organization-defined personnel or roles] in the event of an audit processing failure; and
 b. Takes the following additional actions: [Assignment: organization-defined actions to be taken (e.g., shut down information system, overwrite oldest audit records, stop generating audit records)].
- **AU-5 (1)**: The information system provides a warning to [Assignment: organization-defined personnel, roles, and/or locations] within [Assignment: organization-defined time period] when allocated audit record storage volume reaches [Assignment: organization-defined percentage] of repository maximum audit record storage capacity.
- **AU-5 (2)**: The information system provides an alert in **real-time** to **service provider personnel with authority to address failed audit events** when the following audit failure events occur: **audit failure events requiring real-time alerts, as defined by organization  audit policy**.
- **AU-6**: The organization:
 a. Reviews and analyzes information system audit records **at least weekly** for indications of [Assignment: organization-defined inappropriate or unusual activity]; and
 b. Reports findings to [Assignment: organization-defined personnel or roles].
- **AU-6 (1)**: The organization employs automated mechanisms to integrate audit review, analysis, and reporting processes to support organizational processes for investigation and response to suspicious activities.
- **AU-6 (3)**: The organization analyzes and correlates audit records across different repositories to gain organization-wide situational awareness.
- **AU-6 (4)**: The information system provides the capability to centrally review and analyze audit records from multiple components within the system.
- **AU-6 (5)**: The organization integrates analysis of audit records with analysis of [Selection (one or more): vulnerability scanning information; performance data; information system monitoring information; **Organization -defined data/information collected from other sources]**] to further enhance the ability to identify inappropriate or unusual activity.
- **AU-6 (6)**: The organization correlates information from audit records with information obtained from monitoring physical access to further enhance the ability to identify suspicious, inappropriate, unusual, or malevolent activity.
- **AU-6 (7)**: The organization specifies the permitted actions for each [Selection (one or more): information system process; role; user] associated with the review, analysis, and reporting of audit information.
- **AU-6 (10)**: The organization adjusts the level of audit review, analysis, and reporting within the information system when there is a change in risk based on law enforcement information, intelligence information, or other credible sources of information.
- **AU-7**: The information system provides an audit reduction and report generation capability that:
 a. Supports on-demand audit review, analysis, and reporting requirements and after-the-fact investigations of security incidents; and
 b. Does not alter the original content or time ordering of audit records.
- **AU-7 (1)**: The information system provides the capability to process audit records for events of interest based on [Assignment: organization-defined audit fields within audit records].
- **AU-8**: The information system:
 a. Uses internal system clocks to generate time stamps for audit records; and
 b. Records time stamps for audit records that can be mapped to Coordinated Universal Time (UTC) or Greenwich Mean Time (GMT) and meets **one second granularity of time measurement**.
- **AU-8 (1)**: The information system:
 (a)   Compares the internal information system clocks **At least hourly** with [Assignment: organization-defined authoritative time source]; and
 (b)   Synchronizes the internal system clocks to the authoritative time source when the time difference is greater than **At least hourly**.
- **AU-9**: The information system protects audit information and audit tools from unauthorized access, modification, and deletion.
- **AU-9 (2)**: The information system backs up audit records **at least weekly** onto a physically different system or system component than the system or component being audited.
- **AU-9 (3)**: The information system implements cryptographic mechanisms to protect the integrity of audit information and audit tools.
- **AU-9 (4)**: The organization authorizes access to management of audit functionality to only [Assignment: organization-defined subset of privileged users].
- **AU-10**: The information system protects against an individual (or process acting on behalf of an individual) falsely denying having performed **minimum actions including the addition, modification, deletion, approval, sending, or receiving of data**.
- **AU-11**: The organization retains audit records for **at least one (1) year** to provide support for after-the-fact investigations of security incidents and to meet regulatory and organizational information retention requirements.
- **AU-12**: The information system:
 a. Provides audit record generation capability for the auditable events defined in AU-2 a. at **all information system and network components where audit capability is deployed/available**;
 b. Allows [Assignment: organization-defined personnel or roles] to select which auditable events are to be audited by specific components of the information system; and
 c.    Generates audit records for the events defined in AU-2 d. with the content defined in AU-3.
- **AU-12 (1)**: The information system compiles audit records from **all network, data storage, and computing devices** into a system-wide (logical or physical) audit trail that is time- correlated to within [Assignment: organization-defined level of tolerance for relationship between time stamps of individual records in the audit trail].
- **AU-12 (3)**: The information system provides the capability for **service provider-defined individuals or roles with audit configuration responsibilities** to change the auditing to be performed on **all network, data storage, and computing devices** based on [Assignment: organization-defined selectable event criteria] within [Assignment: organization-defined time thresholds].

### SECURITY ASSESSMENT AND AUTHORIZATION

- **CA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A security assessment and authorization policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the security assessment and authorization policy and associated security assessment and authorization controls; and
 b. Reviews and updates the current:
   1. Security assessment and authorization policy **at least annually**; and
   2. Security assessment and authorization procedures **at least annually or whenever a significant change occurs**.
- **CA-2**: The organization:
 a. Develops a security assessment plan that describes the scope of the assessment including:
   1. Security controls and control enhancements under assessment;
   2. Assessment procedures to be used to determine security control effectiveness; and
   3. Assessment environment, assessment team, and assessment roles and responsibilities;
 b. Assesses the security controls in the information system and its environment of operation **at least annually** to determine the extent to which the controls are implemented correctly, operating as intended, and producing the desired outcome with respect to meeting established security requirements;
 c. Produces a security assessment report that documents the results of the assessment; and
 d. Provides the results of the security control assessment to **individuals or roles to include FedRAMP PMO**.
- **CA-2 (1)**: The organization employs assessors or assessment teams with [Assignment: organization-defined level of independence] to conduct security control assessments.
- **CA-2 (2)**: The organization includes as part of security control assessments, **at least annually**, [Selection: announced; unannounced], [Selection (one or more): in-depth monitoring; vulnerability scanning; malicious user testing; insider threat assessment; performance/load testing; [Assignment: organization-defined other forms of security assessment]].
- **CA-2 (3)**: The organization accepts the results of an assessment of **any FedRAMP Accredited 3PAO** performed by **any FedRAMP Accredited 3PAO** when the assessment meets **the conditions of the JAB/AO in the FedRAMP Repository**.
- **CA-3**: The organization:
 a. Authorizes connections from the information system to other information systems through the use of Interconnection Security Agreements;
 b. Documents, for each interconnection, the interface characteristics, security requirements, and the nature of the information communicated; and
 c. Reviews and updates Interconnection Security Agreements **at least annually and on input from FedRAMP**.
- **CA-3 (3)**: The organization prohibits the direct connection of an **Boundary Protections which meet the Trusted Internet Connection (TIC) requirements** to an external network without the use of [Assignment; organization-defined boundary protection device].
- **CA-3 (5)**: The organization employs [Selection: allow-all, deny-by-exception; deny-all, permit-by-exception] policy for allowing **deny-all, permit by exception** to connect to external information systems.
- **CA-5**: The organization:
 a. Develops a plan of action and milestones for the information system to document the organization’s planned remedial actions to correct weaknesses or deficiencies noted during
the assessment of the security controls and to reduce or eliminate known vulnerabilities in the system; and
 b. Updates existing plan of action and milestones **at least monthly** based on the findings from security controls assessments, security impact analyses, and continuous monitoring activities.
- **CA-6**: The organization:
 a. Assigns a senior-level executive or manager as the authorizing official for the information system;
 b. Ensures that the authorizing official authorizes the information system for processing before commencing operations; and
 c. Updates the security authorization **at least every three (3) years or when a significant change occurs**.
- **CA-7**: The organization develops a continuous monitoring strategy and implements a continuous monitoring program that includes:
 a. Establishment of [Assignment: organization-defined metrics] to be monitored;
 b. Establishment of [Assignment: organization-defined frequencies] for monitoring and [Assignment: organization-defined frequencies] for assessments supporting such monitoring;
 c. Ongoing security control assessments in accordance with the organizational continuous monitoring strategy;
 d. Ongoing security status monitoring of organization-defined metrics in accordance with the organizational continuous monitoring strategy;
 e. Correlation and analysis of security-related information generated by assessments and monitoring;
 f. Response actions to address results of the analysis of security-related information; and
 g. Reporting the security status of organization and the information system to **to meet Federal and FedRAMP requirements** [Assignment: organization-defined frequency].
- **CA-7 (1)**: The organization employs assessors or assessment teams with [Assignment: organization-defined level of independence] to monitor the security controls in the information system on an ongoing basis.
- **CA-7 (3)**: The organization employs trend analyses to determine if security control implementations, the frequency of continuous monitoring activities, and/or the types of activities used in the continuous monitoring process need to be modified based on empirical data.
- **CA-8**: The organization conducts penetration testing **at least annually** on [Assignment: organization-defined information systems or system components].
- **CA-8 (1)**: The organization employs an independent penetration agent or penetration team to perform penetration testing on the information system or system components.
- **CA-9**: The organization:
 a. Authorizes internal connections of [Assignment: organization-defined information system components or classes of components] to the information system; and
 b. Documents, for each internal connection, the interface characteristics, security requirements, and the nature of the information communicated.

### CONFIGURATION MANAGEMENT

- **CM-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A configuration management policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the configuration management policy and associated configuration management controls; and
 b. Reviews and updates the current:
   1. Configuration management policy **at least annually**; and
   2. Configuration management procedures **at least annually or whenever a significant change occurs**.
- **CM-2**: The organization develops, documents, and maintains under configuration control, a current baseline configuration of the information system.
- **CM-2 (1)**: The organization reviews and updates the baseline configuration of the information system: 
 (a)   [Assignment: organization-defined frequency];
 (b)   When required due to [Assignment organization-defined circumstances]; and
 (c)   As an integral part of information system component installations and upgrades.
- **CM-2 (2)**: The organization employs automated mechanisms to maintain an up-to-date, complete, accurate, and readily available baseline configuration of the information system.
- **CM-2 (3)**: The organization retains **organization-defined previous versions of baseline configurations of the previously approved baseline configuration of IS components** to support rollback.
- **CM-2 (7)**: The organization:
 (a)   Issues [Assignment: organization-defined information systems, system components, or devices] with [Assignment: organization-defined configurations] to individuals traveling to locations that the organization deems to be of significant risk; and
 (b)   Applies [Assignment: organization-defined security safeguards] to the devices when the individuals return.
- **CM-3**: The organization:
 a. Determines the types of changes to the information system that are configuration-controlled;
 b. Reviews proposed configuration-controlled changes to the information system and approves or disapproves such changes with explicit consideration for security impact analyses;
 c. Documents configuration change decisions associated with the information system;
 d. Implements approved configuration-controlled changes to the information system;
 e. Retains records of configuration-controlled changes to the information system for [Assignment: organization-defined time period];
 f. Audits and reviews activities associated with configuration-controlled changes to the information system; and
 g. Coordinates and provides oversight for configuration change control activities through [Assignment: organization-defined configuration change control element (e.g., committee, board] that convenes [Selection (one or more): [Assignment: organization-defined frequency]; [Assignment: organization-defined configuration change conditions]].
- **CM-3 (1)**: The organization employs automated mechanisms to:
 (a)   Document proposed changes to the information system;
 (b)   Notify [Assignment: organized-defined approval authorities] of proposed changes to the information system and request change approval;
 (c)   Highlight proposed changes to the information system that have not been approved or disapproved by [Assignment: organization-defined time period];
 (d)   Prohibit changes to the information system until designated approvals are received; 
 (e)   Document all changes to the information system; and
 (f) Notify [Assignment: organization-defined personnel] when approved changes to the information system are completed.
- **CM-3 (2)**: The organization tests, validates, and documents changes to the information system before implementing the changes on the operational system.
- **CM-3 (4)**: The organization requires an information security representative to be a member of the [Assignment: organization-defined configuration change control element].
- **CM-3 (6)**: The organization ensures that cryptographic mechanisms used to provide [Assignment: organization-defined security safeguards] are under configuration management.
- **CM-4**: The organization analyzes changes to the information system to determine potential security impacts prior to change implementation.
- **CM-4 (1)**: The organization analyzes changes to the information system in a separate test environment before implementation in an operational environment, looking for security impacts due to flaws, weaknesses, incompatibility, or intentional malice.
- **CM-5**: The organization defines, documents, approves, and enforces physical and logical access restrictions associated with changes to the information system.
- **CM-5 (1)**: The information system enforces access restrictions and supports auditing of the enforcement actions.
- **CM-5 (2)**: The organization reviews information system changes **at least every thirty (30) days** and [Assignment: organization-defined circumstances] to determine whether unauthorized changes have occurred.
- **CM-5 (3)**: The information system prevents the installation of [Assignment: organization-defined software and firmware components] without verification that the component has been digitally signed using a certificate that is recognized and approved by the organization.
- **CM-5 (5)**: The organization:
 (a)   Limits privileges to change information system components and system-related information within a production or operational environment; and
 (b)   Reviews and reevaluates privileges [Assignment: organization-defined frequency].
- **CM-6**: The organization:
 a. Establishes and documents configuration settings for information technology products employed within the information system using **United States Government Configuration Baseline (USGCB)** that reflect the most restrictive mode consistent with operational requirements;
 b. Implements the configuration settings;
 c. Identifies, documents, and approves any deviations from established configuration settings for [Assignment: organization-defined information system components] based on [Assignment: organization-defined operational requirements]; and
 d. Monitors and controls changes to the configuration settings in accordance with organizational policies and procedures.
- **CM-6 (1)**: The organization employs automated mechanisms to centrally manage, apply, and verify configuration settings for [Assignment: organization-defined information system components].
- **CM-6 (2)**: The organization employs [Assignment: organization-defined security safeguards] to respond to unauthorized changes to [Assignment: organization-defined configuration settings].
- **CM-7**: The organization:
 a. Configures the information system to provide only essential capabilities; and
 b. Prohibits or restricts the use of the following functions, ports, protocols, and/or services: **United States Government Configuration Baseline (USGCB)**.
- **CM-7 (1)**: The organization:
 (a)   Reviews the information system [Assignment: organization-defined frequency] to identify unnecessary and/or nonsecure functions, ports, protocols, and services; and
 (b)   Disables [Assignment: organization-defined functions, ports, protocols, and services within the information system deemed to be unnecessary and/or nonsecure].
- **CM-7 (2)**: The information system prevents program execution in accordance with [Selection (one or more): [Assignment: organization-defined policies regarding software program usage and restrictions]; rules authorizing the terms and conditions of software program usage].
- **CM-7 (5)**: The organization:
 (a)   Identifies [Assignment: organization-defined software programs authorized to execute on the information system];
 (b)   Employs a deny-all, permit-by-exception policy to allow the execution of authorized software programs on the information system; and
 (c)   Reviews and updates the list of authorized software programs [Assignment: organization- defined frequency].
- **CM-8**: The organization:
 a. Develops and documents an inventory of information system components that:
   1. Accurately reflects the current information system;
   2. Includes all components within the authorization boundary of the information system;
   3. Is at the level of granularity deemed necessary for tracking and reporting; and
   4. Includes [Assignment: organization-defined information deemed necessary to achieve effective information system component accountability]; and
 b. Reviews and updates the information system component inventory **at least monthly**.
- **CM-8 (1)**: The organization updates the inventory of information system components as an integral part of component installations, removals, and information system updates.
- **CM-8 (2)**: The organization employs automated mechanisms to help maintain an up-to-date, complete, accurate, and readily available inventory of information system components.
- **CM-8 (3)**: The organization:
 (a)   Employs automated mechanisms [Assignment: organization-defined frequency] to detect the presence of unauthorized hardware, software, and firmware components within the information system; and
 (b)   Takes the following actions when unauthorized components are detected: [Selection (one or more): disables network access by such components; isolates the components; notifies [Assignment: organization-defined personnel or roles]].
- **CM-8 (4)**: The organization includes in the information system component inventory information, a means for identifying by [Selection (one or more): name; position; role], individuals responsible/accountable for administering those components.
- **CM-8 (5)**: The organization verifies that all components within the authorization boundary of the information system are not duplicated in other information system inventories.
- **CM-9**: The organization develops, documents, and implements a configuration management plan for the information system that:
 a. Addresses roles, responsibilities, and configuration management processes and procedures;
 b. Establishes a process for identifying configuration items throughout the system development life cycle and for managing the configuration of the configuration items;
 c. Defines the configuration items for the information system and places the configuration items under configuration management; and
 d. Protects the configuration management plan from unauthorized disclosure and modification.
- **CM-10**: The organization:
a. Uses software and associated documentation in accordance with contract agreements and copyright laws;
b. Tracks the use of software and associated documentation protected by quantity licenses to control copying and distribution; and
c. Controls and documents the use of peer-to-peer file sharing technology to ensure that this capability is not used for the unauthorized distribution, display, performance, or reproduction of copyrighted work.
- **CM-10 (1)**: The organization establishes the following restrictions on the use of open source software: [Assignment: organization-defined restrictions].
- **CM-11**: The organization:
 a. Establishes [Assignment: organization-defined policies] governing the installation of software by users;
 b. Enforces software installation policies through [Assignment: organization-defined methods]; and
 c. Monitors policy compliance at **Continuously (via CM-7 (5))**.
- **CM-11 (1)**: The information system alerts [Assignment: organization-defined personnel or roles] when the unauthorized installation of software is detected.

### CONTINGENCY PLANNING

- **CP-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A contingency planning policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the contingency planning policy and associated contingency planning controls; and
 b. Reviews and updates the current:
   1. Contingency planning policy **at least annually**; and
   2. Contingency planning procedures **at least annually or whenever a significant change occurs**.
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
- **CP-2 (1)**: The organization coordinates contingency plan development with organizational elements responsible for related plans.
- **CP-2 (2)**: The organization conducts capacity planning so that necessary capacity for information processing, telecommunications, and environmental support exists during contingency operations.
- **CP-2 (3)**: The organization plans for the resumption of essential missions and business functions within
[Assignment: organization-defined time period] of contingency plan activation.
- **CP-2 (4)**: The organization plans for the resumption of all missions and business functions within
**time period defined in service provider and organization  SLA** of contingency plan activation.
- **CP-2 (5)**: The organization plans for the continuance of essential missions and business functions with little or no loss of operational continuity and sustains that continuity until full information system restoration at primary processing and/or storage sites.
- **CP-2 (8)**: The organization identifies critical information system assets supporting essential missions and business functions.
- **CP-3**: The organization provides contingency training to information system users consistent with assigned roles and responsibilities:
 a. Within **ten (10) days** of assuming a contingency role or responsibility;
 b. When required by information system changes; and
 c. **at least annually** thereafter.
- **CP-3 (1)**: The organization incorporates simulated events into contingency training to facilitate effective response by personnel in crisis situations.
- **CP-4**: The organization:
 a. Tests the contingency plan for the information system **at least annually** using **functional exercises** to determine the effectiveness of the plan and the organizational readiness to execute the plan;
 b. Reviews the contingency plan test results; and
 c. Initiates corrective actions, if needed.
- **CP-4 (1)**: The organization coordinates contingency plan testing with organizational elements responsible for related plans.
- **CP-4 (2)**: The organization tests the contingency plan at the alternate processing site:
 (a)   To familiarize contingency personnel with the facility and available resources; and
 (b)   To evaluate the capabilities of the alternate processing site to support contingency operations.
- **CP-6**: The organization:
 a. Establishes an alternate storage site including necessary agreements to permit the storage and retrieval of information system backup information; and
 b. Ensures that the alternate storage site provides information security safeguards equivalent to that of the primary site.
- **CP-6 (1)**: The organization identifies an alternate storage site that is separated from the primary storage site to reduce susceptibility to the same threats.
- **CP-6 (2)**: The organization configures the alternate storage site to facilitate recovery operations in accordance with recovery time and recovery point objectives.
- **CP-6 (3)**: The organization identifies potential accessibility problems to the alternate storage site in the event of an area-wide disruption or disaster and outlines explicit mitigation actions.
- **CP-7**: The organization:
 a. Establishes an alternate processing site including necessary agreements to permit the transfer and resumption of [Assignment: organization-defined information system operations] for essential missions/business functions within [Assignment: organization-defined time period consistent with recovery time and recovery point objectives] when the primary processing capabilities are unavailable;
 b. Ensures that equipment and supplies required to transfer and resume operations are available at the alternate processing site or contracts are in place to support delivery to the site within the organization-defined time period for transfer/resumption; and 
 c. Ensures that the alternate processing site provides information security safeguards equivalent to that of the primary site.
- **CP-7 (1)**: The organization identifies an alternate processing site that is separated from the primary processing site to reduce susceptibility to the same threats.
- **CP-7 (2)**: The organization identifies potential accessibility problems to the alternate processing site in the event of an area-wide disruption or disaster and outlines explicit mitigation actions.
- **CP-7 (3)**: The organization develops alternate processing site agreements that contain priority-of-service provisions in accordance with organizational availability requirements (including recovery time objectives).
- **CP-7 (4)**: The organization prepares the alternate processing site so that the site is ready to be used as the operational site supporting essential missions and business functions.
- **CP-8**: The organization establishes alternate telecommunications services including necessary agreements to permit the resumption of [Assignment: organization-defined information system operations] for essential missions and business functions within [Assignment: organization- defined time period] when the primary telecommunications capabilities are unavailable at either the primary or alternate processing or storage sites.
- **CP-8 (1)**: The organization:
 (a)   Develops primary and alternate telecommunications service agreements that contain priority- of-service provisions in accordance with organizational availability requirements (including recovery time objectives); and
 (b)   Requests Telecommunications Service Priority for all telecommunications services used for national security emergency preparedness in the event that the primary and/or alternate telecommunications services are provided by a common carrier.
- **CP-8 (2)**: The organization obtains alternate telecommunications services to reduce the likelihood of sharing a single point of failure with primary telecommunications services.
- **CP-8 (3)**: The organization obtains alternate telecommunications services from providers that are separated from primary service providers to reduce susceptibility to the same threats.
- **CP-8 (4)**: The organization:
 (a)   Requires primary and alternate telecommunications service providers to have contingency plans;
 (b)   Reviews provider contingency plans to ensure that the plans meet organizational contingency requirements; and
 (c)   Obtains evidence of contingency testing/training by providers [Assignment: organization- defined frequency].
- **CP-9**: The organization:
a. Conducts backups of user-level information contained in the information system **daily incremental; weekly full**;
b. Conducts backups of system-level information contained in the information system **daily incremental; weekly full**;
c. Conducts backups of information system documentation including security-related documentation **daily incremental; weekly full**; and
d. Protects the confidentiality, integrity, and availability of backup information at storage locations.
- **CP-9 (1)**: The organization tests backup information **at least monthly** to verify media reliability and information integrity.
- **CP-9 (2)**: The organization uses a sample of backup information in the restoration of selected information system functions as part of contingency plan testing.
- **CP-9 (3)**: The organization stores backup copies of [Assignment: organization-defined critical information system software and other security-related information] in a separate facility or in a fire-rated container that is not collocated with the operational system.
- **CP-9 (5)**: The organization transfers information system backup information to the alternate storage site **time period and transfer rate consistent with the recovery time and recovery point objectives defined in the service provider and organization  SLA**.
- **CP-10**: The organization provides for the recovery and reconstitution of the information system to a known state after a disruption, compromise, or failure.
- **CP-10 (2)**: The information system implements transaction recovery for systems that are transaction-based.
- **CP-10 (4)**: The organization provides the capability to restore information system components within **time period consistent with the restoration time-periods defined in the service provider and organization  SLA** from configuration-controlled and integrity-protected information representing a known, operational state for the components.

### IDENTIFICATION AND AUTHENTICATION

- **IA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. An identification and authentication policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the identification and authentication policy and associated identification and authentication controls; and
 b. Reviews and updates the current:
   1. Identification and authentication policy **at least annually**; and
   2. Identification and authentication procedures **at least annually or whenever a significant change occurs**.
- **IA-2**: The information system uniquely identifies and authenticates organizational users (or processes acting on behalf of organizational users).
- **IA-2 (1)**: The information system implements multifactor authentication for network access to privileged accounts.
- **IA-2 (2)**: The information system implements multifactor authentication for network access to non- privileged accounts.
- **IA-2 (3)**: The information system implements multifactor authentication for local access to privileged accounts.
- **IA-2 (4)**: The information system implements multifactor authentication for local access to non-privileged accounts.
- **IA-2 (5)**: The organization requires individuals to be authenticated with an individual authenticator when a group authenticator is employed.
- **IA-2 (8)**: The information system implements replay-resistant authentication mechanisms for network access to privileged accounts.
- **IA-2 (9)**: The information system implements replay-resistant authentication mechanisms for network access to non-privileged accounts.
- **IA-2 (11)**: The information system implements multifactor authentication for remote access to privileged and non-privileged accounts such that one of the factors is provided by a device separate from the system gaining access and the device meets **FIPS 140-2, NIAP Certification, or NSA approval**.
- **IA-2 (12)**: The information system accepts and electronically verifies Personal Identity Verification (PIV)
credentials.
- **IA-3**: The information system uniquely identifies and authenticates [Assignment: organization- defined specific and/or types of devices] before establishing a [Selection (one or more): local; remote; network] connection.
- **IA-4**: The organization manages information system identifiers by:
 a. Receiving authorization from **at a minimum, the ISSO (or similar role within the organization)** to assign an individual, group, role, or device identifier;
 b. Selecting an identifier that identifies an individual, group, role, or device;
 c. Assigning the identifier to the intended individual, group, role, or device;
 d. Preventing reuse of identifiers for **at least two (2) years**; and
 e. Disabling the identifier after **thirty-five (35) days**.
- **IA-4 (4)**: The organization manages individual identifiers by uniquely identifying each individual as
**contractors; foreign nationals**.
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
- **IA-5 (2)**: The information system, for PKI-based authentication:
 (a)   Validates certifications by constructing and verifying a certification path to an accepted trust anchor including checking certificate status information;
 (b)   Enforces authorized access to the corresponding private key;
 (c)   Maps the authenticated identity to the account of the individual or group; and
 (d)   Implements a local cache of revocation data to support path discovery and validation in case of inability to access revocation information via the network.
- **IA-5 (3)**: The organization requires that the registration process to receive **All hardware/biometric (multifactor authenticators** be conducted [Selection: in person; by a trusted third party] before **in person** with authorization by [Assignment: organization-defined personnel or roles].
- **IA-5 (4)**: The organization employs automated tools to determine if password authenticators are sufficiently strong to satisfy **complexity as identified in IA-5 (1) Control Enhancement Part (a)**.
- **IA-5 (6)**: The organization protects authenticators commensurate with the security category of the information to which use of the authenticator permits access.
- **IA-5 (7)**: The organization ensures that unencrypted static authenticators are not embedded in applications or access scripts or stored on function keys.
- **IA-5 (8)**: The organization implements **different authenticators on different systems** to manage the risk of compromise due to individuals having accounts on multiple information systems.
- **IA-5 (11)**: The information system, for hardware token-based authentication, employs mechanisms that satisfy [Assignment: organization-defined token quality requirements].
- **IA-5 (13)**: The information system prohibits the use of cached authenticators after [Assignment: organization-defined time period].
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
   1. Incident response policy **at least annually**; and
   2. Incident response procedures **at least annually or whenever a significant change occurs**.
- **IR-2**: The organization provides incident response training to information system users consistent with assigned roles and responsibilities:
 a. Within **within ten (10) days** of assuming an incident response role or responsibility;
 b. When required by information system changes; and
 c. **at least annually** thereafter.
- **IR-2 (1)**: The organization incorporates simulated events into incident response training to facilitate effective response by personnel in crisis situations.
- **IR-2 (2)**: The organization employs automated mechanisms to provide a more thorough and realistic incident response training environment.
- **IR-3**: The organization tests the incident response capability for the information system **at least every six (6) months** using [Assignment: organization-defined tests] to determine the incident response effectiveness and documents the results.
- **IR-3 (2)**: The organization coordinates incident response testing with organizational elements responsible for related plans.
- **IR-4**: The organization:
a. Implements an incident handling capability for security incidents that includes preparation, detection and analysis, containment, eradication, and recovery;
b. Coordinates incident handling activities with contingency planning activities; and
c. Incorporates lessons learned from ongoing incident handling activities into incident response procedures, training, and testing/exercises, and implements the resulting changes accordingly.
- **IR-4 (1)**: The organization employs automated mechanisms to support the incident handling process.
- **IR-4 (2)**: The organization includes dynamic reconfiguration of **all network, data storage, and computing devices** as part of the incident response capability.
- **IR-4 (3)**: The organization identifies [Assignment: organization-defined classes of incidents] and [Assignment: organization-defined actions to take in response to classes of incidents] to ensure continuation of organizational missions and business functions.
- **IR-4 (4)**: The organization correlates incident information and individual incident responses to achieve an organization-wide perspective on incident awareness and response.
- **IR-4 (6)**: The organization implements incident handling capability for insider threats.
- **IR-4 (8)**: The organization coordinates with **external organizations including consumer incident responders and network defenders and the appropriate CIRT/CERT (such as US-CERT, DOD CERT, IC CERT)** to correlate and share [Assignment: organization-defined incident information] to achieve a cross- organization perspective on incident awareness and more effective incident responses.
- **IR-5**: The organization tracks and documents information system security incidents.
- **IR-5 (1)**: The organization employs automated mechanisms to assist in the tracking of security incidents and in the collection and analysis of incident information.
- **IR-6**: The organization:
 a. Requires personnel to report suspected security incidents to the organizational incident response capability within **US-CERT incident reporting timelines as specified in NIST Special Publication 800-61 (as amended)**; and
 b. Reports security incident information to [Assignment: organization-defined authorities].
- **IR-6 (1)**: The organization employs automated mechanisms to assist in the reporting of security incidents.
- **IR-7**: The organization provides an incident response support resource, integral to the organizational incident response capability that offers advice and assistance to users of the information system for the handling and reporting of security incidents.
- **IR-7 (1)**: The organization employs automated mechanisms to increase the availability of incident response- related information and support.
- **IR-7 (2)**: The organization:
 (a)   Establishes a direct, cooperative relationship between its incident response capability and external providers of information system protection capability; and
 (b)   Identifies organizational incident response team members to the external providers.
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
- **IR-9**: The organization responds to information spills by:
 a. Identifying the specific information involved in the information system contamination;
 b. Alerting [Assignment: organization-defined personnel or roles] of the information spill using a method of communication not associated with the spill;
 c. Isolating the contaminated information system or system component;
 d. Eradicating the information from the contaminated information system or component;
 e. Identifying other information systems or system components that may have been subsequently contaminated; and
 f. Performing other [Assignment: organization-defined actions].
- **IR-9 (1)**: The organization assigns [Assignment: organization-defined personnel or roles] with responsibility for responding to information spills.
- **IR-9 (2)**: The organization provides information spillage response training **at least annually**.
- **IR-9 (3)**: The organization implements [Assignment: organization-defined procedures] to ensure that organizational personnel impacted by information spills can continue to carry out assigned tasks while contaminated systems are undergoing corrective actions.
- **IR-9 (4)**: The organization employs [Assignment: organization-defined security safeguards] for personnel exposed to information not within assigned access authorizations.

### MAINTENANCE

- **MA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A system maintenance policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the system maintenance policy and associated system maintenance controls; and
 b. Reviews and updates the current:
   1. System maintenance policy **at least annually**; and
   2. System maintenance procedures **at least annually or whenever a significant change occurs**.
- **MA-2**: The organization:
 a. Schedules, performs, documents, and reviews records of maintenance and repairs on information system components in accordance with manufacturer or vendor specifications and/or organizational requirements;
 b. Approves and monitors all maintenance activities, whether performed on site or remotely and whether the equipment is serviced on site or removed to another location;
 c. Requires that [Assignment: organization-defined personnel or roles] explicitly approve the removal of the information system or system components from organizational facilities for off-site maintenance or repairs;
 d. Sanitizes equipment to remove all information from associated media prior to removal from organizational facilities for off-site maintenance or repairs;
 e. Checks all potentially impacted security controls to verify that the controls are still functioning properly following maintenance or repair actions; and
 f. Includes [Assignment: organization-defined maintenance-related information] in organizational maintenance records.
- **MA-2 (2)**: The organization:
 (a)   Employs automated mechanisms to schedule, conduct, and document maintenance and repairs; and
 (b)   Produces up-to date, accurate, and complete records of all maintenance and repair actions requested, scheduled, in process, and completed.
- **MA-3**: The organization approves, controls, and monitors information system maintenance tools.
- **MA-3 (1)**: The organization inspects the maintenance tools carried into a facility by maintenance personnel for improper or unauthorized modifications.
- **MA-3 (2)**: The organization checks media containing diagnostic and test programs for malicious code before the media are used in the information system.
- **MA-3 (3)**: The organization prevents the unauthorized removal of maintenance equipment containing organizational information by:
 (a)   Verifying that there is no organizational information contained on the equipment; 
 (b)   Sanitizing or destroying the equipment;
 (c)   Retaining the equipment within the facility; or
 (d)   Obtaining an exemption from [Assignment: organization-defined personnel or roles] explicitly authorizing removal of the equipment from the facility.
- **MA-4**: The organization:
 a. Approves and monitors nonlocal maintenance and diagnostic activities;
 b. Allows the use of nonlocal maintenance and diagnostic tools only as consistent with organizational policy and documented in the security plan for the information system;
 c. Employs strong authenticators in the establishment of nonlocal maintenance and diagnostic sessions;
 d. Maintains records for nonlocal maintenance and diagnostic activities; and
 e. Terminates session and network connections when nonlocal maintenance is completed.
- **MA-4 (2)**: The organization documents in the security plan for the information system, the policies and procedures for the establishment and use of nonlocal maintenance and diagnostic connections.
- **MA-4 (3)**: The organization:
 (a)   Requires that nonlocal maintenance and diagnostic services be performed from an information system that implements a security capability comparable to the capability implemented on the system being serviced; or
 (b)   Removes the component to be serviced from the information system and prior to nonlocal maintenance or diagnostic services, sanitizes the component (with regard to organizational information) before removal from organizational facilities, and after the service is performed, inspects and sanitizes the component (with regard to potentially malicious software) before reconnecting the component to the information system.
- **MA-4 (6)**: The information system implements cryptographic mechanisms to protect the integrity and confidentiality of nonlocal maintenance and diagnostic communications.
- **MA-5**: The organization:
 a. Establishes a process for maintenance personnel authorization and maintains a list of authorized maintenance organizations or personnel;
 b. Ensures that non-escorted personnel performing maintenance on the information system have required access authorizations; and
 c. Designates organizational personnel with required access authorizations and technical competence to supervise the maintenance activities of personnel who do not possess the required access authorizations.
- **MA-5 (1)**: The organization:
 (a)   Implements procedures for the use of maintenance personnel that lack appropriate security clearances or are not U.S. citizens, that include the following requirements:
    (1)   Maintenance personnel who do not have needed access authorizations, clearances, or formal access approvals are escorted and supervised during the performance of maintenance and diagnostic activities on the information system by approved organizational personnel who are fully cleared, have appropriate access authorizations, and are technically qualified;
   (2)   Prior to initiating maintenance or diagnostic activities by personnel who do not have needed access authorizations, clearances or formal access approvals, all volatile information storage components within the information system are sanitized and all nonvolatile storage media are removed or physically disconnected from the system and secured; and
 (b)   Develops and implements alternate security safeguards in the event an information system component cannot be sanitized, removed, or disconnected from the system.
- **MA-6**: The organization obtains maintenance support and/or spare parts for [Assignment: organization-defined information system components] within [Assignment: organization-defined time period] of failure.

### MEDIA PROTECTION

- **MP-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A media protection policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the media protection policy and associated media protection controls; and
 b. Reviews and updates the current:
   1. Media protection policy **at least annually**; and
   2. Media protection procedures **at least annually or whenever a significant change occurs**.
- **MP-2**: The organization restricts access to **any digital and non-digital media deemed sensitive** to [Assignment: organization-defined personnel or roles].
- **MP-3**: The organization:
 a. Marks information system media indicating the distribution limitations, handling caveats, and applicable security markings (if any) of the information; and
 b. Exempts **no removable media types** from marking as long as the media remain within **organization-defined security safeguards not applicable**.
- **MP-4**: The organization:
 a. Physically controls and securely stores **all types of digital and non-digital media with sensitive information** within **see additional FedRAMP requirements and guidance**; and
 b. Protects information system media until the media are destroyed or sanitized using approved equipment, techniques, and procedures.
- **MP-5**: The organization:
 a. Protects and controls [Assignment: organization-defined types of information system media] during transport outside of controlled areas using [Assignment: organization-defined security safeguards];
 b. Maintains accountability for information system media during transport outside of controlled areas;
 c. Documents activities associated with the transport of information system media; and
 d. Restricts the activities associated with the transport of information system media to authorized personnel.
- **MP-5 (4)**: The information system implements cryptographic mechanisms to protect the confidentiality and integrity of information stored on digital media during transport outside of controlled areas.
- **MP-6**: The organization:
 a. Sanitizes **techniques and procedures IAW NIST SP 800-88 and Section 5.9: Reuse and Disposal of Storage Media and Hardware** prior to disposal, release out of organizational control, or release for reuse using [Assignment: organization- defined sanitization techniques and procedures] in accordance with applicable federal and organizational standards and policies; and
 b. Employs sanitization mechanisms with the strength and integrity commensurate with the security category or classification of the information.
- **MP-6 (1)**: The organization reviews, approves, tracks, documents, and verifies media sanitization and disposal actions.
- **MP-6 (2)**: The organization tests sanitization equipment and procedures **at least every six (6) months** to verify that the intended sanitization is being achieved.
- **MP-6 (3)**: The organization applies non-destructive sanitization techniques to portable storage devices prior to connecting such devices to the information system under the following circumstances: [Assignment: organization-defined circumstances requiring sanitization of portable storage devices].
- **MP-7**: The organization [Selection: restricts; prohibits] the use of [Assignment: organization- defined types of information system media] on [Assignment: organization-defined information systems or system components] using [Assignment: organization-defined security safeguards].
- **MP-7 (1)**: The organization prohibits the use of portable storage devices in organizational information systems when such devices have no identifiable owner.

### PHYSICAL AND ENVIRONMENTAL PROTECTION

- **PE-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A physical and environmental protection policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the physical and environmental protection policy and associated physical and environmental protection controls; and
 b. Reviews and updates the current:
   1. Physical and environmental protection policy **at least annually**; and
   2. Physical and environmental protection procedures **at least annually or whenever a significant change occurs**.
- **PE-2**: The organization:
 a. Develops, approves, and maintains a list of individuals with authorized access to the facility where the information system resides;
 b. Issues authorization credentials for facility access;
 c. Reviews the access list detailing authorized facility access by individuals **at least every ninety (90) days**; and
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
- **PE-3 (1)**: The organization enforces physical access authorizations to the information system in addition to the physical access controls for the facility at [Assignment: organization-defined physical spaces containing one or more components of the information system].
- **PE-4**: The organization controls physical access to [Assignment: organization-defined information system distribution and transmission lines] within organizational facilities using [Assignment: organization-defined security safeguards].
- **PE-5**: The organization controls physical access to information system output devices to prevent unauthorized individuals from obtaining the output.
- **PE-6**: The organization:
 a. Monitors physical access to the facility where the information system resides to detect and respond to physical security incidents;
 b. Reviews physical access logs **at least monthly** and upon occurrence of [Assignment: organization-defined events or potential indications of events]; and
 c. Coordinates results of reviews and investigations with the organizational incident response capability.
- **PE-6 (1)**: The organization monitors physical intrusion alarms and surveillance equipment.
- **PE-6 (4)**: The organization monitors physical access to the information system in addition to the physical access monitoring of the facility as [Assignment: organization-defined physical spaces containing one or more components of the information system].
- **PE-8**: The organization:
 a. Maintains visitor access records to the facility where the information system resides for **for a minimum of one (1) year**; and
 b. Reviews visitor access records **at least monthly**.
- **PE-8 (1)**: The organization employs automated mechanisms to facilitate the maintenance and review of visitor access records.
- **PE-9**: The organization protects power equipment and power cabling for the information system from damage and destruction.
- **PE-10**: The organization:
 a. Provides the capability of shutting off power to the information system or individual system components in emergency situations;
 b. Places emergency shutoff switches or devices in [Assignment: organization-defined location by information system or system component] to facilitate safe and easy access for personnel; and
 c. Protects emergency power shutoff capability from unauthorized activation.
- **PE-11**: The organization provides a short-term uninterruptible power supply to facilitate [Selection (one or more): an orderly shutdown of the information system; transition of the information system to long-term alternate power] in the event of a primary power source loss.
- **PE-11 (1)**: The organization provides a long-term alternate power supply for the information system that is capable of maintaining minimally required operational capability in the event of an extended loss of the primary power source.
- **PE-12**: The organization employs and maintains automatic emergency lighting for the information system that activates in the event of a power outage or disruption and that covers emergency exits and evacuation routes within the facility.
- **PE-13**: The organization employs and maintains fire suppression and detection devices/systems for the information system that are supported by an independent energy source.
- **PE-13 (1)**: The organization employs fire detection devices/systems for the information system that activate automatically and notify **service provider building maintenance/physical security personnel** and **service provider emergency responders with incident response responsibilities** in the event of a fire.
- **PE-13 (2)**: The organization employs fire suppression devices/systems for the information system that provide automatic notification of any activation to Assignment: organization-defined personnel or roles] and [Assignment: organization-defined emergency responders].
- **PE-13 (3)**: The organization employs an automatic fire suppression capability for the information system when the facility is not staffed on a continuous basis.
- **PE-14**: The organization:
 a. Maintains temperature and humidity levels within the facility where the information system resides at **consistent with American Society of Heating, Refrigerating and Air-conditioning Engineers (ASHRAE) document entitled Thermal Guidelines for Data Processing Environments**; and
 b. Monitors temperature and humidity levels **continuously**.
- **PE-14 (2)**: The organization employs temperature and humidity monitoring that provides an alarm or notification of changes potentially harmful to personnel or equipment.
- **PE-15**: The organization protects the information system from damage resulting from water leakage by providing master shutoff or isolation valves that are accessible, working properly, and known to key personnel.
- **PE-15 (1)**: The organization employs automated mechanisms to detect the presence of water in the vicinity of the information system and alerts **service provider building maintenance/physical security personnel**.
- **PE-16**: The organization authorizes, monitors, and controls **all information system components** entering and exiting the facility and maintains records of those items.
- **PE-17**: The organization:
 a. Employs [Assignment: organization-defined security controls] at alternate work sites;
 b. Assesses as feasible, the effectiveness of security controls at alternate work sites; and
 c. Provides a means for employees to communicate with information security personnel in case of security incidents or problems.
- **PE-18**: The organization positions information system components within the facility to minimize potential damage from **physical and environmental hazards identified during threat assessment** and to minimize the opportunity for unauthorized access.

### PLANNING

- **PL-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A security planning policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the security planning policy and associated security planning controls; and
 b. Reviews and updates the current:
   1. Security planning policy **at least annually**; and
   2. Security planning procedures **at least annually or whenever a significant change occurs**.
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
- **PL-2 (3)**: The organization plans and coordinates security-related activities affecting the information system with [Assignment: organization-defined individuals or groups] before conducting such activities in order to reduce the impact on other organizational entities.
- **PL-4**: The organization:
 a. Establishes and makes readily available to individuals requiring access to the information system, the rules that describe their responsibilities and expected behavior with regard to information and information system usage;
 b. Receives a signed acknowledgment from such individuals, indicating that they have read, understand, and agree to abide by the rules of behavior, before authorizing access to information and the information system;
 c. Reviews and updates the rules of behavior **annually**; and d. Requires individuals who have signed a previous version of the rules of behavior to read and
resign when the rules of behavior are revised/updated.
- **PL-4 (1)**: The organization includes in the rules of behavior, explicit restrictions on the use of social media/networking sites and posting organizational information on public websites.
- **PL-8**: The organization:
 a. Develops an information security architecture for the information system that:
   1. Describes the overall philosophy, requirements, and approach to be taken with regard to protecting the confidentiality, integrity, and availability of organizational information;
   2. Describes how the information security architecture is integrated into and supports the enterprise architecture; and
   3. Describes any information security assumptions about, and dependencies on, external services;
 b. Reviews and updates the information security architecture **at least annually or when a significant change occurs** to reflect updates in the enterprise architecture; and
 c. Ensures that planned information security architecture changes are reflected in the security plan, the security Concept of Operations (CONOPS), and organizational procurements/acquisitions.

### PERSONNEL SECURITY

- **PS-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A personnel security policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the personnel security policy and associated personnel security controls; and
 b. Reviews and updates the current:
   1. Personnel security policy **at least annually**; and
   2. Personnel security procedures **at least annually or whenever a significant change occurs**.
- **PS-2**: The organization:
 a. Assigns a risk designation to all organizational positions;
 b. Establishes screening criteria for individuals filling those positions; and
 c. Reviews and updates position risk designations **at least annually**.
- **PS-3**: The organization:
 a. Screens individuals prior to authorizing access to the information system; and
 b. Rescreens individuals according to [Assignment: organization-defined conditions requiring rescreening and, where rescreening is so indicated, the frequency of such rescreening].
- **PS-3 (3)**: The organization ensures that individuals accessing an information system processing, storing, or transmitting information requiring special protection:
 (a)   Have valid access authorizations that are demonstrated by assigned official government duties; and
 (b)   Satisfy [Assignment: organization-defined additional personnel screening criteria].
- **PS-4**: The organization, upon termination of individual employment:
 a. Disables information system access within **eight (8) hours**;
 b. Terminates/revokes any authenticators/credentials associated with the individual;
 c. Conducts exit interviews that include a discussion of [Assignment: organization-defined information security topics];
 d. Retrieves all security-related organizational information system-related property;
 e. Retains access to organizational information and information systems formerly controlled by terminated individual; and
 f. Notifies [Assignment: organization-defined personnel or roles] within [Assignment: organization-defined time period].
- **PS-4 (2)**: The organization employs automated mechanisms to notify **access control personnel responsible for disabling access to the system** upon termination of an individual.
- **PS-5**: The organization:
 a. Reviews and confirms ongoing operational need for current logical and physical access authorizations to information systems/facilities when individuals are reassigned or transferred to other positions within the organization;
 b. Initiates **twenty-four (24) hours** within [Assignment: organization-defined time period following the formal transfer action];
 c. Modifies access authorization as needed to correspond with any changes in operational need due to reassignment or transfer; and
 d. Notifies **twenty-four (24) hours** within [Assignment: organization-defined time period].
- **PS-6**: The organization:
 a. Develops and documents access agreements for organizational information systems;
 b. Reviews and updates the access agreements **at least annually**; and
 c. Ensures that individuals requiring access to organizational information and information systems:
   1. Sign appropriate access agreements prior to being granted access; and
   2. Re-sign access agreements to maintain access to organizational information systems when access agreements have been updated or **at least annually and any time there is a change to the user's level of access**.
- **PS-7**: The organization:
 a. Establishes personnel security requirements including security roles and responsibilities for third-party providers;
 b. Requires third-party providers to comply with personnel security policies and procedures established by the organization;
 c. Documents personnel security requirements;
 d. Requires third-party providers to notify **terminations: immediately; transfers: within twenty-four (24) hours** of any personnel transfers or terminations of third-party personnel who possess organizational credentials and/or badges, or who have information system privileges within [Assignment: organization-defined time period]; and
 e. Monitors provider compliance.
- **PS-8**: The organization:
 a. Employs a formal sanctions process for individuals failing to comply with established information security policies and procedures; and
 b. Notifies **at a minimum, the ISSO and/or similar role within the organization** within [Assignment: organization-defined time period] when a formal employee sanctions process is initiated, identifying the individual sanctioned and the reason for the sanction.

### RISK ASSESSMENT

- **RA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A risk assessment policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the risk assessment policy and associated risk assessment controls; and
 b. Reviews and updates the current:
   1. Risk assessment policy **at least annually**; and
   2. Risk assessment procedures **at least annually or whenever a significant change occurs**.
- **RA-2**: The organization:
 a. Categorizes information and the information system in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance;
 b. Documents the security categorization results (including supporting rationale) in the security plan for the information system; and
 c. Ensures that the security categorization decision is reviewed and approved by the authorizing official or authorizing official designated representative.
- **RA-3**: The organization:
 a. Conducts an assessment of risk, including the likelihood and magnitude of harm, from the unauthorized access, use, disclosure, disruption, modification, or destruction of the information system and the information it processes, stores, or transmits;
 b. Documents risk assessment results in [Selection: security plan; risk assessment report; **security assessment report**];
 c. Reviews risk assessment results **at least annually or whenever a significant change occurs**;
 d. Disseminates risk assessment results to [Assignment: organization-defined personnel or roles]; and
 e. Updates the risk assessment **annually** or whenever there are significant changes to the information system or environment of operation (including the identification of new threats and vulnerabilities), or other conditions that may impact the security state of the system.
- **RA-5**: The organization:
 a. Scans for vulnerabilities in the information system and hosted applications **monthly operating system/infrastructure; monthly web applications and databases** and when new vulnerabilities potentially affecting the system/applications are identified and reported;
 b. Employs vulnerability scanning tools and techniques that facilitate interoperability among tools and automate parts of the vulnerability management process by using standards for:
   1. Enumerating platforms, software flaws, and improper configurations;
   2. Formatting checklists and test procedures; and
   3. Measuring vulnerability impact;
 c. Analyzes vulnerability scan reports and results from security control assessments;
 d. Remediates legitimate vulnerabilities **high-risk vulnerabilities mitigated within thirty (30) days from date of discovery; moderate-risk vulnerabilities mitigated within ninety (90) days from date of discovery; low risk vulnerabilities mitigated within one hundred and eighty (180) days from date of discovery**, in accordance with an organizational assessment of risk; and
 e. Shares information obtained from the vulnerability scanning process and security control assessments with [Assignment: organization-defined personnel or roles] to help eliminate similar vulnerabilities in other information systems (i.e., systemic weaknesses or deficiencies).
- **RA-5 (1)**: The organization employs vulnerability scanning tools that include the capability to readily update the information system vulnerabilities to be scanned.
- **RA-5 (2)**: The organization updates the information system vulnerabilities scanned [Selection (one or more): **prior to a new scan**; prior to a new scan; when new vulnerabilities are identified and reported].
- **RA-5 (3)**: The organization employs vulnerability scanning procedures that can identify the breadth and depth of coverage (i.e., information system components scanned and vulnerabilities checked).
- **RA-5 (4)**: The organization determines what information about the information system is discoverable by adversaries and subsequently takes **notify appropriate service provider personnel and follow procedures for organization  and service provider-defined corrective actions**.
- **RA-5 (5)**: The information system implements privileged access authorization to **operating systems / web applications / databases** for selected **all scans**.
- **RA-5 (6)**: The organization employs automated mechanisms to compare the results of vulnerability scans over time to determine trends in information system vulnerabilities.
- **RA-5 (8)**: The organization reviews historic audit logs to determine if a vulnerability identified in the information system has been previously exploited.
- **RA-5 (10)**: The organization correlates the output from vulnerability scanning tools to determine the presence of multi-vulnerability/multi-hop attack vectors.

### SYSTEM AND SERVICES ACQUISITION

- **SA-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A system and services acquisition policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the system and services acquisition policy and associated system and services acquisition controls; and
 b. Reviews and updates the current:
   1. System and services acquisition policy **at least annually**; and
   2.  System and services acquisition procedures **at least annually or whenever a significant change occurs**.
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
- **SA-4 (1)**: The organization requires the developer of the information system, system component, or information system service to provide a description of the functional properties of the security controls to be employed.
- **SA-4 (2)**: The organization requires the developer of the information system, system component, or information system service to provide design and implementation information for the security controls to be employed that includes: [Selection (one or more): security-relevant external system interfaces; high-level design; low-level design; source code or hardware schematics; **organization-defined design/implementation information]**] at [Assignment: organization-defined level of detail].
- **SA-4 (8)**: The organization requires the developer of the information system, system component, or information system service to produce a plan for the continuous monitoring of security control effectiveness that contains **at least the minimum requirement as defined in control CA-7**.
- **SA-4 (9)**: The organization requires the developer of the information system, system component, or information system service to identify early in the system development life cycle, the functions, ports, protocols, and services intended for organizational use.
- **SA-4 (10)**: The organization employs only information technology products on the FIPS 201-approved products list for Personal Identity Verification (PIV) capability implemented within organizational information systems.
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
- **SA-8**: The organization applies information system security engineering principles in the specification, design, development, implementation, and modification of the information system.
- **SA-9**: The organization:
 a. Requires that providers of external information system services comply with organizational information security requirements and employ **FedRAMP Security Controls Baseline(s) if Federal information is processed or stored within the external system** in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and guidance;
 b. Defines and documents government oversight and user roles and responsibilities with regard to external information system services; and
 c. Employs **Federal/FedRAMP Continuous Monitoring requirements must be met for external systems where Federal information is processed or stored** to monitor security control compliance by external service providers on an ongoing basis.
- **SA-9 (1)**: The organization:
 (a)   Conducts an organizational assessment of risk prior to the acquisition or outsourcing of dedicated information security services; and
 (b)   Ensures that the acquisition or outsourcing of dedicated information security services is approved by [Assignment: organization-defined personnel or roles].
- **SA-9 (2)**: The organization requires providers of **all external systems where Federal information is processed or stored** to identify the functions, ports, protocols, and other services required for the use of such services.
- **SA-9 (4)**: The organization employs **all external systems where Federal information is processed or stored** to ensure that the interests of [Assignment: organization-defined external service providers] are consistent with and reflect organizational interests.
- **SA-9 (5)**: The organization restricts the location of [Selection (one or more): information processing; information/data; information system services] to **information processing, information data, AND information services** based on [Assignment: organization-defined requirements or conditions].
- **SA-10**: The organization requires the developer of the information system, system component, or information system service to:
 a. Perform configuration management during system, component, or service [Selection (one or more): design; development; implementation; operation];
 b. Document, manage, and control the integrity of changes to [Assignment: organization-defined configuration items under configuration management];
 c. Implement only organization-approved changes to the system, component, or service;
 d. Document approved changes to the system, component, or service and the potential security impacts of such changes; and
 e. Track security flaws and flaw resolution within the system, component, or service and report findings to [Assignment: organization-defined personnel].
- **SA-10 (1)**: The organization requires the developer of the information system, system component, or information system service to enable integrity verification of software and firmware components.
- **SA-11**: The organization requires the developer of the information system, system component, or information system service to:
 a. Create and implement a security assessment plan;
 b. Perform [Selection (one or more): unit; integration; system; regression] testing/evaluation at [Assignment: organization-defined depth and coverage];
 c. Produce evidence of the execution of the security assessment plan and the results of the security testing/evaluation;
 d. Implement a verifiable flaw remediation process; and
 e. Correct flaws identified during security testing/evaluation.
- **SA-11 (1)**: The organization requires the developer of the information system, system component, or information system service to employ static code analysis tools to identify common flaws and document the results of the analysis.
- **SA-11 (2)**: The organization requires the developer of the information system, system component, or information system service to perform threat and vulnerability analyses and subsequent testing/evaluation of the as-built system, component, or service.
- **SA-11 (8)**: The organization requires the developer of the information system, system component, or information system service to employ dynamic code analysis tools to identify common flaws and document the results of the analysis.
- **SA-12**: The organization protects against supply chain threats to the information system, system component, or information system service by employing **organization and service provider-defined personnel security requirements, approved HW/SW vendor list/process, and secure SDLC procedures** as part of a comprehensive, defense-in-breadth information security strategy.
- **SA-15**: The organization:
 a. Requires the developer of the information system, system component, or information system service to follow a documented development process that:
   1. Explicitly addresses security requirements;
   2. Identifies the standards and tools used in the development process;
   3. Documents the specific tool options and tool configurations used in the development process; and
   4. Documents, manages, and ensures the integrity of changes to the process and/or tools used in development; and
 b. Reviews the development process, standards, tools, and tool options/configurations **as needed and as dictated by the current threat posture** to determine if the process, standards, tools, and tool options/configurations selected and employed can satisfy **organization and service provider- defined security requirements**.
- **SA-16**: The organization requires the developer of the information system, system component, or information system service to provide [Assignment: organization-defined training] on the correct use and operation of the implemented security functions, controls, and/or mechanisms.
- **SA-17**: The organization requires the developer of the information system, system component, or information system service to produce a design specification and security architecture that:
 a. Is consistent with and supportive of the organization’s security architecture which is established within and is an integrated part of the organization’s enterprise architecture;
 b. Accurately and completely describes the required security functionality, and the allocation of security controls among physical and logical components; and
 c. Expresses how individual security functions, mechanisms, and services work together to provide required security capabilities and a unified approach to protection.

### SYSTEM AND COMMUNICATIONS PROTECTION

- **SC-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A system and communications protection policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the system and communications protection policy and associated system and communications protection controls; and
 b. Reviews and updates the current:
   1. System and communications protection policy **at least annually**; and
   2. System and communications protection procedures **at least annually or whenever a significant change occurs**.
- **SC-2**: The information system separates user functionality (including user interface services) from information system management functionality.
- **SC-3**: The information system isolates security functions from nonsecurity functions.
- **SC-4**: The information system prevents unauthorized and unintended information transfer via shared system resources.
- **SC-5**: The information system protects against or limits the effects of the following types of denial of service attacks: [Assignment: organization-defined types of denial of service attacks or reference to source for such information] by employing [Assignment: organization-defined security safeguards].
- **SC-6**: The information system protects the availability of resources by allocating [Assignment: organization-defined resources] by [Selection (one or more); priority; quota; [Assignment: organization-defined security safeguards]].
- **SC-7**: The information system:
 a. Monitors and controls communications at the external boundary of the system and at key internal boundaries within the system;
 b. Implements subnetworks for publicly accessible system components that are [Selection: physically; logically] separated from internal organizational networks; and
 c. Connects to external networks or information systems only through managed interfaces consisting of boundary protection devices arranged in accordance with an organizational security architecture.
- **SC-7 (3)**: The organization limits the number of external network connections to the information system.
- **SC-7 (4)**: The organization:
 (a)   Implements a managed interface for each external telecommunication service; 
 (b)   Establishes a traffic flow policy for each managed interface;
 (c)   Protects the confidentiality and integrity of the information being transmitted across each interface;
 (d)   Documents each exception to the traffic flow policy with a supporting mission/business need and duration of that need; and
 (e)   Reviews exceptions to the traffic flow policy [Assignment: organization-defined frequency] and removes exceptions that are no longer supported by an explicit mission/business need.
- **SC-7 (5)**: The information system at managed interfaces denies network communications traffic by default and allows network communications traffic by exception (i.e., deny all, permit by exception).
- **SC-7 (7)**: The information system, in conjunction with a remote device, prevents the device from simultaneously establishing non-remote connections with the system and communicating via some other connection to resources in external networks.
- **SC-7 (8)**: The information system routes [Assignment: organization-defined internal communications traffic] to [Assignment: organization-defined external networks] through authenticated proxy servers at managed interfaces.
- **SC-7 (10)**: The organization prevents the unauthorized exfiltration of information across managed interfaces.
- **SC-7 (12)**: The organization implements **Host Intrusion Prevention System (HIPS), Host Intrusion Detection System (HIDS), or minimally a host-based firewall** at [Assignment: organization-defined information system components].
- **SC-7 (13)**: The organization isolates [Assignment: organization-defined information security tools, mechanisms, and support components] from other internal information system components by implementing physically separate subnetworks with managed interfaces to other components of the system.
- **SC-7 (18)**: The information system fails securely in the event of an operational failure of a boundary protection device.
- **SC-7 (20)**: The information system provides the capability to dynamically isolate/segregate [Assignment: organization-defined information system components] from other components of the system.
- **SC-7 (21)**: The organization employs boundary protection mechanisms to separate [Assignment: organization-defined information system components] supporting [Assignment: organization- defined missions and/or business functions].
- **SC-8**: The information system protects the [Selection (one or more): confidentiality; integrity] of transmitted information.
- **SC-8 (1)**: The information system implements cryptographic mechanisms to [Selection (one or more): prevent unauthorized disclosure of information; detect changes to information] during transmission unless otherwise protected by **prevent unauthorized disclosure of information AND detect changes to information**.
- **SC-10**: The information system terminates the network connection associated with a communications session at the end of the session or after **no longer than ten (10) minutes for privileged sessions and no longer than fifteen (15) minutes for user sessions** of inactivity.
- **SC-12**: The organization establishes and manages cryptographic keys for required cryptography employed within the information system in accordance with [Assignment: organization-defined requirements for key generation, distribution, storage, access, and destruction].
- **SC-12 (1)**: The organization maintains availability of information in the event of the loss of cryptographic keys by users.
- **SC-12 (2)**: The organization produces, controls, and distributes symmetric cryptographic keys using [Selection: NIST FIPS-compliant; NSA-approved] key management technology and processes.
- **SC-12 (3)**: The organization produces, controls, and distributes asymmetric cryptographic keys using [Selection: NSA-approved key management technology and processes; approved PKI Class 3 certificates or prepositioned keying material; approved PKI Class 3 or Class 4 certificates and hardware security tokens that protect the user’s private key].
- **SC-13**: The information system implements **FIPS-validated or NSA-approved cryptography** in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, and standards.
- **SC-15**: The information system:
 a. Prohibits remote activation of collaborative computing devices with the following exceptions: **no exceptions**; and
 b. Provides an explicit indication of use to users physically present at the devices.
- **SC-17**: The organization issues public key certificates under an [Assignment: organization- defined certificate policy] or obtains public key certificates from an approved service provider.
- **SC-18**: The organization:
 a. Defines acceptable and unacceptable mobile code and mobile code technologies;
 b. Establishes usage restrictions and implementation guidance for acceptable mobile code and mobile code technologies; and
 c. Authorizes, monitors, and controls the use of mobile code within the information system.
- **SC-19**: The organization:
 a. Establishes usage restrictions and implementation guidance for Voice over Internet Protocol (VoIP) technologies based on the potential to cause damage to the information system if used maliciously; and
 b. Authorizes, monitors, and controls the use of VoIP within the information system.
- **SC-20**: The information system:
 a. Provides additional data origin and integrity artifacts along with the authoritative name resolution data the system returns in response to external name/address resolution queries; and
 b. Provides the means to indicate the security status of child zones and (if the child supports secure resolution services) to enable verification of a chain of trust among parent and child domains, when operating as part of a distributed, hierarchical namespace.
- **SC-21**: The information system requests and performs data origin authentication and data integrity verification on the name/address resolution responses the system receives from authoritative sources.
- **SC-22**: The information systems that collectively provide name/address resolution service for an organization are fault-tolerant and implement internal/external role separation.
- **SC-23**: The information system protects the authenticity of communications sessions.
- **SC-23 (1)**: The information system invalidates session identifiers upon user logout or other session termination.
- **SC-24**: The information system fails to a [Assignment: organization-defined known-state] for [Assignment: organization-defined types of failures] preserving [Assignment: organization-defined system state information] in failure.
- **SC-28**: The information system protects the [Selection (one or more): confidentiality; integrity] of **confidentiality AND integrity**.
- **SC-28 (1)**: The information system implements cryptographic mechanisms to prevent unauthorized disclosure and modification of **all information system components storing customer data deemed sensitive** on [Assignment: organization-defined information system components].
- **SC-39**: The information system maintains a separate execution domain for each executing process.

### SYSTEM AND INFORMATION INTEGRITY

- **SI-1**: The organization:
 a. Develops, documents, and disseminates to [Assignment: organization-defined personnel or roles]:
   1. A system and information integrity policy that addresses purpose, scope, roles, responsibilities, management commitment, coordination among organizational entities, and compliance; and
   2. Procedures to facilitate the implementation of the system and information integrity policy and associated system and information integrity controls; and
 b. Reviews and updates the current:
   1. System and information integrity policy **at least annually**; and
   2.  System and information integrity procedures **at least annually or whenever a significant change occurs**.
- **SI-2**: The organization:
a. Identifies, reports, and corrects information system flaws;
b. Tests software and firmware updates related to flaw remediation for effectiveness and potential side effects before installation;
c. Installs security-relevant software and firmware updates within **thirty (30) days of release of updates** of the release of the updates; and
d. Incorporates flaw remediation into the organizational configuration management process.
- **SI-2 (1)**: The organization centrally manages the flaw remediation process.
- **SI-2 (2)**: The organization employs automated mechanisms **at least monthly** to determine the state of information system components with regard to flaw remediation.
- **SI-2 (3)**: The organization:
 (a)   Measures the time between flaw identification and flaw remediation; and
 (b)   Establishes [Assignment: organization-defined benchmarks] for taking corrective actions.
- **SI-3**: The organization:
 a. Employs malicious code protection mechanisms at information system entry and exit points to detect and eradicate malicious code;
 b. Updates malicious code protection mechanisms whenever new releases are available in accordance with organizational configuration management policy and procedures;
 c. Configures malicious code protection mechanisms to:
   1. Perform periodic scans of the information system **at least weekly** and real-time scans of files from external sources at [Selection (one or more); endpoint; network entry/exit points] as the files are downloaded, opened, or executed in accordance with organizational security policy; and
   2. [Selection (one or more): block malicious code; quarantine malicious code; send alert to administrator; [Assignment: organization-defined action, **to include blocking and quarantining malicious code and alerting administrator or defined security personnel near-realtime**]] in response to malicious code detection; and
 d. Addresses the receipt of false positives during malicious code detection and eradication and the resulting potential impact on the availability of the information system.
- **SI-3 (1)**: The organization centrally manages malicious code protection mechanisms.
- **SI-3 (2)**: The information system automatically updates malicious code protection mechanisms.
- **SI-3 (7)**: The information system implements nonsignature-based malicious code detection mechanisms.
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
- **SI-4 (1)**: The organization connects and configures individual intrusion detection tools into an information system-wide intrusion detection system.
- **SI-4 (2)**: The organization employs automated tools to support near real-time analysis of events.
- **SI-4 (4)**: The information system monitors inbound and outbound communications traffic **continuously** for unusual or unauthorized activities or conditions.
- **SI-4 (5)**: The information system alerts [Assignment: organization-defined personnel or roles] when the following indications of compromise or potential compromise occur: [Assignment: organization- defined compromise indicators].
- **SI-4 (11)**: The organization analyzes outbound communications traffic at the external boundary of the information system and selected [Assignment: organization-defined interior points within the system (e.g., subnetworks, subsystems)] to discover anomalies.
- **SI-4 (14)**: The organization employs a wireless intrusion detection system to identify rogue wireless devices and to detect attack attempts and potential compromises/breaches to the information system.
- **SI-4 (16)**: The organization correlates information from monitoring tools employed throughout the information system.
- **SI-4 (18)**: The organization analyzes outbound communications traffic at the external boundary of the information system (i.e., system perimeter) and at [Assignment: organization-defined interior points within the system (e.g., subsystems, subnetworks)] to detect covert exfiltration of information.
- **SI-4 (19)**: The organization implements [Assignment: organization-defined additional monitoring] of individuals who have been identified by [Assignment: organization-defined sources] as posing an increased level of risk.
- **SI-4 (20)**: The organization implements [Assignment: organization-defined additional monitoring] of privileged users.
- **SI-4 (22)**: The information system detects network services that have not been authorized or approved by [Assignment: organization-defined authorization or approval processes] and [Selection (one or more): audits; alerts [Assignment: organization-defined personnel or roles]].
- **SI-4 (23)**: The organization implements [Assignment: organization-defined host-based monitoring mechanisms] at [Assignment: organization-defined information system components].
- **SI-4 (24)**: The information system discovers, collects, distributes, and uses indicators of compromise.
- **SI-5**: The organization:
 a. Receives information system security alerts, advisories, and directives from [Assignment: organization-defined external organizations, **to include US-CERT**] on an ongoing basis;
 b. Generates internal security alerts, advisories, and directives as deemed necessary;
 c. Disseminates security alerts, advisories, and directives to: [Selection (one or more): [Assignment: organization-defined personnel or roles, **to include system security personnel and administrators with configuration/patch-management responsibilities**]; [Assignment: organization-defined elements within the organization]; [Assignment: organization-defined external organizations]]; and
 d. Implements security directives in accordance with established time frames, or notifies the issuing organization of the degree of noncompliance.
- **SI-5 (1)**: The organization employs automated mechanisms to make security alert and advisory information available throughout the organization.
- **SI-6**: The information system:
 a. Verifies the correct operation of [Assignment: organization-defined security functions];
 b. Performs this verification [Selection (one or more): [Assignment: organization-defined system transitional states, **to include upon system startup and/or restart and at least monthly**]; upon command by user with appropriate privilege; [Assignment: organization-defined frequency]];
 c. Notifies [Assignment: organization-defined personnel or roles, **to include system administrators and security personnel**] of failed security verification tests; and
 d. [Selection (one or more): shuts the information system down; restarts the information system; [Assignment: organization-defined alternative action(s), **to include notification of system administrators and security personnel**]] when anomalies are discovered.
- **SI-7**: The organization employs integrity verification tools to detect unauthorized changes to [Assignment: organization-defined software, firmware, and information].
- **SI-7 (1)**: The information system performs an integrity check of [Assignment: organization-defined software, firmware, and information] [Selection (one or more): at startup; at [Assignment: organization-defined transitional states or security-relevant events, **selection to include security relevant events**]; **at least monthly**].
- **SI-7 (2)**: The organization employs automated tools that provide notification to [Assignment: organization- defined personnel or roles] upon discovering discrepancies during integrity verification.
- **SI-7 (5)**: The information system automatically [Selection (one or more): shuts the information system down; restarts the information system; implements [Assignment: organization-defined security safeguards]] when integrity violations are discovered.
- **SI-7 (7)**: The organization incorporates the detection of unauthorized [Assignment: organization-defined security-relevant changes to the information system] into the organizational incident response capability.
- **SI-7 (14)**: The organization:
 (a)   Prohibits the use of binary or machine-executable code from sources with limited or no warranty and without the provision of source code; and
 (b)   Provides exceptions to the source code requirement only for compelling mission/operational requirements and with the approval of the authorizing official.
- **SI-8**: The organization:
 a. Employs spam protection mechanisms at information system entry and exit points to detect and take action on unsolicited messages; and
 b. Updates spam protection mechanisms when new releases are available in accordance with organizational configuration management policy and procedures.
- **SI-8 (1)**: The organization centrally manages spam protection mechanisms.
- **SI-8 (2)**: The information system automatically updates spam protection mechanisms.
- **SI-10**: The information system checks the validity of [Assignment: organization-defined information inputs].
- **SI-11**: The information system:
 a. Generates error messages that provide information necessary for corrective actions without revealing information that could be exploited by adversaries; and
 b. Reveals error messages only to [Assignment: organization-defined personnel or roles].
- **SI-12**: The organization handles and retains information within the information system and information output from the system in accordance with applicable federal laws, Executive Orders, directives, policies, regulations, standards, and operational requirements.
- **SI-16**: The information system implements [Assignment: organization-defined security safeguards] to protect its memory from unauthorized code execution.

