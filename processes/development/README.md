# Development

This section defines how development work is undertaken within IES, the Information Exchange Standard.

It applies to development activity carried out in repositories within the IES GitHub organisation, including IES Top, IES Core, domain-driven repositories, and administrative repositories.

---

## Purpose

The purpose of this section is to ensure that IES development is transparent, traceable, technically coherent, and aligned with the IES governance framework.

Development processes support:

* consistent repository-based working
* clear issue and pull request workflows
* appropriate review and approval
* traceability between proposals, implementation, and release
* alignment between domain-driven development and IES Top and IES Core
* clear distinction between official IES work and external or informal material

---

## Authoritative Development Environment

The IES GitHub organisation is the authoritative development environment for IES.

Official IES development activity, approved repository content, governance documentation, and release material are maintained through repositories in the IES GitHub organisation.

Work carried out elsewhere, including private forks, local machines, external repositories, or other systems, may support discussion, experimentation, or preparation. However, it is not part of the official approved state of IES unless it is proposed, reviewed, accepted, and merged through the relevant IES governance and development processes.

---

## Development Principles

Development activity within IES should follow these principles.

### Repository-Based Working

Development should take place through the relevant repository in the IES GitHub organisation.

Issues, proposals, branches, pull requests, review comments, approvals, and release records should be maintained in GitHub wherever appropriate to support transparency and traceability.

### Proportionate Review

Development work should be reviewed in proportion to its impact.

Minor documentation corrections, routine maintenance, and low-risk repository updates should not require the same level of review as changes affecting IES Top, IES Core, cross-domain alignment, public release, or governance arrangements.

### Traceability

Material changes should be traceable from proposal or issue through to review, approval, implementation, and release.

Where conceptual models, implementation artefacts, or serialised outputs are involved, the relationship between them should be clear. Where implementation constraints require divergence from a conceptual source, that divergence should be documented and justified.

### Technical Coherence

Development should preserve the technical coherence of IES.

Domain-driven repositories should build from, extend, or align with IES Top and IES Core. Changes that affect those repositories should be considered for their impact on domain-driven repositories and wider interoperability.

### Appropriate Authority

Repository permissions do not replace governance authority.

A person may have technical permission to make a change in GitHub, but that change must still follow the relevant governance, review, and approval process.

### Security and Access Control

Development activity must respect repository-level security, access control, and assurance requirements.

Repository-specific requirements take precedence where they impose stricter controls on access, disclosure, review, or release.

---

## Repository Expectations

Each repository in the IES GitHub organisation is expected to maintain repository-level documentation that is consistent with the IES governance framework.

Repository-level documentation should identify:

* what the repository contains
* what type of repository it is
* who is responsible for it
* where maintainer information is recorded
* how issues and proposed changes should be raised
* how development and review are managed
* any repository-specific security, access, assurance, or release requirements

Repository Maintainer information is maintained in the relevant repository’s maintainer file, not centrally in this governance repository.

---

## Development Routes

Development may arise through several routes, including:

* issues raised in the relevant repository
* proposals made through the proposal process
* domain-driven development led by a Domain Working Group
* maintenance activity by IES Top (Layer 0) Ontology Maintainers and IES Core (Layer 1) Ontology Maintainers or Repository Maintainers
* governance or documentation updates
* release preparation activity

The appropriate route depends on the type, scope, and impact of the change.

---

## Domain-Driven Development

Domain-driven development is led by the relevant Domain Working Group.

Domain-driven repositories are governed directly by the relevant Domain Working Group and should remain aligned with IES Top and IES Core.

Where domain-driven development identifies a required change to IES Top or IES Core, that change must follow the relevant proposal, review, and approval process.

---

## Development Affecting IES Top or IES Core

IES Top and IES Core are maintained by the IES Top (Layer 0) Ontology Maintainers and IES Core (Layer 1) Ontology Maintainers.

Changes affecting IES Top or IES Core require particular care because they may affect multiple domain-driven repositories.

Routine maintenance may be handled by the IES Top (Layer 0) Ontology Maintainers and IES Core (Layer 1) Ontology Maintainers where it does not materially alter the structure, meaning, or cross-domain behaviour of IES Top or IES Core.

Material changes must follow the relevant proposal, review, and approval process. Changes with strategic, cross-domain, high-impact, or disputed implications must be escalated to the Steering Group.

---

## GitHub Working Practices

Development should use GitHub working practices that support transparent and traceable collaboration.

This may include:

* creating issues for problems, questions, or proposed changes
* using branches for development work
* using pull requests for review and approval
* applying branch protection and review requirements where appropriate
* documenting decisions and approvals in issues, pull requests, release notes, or relevant governance records
* keeping repository documentation up to date

People with repository permissions are expected to understand the GitHub workflows and access controls relevant to their role.

---

## Contents

* [Development Rules](./development-rules.md)
* [Repository Naming](./repository-naming.md)
