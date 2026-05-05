# Release Process

This document defines the process for making IES repositories, artefacts, documentation, and releases publicly available.

It describes how public release readiness is assessed, approved, implemented, and recorded.

---

## Purpose

The purpose of this process is to ensure that material published publicly as part of IES is accurate, authorised, appropriately documented, and consistent with the IES governance framework.

The release process supports:

* clear public-facing information
* appropriate governance approval
* completed mandatory repository documentation
* appropriate licensing and notices
* security and access review before publication
* traceability between development, approval, and release
* consistency across repositories in the IES GitHub organisation

No repository, artefact, or release should be made public as an official IES output unless it has completed the relevant release process.

---

## Scope

This process applies to public release activity within the IES GitHub organisation.

It may apply to:

* IES Top
* IES Core
* domain-driven repositories
* administrative repositories
* ontology artefacts
* documentation
* examples and supporting material
* release notes
* governance documentation
* repository status changes
* public-facing website or publication material

This process applies both to repositories being made public for the first time and to subsequent official releases of material already held in public repositories.

---

## Core Principle

The IES GitHub organisation is the authoritative source for official IES governance documentation, approved development activity, ontology content, and public releases.

Public release must therefore be managed through the IES GitHub organisation and recorded through the appropriate repository, governance, and release records.

Material developed outside the IES GitHub organisation is not part of an official IES release unless it is proposed, reviewed, accepted, and published through the relevant IES governance and development processes.

---

## Release Types

Public release activity may include different types of release.

### Initial Public Repository Release

An initial public repository release occurs when a repository is made publicly visible for the first time.

This requires review of repository name, repository purpose, mandatory documentation, licensing, security arrangements, maintainer information, and public-facing content.

### Versioned Release

A versioned release occurs when a repository publishes a specific release version.

This may include ontology artefacts, documentation, examples, release notes, changelog entries, tags, or other release artefacts.

### Documentation Release

A documentation release occurs when governance, user guidance, technical guidance, or repository documentation is published or materially updated.

Minor documentation corrections may not require a formal release process unless they affect public commitments, governance meaning, licensing, security, or technical interpretation.

### Corrective Release

A corrective release occurs where a published repository, artefact, or document needs to be corrected.

This may be required because of an error, omission, security concern, broken reference, incorrect release artefact, or misleading public-facing information.

### Superseding or Deprecation Release

A superseding or deprecation release occurs where an existing repository, artefact, or release is replaced, deprecated, archived, or marked as no longer current.

The repository or artefact should clearly indicate its status and direct users to the current approved material where applicable.

---

## When Release Approval is Required

Release approval is normally required where:

* a repository is made public for the first time
* a new official version is published
* a release affects IES Top or IES Core
* a release affects domain-driven ontology content
* a release has cross-domain implications
* a release changes public-facing governance documentation
* a release changes public-facing technical documentation
* a release changes licensing, notices, attribution, or security documentation
* a repository is archived, deprecated, superseded, or withdrawn
* a corrective release is required for material public-facing content
* a release has strategic, operational, legal, security, or reputational implications

Routine minor updates in a public repository may be managed through the relevant development and repository-level workflow, provided they do not require formal release approval.

---

## Release Roles and Responsibilities

### Responsible Group or Function

Each release should have a responsible group or function.

Depending on the repository or artefact, this may be:

* a Domain Working Group
* the Common Ontology Maintainers
* Platform and Communications Management
* the Steering Group
* a repository-level maintainer group

The responsible group or function is accountable for ensuring that the release is ready for review and publication.

### Repository Maintainers

Repository Maintainers support release preparation for the repositories they maintain.

They may help ensure that repository documentation is complete, issues and pull requests are resolved, release notes are prepared, and repository-level requirements are met.

Repository Maintainer information is maintained in the relevant repository’s maintainer file.

### Domain Working Groups

Domain Working Groups are responsible for domain-driven releases within their domain.

They should ensure that domain-driven ontology content is appropriate, aligned with IES Top and IES Core, and supported by the necessary domain review.

### Common Ontology Maintainers

Common Ontology Maintainers are responsible for releases affecting IES Top and IES Core.

They should ensure that technical review has been completed, material changes have followed the appropriate proposal and approval route, and release artefacts are technically coherent.

### Platform and Communications Management

