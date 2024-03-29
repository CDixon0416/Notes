# Condensed Notes from ProfessorMesser's Video Series on CompTIA's Security+
#### Sourced from: https://www.professormesser.com/security-plus/sy0-601/sy0-601-video/sy0-601-comptia-security-plus-course/
<details>
<summary> Section 0: The SY0-601 CompTIA Security+ Exam</summary>
   <details>
   <summary> "0.1: Introduction" </summary>
      
      - Security+ builds a great foundation
      - Professional prerequisite
      - Certifications that aren't vendor-specific

      - About this training course
          - Bite-Sized Videos
          - Quality Material with real world examples
          - Free course, notes and practice exams are paid

      - About the exam
          - 90 minutes, maximum of 90 questions
          - Passing Score: 750 on a scale from 100-900
          - 5 Domains, corresponds to the sections below
          - Section 1 24%
          - Section 2 21%
          - Section 3 25%
          - Section 4 16%
          - Section 5 14%
          - Use Objectives as a final checklist for Exam
          - Get plenty of sleep, plenty to eat, etc
          - Time Management is important
   </details>
</details>
<details open>
<summary> Section 1: Attacks, Threats, and Vulnerabilities </summary>
   <details>   
   <summary> "1.1: Social Engineering" </summary>
      
      - Phishing: Social Engineering with a touch of Spoofing
      - Often delivered by text, email, etc
      - Don't be fooled -> Check the URL
      - Look for obvious errors in the webpage

      - Tricks and Misdirection
         - Digital slight of hand
         - Typosquatting
         - Pretexting
            - Lying to get information
            - Creating false scenarios and time sensitive issues
      - Pharming
         - Redirection of legit website to a bogus site
            - Poisoned DNS or client vuln
         - Combine Pharming with Phishing
            - Pharming - Harvest large groups of people
            - Phising - Collect access credentials
         - Difficult for anti-malware software to stop
            - Everything appears legitimate to the user
      - Vishing - Voice Phishing
      - Smishing - SMS Phishing

      - Reconnaissance
         - Gather information on the victim
      - Background information
         - Lead generation sites
         - Corporate web site
         - Social media sites of employees (i.e LinkedIn)
      - Attacker builds a believable pretext
         - Where you work
         - Where you bank
         - Recent financial transactions
         - Family and friends
      - Spear Phising
         - Targeted phishing with inside information
         - May include "whaling" or hitting a high level person such as the CEO or CFO
        
      - Impersonation:
         - Attackers pretend to be someone they aren't 
         - Before the attack the trap is set, there is an actor and a story
            - Uses some of the details from their reconnaissance
            - Can include attacking the victim by masquerading as someone who outranks them
            - Commonly used to commit identity fraud: i.e. Credit card fraud, Bank Fraud, Loan Fraud, Government benefits fraud   
         - Protection against impersonation
            - Never volunteer information
            - Don't disclose personal details
            - Always verify before revealing info
            - Verification should be encouraged
        
      - Dumpster Diving:
         - Important information thrown out with the trash
         - Prevent attackers from getting useful information by shredding important documents and secure your garbage location
      
      - Shoulder Surfing:
         - You have access to important information
         - Prevent attackers by using privacy filters and keeping your monitor out of potential lines of sight
        
      - Hoaxes:
         - A threat that doesn't actually exist
         - Still often consume lots of resources
         - Most protection is as simple as ensuring you're spam filter is enabled
         - When in doubt look online at sites such as hoaxslayer.net and snopes.com to see if this is a common hoax
        
      - Watering Hole Attacks:
         - What if your network was really secure? Bring the victim to you.
         - Attack the metaphorical watering hole where the target is likely to be and try to compromise them via a third party to indirectly attack their network
            - Determine which website the victim group uses
            - Infect one of these third-party sites
            - Infect all visitors and hope your target is one of them
         - Prevention
            - Defense in depth
            - Firewalls and IPS
            - Anti-virus/malware signature updates
        
        - Spam:
           - Unsolicited messages
           - Various content
           - Significant technology issue
              - Security concerns
              - Resource utilization
              - Storages costs
           - Prevention
              - Spam filter
                 - allowed list
                 - SMTP standards checking
                 - Reverse DNS lookup
                 - Tarpitting
                 - Recipient filtering
        
        - Influence Campaigns:
           - Sway public opinion on political and social issues
           - Typically a nation-state actor
              - Includes targeted advertising
              - Enabled through social media
        
        - Other Social Engineering Attacks:
           - Tailgating
           - Invoice Scams
           - Credential Harvesting 
        
        - Principles of Social Engineering:
           - Constantly changing, you never know what they'll use next
              - May involve multiple people or organization
              - May be in person or electronic including automation
           - Principles
              - Authority
              - Intimidation
              - Consensus or Social Proof
              - Scarcity
              - Urgency
              - Familiarity or Liking
              - Trust
   </details>
   <details>
   <summary> "1.2: Attack Types" </summary>
        
      - Malware
           - Malicious Software
           - Gather information
           - Participate in a group (think botnet)
           - Show you advertising (adware)
           - Viruses and Worms (such as ransomware)
        - How you get malware
           - Possible scenario:
              - A worm takes advantage of a vulnerability
              - That worm then installs malware that includes a Rootkit
              - That root kit may install a bot, and now your device is part of a botnet
        - Your computer must run a program
           - Don't click links in email from untrusted sources
           - Web page pop-up
           - Drive-by download
           - Worm
           - Keep your OS and Application patched
            
      - Viruses and Worms
         - Viruses
            - Malware that can reproduce itself
            - Reproduces through file systems or the network
            - May or may not cause problems (adware vs ransomware)
            - Prevent/Cure with Anti-virus signatures staying up to date
         - Types of Viruses
            - Program Viruses
               - Part of the application
            - Boot Sector Viruses
               - Part of the bootloader
            - Script Viruses
               - OS and Browser based
            - Macro Viruses
               - Application based such as MS Office
            - Fileless Viruses
               - Stealth attack that operates entirely in memory
         - Worms
            - Malware that self replicates without user intervention
      
      - Ransomware and Crypto-malware
         - Ransomware
            - Malware that typically encrypts a device and requires a ransom to get the data back
            - Evolved from HOAXes into real attacks using crypto-malware
         - Crypto-Malware
            - Malware that uses cryptography to be able to encrypt all of your personal information for a ransom

      - Trojans and RATs
         - Trojans
            - Malware that masquerades as a legitimate program or file
         - RAT
            - Remote Access Trojan or Remote Administration Tool

      - Rootkits
         - Can be present in any OS
         - Normally modifies the kernel of the OS not the filesystem of the OS
           
      - Spyware
         - More malicious than adware
         - Used to spy on the user to gain information about them or their habits

      - Bots and Botnets
         - Automation of system by malware
         - Installed via Trojan Horse
         - Multiple bots make up a botnet
         - Controlled via a C&C server which sends out commands
         - Can be used for DDOS, Spam, Network Traffic, and other tasks

      - Logic Bombs
         - A type of attack that occurs when a seperate event is triggered
         - Commonly left by disgruntled employees

      - Password Attacks
         - Plaintext/unencrypted passwords
         - Hashing a password
            - Only works one way and can't be reversed
         - Spraying attack
            - Try to use common passwords for every account
         - Brute Force
            - Try every possible password combination until a hash is matched
         - Offline Attack
            - Brute force but offline, by copying the password hashes
         - Dictionary Attack
            - Use a dictionary to find common words
            - More targeted brute force using plain english words as the guess
         - Rainbow Tables
            - An optimized, pre-built set of hashes
         - Salting the hash
            - Random data added to a password when hashing
            - Every user gets their own random salt

      - Physical Attacks
         - Malicious USB Cable
         - Malicious Flash Drive
         - Skimming
         - Card Cloning

      - Adversarial Artiifical Intelligence
         - Using malicious or invalid data to poison a training set for the AI

      - Supply Chain Attacks
         - An attack that focuses on the third party technology a company uses to infect them from a trusted source/vendor
          
      - Cloud-based vs On-Prem Attacks
          - More flexability vs more control
          - Higher cost vs Higher Risk
          - Cloud-based can rely on security and IT services from the cloud provider
          - On-Prem solutions can be more narrow and focused for your business
          
      - Cryptographic Attacks
          - How do you guarantee that data you've sent is secure?
             - Without the key the attackers look for exploits/vulnerability/bad configuration in cryptography itself
          - Hash Collision
             - When two types of plaintexts generate the same hash values
             - Hashes are supposed to unique for every unique plaintext
          - Downgrade Attack
             - A form of MITM where you degrade the type of encryption between two hosts to a less secure form that can be easier to break such as MD5
   </details>
   <details open>
   <summary> "1.3: Application Attacks" </summary>
      TODO
   </details>
   <details open>
   <summary> "1.4: Network Attacks" </summary>
      TODO
   </details>
   <details>
   <summary> "1.5: Threat Actors and Vectors" </summary>
       
      - Threat Actors
          - An entity responsible for an event that has an impact on the safety of another entity
          - APT
             - Advanced Persistent Threat
          - Insiders
             - Normally not a professional hacker but has institutional knowledge
          - Nation States
             - Governments
             - National Security
             - Highest Sophistication
             - Constant attacks, massive resources
          - Hacktivist
             - A hacker with a purpose
             - Normally a social change or political agenda
             - Very specific
             - Limited funding
          - Script Kiddies
             - Runs pre-made scripts without any knowledge of what's happening
             - Not very sophisticated
             - Lacks formal funding
             - Motivated by the hunt
          - Organized Crime
             - Professional Criminals
             - Very Sophisticated (Best money can buy)
             - More organized and may look like a normal company
          - Hackers
             - Experts with technology
             - Authorized vs Unauthorized
          - Shadow IT
             - Going around the internal IT organization
             - IT can put up roadblocks
             - Not always a good thing
          - Competitors
             - High level of sophistication
             - DoS, Espionage, Harm Reputation
       
       - Attack Vectors
          - Method used by an attacker
          - Direct access attack vectors
             - Modify OS
             - Attach a keylogger
             - Transfer Files
             - Denial of service
          - Wireless attack vectors
             - Default login credentials
             - Rogue access points
             - Evil twin (MitM access point)
             - Protocol Vulnerabilities
          - Email attack vectors
             - One of biggest and most successful attack vectors
             - Phising Attacks
             - Deliver Malware to end user
             - Social Engineering Attacks
          - Supply chain attack vectors
             - Tamper with the underlying infrastructure
             - Gain access to a network using a vendor
             - Modify the manufacturing process
             - Counterfeit networking equipment
          - Social media attack vectors
             - User profiling
             - Fake Friends
          - Removable Media attack vectors
             - Get around firewall
             - Malicious USB
             - Data exfiltration
          - Cloud attack vectors
             - Public facing
             - Security misconfigurations
             - Brute Force attacks
             - Orchestration attacks
             - Denial of Service  
       
       - Threat Intelligence
          - Research the threats
          - Data is everywhere
          - OSINT
             - Internet
             - Government data
             - Commercial data
          - Closed/proprietary intelligence
             - Threat intelligence services
             - Threat analytics
             - Constant threat monitoring
          - Vulnerability Databases
             - Public research
             - CVE (Common Vulnerabilities and Exposures)
                - Sponsored by DHS and CISA
                - Provides severity scoring and patching information
          - Automated indicator sharing (AIS)
             - Structured Threat Information eXpression (STIX)
             - Trusted Automated eXchanged of Indicator Information (TAXII)
          - Indicators of compromise
             - An event that indicates an intrusion
             - Indicators
                - Unusual amount of network activity
                - Change to file hash values
                - Irregular international traffic
                - Changes to DNS data
                - Uncommon login patterns
          - Predictive analysis
             - Find suspicious patterns
             - Big data but for cybersecurity
             - Identify behaviors
             - Create a forecast for potential attacks
             - Often combined with machine learning
               
       - Threat Research
          - Know your enemy
          - Continuing education
          - Vendor Websites
             - Involved in the disclosure process
          - Vulnerability feeds
          - Conferences
          - Academic Journals
          - RFCs
          - Local industry groups
          - Social Media
          - Threat Feeds
   </details>
   <details>
   <summary> "1.6: Vulnerabilities" </summary>
       
      - Vulnerability Types
          - Zero-day attacks
             - Vulnerability that has not been detected or published
             - Attackers keep these yet-to-be-discovered vulns to themselves
          - Open Permissions
             - Data without a security component and anyone can read it
             - Increasingly common with cloud storage
          - Unsecured Root Accounts
             - Can be a misconfiguration
             - Easy to hack password
             - Disable direct login to root
          - Weak Encryption
             - TLS is one of the most common issues
          - Insecure protocols
             - Verify with a packet capture
          - Default settings
             - Mirai botnet
          - Open ports and services
             - Often managed with a firewall
             - Easy to misconfigure
          - Improper Patch Management
          - Legacy Systems
            
       - Third-party Risks
          - IT Security doesn't change because it's a third-party
          - Human error is stil the biggest issue
          - System integration risk
             - Can be on-site
             - Can include elevated OS access
             - Can run software on the internal network
             - Lack of vendor support
                - Security requires diligence
                - Vendors are the only ones who can fix their products
          - Supply chain risk
             - You can't always control security at a third-party
             - Always maintain local security controls
             - Hardware and Software from a vendor can contain malware
             - Outsourced code development
                - Development systems should be isolated
                - Test code security
             - Data Storage
                - Consider the type of data
                - Storage at a third-party may need encryption
                  
       - Vulnerability Impacts
          - Data loss
          - Identity Theft
          - Financial loss
          - Reputation Impacts
          - Availability loss
   </details>
   <details>
   <summary> "1.7: Security Assessments" </summary>
       
      - Threat Hunting
          - Find the attacker before they find you
          - Strategies are constantly changing
          - Intelligence fusion
             - Too much data to properly detect, analyze, and react
          - Fusing the data
             - Collect the data
             - Add external sources
             - Correlate with big data analytics
          - Cybersecurity maneuvers
             - Modify firewalls, OS, and networks based on analysis
             - Mostly automated once setup correctly
             - "Tomorrow it's a different fight"
      
       - Vulnerability Scans
          - Usually minimally invasive
          - Unlike a penetration test
          - Port Scan
             - Send traffic and see what ports are open
          - Identify systems
          - Test from outside and inside
          - Scan Types
             - Non-intrusive scans
                - Gather info, does not exploit a vulnerability
             - Intrusive scans
                - Test the vulnerability yourself
             - Non-credentialed vs credentialed scan
             - Application scans
             - Web Application scans
             - Network Scans
       
       - Security Information and Event Management
          - SIEM
             - Log collection of security alerts
             - Log aggregation and long-term storage
             - Data Correlation
             - Forensic analysis
          - Syslog
             - Standard for message logging
             - Lots of storage needed
          - SIEM Data
             - Data Inputs
                - Server auth attempts
                - VPN connections
                - Firewall logs
                - Denied outbound traffic
                - Network utilizations
             - Packet Captures
          - Security Monitoring
             - Constant information flow
             - Track important statistics
             - Send alerts
          - SOAR
             - Security orchestration, automation, and response
             - Orchestration
                - Connect many tools together
             - Automation
             - Respone   
   </details>
   <details>
   <summary> "1.8: Penetration Testing" </summary>
       
      - Penetration Testing
          - Pentest
             - Simulate an attack
             - Similar to vuln scanning but trys to actually exploit a vulnerability
             - Often a compliance mandate
             - See NIST 800-115
         - Rules of engagement
            - Defines purpose and scope
            - More importantly it makes everyone aware of the test parameters
            - Types of testing and schedule
            - IP address ranges, emergency contacts, sensitive information handling
         - How much do you know about the test?
            - Blind test
               - Tester knows nothing about the systems
            - Known environment
               - Full disclosure
            - Partially known
               - Mix of the previous two
         - Exploiting Vulnerabilites
               - Try to break into the system
               - May try multiple techniques, similiar to a real threat actor
               - Process
                  - Initial Exploitation
                  - Lateral Movement
                  - Persistence
                  - Clean up (Be responsible return system to starting state)
      
      - Reconnaissance
         - Need information before the attack
         - Gather a digital footprint
         - Understand the security posture
         - Minimize the attack area and focus on key systems
         - Create a network map
         - Passive footprinting
            - Learn as much as you can from open sources
            - Social media
            - Corporate site
            - Online forums
            - Social Engineering
            - Dumpster diving
         - OSINT
            - Open source intelligence
            - Date is everywhere osintframework.com
            - Automated gathering tools
         - Wardriving/warflying
            - Combine WiFi monitoring and a GPS
            - Search from your car or a drone
            - Huge amount of intel in a short period of time
            - Get information about security configurations or distance from you
            - Combine with free tools to find physical locations such as Kismit and inSSiDer
         - Active Footprinting
            - Send information into network or device to gain more information
            - Ping scans, port scans, analyze DNS
            - Can be seen by someone monitoring their network
         
      - Security Teams
         - Cybsersecurity involves many skills
         - Become an expert in your niche
         - Offensive Security Team (Red)
            - Ethical Hacking
         - Defensive Security Team (Blue)
            - Operational Security
            - Incident Response
            - Digital Forensics
         - Purple Team
            - Combined efforts between red and blue team
            - Cooperate instead of compete
         - White Team
            - Not on a side
            - Manages the interaction between the red and blue teams
            - Picture as a referee for security exercises
   </details>
