# Lab 2 — Reflection answers

1. **Discussion vs Issue.** A Discussion is an open conversation for exploring
   questions and reaching agreement. An Issue tracks a specific piece of work
   the team must do, with acceptance criteria, an owner, and a state.
2. **Why record it in the SRS.** Discussion threads are long and informal. The
   SRS is the single, version-controlled source of the agreed behavior, so
   design, implementation and tests all work from the same definition.
3. **Unique IDs.** They let Issues, commits, pull requests and tests refer to a
   requirement without ambiguity, which is what makes traceability possible.
4. **Testable requirement.** It states observable behavior with a pass/fail
   check. Example: FR-003 — "the displayed total equals the sum of unit price
   × quantity for all selected items." Two items at ₹40 × 2 and ₹25 × 1 must
   show ₹105.
5. **Functional vs non-functional.** Functional requirements describe what the
   system does (FR-001 show the menu). Non-functional requirements describe
   qualities or constraints on how well it does it (NFR-001 response time,
   NFR-002 privacy).
6. **Provisional performance target.** The numbers came from a classroom
   scenario, not from measurement or a real stakeholder agreement, and the test
   environment is not defined yet. They must be confirmed before deployment.
7. **Cancellation not confirmed.** The stakeholder has not decided. Building a
   guessed rule risks wasted work and behavior that conflicts with canteen
   operations. It stays an open question with its own decision Issue.
8. **Projects for planning.** The board shows every requirement in one place
   with priority, type and estimate fields, so the team can sort, filter, and
   select a sprint backlog, and watch progress through Todo → In Progress → Done.
9. **Security outside Sprint 1.** Privacy failures expose real student data and
   are costly to retrofit. NFR-002 must shape the design early and be done
   before any real data is used, even if no security code is written in Sprint 1.
10. **Moving to Done.** Only when the Definition of Done is met: acceptance
    criteria checked, invalid inputs handled, review done, tests passing, and
    the SRS updated where affected.
