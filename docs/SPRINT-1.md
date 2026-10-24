# Sprint 1 Plan

## Sprint goal

> **Sprint 1 goal:** A student can see available menu items, select one or more
> items with valid quantities, and see a correctly calculated total before
> submitting an order.

## Product backlog

| Requirement | Type | Priority | Estimate | Sprint | Status |
|---|---|---|---:|---|---|
| FR-001 — View menu | Functional | High | 3 | Sprint 1 | Todo |
| FR-002 — Select menu items and quantities | Functional | High | 5 | Sprint 1 | Todo |
| FR-003 — Calculate order total | Functional | High | 3 | Sprint 1 | Todo |
| FR-004 — Submit an order | Functional | High | 5 | Backlog | Todo |
| FR-005 — Track order status | Functional | Medium | 5 | Backlog | Todo |
| NFR-001 — Verify menu response time | Non-functional | Medium | 3 | Backlog | Todo |
| NFR-002 — Protect order privacy and authorization | Non-functional | High | 5 | Backlog | Todo |
| Decision needed — define order cancellation policy | Clarification | Medium | — | Backlog (not sprint work) | Todo |

**Sprint 1 planned estimate:** 3 + 5 + 3 = **11 story points** (relative estimates, not hours).

## Prioritization rationale

- FR-001 (view menu) is a prerequisite for selecting items.
- FR-002 (select items/quantities) is a prerequisite for calculating the total.
- FR-003 (total) completes a small, coherent user journey that can be verified.
- FR-004 and FR-005 are needed for the end-to-end workflow and follow in a later iteration.
- NFR-002 (privacy) is **high priority** and must be addressed before any real
  student data is used; it is not optional just because it is not in Sprint 1.
- NFR-001 (performance) needs an agreed test environment and an existing
  workflow to measure; the target must be validated before real deployment.
- The cancellation decision is unresolved analysis work, so it is not sprint work.

## Definition of Done

An Issue is Done only when:

- The behavior matches the requirement and its acceptance criteria.
- Invalid inputs are handled as specified.
- The change has been reviewed by another team member when applicable.
- Relevant tests have passed.
- Any affected SRS documentation is updated.
- The team has checked the acceptance criteria before moving it to **Done**.

Because Lab 2 is a planning lab, the Sprint 1 Issues stay in **Todo**.