</details>
<details open>
<summary> Section 2: Architecture and Design </summary>
   <details open>
   <summary> "2.1: Enterprise Security" </summary>
     
      TODO
      - Configuration Management
      - Protecting Data
      - Data Loss Prevention
      - Managing Security
      - Site Resilience
      - Honeypots and Deception
   </details>
   <details open>
   <summary> "2.2: Virtualization and Cloud Computing" </summary>
     
      TODO
      - Cloud Models
      - Edge and Fog Computing
      - Designing the Cloud
      - Infrastructure as Code
      - Virtualization Security
   </details>
   <details>
   <summary> "2.3: Secure Application Development" </summary>
      
      - Secure Deployments
      - Development to Production
         - How will you deploy it safely and reliably?
         - How will you test and deploy patches?
      - Sandboxing
         - Isolated testing environment
         - No connection to the real world or a production system
         - Helpful for incremental development
      - Building the application  
         - Development
         - Test
         - QA
         - Staging
         - Production
      - Secure baselines
         - All applications should use the baseline
         - Firewall settings, patch levels, os file versions
         - May require constant updates
         - Integrity checks to verify production matches baseline
        
      - Provisioning and Deprovisioning
         - Provisioning
            - Deploy an application
            - Application Software Security
            - Network Security
            - Security scans such as nessus
         - Scalability
            - Ability to increase the workload in a given infrastructure
         - Elasticity
            - Ability to increase or decrease available resources as the workload changes
         - Orchestration
            - Automate the provisiong and deprovisioning of applications
            - Servers,networks,switches,firewalls,policies
            - Can move around the world as needed
            - Security policies are part of orchestration
         - Deprovisioning
            - Dismantling and removing an application instance
            - Security deprovisioning is important
            - If the application is gone so is the access
            - Don't leave information out there

      - Secure Coding Techniques
         - A balance between time and quality
         - Vulnerabilities will eventually be found
         - Stored procedures
            - SQL Databases
            - Client requests can be complex
            - Stored procedures limit the clients interactions to approved parameters
         - Obfusacation
            - Take readable code and turn it into nonsense
            - Helps prevent the search for vulnerabilities
         - Code Reuse
            - Also can copy vulnerabilites
            - Dead code
            - All code is an opportunity for a security problem
         - Input Validation
            - Validate actual vs expected
            - Fuzzers will find what you missed
            - Server side validation
            - Client side validation
            - Use both, but at least server side
         - Memory Management
            - Never trust user input
            - Some built-in functions are insecure
         - Third-party libraries and SDKs
            - Extend the functionality of a programming language
            - Extensive testing is required
            - Balancing act between functionality and security
         - Data Exposure
            - How is the application handling the data?
            - Check all input and output processes for data exposure
         - Version Control
            - Track changes of the software releases
            - Useful for security
      
      - Software Diversity
         - Once you exploit one binary you can exploit them all
         - Alternative compiler paths would result in a different binary each time it's compiled
         - This would mean an attacker can't use the same exploit across the network

      - Automation and Scripting
         - Plan for change
         - Continuous monitoring
         - Configuration validation
         - Continuous Integration (CI)
            - Code is constantly written
            - Basic set of security checks during development
            - Large-scale security analysis during testing
         - Continuous Delivery (CD) 
            - Automate the testing process
         - Continuous Deployment
            - Automate the release process
  </details>
  <details open>
  <summary> "2.4: Authentication and Authorization" </summary>
     TODO
  </details>
  <details open>
  <summary> "2.5: Resilience" </summary>
     TODO
  </details>
  <details open>
  <summary> "2.6: Embedded Systems" </summary>
     TODO
  </details>
  <details open>
  <summary> "2.7: Physical Security Controls" </summary>
     TODO
  </details>
  <details open>
  <summary> "2.8: Cryptographic Concepts" </summary>
     TODO
  </details>