Platform and Communications Management supports the practical publication of releases.

This may include repository visibility, GitHub settings, release communication, public-facing navigation, website or domain publication arrangements, and checking that release material is accessible and appropriately presented.

### Steering Group

The Steering Group provides approval where a release has strategic, cross-domain, governance, high-impact, disputed, or public-interest implications.

The Steering Group must be involved where required by the governance framework or where the relevant release route cannot resolve an issue.

---

## Initial Public Repository Release Requirements

Before a repository is made public, it must be reviewed for public release readiness.

A repository should not be made public until the following have been completed where applicable:

* repository name has been reviewed against the repository naming rules
* repository description is clear and accurate
* repository purpose and status are clear
* responsible group or function is identified
* maintainer information is completed in the repository’s maintainer file
* mandatory repository documentation is present and filled in
* licensing and notice files are complete and appropriate
* security reporting information is present
* contribution information is clear
* code of conduct is present
* version and changelog information is present where required
* sensitive, unsuitable, private, or draft-only material has been removed
* issues, discussions, pull requests, and branches have been reviewed for suitability
* repository visibility and access settings have been checked
* branch protection and review requirements are appropriate
* public-facing links are checked
* Ontology Index entries are prepared or updated
* release communication requirements are identified

The repository should be understandable to users who are not already involved in IES governance or development.

---

## Mandatory Repository Documentation

Public repositories must include repository-level documentation appropriate to their purpose and status.

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

Additional documentation may be required depending on the repository category, content, risk, or release type.

Mandatory documentation must be completed before a repository is made public.

---

## Release Preparation

Before release, the responsible group or function should confirm that:

* the release scope is clear
* the repository or artefact status is clear
* relevant proposals or approvals have been completed
* relevant issues and pull requests have been resolved or documented
* required reviews have been completed
* release notes or changelog entries are prepared
* version information is correct
* licensing and notices are complete
* security and access requirements have been checked
* public-facing documentation is accurate
* relevant links are working
* the Ontology Index is updated or ready to be updated
* any communication activity is prepared

Where a release depends on another repository, process, proposal, or decision, the dependency should be resolved or recorded before release.

---

## Review and Approval

Release review should be proportionate to the release impact.

Review may involve:

* the responsible Domain Working Group
* Common Ontology Maintainers
* Repository Maintainers
* Platform and Communications Management
* the Steering Group
* security, legal, licensing, or communications reviewers where required

Approval must be recorded in an appropriate place.

This may include:

* Steering Group minutes
* Domain Working Group records
* GitHub issues
* pull requests
* release notes
* governance decision records
* repository-level release records

Where Steering Group approval is required, the decision is made by majority vote of the Voting Members unless a different rule applies in the relevant governance documentation. Where a vote is tied, the Steering Group Chair has the casting vote.

---

## Publication

Once release approval has been granted, publication may proceed through the appropriate route.

Publication may include:

* changing repository visibility to public
* creating a GitHub release
* applying a version tag
* merging release documentation
* publishing release notes
* updating the repository README
* updating the Ontology Index
* updating public-facing links
* publishing or updating website material
* communicating the release through agreed channels

Publication should be carried out by people with the appropriate permissions and should follow the agreed GitHub workflow.

---

## Versioning and Release Records

Repositories should maintain clear version and release records.

Where applicable, a release should include:

* version number
* release date
* release summary
* changelog entry
* release notes
* links to relevant issues, pull requests, proposals, or decisions
* details of breaking changes or compatibility considerations
* known limitations
* migration guidance where needed
* responsible group or function
* approval record

The `VERSION` file and `CHANGELOG.md` should be updated where relevant.

---

## Security and Sensitive Information

Security and sensitive information must be reviewed before public release.

Before release, the responsible group or function should confirm that the repository or artefact does not contain:

* credentials, keys, tokens, or secrets
* personal data that should not be published
* security-sensitive details that should not be public
* commercially sensitive material that should not be public
* material that is not appropriately licensed for publication
* internal-only comments, drafts, or working material
* unsuitable issues, pull requests, branches, or repository history where relevant

Security vulnerabilities must follow the relevant repository security process and must not be raised through public GitHub issues.

---

## Licensing, Notices, and Attribution

Licensing and notices must be complete and appropriate before public release.

The responsible group or function should confirm that:

