 # MCSA

## This repository contains my personal study notes, handwritten documentation, and concept-oriented summaries from the MCSA course. It is not intended to replace the official course material, but rather to provide concise explanations and structured notes that can help others review Windows Server, Active Directory, networking, authentication, and enterprise infrastructure concepts more efficiently.


MCSA (Concept-Based Roadmap)
1. Windows Server Fundamentals
Topics
Windows Server Editions
Server Roles & Features
Server Manager
Core vs Desktop Experience
Windows Architecture
Windows Services
Boot Process
Windows File System (NTFS/ReFS)
Volumes & Partitions
Storage Concepts
2. Active Directory Domain Services (AD DS)
Active Directory Basics
What is Active Directory
Why Active Directory Exists
Authentication vs Authorization
Domain
Tree
Forest
Trust
Site
Global Catalog
Schema
FSMO Roles
Replication
LDAP
Kerberos
DNS Dependency
Domain Controllers
What is DC
Writable DC
Read Only Domain Controller (RODC)
SYSVOL
NTDS.dit
NETLOGON
Replication Mechanism
Active Directory Objects
Users
Groups
Computers
Organizational Units (OU)
Contacts
Shared Folders
Printers
Group Types
Security Groups
Distribution Groups
Domain Local
Global
Universal
Group Nesting
Group Policy (GPO)
What is GPO
Local Policy
Domain Policy
Processing Order (LSDOU)
Loopback Processing
Administrative Templates
Security Policies
GPO Inheritance
Enforced
Block Inheritance
WMI Filter
GPO Replication
AD Security
SID
RID
ACL
DACL
SACL
Access Token
Privileges
Permissions
Inheritance
3. DNS
Fundamentals
Why DNS Exists
Name Resolution
Recursive Query
Iterative Query
Root Servers
Forward Lookup
Reverse Lookup
DNS Records
A
AAAA
PTR
NS
SOA
MX
TXT
CNAME
SRV
DNS Zones
Primary
Secondary
Stub
Active Directory Integrated
DNS Replication
Zone Transfer
Dynamic DNS
Secure Dynamic Update
Aging & Scavenging
4. DHCP
Why DHCP Exists
DORA Process
Scope
Reservation
Exclusion
Lease
DHCP Options
Relay Agent
Failover
5. Networking
TCP/IP
IPv4
IPv6
Subnetting (Concept)
Gateway
Routing
NAT
VLAN
ARP
ICMP
Network Services
DNS
DHCP
NTP
SMB
RPC
LDAP
Kerberos
WinRM
6. File Server
NTFS Permissions
Share Permissions
Effective Permissions
Access Based Enumeration
Shadow Copy
Offline Files
DFS Namespace
DFS Replication
Quota
FSRM
7. Storage
Basic Disk
Dynamic Disk
RAID Concepts
Storage Spaces
Deduplication
iSCSI
8. Hyper-V
Hypervisor
Virtual Machine
Virtual Switch
Generation 1 vs Generation 2
Checkpoints
Dynamic Memory
Live Migration (Concept)
Virtual Hard Disk (VHD/VHDX)
9. Windows Security
Windows Firewall
Windows Defender
Credential Guard
Device Guard
BitLocker
Secure Boot
UAC
LAPS
Windows Hello for Business
10. Identity & Authentication
NTLM
Kerberos
Ticket Structure
TGT
TGS
SPN
PAC
Delegation
Constrained Delegation
Authentication Flow
11. Certificate Services (PKI)
PKI
CA
Certificate
CSR
CRL
OCSP
Root CA
Intermediate CA
Auto Enrollment
12. Windows Update Services
WSUS
Update Approval
Target Groups
Patch Management
13. Windows Server Administration
MMC
Event Viewer
Task Scheduler
Services.msc
Registry
PowerShell Basics
Remote Management
WinRM
14. Backup & Recovery
Windows Backup
Bare Metal Recovery
System State Backup
Volume Shadow Copy
Restore Process
15. Monitoring
Performance Monitor
Resource Monitor
Reliability Monitor
Event Viewer
Windows Logs
Audit Policy
16. Active Directory Security (Blue Team View)

این بخش از خود MCSA مهم‌تر است.

Kerberos Attack Surface
NTLM Weaknesses
Pass The Hash
Pass The Ticket
Golden Ticket
Silver Ticket
DCSync
DCShadow
Skeleton Key
AdminSDHolder
SID History
Kerberoasting
AS-REP Roasting
GPP Password
LAPS
LDAP Signing
SMB Signing
Credential Guard
17. Active Directory Hardening
Tiering
Least Privilege
Privileged Access Workstations
Protected Users
Authentication Policies
MFA
Secure Admin Model
Attack Surface Reduction
اگر فقط Concept بخوانی، این موارد را حذف کن

نیازی نیست زمان زیادی روی این‌ها بگذاری:

نصب Windows Server
Wizardهای AD DS
PowerShell Deployment
Hyper-V Configuration
Storage Configuration
Cluster Configuration
NIC Teaming
Failover Cluster Installation
Windows Deployment Services (WDS)
MDT
Nano Server
Containers
اولویت مطالعه برای یک SOC Manager / Blue Teamer

اگر هدفت تقویت دانش برای SOC، Threat Hunting و Incident Response است، ترتیب مطالعه را این‌گونه پیشنهاد می‌کنم:

Active Directory (کامل)
Kerberos & NTLM
Group Policy
DNS
LDAP
Windows Authentication
File Permissions (ACL, DACL, SACL)
Windows Event Logs
PKI
DHCP
Hyper-V (مفهومی)
Storage (مفهومی)

با این رویکرد، به‌جای حفظ کردن مراحل نصب و تنظیمات، روی درک عمیق معماری ویندوز سرور و اکتیودایرکتوری تمرکز می‌کنی؛ دانشی که برای مصاحبه‌های SOC، تحلیل حملات مبتنی بر Active Directory و مباحثی مثل FOR500، SEC504 و Threat Hunting بیشترین ارزش را دارد.