</details>
<details open>
<summary> Section 3: Implementation </summary>
  <details>
   <summary> "3.1: Secure Protocols" </summary>
     
     - Secure Protocols
        - Voice and Video
           - SRTP: Secure Real Time Transport Protocol
           - Adds security to RTP
           - Encryption, Authentication, Integrity and replay protection
        - Time Synchronization
           - Classic NTP has no security features
           - Makes it exploitable as an amplifier
           - NTPsec
           - Cleaned up code base for NTP
        - Email
           - S/MIME: Secure/Multipurpose Internet Mail Extensions
           - Public/Private key pair used for digitial signing
           - Secure POP and Secure IMAP
              - Can use SSL
           - SSL/TLS
              - For encrypted web mail
        - Web
           - SSL/TLS
           - Secure Sockets Layer / Transport Layer Security
           - HTTPS
        - IPsec
           - Internet protocol security
           - Security for Layer 3
           - Authentication Header (AH)
           - Encapsulation Security Payload (ESP)
        - File Transfer
           - FTPS: File over SSL
           - SFTP: File over SSH
        - LDAP
           - Lightweight Directory Access Protocol
           - Protocol for reading and writing directories over an IP network
           - LDAPS: LDAP over SSL
           - SASL: Simple Authentication and Security Layer
        - Remote Access
           - SSH
        - Domain Name Resolution
           - Same problem as NTP
           - DNSSec
           - Validate DNS responses
        - Routing and Switching
           - SSH
           - SNMPv3: Simple Network Management Protocol 3
              - Provides CIA Triad
           - HTTPS
        - Network Address Allocation
           - DHCP: Dynamic Host Configuration Protocol
           - Same issues as NTP, or DNS
           - Combined with active directory to authorize DHCP servers
        - Subscription services
           - Anti-virus, IPS, Firewall updates
           - Constant updates all using different methods
           - Check for encryption and integrity checks       
