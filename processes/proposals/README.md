# Proposals

This section defines how proposals are made, reviewed, approved, deferred, rejected, or escalated within IES, the Information Exchange Standard.

Proposals are the formal route for material governance, technical, operational, repository, domain, and publication decisions. They provide a structured way to describe a proposed change, identify its impact, route it to the appropriate governance group, and record the outcome.

---

## Purpose

The purpose of the proposal process is to ensure that material changes to IES are considered transparently, proportionately, and by the appropriate governance route.

The proposal process supports:

* clear description of proposed changes
* early identification of impact, risk, and dependencies
* review by the appropriate people or groups
* proportionate decision-making
* escalation where required
* traceability from proposal through to implementation and release
* alignment with the IES Charter

Not every change requires a formal proposal. Routine activity, minor corrections, low-risk maintenance, and small documentation changes may normally be handled through the relevant repository issue or pull request workflow.

---

## When a Proposal is Required

A proposal should be used where a change is material, has governance significance, affects more than one group or repository, or requires a formal decision.

A proposal is normally required for:

* material changes to IES governance
* changes to governance roles, decision-making rules, or membership models
* creation, renaming, merger, suspension, or retirement of a Domain Working Group
* appointment or replacement of certain official role-holders where governance approval is required
* changes to IES Top or IES Core
* changes with cross-domain implications
* creation, renaming, publication, archiving, deprecation, or transfer of a repository
* changes to mandatory repository documentation or repository structure
* changes to development, review, branching, release, or contribution processes
* changes to tooling, platforms, modelling tools, publication infrastructure, or GitHub organisation arrangements
* changes affecting licensing, attribution, legal terms, security arrangements, or access controls
* public release decisions where formal approval is required
* disputed matters that cannot be resolved at the relevant working level
* exceptions or waivers from normal governance, repository, development, or release rules

The route for a proposal depends on its impact, not only on the file, repository, or group where the issue first arises.

---

## Types of Proposal

IES may use proposals for a range of governance, technical, operational, and publication matters.

### Governance and Role Proposals

Governance and role proposals concern how IES is governed.

These may include:

* changes to the IES Charter
* changes to governance roles or responsibilities
* changes to Steering Group decision-making rules
* changes to L0 or L1 Ontology Maintainer membership rules
* changes to Platform and Communications responsibilities
* changes to public record requirements
* changes to escalation routes

These proposals will normally require Steering Group consideration.

### Domain Governance Proposals

Domain governance proposals concern the creation, scope, naming, transfer, or retirement of domain responsibilities.

These may include:

* forming a new Domain Working Group
* renaming a Domain Working Group
* changing the scope of a Domain Working Group
* merging or splitting Domain Working Groups
* transferring a repository or extension from one Domain Working Group to another
* adopting, renaming, superseding, or retiring material originally developed under another domain
* suspending or retiring an inactive Domain Working Group

A domain namespace should not be created in repository names unless the relevant Domain Working Group has been formally established.

### Ontology and Technical Proposals

Ontology and technical proposals concern changes to ontology content, modelling principles, serialisation, implementation artefacts, or technical coherence.

These may include:

* changes to IES Top
* changes to IES Core
* changes to domain-driven ontology extensions
* changes affecting cross-domain alignment
* changes affecting ontology modelling principles
* changes affecting RDF implementation or serialisation
* changes affecting traceability between conceptual models and implementation artefacts
* changes requiring migration guidance or compatibility notes

Changes affecting IES Top or IES Core should involve the L0 or L1 Ontology Maintainers. Strategic, cross-domain, high-impact, or disputed matters must be escalated to the Steering Group.

### Repository Lifecycle Proposals

Repository lifecycle proposals concern the creation, publication, renaming, archiving, deprecation, transfer, or retirement of repositories.

These may include:

* creating a new repository
* making a repository public
* renaming a repository
* archiving a repository
* deprecating or superseding a repository
* transferring responsibility for a repository
* changing whether a repository is administrative or ontology-bearing
* changing mandatory repository files or repository-level documentation requirements

These proposals should align with repository naming, development, ontology index, and public release processes.

### Tooling, Platform, and Development Process Proposals

Tooling, platform, and development process proposals concern how IES is developed, managed, validated, published, or maintained.

These may include:

* changing modelling tools
* adopting new ontology editing or validation tools
* migrating issue tracking, documentation, release, or publication tooling
* changing GitHub organisation structure or permissions models
* changing branching strategy or pull request requirements
* changing validation, testing, or quality assurance expectations
* changing mandatory repository file structure
* changing versioning, changelog, or release note requirements

These proposals may involve Platform and Communications Management, L0 or L1 Ontology Maintainers, Repository Maintainers, Domain Working Groups, or the Steering Group depending on impact.

### Release and Publication Proposals

Release and publication proposals concern public availability and official release status.

These may include:

* approving a public release
* changing release criteria or cadence
* publishing a repository for the first time
* withdrawing, correcting, or superseding a public release
* changing public-facing release artefacts
* changing release communication arrangements
* changing public-facing documentation associated with a release

A repository, artefact, or change must not be made public as an official IES output until it has completed the relevant public release process.

### Access, Security, Legal, and Risk Proposals

Access, security, legal, and risk proposals concern permissions, security posture, legal basis, licensing, attribution, or risk management.

These may include:

* changes to repository access models
* changes to branch protection or protected branch rules
* changes to security reporting arrangements
* responses to significant security, legal, operational, or continuity risks
* changes to licensing approach
* inclusion of third-party material
* changes to attribution or acknowledgement requirements
* changes to contributor terms

