# Formal candidate relations

**Conceptual notation, not validated equations**  
**Documentation revision:** 2 · 2026-10-05  
**Status:** research candidates; not Core; no implementation or experimental result claimed here.

These four relations develop the public [research hypotheses](hypotheses.md) into definitions and possible tests. They were prepared in dialogue with an AI assistant and approved by Hayrettin Atas for inclusion as research candidates. Approval to publish is not scientific validation or promotion into the operational Core.

## How to read the notation

`+` means “consider together”, not numerical addition. `→` denotes a proposed dependency or sequence, not a proved implication. The relations are not dimensionally specified equations. Their terms, domains, measurements and failure conditions must be fixed before an experimental implementation can be evaluated.

The German formulations below preserve the proposals discussed for this documentation update. The software interpretations and test designs are new operationalization proposals, not recovered historical implementations.

## Source and attribution boundary

| Candidate | Source position in this update | Historical limitation |
|---|---|---|
| FC-01 | Related pressure/gradient motif appears in the author-provided research dossier dated 2026-10-05. The exact chain below is an editorial formulation for this update. | No original archival date or sole authorship is established for this exact formulation. |
| FC-02 | Present dialogue proposal for a temporal decision process. | No directly verified original Intuitionsarchiv passage is available for this exact relation. |
| FC-03 | Related bounded-mutation motif appears in the author-provided research dossier dated 2026-10-05. The exact chain below is an editorial formulation for this update. | No original archival date or sole authorship is established for this exact formulation. |
| FC-04 | Present dialogue proposal for retaining separately bound alternatives. | No directly verified original Intuitionsarchiv passage is available for this exact relation. |

The dossier is a later synthesis, not an original chat transcript. Earlier dates in the general [provenance note](provenance.md) must not be transferred to these four formulations. Private chats, identifiers and archive mappings are not published. This source limitation does not prevent testing a new candidate; it limits historical claims about it.

## FC-01 — Boundary, difference and event formation

### Candidate relation

```text
Grenze + Differenz → Gradient → Fluss → Ereignis
```

### Meaning

A boundary and an observable difference may identify a direction of change. Whether anything changes also depends on a permitted coupling or transition path. A difference alone does not imply flow. An impermeable boundary, a missing mechanism or an out-of-scope difference may produce no transition.

Here “pressure”, “gradient” and “flow” are conceptual terms until an experiment defines their variables. No physical conservation law, unit or new force is asserted.

### Possible software translation

Represent a bounded state, its reference revision and a named discrepancy. A monitor may propose a review event when an eligible discrepancy is present. The event is a record or task candidate, not an authorized external effect. Provenance and scope accompany the proposal; an independent authorization step remains necessary for any consequential action.

### Test and failure conditions

Compare the monitor with a predeclared explicit-rule monitor on the same state changes. Include relevant discrepancies, irrelevant differences, unchanged states and blocked transition paths. Measure useful and unnecessary review candidates, missed eligible changes, evidence retention and unauthorized effect attempts.

The usefulness hypothesis is not supported if the proposed relation adds no benefit over the baseline, produces systematic spurious candidates or loses the boundary. A blocked path producing no action is an expected control, not a failure.

