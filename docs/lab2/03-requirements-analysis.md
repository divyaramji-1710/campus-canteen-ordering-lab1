# Requirements analysis of the customer-discovery Discussion

Each point from the stakeholder conversation is classified below.

| # | Topic | Classification | Recorded as |
|---|---|---|---|
| 1 | Students browse and order; staff view orders and update status | Confirmed requirement | FR-001, FR-002, FR-004, FR-005 |
| 1 | Administration may manage menu information later | Open question | SRS §8 — who may add/edit/disable items |
| 2 | Item shows name, price, availability | Confirmed requirement | FR-001 |
| 2 | Short description | Optional (nice to have) | FR-001 ("may be displayed") |
| 3 | Multiple items, positive whole-number quantity | Confirmed requirement | FR-002 |
| 4 | Total = Σ(price × quantity) | Confirmed requirement | FR-003 |
| 4 | Taxes and service charges | Out of scope (initial prototype) | FR-003, SRS §6 |
| 5 | Statuses Submitted, Preparing, Ready, Completed | Confirmed requirement | FR-005 |
| 6 | Order cancellation | **Open question** | SRS §8, decision Issue |
| 7 | 95% of menu requests < 2 s at 50 virtual users | **Assumption** (provisional classroom target) | NFR-001 |
| 8 | A student must not see another student's order | Confirmed requirement | NFR-002 |
| 9 | Real payment gateway | **Out of scope** | SRS §2, FR-004 (simulated) |

## Why cancellation remains an open question

The stakeholder explicitly said the cancellation policy is not agreed. The team
does not know whether cancellation is allowed at all, or until which status
(Submitted? before Preparing?). Writing a rule now would be a guess presented
as a requirement, and it could conflict with how staff actually prepare food.
It is therefore tracked as a decision Issue, kept out of Sprint 1, and will only
become a requirement with its own ID once the stakeholder decides.
