# The SaaS CTO Security Checklist

> Checklist de segurança essencial para fundadores, CTOs e lideranças técnicas de startups e empresas SaaS.


## Your company

### [ ] Ensure your domain names are secured `[Seed]`

Domain names should be renewed regularly. If you have bought one from a third party, you should also make sure that the authoritative configured name server is your own. Read more: http://www.esecurityplanet.com/views/article.php/3928456/8-Tips-for-Protecting-Your-Domain-Names.htm Be honest and transparent about any data you collect Seed In the case of a breach, the attackers may disclose any data they gather. Your customers need to be aware of what data you're storing. Read more: https://hbr.org/2015/05/customer-data-designing-for-transparency-and-trust

### [ ] Make sure all your critical services are secured `[Seed]`

Many companies rely on Google Apps, Slack, Wordpress… These services all have defaults that should be improved to increase the security level. All of these services should be kept up to date. Read more: https://blog.trailofbits.com/2015/07/07/how-to-harden-your-google-apps/ https://codex.wordpress.org/Hardening_WordPress

### [ ] Make sure your email is secured `[Seed]`

Email is the first point of call for cyber attacks with research indicating that 91% of them start via email. DMARC is a widely deployed industry-standard protocol that helps companies secure their email and domains against phishing attacks. Check your domains: https://ondmarc.com Read more: https://dmarc.org

### [ ] Do not share WiFi `[Seed]`

Sharing WiFi networks with guests or neighbors may give them the opportunity to gather information on your network, and allow them to access resources protected by source IP. Use an isolated and dedicated guest WiFi network. Set up a calendar reminder to change the password every two months, since this password is shared.

### [ ] Take special care of your non-tech employees `[Series A]`

Non-tech employees are less used to technical trickery and can be deceived more easily than others, opening the door to ransomware or confidentiality issues. They should be trained and empowered to be distrustful and to preserve the company’s assets. Read more: http://www.zdnet.com/pictures/hacked-the-six-most-common-ways-non-tech-people-fall-victim

### [ ] Have a public security policy `[Series A]`

This is a page on your corporate website describing how you plan to respond to external bug reports. You should advertise that you support responsible disclosure . Keep in mind that most of the reports that you receive probably won't be relevant. Great examples: https://www.airbnb.com/security https://www.apple.com/support/security/

### [ ] Have an internal security policy `[Post-Series A]`

This is a short document stating the security requirements in your company and defining who is responsible and who is concerned with all aspects of security. Read More: https://www.sans.org/reading-room/whitepapers/policyissues/creating-information-systems-security-policy-534

### [ ] Set up a bug bounty program `[Post-Series A]`

A bug bounty program will allow external hackers to report vulnerabilities. Most of the bug bounties program allow you to offer rewards for bugs found. You need security aware people inside your development teams to evaluate any reports you receive. Places to start: https://bountyfactory.io/ https://hackerone.com/ https://cobalt.io

### [ ] Make an inventory of your company’s assets `[Post-Series A]`

An awareness of your company’s assets enables you to monitor the points that need the most attention and vulnerabilities that need to be hardened. Read more: http://advisera.com/27001academy/knowledgebase/how-to-handle-asset-register-asset-inventory-according-to-iso-27001/

### [ ] Have a security incident response plan `[Post-Series A]`

This will allow whoever is in charge at the time of a breach to communicate accordingly about an incident and will allow the fastest response in technical / communication terms. Read more: https://zeltser.com/security-incident-response-program-tips/


## Your employees

### [ ] Accustom everyone to security practices `[Seed]`

Humans are often the weakest links in the chain of security. By explaining how an attacker could infiltrate your company, you will increase your employees’ awareness and thus minimize the chance of them falling for such a trap. http://www.govtech.com/blogs/lohrmann-on-cybersecurity/Ten-Recommendations-for-Security-Awareness-Programs.html

### [ ] Require 2FA in your services `[Seed]`

Your employees should all use 2-factor authentication on all services you use. If their password is stolen, the attacker cannot use it without the second factor. Read more: https://en.wikipedia.org/wiki/Multi-factor_authentication https://support.google.com/a/answer/184711 https://get.slack.help/hc/en-us/articles/212221668-Require-two-factor-authentication-for-your-team

### [ ] Encrypt all employee laptops &amp; phones `[Seed]`

By encrypting all laptops, you protect both your company’s assets, and your employees’ private files. Read more: https://support.apple.com/en-us/HT204837 https://wiki.archlinux.org/index.php/Dm-crypt https://support.microsoft.com/en-us/instantanswers/e7d75dd2-29c2-16ac-f03d-20cfdf54202f/turn-on-device-encryption Locking your employees’ phone is the same, and will protect against both pranks and accidents (e.g. an employee’s child accidentally wiping a mailbox).

