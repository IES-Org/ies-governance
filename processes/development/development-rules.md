# Development Rules

This document defines the rules for development activity within IES, the Information Exchange Standard.

It applies to repositories within the IES GitHub organisation, including IES Top, IES Core, domain-driven repositories, and administrative repositories.

---

## Core Rule

Official IES development must take place within the IES GitHub organisation.

Work carried out outside the IES GitHub organisation, including work on local machines, private forks, private repositories, or external systems, may support discussion, experimentation, or preparation. It is not part of the official approved state of IES unless it is proposed, reviewed, accepted, and merged through the relevant IES governance and development processes.

---

## Development Principles

Development activity must support:

* transparency
* traceability
* technical coherence
* proportionate review
* appropriate governance approval
* repository-level accountability
* clear distinction between official and informal material

Repository permissions do not replace governance authority. A person may have technical permission to make a change in GitHub, but that change must still follow the relevant governance, review, and approval process.

---

## Repository-Based Working

Development should be managed through the relevant repository in the IES GitHub organisation.

Where appropriate, development activity should use:

* GitHub issues for problems, questions, requests, or proposed changes
* branches for development work
* pull requests for review and approval
* review comments to record discussion and feedback
* release notes or changelogs to record material changes
* repository-level documentation to explain the content, purpose, status, and maintenance arrangements of the repository

General issues and proposed changes should normally be raised through GitHub issues or pull requests rather than through direct contact with individual maintainers. This supports transparency and traceability.

Security matters must not be raised through public GitHub issues. They must follow the relevant repository security process.

---

## Mandatory Repository Documentation

Each repository within the IES GitHub organisation must maintain repository-level documentation appropriate to its purpose, status, and risk.

Before a repository is made public, it must go through the public release process and must have the required documentation completed.

A public IES repository should normally include:

* `README.md`
* `CONTRIBUTING.md`
* `CODE_OF_CONDUCT.md`
* `SECURITY.md`
* `MAINTAINERS.md`
* `CHANGELOG.md`
* `VERSION`
* `LICENSE.md`
* `OGL_LICENSE.md`
* `NOTICE.md`
* `ACKNOWLEDGEMENTS.md`

Additional repository-specific documentation may be required depending on the type of repository.

---

## README

Each repository must include a `README.md`.

The README should explain:

* the name and purpose of the repository
* what the repository contains
* whether the repository contains ontology content or administrative material
* how the repository relates to IES
* where users can find key documentation
* how users can raise issues or provide feedback
* licensing and contribution information where appropriate

The README should be written for users who may arrive at the repository without prior knowledge of the wider IES structure.

---

## Maintainer Information

Each repository must include a `MAINTAINERS.md` file.

The maintainer file should identify:

* the people or role-holders responsible for the repository
* their organisations where appropriate
* their GitHub usernames or relevant contact routes
* their areas of responsibility
* how general issues should be raised
* how unresolved issues may be escalated

Repository Maintainer information is maintained in the relevant repository, not centrally in the governance repository.

For IES Top and IES Core, the relevant maintainers are the IES Top (Layer 0) Ontology Maintainers and IES Core (Layer 1) Ontology Maintainers. Current IES Top (Layer 0) Ontology Maintainers and IES Core (Layer 1) Ontology Maintainers are recorded centrally in the governance repository, but repository-level maintainer files should still explain how maintenance operates for the specific repository.

---

## Security Documentation

Each public repository must include a `SECURITY.md` file.

The security file should explain:

* how security concerns should be reported
* that security vulnerabilities must not be raised through public GitHub issues
* what information should be included in a vulnerability report
* what the expected acknowledgement route or timeframe is, where applicable
* what is in scope and out of scope for the repository
* any repository-specific security requirements

Repository-level security requirements may be stricter than the general IES governance framework and must be followed where they apply.

---

## Contribution Documentation

Each public repository must include a `CONTRIBUTING.md` file.

The contribution file should explain:

* how users can raise issues
* how users can suggest documentation improvements
* whether pull requests are accepted
* whether direct contributions are limited to approved contributors
* how contribution licensing is handled
* where users can find maintainer or contact information

The contribution model must be consistent with the repository’s governance status. Where public pull requests are not accepted, this must be stated clearly.

---

## Code of Conduct

Each public repository must include a `CODE_OF_CONDUCT.md` file.

The Code of Conduct should explain the expected behaviour for people interacting with the repository, including users, contributors, maintainers, and public participants.

It should cover:

* respectful and professional communication
* constructive feedback
* unacceptable behaviour
* reporting routes
* enforcement or escalation arrangements
* the scope of the Code of Conduct

---

## Licensing and Notices

Each public repository must include licensing and notice documentation appropriate to its contents.

Where a repository contains both code and documentation, it should distinguish between the applicable licences.

A public IES repository should normally include:

* `LICENSE.md` for code or software licence terms
* `OGL_LICENSE.md` for Open Government Licence terms applying to documentation
* `NOTICE.md` for attribution, copyright, and legal notices
* `ACKNOWLEDGEMENTS.md` where organisational or individual contributions should be recognised

Repository-level licensing must be clear before a repository is made public.

---

## Version and Change Records

Each public repository must include a `VERSION` file and should maintain a `CHANGELOG.md`.

The `VERSION` file should identify the current version of the repository or release.

The changelog should record material changes in a way that supports traceability. This may include:

