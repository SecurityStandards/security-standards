# THSA (v2019.1)

Referência oficial: https://www.together.health/security-assessment

## Controles e Domínios (31)

### Security & Privacy Governance

- **GOV-01**: Does the organization staff a function to centrally-govern cybersecurity and privacy controls?
- **GOV-02**: Does the organization establish, maintain and disseminate cybersecurity and privacy policies, standards and procedures?
- **GOV-03**: Does the organization review cybersecurity and privacy policies, standards and procedures at planned intervals or if significant changes occur to ensure their continuing suitability, adequacy and effectiveness?
- **GOV-04**: Does the organization assign a qualified individual with the mission and resources to centrally-manage coordinate, develop, implement and maintain an enterprise-wide cybersecurity and privacy program?
- **GOV-05**: Does the organization develop, report and monitor cybersecurity and privacy program measures of performance?
- **GOV-06**: Does the organization identify and document appropriate contacts within relevant law enforcement and regulatory bodies?
- **GOV-07**: Does the organization establish contact with selected groups and associations within the cybersecurity & privacy communities to: 
 ▪ Facilitate ongoing cybersecurity and privacy education and training for organizational personnel;
 ▪ Maintain currency with recommended cybersecurity and privacy practices, techniques and technologies; and
 ▪ Share current security-related information including threats, vulnerabilities and incidents?

### Asset Management

- **AST-01**: Does the organization facilitate the implementation of asset management controls?
- **AST-02**: Does the organization inventory system components that:
 ▪ Accurately reflects the current system; 
 ▪ Is at the level of granularity deemed necessary for tracking and reporting;
 ▪ Includes organization-defined information deemed necessary to achieve effective property accountability; and
 ▪ Is available for review and audit by designated organizational officials?

- **AST-02.1**: Does the organization update asset inventories as part of component installations, removals and asset upgrades?
- **AST-04**: Does the organization maintain network architecture diagrams that: 
 ▪ Contain sufficient detail to assess the security of the network's architecture;
 ▪ Reflect the current state of the network environment; and
 ▪ Document all sensitive data flows?
- **AST-09**: Does the organization securely destroy media when it is no longer needed for business or legal reasons?
- **AST-11**: Does the organization authorize, control and track systems entering and exiting organizational facilities?

### Business Continuity & Disaster Recovery

- **BCD-01**: Does the organization facilitate the implementation of contingency planning controls?
- **BCD-02**: Does the organization identify and document the critical systems, applications and services that support essential missions and business functions?
- **BCD-03.1**: Does the organization incorporate simulated events into contingency training to facilitate effective response by personnel in crisis situations?
- **BCD-04**: Does the organization conduct tests and/or exercises to determine the contingency plan's effectiveness and the organization’s readiness to execute the plan?
- **BCD-05**: Does the organization conduct a Root Cause Analysis (RCA) and "lessons learned" activity every time the contingency plan is activated?
- **BCD-06**: Does the organization keep contingency plans current with business needs and technology changes?
- **BCD-08**: Does the organization establish an alternate storage site that includes both the assets and necessary agreements to permit the storage and recovery of system backup information?
- **BCD-09**: Does the organization establish an alternate processing site that provides security measures equivalent to that of the primary site?
- **BCD-09.2**: Does the organization identify potential accessibility problems to the alternate processing site and possible mitigation actions, in the event of an area-wide disruption or disaster?
- **BCD-11**: Does the organization create recurring backups of data, software and system images to ensure the availability of the data?
- **BCD-12**: Does the organization ensure the recovery and reconstitution of systems to a known state after a disruption, compromise or failure?

### Capacity & Performance Planning

- **CAP-01**: Does the organization facilitate the implementation of capacity management controls to ensure optimal system performance for future capacity requirements?

### Change Management

- **CHG-02**: Does the organization govern the technical configuration change control processes?

### Compliance

- **CPL-01**: Does the organization facilitate the implementation of relevant legislative statutory, regulatory and contractual controls?
- **CPL-02**: Does the organization provide a security controls oversight function?
- **CPL-03**: Does the organization ensure managers regularly review the processes and documented procedures within their area of responsibility to adhere to appropriate security policies, standards and other applicable requirements?

