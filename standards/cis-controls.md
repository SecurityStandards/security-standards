# CIS Controls (v7)

Referência oficial: https://www.cisecurity.org/controls/

## Controles e Domínios (20)

### § Basic
【C01】 Inventory and Control of Hardware Assets

- **1.1**: Utilize an active discovery tool to identify devices connected to the organization’s network and update the hardware asset inventory.
- **1.2**: Utilize a passive discovery tool to identify devices connected to the organization's network and automatically update the organization's hardware asset inventory.
- **1.3**: Use Dynamic Host Configuration Protocol (DHCP) logging on all DHCP servers or IP address management tools to update the organization's hardware asset inventory.
- **1.4**: Maintain an accurate and up-to-date inventory of all technology assets with the potential to store or process information. This inventory shall include all hardware assets, whether connected to the organization's network or not.
- **1.5**: Ensure that the hardware asset inventory records the network address, hardware address, machine name, data asset owner, and department for each asset and whether the hardware asset has been approved to connect to the network.
- **1.6**: Ensure that unauthorized assets are either removed from the network, quarantined or the inventory is updated in a timely manner.
- **1.7**: Utilize port level access control, following 802.1x standards, to control which devices can authenticate to the network. The authentication system shall be tied into the hardware asset inventory data to ensure only authorized devices can connect to the network.
- **1.8**: Use client certificates to authenticate hardware assets connecting to the organization's trusted network.

### § Basic
【C02】 Inventory and Control of Software Assets

- **2.1**: Maintain an up-to-date list of all authorized software that is required in the enterprise for any business purpose on any business system.
- **2.2**: Ensure that only software applications or operating systems currently supported by the software's vendor are added to the organization's authorized software inventory. Unsupported software should be tagged as unsupported in the inventory system.
- **2.3**: Utilize software inventory tools throughout the organization to automate the documentation of all software on business systems.
- **2.4**: The software inventory system should track the name, version, publisher, and install date for all software, including operating systems authorized by the organization.
- **2.5**: The software inventory system should be tied into the hardware asset inventory so all devices and associated software are tracked from a single location.
- **2.6**: Ensure that unauthorized software is either removed or the inventory is updated in a timely manner.
- **2.7**: Utilize application whitelisting technology on all assets to ensure that only authorized software executes and all unauthorized software is blocked from executing on assets.
- **2.8**: The organization's application whitelisting software must ensure that only authorized software libraries (such as *.dll, *.ocx, *.so, etc) are allowed to load into a system process.
- **2.9**: The organization's application whitelisting software must ensure that only authorized, digitally signed scripts (such as *.ps1, *.py, macros, etc) are allowed to run on a system.
- **2.10**: Physically or logically segregated systems should be used to isolate and run software that is required for business operations but incur higher risk for the organization.

### § Basic
【C03】 Continuous Vulnerability Management

- **3.1**: Utilize an up-to-date SCAP-compliant vulnerability scanning tool to automatically scan all systems on the network on a weekly or more frequent basis to identify all potential vulnerabilities on the organization's systems.
- **3.2**: Perform authenticated vulnerability scanning with agents running locally on each system or with remote scanners that are configured with elevated rights on the system being tested.
- **3.3**: Use a dedicated account for authenticated vulnerability scans, which should not be used for any other administrative activities and should be tied to specific machines at specific IP addresses.
- **3.4**: Deploy automated software update tools in order to ensure that the operating systems are running the most recent security updates provided by the software vendor.
- **3.5**: Deploy automated software update tools in order to ensure that third-party software on all systems is running the most recent security updates provided by the software vendor.
- **3.6**: Regularly compare the results from back-to-back vulnerability scans to verify that vulnerabilities have been remediated in a timely manner.
- **3.7**: Utilize a risk-rating process to prioritize the remediation of discovered vulnerabilities.

### § Basic
【C04】 Controlled Use of Administrative Privileges

