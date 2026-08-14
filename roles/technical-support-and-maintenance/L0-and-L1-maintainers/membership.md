# IES Top and IES Core Ontology Maintainer Membership

This document defines the membership model for IES Top Ontology Maintainers and IES Core Ontology Maintainers.

It describes eligibility, appointment, responsibilities, participation expectations, access arrangements, review and removal. It also defines how current and past maintainers are recorded.

## Membership Model

IES Top Ontology Maintainers are responsible for maintaining IES Top (Layer 0).

IES Core Ontology Maintainers are responsible for maintaining IES Core (Layer 1).

These are separate roles. An individual may be appointed to either or both, but appointment to one role does not confer responsibility, authority or repository permissions for the other.

Maintainers provide technical stewardship of the ontology layer for which they are appointed. They must act in the interests of IES as a whole, rather than those of any single domain, organisation or repository.

Maintainers appointed to the same ontology share responsibility for that ontology. Individuals may take the lead in particular areas of expertise, but this does not create exclusive ownership of any part of IES Top or IES Core.

The number and composition of maintainers should remain proportionate to the needs of IES and provide sufficient resilience, continuity and technical oversight.

Across the IES Top and IES Core maintainer roles, there must be at least one public sector representative.

## Eligibility

A candidate must have the technical expertise, judgement and practical capability required to maintain the ontology layer for which they are being considered within the IES GitHub organisation.

All candidates should have a strong understanding of:

* ontology engineering
* foundational and extensional ontology principles
* 4D modelling principles
* RDF ontology implementation
* domain-driven extensions
* GitHub-based version control and repository development
* issue management, pull requests, branching and review workflows
* repository access controls and the responsible use of elevated permissions
* the effects of ontology changes on interoperability, compatibility and maintainability
* the relationship between conceptual models and implementation artefacts

An IES Top Ontology Maintainer should have strong expertise in:

* IES Top
* its role as Layer 0
* its relationship with IES Core
* the potential downstream effects of changes across IES Core and domain extensions

An IES Core Ontology Maintainer should have strong expertise in:

* IES Core
* its role as Layer 1
* its dependency on IES Top
* the potential downstream effects of changes across domain extensions

A candidate must be capable of assessing proposed changes in the context of the wider IES ecosystem and working effectively within the GitHub-based development model used by IES.

The maintainers should collectively provide an appropriate balance of:

* foundational ontology expertise
* RDF ontology implementation capability
* domain-extension knowledge
* public sector and cross-government understanding
* GitHub-based development and review experience
* repository access and branching expertise
* licensing, security and release knowledge
* continuity and operational resilience

## Appointment

IES Top Ontology Maintainers and IES Core Ontology Maintainers are appointed separately by majority vote of the Steering Group.

A candidate may be proposed where:

* additional maintainer capacity is required
* greater resilience or continuity is needed
* a gap in technical expertise has been identified
* the candidate possesses the expertise and practical GitHub capability required for the relevant role

Each appointment must identify whether the candidate is being appointed as:

* an IES Top Ontology Maintainer
* an IES Core Ontology Maintainer
* both, through two distinct appointments

Appointment to both roles should not be presumed merely because a candidate is qualified for one of them.

The Steering Group should consider both the suitability of the candidate and the existing capability and composition of the relevant maintainer group.

Appointments must be documented in the relevant Steering Group records and added to the appropriate current-maintainer record.

## Number and Composition of Maintainers

The number of maintainers for each ontology should remain proportionate to its maintenance and governance needs.

There should be enough maintainers to provide:

* resilience and continuity
* timely technical review
* appropriate separation of review and implementation activity
* effective repository maintenance
* access to the required areas of technical expertise

The groups should not become so large that accountability, decision-making or technical coherence is weakened.

The Steering Group should consider the composition of the IES Top and IES Core maintainer groups both separately and collectively.

Where only one public sector representative is appointed across the two groups, the Steering Group should consider whether that arrangement provides sufficient coverage for decisions affecting both ontology layers.

## Responsibilities of Maintainers

Maintainers are responsible for the ontology layer to which they have been appointed.

Their responsibilities include:

* maintaining its structure and technical integrity
* reviewing proposed changes
* identifying semantic, technical and implementation implications
* ensuring consistency with ontology engineering and 4D modelling principles
* evaluating downstream effects
* using GitHub effectively to support traceable development and review
* implementing changes approved through the appropriate governance route
* documenting material changes
* supporting release activity
* escalating strategic, cross-domain, high-impact or disputed matters to the Steering Group

IES Top Ontology Maintainers must carefully assess the effects of proposed changes on IES Core and on domain extensions that depend directly or indirectly on IES Top.

IES Core Ontology Maintainers must carefully assess the effects of proposed changes on domain extensions that depend on IES Core and determine whether a proposed change also has implications for IES Top.

Where a change affects both ontology layers, the relevant IES Top and IES Core Ontology Maintainers must coordinate their technical assessment.

Maintainers must act in accordance with the IES Charter and relevant governance processes.

## Domain-Originated Requirements

A domain extension may occasionally identify a requirement for a change to IES Top, IES Core or both.

The requirement should first be developed and assessed through the relevant domain-managed technical team. The team should:

* define the requirement clearly
* provide supporting evidence
* explain why it cannot be addressed solely within the domain extension
* consider domain and cross-domain implications
* identify affected concepts, dependencies and implementation artefacts
* provide an initial impact assessment

