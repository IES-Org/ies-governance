# IES Common

IES Common is the conceptual grouping of IES Top and IES Core.

There is no separate IES Common repository. IES Common refers collectively to:

* `ies-top`
* `ies-core`

Together, these repositories provide the shared ontology foundation used across domain-driven development within IES.

---

## Purpose

The purpose of IES Common is to provide shared ontology structures that support consistency across domains.

IES Common allows domain-driven repositories to build from, extend, or align with a common foundation rather than developing isolated or incompatible ontology structures.

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

## Governance

IES Top and IES Core are subject to stricter governance than domain-driven repositories because changes to them may affect multiple domains.

Changes to IES Top or IES Core must follow the relevant proposal, review, and approval process. Changes with strategic, cross-domain, high-impact, or disputed implications must be escalated to the Steering Group.

Common Ontology Maintainers are responsible for maintaining IES Top and IES Core within the IES governance framework.

More information is available in:

* [Common Ontology Maintainers](../roles/technical-support-and-maintenance/common-ontology-maintainers/overview.md)
* [Common Ontology Maintainer Membership](../roles/technical-support-and-maintenance/common-ontology-maintainers/membership.md)
* [Current Common Ontology Maintainers](../roles/technical-support-and-maintenance/common-ontology-maintainers/current-common-ontology-maintainers.md)

---

## Relationship with Domain-Driven Repositories

Domain-driven repositories build from, extend, or align with IES Top and IES Core.

Domain-driven extensions are governed directly by the relevant Domain Working Groups. Where a domain identifies a required change to IES Top or IES Core, the change must be proposed through the appropriate governance process.

This arrangement allows domains to develop material relevant to their own needs while preserving shared structures across IES.

---

## Repository Information

| Repository | Repository Type | Maintained By               | Repository-Level Maintainer Information |
| :--------- | :-------------- | :-------------------------- | :-------------------------------------- |
| `ies-top`  | IES Top         | Common Ontology Maintainers | Maintained in the `ies-top` repository  |
| `ies-core` | IES Core        | Common Ontology Maintainers | Maintained in the `ies-core` repository |

---

## Notes

* IES Common is not a separate repository.
* IES Common refers collectively to IES Top and IES Core.
* IES Top is maintained in the `ies-top` repository.
* IES Core is maintained in the `ies-core` repository.
* IES Top and IES Core are maintained by the Common Ontology Maintainers.
* Domain-driven repositories build from, extend, or align with IES Top and IES Core.

