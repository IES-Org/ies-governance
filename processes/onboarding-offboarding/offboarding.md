# Offboarding from the IES GitHub Organisation

This document defines the process for offboarding individuals from the IES GitHub organisation.

It describes how access is reviewed, removed, confirmed, and recorded when an individual no longer requires access or no longer holds a role that requires access.

---

## Purpose

The purpose of this process is to ensure that access to the IES GitHub organisation is removed or amended in a controlled, timely, proportionate, and auditable way.

This process supports:

* removal of access that is no longer required
* alignment between GitHub access and current governance roles
* protection of repositories, branches, and organisation settings
* prevention of unmanaged or excessive access
* clear audit records for access changes
* continuity where responsibilities need to be transferred

Failure to follow this process may result in inappropriate access remaining active.

---

## Scope

This process applies to:

* all individuals with access to the IES GitHub organisation
* all repositories within the IES GitHub organisation
* GitHub team access
* repository-level access
* organisation-level access
* elevated access permissions
* access associated with governance, development, maintenance, platform, or communications roles

This process concerns access to the IES GitHub organisation. It does not, by itself, remove a person from a governance role unless that role is separately ended through the relevant governance route.

---

## Core Principle

Access to the IES GitHub organisation must remain justified, proportionate, and aligned with the individual’s current role or contribution.

Access must be removed or amended when it is no longer required.

Offboarding may be triggered by:

* a person leaving a role
* a person leaving an organisation
* a person leaving a Domain Working Group
* a person no longer requiring access
* an access review date being reached
* a repository changing status
* a governance, security, operational, or conduct concern
* replacement of a Domain Working Group Representative
* replacement or removal of a L0 or L1 Ontology Maintainer
* replacement or removal of a Platform and Communications role-holder
* a request from an authorised governance role-holder

---

## Offboarding Request Process

### Offboarding Request Submission

An authorised individual submits an offboarding request by email to:

```text
administrator@informationexchangestandard.org
```

An offboarding request may be submitted by one of the following:

* a Domain Working Group Chair
* a Domain Working Group Representative
* the Steering Group Chair
* a Platform and Communications role-holder
* an IES GitHub Organisation Administrator

Where access is associated with a specific Domain Working Group, the request should normally come from the relevant Domain Working Group Chair or Representative.

Where access is associated with platform administration, L0 or L1 Ontology Maintainer responsibilities, or elevated permissions, the request should be routed with appropriate visibility to the Steering Group or Platform and Communications role-holders.

---

### Distribution and Visibility

On receipt, the offboarding request should be distributed to the relevant parties for visibility and validation.

This may include:

* the relevant Domain Working Group Chair
* the relevant Domain Working Group Representative
* IES GitHub Organisation Administrators
* Platform and Communications role-holders
* L0 or L1 Ontology Maintainers, where access relates to IES Top or IES Core
* the Steering Group, where the access is elevated or governance-significant

This supports shared awareness of access changes and helps ensure that offboarding decisions are transparent and auditable.

---

### Review and Validation

Recipients should review the request to confirm that:

* the individual has access that should be removed or amended
* the access is no longer required or is no longer proportionate
* the request aligns with the relevant governance role or responsibility change
* any repository, team, organisation, or enterprise-level access is identified
* any ownership, maintainer, or role-holder responsibilities need to be transferred
* there are no unresolved security, legal, operational, or continuity considerations

Where concerns are raised, offboarding may be delayed, amended, escalated, or handled urgently depending on the risk.

---

### Access Removal or Amendment

IES GitHub Organisation Administrators remove or amend access using the least disruptive route that addresses the access requirement.

This may include:

* removing the individual from GitHub teams
* removing repository-level permissions
* removing organisation-level permissions
* removing enterprise-level permissions
* removing elevated permissions
* changing repository ownership or responsibility records
* updating branch protection, review, or release settings where required

Permissions must be removed where they are no longer justified.

Where multiple access paths exist, GitHub applies the highest permission available to the user. Administrators must check team, repository, organisation, and enterprise-level access to ensure the intended access change has taken effect.

---

### Audit Logging

Following offboarding, access changes must be recorded in the access audit log.

The audit record should include:

* individual details
* organisation
* GitHub username
* previous access
* access removed or amended
* reason for offboarding
* date of offboarding
* requester
* approving or provisioning role-holder
* any replacement role-holder where relevant
* any residual access or follow-up actions
* any relevant notes or conditions

This ensures traceability of access decisions.

---

### Confirmation

A confirmation email should be issued once offboarding has been completed.

The confirmation should:

* confirm that access has been removed or amended
* identify the relevant team, repository, organisation, or elevated access affected
* state whether any follow-up actions remain
* be copied to `administrator@informationexchangestandard.org`

Where appropriate, confirmation may also be copied to the relevant Domain Working Group Chair, Domain Working Group Representative, Platform and Communications role-holder, or Steering Group Chair.

---

## Required Information

All offboarding requests should include the following information:

* first name
* surname
* organisation
* GitHub username
* email address, where known
* current Domain Working Group, team, repository, or role association
* access to be removed or amended, where known
* reason for offboarding
* requested effective date
* replacement role-holder, where relevant
* any continuity, security, or operational concerns

