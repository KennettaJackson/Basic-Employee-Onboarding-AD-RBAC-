# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Before this project, Northstar Medical Group's Active Directory environment (Fictional Company) was poorly managed by an MSP and had very little structure. Users were created manually with inconsistent permissions, departments weren't properly organized, and there was no reliable process for onboarding or offboarding employees. Documentation was almost nonexistent, which led to delays, confusion, and accounts remaining active long after employees left the company. On top of that, these issues created unnecessary security risks and put the organization at risk of failing HIPAA compliance requirements.

## Solution Overview
* To fix these issues, I built a new Active Directory domain for Northstar Medical Group (NMG.com) from the ground up and designed a structured Organizational Unit (OU) hierarchy based on business departments. I created security groups using a flat Role-Based Access Control (RBAC) model so permissions could be assigned through group membership instead of managing users individually. This approach follows the principle of least privilege by ensuring users only receive the access they need for their roles. I also simulated and resolved a mock support ticket where a user was provisioned with the incorrect level of access, reinforcing how to identify and correct permission issues in a real-world environment. The new structure makes user provisioning and access management more secure, consistent, and scalable while reducing the risk of human error.

## Video Walkthrough
https://www.loom.com/share/497604b4b6684bcc8a7e8b40d16cebb9

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built the NMG.com Active Directory domain from scratch.
* Designed a structured OU hierarchy and implemented a flat RBAC model using security groups to simplify and secure access management.
* Fully documented the setup process, including OU structure, group design, and user provisioning workflow for future reference and scalability.
* Successfully resolved a mock support ticket involving a user with incorrect access by identifying the issue and correcting group membership to enforce proper permissions.
* Gained a stronger understanding of Role-Based Access Control (RBAC), the Principle of Least Privilege, Active Directory structure, and how proper organization and attributes directly impact security, compliance, and day-to-day IT operations.

