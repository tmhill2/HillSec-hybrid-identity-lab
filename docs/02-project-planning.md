# Phase 1 – Project Planning

## Objective

The objective of this phase was to design the identity architecture for the HillSec environment before implementing any technical components. Planning the organizational structure, access model, and naming conventions established a scalable foundation aligned with enterprise Identity and Access Management (IAM) best practices.

---

## Company Overview

HillSec is a fictional cybersecurity consulting and managed security services company created to simulate a real-world enterprise IAM implementation.

The organization consists of 25 employees distributed across multiple business units and utilizes a hybrid identity architecture built with Okta Workforce Identity Cloud, Microsoft Entra ID, Active Directory, and Splunk Enterprise.

---

## Organizational Design

The organization was designed to reflect a small-to-medium enterprise with clearly defined business functions.

### Departments

| Department | Employees |
|------------|----------:|
| Executive | 2 |
| Identity & Access Management | 2 |
| IT Operations | 4 |
| Security Operations | 3 |
| Engineering | 5 |
| Finance | 3 |
| Human Resources | 2 |
| Sales | 3 |
| Marketing | 1 |

---

## Identity Architecture

The environment was designed using a hybrid identity model consisting of:

- Okta Workforce Identity Cloud
- Microsoft Entra ID
- Active Directory
- Splunk Enterprise

This architecture allows the project to demonstrate both cloud-based and on-premises identity management concepts.

---

## RBAC Design

The project uses a Role-Based Access Control (RBAC) model.

Permissions are assigned to groups rather than individual users. This approach simplifies user provisioning, role changes, and offboarding while supporting the principle of least privilege.

Three group categories were defined during the planning phase:

- Administrative Groups
- Department Groups
- Application Groups

---

## Naming Standards

To maintain consistency throughout the environment, standardized naming conventions were established.

| Prefix | Purpose |
|--------|---------|
| ADM- | Administrative Groups |
| GRP- | Department Groups |
| APP- | Application Access Groups |

---

## Planning Decisions

Several design decisions were made before implementation began:

- Create organizational groups before provisioning users.
- Use group-based access assignments instead of direct user permissions.
- Separate privileged administrative groups from standard department groups.
- Design a scalable identity structure capable of supporting future application integrations.

---

## Technology Stack

- Okta Workforce Identity Cloud
- Microsoft Entra ID
- Active Directory
- Splunk Enterprise
- GitHub
- Windows Server
- Windows 11
- Kali Linux

---

## Lessons Learned

Planning the identity architecture before implementation establishes a clear roadmap for deployment. Defining organizational structure, RBAC strategy, and naming conventions in advance reduces implementation complexity and mirrors enterprise IAM project methodologies.