### Configuration Management

- **CFG-01**: Does the organization facilitate the implementation of configuration management controls?
- **CFG-02**: Does the organization develop, document and maintain secure baseline configurations for technology platform that are consistent with industry-accepted system hardening standards?
- **CFG-02.9**: Does the organization allow baseline controls to be specialized or customized by applying a defined set of tailoring actions that are specific to:
 ▪ Mission / business functions;
 ▪ Operational environment;
 ▪ Specific threats or vulnerabilities; or
 ▪ Other conditions or situations that could affect mission / business success?
- **CFG-03**: Does the organization configure systems to provide only essential capabilities by specifically prohibiting or restricting the use of ports, protocols, and/or services?
- **CFG-03.3**: Does the organization whitelist or blacklist applications in an order to limit what is authorized to execute on systems?
- **CFG-04.2**: Does the organization allow only approved Internet browsers and email clients to run on systems?
- **CFG-05**: Does the organization restrict the ability of non-privileged users to install unauthorized software?

### Monitoring

- **MON-01**: Does the organization facilitate the implementation of enterprise-wide monitoring controls?
- **MON-01.1**: Does the organization implement Intrusion Detection / Prevention Systems (IDS / IPS) technologies on critical systems, key network segments and network choke points?
- **MON-01.4**: Does the organization monitor, correlate and respond to alerts from physical, cybersecurity, privacy and supply chain activities to achieve integrated situational awareness?
- **MON-01.5**: Does the organization utilize Wireless Intrusion Detection / Protection Systems (WIDS / WIPS) to identify rogue wireless devices and to detect attack attempts via wireless networks?
- **MON-01.7**: Does the organization utilize a File Integrity Monitor (FIM) or similar change-detection technology on critical assets to generate alerts for unauthorized modifications?
- **MON-01.8**: Does the organization review event logs on an ongoing basis and escalate incidents in accordance with established timelines and procedures?
- **MON-01.9**: Does the organization log all Internet-bound requests, in order to identify prohibited activities and assist incident handlers with identifying potentially compromised systems?
- **MON-06**: Does the organization provide an event log report generation capability to aid in detecting and assessing anomalous activities?
- **MON-16**: Does the organization detect and respond to anomalous behavior that could indicate account compromise or other malicious activities?
- **MON-16.1**: Does the organization monitor internal personnel activity for potential security incidents?
- **MON-16.2**: Does the organization monitor third-party personnel activity for potential security incidents?
- **MON-16.3**: Does the organization monitor for unauthorized activities, accounts, connections, devices, and software?

### Cryptographic Protections

- **CRY-01**: Does the organization facilitate the implementation of cryptographic protections controls using known public standards and trusted cryptographic technologies?
- **CRY-01.1**: Are cryptographic mechanisms used to prevent unauthorized disclosure of information as an alternate to physical safeguards?
- **CRY-03**: Are cryptographic mechanisms utilized to protect the confidentiality of data being transmitted?
- **CRY-04**: Are cryptographic mechanisms utilized to protect the integrity of data being transmitted?
- **CRY-05**: Are cryptographic mechanisms utilized on systems to prevent unauthorized disclosure of information at rest?
- **CRY-05.1**: Are cryptographic mechanisms utilized on storage media to protect the confidentiality and integrity of the information being stored?

### Data Classification & Handling

