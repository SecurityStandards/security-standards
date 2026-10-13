# CIS Google Cloud Foundations (v1.1.0)

Referência oficial: #

## Controles e Domínios (7)

### Identity and Access Management

- **1.1**: Use corporate login credentials instead of personal accounts, such as Gmail accounts.
- **1.2**: Setup multi-factor authentication for Google Cloud Platform accounts.
- **1.3**: Setup Security Key Enforcement for Google Cloud Platform admin accounts.
- **1.4**: User managed service accounts should not have user-managed keys.
- **1.5**: A service account is a special Google account that belongs to an application or a VM, instead of to an individual end-user. The application uses the service account to call the service's Google API so that users aren't directly involved. It's recommended not to use admin access for ServiceAccount.
- **1.6**: It is recommended to assign the Service Account User (iam.serviceAccountUser) and Service Account Token Creator (iam.serviceAccountTokenCreator) roles to a user for a specific service account rather than assigning the role to a user at project level.
- **1.7**: Service Account keys consist of a key ID (Private_key_Id) and Private key, which are used to sign programmatic requests users make to Google cloud services accessible to that particular service account. It is recommended that all Service Account keys are regularly rotated.
- **1.8**: It is recommended that the principle of 'Separation of Duties' is enforced while assigning service-account related roles to users.
- **1.9**: It is recommended that the IAM policy on Cloud KMS cryptokeys should restrict anonymous and/or public access.
- **1.10**: Google Cloud Key Management Service stores cryptographic keys in a hierarchical structure designed for useful and elegant access control management.
The format for the rotation schedule depends on the client library that is used. For the gcloud command-line tool, the next rotation time must be in ISO or RFC3339 format, and the rotation period must be in the form INTEGER[UNIT], where units can be one of seconds (s), minutes (m), hours (h) or days (d).
- **1.11**: It is recommended that the principle of 'Separation of Duties' is enforced while assigning KMS related roles to users.
- **1.12**: Keys are insecure because they can be viewed publicly, such as from within a browser, or they can be accessed on a device where the key resides. It is recommended to use standard authentication flow instead.
- **1.13**: Unrestricted keys are insecure because they can be viewed publicly, such as from within a browser, or they can be accessed on a device where the key resides. It is recommended to restrict API key usage to trusted hosts, HTTP referrers and apps.
- **1.14**: API keys are insecure because they can be viewed publicly, such as from within a browser, or they can be accessed on a device where the key resides. It is recommended to restrict API keys to use (call) only APIs required by an application.
- **1.15**: It is recommended to rotate API keys every 90 days.

### Logging and Monitoring

- **2.1**: It is recommended that Cloud Audit Logging is configured to track all admin activities and read, write access to user data.
- **2.2**: It is recommended to create a sink that will export copies of all the log entries. This can help aggregate logs from multiple projects and export them to a Security Information and Event Management (SIEM).
- **2.3**: Enabling retention policies on log buckets will protect logs stored in cloud storage buckets from being overwritten or accidentally deleted. It is recommended to set up retention policies and configure Bucket Lock on all storage buckets that are used as log sinks.
- **2.4**: In order to prevent unnecessary project ownership assignments to users/service-accounts and further misuses of projects and resources, all `roles/Owner` assignments should be monitored.
- **2.5**: Google Cloud Platform (GCP) services write audit log entries to the Admin Activity and Data Access logs to help answer the questions of, "who did what, where, and when?" within GCP projects.
Cloud audit logging records information includes the identity of the API caller, the time of the API call, the source IP address of the API caller, the request parameters, and the response elements returned by GCP services. Cloud audit logging provides a history of GCP API calls for an account, including API calls made via the console, SDKs, command-line tools, and other GCP services.
- **2.6**: It is recommended that a metric filter and alarm be established for changes to Identity and Access Management (IAM) role creation, deletion and updating activities.
- **2.7**: It is recommended that a metric filter and alarm be established for Virtual Private Cloud (VPC) Network Firewall rule changes.
- **2.8**: It is recommended that a metric filter and alarm be established for Virtual Private Cloud (VPC) network route changes.
- **2.9**: It is recommended that a metric filter and alarm be established for Virtual Private Cloud (VPC) network changes.
- **2.10**: It is recommended that a metric filter and alarm be established for Cloud Storage Bucket IAM changes.
- **2.11**: It is recommended that a metric filter and alarm be established for SQL instance configuration changes.

