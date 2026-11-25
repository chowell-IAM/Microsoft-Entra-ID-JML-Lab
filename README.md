# Microsoft Entra ID – Identity Lifecycle Management Lab

## Project Overview
This hands-on IAM lab demonstrates identity lifecycle management using a personal Microsoft Entra ID environment.

## Lab Environment
- Microsoft Entra ID Free
- Cloud-based test user accounts
- Security groups
- Microsoft Entra admin center

## Phase 1 – Joiner (Completed)
- Created a test user named Jordan Mitchell.
- Assigned employee ID LAB001.
- Assigned the Finance department and Financial Analyst job title.
- Created Finance and HR security groups.
- Added the user to SG-Finance-Employees.
- Verified group membership.

## Phase 2 – Mover (Completed)
- Simulated an employee transfer from Finance to HR.
- Updated the department and job title to HR Specialist.
- Removed Finance security group membership.
- Added the user to SG-HR-Employees.
- Verified that the previous group membership was removed.

## Phase 3 – Leaver (Completed)
- Simulated an HR-authorized employee termination.
- Disabled the user account in Microsoft Entra ID.
- Successfully revoked sign-in sessions.
- Removed membership from SG-HR-Employees.
- Verified that no group memberships remained.
- Confirmed that the account status was Disabled.
- Reviewed Microsoft Entra audit logs to validate
  successful deprovisioning activities.

## Audit and Compliance Verification
- Verified successful account disablement.
- Verified session revocation.
- Verified security group membership removal.
- Reviewed timestamps and success statuses in audit logs.
- Retained the disabled account for auditing purposes.


## Security Concepts
- Identity lifecycle management (JML)
- User provisioning and deprovisioning
- Role-based access control (RBAC) concepts
- Principle of least privilege
- Identity governance

## Project Status
Completed

## Certification
CompTIA Security+ (SY0-701)