- **DCH-01**: Does the organization facilitate the implementation of data protection controls?
- **DCH-01.1**: Does the organization ensure data stewardship is assigned, documented and communicated?
- **DCH-02**: Does the organization ensure data and assets are categorized in accordance with applicable statutory, regulatory and contractual requirements?
- **DCH-03.2**: Does the organization apply data masking to sensitive information that is displayed or printed?
- **DCH-04**: Does the organization mark media in accordance with data protection requirements so that personnel are alerted to distribution limitations, handling caveats and applicable security requirements?
- **DCH-04.1**: Are automated mechanisms used to mark media and system output to indicate the distribution limitations, handling requirements and applicable security markings (if any) of the information to aide Data Loss Prevention (DLP) technologies?
- **DCH-05**: Does the organization bind security attributes to information as it is stored, transmitted and processed?
- **DCH-05.1**: Does the organization dynamically associate security and privacy attributes with individuals and objects as information is created, combined, or transformed, in accordance with organization-defined cybersecurity and privacy policies?
- **DCH-05.2**: Does the organization provide authorized individuals (or processes acting on behalf of individuals) the capability to define or change the value of associated security and privacy attributes?
- **DCH-05.3**: Does the organization maintain the association and integrity of security and privacy attributes to individuals and objects?
- **DCH-05.4**: Does the organization provide the capability to associate security and privacy attributes with individuals and objects by authorized individuals (or processes acting on behalf of individuals)?
- **DCH-05.5**: Does the organization display security and privacy attributes in human-readable form on each object that the system transmits to output devices to identify special dissemination, handling or distribution instructions using human-readable, standard naming conventions?
- **DCH-05.6**: Does the organization require personnel to associate and maintain the association of security and privacy attributes with individuals and objects in accordance with security and privacy policies?
- **DCH-05.7**: Does the organization provide a consistent interpretation of security and privacy attributes transmitted between distributed system components?
- **DCH-05.8**: Does the organization associate security and privacy attributes to information?
- **DCH-05.9**: Does the organization re-classify data as required, due to changing business/technical requirements?
- **DCH-05.10**: Does the organization provide authorized individuals the capability to define or change the type and value of security and privacy attributes available for association with subjects and objects?
- **DCH-05.11**: Does the organization audit changes to security and privacy attributes and respond to them in a timely manner?
- **DCH-08**: Does the organization securely dispose of media when it is no longer required, using formal procedures?
- **DCH-09**: Does the organization sanitize media, both digital and non-digital, with the strength and integrity commensurate with the classification or sensitivity of the information prior to disposal, release out of organizational control or release for reuse?
- **DCH-12**: Does the organization restrict removable media in accordance with data handling and acceptable usage parameters?
- **DCH-18**: Does the organization retain media and data in accordance with applicable statutory, regulatory and contractual obligations?

### Embedded Technology

- **EMB-01**: Does the organization facilitate the implementation of embedded technology controls?
- **EMB-02**: Does the organization proactively manage the cybersecurity and privacy risks associated with Internet of Things (IoT)?
- **EMB-03**: Does the organization proactively manage the cybersecurity and privacy risks associated with Operational Technology (OT)?

### Endpoint Security

- **END-01**: Does the organization facilitate the implementation of endpoint security controls?
- **END-02**: Does the organization protect the confidentiality, integrity, availability and safety of endpoint devices?
- **END-03**: Does the organization prohibit user installation of software without explicitly assigned privileged status?
- **END-04**: Does the organization utilize antimalware technologies to detect and eradicate malicious code?
- **END-04.1**: Does the organization automatically update antimalware technologies, including signature definitions?
- **END-06**: Does the organization utilize File Integrity Monitor (FIM) technology to detect and report unauthorized changes to system files and configurations?
- **END-08**: Does the organization utilize anti-phishing and spam protection technologies to detect and take action on unsolicited messages transported by electronic mail?
- **END-08.1**: Does the organization centrally-manage anti-phishing and spam protection technologies?
- **END-08.2**: Does the organization automatically update anti-phishing and spam protection technologies when new releases are available in accordance with configuration and change management practices?
- **END-10**: Does the organization address mobile code / operating system-independent applications?

### Human Resources Security

- **HRS-01**: Does the organization facilitate the implementation of personnel security controls?
- **HRS-03**: Does the organization define cybersecurity responsibilities for all personnel?
- **HRS-05.1**: Does the organization define acceptable and unacceptable rules of behavior for the use of technologies, including consequences for unacceptable behavior?
- **HRS-07**: Does the organization sanction personnel failing to comply with established security policies, standards and procedures?

