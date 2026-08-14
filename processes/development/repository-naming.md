## Purpose

The purpose of repository naming rules is to support consistency, navigation, accountability, and discoverability across the IES GitHub organisation.

Repository names should help users and contributors understand:

* whether a repository contains ontology content or administrative material
* whether it relates to IES Top, IES Core, a domain-driven extension, or governance activity
* the domain or sub-domain to which an ontology extension relates
* how the repository relates to other IES repositories

Responsibility for a repository should be recorded separately from the domain or sub-domain represented by its name.

---

## Repository Categories

IES repositories are organised into four broad categories:

* IES Top
* IES Core
* domain-driven repositories
* administrative repositories

Each category has its own naming pattern.

---

## Domain-Driven Repositories

Domain-driven repositories contain ontology content developed to extend IES for a particular domain or sub-domain.

The domain represented by a repository is distinct from the Domain Working Group responsible for undertaking or governing the work. A Domain Working Group may develop ontology extensions relating to domains other than the area from which the working group takes its name.

Domain and sub-domain naming should be aligned to the UNESCO Thesaurus group structure. This provides a common, stable and enduring taxonomy against which IES domain extensions can be organised, while allowing that taxonomy to evolve independently of the organisational structure of IES Domain Working Groups.

The standard naming pattern is:

```text
ies-[domain]
```

Where:

* `ies` identifies the repository as part of the IES GitHub organisation
* `[domain]` identifies the applicable domain or sub-domain derived from the UNESCO Thesaurus group structure

The domain element should be kept short. Where the UNESCO Thesaurus term would result in an unnecessarily long repository name, an agreed abbreviated form may be used, provided that its relationship to the applicable UNESCO Thesaurus grouping is documented.

For example, ontology work concerning building materials in the context of EPC data may map to the UNESCO Thesaurus grouping **Materials and products (6.55)**. An agreed shortened form may therefore result in the repository name:

```text
ies-matprod
```

This work might, for example, be undertaken by the Environment Domain Working Group because it arises from an environmental use case. The repository name nevertheless identifies the domain extension being developed, rather than the Domain Working Group undertaking the work.

A different Domain Working Group could undertake work relating to the same domain where appropriate. Conversely, a single Domain Working Group may undertake extension work across several domains or sub-domains.

The applicable UNESCO Thesaurus grouping and the Domain Working Group or other group responsible for the work should be recorded in the repository documentation and Ontology Index.

---

## Domain Authority

Ontology domains and Domain Working Groups are separate concepts within IES governance.

A domain or sub-domain identifies an area of ontology extension. A Domain Working Group is an organisational mechanism through which contributors may coordinate, govern and undertake development work.

The existence of a domain-based extension does not require the existence of a corresponding Domain Working Group. Likewise, the name of a Domain Working Group does not restrict that group to developing ontology content only within a related domain.

A formally established Domain Working Group may undertake development of an extension for another domain or sub-domain where there is an identified need for the extension and the work falls within the group's agreed activities and governance arrangements.

Repository names must therefore identify the domain or sub-domain represented by the ontology extension and must not be used to encode the identity of the Domain Working Group responsible for the work.

Responsibility and accountability for the repository must instead be recorded through the relevant repository documentation, maintainer arrangements and Ontology Index.

---

## Emerging Domain Needs

A need for a domain or sub-domain extension may arise without a dedicated Domain Working Group existing for that domain.

The absence of such a Domain Working Group should not prevent necessary ontology development from taking place.

Where an established Domain Working Group identifies a requirement for an extension relating to another domain or sub-domain, it may undertake that work through the appropriate IES governance and development processes. The repository should be named according to the domain or sub-domain being extended, using the applicable UNESCO Thesaurus grouping, rather than according to the Domain Working Group undertaking the work.

For example, the Environment Domain Working Group may identify a requirement arising from an environmental use case for ontology content relating to a domain that would not naturally be regarded as an environment domain. Where appropriate, the Environment Domain Working Group may nevertheless undertake that development without requiring a new Domain Working Group to be established solely for that purpose.

