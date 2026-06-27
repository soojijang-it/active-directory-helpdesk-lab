# Active Directory Helpdesk Lab


## Project Type
Enterprise Windows Infrastructure • Active Directory • IT Support • System Administration • Virtual Lab

---

## Project Summary
This project simulates a real-world enterprise Active Directory environment using Windows Server 2022 and Windows 11 Pro in a virtualized lab. It demonstrates core IT Support and System Administration workflows including domain deployment, identity management, Group Policy configuration, DNS setup, authentication, and troubleshooting.

---

## Key Highlights
- Built a complete Active Directory domain from scratch using Windows Server 2022  
- Deployed and configured Windows 11 Pro domain-joined client  
- Configured VirtualBox networking (host-only, static IP, DNS)  
- Installed and configured Active Directory Domain Services (AD DS)  
- Designed Organizational Units (OUs) and Role-Based Access Control (RBAC)  
- Managed domain users, security groups, and authentication  
- Configured NTFS + SMB file sharing permissions  
- Implemented and validated Group Policy Objects (GPOs)  
- Simulated Help Desk troubleshooting (password resets, access issues)  
- Verified environment using Active Directory Users and Computers (ADUC)  

---

## Environment

### Virtualization
- Oracle VirtualBox

### Domain Controller
- Windows Server 2022 (TECHCORP-DC1)
- Active Directory Domain Services (AD DS)
- DNS Server
- Group Policy Management Console (GPMC)

### Client
- Windows 11 Pro (Client1)
- Domain-joined workstation
- Active Directory authentication enabled

### Domain
- techcorp.local

### Network
- Host-only adapter
- Static IP on DC1
- DNS pointed to DC1
- AD-integrated name resolution

---

## Technologies Used
- Windows Server 2022  
- Windows 11 Pro  
- Active Directory Domain Services (AD DS)  
- DNS Server  
- Group Policy Management  
- NTFS Permissions  
- SMB File Sharing  
- Oracle VirtualBox  

---

## Skills Demonstrated
- Active Directory deployment & administration  
- Identity & Access Management (IAM)  
- Role-Based Access Control (RBAC)  
- Windows Server configuration  
- DNS configuration & troubleshooting  
- Group Policy design & enforcement  
- File sharing security (NTFS/SMB)  
- Domain join & authentication flow  
- Help Desk troubleshooting workflows  
- System validation (ADUC, gpresult, RSOP)  

---

## Implementation Breakdown

### Infrastructure Setup
- VM creation and configuration  
- Static IP and hostname setup  
- Network configuration (host-only)

### Active Directory Deployment
- AD DS installation  
- Domain promotion  
- OU structure design  
- User & group creation  
- Security group configuration  

### File Sharing & Permissions
- SMB share setup  
- NTFS permissions configuration  
- Access testing (allowed vs denied)

### Group Policy (GPO)
- Policy creation and linking  
- Enforcement testing  
- gpresult / RSOP validation  

### Client Integration
- Domain join process  
- Authentication verification  
- Policy application validation  

### Help Desk Simulation
- Password resets  
- Access troubleshooting  
- Permission correction  
- Login issues resolution  

---

## Troubleshooting Scenarios
- DNS misconfiguration causing domain join failure  
- Authentication failures  
- NTFS permission denial  
- GPO not applying correctly  
- Account lockouts and password resets  

---

## Learning Outcomes
- Enterprise Active Directory architecture understanding  
- Real-world Windows Server administration  
- Identity and access control management  
- Group Policy implementation  
- Secure file sharing configuration  
- End-to-end domain client lifecycle  
- IT Help Desk operational skills  

---

## Project Summary
This lab demonstrates a complete Active Directory environment lifecycle from infrastructure setup to enterprise-style administration and troubleshooting, replicating real IT support and system administration workflows.