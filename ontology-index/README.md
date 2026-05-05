# Ontology Index

The Ontology Index provides an index of repositories in the IES GitHub organisation.

It identifies the repositories that make up or support IES, the type of repository, the responsible domain or group, and where repository-level information can be found.

---

## Purpose

The purpose of the Ontology Index is to make the structure of IES repositories clear and navigable.

It helps users and contributors understand:

* which repositories exist
* what type of repository each one is
* whether a repository contains ontology content or administrative material
* which domain or group is responsible for each repository
* where to find repository-level documentation, maintainer information, and contact routes

The Ontology Index does not maintain a central list of Repository Maintainers. Each repository is expected to maintain its own repository-level maintainer file.

---

## Repository Categories

IES repositories are organised into four broad categories:

* **IES Top**
* **IES Core**
* **Domain-driven repositories**
* **Administrative repositories**

These categories distinguish between the top-level ontology repository, the core ontology repository, domain-specific ontology development, and repositories that support governance, management, planning, or communication.

---

## IES Top

IES Top is the single top-level ontology repository.

It is maintained in the `ies-top` repository and provides the highest-level ontology structures used across IES.

IES Top is maintained by the Common Ontology Maintainers.

---

## IES Core

IES Core is the single core ontology repository.

It is maintained in the `ies-core` repository and provides common ontology structures used across domain-driven development.

IES Core is maintained by the Common Ontology Maintainers.

---

## IES Common

IES Common is the conceptual grouping of IES Top and IES Core.

There is no separate IES Common repository. IES Common refers collectively to the `ies-top` and `ies-core` repositories and the shared ontology foundation they provide.

Changes to IES Top or IES Core may affect multiple domains and are therefore subject to stricter governance.

Common Ontology Maintainer information is maintained centrally in the governance repository.

More information is available in:

* [IES Common](./ies-common.md)
* [Common Ontology Maintainers](../roles/technical-support-and-maintenance/common-ontology-maintainers/overview.md)
* [Current Common Ontology Maintainers](../roles/technical-support-and-maintenance/common-ontology-maintainers/current-common-ontology-maintainers.md)

---

## Domain-Driven Repositories

Domain-driven repositories contain ontology content developed for a specific domain.

They build from, extend, or align with IES Top and IES Core and are governed directly by the relevant Domain Working Group.

Repository-level maintainer information is maintained in the relevant repository, not centrally in this governance repository.

More information is available in:

* [Domain Repositories](./domain-repositories.md)
* [Active Domain Working Groups](../roles/domain-working-groups/active-groups.md)
* [Domain Working Group Official Role-Holders](../roles/domain-working-groups/official-role-holders.md)

---

## Administrative Repositories

Administrative repositories contain governance, management, planning, coordination, or informational material relating to IES.

They do not contain ontology content and are not part of IES Top, IES Core, or any domain-driven ontology extension. They may nevertheless be authoritative for governance, operation, roadmap, communication, or management of IES.

More information is available in:

* [Administrative Repositories](./administrative-repositories.md)

---

## Repository-Level Documentation

Each repository within the IES GitHub organisation is expected to maintain repository-level documentation that is consistent with the IES governance framework.

Repository-level documentation should identify:

* what the repository contains
* what type of repository it is
* who is responsible for it
* where maintainer information is recorded
* how issues and proposed changes should be raised
* any repository-specific requirements, including security or access requirements

Repository-level maintainer information should be maintained in the relevant repository’s maintainer file.

---

## Contact and Contribution Routes

Users and contributors should use the repository-level documentation for the repository they are interested in.

For general issues or proposed changes, the preferred route is normally through GitHub issues or pull requests in the relevant repository. For security matters, contributors should follow the relevant repository security process.

Where a question relates to a domain, the relevant Domain Working Group should normally be the first governance route. Where a question relates to IES Top or IES Core, the Common Ontology Maintainers are the relevant technical stewardship route.

---

## Contents

* [IES Common](./ies-common.md)
* [Domain Repositories](./domain-repositories.md)
* [Administrative Repositories](./administrative-repositories.md)