- **4.1**: Use automated tools to inventory all administrative accounts, including domain and local accounts, to ensure that only authorized individuals have elevated privileges.
- **4.2**: Before deploying any new asset, change all default passwords to have values consistent with administrative level accounts.
- **4.3**: Ensure that all users with administrative account access use a dedicated or secondary account for elevated activities. This account should only be used for administrative activities and not internet browsing, email, or similar activities.
- **4.4**: Where multi-factor authentication is not supported (such as local administrator, root, or service accounts), accounts will use passwords that are unique to that system.
- **4.5**: Use multi-factor authentication and encrypted channels for all administrative account access.
- **4.6**: Ensure administrators use a dedicated machine for all administrative tasks or tasks requiring administrative access. This machine will be segmented from the organization's primary network and not be allowed Internet access. This machine will not be used for reading e-mail, composing documents, or browsing the Internet.
- **4.7**: Limit access to scripting tools (such as Microsoft PowerShell and Python) to only administrative or development users with the need to access those capabilities.
- **4.8**: Configure systems to issue a log entry and alert when an account is added to or removed from any group assigned administrative privileges.
- **4.9**: Configure systems to issue a log entry and alert on unsuccessful logins to an administrative account.

### § Basic
【C05】 Secure Configuration for Hardware and Software on Mobile Devices, Laptops, Workstations and Servers

- **5.1**: Maintain documented, standard security configuration standards for all authorized operating systems and software.
- **5.2**: Maintain secure images or templates for all systems in the enterprise based on the organization's approved configuration standards. Any new system deployment or existing system that becomes compromised should be imaged using one of those images or templates.
- **5.3**: Store the master images and templates on securely configured servers, validated with integrity monitoring tools, to ensure that only authorized changes to the images are possible.
- **5.4**: Deploy system configuration management tools that will automatically enforce and redeploy configuration settings to systems at regularly scheduled intervals.
- **5.5**: Utilize a Security Content Automation Protocol (SCAP) compliant configuration monitoring system to verify all security configuration elements, catalog approved exceptions, and alert when unauthorized changes occur.

### § Basic
【C06】 Maintenance, Monitoring and Analysis of Audit Logs

- **6.1**: Use at least three synchronized time sources from which all servers and network devices retrieve time information on a regular basis so that timestamps in logs are consistent.
- **6.2**: Ensure that local logging has been enabled on all systems and networking devices.
- **6.3**: Enable system logging to include detailed information such as a event source, date, user, timestamp, source addresses, destination addresses, and other useful elements.
- **6.4**: Ensure that all systems that store logs have adequate storage space for the logs generated.
- **6.5**: Ensure that appropriate logs are being aggregated to a central log management system for analysis and review.
- **6.6**: Deploy Security Information and Event Management (SIEM) or log analytic tool for log correlation and analysis.
- **6.7**: On a regular basis, review logs to identify anomalies or abnormal events.
- **6.8**: On a regular basis, tune your SIEM system to better identify actionable events and decrease event noise.

### § Foundational
【C07】 Email and Web Browser Protections

- **7.1**: Ensure that only fully supported web browsers and email clients are allowed to execute in the organization, ideally only using the latest version of the browsers and email clients provided by the vendor.
- **7.2**: Uninstall or disable any unauthorized browser or email client plugins or add-on applications.
- **7.3**: Ensure that only authorized scripting languages are able to run in all web browsers and email clients.
- **7.4**: Enforce network-based URL filters that limit a system's ability to connect to websites not approved by the organization. This filtering shall be enforced for each of the organization's systems, whether they are physically at an organization's facilities or not.
- **7.5**: Subscribe to URL categorization services to ensure that they are up-to-date with the most recent website category definitions available. Uncategorized sites shall be blocked by default.
- **7.6**: Log all URL requests from each of the organization's systems, whether onsite or a mobile device, in order to identify potentially malicious activity and assist incident handlers with identifying potentially compromised systems. 
- **7.7**: Use DNS filtering services to help block access to known malicious domains.
- **7.8**: To lower the chance of spoofed or modified emails from valid domains, implement Domain-based Message Authentication, Reporting and Conformance (DMARC) policy and verification, starting by implementing the Sender Policy Framework (SPF) and the DomainKeys Identified Mail(DKIM) standards.
- **7.9**: Block all e-mail attachments entering the organization's e-mail gateway if the file types are unnecessary for the organization's business.
- **7.10**: Use sandboxing to analyze and block inbound email attachments with malicious behavior.

