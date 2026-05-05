# Glossary

This glossary defines key terms used within the IES governance documentation.

These definitions provide a shared understanding of roles, structures, repository types, and governance concepts used across the governance framework.

---

## Access

Access means permission to view, contribute to, maintain, administer, or otherwise interact with repositories, teams, settings, or resources within the IES GitHub organisation.

Access must be proportionate to the role being performed.

---

## Administrative Repository

An Administrative Repository is a repository containing governance, management, planning, coordination, or informational material relating to IES.

Administrative repositories do not contain ontology content and are not part of IES Top, IES Core, or any domain-driven ontology extension.

---

## Advisory Member

An Advisory Member is a non-voting member of the Steering Group appointed to provide specialist technical advice.

Advisory Members must be members of an active Domain Working Group and should have strong expertise in ontology development, IES Top, IES Core, domain-driven extensions, and related technical matters.

Advisory Members are not appointed to represent their Domain Working Group.

---

## Authoritative Source

The Authoritative Source is the recognised location for the current approved state of IES governance documentation, approved development activity, ontology content, and official releases.

The IES GitHub organisation is the authoritative source for IES.

---

## Branch Protection

Branch Protection is a GitHub configuration that restricts how changes may be made to a branch.

Branch protection may require pull request review, status checks, restricted merge permissions, or other safeguards before changes can be merged.

---

## Common Ontology Maintainer

A Common Ontology Maintainer is an individual appointed by majority vote of the Steering Group to maintain IES Top and IES Core.

Common Ontology Maintainers are responsible for:

* maintaining IES Top and IES Core
* reviewing proposed changes affecting IES Top and IES Core
* providing technical advice on ontology modelling, 4D principles, RDF implementation, and technical consistency
* implementing approved changes
* supporting alignment between IES Top, IES Core, and domain-driven extensions

Their authority is limited to the scope defined in the governance model and does not extend to domain-driven repositories or strategic decision-making.

The Common Ontology Maintainer group must include at least one Public Sector Representative.

---

## Contribution

A Contribution is a proposed addition, change, correction, review, issue, pull request, comment, or other input to IES.

Contributions may come from governance role-holders, working group participants, repository maintainers, organisations, or external users.

---

## Contributor

A Contributor is a person or organisation that contributes to IES.

A Contributor does not automatically hold governance authority or repository permissions.

---

## Domain

A domain within IES represents a distinct functional area, sector, or area of subject matter expertise that encompasses a specific set of concepts, relationships, and information exchange requirements.

Domains support organised ontology development by providing clear ownership, subject matter expertise, and accountability for domain-driven extensions.

A domain should normally be governed through a formally established Domain Working Group before repositories are created in that domain’s name.

---

## Domain Ontology

A Domain Ontology is a modular ontology developed within a specific Domain Working Group to represent concepts and relationships relevant to that domain.

Domain ontologies:

* are developed and managed by their respective Domain Working Groups
* typically build upon, extend, or align with IES Top and IES Core
* may evolve and be released independently using agreed governance processes

While domain ontologies are independently managed, they may be affected by changes to IES Top or IES Core due to shared dependencies.

---

## Domain Working Group

A Domain Working Group is a group of contributors responsible for domain-driven development within IES.

Each Domain Working Group:

* manages domain-specific ontology development
* provides subject matter expertise
* ensures alignment with IES Top and IES Core
* participates in governance through representation at the Steering Group

Domain Working Groups are responsible for domain-driven extensions within their area of scope.

---

## Domain Working Group Chair

The Domain Working Group Chair is the person responsible for leading a Domain Working Group.

The Chair supports the effective operation of the Domain Working Group, coordinates domain activity, and ensures that the group operates within the IES governance framework.

A Domain Working Group Chair is a Voting Member of the Steering Group.

---

## Domain Working Group Representative

The Domain Working Group Representative is appointed by the Domain Working Group Chair to support the Domain Working Group’s participation in Steering Group activity.

The Representative role provides resilience and continuity for the Domain Working Group’s participation in governance.

A Domain Working Group Representative is a Voting Member of the Steering Group.

---

## Domain-Driven Repository

A Domain-Driven Repository is a repository containing ontology content developed for a specific domain.

Domain-driven repositories are governed directly by the relevant Domain Working Group and should build from, extend, or align with IES Top and IES Core.

Repository names must not imply governance by a Domain Working Group that has not been formally established.

---

## GitHub Organisation Custodian

The GitHub Organisation Custodian is the primary role-holder responsible for supporting administration of the IES GitHub organisation.

Responsibilities may include:

* managing access, roles, and permissions
* maintaining repository settings and organisation settings
* supporting repository structure and standards
* supporting publication and release processes
* ensuring continuity of service

This function operates as part of Platform and Communications Management and does not make governance or ontology modelling decisions.

---

## Governance

Governance refers to the framework of roles, responsibilities, principles, decision-making arrangements, and processes that guide how IES is managed, developed, maintained, and released.

Governance helps ensure that IES remains:

* aligned with public interest
* technically coherent
* transparent and accountable
* usable across domains
* capable of evolving over time

---

## IES

IES means the Information Exchange Standard.

IES supports consistent information exchange across organisations, systems, assets, sectors, and domains.

---

## IES Common

IES Common is the conceptual grouping of IES Top and IES Core.

There is no separate IES Common repository. IES Common refers collectively to:

* `ies-top`
* `ies-core`

Together, these repositories provide the shared ontology foundation used across domain-driven development within IES.

Changes to IES Top or IES Core may have downstream impact on domain-driven repositories and therefore require appropriate governance and review.

IES Common does not govern or manage domain ontologies, which remain under the responsibility of their respective Domain Working Groups.

