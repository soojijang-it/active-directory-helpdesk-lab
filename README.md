# Active Directory Helpdesk Lab

## Project Type
Enterprise Windows Infrastructure • Active Directory • IT Support • System Administration • Virtual Lab

---

## Project Highlights
- Built a complete Active Directory domain environment from scratch using Windows Server 2022  
- Deployed and configured a Windows 11 Pro domain-joined client  
- Configured virtual infrastructure, host-only networking, static IP addressing, and DNS  
- Installed and configured Active Directory Domain Services (AD DS)  
- Designed Organizational Units (OUs) and implemented Role-Based Access Control (RBAC)  
- Created and managed domain users, security groups, and authentication  
- Configured NTFS and SMB file sharing permissions for secure access control  
- Implemented and validated Group Policy Objects (GPOs)  
- Simulated real-world Help Desk troubleshooting scenarios (password reset, access control)  
- Validated full Active Directory structure using ADUC  

---

## Overview
This project simulates a real-world enterprise Active Directory environment using Windows Server 2022 and Windows 11 Pro in a virtualized lab.

It demonstrates core IT Support and System Administration responsibilities including domain deployment, identity management, access control, Group Policy configuration, DNS setup, authentication, and troubleshooting.

The objective is to replicate enterprise IT workflows commonly used in corporate environments and Managed Service Provider (MSP) operations.

---

## Environment

### Virtualization Platform
- Oracle VirtualBox  

### Domain Controller
- Windows Server 2022 (TECHCORP-DC1)  
- Active Directory Domain Services (AD DS)  
- DNS Server  
- Group Policy Management  

### Client Machine
- Windows 11 Pro (Client1)  
- Domain-joined workstation  
- Active Directory authentication  

### Domain
- techcorp.local  

### Network Configuration
- Host-only virtual network  
- Static IP configured on DC1  
- Client configured to use DC1 as primary DNS  
- Domain resolution handled via AD DNS  

---

## Architecture Overview

### Domain Controller (DC1)
- Active Directory Domain Services  
- DNS Server  
- Group Policy Management  
- User and Group Management  
- File Sharing Services  

### Client Machine (Client1)
- Windows 11 domain-joined workstation  
- Active Directory authentication  
- Group Policy application  
- Access to domain resources  

---

## Technologies Used
- Windows Server 2022  
- Windows 11 Pro  
- Active Directory Domain Services (AD DS)  
- DNS Server  
- Group Policy Management Console (GPMC)  
- NTFS Permissions  
- SMB File Sharing  
- Oracle VirtualBox  

---

## Skills Demonstrated
- Active Directory domain deployment  
- Identity and Access Management (IAM)  
- Role-Based Access Control (RBAC)  
- Windows Server administration  
- DNS configuration and name resolution  
- Group Policy configuration and enforcement  
- File sharing and NTFS permissions  
- Domain join and authentication flow  
- Help Desk troubleshooting (access denied, password reset)  
- System validation using ADUC and gpresult / RSOP  

---

## Project Implementation

### Virtual Infrastructure Setup
- 01-ad-domain-controller-setup  
- 02-vm-dc1-settings  
- 03-vm-first-login  
- 04-vm-hostname-verification  
- 05-vm-static-ip-config  

### Active Directory Deployment
- 06-ad-prerequisites-check  
- 07-ad-ds-installation-success  
- 08-ad-ou-structure  
- 09-ad-security-groups  
- 10-ad-user-creation  

### File Sharing & Permissions
- 11-ad-file-share-ntfs-permissions  
- 12-ad-file-share-access-success  
- 13-ad-file-share-access-denied-test  

### Group Policy (GPO)
- 14-gpo-configuration  
- 15-gpresult-rsop-verification  

### Client Domain Integration
- 16-ad-client1-domain-settings  
- 17-client-domain-join  
- 18-client-login-verification  

### Validation & Help Desk
- 19-password-reset  
- 20-aduc-users-groups-review  

---

## Troubleshooting Scenarios
- Domain join failures and DNS misconfiguration  
- User authentication issues  
- Access denied errors due to NTFS permissions  
- Group Policy not applying (gpresult / RSOP validation)  
- Password reset and account reactivation  

---

## Screenshots
- VM and server configuration  
- Active Directory installation  
- OU and user creation  
- Security group configuration  
- File sharing permissions  
- Group Policy deployment  
- Client domain join process  
- Authentication verification  
- Help Desk troubleshooting scenarios  
- Final ADUC structure validation  

---

## Learning Outcomes
- Full understanding of Active Directory architecture  
- Practical Windows Server administration experience  
- Identity and access management skills  
- Group Policy deployment and troubleshooting  
- Enterprise file sharing security configuration  
- Domain client integration and authentication flow  
- Help Desk support simulation in enterprise environment  

---

## Project Summary
This project demonstrates a complete Active Directory lifecycle from infrastructure setup to final validation. It replicates enterprise IT and MSP environments, showcasing hands-on system administration, identity management, security enforcement, and Help Desk operations.