This separation allows necessary ontology domains and sub-domains to be developed:

* without requiring a one-to-one relationship between domains and Domain Working Groups
* without requiring a dedicated Domain Working Group to be established before necessary extension work can begin
* while retaining clear accountability for the group undertaking and maintaining the work
* without coupling the ontology extension taxonomy to the organisational structure of IES
* while allowing responsibility for an extension to change without necessarily requiring the repository to be renamed

Where a dedicated Domain Working Group is subsequently established, responsibility for relevant extension material may be reviewed, transferred or shared through the appropriate governance process. Such a change in responsibility does not, by itself, require the repository or domain extension to be renamed.

---

## Domain Names

Domain and sub-domain names used in repository names should be aligned to the relevant UNESCO Thesaurus grouping.

A domain name should be:

* short
* clear
* stable
* understandable to users outside the Domain Working Group responsible for the work
* traceable to the applicable UNESCO Thesaurus grouping
* consistent with the wider IES domain extension taxonomy

Where the full UNESCO Thesaurus label would result in an unnecessarily long repository name, an agreed short form should be used.

For example:

```text
Materials and products (6.55) → matprod
```

resulting in:

```text
ies-matprod
```

The mapping between the repository name and its UNESCO Thesaurus grouping should be recorded so that the basis of the domain taxonomy remains explicit and consistently applied.

Domain names should remain stable once established. Where the UNESCO Thesaurus evolves, the impact on the IES domain taxonomy and existing repository names should be considered carefully before any repository is renamed.

A change to the Domain Working Group responsible for a repository does not constitute a change to the domain represented by the repository.

---

## Creating a New Repository

A new repository should only be created where there is a clear need and an agreed responsible group or function.

Before creating a repository, the following should be identified:

* the repository category
* the proposed repository name
* for a domain-driven repository, the applicable UNESCO Thesaurus grouping and any agreed short form
* the responsible Domain Working Group, governance group, or function
* the purpose of the repository
* whether the repository will contain ontology content
* whether the repository is expected to become public
* the initial repository-level maintainer arrangements
* any security, access, or publication requirements

For domain-driven repositories, there must be an established group or governance arrangement responsible for developing and maintaining the work. There does not need to be a Domain Working Group corresponding to the domain or sub-domain represented by the repository.

Repository creation should follow the relevant IES governance and development processes.

---

## Relationship with the Ontology Index

The Ontology Index records IES repositories and their categories.

When a repository is created, renamed, archived, deprecated, superseded, or made public, the Ontology Index should be reviewed and updated where required.

The Ontology Index should identify:

* the repository name
* the repository category
* for domain-driven repositories, the applicable UNESCO Thesaurus grouping
* the responsible Domain Working Group, group, or function
* the repository purpose
* the repository status
* where repository-level maintainer information can be found

Where an abbreviated domain or sub-domain name is used in a repository name, the Ontology Index should record its relationship to the applicable UNESCO Thesaurus grouping.

The domain classification and the group responsible for the repository should be recorded separately.

---

## Notes

* `ies-top` is reserved for IES Top.
* `ies-core` is reserved for IES Core.
* Domain-driven repositories identify the domain or sub-domain being extended rather than the Domain Working Group responsible for the work.
* Domain and sub-domain naming should be aligned to the UNESCO Thesaurus group structure.
* Agreed shortened forms may be used to keep repository names concise, provided that their relationship to the UNESCO Thesaurus is documented.
* Ontology domains and Domain Working Groups are separate concepts and do not have a one-to-one relationship.
* A Domain Working Group may undertake extension work relating to domains or sub-domains other than the area from which the working group takes its name.
* A domain extension does not require a dedicated Domain Working Group to exist before the extension can be developed.
* Responsibility for a domain-driven repository must be recorded separately from its domain classification.
* Administrative repositories should identify the administrative function they support.
* Repository names should be stable, clear, and consistent.
* Repository names must be reviewed before repositories are made public.