### § Foundational
【C08】 Malware Defenses

- **8.1**: Utilize centrally managed anti-malware software to continuously monitor and defend each of the organization's workstations and servers.
- **8.2**: Ensure that the organization's anti-malware software updates its scanning engine and signature database on a regular basis.
- **8.3**: Enable anti-exploitation features such as Data Execution Prevention (DEP) or Address Space Layout Randomization (ASLR) that are available in an operating system or deploy appropriate toolkits that can be configured to apply protection to a broader set of applications and executables.
- **8.4**: Configure devices so that they automatically conduct an anti-malware scan of removable media when inserted or connected.
- **8.5**: Configure devices to not auto-run content from removable media.
- **8.6**: Send all malware detection events to enterprise anti-malware administration tools and event log servers for analysis and alerting.
- **8.7**: Enable Domain Name System (DNS) query logging to detect hostname lookups for known malicious domains.
- **8.8**: Enable command-line audit logging for command shells, such as Microsoft Powershell and Bash.

### § Foundational
【C09】 Limitation and Control of Network Ports, Protocols, and Services

- **9.1**: Associate active ports, services and protocols to the hardware assets in the asset inventory.
- **9.2**: Ensure that only network ports, protocols, and services listening on a system with validated business needs, are running on each system.
- **9.3**: Perform automated port scans on a regular basis against all systems and alert if unauthorized ports are detected on a system.
- **9.4**: Apply host-based firewalls or port filtering tools on end systems, with a default-deny rule that drops all traffic except those services and ports that are explicitly allowed.
- **9.5**: Place application firewalls in front of any critical servers to verify and validate the traffic going to the server. Any unauthorized traffic should be blocked and logged.

### § Foundational
【C10】 Data Recovery Capabilities

- **10.1**: Ensure that all system data is automatically backed up on regular basis.
- **10.2**: Ensure that each of the organization's key systems are backed up as a complete system, through processes such as imaging, to enable the quick recovery of an entire system.
- **10.3**: Test data integrity on backup media on a regular basis by performing a data restoration process to ensure that the backup is properly working.
- **10.4**: Ensure that backups are properly protected via physical security or encryption when they are stored, as well as when they are moved across the network. This includes remote backups and cloud services.
- **10.5**: Ensure that all backups have at least one backup destination that is not continuously addressable through operating system calls.

### § Foundational
【C11】 Secure Configuration for Network Devices, such as Firewalls, Routers and Switches

- **11.1**: Maintain standard, documented security configuration standards for all authorized network devices.
- **11.2**: All configuration rules that allow traffic to flow through network devices should be documented in a configuration management system with a specific business reason for each rule, a specific individual’s name responsible for that business need, and an expected duration of the need.
- **11.3**: Compare all network device configuration against approved security configurations defined for each network device in use and alert when any deviations are discovered.
- **11.4**: Install the latest stable version of any security-related updates on all network devices.
- **11.5**: Manage all network devices using multi-factor authentication and encrypted sessions.
- **11.6**: Ensure network engineers use a dedicated machine for all administrative tasks or tasks requiring elevated access. This machine shall be segmented from the organization's primary network and not be allowed Internet access. This machine shall not be used for reading e-mail, composing documents, or surfing the Internet.
- **11.7**: Manage the network infrastructure across network connections that are separated from the business use of that network, relying on separate VLANs or, preferably, on entirely different physical connectivity for management sessions for network devices.

### § Foundational
【C12】 Boundary Defense

