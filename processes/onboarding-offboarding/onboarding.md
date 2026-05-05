# Onboarding to the IES GitHub Organisation

This document defines the process for onboarding individuals to the IES GitHub organisation.

It describes how access is requested, reviewed, approved, provisioned, confirmed, and recorded.

---

## Purpose

The purpose of this process is to ensure that access to the IES GitHub organisation is controlled, deliberate, proportionate, and auditable.

This process supports:

* access being assigned in line with governance roles and responsibilities
* transparent and auditable onboarding decisions
* appropriate use of GitHub teams, repository permissions, and organisation permissions
* prevention of unauthorised or unmanaged access
* clear lifecycle management for access reviews and removal

Failure to follow this process may result in rejection of the access request.

---

## Scope

This process applies to:

* all individuals requesting access to the IES GitHub organisation
* all repositories within the IES GitHub organisation
* GitHub team access
* repository-level access
* organisation-level access
* elevated access requests

This process concerns access to the IES GitHub organisation. It does not, by itself, confer governance authority or appoint an individual to a governance role.

---

## Core Principle

Access to the IES GitHub organisation is endorsement-based.

No individual may be onboarded without explicit endorsement from one of the following:

* a Domain Working Group Chair
* a Domain Working Group Representative

There is no direct self-service or public access pathway for joining the IES GitHub organisation.

Access must be justified, proportionate, and aligned with the individual’s role or contribution.

---

## Access Request Process

### Endorsement Submission

An authorised individual submits an endorsement request by email to:

```text
admin@informationexchangestandard.org
```

The endorsement request must be submitted by a Domain Working Group Chair or Domain Working Group Representative. The mailbox is configured to accept incoming mail only from Steering Group Voting Members, as they are the only individuals authorised to provide endorsement.

The mailbox may be configured to accept onboarding requests only from authorised senders and to reject or disregard requests from unauthorised senders.

This ensures that onboarding requests originate from within the recognised governance structure.

---

### Distribution and Visibility

On receipt, the endorsement request should be distributed to the relevant parties for visibility and review.

This may include:

* Domain Working Group Chairs
* Domain Working Group Representatives
* IES GitHub Organisation Administrators
* Platform and Communications role-holders

This supports shared awareness of access requests and helps ensure that access decisions are transparent and auditable.

---

### Review and Validation

Recipients should review the request to confirm that:

* the request is appropriate and justified
* the requested level of access is proportionate
* the request aligns with governance roles and responsibilities
* the requested access is limited to what is needed
* there is no conflict with existing permissions or access arrangements
* there are no obvious security, operational, or governance concerns

Where concerns are raised, onboarding may be delayed, amended, escalated, or rejected.

---

### Audit Logging

Following review, onboarding details must be recorded in an access audit log.

The audit record should include:

* individual details
* organisation
* sector
* Domain Working Group endorsement
* GitHub username
* email address
* email type
* access requested
* access granted
* business justification
* date of onboarding
* access review date
* approving or provisioning role-holder
* any relevant notes or conditions

This ensures traceability of access decisions.

---

### Access Provisioning

IES GitHub Organisation Administrators provision access using:

* team-based permissions where possible
* repository-level permissions where necessary
* organisation-level permissions only where justified
* enterprise-level permissions only where specifically required and authorised

Permissions must follow the principle of least privilege.

Where multiple access paths exist, GitHub applies the highest permission available to the user. This should be considered when assigning access through teams, repositories, or organisation-level roles.

---

### Confirmation

A confirmation email should be issued to the onboarded individual once access has been provisioned.

The confirmation should:

* confirm that onboarding has been completed
* specify the level or type of access granted
* identify the relevant team or repositories where appropriate
* state the access review date
* provide any relevant guidance or links
* be copied to `admin@informationexchangestandard.org`

This ensures transparency and shared awareness of the access decision.

---

## Required Information

All onboarding requests must include the following information:

* first name
* surname
* access review date
* Domain Working Group endorsement
* organisation
* sector
* GitHub username
* email address
* email type
* team or repository access required
* business justification

Requests that do not include the required information may be rejected or returned for clarification.

---

## Endorsement Email Template

The following template may be used by Domain Working Group Chairs or Domain Working Group Representatives when submitting an onboarding request.

```text
Subject: IES GitHub organisation onboarding endorsement - [Name]

Hi,

This is an endorsement request for [First name] [Surname] from [Organisation] to be onboarded to the IES GitHub organisation.

First name:
[First name]

Surname:
[Surname]

Access review date:
[Date]

Domain Working Group endorsement:
[Domain Working Group]

Organisation:
[Organisation]

Sector:
[Public / Private / Academic / Other]

GitHub username:
[GitHub username]

Email address:
[Email address]

Email type:
[Corporate / Personal]

Team or repository access required:
[Team or repository access]

Business justification:
[Justification]

Many thanks,

[Name]
[Domain Working Group Chair / Domain Working Group Representative]
```

---

## Permission Model

Access within the IES GitHub organisation may be structured across several levels:

* repository permissions
* team permissions
* organisation permissions
* enterprise permissions

Repository and team permissions should be used where possible.

Organisation permissions should be limited to people who need them for their role.

Enterprise permissions are restricted and should be limited to the IES GitHub Organisation Custodian or other specifically authorised role-holders where required.

Access must be proportionate to the role being performed.

---

## Governance Alignment

Access must align with IES governance roles and responsibilities.

Typical access patterns may include:

* Domain Working Group members receiving access to relevant domain repositories where needed
* Repository Maintainers receiving access to the repositories they maintain
* Common Ontology Maintainers receiving access appropriate to maintaining IES Top and IES Core
* Platform and Communications role-holders receiving access appropriate to managing the IES GitHub organisation and related platform responsibilities
* Steering Group Voting Members receiving read access across repositories where required to support oversight and informed decision-making

Access to GitHub does not confer governance authority.

A person may have technical permission to view, edit, review, or merge content in GitHub, but governance authority derives from the relevant IES role, process, or decision route.

---

## Access Review and Lifecycle

Access must be reviewed at the defined access review date.

Access should also be reviewed where:

* a person changes role
* a person changes organisation
* a person leaves a Domain Working Group
* a person no longer requires access
* a repository changes status
* a security, governance, or operational concern is identified
* elevated permissions are no longer required

Access must be removed where it is no longer required.

Access records should be updated when access is granted, changed, reviewed, or removed.

---

## Escalation

Escalation is required where:

* there is disagreement about access
* elevated permissions are requested
* governance alignment is unclear
* the business justification is insufficient
* the requested access appears disproportionate
* a security or operational concern is identified
* a request cannot be validated through the endorsement route

The Steering Group may act as the final authority in unresolved access cases.

Urgent security or access issues should be escalated through the appropriate security or platform route.

---

## Relationship to Other Processes

This process operates alongside:

* [Offboarding](./offboarding.md)
* [Development Rules](../development/development-rules.md)
* [Repository Naming](../development/repository-naming.md)
* [Release Process](../public-release/release-process.md)

Access relating to public repositories must also align with the public release process and repository-level documentation requirements.

---

## Status

This document defines the current onboarding process for access to the IES GitHub organisation.

The process may evolve as IES governance, tooling, security requirements, and operational arrangements mature.
