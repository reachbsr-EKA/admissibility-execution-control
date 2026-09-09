# Admissibility and Deterministic Execution Control

Independent first-principles research on admissibility, representation, constrained continuation, state coherence, and deterministic execution control for adaptive systems.

The work developed outside the conventional AI/ML research pipeline. An independently formed structural framework around admissibility, persistence, representation, and constrained continuation generated a concrete downstream control problem: how can an adaptive computational system continue changing while preserving the invariants required for coherent operation?

That question produced a substrate-independent recursive-control architecture that progressed through substantive U.S. patent examination, allowance of all 17 claims, and issuance as U.S. Patent No. 12,730,417 on September 8, 2026.

The engineering program subsequently continued into deterministic execution control, finite behavioral completion, and a Lean semantic core closed, verified, frozen, and package-integrated at `v0.1.126`. Those completed results now form a bounded baseline for a further engineering frontier concerned with preservation and verification of artifact identity, reproducible execution state, provenance, authority, claim correspondence, and epistemic standing across recursive continuation.

The repository is organized so that external evidence, established engineering results, formal results, active engineering, structural interpretations, historical provenance, and open research remain explicitly distinguished.

Completed engineering results and active engineering are separated deliberately: the former have a bounded public evidence surface, while the latter may contain substantial implementation work whose complete public evidence package has not yet been frozen.

Each downstream artifact or research object can therefore be inspected according to its own evidentiary standing without requiring prior agreement with the first-principles framework that generated the research trajectory.

Four transitions in this trajectory are load-bearing rather than merely chronological:

1. **structural admissibility → engineering continuation**
2. **represented continuation → execution authority**
3. **informal structural distinctions → formal and independently inspectable realization**
4. **verified realization → preservation of warranted standing across recursive continuation**

The fourth transition defines the current engineering frontier. Verification establishes something about an artifact under specified conditions; it does not by itself establish that the artifact's identity, provenance, authority, claim correspondence, and epistemic status remain correctly preserved as that artifact is reproduced, transferred, incorporated, or recursively continued.

The current engineering program therefore extends deterministic control from the authorization of individual continuations toward preservation of the relations required for warranted downstream reliance.

### Evidence boundary

This repository distinguishes artifacts and claims by evidentiary standing:

- **EXTERNAL EVIDENCE** — independently issued, examined, or otherwise externally established material
- **ENGINEERING RESULT** — implemented and behaviorally demonstrated system result within a stated target
- **FORMAL RESULT** — machine-checked result within an explicitly bounded formal scope
- **ACTIVE ENGINEERING FRONTIER** — implemented or developing engineering work whose complete public evidence surface has not yet been frozen
- **STRUCTURAL INTERPRETATION** — downstream analysis, conceptual retyping, or structural synthesis
- **HISTORICAL PROVENANCE** — earlier working material preserved to document research lineage
- **OPEN RESEARCH** — questions, hypotheses, prospective applications, or research directions not established by the frozen evidence base

These categories are intentionally non-transitive.

An artifact does not inherit the evidentiary standing of an upstream or downstream artifact merely because the two belong to the same research lineage. External examination, implementation, formal verification, structural interpretation, and open research each establish different things and must be evaluated within their own scope.

### Inspection boundary

This repository is the curated public inspection surface.

It contains public evidence, structural notes, milestone summaries, historical provenance, and bounded descriptions of active or prospective research intended for external review.

The complete Lean source underlying the frozen finite semantic core is preserved separately in a private repository and is not part of the current public inspection surface. Claims about that core are therefore limited here to the stated frozen milestone, version, commit, imported module set, and reported build and runtime status.

Active engineering may likewise extend beyond the artifacts currently exposed in this repository. Where a complete public evidence package has not yet been frozen, such work is identified as **ACTIVE ENGINEERING FRONTIER** rather than presented as an established **ENGINEERING RESULT**.

Open research is presented only as research direction. Prospective applications, including navigation of large formal problem spaces, do not acquire the standing of established engineering or formal results merely by appearing in the same research lineage.

## Start here