</details>
<details open>
<summary> 3.2: Host and Application Security </summary>
   TODO
</details>
<details open>
<summary> 3.3: Secure Network Designs </summary>
   TODO
</details>
<details>
<summary> 3.4: Wireless Security </summary>
      
      - Wireless Cryptography
         - An organization's wireless netowrk can contain confidential information
         - Authenticate the users before granting access
         - Ensure that all communication is confidential
         - Verify the integrity of all communication
         - Wireless encryption
            - All wireless computers are radio transmitters and receivers
            - Solution: Encrypt the data
            - Only people with the right key can transmit and listen
         - WPA2 and CCMP
            - Wi-fi protected access 2
            - CCMP block cipher mode
               - Data confidentiality with AES
               - Message integrity with CBC-MAC
         - WPA3
            - GCMP block cipher mode
               - Data confidentiality with AES
               - Message integrity with GMAC
         - WPA2 has a PSK brute-force problem
      - Wireless Authentication Methods
         - Gain access to a wireless network
         - Credentials
            - Shared password/pre-shared key (PSK)
            - Centralized authentication (802.1x)
         - Wireless security modes
            - Open System
               - No password
            - WPA3-Personal
               - WPA3 with a PSK
            - WPA3-Enterprise
               - WPA3 with 802.1X
            - Captive Portal
               - Web session based credentials
      - Wireless Authentication Protocols
         - Extensible Authentication Protocol (EAP)
            - Integrates with 802.1X
         - 802.1X
            - Port based Network Access Control
            - Used in conjunction with an access database (RADIUS, LDAP, TACACS+)
            - Supplicant - Client
            - Authenticator - Device that provides access
            - Authentication Server - Validates the client credentials
         - EAP-FAST
            - EAP Flexible Authentication via Secure Tunneling
            - Supplicant and AS mutually authenticate and negotiate a TLS tunnel
         - PEAP
            - Protected Extensible Authentication Protocol
            - Also encapsulates EAP in a TLS tunnel
            - AS uses a digital cert instead of a PAC
            - User can also authenticate with a GTC(Generic token card)
         - EAP-TLS
            - EAP Transport Layer Security
            - Requires digitial certificate on the AS and all other devices
            - Needs a Public Key Infrastructure (PKI)
         - EAP-TTLS
            - EAP Tunneled Transport Layer Security
            - Requires a digitial cert on the AS
            - Builds a TLS tunnel using this digitial cert
            - Use any authentication method inside the TLS tunnel
         - RADIUS Federation
            - Members of one organization canauthenticate to the network of another organization
            - Uses 802.1X as the authentication method
      - Installing Wireless Networks
         - Site Surveys
            - Determine existing wireless landscape
            - Identify existing access points you may not control all of them
            - Work around existing frequencies
            - Plan for ongoing site surveys
            - Heat maps
         - Wireless survey tools
            - Signal coverage
            - Potential interference
            - Built-in tools for AP
            - 3rd-party tools
            - Spectrum analyzer
         - Wireless packet analysis
            - Wireless networks are incredibly easy to monitor
            - You have to be quiet
            - Some network drivers won't capture wireless information
         - Channel selection and overlaps
            - Overlapping channels
               - Frequency conflicts
               - Automatic or manual configuration
         - Acess point placement
            - Minimal overlap, maximize coverage
            - Avoid interference
               - Microwaves
               - Building materials
               - Third party wireless networks
            - Signal Control
               - Place APs where the users are
               - Avoid excessive signal distance (i.e. outside the building)
         - Wireless infrastructure security
            - Wireless controllers
               - Centralized management of wireless access points
            - Securing wireless controllers
               - Use strong encryption with HTTPs
               - Automatic timeout
            - Securing access points
               - Use strong passwords
               - Update to the latest firmware
               
   </details>
   <details open>
   <summary> 3.5: Mobile Security </summary>
      TODO
   </details>
   <details open>
   <summary> 3.6: Cloud Security </summary>
      TODO
   </details>
   <details open>
   <summary> 3.7: Identity and Account Management </summary>
      TODO
   </details>
   <details open>
   <summary> 3.8: Authentication and Authorization Services </summary>
      TODO
   </details>
   <details open>
   <summary> 3.9: Public Key Infrastructure </summary>
      TODO
   </details>