### Identification & Authentication

- **IAC-01**: Does the organization facilitate the implementation of identification and access management controls?
- **IAC-02**: Does the organization uniquely identify and authenticate organizational users and processes acting on behalf of organizational users?
- **IAC-04**: Does the organization uniquely identify and authenticate devices before establishing a connection?
- **IAC-06**: Does the organization require Multi-Factor Authentication (MFA) for remote network access?
- **IAC-06.2**: Does the organization utilize Multi-Factor Authentication (MFA) to authenticate network access for non-privileged accounts?
- **IAC-07**: Does the organization utilize a formal user registration and de-registration process that governs the assignment of access rights?
- **IAC-07.1**: Does the organization revoke user access rights following changes in personnel roles and duties, if no longer necessary or permitted?
- **IAC-07.2**: Does the organization revoke user access rights in a timely manner, upon termination of employment or contract?
- **IAC-08**: Does the organization enforce a Role-Based Access Control (RBAC) policy over users and resources?
- **IAC-09**: Does the organization govern naming standards for usernames and systems?
- **IAC-10**: Does the organization securely manage passwords for users and devices?
- **IAC-10.1**: For password-based authentication, does the organization enforce password complexity to ensure strong passwords?
- **IAC-10.8**: Does the organization ensure vendor-supplied defaults are changed as part of the installation process?
- **IAC-15**: Does the organization proactively govern account management of individual, group, system, application, guest and temporary accounts?
- **IAC-15.2**: Are automated mechanisms used to disable or remove temporary and emergency accounts after an organization-defined time period for each type of account?
- **IAC-16**: Does the organization restrict and control privileged access rights for users and services?
- **IAC-21**: Does the organization utilize the concept of least privilege, allowing only authorized access to processes necessary to accomplish assigned tasks in accordance with organizational business functions?
- **IAC-22**: Does the organization enforce a limit for consecutive invalid login attempts by a user during an organization-defined time period and automatically locks the account when the maximum number of unsuccessful attempts is exceeded?
- **IAC-24**: Does the organization initiate a session lock after an organization-defined time period of inactivity, or upon receiving a request from a user, and retain the session lock until the user reestablishes access using established identification and authentication methods?
- **IAC-25**: Are automated mechanisms used to log out users, both locally on the network and for remote sessions, at the end of the session or after an organization-defined period of inactivity?
- **IAC-28**: Does the organization collect, validate and verify identity evidence of a user?
- **IAC-28.1**: Does the organization require the registration process to receive supervisor or sponsor authorization for new accounts?
- **IAC-28.2**: Does the organization require evidence of individual identification to be presented to the registration authority?
- **IAC-28.3**: Does the organization require that the presented identity evidence be validated and verified through organizational-defined methods of validation and verification?

### Incident Response

- **IRO-01**: Does the organization facilitate the implementation of incident response controls?
- **IRO-02**: Doe incident handling processes cover preparation, detection and analysis, containment, eradication and recovery?
- **IRO-03**: Does the organization define specific Indicators of Compromise (IOC) that identify the potential impact of likely cybersecurity events?
- **IRO-04**: Does the organization maintain and make available a current and viable Incident Response Plan (IRP) to all stakeholders?
- **IRO-04.2**: Does the organization regularly update incident response strategies to keep current with business needs, technology changes and regulatory requirements?
- **IRO-06.1**: Does the organization coordinate incident response testing with organizational elements responsible for related plans?
- **IRO-07**: Does the organization establish an integrated team of cybersecurity, IT and business function representatives that are capable of addressing cybersecurity and privacy incident response operations?
- **IRO-08**: Does the organization perform digital forensics and maintain the integrity of the chain of custody?
- **IRO-09**: Does the organization document, monitor and report cybersecurity and privacy incidents?
- **IRO-10**: Does the organization report incidents:
 ▪ Internally to organizational incident response personnel within organization-defined time-periods; and
 ▪ Externally to regulatory authorities and affected parties, as necessary?
