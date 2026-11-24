# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* NorthStar Medical Group (NMG) is a fictional healthcare organization with over 200 employees that outsourced its IT Infrastructure to a third-party Managed Service Provider (MSP). Over time, inconsistent user provisioning, a lack of role-based access control (RBAC), and limited audit trials created security vulnerabilities and potential HIPPA compliance risks. 

## Solution Overview
* To address these challenges, I developed an employee onboarding process using Active Directory and implemented an RBAC matrix to ensure users received appropriate access based on their job responsibilities. I also simulated a help desk incident involving incorrect access permissions, performed root cause analysis, implemented corrective actions, and documented the resolution.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU Structure
* Implemented RBAC with security groups mapped to each department
* Provisioned user accounts with consistent naming conventions and attribute standards
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)
* Documented full incident resolution with root cause analysis
