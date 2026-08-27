Computer-Security/
│
├── README.md
│
├── 01-Computer-Security-Overview.md
├── 02-Security-Elements-CIA-Triad.md
├── 03-Security-Terminologies.md
├── 04-Security-Layers.md
├── 05-Securing-Operating-System.md
├── 06-Antivirus.md
├── 07-Malware.md
├── 08-Encryption.md
├── 09-Data-Backup.md
├── 10-Disaster-Recovery.md
├── 11-Network-Security.md
├── 12-Security-Policies.md
├── 13-Security-Checklist.md
└── 14-Legal-Compliance.md
01 — Computer Security Overview
Important topics
What is Computer Security?
Why Computer Security is needed
Importance of information security
Security threats
Cyberattacks
Security goals
Security controls
People, Processes, Technology
Basic security architecture
Most important
Computer Security
       ↓
Protect
       ↓
Data + Systems + Networks + Users
02 — Security Elements / CIA Triad 

This is one of the most important topics.
Confidentiality
Integrity
Availability
CIA Triad
Authentication
Authorization
Accountability
Non-repudiation
Remember
Confidentiality → Who can SEE?
Integrity       → Who can CHANGE?
Availability    → Can I ACCESS?

03 — Security Terminologies 

You should know these terms very clearly.

Important topics
Asset
Threat
Vulnerability
Attack
Risk
Exploit
Exposure
Security control
Authentication
Authorization
Identification
Incident
Breach
Attack surface
Most important relationship
Threat
   ↓
Vulnerability
   ↓
Exploit / Attack
   ↓
Risk
   ↓
Damage

04 — Security Layers 
Important topics
Physical Security
Network Security
Operating System Security
Application Security
Data Security
User Security
Defense in Depth
Least Privilege
Basic model
Physical
   ↓
Network
   ↓
Operating System
   ↓
Application
   ↓
Data
   ↓
User

05 — Securing Operating System 
Important topics
OS security
Security updates
Security patches
User accounts
Password security
User permissions
Least privilege
File permissions
Firewall
Secure configuration
System logs
System monitoring
Disable unnecessary services
Secure Windows
Secure Linux
Important concept
Update
   +
Strong Authentication
   +
Least Privilege
   +
Firewall
   +
Monitoring
   
Better OS Security

06 — Antivirus
Important topics
What is Antivirus?
How antivirus works
Malware detection
Signature-based detection
Heuristic detection
Behavioral detection
Real-time protection
Quarantine
Malware removal
Antivirus limitations
Basic process
File
 ↓
Scan
 ↓
Safe? ── YES → Allow
 ↓
 NO
 ↓
Block / Quarantine

07 — Malware 

Important malware types
Virus
Worm
Trojan
Ransomware
Spyware
Adware
Rootkit
Bot/Botnet
Keylogger
Understand the differences
Malware	Main characteristic
Virus	Infects files/programs
Worm	Spreads between systems
Trojan	Pretends to be legitimate software
Ransomware	Makes data/systems inaccessible and demands payment
Spyware	Secretly monitors/collects information
Adware	Displays unwanted advertisements
Rootkit	Hides malicious activity/access
Keylogger	Records keystrokes

08 — Encryption 
Very important for network and cybersecurity.
What is encryption?
Plaintext
Ciphertext
Encryption
Decryption
Cryptographic keys
Symmetric encryption
Asymmetric encryption
AES
RSA
ECC
Hashing
Digital signatures
Certificates
TLS/HTTPS
Basic flow
Plaintext
    ↓
Encryption + Key
    ↓
Ciphertext
    ↓
Decryption + Key
    ↓
Plaintext
Remember
Encryption → Protect confidentiality

Hashing → Integrity / password-related applications

Digital Signature → Authenticity + Integrity + Non-repudiation