- **IRO-10.2**: Does the organization report sensitive data incidents in a timely manner?
- **IRO-10.4**: Does the organization provide security and privacy incident information to the provider of the product or service and other organizations involved in the supply chain for systems or system components related to the incident?
- **IRO-11.2**: Does the organization establish a direct, cooperative relationship between the organization's incident response capability and external service providers?
- **IRO-13**: Does the organization incorporate lessons learned from analyzing and resolving cybersecurity and privacy incidents to reduce the likelihood or impact of future incidents?
- **IRO-14**: Does the organization maintain incident response contacts with applicable regulatory and law enforcement agencies?

### Information Assurance

- **IAO-03.2**: Does the organization protect sensitive data that is collected, developed, received, transmitted, used or stored in support of the performance of a contract?

### Maintenance

- **MNT-01**: Does the organization develop, disseminate, review & update procedures to facilitate the implementation of maintenance controls across the enterprise?
- **MNT-02**: Does the organization conduct controlled maintenance activities throughout the lifecycle of the system, application or service?
- **MNT-05**: Does the organization authorize, monitor and control non-local maintenance and diagnostic activities?

### Mobile Device Management

- **MDM-05**: Does the organization remotely purge selected information from mobile devices?

### Network Security

- **NET-01**: Does the organization develop, govern & update procedures to facilitate the implementation of network security controls?
- **NET-02**: Does the organization implement security functions as a layered structure that minimizes interactions between layers of the design and avoiding any dependence by lower layers on the functionality or correctness of higher layers?
- **NET-02.1**: Do mechanism exist to protect against or limit the effects of Denial of Service (DoS) attacks?
- **NET-02.2**: Does the organization implement and manage a secure guest network?
- **NET-03**: Are boundary protection mechanisms utilized to monitor and control communications at the external network boundary and at key internal boundaries within the network?
- **NET-03.1**: Does the organization limit the number of external network connections that a system will simultaneously accept?
- **NET-04**: Does the organization design, implement and review firewall and router configurations to restrict connections between untrusted networks and internal systems?
- **NET-06**: Does the organization logically or physically segment information flows to accomplish network segmentation?
- **NET-08.1**: Does the organization require De-Militarized Zone (DMZ) network segments to separate untrusted networks from trusted networks?
- **NET-14**: Does the organization define, control and review remote access methods?
- **NET-17**: Is Data Loss Prevention (DLP) used to protect sensitive information as it is stored, transmitted and processed?
- **NET-18**: Does the organization force Internet-bound network traffic through a proxy device for URL content filtering to limit a user's ability to connect to prohibited content?
- **NET-18.1**: Does the organization route internal communications traffic to external networks through organization-approved proxy servers at managed interfaces?

### Physical & Environmental Security

- **PES-01**: Does the organization facilitate the operation of physical and environmental protection controls?
- **PES-02**: Does the organization maintain a current list of personnel with authorized access to organizational facilities (except for those areas within the facility officially designated as publicly accessible)?
- **PES-02.1**: Does the organization authorize physical access to facilities based on the position or role of the individual?
- **PES-03**: Does the organization enforce physical access authorizations for all physical access points (including designated entry/exit points) to facilities (excluding those areas within the facility officially designated as publicly accessible)?
- **PES-03.2**: Does the organization protect system components from unauthorized physical access (e.g.?, lockable physical casings)?
- **PES-04**: Are physical access controls designed and implemented for offices, rooms and facilities?
- **PES-04.1**: Do physical access controls ensure that only authorized personnel are allowed access to secure areas?
- **PES-05**: Does the organization monitor for, detect and respond to physical security incidents?
- **PES-12**: Does the organization locate system components within the facility to minimize potential damage from physical and environmental hazards and to minimize the opportunity for unauthorized access?
- **PES-12.1**: Does the organization protect power and telecommunications cabling carrying data or supporting information services from interception, interference or damage?
- **PES-12.2**: Does the organization restrict access to printers and other system output devices to prevent unauthorized individuals from obtaining the output?
- **PES-13**: Does the organization protect the system from information leakage due to electromagnetic signals emanations?

