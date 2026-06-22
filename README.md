\# Active Directory Helpdesk Lab



\---



\## Overview

This project simulates a real-world corporate Active Directory environment using Windows Server. It demonstrates core IT Help Desk and System Administration tasks including domain setup, user and group management, organizational units, file sharing, group policy, and access control enforcement.



\---



\## Purpose

To develop practical IT support and system administration skills in a controlled virtual environment, focusing on Active Directory operations, identity management, and troubleshooting scenarios commonly found in enterprise environments.



\---



\## Skills Covered

\- Active Directory Domain Services (AD DS)

\- Domain Controller configuration

\- User and Group Management

\- Organizational Units (OU) design

\- Security Groups and Role-Based Access Control (RBAC)

\- NTFS and Share Permissions

\- Group Policy Object (GPO) implementation

\- Domain-joined client authentication

\- Help Desk troubleshooting (password reset, access denied resolution)



\---



\## Environment

\- Windows Server (Domain Controller - DC1)

\- Windows 10/11 Client VM (Client1)

\- Active Directory Domain Services (AD DS)

\- Domain: techcorp.local



\---



\## Lab Steps



\### 1. Infrastructure Setup

\- Installed Windows Server for Domain Controller (DC1)

\- Installed Windows 10/11 Client machine (Client1)

\- Configured network connectivity between server and client



\---



\### 2. Active Directory Domain Services Setup

\- Installed Active Directory Domain Services (AD DS)

\- Promoted server to Domain Controller

\- Created new forest and domain: `techcorp.local`



\---



\### 3. User and Group Management

\- Created multiple user accounts in Active Directory Users and Computers (ADUC)

\- Created security groups for departments (IT, HR, Finance)

\- Assigned users to appropriate security groups



\---



\### 4. Organizational Unit (OU) Structure

\- Created departmental OUs (IT, HR, Finance)

\- Moved users into appropriate OUs for structured administration



\---



\### 5. File Sharing \& Permissions

\- Created shared folders on Domain Controller

\- Configured NTFS and share permissions

\- Applied role-based access using security groups (HR access control tested)



\---



\### 6. Client Domain Authentication

\- Joined Client1 to domain

\- Verified successful domain login using `whoami`

\- Confirmed domain user authentication



\---



\### 7. Access Control Testing

\- Tested shared folder access from Client1 using domain credentials

\- Verified permission enforcement across different user groups



\---



\### 8. Help Desk Task Simulation

\- Performed password reset using Active Directory Users and Computers (ADUC)

\- Verified account recovery and administrative support capability



\---



\### 9. Group Policy (GPO Implementation)

\- Created Group Policy Object to restrict Control Panel access

\- Linked GPO to Organizational Units to enforce policy



\---



\### 10. Security Validation (Access Denied Test)

\- Attempted restricted access from Client1

\- Confirmed access denied due to NTFS and group-based permissions



\---



\## Screenshots Overview



1\. Domain Controller (DC1 Setup)  

&#x20;  - Active Directory Domain Services installed and domain configured



2\. Active Directory Users  

&#x20;  - User accounts created and managed in ADUC



3\. Security Groups  

&#x20;  - IT, HR, Finance groups configured for role-based access control



4\. Organizational Units (OU Structure)  

&#x20;  - Users organized into department-based OUs



5\. File Sharing \& Permissions  

&#x20;  - NTFS and share permissions configured for HR folder



6\. Client Domain Login  

&#x20;  - Successful domain authentication verified using whoami



7\. Access Test  

&#x20;  - Shared folder access tested from Client1



8\. Password Reset (Helpdesk Task)  

&#x20;  - Password reset performed using ADUC



9\. Group Policy (GPO Configuration)  

&#x20;  - GPO created and linked to enforce restrictions



10\. Access Denied Test  

&#x20;   - Demonstration of permission enforcement using restricted access attempt



\---



\## Project Summary

This lab demonstrates a complete Active Directory environment implementation, focusing on identity management, access control, and enterprise-level user administration. It simulates real-world IT Help Desk and System Administrator tasks within a Windows Server domain.



\---



\## Key Outcomes

\- Built and configured a full Windows Server domain environment

\- Implemented structured Active Directory architecture (users, groups, OUs)

\- Applied security controls using NTFS and Group Policies

\- Simulated real-world help desk troubleshooting scenarios

\- Validated access control and authentication mechanisms



\---