---

## IES Core

IES Core is the single core ontology repository within IES.

IES Core is maintained in the `ies-core` repository and forms part of IES Common.

---

## IES GitHub Organisation

The IES GitHub Organisation is the GitHub organisation used as the authoritative source for IES governance documentation, approved development activity, ontology content, and official releases.

---

## IES Top

IES Top is the single top-level ontology repository within IES.

IES Top is maintained in the `ies-top` repository and forms part of IES Common.

---

## Issue

An Issue is a GitHub record used to raise a problem, question, request, discussion point, or proposed change.

Issues support transparent and traceable development.

---

## Lazy Consensus

Lazy Consensus is a decision-making approach in which a proposal is accepted if no objections are raised within a defined period.

Within IES, Lazy Consensus may be used where explicitly permitted by the relevant Domain Working Group or process. It should not be used for matters that require Steering Group approval, changes to IES Top or IES Core, public release approval, or other material governance decisions unless explicitly authorised.

---

## Maintainer

A Maintainer is a person with responsibility for maintaining a repository, ontology artefact, platform function, or other defined area of IES.

The term must be used carefully because Common Ontology Maintainers and Repository Maintainers are distinct roles.

---

## Major Change

A Major Change is a change that has potential governance, technical, semantic, strategic, public-facing, or cross-domain impact.

Examples may include:

* changes to IES Top or IES Core
* introduction of new core concepts
* changes to existing structures used across domains
* breaking or non-backward-compatible changes
* changes to governance roles, processes, or decision-making arrangements
* changes affecting public release or official interpretation of IES

Major changes must follow the relevant proposal, review, and approval process.

---

## Material Change

A Material Change is a change with governance, technical, operational, public-facing, cross-domain, security, release, or strategic significance.

Material changes normally require review, approval, and traceability beyond routine repository maintenance.

---

## Minor Change

A Minor Change is a change that does not materially alter the structure, semantics, intended use, governance meaning, or cross-domain impact of IES.

Examples may include:

* minor corrections
* non-substantive documentation updates
* low-risk repository housekeeping
* non-breaking clarifications

Minor changes may normally be handled through the relevant repository issue or pull request workflow, subject to repository-level controls.

---

## Ontology Index

The Ontology Index is the section of the governance repository that indexes repositories in the IES GitHub organisation.

It identifies repository categories, responsible domains or groups, repository purposes, repository status, and where repository-level information can be found.

---

## Platform and Communications Management

Platform and Communications Management is the function responsible for supporting the operation of the IES GitHub organisation and communication around IES governance, development, and release activity.

This function includes the GitHub Organisation Custodian role.

Platform and Communications Management supports administration, access, repository settings, public-facing navigation, release communication, and operational sustainability. It does not approve ontology changes, domain-driven development decisions, or governance changes.

---

## Proposal

A Proposal is a structured request for a material governance, technical, operational, repository, domain, tooling, release, or publication decision within IES.

Proposals are normally submitted using the proposal template and routed through the appropriate governance process.

---

## Public Sector Representative

A Public Sector Representative is an individual who is officially appointed or authorised by a government department, public body, or public sector organisation to act on its behalf within the IES governance structure.

They may include:

* government employees
* local government employees
* individuals contracted to perform roles on behalf of government
* interim representatives temporarily assigned by a public sector organisation

Public Sector Representatives operate under official credentials, are accountable to the organisation they represent, and act on its behalf rather than in a personal capacity.

---

## Pull Request

A Pull Request is a GitHub mechanism for proposing, reviewing, discussing, and merging changes to a repository.

Pull requests support review, approval, and traceability.

---

## Repository

A Repository is a GitHub repository within the IES GitHub organisation.

Repositories may contain ontology content, governance documentation, administrative material, release artefacts, examples, or supporting documentation.

---

## Repository Maintainer

A Repository Maintainer is an individual with appropriate access and responsibility to manage and apply changes within a specific GitHub repository.

Repository Maintainers are responsible for the repositories they maintain. Their responsibilities and contact details are maintained in the relevant repository’s maintainer file, not centrally in the governance repository.

Repository Maintainer status does not confer governance authority beyond the relevant repository arrangements.

---

## Repository Permissions

Repository Permissions are GitHub permissions that allow a person to view, contribute to, maintain, or administer a repository.

Repository permissions do not confer governance authority.

---

## Steering Group

The Steering Group is the principal governance body responsible for strategic oversight and governance direction for IES.

The Steering Group is responsible for:

* setting strategic direction
* approving major changes to IES Top and IES Core
* ensuring cross-domain alignment
* resolving escalated issues
* considering strategic, cross-domain, high-impact, disputed, or governance-wide matters

The Steering Group consists of Voting Members and Advisory Members.

---

## Steering Group Chair

The Steering Group Chair is responsible for supporting the effective and impartial operation of the Steering Group.

The Steering Group Chair must be an existing Domain Working Group Chair and a Public Sector Representative.

The Steering Group Chair is appointed by majority vote of the Voting Members.

---

## Technical Support and Maintenance

Technical Support and Maintenance is the area of IES governance covering technical integrity, repository support, platform management, and maintenance activity.

It includes:

* Common Ontology Maintainers
* Repository Maintainers
* Platform and Communications Management

Technical Support and Maintenance functions support the implementation of governance decisions and the operation of IES. They do not replace the authority of the Steering Group or Domain Working Groups.

---

## Voting Member

A Voting Member is a member of the Steering Group with authority to participate in formal decision-making.

Voting Members are:

* Domain Working Group Chairs
* Domain Working Group Representatives

Each Voting Member holds one vote.

Where a vote is tied, the Steering Group Chair has the casting vote.

