# Admissibility and Deterministic Execution Control

Independent first-principles research on admissibility, representation, constrained continuation, state coherence, and deterministic execution control for adaptive systems.

The work developed outside the conventional AI/ML research pipeline. An independently formed structural framework around admissibility, persistence, representation, and constrained continuation generated a concrete downstream control problem: how can an adaptive computational system continue changing while preserving the invariants required for coherent operation?

That question produced a substrate-independent recursive-control architecture that progressed through substantive U.S. patent examination, allowance of all 17 claims, and issuance as U.S. Patent No. 12,730,417 on September 8, 2026.

The engineering program subsequently continued into deterministic execution control, finite behavioral completion, and a Lean semantic core closed, verified, frozen, and package-integrated at `v0.1.126`. Those completed results now form a bounded baseline for a further engineering frontier concerned with preservation and verification of artifact identity, reproducible execution state, provenance, authority, claim correspondence, and epistemic standing across recursive continuation.

The repository is organized so that external evidence, implemented engineering results, formal results, structural interpretations, historical provenance, and open research remain explicitly distinguished. Each downstream artifact can therefore be inspected on its own technical merits without requiring prior agreement with the first-principles framework that generated the research trajectory.

Three transitions in this trajectory are load-bearing rather than merely chronological:

1. **structural admissibility → engineering continuation**
2. **represented continuation → execution authority**
3. **informal structural distinctions → formal and independently inspectable realization**

The current engineering frontier extends these transitions from control of individual continuations toward preservation of warranted identity, provenance, authority, and verification across recursively evolving computational and formal artifacts.

### Evidence boundary

- **EXTERNAL EVIDENCE** — independently issued or examined material
- **ENGINEERING RESULT** — implemented and behaviorally demonstrated system result
- **FORMAL RESULT** — machine-checked result within the stated formal scope
- **STRUCTURAL INTERPRETATION** — downstream analysis or conceptual retyping
- **HISTORICAL PROVENANCE** — earlier working material preserved for lineage
- **OPEN RESEARCH** — active questions not yet part of the frozen core

### Inspection boundary

This repository is the curated public inspection surface.

It contains the public evidence, structural notes, and milestone summaries intended for external review.

The complete Lean source is preserved separately in a private repository and is not part of the current public inspection surface. Claims about the Lean core here are therefore limited to the stated frozen milestone, version, commit, imported module set, and reported build/runtime status.

## Start here

The repository is organized by evidentiary standing rather than chronology. The following artifacts and checkpoints provide the shortest inspection path through the established work and its current engineering frontier.

1. **EXTERNAL EVIDENCE — U.S. Patent No. 12,730,417**

   **Systems and Methods for State-Coherent Recursive Processing**

   U.S. Patent Application No. 19/394,177 progressed through substantive examination, allowance of all 17 claims, and issuance as **U.S. Patent No. 12,730,417 on September 8, 2026**.

   The patent provides an external examination and prosecution checkpoint for the state-coherent recursive-processing architecture developed along this research lineage. It is not treated as validation of the broader structural framework, formal results, or downstream research interpretations.

2. **ENGINEERING RESULT — [Deterministic execution-control implementation](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/EKA_Deterministic_Execution_Control_Technical_Evidence_Note.pdf)**

   Completed supervisory control layer separating probabilistic or adaptive candidate generation from deterministic execution authority.

   Candidate continuations are gated before actuation through `RESPOND`, `REFUSE`, `DEFER`, or `SILENCE`, with explicit execution interlocks, recovery conditions, and bounded halt behavior. The defined 13-criterion behavioral target was completed and frozen with no remaining core-build dependencies.

   The result is bounded to the demonstrated supervisory architecture and stated behavioral target. It does not establish production deployment, universal coverage, or correctness outside that target.

3. **FORMAL RESULT — Lean finite semantic core — completed and frozen at `v0.1.126` (`28a5933`)**

   The defined finite semantic target is closed and package-integrated: 9/9 closure criteria are satisfied; Lean module checks PASS; root compile PASS; `lake build` PASS (18 jobs); runtime PASS.

   The formal result is bounded to the finite semantic core represented in the frozen milestone. It establishes the stated distinctions within that formal scope and confirms their integration into the package root. It does not establish ontological exhaustiveness, asymptotic complexity claims, P vs NP, or any stronger result not explicitly represented in the frozen core.

4. **ACTIVE ENGINEERING FRONTIER — recursive artifact identity, verification, provenance, and authority**

   The engineering program has continued beyond the frozen execution-control and Lean milestones into deterministic preservation and verification of computational and formal artifacts across recursive continuation.

   The active frontier concerns artifact identity, reproducible environment reconstruction, replay of formal verification, authority-surface characterization, provenance, bounded claim correspondence, authorized standing, and epistemic preservation.

   These activities constitute a new engineering surface downstream of the established results. Their standing depends on their own implementation and verification evidence and does not retroactively enlarge the scope of the frozen execution-control or Lean results.

5. **STRUCTURAL INTERPRETATION — [Strategic implications — bounded execution as AI infrastructure](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/Strategic_Implications_Bounded_Execution_as_AI_Infrastructure.pdf)**

   Downstream strategic analysis, not primary technical evidence.

   The paper examines why reliable execution under uncertainty may become a more durable bottleneck than intelligence generation alone and considers a control layer centered on execution gating, invariant preservation, auditability, fail-safe behavior, and institutional trust.

### Stopping rule

The finite semantic core is frozen under the rule:

> **STOP ONTOLOGICAL EXPANSION**

The purpose of the stopping rule is methodological: once the required structural distinctions are represented, imported, and verified, stronger claims must be introduced as new research objects rather than silently folded into the existing core.