### [ ] Accustom your team to locking their machines while away `[Seed]`

Your office may be secured, but you will eventually have to receive external people for a party or a meeting. Locking all the machines is a great habit. If you get in the habit of locking your machine at the office, you’ll be unlikely to forget to also do it in a Starbucks or at a meetup. Read more: https://www.cnet.com/how-to/7-ways-to-lock-your-macbook

### [ ] Use a password manager to ensure you only use strong passwords `[Seed]`

Using a complex and unique password for every website is great advice, but it can be very difficult to remember all of them. Password managers are a great way to manage these, since they will remember everything for you with a master password. Great password managers are: https://www.dashlane.com https://lastpass.com https://support.apple.com/en-us/HT204085

### [ ] Follow an onboarding / offboarding checklist `[Seed]`

This checklist should contain a list of all the steps you need to enforce when an employee, contractor, intern, etc., joins your company. A similar list should also be used when the someone is leaving your team to ensure that they no longer have access to any of your company’s resources. Great examples from Gitlab: https://about.gitlab.com/handbook/general-onboarding/ https://about.gitlab.com/handbook/offboarding/

### [ ] Do not share accounts `[Series A]`

Sharing a user account makes it hard to understand who is using the service or to identify who has performed a given action.

### [ ] Use centralized account management `[Series A]`

A centralized place with all user authorizations is the best way not to forget anything once you need to update a user profile (e.g. if an internship came to its end). It is also great place to define standard account creation you need for a given user. Configuring with Google Apps: https://support.google.com/a/answer/6087519


## Your infrastructure

### [ ] Use SSL certificates to secure people using your website `[Seed]`

Encrypting communications is not only about privacy, but also about your users’ safety, since it will prevent most attempts at tempering with what they receive. Two free popular solutions are: https://letsencrypt.org/ https://www.cloudflare.com/ssl/ You can also choose your own custom certificate (which may allow you to get a beautiful green bar if you pay for the extra “Extended Validation”): https://www.digicert.com https://www.rapidssl.com

### [ ] Check your website’s basic security `[Seed]`

Websites are vulnerable to many different classes of vulnerabilities, some may be prevented by the appropriate configuration on the server. Static websites may expose your users to less risks. Check your website configuration: https://myheaders.sqreen.io https://securityheaders.io https://www.ssllabs.com/

### [ ] Isolate assets at the network level `[Seed]`

Only your public APIs should be exposed to the Internet. You should isolate your networks to prevent any unauthorized accesses to your database. This will prevent attackers from connecting to it and attempting to crack the password, or exploit vulnerabilities. Read more: http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Subnets.html

### [ ] Keep your OS up to date `[Seed]`

You should download all of your OS’s security updates and regularly update your machines. For servers, you can delegate it to a PaaS provider (Heroku, AWS Beanstalk, etc.). https://appcanary.com/

### [ ] Backup, then backup again `[Seed]`

Backup all your critical assets. Ensure that you attempt to restore your backups frequently so you can guarantee that they're working as intended. S3 is a very cheap and effective way to backup your assets: https://aws.amazon.com/getting-started/backup-files-to-amazon-s3/

### [ ] Restrict internal services by IP addresses (your company’s ISP, VPNs, etc.) `[Series A]`

Everything non-public should only be accessible through a bounce host (e.g. no direct access to databases). Read more: https://aws.amazon.com/fr/blogs/security/securely-connect-to-linux-instances-running-in-a-private-amazon-vpc/

### [ ] Centralize and archive your logs and make them meaningful `[Series A]`

Logs are necessary to trace what happened after an incident, find where the attacker came from, and possible even who they are. Many solutions exist to gather your logs. You need to take care about that the system time configured on each of your machines is in sync so that you can easily cross-correlate logs. Read more: https://en.wikipedia.org/wiki/Network_Time_Protocol https://www.elastic.co/products

### [ ] Protect your application from DDoS attacks `[Series A]`

A Distributed Denial-of-Service Attack (DDoS) can have devastating consequences on businesses. Basic DDoS protections can easily by integrated with a CDN such as CloudFlare or CloudFront .

### [ ] Keep a list of your servers `[Series A]`

This is built-in if you are using a cloud service and all your machines are registered or spawned through it. Otherwise, you will need to create and maintain a list of your assets (servers, network devices, etc.), and review it regularly to determine if you still need them, keep them up to date, and ensure that they benefit from your latest deployments.

### [ ] Watch for unusual patterns in your metrics `[Series A]`

Takeovers will often be used to steal your data or setup your servers to be used as bouncers. These can be detected by watching for unusual patterns in metrics such as network bandwidth, CPU and memory consumption, and disk usage. https://newrelic.com/server-monitoring https://www.sysdig.com/