### Privacy

- **PRI-01**: Does the organization facilitate the implementation and operation of privacy controls?
- **PRI-01.1**: Does the organization appoints a Chief Privacy Officer (CPO) or similar role, with the authority, mission, accountability and resources to coordinate, develop and implement, applicable privacy requirements and manage privacy risks through the organization-wide privacy program?
- **PRI-02**: Do mechanisms exist to:
 ▪ Make privacy notice(s) available to individuals upon first interacting with an organization and subsequently as necessary?
 ▪ Ensure that privacy notices are clear and easy-to-understand, expressing information about Personal Information (PI) processing in plain language?
- **PRI-05**: Do mechanisms exist to: 
 ▪ Retain Personal Information (PI), including metadata, for an organization-defined time period to fulfill the purpose(s) identified in the notice or as required by law;
 ▪ Disposes of, destroys, erases, and/or anonymizes the PI, regardless of the method of storage; and
 ▪ Uses organization-defined techniques or methods to ensure secure deletion or destruction of PI (including originals, copies and archived records)?
- **PRI-06**: Does the organization provide individuals the ability to access their Personal Information (PI) maintained in organizational systems of records?
- **PRI-06.1**: Does the organization establish and implement a process for:
 ▪ Individuals to have inaccurate Personal Information (PI) maintained by the organization corrected or amended; and
 ▪ Disseminating corrections or amendments of PI to other authorized users of the PI?
- **PRI-06.4**: Does the organization implement a process for receiving and responding to complaints, concerns or questions from individuals about the organizational privacy practices?
- **PRI-07.1**: Does the organization includes privacy requirements in contracts and other acquisition-related documents that establish privacy roles and responsibilities for contractors and service providers?
- **PRI-12**: Does the organization develop processes to identify and record the method under which Personal Information (PI) is updated and the frequency that such updates occur?
- **PRI-14.1**: Does the organization develop and maintain an accounting of disclosures of Personal Information (PI) held by the organization and make the accounting of disclosures available to the person named in the record, upon request?

### Project & Resource Management

- **PRM-03**: Does the organization identify and allocate resources for management, operational, technical and privacy requirements within business process planning for projects / initiatives?
- **PRM-04**: Does the organization assess security and privacy controls in system project development to determine the extent to which the controls are implemented correctly, operating as intended and producing the desired outcome with respect to meeting the requirements?
- **PRM-05**: Does the organization identify critical system components and functions by performing a criticality analysis for critical systems, system components or services at pre-defined decision points in the Secure Development Life Cycle (SDLC)?
- **PRM-07**: Does the organization ensure changes to systems within the Secure Development Life Cycle (SDLC) are controlled through formal change control procedures?

### Risk Management

- **RSK-01**: Does the organization facilitate the implementation of risk management controls?
- **RSK-03**: Does the organization identify and document risks, both internal and external?
- **RSK-04**: Does the organization conduct an annual assessment of risk that includes the likelihood and magnitude of harm, from unauthorized access, use, disclosure, disruption, modification or destruction of the organization's systems and data?
- **RSK-06**: Does the organization remediate risks to an acceptable level?
- **RSK-08**: Does the organization conduct a Business Impact Analysis (BIA)?
- **RSK-09**: Does the organization develop a plan for managing supply chain risks associated with the development, acquisition, maintenance and disposal of systems, system components and services?
- **RSK-09.1**: Does the organization assess supply chain risks associated with systems, system components and services?
- **RSK-10**: Does the organization conduct a Data Protection Impact Assessment (DPIA) on systems, applications and services to evaluate privacy implications?

### Secure Engineering & Architecture

- **SEA-01**: Does the organization facilitate the implementation of industry-recognized security and privacy practices in the specification, design, development, implementation and modification of systems and services?
- **SEA-01.1**: Does the organization centrally-manage the organization-wide management and implementation of cybersecurity and privacy controls and related processes?
- **SEA-02**: Does the organization develop an enterprise architecture, aligned with industry-recognized leading practices, with consideration for cybersecurity and privacy principles that addresses risk to organizational operations, assets, individuals, other organizations?
- **SEA-02.1**: Does the organization standardize technology and process terminology to reduce confusion amongst groups and departments?
- **SEA-07.2**: Does the organization enable systems to fail to an organization-defined known-state for types of failures, preserving system state information in failure?

