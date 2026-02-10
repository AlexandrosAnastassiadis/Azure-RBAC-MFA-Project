# Azure Identity & Access Management Project (RBAC & MFA)

## Overview
This project demonstrates how to secure access to Azure resources using
**Microsoft Entra ID**, **Multi-Factor Authentication (MFA)**, and
**Azure Role-Based Access Control (RBAC)**.

The focus is on applying **least privilege**, validating permissions through
real actions, and confirming results using **Azure Activity Logs**.

---

## Technologies & Services Used
- Microsoft Azure
- Microsoft Entra ID (Azure AD)
- Multi-Factor Authentication (MFA)
- Azure RBAC (Reader & Contributor roles)
- Azure Resource Groups
- Windows Server 2022 Virtual Machine
- Azure Activity Logs

---

## Project Scope
- Created a dedicated user account in Microsoft Entra ID
- Enforced MFA to strengthen authentication
- Deployed a resource group and a Windows Server 2022 VM
- Assigned RBAC roles at **resource group scope**
- Verified access permissions by attempting restricted and allowed actions
- Audited security events using Azure Activity Logs

---

## Key Security Concepts Demonstrated
- **Least Privilege** – starting with Reader role before elevating permissions
- **Strong Authentication** – enforcing MFA on user accounts
- **Role-Based Access Control** – managing access at the correct scope
- **Auditing & Monitoring** – verifying actions through Activity Logs
- **Defense in Depth** – combining identity security with access control

---

## Validation & Testing
- Confirmed Reader role could view resources but not restart the VM
- Verified denied actions through error messages and activity logs
- Upgraded role to Contributor and successfully restarted the VM
- Reviewed Activity Logs to confirm both denied and successful operations

---

## Outcome
This project provided hands-on experience with Azure identity and access
management and demonstrated how RBAC and MFA work together to secure
cloud environments.

It highlights practical understanding of how organizations control
who can access resources, what actions they can perform, and how
those actions are audited.

---

## Lessons Learned
- MFA significantly reduces the risk of account compromise
- RBAC must be applied at the correct scope to be effective
- Reader and Contributor roles have clear and enforceable boundaries
- Activity Logs are essential for auditing and troubleshooting access issues



