# EO-MKT-001 — Developer Demand Experiment

**Status:** Draft. No external research outreach has been authorized or posted from this repository.

## Decision
Should Earth Online invest in a narrowly scoped third-party guest-object viewer adapter?

## Hypothesis
An existing browser-3D creator would invest integration time to receive visitors with controlled external objects, while retaining their current engine and host environment.

## Scope
Concept storyboard and transparent feedback request only. **No public SDK. No new development request.**

## Constraints
- Founder availability: approximately 30–60 minutes on limited evenings
- Incremental cash budget target: CAD $0
- Avoid requiring direct sales to individual businesses
- Keep the Earth Online core repository private
- Never advertise complete cross-runtime visitation as implemented

## Metrics (exploratory thresholds, not statistical evidence)
- At least five substantive responses from relevant developers
- At least three explicit, concrete project scenarios
- At least one developer willing to pilot with an existing project
- Document objections and solutions currently used

Record qualified exposures separately from vanity metrics such as stars and upvotes. Silence without qualified reach is inconclusive.

## Procedure
1. Approve accuracy of concept illustration and documentation.
2. Create a separate concept repository; review privacy and licenses.
3. Publish **only after founder approval**.
4. Post one transparent request for feedback in a developer community consistent with its rules.
5. Classify replies: actual need, objection, competitor, integration willingness, evidence of budget.
6. Apply the decision gate.

## Decision gate
- **Proceed to technical scoping:** one credible existing project volunteers for a limited integration, and substantive responses support meaningful value.
- **Revise positioning:** developer interest is mainly in discovery, visitor traffic, or social features rather than portable objects.
- **Pause:** no actionable willingness to integrate after adequate qualified exposure.
- **Inconclusive:** no meaningful responses and insufficient reach.

## Technical checkpoint (separate CTO approval)
CTO review EO-ARCH-REVIEW-001 concluded **B — Adaptable**. A read-only external viewer is a smaller experiment than full cross-runtime Visit. Authentication, permission boundaries, reliability and adapter maintenance must be assessed before engineering is authorized.

## Explicit non-goals
Do not build a distributed object ownership standard, multi-engine SDK, unrestricted visitor scripts, or paid hosted federation in this round.