</details>
<summary> Section 4: Operations and Incident Response </summary>
   <details open>
   <summary> 4.1: Security Tools </summary>
      TODO
   </details>
   <details open>
   <summary> 4.2: Incident Response </summary>
      TODO
   </details>
   <details open>
   <summary> 4.3: Investigations </summary>
      TODO
   </details>
   <details open>
   <summary> 4.4: Securing an Environment </summary>
      TODO
   </details>
   <details open>
   <summary> 4.5: Digital Forensics </summary>
      TODO
   </details>
</details>
<summary> Section 5: Governance, Risk, and Compliance </summary>
   <details>
   <summary> 5.1: Security Controls </summary>
      
      - Prevent security events, minimize the impact and limit the damage
      - Control Categories
         - Managerial Controls
            - Controls that address security design and implementation
            - Security policies, standard operating procedures
         - Operational Controls
            - Controls that are implemented by people
            - Security guards, awareness programs
         - Technical Controls
            - Controls implmented using systems
            - Firewalls, Operating systems controls
      - Control Types
         - Preventive
            - Prevents access, door lock or firewall
         - Detective
            - Identifies and records any intrusion attempt
         - Corrective
            - Mitigate any damage that occurs during a security event
         - Deterrent
            - May deter someone from an intrusion
         - Compensating
            - Doesn't prevent an attack, but compensates for the results of the attack
         - Physical     
   </details>
   <details open>
   <summary> 5.2: Regulations, Standards, and Frameworks </summary>
      TODO
   </details>
   <details open>
   <summary> 5.3: Organizational Security Policies </summary>
      TODO
   </details>
   <details open>
   <summary> 5.4: Risk Management </summary>
      TODO
   </details>
   <details>
   <summary> 5.5: Data Privacy </summary>
      
      - Privacy and Data Breaches
         - Data Lifecycle
            - Creation and Receipt
            - Distribution
            - Use
            - Maintenance
         - Consequences
            - Reputation Damage
            - Identity Theft
            - Fines
            - IP Theft
         - Discovery
            - Internal escalation process
            - External escalation process
            - Public disclosure
         - Privacy Impact Assessment (PIA)
            - Privacy risk needs to be identified in each initiative
            - Advantages
               - Fix privacy issues before they become a problem
               - Avoid data breach
               - Provides evidence of a focus on privacy
      - Data Classifications
         - Labeling sensitive data
            - Not all data has the same level of sensitivity
            - Different levels require different security and handling
         - Classifications
            - Proprietary
               - Data that is owned by an organization
            - PII
               - Personally Identifiable Information
            - PHI
               - Protected Health Information
            - Public/Unclassified
            - Private/Classified/Restricted
            - Sensitive
            - Confidential
            - Critical
      - Enhancing Privacy
         - Tokenization
            - Replace sensitive data with a non-sensitive placeholder
            - Common with credit card processing
            - Attacker capturing the card numbers can't use them later
         - Data minimization
            - Only collect and retain the necessary data
            - Included in many regulations
            - Internal data use should be limited
         - Data Masking
            - Hide some of the original data
            - Protects PII
            - May only be hidden from view by permissions
         - Anonymization
            - Make it impossible to identify individual data from a dataset
            - Hashing, masking, etc
            - Convert from detailed customer purchase data
         - Pseudoanonymization
            - Replace personal information with pseudonums
            - May be reversible for other processes
      - Data Roles and Responsibilities
         - High-level data relationships
         - Data owner
            - Accountable for specific data, often a senior officer
            - VP of Sales owns the customer relationship data
         - Data controller
            - Manages the purposes and means by which personal data is processed
         - Data processor
            - Processes data on behalf of the data controller
         - Data custodian
            - Responsible for data accuracy, privacy, and security
         - Data protection officer
            - Responsible for the organization's data privacy
   </details>
</details>