**Connections:** H1/H2; E5/E6. See [TFC-01](../experiments/formal-candidate-tests.md#tfc-01--difference-to-review-candidate).

## FC-02 — Temporal decision surface

### Candidate relation

```text
Gegenwart + Erinnerung + mögliche Zukunft → Bewertung → Auswahl → Handlung
```

### Meaning

A decision process considers present state, applicable memory and explicitly hypothetical successor states. Memories have scope and validity; imagined futures are not observations. “Selection” selects a proposal. The final “Handlung” in the conceptual chain is conditional on the separate authorization boundary.

### Possible software translation

Bind the current state to a revision, check retrieved memory for applicability and construct labeled successor candidates. Evaluation may return a proposal, a request for more evidence or a hold. Immediately before a consequential action, re-check relevant state and authorization; a previous evaluation does not carry indefinite validity.

No concrete scoring function, weight set or optimization objective is specified here. This is not a claim of a new planning algorithm.

### Test and failure conditions

Compare current-state-only, current state with validated memory, and current state with validated memory plus explicit successor candidates. Match task set, tools, model configuration and resource budgets. Include expired memories, missing evidence and changes of reference state during evaluation.

Measure task performance, stale-evidence use, valid holds, latency and evaluation cost. The usefulness hypothesis is not supported if successor modeling only adds cost or imagined evidence, or if stale decisions pass the action boundary.

**Connections:** H1/H2; RQ3/RQ6; E1/E5/E6. See [TFC-02](../experiments/formal-candidate-tests.md#tfc-02--time-bound-evaluation).

## FC-03 — Bounded variation at an organizational boundary

### Candidate relation

```text
Elternordnung + Milieudifferenz → begrenzte Variation → Randfunktion
→ veränderte Zustände → Nachfolgeordnung
```

### Meaning

A parent configuration is confronted with a changed environment. Proposed variation is confined to a declared boundary or change surface. A successor configuration is retained only after comparison. “Fractal boundary mutation” is the motivating analogy, not a demonstrated fractal property or a law of biological inheritance.

### Possible software translation

Snapshot the parent and provenance, freeze the permitted change surface and evaluation contract, generate a variant, then compare it with the parent. Return keep, discard or hold, with an evaluation record and a rollback reference. The variant must not rewrite its evaluator, authorization rules or acceptance criteria as part of the same trial.

Promotion into the operational Core remains a distinct authorization; a positive test does not grant it.

### Test and failure conditions

Compare bounded variation with a no-change parent and a same-budget variation baseline inside an isolated test environment. Introduce specified task or environment changes. Measure task performance, changes outside the allowed surface, provenance loss, rollback completeness and evaluation cost.

The usefulness hypothesis is not supported if apparent improvement depends on changing the evaluator or exceeds the permitted surface, or if the parent cannot be restored. Reuse of the same diagram at different scales alone is not evidence of fractality.

**Connections:** H3/H4; E3/E4. See [TFC-03](../experiments/formal-candidate-tests.md#tfc-03--bounded-variation-and-return).

## FC-04 — Binding alternatives without premature selection

### Candidate relation

```text
Bindung ≠ notwendigerweise Auswahl

gemeinsamer Möglichkeitszustand → unterschiedliche Randbindung
→ parallele Entwicklung → Phasendifferenz → Rekopplung
→ sichtbare Signatur
```

### Meaning

Two alternatives can retain distinct contexts and provenance without one immediately becoming canonical and the other being discarded. In this candidate, “Randbindung” means attachment to an explicit branch context. It does not establish truth, authorize execution or bypass the project's governance binding step.

“Phasendifferenz” is an analogy for divergence of branch state or progression unless a future experiment supplies a mathematical definition. It is not a claim of quantum phase, superposition or interference. “Rekopplung” means an explicit comparison of compatible branch outputs, not an automatic merge.

### Possible software translation

Fork candidates from a recorded common parent, retain each branch's assumptions, evidence lineage and allowed scope, then compare them when new evidence arrives. Differences and unresolved conflicts remain explicit. A shared ancestor or duplicated source is not independent confirmation. The comparison may select, keep alternatives separate or hold; none of those outcomes grants external effect authority.

### Test and failure conditions

Compare immediate selection with bounded retention of alternatives under the same overall budget. Use tasks with initially ambiguous evidence, later disambiguation, and cases where ambiguity remains. Include duplicate-source and incompatible-scope controls.

Measure premature wrong selections, later corrections, unresolved-conflict retention, duplicate-evidence errors and computational cost. The usefulness hypothesis is not supported if retention only increases cost, amplifies copied evidence or silently merges incompatible branches.

**Connections:** H1/H3; RQ4/RQ5; E1/E2/E5. See [TFC-04](../experiments/formal-candidate-tests.md#tfc-04--retaining-alternatives).

## Shared boundary

All four candidates require scoped definitions and implementations before they can be evaluated. Their publication adds research questions and proposed tests, not executed capabilities. No private candidate-pressure scoring function or unpublished implementation is included.

Read next: [test specifications](../experiments/formal-candidate-tests.md), [project status](../STATUS.md), [provenance boundary](provenance.md).