The repository is organized by evidentiary standing rather than chronology. The following artifacts and checkpoints provide the shortest inspection path through the established work and its current engineering frontier.

1. **EXTERNAL EVIDENCE — [U.S. Patent No. 12,730,417](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/US_Patent_12730417_B1.pdf)**

   **Systems and Methods for State-Coherent Recursive Processing**

   U.S. Patent Application No. 19/394,177 progressed through substantive examination, allowance of all 17 claims, and issuance as **U.S. Patent No. 12,730,417 B1 on September 8, 2026**.

   The issued patent provides the primary external examination and prosecution checkpoint for the state-coherent recursive-processing architecture developed along this research lineage.

   Historical prosecution materials, including the earlier allowance evidence, are retained separately as provenance.

   The patent is treated as external evidence of examination and issuance. It is not treated as validation of the broader structural framework, formal results, or downstream research interpretations presented in this repository.

2. **ENGINEERING RESULT — [Deterministic execution-control implementation](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/EKA_Deterministic_Execution_Control_Technical_Evidence_Note.pdf)**

   Completed supervisory control layer separating probabilistic or adaptive candidate generation from deterministic execution authority.

   Candidate continuations are gated before actuation through `RESPOND`, `REFUSE`, `DEFER`, or `SILENCE`, with explicit execution interlocks, recovery conditions, and bounded halt behavior. The defined 13-criterion behavioral target was completed and frozen with no remaining core-build dependencies.

   The result is bounded to the demonstrated supervisory architecture and stated behavioral target. It does not establish production deployment, universal coverage, or correctness outside that target.

3. **FORMAL RESULT — Lean finite semantic core — completed and frozen at `v0.1.126` (`28a5933`)**

   The defined finite semantic target is closed and package-integrated: 9/9 closure criteria are satisfied; Lean module checks PASS; root compile PASS; `lake build` PASS (18 jobs); runtime PASS.

   The formal result is bounded to the finite semantic core represented in the frozen milestone. It establishes the stated distinctions within that formal scope and confirms their integration into the package root. It does not establish ontological exhaustiveness, asymptotic complexity claims, P vs NP, or any stronger result not explicitly represented in the frozen core.

4. **ACTIVE ENGINEERING FRONTIER — deterministic verification across recursive continuation**

   The engineering program has continued beyond the frozen execution-control and Lean milestones into a developing verification architecture for preserving the warranted standing of computational and formal artifacts across recursive continuation.

   The current engineering surface includes:

   - candidate materialization and artifact identity;
   - reproducible environment and dependency reconstruction;
   - replay of formal verification;
   - characterization of formal authority surfaces;
   - provenance characterization and binding;
   - bounded correspondence between verified artifacts and attached claims;
   - determination of authorized standing; and
   - preservation of epistemic status across downstream continuation.

   The architectural objective is not merely to determine whether an artifact exists or whether a formal check passes. It is to preserve the relations required to determine **what was verified, under which conditions, from which provenance, with what authority, and what the resulting artifact is warranted to claim downstream**.

   This work is classified as **ACTIVE ENGINEERING FRONTIER** because substantial implementation exists while its complete public evidence surface has not yet been frozen in this repository. It does not inherit the evidentiary standing of the completed execution-control implementation or frozen Lean semantic core.

5. **STRUCTURAL INTERPRETATION — [Strategic implications — bounded execution as AI infrastructure](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/Strategic_Implications_Bounded_Execution_as_AI_Infrastructure.pdf)**

   Downstream strategic analysis, not primary technical evidence.

   The paper examines why reliable execution under uncertainty may become a more durable bottleneck than intelligence generation alone and considers a control layer centered on execution gating, invariant preservation, auditability, fail-safe behavior, and institutional trust.

### Stopping rule

The finite Lean semantic core is frozen under the rule:

> **STOP ONTOLOGICAL EXPANSION**

The stopping rule applies to the established semantic baseline. Its purpose is methodological: once the required structural distinctions are represented, imported, and verified within the defined formal scope, stronger claims must not be silently folded back into that core.

Further work therefore proceeds only when licensed by a distinct downstream object, including:

