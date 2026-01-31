# Active Directory Account & Policy Security Lab

## Overview
This project demonstrates the implementation of identity and access management controls in a Windows Server 2022 Active Directory environment. The lab focuses on organizational unit (OU) design, user account management, Group Policy enforcement, and domain-level password and lockout hardening aligned with Security+ best practices.

## Environment
- Windows Server 2022
- Active Directory Domain Services (AD DS)
- Group Policy Management
- Single-domain lab environment (mycompany.com)

## Key Implementations
- Created department-based Organizational Units (Engineering and Marketing)
- Added and managed domain user accounts within OUs
- Implemented Group Policy Objects (GPOs) to:
  - Prohibit access to the Control Panel and PC settings
  - Deny all access to removable storage devices
- Hardened domain password and account lockout policies

## Security Concepts Demonstrated
- Identity and Access Management (IAM)
- Least privilege enforcement
- Policy scoping and inheritance
- Protection against brute-force attacks
- Insider threat mitigation

## Learning Outcomes
- Understanding how OU structure affects policy enforcement
- Applying Group Policy to enforce organizational security controls
- Implementing domain-level password and lockout policies
