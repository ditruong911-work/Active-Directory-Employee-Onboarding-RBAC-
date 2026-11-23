# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* In this project I am working with a fictional company called Northstar Medical Group. They are a big organization with over 200+ employees that has been delegating their IT Infrastructure to a third-party MSP. It started out good but became disorganized, there was no RBAC policy in place. Users were being assigned access ad-hoc and there were no audit trails that resulted in HIPPA risks. 

## Solution Overview
* The solution was to take ownership of Northstar's Identity Infrastructure by building a basic employee onboarding pipeline in Active Directory. I set up the RBAC matrix to ensure users were given access ONLY according to their role. I also simulated a mock ticket where a user was provisioned with the incorrect level of access.  

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
