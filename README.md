#  Active Directory Account & Policy Security Lab

##  Overview
This project demonstrates the implementation of identity and access management (IAM) controls in a Windows Server 2022 Active Directory environment.

The lab focuses on designing Organizational Units (OUs), managing domain user accounts, and enforcing security policies using Group Policy Objects (GPOs). The goal was to simulate how organizations control user access, enforce security standards, and protect against common threats.

---

##  Environment
- Windows Server 2022  
- Active Directory Domain Services (AD DS)  
- Group Policy Management Console (GPMC)  
- Single-domain environment (`mycompany.com`)  

---

##  Key Implementations

###  Organizational Unit (OU) Design
- Created department-based OUs:
  - Engineering  
  - Marketing  
- Structured users within OUs to allow targeted policy enforcement  

---

### 👤 User Account Management
- Created and managed domain user accounts  
- Assigned users to appropriate OUs based on role/department  
- Applied least privilege principles through controlled access  

---

###  Group Policy Configuration (GPOs)
Configured GPOs to enforce security controls:

- Disabled access to Control Panel and PC settings  
- Blocked access to removable storage devices  
- Applied policies at the OU level for targeted enforcement  

---

### 🔐 Password & Account Lockout Policies
Configured domain-level security policies to reduce risk of unauthorized access:

- Minimum password length enforced  
- Password complexity requirements enabled  
- Account lockout after multiple failed login attempts  
- Lockout duration configured to prevent brute-force attacks  

---

## ⚙️ Example Configurations

### Password Policy
- Minimum length: 8+ characters  
- Complexity: Enabled  
- Account lockout threshold: 5 attempts  
- Lockout duration: 15 minutes  

### GPO Restrictions
- Control Panel access: Disabled  
- Removable storage: Blocked  

### OU Structure
- Engineering OU  
- Marketing OU  
- Users assigned based on department for policy targeting  

---

##  Security Concepts Demonstrated
- Identity and Access Management (IAM)  
- Least privilege enforcement  
- Group Policy scoping and inheritance  
- Protection against brute-force attacks  
- Insider threat mitigation  

---

## 📊 Key Takeaways
- OU structure directly impacts how policies are applied  
- Group Policy enables centralized security management  
- Strong password and lockout policies reduce attack risk  
- Access control is critical in enterprise environments  

---

##  Skills Demonstrated
- Active Directory administration  
- OU design and policy structuring  
- Group Policy configuration and enforcement  
- Account security and hardening  
- Enterprise security best practices  

---

## Ethical Statement
This lab was conducted in a controlled environment for educational and defensive security training purposes only.