- **12.1**: Maintain an up-to-date inventory of all of the organization's network boundaries.
- **12.2**: Perform regular scans from outside each trusted network boundary to detect any unauthorized connections which are accessible across the boundary.
- **12.3**: Deny communications with known malicious or unused Internet IP addresses and limit access only to trusted and necessary IP address ranges at each of the organization's network boundaries,.
- **12.4**: Deny communication over unauthorized TCP or UDP ports or application traffic to ensure that only authorized protocols are allowed to cross the network boundary in or out of the network at each of the organization's network boundaries.
- **12.5**: Configure monitoring systems to record network packets passing through the boundary at each of the organization's network boundaries.
- **12.6**: Deploy network-based Intrusion Detection Systems (IDS) sensors to look for unusual attack mechanisms and detect compromise of these systems at each of the organization's network boundaries.
- **12.7**: Deploy network-based Intrusion Prevention Systems (IPS) to block malicious network traffic at each of the organization's network boundaries.
- **12.8**: Enable the collection of NetFlow and logging data on all network boundary devices.
- **12.9**: Ensure that all network traffic to or from the Internet passes through an authenticated application layer proxy that is configured to filter unauthorized connections.
- **12.10**: Decrypt all encrypted network traffic at the boundary proxy prior to analyzing the content. However, the organization may use whitelists of allowed sites that can be accessed through the proxy without decrypting the traffic.
- **12.11**: Require all remote login access to the organization's network to encrypt data in transit and use multi-factor authentication.
- **12.12**: Scan all enterprise devices remotely logging into the organization's network prior to accessing the network to ensure that each of the organization's security policies has been enforced in the same manner as local network devices.

### § Foundational
【C13】 Data Protection

- **13.1**: Maintain an inventory of all sensitive information stored, processed, or transmitted by the organization's technology systems, including those located onsite or at a remote service provider.
- **13.2**: Remove sensitive data or systems not regularly accessed by the organization from the network. These systems shall only be used as stand alone systems (disconnected from the network) by the business unit needing to occasionally use the system or completely virtualized and powered off until needed.
- **13.3**: Deploy an automated tool on network perimeters that monitors for unauthorized transfer of sensitive information and blocks such transfers while alerting information security professionals.
- **13.4**: Only allow access to authorized cloud storage or email providers.
- **13.5**: Monitor all traffic leaving the organization and detect any unauthorized use of encryption.
- **13.6**: Utilize approved whole disk encryption software to encrypt the hard drive of all mobile devices.
- **13.7**: If USB storage devices are required, enterprise software should be used that can configure systems to allow the use of specific devices. An inventory of such devices should be maintained.
- **13.8**: Configure systems not to write data to external removable media, if there is no business need for supporting such devices.
- **13.9**: If USB storage devices are required, all data stored on such devices must be encrypted while at rest.

### § Foundational
【C14】 Controlled Access Based on the Need to Know

- **14.1**: Segment the network based on the label or classification level of the information stored on the servers, locate all sensitive information on separated Virtual Local Area Networks (VLANs).
- **14.2**: Enable firewall filtering between VLANs to ensure that only authorized systems are able to communicate with other systems necessary to fulfill their specific responsibilities.
- **14.3**: Disable all workstation to workstation communication to limit an attacker's ability to move laterally and compromise neighboring systems, through technologies such as Private VLANs or microsegmentation.
- **14.4**: Encrypt All Sensitive Information in Transit.
- **14.5**: Utilize an active discovery tool to identify all sensitive information stored, processed, or transmitted by the organization's technology systems, including those located onsite or at a remote service provider and update the organization's sensitive information inventory.
- **14.6**: Protect all information stored on systems with file system, network share, claims, application, or database specific access control lists. These controls will enforce the principle that only authorized individuals should have access to the information based on their need to access the information as a part of their responsibilities.
- **14.7**: Use an automated tool, such as host-based Data Loss Prevention, to enforce access controls to data even when data is copied off a system.
- **14.8**: Encrypt all sensitive information at rest using a tool that requires a secondary authentication mechanism not integrated into the operating system, in order to access the information.
- **14.9**: Enforce detailed audit logging for access to sensitive data or changes to sensitive data (utilizing tools such as File Integrity Monitoring or Security Information and Event Monitoring).

