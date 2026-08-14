# IES Top and IES Core Ontology Maintainers Overview

IES Top and IES Core provide the foundational ontology layers on which IES domain extensions depend. Because changes to either layer may have consequences across multiple domains, both maintainer roles are tightly governed and assigned only to suitably qualified individuals.

The same person may hold both roles, but this is not required. Appointment as an IES Top Ontology Maintainer does not confer responsibility for IES Core, and vice versa.

## Purpose

The purpose of the IES Top Ontology Maintainer and IES Core Ontology Maintainer roles is to protect the technical integrity, coherence, stability, and maintainability of their respective ontology layers.

L0 & L1 Maintainers support IES by:

* maintaining IES Top and IES Core
* reviewing proposed changes to IES Common
* assessing the impact of changes on domain-driven repositories
* supporting alignment between IES Common and domain-driven development
* implementing approved changes to IES Top and IES Core
* advising on ontology modelling, 4D principles, and technical consistency

Maintainers should act in the interests of IES as a whole, rather than those of any single domain, organisation, or repository.

## Scope of Responsibility

IES Top Ontology Maintainers are responsible for IES Top (Layer 0).

IES Core Ontology Maintainers are responsible for IES Core (Layer 1).

These responsibilities are assigned separately. Neither role automatically grants authority over the other ontology or over any domain extension.

Domain extensions sit below IES Top and IES Core and are maintained through their own domain-level governance and repository arrangements.

## Change Impact and Dependency Management

Changes to IES Top or IES Core may have downstream effects across some or all IES domain extensions. These effects may include changes to meaning, inheritance, constraints, compatibility, implementation behaviour, or interoperability.

Before progressing a material change, the relevant maintainers should:

* identify affected concepts, relationships, constraints, and dependencies
* evaluate the likely impact on existing domain extensions
* consult the relevant domain-managed technical teams where specialist assessment is required
* consider migration, compatibility, release, and implementation implications
* document significant risks, dependencies, and required follow-up actions
* ensure that the proposed change has been considered through the appropriate governance route

Where a change affects both IES Top and IES Core, the relevant maintainers should undertake a coordinated review.

## Domain-Originated Requirements

Domain extensions may occasionally identify a requirement for a change to IES Top, IES Core, or both.

Such requirements should be developed and assessed initially through the relevant domain-managed technical team. The technical team should define the requirement, provide supporting evidence, consider domain and cross-domain implications, and identify why the requirement cannot be addressed solely within the domain extension.

The proposal should then be promoted for consideration through the Advisory Members and progressed through the appropriate IES governance process.

IES Top and IES Core Ontology Maintainers should support the technical assessment of such proposals, but domain-managed technical teams and Advisory Members do not directly approve changes to IES Top or IES Core.

## Authority

IES Top Ontology Maintainers have authority to maintain IES Top within the limits of the IES governance framework.

IES Core Ontology Maintainers have equivalent authority for IES Core.

Maintainers may undertake routine maintenance that does not materially alter the ontology’s structure, meaning, behaviour, or downstream use.

Material changes must follow the relevant proposal, review, and approval process. Changes with strategic, cross-domain, high-impact, or disputed implications must be escalated to the Steering Group.

A maintainer for one ontology must not approve or implement a change to the other ontology solely by virtue of holding their existing role.

## Relationship with the Steering Group

The Steering Group provides strategic oversight and governance direction for IES.

IES Top and IES Core Ontology Maintainers advise the Steering Group on the technical implications of proposed changes within their respective areas of responsibility. This may include identifying risks, evaluating downstream effects, recommending technical approaches, and implementing changes approved through the appropriate governance route.

The Steering Group must be involved where a proposed change has strategic, cross-domain, high-impact, or disputed implications.

## Relationship with Advisory Members

Advisory Members provide a route through which domain-originated requirements may be promoted for wider consideration.

Where a domain-managed technical team identifies a requirement affecting IES Top or IES Core, the proposal should be raised through the Advisory Members with sufficient technical justification and impact analysis to support informed consideration.

Advisory Members may advise on priority, relevance, cross-domain significance, and the appropriate governance route. They do not directly maintain or approve changes to IES Top or IES Core.

## Relationship with Domain Working Groups and technical teams

Domain Working Groups provide direction and oversight for domain-driven development.

Domain-managed technical teams are responsible for developing, maintaining, and evaluating technical changes within their domain extensions. They should also identify and document any dependency on a change to IES Top or IES Core.

IES Top and IES Core Ontology Maintainers should engage with these teams where:

* a proposed foundational change may affect one or more domain extensions
* a domain-originated proposal requires technical review
* specialist domain knowledge is needed to assess impact
* coordinated migration or implementation activity may be required

Domain Working Groups and their technical teams do not directly govern changes to IES Top or IES Core.

## Relationship with Repository Maintainers

Repository Maintainers are responsible for maintaining specific IES repositories.

The IES Top Ontology Maintainer and IES Core Ontology Maintainer roles are distinct from ordinary repository maintenance. A person may hold both roles where separately appointed, but repository permissions alone do not confer ontology governance authority.

Repository Maintainer information is maintained in the relevant repository’s maintainer file.

IES Top Ontology Maintainer and IES Core Ontology Maintainer information is maintained centrally in this governance repository.

## Technical Expectations

IES Top Ontology Maintainers should have strong expertise in:

* ontology engineering
* 4D modelling principles
* IES Top
* the relationship between IES Top and IES Core
* domain-extension dependencies
* version control and repository-based development
* interoperability, compatibility, and change-impact assessment

IES Core Ontology Maintainers should have corresponding expertise in IES Core and its relationship with IES Top and domain extensions.

Both roles require the ability to assess changes in the context of the wider IES ecosystem, including their potential downstream effects across multiple domains.

## Access and Permissions

IES Top Ontology Maintainers have access and permissions appropriate to maintaining IES Top.

IES Core Ontology Maintainers have access and permissions appropriate to maintaining IES Core.

Access to one ontology should not automatically provide maintenance permissions for the other.

Permissions should remain proportionate to the role and should be reviewed when a maintainer leaves the role, changes responsibilities, no longer requires access, or becomes subject to a relevant governance, security, or operational review.

## Public Record

Current and past maintainers are recorded centrally and separately for each ontology.

Current and historic records are maintained in:

* Current IES Top Ontology Maintainers
* Past IES Top Ontology Maintainers
* Current IES Core Ontology Maintainers
* Past IES Core Ontology Maintainers

Membership rules are defined in:

* IES Top Ontology Maintainer Membership
* IES Core Ontology Maintainer Membership

