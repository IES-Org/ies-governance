# Repository Naming

This document defines the naming rules for repositories within the IES GitHub organisation.

Repository names should make clear what the repository contains, what type of repository it is, and where responsibility for the repository sits.

---

## Purpose

The purpose of repository naming rules is to support consistency, navigation, accountability, and discoverability across the IES GitHub organisation.

Repository names should help users and contributors understand:

* whether a repository contains ontology content or administrative material
* whether it relates to IES Top, IES Core, a domain-driven extension, or governance activity
* which domain or group is responsible for the repository
* how the repository relates to other IES repositories

---

## General Naming Rules

Repository names must be clear, descriptive, and consistent.

Repository names should:

* use lower-case letters
* use hyphens to separate words
* avoid spaces, underscores, and special characters
* avoid abbreviations unless they are established within IES
* avoid names that are ambiguous or likely to become misleading
* reflect the purpose and responsibility of the repository

Repository names should be stable once created. A repository should only be renamed where there is a clear governance, technical, or usability reason to do so.

---

## Repository Categories

IES repositories are organised into four broad categories:

* IES Top
* IES Core
* domain-driven repositories
* administrative repositories

Each category has its own naming pattern.

---

## IES Top

IES Top is maintained in the `ies-top` repository.

There must only be one repository for IES Top.

The repository name is:

```text
ies-top
```

IES Top is maintained by the L0 Ontology Maintainers.

---

## IES Core

IES Core is maintained in the `ies-core` repository.

There must only be one repository for IES Core.

The repository name is:

```text
ies-core
```

IES Core is maintained by the L1 Ontology Maintainers.

---

## Domain-Driven Repositories

Domain-driven repositories contain ontology content developed for a specific domain.

Domain-driven repository names must indicate the Domain Working Group responsible for the repository. The domain element in the repository name identifies the domain under whose governance the repository is developed and maintained.

The standard naming pattern is:

```text
ies-[responsible-domain]-[repository-purpose]
```

Where:

* `ies` identifies the repository as part of the IES GitHub organisation
* `[responsible-domain]` identifies the responsible Domain Working Group
* `[repository-purpose]` identifies the content, extension, package, or purpose of the repository

The exact repository purpose should be chosen to make the content of the repository clear.

---

## Domain Authority

A repository name must not imply that a domain exists, or that a repository is governed by a Domain Working Group, unless that Domain Working Group has been formally established.

A domain-driven repository must be developed under the authority of the Domain Working Group identified in the repository name. A group must not create or publish a repository in the name of another domain where that domain has not been established or is not responsible for the work.

This prevents repository names from creating the appearance of domain authority where none exists.

---

## Emerging Domain Needs

A need for domain-specific material may arise before the relevant Domain Working Group exists.

Where this happens, the work should be named and governed under the Domain Working Group that is actually responsible for developing it. The repository name should make clear the responsible domain and the perspective from which the work is being developed.

For example, where an established Domain Working Group develops material relating to another potential domain because it is relevant to its own use case, the repository name should identify the established Domain Working Group as the responsible domain. It should not imply that the work has been developed, reviewed, or approved by a Domain Working Group that does not yet exist.

This avoids:

* creating the appearance of domain authority where none exists
* implying subject matter expert review by a Domain Working Group that does not exist
* proliferating unmanaged or unsupported domain namespaces
* creating repositories without a Chair, Representative, or organisational backing
* weakening accountability for domain-driven development

Where the relevant Domain Working Group is later established, suitable material may be reviewed, adopted, transferred, renamed, or superseded through the appropriate governance process.

---

## Domain Names

Domain names used in repository names should match the relevant Domain Working Group name or agreed short form.

Where a new Domain Working Group is established, its repository naming convention should be agreed as part of the formation of the group.

A domain name should be:

* short
* clear
* stable
* understandable to users outside the Domain Working Group
* consistent across repositories managed by the same Domain Working Group

Where a domain name changes, the impact on repository names should be considered carefully before any repository is renamed.

---

## Repository Purpose

The repository purpose element should be short but meaningful.

It may describe, for example:

* a domain extension
* an ontology package
* examples or test material
* governance documentation
* public release material
* roadmap or planning information
* supporting documentation

The purpose element should not duplicate information already clear from the domain name unless this improves clarity.

---

## Administrative Repositories

Administrative repositories contain governance, management, planning, coordination, or informational material relating to IES.

Administrative repository names should identify the administrative function they support.

The standard naming pattern is:

```text
ies-[administrative-purpose]
```

Examples:

```text
ies-governance
ies-roadmap
ies-documentation
```

Administrative repositories must not be named in a way that implies they contain ontology content unless they do.

---

## Creating a New Repository

A new repository should only be created where there is a clear need and an agreed responsible group or function.

Before creating a repository, the following should be identified:

* the repository category
* the proposed repository name
* the responsible Domain Working Group, governance group, or function
* the purpose of the repository
* whether the repository will contain ontology content
* whether the repository is expected to become public
* the initial repository-level maintainer arrangements
* any security, access, or publication requirements

For domain-driven repositories, the responsible Domain Working Group must already be established. A repository must not be created in the name of a domain that does not yet have the governance arrangements needed to own and maintain the work.

Repository creation should follow the relevant IES governance and development processes.

---

## Renaming a Repository

Repository renaming should be avoided unless there is a clear reason.

A repository may be renamed where:

* the current name is misleading
* the responsible domain or function has changed
* the repository purpose has materially changed
* the repository naming no longer aligns with IES naming rules
* a rename would significantly improve clarity or discoverability
* material is adopted, transferred, or superseded by a newly established Domain Working Group

Before renaming a repository, the impact should be considered on:

* links
* issues
* pull requests
* documentation
* release references
* dependent repositories
* external users
* the Ontology Index

Repository renaming should be documented in the relevant repository and reflected in the Ontology Index.

---

## Archived, Deprecated, and Superseded Repositories

Repository names should not be changed solely because a repository is archived, deprecated, or superseded.

Instead, the repository status should be made clear in the repository documentation.

Where a repository is archived, deprecated, or superseded, the repository should explain:

* its current status
* whether it should still be used
* what repository or release supersedes it, where applicable
* where users should go for current approved material

The Ontology Index should also be updated where repository status changes.

---

## Public Repository Naming

Before a repository is made public, its name must be reviewed as part of the public release process.

The name must be:

* consistent with these naming rules
* clear to users outside the IES contributor community
* consistent with the repository contents
* consistent with the repository description and README
* reflected accurately in the Ontology Index

A repository must not be made public with a temporary, unclear, misleading, or internally meaningful name.

A domain-driven repository must not be made public with a name that implies governance by a Domain Working Group that has not been formally established.

---

## Relationship with the Ontology Index

The Ontology Index records IES repositories and their categories.

When a repository is created, renamed, archived, deprecated, superseded, or made public, the Ontology Index should be reviewed and updated where required.

The Ontology Index should identify:

* the repository name
* the repository category
* the responsible domain, group, or function
* the repository purpose
* the repository status
* where repository-level maintainer information can be found

---

## Notes

* `ies-top` is reserved for IES Top.
* `ies-core` is reserved for IES Core.
* Domain-driven repositories must identify the responsible Domain Working Group in the repository name.
* A repository name must not imply governance by a Domain Working Group that has not been formally established.
* Work relating to an emerging domain should be named under the established Domain Working Group responsible for developing it.
* Administrative repositories should identify the administrative function they support.
* Repository names should be stable, clear, and consistent.
* Repository names must be reviewed before repositories are made public.