### Networking

- **3.1**: To prevent use of default network, a project should not have a default network.
- **3.2**: In order to prevent use of legacy networks, a project should not have a legacy network configured.
- **3.3**: Cloud Domain Name System (DNS) is a fast, reliable and cost-effective domain name system that powers millions of domains on the internet. Domain Name System Security Extensions (DNSSEC) in Cloud DNS enables domain owners to take easy steps to protect their domains against DNS hijacking and man-in-the-middle and other attacks.
- **3.4**: DNSSEC algorithm numbers in this registry may be used in CERT RRs. Zone signing (DNSSEC) and transaction security mechanisms (SIG(0) and TSIG) make use of particular subsets of these algorithms. The algorithm used for key signing should be a recommended one and it should be strong.
- **3.5**: DNSSEC algorithm numbers in this registry may be used in CERT RRs. Zone signing (DNSSEC) and transaction security mechanisms (SIG(0) and TSIG) make use of particular subsets of these algorithms. The algorithm used for key signing should be a recommended one and it should be strong.
- **3.6**: GCP Firewall Rules are specific to a VPC Network. Each rule either allows or denies traffic when its conditions are met. Its conditions allow the user to specify the type of traffic, such as ports and protocols, and the source or destination of the traffic, including IP addresses, subnets, and instances.
Firewall rules are defined at the VPC network level and are specific to the network in which they are defined. The rules themselves cannot be shared among networks. Firewall rules only support IPv4 traffic. When specifying a source for an ingress rule or a destination for an egress rule by address, only an IPv4 address or IPv4 block in CIDR notation can be used. Generic (0.0.0.0/0) incoming traffic from the internet to VPC or VM instance using SSH on Port 22 can be avoided.
- **3.7**: GCP Firewall Rules are specific to a VPC Network. Each rule either allows or denies traffic when its conditions are met. Its conditions allow users to specify the type of traffic, such as ports and protocols, and the source or destination of the traffic, including IP addresses, subnets, and instances.
Firewall rules are defined at the VPC network level and are specific to the network in which they are defined. The rules themselves cannot be shared among networks. Firewall rules only support IPv4 traffic. When specifying a source for an ingress rule or a destination for an egress rule by address, an IPv4 address or IPv4 block in CIDR notation can be used. Generic (0.0.0.0/0) incoming traffic from the Internet to a VPC or VM instance using RDP on Port 3389 can be avoided.
- **3.8**: Flow Logs is a feature that enables users to capture information about the IP traffic going to and from network interfaces in the organization's VPC Subnets. Once a flow log is created, the user can view and retrieve its data in Stackdriver Logging. It is recommended that Flow Logs be enabled for every business-critical VPC subnet.
- **3.9**: Secure Sockets Layer (SSL) policies determine what port Transport Layer Security (TLS) features clients are permitted to use when connecting to load balancers. To prevent usage of insecure features, SSL policies should use (a) at least TLS 1.2 with the MODERN profile; or (b) the RESTRICTED profile, because it effectively requires clients to use TLS 1.2 regardless of the chosen minimum TLS version; or (3) a CUSTOM profile that does not support any of the following features:
  • TLS_RSA_WITH_AES_128_GCM_SHA256
  • TLS_RSA_WITH_AES_256_GCM_SHA384
  • TLS_RSA_WITH_AES_128_CBC_SHA
  • TLS_RSA_WITH_AES_256_CBC_SHA
  • TLS_RSA_WITH_3DES_EDE_CBC_SHA

### Virtual Machines

