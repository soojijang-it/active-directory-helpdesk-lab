# Active Directory Helpdesk Lab

## Overview
This project simulates a real-world corporate Active Directory environment using Windows Server. It demonstrates core IT Help Desk and System Administration tasks including domain setup, user and group management, organizational units, file sharing, group policy, and access control enforcement.

---

## Purpose
To develop practical IT support and system administration skills in a controlled virtual environment, focusing on Active Directory operations, identity management, and troubleshooting scenarios commonly found in enterprise environments.

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
- Help Desk troubleshooting (password reset, access denied resolution)

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
- Configured network connectivity between server and client

---

### 2. Active Directory Domain Services Setup
- Installed Active Directory Domain Services (AD DS)
- Promoted server to Domain Controller
- Created new forest and domain: `techcorp.local`

---

### 3. User and Group Management
- Created multiple user accounts in Active Directory Users and Computers (ADUC)
- Created security groups for departments (IT, HR, Finance)
- Assigned users to appropriate security groups

---

### 4. Organizational Unit (OU) Structure
- Created departmental OUs (IT, HR, Finance)
- Moved users into appropriate OUs for structured administration

---

### 5. File Sharing & Permissions
- Created shared folders on Domain Controller
- Configured NTFS and share permissions
- Applied role-based access using security groups

---

### 6. Client Domain Authentication
- Joined Client1 to domain
- Verified successful domain login using `whoami`

---

### 7. Access Control Testing
- Tested shared folder access from Client1
- Verified permission enforcement across user groups

---

### 8. Help Desk Task Simulation
- Performed password reset using ADUC
- Verified account recovery

---

### 9. Group Policy (GPO Implementation)
- Created Group Policy Object to restrict Control Panel access
- Linked GPO to Organizational Units

---

### 10. Security Validation (Access Denied Test)
- Attempted restricted access from Client1
- Confirmed access denied due to permissions

---

## Screenshots Overview

1. Domain Controller setup  
2. AD DS installation  
3. User creation in ADUC  
4. OU structure  
5. File sharing and permissions  
6. Client domain login  
7. Access testing  
8. Password reset  
9. GPO configuration  
10. Access denied test  

---

## Project Summary
This lab demonstrates a complete Active Directory environment implementation, focusing on identity management, access control, and enterprise-level user administration.

---

## Key Outcomes
- Built and configured a Windows Server domain environment
- Implemented Active Directory structure (users, groups, OUs)
- Applied security controls using NTFS and Group Policies
- Simulated help desk troubleshooting scenarios
- Validated authentication and access control