09 — Data Backup 
Important topics
What is backup?
Why backup is required
Full backup
Incremental backup
Differential backup
Local backup
Off-site backup
Cloud backup
Offline backup
Backup testing
Backup security
3-2-1 backup strategy
Important
Original Data
     ↓
Backup
     ↓
Data Loss
     ↓
Restore
     ↓
Data Recovered

10 — Disaster Recovery 
Important topics
What is Disaster Recovery?
Disaster Recovery Plan (DRP)
Business Continuity
RTO
RPO
Recovery strategies
Backup and restoration
Failover
Redundancy
Disaster recovery testing
Recovery site concepts
Very important

RTO = How quickly should we recover?

RPO = How much data loss can we tolerate?

Disaster
   ↓
Detection
   ↓
Response
   ↓
Recovery
   ↓
Restore Systems
   ↓
Resume Operations

11 — Network Security 
This is one of the biggest topics.
What is Network Security?
Network threats
Firewall
VPN
IDS
IPS
Network segmentation
Authentication
Access control
Secure protocols
HTTPS
TLS
Network monitoring
Wi-Fi security
DDoS
DNS security
Zero Trust basics
Basic architecture
Internet
   ↓
Firewall
   ↓
Router
   ↓
Switch
   ↓
Network
   ↓
Servers / Computers
Important difference
Firewall → Controls traffic

IDS → Detects suspicious activity

IPS → Detects + can block activity

VPN → Creates protected communication channel

12 — Security Policies 
Important topics
What is a security policy?
Password Policy
Access Control Policy
Acceptable Use Policy
Data Protection Policy
Backup Policy
Incident Response Policy
Remote Access Policy
Network Security Policy
Security Awareness Policy
Policy enforcement
Policy review
Example
Security Policy
       ↓
Rules
       ↓
Employees
       ↓
Secure behavior
       ↓
Reduced risk

13 — Security Checklist
This is the practical implementation section.
OS updated
Applications updated
Strong passwords
MFA enabled
Firewall enabled
Antivirus/endpoint protection active
Backups available
Backups tested
Least privilege applied
Unused accounts disabled
Unnecessary software removed
Sensitive data protected
Logs monitored
Security incidents reported
Disaster recovery plan tested
Employees trained
Simple checklist
[ ] OS Updated
[ ] Applications Updated
[ ] Strong Password
[ ] MFA Enabled
[ ] Firewall Enabled
[ ] Antivirus Active
[ ] Backup Available
[ ] Backup Tested
[ ] Least Privilege
[ ] Logs Monitored
[ ] DR Plan Tested

14 — Legal Compliance 
Important topics
What is Legal Compliance?
Privacy
Data protection
Personal data
Data retention
Access control requirements
Security requirements
Audit
Incident reporting
Breach notification
Regulatory requirements
Organizational policies
Industry standards
Important distinction
Security
   ↓
Protect systems and information

Compliance
   ↓
Meet applicable laws,
regulations, contracts,
and requirements
⭐ Priority for Learning

If your goal is to become strong in Computer Security, don't give equal time to every topic.

🔴 Must Know
1. Computer Security Basics
2. CIA Triad
3. Threats / Vulnerabilities / Attacks / Risk
4. Security Layers
5. OS Security
6. Malware
7. Encryption
8. Network Security
9. Backup
10. Disaster Recovery
🟡 Should Know
11. Antivirus
12. Security Policies
13. Security Checklist
14. Legal Compliance
🎯 Interview Priority

For interviews, I would especially prepare these:

CIA Triad
   ↓
Authentication vs Authorization
   ↓
Threat vs Vulnerability vs Risk
   ↓
Virus vs Worm vs Trojan
   ↓
Ransomware
   ↓
Encryption
   ↓
Symmetric vs Asymmetric Encryption
   ↓
Hashing
   ↓
Firewall
   ↓
IDS vs IPS
   ↓
VPN
   ↓
Backup
   ↓
RTO vs RPO
   ↓
Defense in Depth
   ↓
Least Privilege