### § Foundational
【C15】 Wireless Access Control

- **15.1**: Maintain an inventory of authorized wireless access points connected to the wired network.
- **15.2**: Configure network vulnerability scanning tools to detect and alert on unauthorized wireless access points connected to the wired network.
- **15.3**: Use a wireless intrusion detection system (WIDS) to detect and alert on unauthorized wireless access points connected to the network.
- **15.4**: Disable wireless access on devices that do not have a business purpose for wireless access.
- **15.5**: Configure wireless access on client machines that do have an essential wireless business purpose, to allow access only to authorized wireless networks and to restrict access to other wireless networks.
- **15.6**: Disable peer-to-peer (adhoc) wireless network capabilities on wireless clients.
- **15.7**: Leverage the Advanced Encryption Standard (AES) to encrypt wireless data in transit.
- **15.8**: Ensure that wireless networks use authentication protocols such as Extensible Authentication Protocol-Transport Layer Security (EAP/TLS), that requires mutual, multi-factor authentication.
- **15.9**: Disable wireless peripheral access of devices (such as Bluetooth and NFC), unless such access is required for a business purpose.
- **15.10**: Create a separate wireless network for personal or untrusted devices. Enterprise access from this network should be treated as untrusted and filtered and audited accordingly.

### § Foundational
【C16】 Account Monitoring and Control

- **16.1**: Maintain an inventory of each of the organization's authentication systems, including those located onsite or at a remote service provider.
- **16.2**: Configure access for all accounts through as few centralized points of authentication as possible, including network, security, and cloud systems.
- **16.3**: Require multi-factor authentication for all user accounts, on all systems, whether managed onsite or by a third-party provider.
- **16.4**: Encrypt or hash with a salt all authentication credentials when stored.
- **16.5**: Ensure that all account usernames and authentication credentials are transmitted across networks using encrypted channels.
- **16.6**: Maintain an inventory of all accounts organized by authentication system.
- **16.7**: Establish and follow an automated process for revoking system access by disabling accounts immediately upon termination or change of responsibilities of an employee or contractor . Disabling these accounts, instead of deleting accounts, allows preservation of audit trails.
- **16.8**: Disable any account that cannot be associated with a business process or business owner.
- **16.9**: Automatically disable dormant accounts after a set period of inactivity.
- **16.10**: Ensure that all accounts have an expiration date that is monitored and enforced.
- **16.11**: Automatically lock workstation sessions after a standard period of inactivity.
- **16.12**: Monitor attempts to access deactivated accounts through audit logging.
- **16.13**: Alert when users deviate from normal login behavior, such as time-of-day, workstation location and duration.

### § Organizational
【C17】 Implement a Security Awareness and Training Program

- **17.1**: Perform a skills gap analysis to understand the skills and behaviors workforce members are not adhering to, using this information to build a baseline education roadmap.
- **17.2**: Deliver training to address the skills gap identified to positively impact workforce members' security behavior.
- **17.3**: Create a security awareness program for all workforce members to complete on a regular basis to ensure they understand and exhibit the necessary behaviors and skills to help ensure the security of the organization. The organization's security awareness program should be communicated in a continuous and engaging manner.
- **17.4**: Ensure that the organization's security awareness program is updated frequently (at least annually) to address new technologies, threats, standards and business requirements.
- **17.5**: Train workforce members on the importance of enabling and utilizing secure authentication.
- **17.6**: Train the workforce on how to identify different forms of social engineering attacks, such as phishing, phone scams and impersonation calls.
- **17.7**: Train workforce on how to identify and properly store, transfer, archive and destroy sensitive information.
- **17.8**: Train workforce members to be aware of causes for unintentional data exposures, such as losing their mobile devices or emailing the wrong person due to autocomplete in email.
- **17.9**: Train employees to be able to identify the most common indicators of an incident and be able to report such an incident.

### § Organizational
【C18】 Application Software Security

