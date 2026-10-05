# Experiment Program

Specifications here are proposals until corresponding run artifacts and results are published.

## Planned experiments
- **E1 Drift / reproducibility** — compare retrieval-only with Core + Corpus + regression.
- **E2 Roles / boundaries** — compare monolithic and role-separated workflows.
- **E3 Transition structures** — map one transition type across micro, meso and macro levels and test invariants/breaks.
- **E4 Bounded mutation** — introduce defined errors or tensions; allow variation only inside a bounded surface; measure keep/discard/hold, rollback and evidence loss.
- **E5 Dynamic reference state** — change context or validity during a multi-stage run and test whether stale assumptions are blocked.
- **E6 Task formation** — inject defined state changes and test whether useful task candidates arise reproducibly, decay appropriately and remain behind the effect boundary.
- **E7 Invariants** — evaluate hypothesized signatures only with predefined post-hoc metrics across many seeds; do not inject target constants into the dynamics.

No experiment result is claimed by this file.

## Formal-candidate subtests

[Detailed protocols TFC-01–TFC-04](formal-candidate-tests.md) connect the [four formal candidates](../research/formal-candidates.md) to this existing program. They add proposed baselines, controls, metrics and failure conditions; they do not report implementations or completed runs.

| Subtest | Candidate | Program connection |
|---|---|---|
| TFC-01 | FC-01 — difference to review candidate | E5/E6 |
| TFC-02 | FC-02 — time-bound evaluation | E1/E5/E6 |
| TFC-03 | FC-03 — bounded variation and return | E3/E4 |
| TFC-04 | FC-04 — retaining alternatives | E1/E2/E5 |

E7 remains a separate simulation-oriented proposal. None of the four new candidate relations establishes a physical law or numerical invariant. Review [STATUS.md](../STATUS.md) before citing an experimental capability or result.
