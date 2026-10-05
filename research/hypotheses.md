# Research Hypotheses

All items are **research candidates**, not canonical truths.

## H1 — Boundary-preserving adaptation
An adaptive agent architecture can remain more auditable when meaningful state transitions preserve source, scope, validity and authorization boundaries.

## H2 — Candidate formation without authority expansion
Internal differences may generate task candidates while a separate authorization layer prevents those candidates from becoming external actions by default.

## H3 — Recurring transition topology
A pattern such as input → boundary → transformation → verification → return may recur at multiple architectural scales. Recurrence of form does not imply recurrence of authority.

## H4 — Bounded mutation
Variation restricted to an explicit mutation surface, followed by fixed comparison and keep/discard/hold decisions, may improve adaptation while retaining rollback and provenance.

## H5 — Measurable stability
Stable behavior should be assessed through predefined observables and repeated runs rather than narrative plausibility.

## H6 — Analogy has a breaking point
Cross-domain analogies become scientifically useful only when the point at which they fail can also be specified.

## Connections to the formal candidates

The following are proposed research connections, not derivations or evidence for H1–H6:

| Candidate | Hypothesis connection | Evaluation proposal |
|---|---|---|
| FC-01 — boundary/difference/event | H1/H2 | TFC-01 within E5/E6 |
| FC-02 — temporal decision surface | H1/H2 | TFC-02 within E1/E5/E6 |
| FC-03 — bounded boundary variation | H3/H4 | TFC-03 within E3/E4 |
| FC-04 — separately bound alternatives | H1/H3 | TFC-04 within E1/E2/E5 |

H5 and H6 constrain all four evaluations: use defined measurements and retain counterexamples. Read [formal candidates](formal-candidates.md) for meanings and source limits, and [test specifications](../experiments/formal-candidate-tests.md) for baselines and failure conditions. No hypothesis is promoted by adding these links.
