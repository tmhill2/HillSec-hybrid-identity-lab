# Phase 2 – Identity Foundation

## Objective

Establish the foundational identity structure within Okta by implementing a scalable Role-Based Access Control (RBAC) model. This phase focused on creating the organizational groups that will support user provisioning, application access, and administrative delegation throughout the project.

---

## Background

The identity foundation represents the first implementation phase of the project. Rather than creating users immediately, the RBAC model was implemented first to ensure permissions could be assigned through group membership instead of directly to individual accounts.

This approach follows enterprise IAM best practices and simplifies future user lifecycle management.

---

## Group Strategy

Three group categories were implemented:

### Administrative Groups

Administrative groups represent privileged roles responsible for managing the identity environment.

| Group |
|--------|
| ADM-IAM-Admins |
| ADM-IT-Admins |
| ADM-Security-Admins |
| ADM-Helpdesk |

---

### Department Groups

Department groups organize users based on business function.

| Group |
|--------|
| GRP-Executive |
| GRP-IAM |
| GRP-IT |
| GRP-Security |
| GRP-Engineering |
| GRP-Finance |
| GRP-HR |
| GRP-Sales |
| GRP-Marketing |

---

### Application Groups

Application groups will be used to assign access to enterprise applications.

| Group |
|--------|
| APP-Microsoft365 |
| APP-GitHub |
| APP-Splunk |
| APP-VPN |

---

## Configuration Summary

A total of seventeen custom groups were created within the Okta Workforce Identity Cloud tenant.

These groups establish the organizational structure that will support user provisioning, application assignments, and authentication policies in subsequent phases of the project.

---

## Validation

The group structure was reviewed to verify:

- Consistent naming conventions
- Accurate descriptions
- Separation of administrative and standard user groups
- Readiness for future user provisioning

---

## Screenshots

### Group Overview

*(Insert your first screenshot)*

### Additional Group View

*(Insert your second screenshot)*

---

## Lessons Learned

Implementing the RBAC structure before creating user accounts establishes a scalable identity foundation and aligns with enterprise IAM implementation practices. Separating administrative, departmental, and application groups simplifies future provisioning, supports least privilege, and improves long-term maintainability.