The proposal should then be promoted through the Advisory Members for consideration under the appropriate IES governance process.

IES Top and IES Core Ontology Maintainers should provide technical advice and impact assessment for proposals affecting their respective ontology layers.

Domain-managed technical teams, Domain Working Groups and Advisory Members do not directly approve or implement changes to IES Top or IES Core.

## Change-Impact Expectations

Because domain extensions sit below IES Top and IES Core, changes to either foundational layer may affect multiple repositories and implementations.

Before progressing a material change, the relevant maintainers should consider:

* changes to meaning, classification or inheritance
* changes to relationships, constraints or modelling patterns
* compatibility with existing domain extensions
* effects on RDF artefacts and implementation behaviour
* interoperability implications
* migration and release requirements
* the need for coordinated changes in downstream repositories
* the risk of introducing divergent or inconsistent implementations

Relevant domain-managed technical teams should be consulted where specialist knowledge is needed to evaluate the consequences of a proposed change.

Significant risks, dependencies and required follow-up actions must be documented through the appropriate issue, proposal or pull-request process.

## Authority and Limits

IES Top Ontology Maintainers have authority to maintain IES Top within the limits of the IES governance framework.

IES Core Ontology Maintainers have equivalent authority for IES Core.

Maintainers may undertake routine maintenance where it does not materially alter the structure, meaning, behaviour or downstream use of the ontology for which they are responsible.

Material changes must follow the relevant proposal, review and approval process.

Changes with strategic, cross-domain, high-impact or disputed implications must be escalated to the Steering Group.

A maintainer must not approve or implement a change to an ontology for which they have not been separately appointed.

Neither role automatically grants authority over domain extensions. These are governed through the relevant Domain Working Group and maintained through their domain-level technical and repository arrangements.

Repository permissions are not a substitute for governance approval.

## Access and Permissions

IES Top Ontology Maintainers must have access and permissions appropriate to maintaining IES Top.

IES Core Ontology Maintainers must have access and permissions appropriate to maintaining IES Core.

Access to one ontology must not automatically provide maintenance permissions for the other.

Permissions must be proportionate to the relevant appointment and consistent with repository-level security and governance requirements.

Maintainers must understand the implications of the permissions they hold, including:

* branch-protection requirements
* pull-request review requirements
* merge permissions
* release permissions
* restrictions applied to protected branches
* the consequences of changes to shared ontology artefacts

Access must be reviewed when a maintainer:

* leaves a role
* changes responsibilities
* no longer requires access
* is removed or replaced
* becomes subject to a relevant governance, security or operational review

Where an individual holds both roles and leaves only one, access associated with the remaining appointment may be retained where appropriate.

## Participation Expectations

Maintainers are expected to participate actively and constructively.

They should:

* review relevant proposals and pull requests in a timely manner
* provide technically grounded advice
* consider impacts across the wider IES ecosystem
* engage with relevant domain-managed technical teams
* use GitHub effectively to support issues, branches, pull requests and traceable implementation
* follow the agreed review, approval and release practices for the relevant repository
* declare relevant conflicts of interest
* support transparent and traceable decision-making
* maintain appropriate records of material changes

Participation should be proportionate to the needs of the ontology and the maintainer’s agreed responsibilities.

## Conflicts of Interest

Maintainers must declare any actual, potential or perceived conflict of interest relating to a matter under consideration.

A conflict does not necessarily prevent participation, but it must be transparent and managed appropriately.

Where necessary, the relevant governance route may determine that a maintainer should not participate in a particular review, decision or implementation activity.

Appointment to both maintainer roles must not be used to bypass independent review where a change affects both IES Top and IES Core.

## Review of Membership

Membership should be reviewed periodically to ensure that each role remains accurate, proportionate and fit for purpose.

A review may consider:

* whether each ontology has sufficient maintainer capacity
* whether maintainers continue to meet the technical expectations of their role
* whether maintainers continue to meet the required GitHub capability expectations
* whether the groups collectively possess the required expertise
* whether public sector representation remains appropriate
* whether access and permissions remain proportionate
* whether additional appointments are required
* whether any maintainer should step down or be replaced
* whether responsibilities remain correctly divided between the two roles

Any material change to membership must be recorded in the relevant public record.

## Removal or Replacement

A maintainer may step down from either role at any time.

A maintainer may be removed or replaced by majority vote of the Steering Group where they:

* are no longer able to perform the role
* no longer meet its technical expectations
* no longer meet its GitHub capability expectations
* are unable to participate for a sustained period
* have a conflict of interest that cannot be managed appropriately
* materially fail to act in accordance with the IES Charter or governance processes

A maintainer may also be removed where the Steering Group determines that the appointment is no longer required.

Removal from one maintainer role does not automatically result in removal from the other. Where an individual holds both roles, the Steering Group must state clearly whether its decision applies to one or both appointments.

Access and permissions associated with the affected role must be reviewed promptly.

Where resignation, removal or replacement would leave insufficient maintainer capacity or remove the only public sector representative, the Steering Group must address the resulting vacancy or composition issue through the same governance route.

## Public Record

Current and past maintainers are recorded centrally and separately for each ontology.

Current appointments are recorded in:

* Current IES Top Ontology Maintainers
* Current IES Core Ontology Maintainers

Historic appointments are recorded in:

* Past IES Top Ontology Maintainers
* Past IES Core Ontology Maintainers

Where an individual holds or has held both roles, each appointment should be recorded separately.

The public record supports transparency, accountability and continuity of technical stewardship.