Some matters in this category may require restricted handling, but the governance route should still be clear and recorded appropriately.

### Operational Sustainability Proposals

Operational sustainability proposals concern the ongoing ability to keep IES available, maintained, and accessible.

These may include:

* funding GitHub organisation costs
* funding website, domain, or publication infrastructure
* changing the organisation responsible for operational costs
* loss of key role-holders
* continuity planning for maintainers or platform administrators
* resourcing for critical maintenance activity
* risks to access, availability, or operational continuity

Where funding, access to funding, or operational continuity is at risk, the matter should be escalated to the Steering Group as a matter of urgency.

### Documentation and Communication Proposals

Documentation and communication proposals concern public-facing explanation, guidance, governance documentation, and communication channels.

These may include:

* major restructuring of governance documentation
* changes to glossary terms
* publication of user guidance
* changes to public website content
* changes to communication channels
* publication of roadmap or explanatory material
* changes to templates or mandatory repository documentation

Small documentation corrections do not normally require a proposal.

### Exception or Waiver Proposals

Exception or waiver proposals request a controlled departure from normal rules.

These may include:

* temporary exception to repository naming rules
* temporary publication of a repository with incomplete documentation
* exceptional access arrangements
* deviation from standard branching or review process
* time-limited governance workaround during transition

Exceptions should be rare, explicit, time-bound, and recorded.

---

## Starting a Proposal

A proposal should normally be started using the [Proposal Template](./proposal-template.md).

The proposal should describe:

* what is being proposed
* why the change is needed
* what repositories, groups, roles, processes, or releases are affected
* what decision is required
* who should review the proposal
* any risks, dependencies, or implementation considerations
* any relevant links to issues, pull requests, discussions, or supporting material

Where a proposal begins as a GitHub issue, pull request, meeting discussion, or informal request, it may still need to be converted into the proposal template if the change is material or requires formal governance decision.

---

## Submitting a Proposal

Completed proposals should be submitted to:

```text
administrator@informationexchangestandard.org
```

Where appropriate, a proposal may also be linked to the relevant GitHub issue, pull request, repository, Domain Working Group record, or Steering Group agenda item.

The administrator should route the proposal to the relevant governance group or role-holders for consideration.

---

## Proposal Routing

The appropriate review and decision route depends on the subject and impact of the proposal.

At a high level:

* domain-specific proposals should normally be considered by the relevant Domain Working Group
* proposals affecting IES Top or IES Core should involve the L0 or L1 Ontology Maintainers
* repository-specific proposals should involve the relevant repository maintainers
* platform, access, GitHub organisation, or communications proposals should involve Platform and Communications Management
* governance, strategic, cross-domain, high-impact, disputed, or exceptional matters should be considered by the Steering Group

Where there is uncertainty about the correct route, the proposal should be escalated to the Steering Group or placed on a Steering Group agenda for routing.

---

## Steering Group Consideration

Proposals requiring Steering Group decision should normally be discussed at a Steering Group meeting.

This means that the time required to decide a proposal may depend on:

* when the proposal is submitted
* whether the proposal is complete
* whether further information is needed
* whether prior review by a Domain Working Group, L0 or L1 Ontology Maintainers, Platform and Communications Management, or Repository Maintainers is required
* the date of the next relevant Steering Group meeting
* whether the proposal is urgent

Urgent proposals may be escalated outside the normal meeting cycle where there is a clear operational, security, continuity, or governance need.

---

## Decision-Making

Proposals should be decided by the group or role-holders with the appropriate authority.

A proposal may be:

* accepted
* accepted with conditions
* deferred
* rejected
* returned for further information
* escalated to another governance route
* superseded by another proposal or decision

Where a Steering Group decision is required, the decision is made by majority vote of the Voting Members unless a different rule applies in the relevant governance documentation.

Where a vote is tied, the Steering Group Chair has the casting vote.

---

## Implementation

An accepted proposal does not by itself implement the change.

Implementation must take place through the appropriate repository, process, role, or governance mechanism. This may involve:

* creating or updating a GitHub issue
* creating a branch
* submitting a pull request
* updating governance documentation
* updating the Ontology Index
* updating membership records
* updating repository-level documentation
* making a repository public through the public release process
* recording a decision in Steering Group minutes or another appropriate governance record

Implementation should remain traceable to the accepted proposal.

---

## Proposal Lifecycle

The proposal lifecycle defines the stages through which a proposal moves.

A proposal may move through stages such as:

* draft
* submitted
* under review
* returned for further information
* accepted
* accepted with conditions
* deferred
* rejected
* implemented
* superseded

More information is available in:

* [Proposal Lifecycle](./proposal-lifecycle.md)

---

## Relationship with Development

Accepted proposals may lead to development activity in one or more repositories.

Development must follow the relevant development rules, repository-level requirements, and GitHub working practices.

More information is available in:

* [Development Rules](../development/development-rules.md)

---

## Relationship with Public Release

Some accepted proposals may require public release activity.

A repository, artefact, or change must not be made public as an official IES output until it has completed the relevant public release process.

More information is available in:

* [Release Process](../public-release/release-process.md)

---

## Records and Traceability

Proposal records should be sufficient to explain what was proposed, why it was proposed, how it was reviewed, what decision was made, and how the decision was implemented.

Records may include:

* proposal documents
* GitHub issues
* pull requests
* review comments
* Steering Group minutes
* Domain Working Group records
* changelog entries
* release notes
* governance decision records

Material proposals should remain traceable from proposal through to implementation and release where relevant.

---

## Contents

* [Proposal Lifecycle](./proposal-lifecycle.md)
* [Proposal Template](./proposal-template.md)