* ontology changes
* documentation changes
* repository structure changes
* release changes
* corrections or clarifications
* breaking changes
* security-relevant changes where appropriate

Versioning and changelog practices should be consistent with the relevant release process.

---

## Ontology Development

Ontology development must preserve the technical coherence of IES.

Domain-driven repositories must build from, extend, or align with IES Top and IES Core.

Changes to domain-driven repositories are governed directly by the relevant Domain Working Group. Where a domain-driven change identifies a required change to IES Top or IES Core, that change must follow the relevant proposal, review, and approval process.

---

## Development Affecting IES Top or IES Core

IES Top and IES Core are maintained by the IES Top (Layer 0) Ontology Maintainers and IES Core (Layer 1) Ontology Maintainers.

Changes to IES Top or IES Core require particular care because they may affect multiple domain-driven repositories.

Routine maintenance may be handled by the IES Top (Layer 0) Ontology Maintainers and IES Core (Layer 1) Ontology Maintainers where it does not materially alter the structure, meaning, or cross-domain behaviour of IES Top or IES Core.

Material changes must follow the relevant proposal, review, and approval process.

Changes with strategic, cross-domain, high-impact, or disputed implications must be escalated to the Steering Group.

---

## Conceptual Models and Implementation Artefacts

Where conceptual models, implementation artefacts, or serialised outputs are used, the relationship between them should be clear and traceable.

For ontology repositories, this may include relationships between:

* conceptual models
* UML or other modelling artefacts
* RDF or other serialised ontology outputs
* documentation
* examples
* release artefacts

Where implementation constraints require divergence from a conceptual source, the divergence should be documented and justified.

Conceptual or implementation artefacts that form part of IES must be maintained within the IES GitHub organisation or otherwise be formally approved and traceable through IES governance processes.

---

## GitHub Capability

People with repository permissions must have sufficient GitHub capability to perform their role responsibly.

This includes understanding, where relevant:

* issues
* branches
* pull requests
* code review
* merge behaviour
* protected branches
* branch protection rules
* repository permissions
* release tags
* repository visibility
* security reporting routes

People with elevated permissions must understand the implications of the permissions they hold.

---

## Branching and Pull Requests

Development should normally use branches and pull requests.

Branching and pull request practices should be proportionate to the repository and type of change.

Repositories should define or follow appropriate expectations for:

* branch naming
* when a branch should be created
* when a pull request is required
* who should review a pull request
* how approval is recorded
* when a pull request may be merged
* whether branch protection applies
* how urgent fixes are handled

Changes should not be merged into protected or release branches unless the relevant review and approval requirements have been met.

---

## Review and Approval

Review and approval must be proportionate to the impact of the change.

Low-risk changes, such as minor documentation corrections or routine repository maintenance, may require a lighter review route.

Material changes require more formal review. This includes changes that affect:

* IES Top
* IES Core
* cross-domain alignment
* domain-driven ontology meaning or structure
* repository security
* public release readiness
* governance documentation
* licensing or public-facing commitments

Approval must be recorded in an appropriate place, such as a pull request, issue, release note, meeting record, or governance decision record.

---

## Public Release Readiness

A repository must not be made public until it has completed the relevant public release process.

Before a repository is made public, it must be checked for:

* complete mandatory documentation
* accurate repository description
* appropriate licensing
* appropriate security documentation
* complete maintainer information
* appropriate version and changelog information
* removal of sensitive or unsuitable material
* appropriate repository visibility and access settings
* consistency with the IES governance framework
* consistency with repository naming rules

Public repositories should be understandable to users who are not already involved in IES governance or development.

---

## Repository Status

Repositories should make their status clear.

A repository may be:

* active
* in development
* archived
* deprecated
* superseded
* released
* experimental, where permitted by governance

Where a repository is not an official release, this should be clear to users.

Where a repository is archived, deprecated, or superseded, the repository should explain where users should go for the current approved material.

---

## Access and Permissions

Repository access must be proportionate to the role being performed.

Repository permissions should be granted only where they are needed and should be reviewed when a person:

* changes role
* leaves a role
* no longer requires access
* has a conflict of interest that affects access
* no longer meets the expectations of the role
* presents a security, governance, or operational concern

Elevated permissions must be limited to those who require them.

Repository permissions must not be used to bypass governance, review, approval, or release requirements.

---

## Records and Traceability

Development records should be sufficient to explain what changed, why it changed, who reviewed it, who approved it, and where it was released.

Depending on the change, records may include:

* issues
* proposals
* pull requests
* review comments
* commit messages
* changelog entries
* version tags
* release notes
* meeting notes
* governance decision records

Material changes should be traceable from proposal or issue through to implementation and release.

---

## Escalation

Development issues should be resolved at the lowest appropriate level.

Escalation may be required where:

* a change affects IES Top or IES Core
* a change has cross-domain implications
* a proposal is disputed
* a repository-level issue cannot be resolved by maintainers
* a security or access concern arises
* a change affects governance documentation or public release
* repository funding, access, availability, or continuity is at risk
* a matter requires Steering Group decision

Escalated matters should be taken through the relevant governance route.

---

## Relationship with Other Processes

Development activity should align with the relevant IES processes.

More information is available in:

* [Proposal Lifecycle](../proposals/proposal-lifecycle.md)
* [Proposal Template](../proposals/proposal-template.md)
* [Repository Naming](./repository-naming.md)
* [Release Process](../public-release/release-process.md)