* the applicable licence or licences are clear
* Open Government Licence material is identified where relevant
* code or software licence terms are clear where relevant
* copyright and attribution notices are included
* third-party material is identified and permitted
* acknowledgements are included where appropriate
* public-facing repository text does not create inconsistent licensing statements

Where licensing, legal, or attribution concerns arise, release should be delayed or escalated until they are resolved.

---

## Ontology Index Updates

The Ontology Index should be updated where public release affects the repository index.

This includes where a repository is:

* created
* made public
* renamed
* archived
* deprecated
* superseded
* transferred to a different responsible group or function
* changed in status
* changed in category

The Ontology Index should identify the repository category, responsible group or function, repository purpose, status, and where repository-level maintainer information can be found.

---

## Corrective Releases

A corrective release may be required where published material contains an error, omission, broken reference, unsuitable content, or misleading information.

Corrective releases should be proportionate to the issue.

Where the issue is minor, it may be corrected through the normal repository workflow.

Where the issue affects governance meaning, technical interpretation, licensing, security, release integrity, or public trust, the correction should be reviewed and approved through the appropriate governance route.

The correction should be recorded in the changelog or release notes where relevant.

---

## Deprecation, Archiving, and Supersession

Where a repository, artefact, or release is deprecated, archived, or superseded, this must be clear to users.

The repository or artefact should identify:

* its current status
* whether it should still be used
* what supersedes it, where applicable
* where users should go for current approved material
* whether support or maintenance has ended
* the date of deprecation, archiving, or supersession

The Ontology Index should be updated where relevant.

---

## Release Checklist

The following checklist may be used when preparing a public release.

```text
Repository or artefact:
[Name]

Release type:
[Initial public repository release / Versioned release / Documentation release / Corrective release / Deprecation or supersession / Other]

Responsible group or function:
[Name]

Release owner:
[Name]

Repository name reviewed:
[Yes / No / Not applicable]

Repository description reviewed:
[Yes / No / Not applicable]

Mandatory repository documentation complete:
[Yes / No / Not applicable]

Maintainer file complete:
[Yes / No / Not applicable]

Security file complete:
[Yes / No / Not applicable]

Licensing and notices complete:
[Yes / No / Not applicable]

Version file updated:
[Yes / No / Not applicable]

Changelog updated:
[Yes / No / Not applicable]

Release notes prepared:
[Yes / No / Not applicable]

Issues and pull requests reviewed:
[Yes / No / Not applicable]

Sensitive or unsuitable material checked:
[Yes / No / Not applicable]

Access and repository settings checked:
[Yes / No / Not applicable]

Branch protection checked:
[Yes / No / Not applicable]

Relevant approvals completed:
[Yes / No / Not applicable]

Ontology Index updated:
[Yes / No / Not applicable]

Public-facing links checked:
[Yes / No / Not applicable]

Communication requirements completed:
[Yes / No / Not applicable]

Approval record:
[Link or reference]

Release record:
[Link or reference]

Date completed:
[Date]

Notes:
[Notes]
```

---

## Escalation

Release issues should be escalated where:

* approval is unclear
* required documentation is incomplete
* licensing or legal concerns arise
* security or sensitive information concerns arise
* repository status is unclear
* repository naming is inconsistent with IES rules
* release readiness is disputed
* release affects IES Top or IES Core
* release has cross-domain implications
* release may affect public trust or official interpretation of IES
* operational continuity, access, or funding concerns affect publication

Escalated matters should be taken through the relevant governance route.

The Steering Group may act as the final authority where a release issue cannot be resolved through the relevant working level.

---

## Relationship to Other Processes

This process operates alongside:

* [Proposal Lifecycle](../proposals/proposal-lifecycle.md)
* [Proposal Template](../proposals/proposal-template.md)
* [Development Rules](../development/development-rules.md)
* [Repository Naming](../development/repository-naming.md)
* [Onboarding](../onboarding-offboarding/onboarding.md)
* [Offboarding](../onboarding-offboarding/offboarding.md)

Public release activity must align with the IES Charter, relevant role documentation, repository-level documentation, and the Ontology Index.

---

## Status

This document defines the current public release process for IES repositories, artefacts, documentation, and releases.

The process may evolve as IES governance, tooling, security requirements, and operational arrangements mature.