- **18.1**: Establish secure coding practices appropriate to the programming language and development environment being used.
- **18.2**: For in-house developed software, ensure that explicit error checking is performed and documented for all input, including for size, data type, and acceptable ranges or formats.
- **18.3**: Verify that the version of all software acquired from outside your organization is still supported by the developer or appropriately hardened based on developer security recommendations.
- **18.4**: Only use up-to-date and trusted third-party components for the software developed by the organization.
- **18.5**: Use only standardized and extensively reviewed encryption algorithms.
- **18.6**: Ensure that all software development personnel receive training in writing secure code for their specific development environment and responsibilities.
- **18.7**: Apply static and dynamic analysis tools to verify that secure coding practices are being adhered to for internally developed software.
- **18.8**: Establish a process to accept and address reports of software vulnerabilities, including providing a means for external entities to contact your security group.
- **18.9**: Maintain separate environments for production and nonproduction systems. Developers should not have unmonitored access to production environments.
- **18.10**: Protect web applications by deploying web application firewalls (WAFs) that inspect all traffic flowing to the web application for common web application attacks. For applications that are not web-based, specific application firewalls should be deployed if such tools are available for the given application type. If the traffic is encrypted, the device should either sit behind the encryption or be capable of decrypting the traffic prior to analysis. If neither option is appropriate, a host-based web application firewall should be deployed.
- **18.11**: For applications that rely on a database, use standard hardening configuration templates. All systems that are part of critical business processes should also be tested.

### § Organizational
【C19】 Incident Response and Management

- **19.1**: Ensure that there are written incident response plans that defines roles of personnel as well as phases of incident handling/management.
- **19.2**: Assign job titles and duties for handling computer and network incidents to specific individuals and ensure tracking and documentation throughout the incident through resolution.
- **19.3**: Designate management personnel, as well as backups, who will support the incident handling process by acting in key decision-making roles.
- **19.4**: Devise organization-wide standards for the time required for system administrators and other workforce members to report anomalous events to the incident handling team, the mechanisms for such reporting, and the kind of information that should be included in the incident notification.
- **19.5**: Assemble and maintain information on third-party contact information to be used to report a security incident, such as Law Enforcement, relevant government departments, vendors, and ISAC partners.
- **19.6**: Publish information for all workforce members, regarding reporting computer anomalies and incidents to the incident handling team. Such information should be included in routine employee awareness activities.
- **19.7**: Plan and conduct routine incident response exercises and scenarios for the workforce involved in the incident response to maintain awareness and comfort in responding to real world threats. Exercises should test communication channels, decision making, and incident responders technical capabilities using tools and data available to them.
- **19.8**: Create incident scoring and prioritization schema based on known or potential impact to your organization. Utilize score to define frequency of status updates and escalation procedures.

### § Organizational
【C20】 Penetration Tests and Red Team Exercises

- **20.1**: Establish a program for penetration tests that includes a full scope of blended attacks, such as wireless, client-based, and web application attacks.
- **20.2**: Conduct regular external and internal penetration tests to identify vulnerabilities and attack vectors that can be used to exploit enterprise systems successfully.
- **20.3**: Perform periodic Red Team exercises to test organizational readiness to identify and stop attacks or to respond quickly and effectively.
- **20.4**: Include tests for the presence of unprotected system information and artifacts that would be useful to attackers, including network diagrams, configuration files, older penetration test reports, e-mails or documents containing passwords or other information critical to system operation.
- **20.5**: Create a test bed that mimics a production environment for specific penetration tests and Red Team attacks against elements that are not typically tested in production, such as attacks against supervisory control and data acquisition and other control systems.
- **20.6**: Use vulnerability scanning and penetration testing tools in concert. The results of vulnerability scanning assessments should be used as a starting point to guide and focus penetration testing efforts.
- **20.7**: Wherever possible, ensure that Red Teams results are documented using open, machine-readable standards (e.g., SCAP). Devise a scoring method for determining the results of Red Team exercises so that results can be compared over time.
- **20.8**: Any user or system accounts used to perform penetration testing should be controlled and monitored to make sure they are only being used for legitimate purposes, and are removed or restored to normal function after testing is over.

