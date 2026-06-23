# Active Directory Helpdesk Lab

## Overview
This project simulates a real-world corporate Active Directory environment using Windows Server. It demonstrates core IT Help Desk and System Administration tasks including domain setup, user and group management, organizational units, file sharing, group policy, access control, and policy enforcement validation.

---

## Purpose
To develop practical IT support and system administration skills in a controlled virtual environment, focusing on Active Directory operations, identity management, Group Policy implementation, and troubleshooting scenarios commonly found in enterprise environments.

---

## Skills Covered
- Active Directory Domain Services (AD DS)
- Domain Controller configuration
- User and Group Management
- Organizational Units (OU) design
- Security Groups and Role-Based Access Control (RBAC)
- NTFS and Share Permissions
- Group Policy Object (GPO) implementation
- Domain-joined client authentication
- DNS resolution in AD environment
- Help Desk troubleshooting (password reset, access denied resolution)
- Group Policy verification (gpresult / RSOP)

---

## Environment
- Windows Server (Domain Controller - DC1)
- Windows 10/11 Client VM (Client1)
- Active Directory Domain Services (AD DS)
- Domain: techcorp.local

---

## Lab Steps

### 1. Infrastructure Setup
- Installed Windows Server for Domain Controller (DC1)
- Installed Windows 10/11 Client machine (Client1)
- Configured Host-only networking between server and client

---

### 2. Active Directory Domain Services Setup
- Installed Active Directory Domain Services (AD DS)
- Promoted server to Domain Controller
- Created new forest and domain: `techcorp.local`

---

### 3. DNS & Network Configuration
- Configured static IP on DC1
- Set DNS on Client1 to DC1 IP (192.168.56.106)
- Verified name resolution and connectivity

---

### 4. Organizational Unit (OU) Structure
- Created departmental OUs (IT, HR, Finance)
- Structured AD for role-based administration

---

### 5. User and Group Management
- Created users (e.g. mike.wilson, finance users)
- Created security groups (IT, Finance, HR groups)
- Assigned users to correct groups and OUs

---

### 6. File Sharing & NTFS Permissions
- Created shared folder on DC1 (IT-Share)
- Configured NTFS + Share permissions
- Applied group-based access control

---

### 7. Client Domain Join & Login Verification
- Joined Client1 to domain (techcorp.local)
- Verified domain login using `whoami`

---

### 8. Access Control Testing
- Tested shared folder access from Client1
- Verified permission enforcement (allowed vs denied access)

---

### 9. Help Desk Simulation (Password Reset)
- Reset user password via ADUC
- Verified login with new credentials

---

### 10. Group Policy Object (GPO Configuration)
- Created GPO (Company Security Policy)
- Linked GPO to domain / OU
- Configured user-side policy settings

---

### 11. GPO Verification
- Verified policy application using:
  - `gpresult /r`
  - `gpresult /h report.html`
- Confirmed “Company Security Policy” applied

---

### 12. Access Denied Security Test
- Attempted restricted access from Client1
- Confirmed NTFS/GPO enforcement

---

### 13. Logon Script Implementation
- Configured logon script (`logon.bat`)
- Applied via GPO
- Verified execution on user login

---

### 14. Active Directory Structure Validation
- Verified OU structure in ADUC
- Confirmed users and groups placement in Finance/other OUs

---

### 15. GPO Policy Applied Proof
- Captured gpresult output showing:
  - User: mike.wilson
  - Applied Group Policy: Company Security Policy
- Confirmed final policy enforcement success

---

## Screenshots Overview

01. Domain Controller setup  
02. AD DS installation & promotion  
03. OU structure creation  
04. Security groups configured  
05. User and group creation  
06. File sharing & NTFS permissions  
07. GPO configuration  
08. Client domain join  
09. Client login verification  
10. GPO result verification  
11. Access control testing  
12. Access denied test  
13. Password reset (Help Desk task)  
14. ADUC structure view  
15. gpresult / RSOP policy applied proof  

---

## Project Summary
This lab demonstrates a complete Active Directory enterprise environment including domain setup, identity management, access control, Group Policy enforcement, and troubleshooting validation using real-world IT help desk scenarios.

---

## Key Outcomes
- Built full Windows Server domain environment
- Designed OU structure for enterprise organization
- Implemented user/group-based security model
- Configured file sharing with NTFS permissions
- Applied and verified Group Policy Objects
- Performed real-world help desk tasks (reset, access control)
- Validated policy enforcement using gpresult / RSOP