- **4.1**: It is recommended to configure your instance to not use the default Compute Engine service account because it has the Editor role on the project.
- **4.2**: To support principle of least privileges and prevent potential privilege escalation it is recommended that instances are not assigned to default service account "Compute Engine default service account" with Scope "Allow full access to all Cloud APIs."
- **4.3**: It is recommended to use Instance specific SSH key(s) instead of using common/shared project-wide SSH key(s) to access Instances.
- **4.4**: Enabling OS login binds SSH certificates to IAM users and facilitates effective SSH certificate management.
- **4.5**: Interacting with a serial port is often referred to as the serial console, which is similar to using a terminal window, in that input and output is entirely in text mode and there is no graphical interface or mouse support.
If you enable the interactive serial console on an instance, clients can attempt to connect to that instance from any IP address. Therefore interactive serial console support should be disabled.
- **4.6**: Compute Engine instance cannot forward a packet unless the source IP address of the packet matches the IP address of the instance. Similarly, GCP won't deliver a packet whose destination IP address is different than the IP address of the instance receiving the packet. However, both capabilities are required if you want to use instances to help route packets.
Forwarding of data packets should be disabled to prevent data loss or information disclosure.
- **4.7**: Customer-Supplied Encryption Keys (CSEK) are a feature in Google Cloud Storage and Google Compute Engine. If you supply your own encryption keys, Google uses your key to protect the Google-generated keys used to encrypt and decrypt your data. By default, Google Compute Engine encrypts all data at rest. Compute Engine handles and manages this encryption for you without any additional actions on your part. However, if you wanted to control and manage this encryption yourself, you can provide your own encryption keys.
- **4.8**: To defend against against advanced threats and ensure that the boot loader and firmware on your VMs are signed and untampered, it is recommended that Compute instances are launched with Shielded VM enabled.
- **4.9**: Compute instances should not be configured to have external IP addresses.
- **4.10**: In order to maintain the highest level of security all connections to an application should be secure by default.

### Storage

- **5.1**: It is recommended that IAM policy on Cloud Storage bucket does not allows anonymous or public access.
- **5.2**: It is recommended that uniform bucket-level access is enabled on Cloud Storage buckets.

### Cloud SQL Database Services

- **6.1.1**: It is recommended to set a password for the administrative user (root by default) to prevent unauthorized access to the SQL database instances.
This recommendation is applicable only for MySQL Instances. PostgreSQL does not offer any setting for No Password from the cloud console.
- **6.1.2**: It is recommended to set the `local_infile` database flag for a Cloud SQL MySQL instance to `off`.
- **6.2.1**: Ensure that the `log_checkpoints` database flag for the Cloud SQL PostgreSQL instance is set to `on`.
- **6.2.2**: Enabling the log_connections setting causes each attempted connection to the server to be logged, along with successful completion of client authentication. This parameter cannot be changed after the session starts.
- **6.2.3**: Enabling the `log_disconnections` setting logs the end of each session, including the session duration.
- **6.2.4**: Enabling the `log_lock_waits` flag for a PostgreSQL instance creates a log for any session waits that take longer than the alloted `deadlock_timeout` time to acquire a lock.
- **6.2.5**: The `log_min_error_statement` flag defines the minimum message severity level that is considered as an error statement. Messages for error statements are logged with the SQL statement. Valid values include DEBUG5, DEBUG4, DEBUG3, DEBUG2, DEBUG1, INFO, NOTICE, WARNING, ERROR, LOG, FATAL, and PANIC. Each severity level includes the subsequent levels mentioned above.
- **6.2.6**: PostgreSQL can create a temporary file for actions such as sorting, hashing and temporary query results when these operations exceed `work_mem`. The `log_temp_files` flag controls logging names and the file size when it is deleted. Configuring `log_temp_files` to 0 causes all temporary file information to be logged, while positive values log only files whose size is greater than or equal to the specified number of kilobytes. A value of -1 disables temporary file information logging.
- **6.2.7**: The `log_min_duration_statement` flag defines the minimum amount of execution time of a statement in milliseconds where the total duration of the statement is logged. Ensure that `log_min_duration_statement` is disabled, i.e., a value of -1 is set.
- **6.3.1**: It is recommended to set "cross db ownership chaining database" flag for Cloud SQL SQL Server instance to `off`.
- **6.3.2**: It is recommended to set "contained database authentication database" flag for Cloud SQL on the SQL Server instance is set to `off`.
- **6.4**: It is recommended to enforce all incoming connections to SQL database instance to use SSL.
- **6.5**: Database Server should accept connections only from trusted Network(s)/IP(s) and restrict access from the world.
- **6.6**: It is recommended to configure Second Generation Sql instance to use private IPs instead of public IPs.
- **6.7**: It is recommended to have all SQL database instances set to enable automated backups.

### BigQuery

- **7.1**: It is recommended that the IAM policy on BigQuery datasets does not allow anonymous and/or public access.

