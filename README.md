# Admissibility and Deterministic Execution Control

Independent first-principles research on admissibility, representation, constrained continuation, and deterministic control for adaptive systems.

The work developed outside the conventional AI/ML research pipeline and led to a broader engineering program on state coherence, bounded continuation, execution gating, and fail-safe recovery.

That engineering path produced an allowed U.S. patent application for state-coherent recursive processing, a completed deterministic execution-control implementation, and a finite Lean semantic core now frozen and package-integrated at `v0.1.126`.

The repository is organized so that the engineering artifacts can be inspected independently of the upstream first-principles framework from which the control problem emerged.

## Start here

1. **[Allowed U.S. patent application — Systems and Methods for State-Coherent Recursive Processing](https://github.com/reachbsr-EKA/admissibility-notes/blob/main/USPTO_Allowance_Evidence_Extract_P14190US01.pdf)**

2. **[Deterministic execution-control implementation](https://github.com/reachbsr-EKA/admissibility-notes/blob/main/EKA_Deterministic_Execution_Control_Technical_Evidence_Note.pdf)**

3. Lean finite semantic core: completed, verified, frozen, and package-integrated at `v0.1.126`
- Closure: 9/9 defined criteria closed
- Verification: Lean module checks PASS · root compile PASS · `lake build` PASS (18 jobs) · runtime PASS
- Stopping rule: `STOP ONTOLOGICAL EXPANSION`

4. **[Strategic implications — bounded execution as AI infrastructure](https://github.com/reachbsr-EKA/admissibility-notes/blob/main/Strategic_Implications_Bounded_Execution_as_AI_Infrastructure.pdf)**  
   Strategic analysis of why the durable bottleneck in high-consequence AI may be reliable execution under uncertainty rather than intelligence generation alone. The paper argues for a control layer centered on execution gating, invariant preservation, auditability, fail-safe behavior, and institutional trust.

## Research lineage

The engineering program emerged from a longer independent first-principles inquiry into admissibility, persistence, representation, and constrained continuation.

That upstream framework was not treated as sufficient on its own. It generated a concrete downstream engineering question: how can an adaptive computational system continue changing while preserving the invariants required for coherent operation?

That question led to the recursive-control architecture that progressed through U.S. patent examination to allowance, and subsequently to deterministic continuation and execution-control mechanisms that were implemented and behaviorally verified.

The upstream framework remains independently contestable; the downstream engineering artifacts are intended to be inspectable on their own technical merits.

Earlier working notes documenting the pre-engineering development path are preserved in [research-lineage/](./research-lineage/).

## Why this is unusual

Two aspects of the work are intentionally explicit.

First, the allowed U.S. patent application is not limited to a narrow AI-safety implementation. Its architecture is described as substrate-independent and extends across adaptive computational systems through invariant monitoring, bounded continuation, deterministic feedback, fail-safe recovery, distributed coordination, and substrate adaptation.

Second, the work emerged outside the conventional AI/ML research career pipeline. My background spans Electrical & Electronics Engineering, software consulting, operations, entrepreneurship, and commercial leadership. The resulting control-systems framing was developed independently before being carried into AI-safety and superintelligence research.

Neither fact is offered as proof of correctness. Their significance is that the engineering program arose from an unusually independent problem-formation path and is intended to be inspected on its technical merits.

Current status

- Upstream structural framework: established
- U.S. patent application derived from downstream engineering work: allowed
- Deterministic execution-control implementation: completed and behaviorally verified
- Lean formalization: active
- Current Lean finite-core closure: 7 of 8 criteria structurally closed; final repository-wide anti-lifting audit pending