The formal repository separates roles explicitly: `main` is the frozen canonical semantic baseline; `research/verification-construction` contains completed bounded Phase-A research establishing verification ≠ construction within its stated formal scope, with no computational-complexity or P vs NP claim; `infra/codespaces-lean` provides the reproducible Lean/Codespaces environment; and `public/inspection-surface` provides the repository-facing documentation and inspection layer.

`K5Execution` and this repository serve complementary roles. `K5Execution` is the canonical Lean-focused formal source for reproducibility and bounded theorem work; `admissibility-execution-control` preserves the broader research, engineering, architectural, evidentiary, and research-lineage context. Further formal continuation beyond the frozen baseline requires a specifically bounded engineering theorem, executable requirement, or separately licensed research branch.

## Structural insights

These notes are the reader-facing bridge into the framework: they begin from familiar AI terminology or foundational arguments and then expose the underlying structural distinctions. 

- [Structural Retyping of Contemporary AI Concepts](./structural-insights/structural-retyping-of-contemporary-ai-concepts.md)
- [Simulation Is Not an Ontology](./structural-insights/simulation-is-not-an-ontology.md)

These notes provide interpretive bridges into the structural framework without changing the primary evidence hierarchy above.

## Research lineage
The engineering program emerged from a longer independent first-principles inquiry into admissibility, persistence, representation, and constrained continuation.
That upstream framework was not treated as sufficient on its own. It generated a concrete downstream engineering question: how can an adaptive computational system continue changing while preserving the invariants required for coherent operation?
That question led to a substrate-independent recursive-control architecture that progressed through substantive U.S. patent examination to allowance with all 17 claims allowed.
The work then continued beyond the patent into deterministic continuation and execution-control mechanisms, finite behavioral completion, and a Lean formalization whose defined semantic core is now closed, verified, frozen, and package-integrated at `v0.1.126`.
The upstream framework remains independently contestable; the patent, implementation, and formalization are intended to be inspectable as separate downstream consequences rather than requiring prior agreement with the ontology.
Earlier working notes documenting the pre-engineering development path are preserved in [`research-lineage/`](./research-lineage/).

## Why this is unusual

The unusual signal is not any single artifact but the convergence of independently developed structural work with separately inspectable engineering, external examination, behavioral completion, and formal closure.

These downstream checkpoints do not establish the upstream framework as correct, nor do they establish universal generalization. They make the trajectory technically inspectable without requiring prior agreement with the framework that generated it.

## Current status

### Patent

- **U.S. Patent No. 12,730,417 — issued September 8, 2026**
- All 17 claims were allowed during prosecution of U.S. Patent Application No. 19/394,177.
- The issued patent is maintained as an external examination and prosecution checkpoint.
- Patent issuance is not treated as proof or validation of the repository's broader ontological, mathematical, engineering, or interpretive claims.

### Execution control

- Deterministic execution-control implementation: completed
- Finite behavioral target: completed and frozen
- Execution authority remains explicitly separated from adaptive or probabilistic candidate generation.

### Lean formalization

- Lean formalization: privately preserved
- Canonical semantic baseline: `main` at `28a5933`
- Annotated tag: `v0.1.126`, resolving to the same commit
- Semantic closure: 9/9 defined closure criteria satisfied
- Verification:
  - `lake build` — PASS (18 jobs)
  - `lake env lean K5Execution.lean` — PASS
  - `lake env lean Main.lean` — PASS
- Reproducible environment: `infra/codespaces-lean`, Full Rebuild validated
- Public inspection layer: `public/inspection-surface`

### Completed bounded research

- Phase-A research on `research/verification-construction`: completed and closed
- Phase-A result: verification ≠ construction within the stated formal scope
- No computational-complexity or P vs NP claim is established by the frozen formal core.

### Formal boundary

- Formal stopping rule: `STOP ONTOLOGICAL EXPANSION`
- Further formal continuation requires a specifically bounded downstream engineering theorem, executable requirement, or separately licensed research branch.


### Established boundary vs open research

The repository distinguishes completed evidence from active and prospective research. Completed results retain their original evidentiary scope; later engineering or research does not retroactively enlarge what those results establish.

**Established and frozen**

- U.S. Patent No. 12,730,417 as an external examination and prosecution checkpoint
- completed deterministic execution-control implementation and finite behavioral target
- Lean finite semantic core frozen at `v0.1.126`
- completed bounded Phase-A result establishing verification ≠ construction within its stated formal scope
- explicit separation of representation, realization, admissibility, epistemic status, verification, construction, capability, and authority
- formal stopping rule: `STOP ONTOLOGICAL EXPANSION`

**Active engineering frontier**

- deterministic preservation and verification of artifact identity across recursive continuation
- reproducible environment and dependency reconstruction
- replay of formal verification under reproduced conditions
- characterization of authority surfaces and provenance
- bounded correspondence between verified artifacts and the claims attached to them
- preservation of authorized standing and epistemic status across downstream continuation

**Open research**

- composition and inheritance of authority across independently evolving loci
- preservation of provenance and attachment relations under recursive modification, migration, compression, and recovery
- certified autonomous regions with bounded exported authority envelopes
- cross-locus propagation of independently verified results without unauthorized authority inheritance
- persistent navigation across large formal research spaces through constraint accumulation, branch elimination, verified continuation, and bounded result propagation
- P vs NP and other Millennium-problem spaces as prospective stress environments for this research architecture; no claim of progress toward solving those problems is made here
- broader consequences and additional applications of the structural framework

Open research is not treated as an implicit extension of the frozen core. Active engineering results acquire standing only through their own implementation and verification evidence, and prospective research directions remain explicitly non-established until independently realized.
- broader consequences of the structural framework
- additional applications and retypings

Open questions are not treated as implicit extensions of the frozen core.