### [ ] Know how to redeploy infrastructure from scratch `[Post-Series A]`

This allows you to quickly spawn new infrastructure and populate it with data from your backups. This is the perfect use case for disaster recovery. Read More: https://aws.amazon.com/cloudformation/ https://cloud.google.com/deployment-manager/


## Your code

### [ ] Enforce a secure code review checklist `[Seed]`

Security should always be kept in mind while coding. Pull requests should be performed with security in mind as well. Depending on where the code is, the checks should be different. Dealing with user entry is one thing, dealing with business structures is another: the concerns are related to the context. In addition to common sense, keep in mind the typical security flaws. Security is also a good topic to ask about when interviewing a candidate. Read more: https://www.owasp.org/index.php/Top_10-2017_Top_10

### [ ] Use a static security code analysis tool `[Seed]`

Static code analysis tools can quickly overwhelm you with a lot of meaningless false-positives. But switching on security-focused tools can help you discover vulnerabilities inside your code and most importantly increase the security awareness inside your team. Integrate these tools with your workflow to reduce friction. Post-commit checks that automatically comment where code reviews are performed are ideal. Tools: https://www.codacy.com/ https://www.owasp.org/index.php/Source_Code_Analysis_Tools

### [ ] Maintain a backlog of security concerns in your issue tracking tool `[Seed]`

Every developer should contribute to maintaining a list of security issues to be fixed in the future. Making them available to the rest of the team will increase the security awareness in the company.

### [ ] Never do cryptography yourself `[Seed]`

Always rely on existing mechanisms, libraries and tools. Cryptography is an expertise. Building your implementations, or using flags and options you don't fully understand will expose you to major risks. Libraries such as na.cl expose few options and restrict you to the good choices.

### [ ] Keep secrets away from code `[Seed]`

Never commit secrets in your code. They should be handled separately in order to prevent them accidentally being shared or exposed. This allows a clear separation between your environments (typically development, staging and production). Read more: https://12factor.net/

### [ ] Perform security oriented test sessions `[Series A]`

Once in a while, the entire technical team should sit together and spend time targeting all parts of the application, looking for vulnerabilities. This is a great time to test for account isolation, token unicity, unauthenticated paths, etc. You will heavily rely on your browser’s web console, curl, and 3rd party tools such as Burp . Read more: https://www.owasp.org/index.php/OWASP_Testing_Guide_v4_Table_of_Contents

### [ ] Use a secure development life cycle `[Post-Series A]`

The secure development lifecycle is a process that helps tackle security issues at the beginning of a project. While rarely used as is, it provides good insights at all stages of the project, from the specification to the release. It will allow you to enforce good practices at every stage of the project life. Read More: https://en.wikipedia.org/wiki/Systems_development_life_cycle


## Your application

### [ ] Run it unprivileged `[Seed]`

In case an attacker successfully attacks your application, having it running as a user with restricted privileges will make it harder for the attacker to take over the host and/or to bounce to other services. Privileged users are root on Unix systems, and Administrator or System on Windows systems.

### [ ] Monitor your dependencies `[Seed]`

Applications are built using dozens of third party libraries. A single flaw in any of these libraries may put your entire application at risk. Some tools allow you to monitor your dependencies against vulnerabilities: https://www.sqreen.io/ https://appcanary.com/ https://snyk.io/ https://gemnasium.com/

### [ ] Use a real-time protection service `[Series A]`

These tools protect web applications from attacks at runtime. The protection logic is inserted into applications. They protect against all major vulnerabilities (SQL injections, XSS attacks, account takeovers, code injections, etc.) without false positives. https://www.sqreen.io/ http://www8.hp.com/us/en/software-solutions/appdefender-application-self-protection/

### [ ] Hire an external penetration testing team `[Post-Series A]`

These take an external and naive point of view of your infrastructure and products. Pentesters will take nothing for granted and will check even the most basic assumptions, as well as all of your infrastructure. You can also ask them to start with a full, blind discovery of your infrastructure, which can help you remember about old assets. Read More: http://www.zdnet.com/article/10-things-you-need-to-know-before-hiring-penetration-testers/


## Your product users

### [ ] Enforce a password policy `[Seed]`

Your user accounts will be much harder to steal if you require them to use complex passwords: mixed case, special characters, minimum length, etc.

### [ ] Encourage your users to use 2FA `[Series A]`

As you get higher profile customers, you will be required to implement stronger security practices. This includes offering them 2-factor authentication, role-based account management, etc. Read More: https://auth0.com/ https://stormpath.com/

### [ ] Monitor your users’ suspicious activities `[Series A]`

Some users may behave suspiciously, trying to hack into your application, subvert your services, or bother your other customers. By monitoring such users, you will be able to block or flag the illegitimate ones. Great tools: https://www.sqreen.io https://castle.io

