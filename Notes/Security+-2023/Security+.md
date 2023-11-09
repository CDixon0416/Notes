# Condensed Notes from ProfessorMesser's Video Series on CompTIA's Security+
#### Sourced from: https://www.professormesser.com/security-plus/sy0-601/sy0-601-video/sy0-601-comptia-security-plus-course/

## Section 0: The SY0-601 CompTIA Security+ Exam
   1. "0.1: Introduction"
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

## Section 1: Attacks, Threats, and Vulnerabilities
   1. "1.1: Social Engineering"
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
             - Commonly used to commit identity fraud: i.e. Credit card fraud, Bank Fraud, Loan Fraud, Government benefits
fraud   
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
   
   2. "1.2: Attack Types"
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

      - Rootkits

      - Spyware

      - Bots and Botnets
         - Automation of system by malware
         - Installed via Trojan Horse
         - Multiple bots make up a botnet
         - Controlled via a C&C server which sends out commands
         - Can be used for DDOS, Spam, Network Traffic, and other tasks
      - Logic Bombs

      - Password Attacks

      - Physical Attacks

      - Adversarial Artiifical Intelligence

      - Supply Chain Attacks

      - Cloud-based vs On-Prem Attacks

      - Cryptographic Attacks
          - How do you guarantee that data you've sent is secure?
             - Without the key the attackers look for exploits/vulnerability/bad configuration in cryptography itself
          - Hash Collision
             - When two types of plaintexts generate the same hash values
             - Hashes are supposed to unique for every unique plaintext
          - Downgrade Attack
             - A form of MITM where you degrade the type of encryption between two hosts to a less secure form that can be easier to break such as MD5
             
    3. "1.3: Application Attacks"
    4. "1.4: Network Attacks"
    5. "1.5: Threat Actors and Vectors"
    6. "1.6: Vulnerabilities"
    7. "1.7: Security Assessments"
    8. "1.8: Penetration Testing"
## Section 2: Architecture and Design
    1. "2.1: Enterprise Security"
    2. "2.2: Virtualization and Cloud Computing"
    3. "2.3: Secure Application Development"
    4. "2.4: Authentication and Authorization"
    5. "2.5: Resilience"
    6. "2.6: Embedded Systems"
    7. "2.7: Physical Security Controls"
    8. "2.8: Cryptographic Concepts"
## Section 3: Implementation
    1. 3.1: Secure Protocols
    2. 3.2: Host and Application Security
    3. 3.3: Secure Network Designs
    4. 3.4: Wireless Security
    5. 3.5: Mobile Security
    6. 3.6: Cloud Security
    7. 3.7: Identity and Account Management
    8. 3.8: Authentication and Authorization Services
    9. 3.9: Public Key Infrastructure
## Section 4: Operations and Incident Response
    1. 4.1: Security Tools
    2. 4.2: Incident Response
    3. 4.3: Investigations
    4. 4.4: Securing an Environment
    5. 4.5: Digital Forensics
## Section 5: Governance, Risk, and Compliance
    1. 5.1: Security Controls
    2. 5.2: Regulations, Standards, and Frameworks
    3. 5.3: Organizational Security Policies
    4. 5.4: Risk Management
    5. 5.5: Data Privacy