- a specifically bounded engineering theorem;
- an executable requirement;
- an independently defined verification obligation; or
- a separately identified research branch.

The frozen formal repository preserves these roles explicitly:

- `main` — canonical semantic baseline;
- `research/verification-construction` — completed bounded Phase-A research establishing verification ≠ construction within its stated formal scope, with no computational-complexity or P vs NP claim;
- `infra/codespaces-lean` — reproducible Lean/Codespaces environment;
- `public/inspection-surface` — repository-facing documentation and inspection layer.

`K5Execution` remains the canonical Lean-focused source for the frozen semantic baseline and bounded theorem work represented here.

This public repository serves a broader role: it preserves the research lineage while maintaining explicit separation among **EXTERNAL EVIDENCE**, **ENGINEERING RESULT**, **FORMAL RESULT**, **ACTIVE ENGINEERING FRONTIER**, **STRUCTURAL INTERPRETATION**, **HISTORICAL PROVENANCE**, and **OPEN RESEARCH**.

Downstream engineering may therefore continue beyond the frozen Lean baseline without reopening it. New implementations, verification systems, authority models, or research-navigation mechanisms acquire standing through their own evidence and do not retroactively modify the scope of the established formal core.

## Structural insights

These notes provide reader-facing bridges into the structural framework. They begin from familiar AI terminology or foundational arguments and expose underlying distinctions in admissibility, representation, realization, continuation, and control.

- [Structural Retyping of Contemporary AI Concepts](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/structural-insights/structural-retyping-of-contemporary-ai-concepts.md)
- [Simulation Is Not an Ontology](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/structural-insights/simulation-is-not-an-ontology.md)

These documents are classified as **STRUCTURAL INTERPRETATION**. They provide interpretive access to the research framework but do not enlarge the standing of the external evidence, engineering results, or formal results documented elsewhere in this repository.

Additional structural notes should be added only when a distinct public research object is ready for inspection rather than using this section to narrate active work ahead of its evidence.

## Research lineage

The engineering program emerged from a longer independent first-principles inquiry into admissibility, persistence, representation, and constrained continuation.

That upstream framework was not treated as sufficient on its own. It generated a concrete downstream engineering question: how can an adaptive computational system continue changing while preserving the invariants required for coherent operation?

That question led to a substrate-independent recursive-control architecture that progressed through substantive U.S. patent examination, allowance of all 17 claims, and issuance as [U.S. Patent No. 12,730,417 B1](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/US_Patent_12730417_B1.pdf) on September 8, 2026.

The work continued beyond the patent into deterministic execution control, finite behavioral completion, and a Lean formalization whose defined semantic core is closed, verified, frozen, and package-integrated at `v0.1.126`.

Completion of those milestones exposed a distinct downstream problem. Controlling whether a continuation may execute is not sufficient to establish whether an artifact produced through recursive continuation preserves the identity, provenance, verification state, authority, and epistemic standing required for downstream reliance.

That problem defines the current engineering frontier. It extends the research trajectory from **execution authority** toward **verification and preservation of warranted standing across recursive continuation**, while leaving the frozen semantic core unchanged.

A further research horizon follows from that engineering problem: whether independently evolving computational and formal loci can propagate warranted results, constraints, and exclusions across a larger search surface without erasure, false attachment, or unsupported authority inheritance. Large formal research spaces are prospective stress environments for that architecture; no result concerning computational complexity, P vs NP, or any Millennium problem is claimed by the established work.

The upstream structural framework remains independently contestable. The issued patent, completed engineering, frozen formalization, active engineering, and prospective research remain separately inspectable stages of one research lineage rather than mutually validating evidence.