### Security Operations

- **OPS-01**: Does the organization facilitate the implementation of operational security controls?
- **OPS-01.1**: Do Standardized Operating Procedures (SOP), or similar mechanisms, used to identify and document day-to-day procedures to enable the proper execution of assigned tasks?
- **OPS-02**: Does the organization develop a security Concept of Operations (CONOPS) that documents management, operational and technical measures implemented to apply defense-in-depth techniques?
- **OPS-03**: Does the organization define supporting business processes and implement appropriate governance and service management to ensure appropriate planning, delivery and support of the organization's technology capabilities supporting business functions, workforce, and/or customers based on industry-recognized standards?

### Security Awareness & Training

- **SAT-01**: Does the organization facilitate the implementation of security workforce development and awareness controls?
- **SAT-02**: Does the organization provide all employees and contractors appropriate awareness education and training that is relevant for their job function?
- **SAT-03**: Does the organization provide role-based security-related training: 
 ▪ Before authorizing access to the system or performing assigned duties; 
 ▪ When required by system changes; and 
 ▪ Annually thereafter?
- **SAT-03.1**: Does the organization include practical exercises in security and privacy training that reinforce training objectives?
- **SAT-03.5**: Does the organization provides specific training for privileged users to ensure privileged users understand their unique roles and responsibilities

### Technology Development & Acquisition

- **TDA-08**: Does the organization manage separate development, testing, and operational environments to reduce the risks of unauthorized access or changes to the operational environment and to ensure no impact to production systems?

### Third-Party Management

- **TPM-01**: Does the organization facilitate the implementation of third-party management controls?
- **TPM-02**: Does the organization identify, prioritize and assess suppliers and partners of critical systems, components and services using a supply chain risk assessment process?
- **TPM-03**: Does the organization evaluate security risks associated with the services and product supply chain?
- **TPM-05**: Does the organization identify, regularly review and document third-party confidentiality, Non-Disclosure Agreements (NDAs) and other contracts that reflect the organization’s needs to protect systems and data?
- **TPM-06**: Does the organization control personnel security requirements including security roles and responsibilities for third-party providers?
- **TPM-11**: Does the organization ensure response/recovery planning and testing are conducted with critical suppliers/providers?

### Threat Management

- **THR-01**: Does the organization implement a threat awareness program that includes a cross-organization information-sharing capability?
- **THR-03**: Does the organization maintain situational awareness of evolving threats?

### Vulnerability & Patch Management

- **VPM-01**: Does the organization facilitate the implementation and monitoring of vulnerability management controls?
- **VPM-02**: Does the organization ensure that vulnerabilities are properly identified, tracked and remediated?
- **VPM-03**: Does the organization identify and assign a risk ranking to newly discovered security vulnerabilities using reputable outside sources for security vulnerability information?
- **VPM-04**: Does the organization address new threats and vulnerabilities on an ongoing basis and ensure assets are protected against known attacks?
- **VPM-05**: Does the organization conduct software patching for all deployed operating systems, applications, and firmware?
- **VPM-06**: Does the organization detect vulnerabilities and configuration errors by recurring vulnerability scanning of systems and web applications?
- **VPM-10**: Does the organization utilize "red team" exercises to simulate attempts by adversaries to compromise systems and applications in accordance with organization-defined rules of engagement? 

### Web Security

- **WEB-01**: Does the organization facilitate the implementation of an enterprise-wide web management policy, as well as associated standards, controls and procedures?
- **WEB-02**: Does the organization utilize a Demilitarized Zone (DMZ) to restrict inbound traffic to authorized devices on certain services, protocols and ports?
- **WEB-03**: Does the organization deploy Web Application Firewalls (WAFs) to provide defense-in-depth protection for application-specific threats?

