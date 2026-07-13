# IES Top (Layer 0) and IES Core (Layer 1)

Together (L0 and L1), these repositories provide the shared ontology foundation used across domain-driven development within IES.

---

## Purpose

L0 and L1 provide shared ontology structures that support consistency across domains.

They allow domain-driven repositories to build from, extend, or align with a common foundation rather than developing isolated or incompatible ontology structures.

---

## IES Top

IES Top (Layer 0) is the single top-level ontology repository.

It is maintained in the `ies-top` repository and provides the highest-level ontology structures used across IES.

IES Top is maintained by the L0 Ontology Maintainers.

---

## IES Core

IES Core is the single core ontology repository.

It is maintained in the `ies-core` repository and provides common ontology structures used across domain-driven development.

IES Core is maintained by the L1 Ontology Maintainers.

---

## Governance

IES Top and IES Core are subject to stricter governance than domain-driven repositories because changes to them may affect multiple domains.

Changes to IES Top or IES Core must follow the relevant proposal, review, and approval process. Changes with strategic, cross-domain, high-impact, or disputed implications must be escalated to the Steering Group.

L0 and L1 Ontology Maintainers are responsible for maintaining IES Top and IES Core, respectively.

---

## Relationship with Domain-Driven Repositories

Domain-driven repositories build from, extend, or align with IES Top and IES Core.

Domain-driven extensions are governed directly by the relevant Domain Working Groups. Where a domain identifies a required change to IES Top or IES Core, the change must be proposed through the appropriate governance process.

This arrangement allows domains to develop material relevant to their own needs while preserving shared structures across IES.

---

## Repository Information

| Repository | Repository Type | Maintained By               | Repository-Level Maintainer Information |
| :--------- | :-------------- | :-------------------------- | :-------------------------------------- |
| `ies-top`  | IES Top         | L0 Ontology Maintainers     | Maintained in the `ies-top` repository  |
| `ies-core` | IES Core        | L1 Ontology Maintainers     | Maintained in the `ies-core` repository |

---