Earlier working material documenting the pre-engineering development path is preserved in [`research-lineage/`](https://github.com/reachbsr-EKA/admissibility-execution-control/tree/main/research-lineage).

## Why this is unusual

The unusual signal is not any single artifact or claim. It is the emergence of a continuous research-to-engineering lineage in which structurally related results have been realized through different and separately inspectable forms of evidence.

The trajectory now includes:

- an independently developed first-principles structural framework;
- a substrate-independent recursive-control architecture subjected to substantive U.S. patent examination and issuance;
- a completed deterministic execution-control implementation with a frozen behavioral target;
- a finite Lean semantic core with an explicitly bounded and frozen theorem surface; and
- a subsequent engineering frontier concerned with preserving artifact identity, reproducibility, verification state, provenance, authority, claim correspondence, and epistemic standing across recursive continuation.

These layers are related by research lineage but are not interchangeable as evidence.

Patent issuance does not establish the upstream structural framework. Engineering success does not prove the ontology. Formal verification establishes only what is represented within the stated formal scope. Structural interpretation does not inherit the standing of a machine-checked result. Active engineering does not acquire the standing of earlier completed milestones merely because it developed from them.

The significance of the lineage is therefore not cumulative validation, but inspectability: each transition can be examined while its evidentiary boundary remains explicit.

## Current status

### Patent

- **Issued patent:** [U.S. Patent No. 12,730,417 B1](https://github.com/reachbsr-EKA/admissibility-execution-control/blob/main/US_Patent_12730417_B1.pdf)
- **Issue date:** September 8, 2026
- **Title:** *Systems and Methods for State-Coherent Recursive Processing*
- **Application:** U.S. Patent Application No. 19/394,177
- **Claims:** all 17 claims allowed during prosecution
- **Evidentiary status:** primary external examination and prosecution checkpoint
- Historical prosecution materials remain preserved as provenance.
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

### Active engineering

- Development status: active
- Evidentiary standing: `ACTIVE ENGINEERING FRONTIER`
- Current objective: deterministic verification and preservation of warranted artifact standing across recursive continuation
- Current engineering surface:
  - candidate materialization and artifact identity
  - reproducible environment and dependency reconstruction
  - replay of formal verification
  - formal authority-surface characterization
  - provenance characterization and binding
  - bounded correspondence between verified artifacts and attached claims
  - determination of authorized standing
  - preservation of epistemic status across downstream continuation
- The active engineering frontier is downstream of the completed execution-control and frozen Lean milestones but does not enlarge their established scope.
- A complete public evidence package for this frontier has not yet been frozen in this repository.

### Formal boundary

- Formal stopping rule: `STOP ONTOLOGICAL EXPANSION`
- Further formal continuation requires a specifically bounded downstream engineering theorem, executable requirement, or separately licensed research branch.


### Established boundary vs open research

The repository distinguishes completed and frozen work from active engineering and prospective research. These status partitions are separate from the evidentiary categories defined above: they describe where work currently stands, not what kind of evidence supports it.

**Established and frozen**

- U.S. Patent No. 12,730,417 as an external examination and prosecution checkpoint
- completed deterministic execution-control implementation and finite behavioral target
- Lean finite semantic core frozen at `v0.1.126`
- completed bounded Phase-A result establishing verification ≠ construction within its stated formal scope
- explicit separation of representation, realization, admissibility, epistemic status, verification, construction, capability, and authority
- formal stopping rule: `STOP ONTOLOGICAL EXPANSION`

**Active engineering**

- deterministic preservation and verification of artifact identity across recursive continuation
- reproducible environment and dependency reconstruction
- replay of formal verification under reproduced conditions
- characterization of authority surfaces and provenance
- bounded correspondence between verified artifacts and the claims attached to them
- preservation of authorized standing and epistemic status across downstream continuation

**Prospective research**

- composition and inheritance of authority across independently evolving loci
- preservation of provenance and attachment relations under recursive modification, migration, compression, and recovery
- certified autonomous regions with bounded exported authority envelopes
- cross-locus propagation of independently verified results without unauthorized authority inheritance
- persistent navigation across large formal research spaces through constraint accumulation, branch elimination, verified continuation, and bounded result propagation
- P vs NP and other Millennium-problem spaces as prospective stress environments for this research architecture; no claim of progress toward solving those problems is made here
- broader consequences and additional applications of the structural framework

Established results retain their original evidentiary scope. Active engineering acquires standing through its own implementation and verification evidence. Prospective research remains explicitly non-established until independently realized.