Requests that do not include sufficient information may be returned for clarification, unless urgent access removal is required.

---

## Offboarding Email Template

The following template may be used when submitting an offboarding request.

```text
Subject: IES GitHub organisation offboarding request - [Name]

Hi,

This is an offboarding request for [First name] [Surname] from [Organisation].

First name:
[First name]

Surname:
[Surname]

Organisation:
[Organisation]

GitHub username:
[GitHub username]

Email address:
[Email address]

Current Domain Working Group, team, repository, or role association:
[Details]

Access to be removed or amended:
[Team, repository, organisation, or elevated access]

Reason for offboarding:
[Reason]

Requested effective date:
[Date]

Replacement role-holder, where relevant:
[Name / Not applicable]

Continuity, security, or operational concerns:
[Details / None identified]

Many thanks,

[Name]
[Role]
```

---

## Permission Model

Access within the IES GitHub organisation may exist across several levels:

* repository permissions
* team permissions
* organisation permissions
* enterprise permissions

Offboarding must consider all relevant access paths.

Repository and team permissions should normally be removed or amended first where access was granted for a specific domain, repository, or contribution route.

Organisation permissions and elevated permissions must be reviewed carefully because they may affect multiple repositories or organisation-level settings.

Enterprise permissions are restricted and should be removed or amended only through the IES GitHub Organisation Custodian or other specifically authorised role-holders.

---

## Governance Alignment

Access must remain aligned with IES governance roles and responsibilities.

Offboarding may be required where:

* a Domain Working Group Chair leaves that role
* a Domain Working Group Representative is replaced
* a Steering Group Advisory Member leaves that role
* a L0 or L1 Ontology Maintainer leaves that role
* a Platform and Communications role-holder leaves that role
* a Repository Maintainer no longer maintains a repository
* a Domain Working Group becomes inactive
* a person no longer contributes to the work for which access was granted

Access to GitHub does not confer governance authority.

Where a person ceases to hold a governance role, the relevant public records should be updated separately from the GitHub access change.

---

## Continuity and Handover

Where offboarding affects an official role-holder, repository maintainer, or person with elevated permissions, continuity should be considered before access is removed where circumstances allow.

This may include:

* identifying a replacement role-holder
* transferring repository maintainer responsibilities
* transferring open issues or pull requests
* checking release or publication responsibilities
* reviewing branch protection or review requirements
* updating repository-level maintainer files
* updating governance records
* updating the Ontology Index where relevant
* ensuring operational funding or platform responsibilities are not left unsupported

Where there is an urgent security, access, or conduct concern, access may need to be removed before continuity arrangements are completed.

---

## Urgent Offboarding

Urgent offboarding may be required where there is a security, access, conduct, legal, operational, or governance risk.

Urgent offboarding may involve immediate removal or suspension of access.

Urgent offboarding should still be recorded and traceable. The audit log should be updated as soon as reasonably possible, and the relevant governance route should be notified.

Urgent offboarding may be required where:

* an account may be compromised
* a person has left an organisation unexpectedly
* a person no longer has authority to act on behalf of an organisation or Domain Working Group
* elevated permissions present a security or governance risk
* a conflict of interest cannot be managed while access remains active
* a serious breach of governance, security, or conduct expectations is identified

---

## Access Review and Lifecycle

Access must be reviewed at the defined access review date.

Access should also be reviewed where:

* a person changes role
* a person changes organisation
* a person leaves a Domain Working Group
* a person no longer requires access
* a repository changes status
* a repository is archived, deprecated, superseded, or made public
* a security, governance, or operational concern is identified
* elevated permissions are no longer required

Access must be removed where it is no longer required.

Access records should be updated when access is removed, amended, reviewed, or retained.

---

## Public Records and Repository Records

Offboarding may require updates to public records or repository-level documentation.

This may include:

* Steering Group Voting Members
* Steering Group Advisory Members
* Domain Working Group official role-holders
* L0 or L1 Ontology Maintainers
* Platform and Communications role-holders
* repository-level maintainer files
* repository README files
* the Ontology Index

Repository Maintainer information should be updated in the relevant repository’s maintainer file.

Current and past role-holder records in the governance repository should be updated where the offboarding affects an official role-holder.

---

## Escalation

Escalation is required where:

* there is disagreement about access removal
* elevated permissions are involved
* governance alignment is unclear
* the access change affects IES Top or IES Core
* the access change affects organisation-level or enterprise-level permissions
* a security or operational concern is identified
* offboarding creates a continuity risk
* no suitable replacement role-holder is available
* the request cannot be validated through the normal route

The Steering Group may act as the final authority in unresolved access cases.

Urgent security or access issues should be escalated through the appropriate security or platform route.

---

## Relationship to Other Processes

This process operates alongside:

* [Onboarding](./onboarding.md)
* [Development Rules](../development/development-rules.md)
* [Repository Naming](../development/repository-naming.md)
* [Release Process](../public-release/release-process.md)

Access relating to public repositories must also align with the public release process and repository-level documentation requirements.

---

## Status

This document defines the current offboarding process for access to the IES GitHub organisation.

The process may evolve as IES governance, tooling, security requirements, and operational arrangements mature.

