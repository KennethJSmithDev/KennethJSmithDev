# Kenneth J. Smith

**Independent Research Engineer · Developer Tools · Systems Architecture**

I work best where the specification does not exist yet.

I turn ambiguous technical bets into bounded prototypes, make systems reveal what is actually true, and preserve enough evidence to decide what should be built next.

My work spans developer tools, agentic software development, systems architecture, and frontier runtime research. A recurring question connects it:

> **Intent → Creation**

How can human intent become a real, maintainable system without losing meaning, ownership, evidence, or human authority along the way?

## Shipped product

### OpsDeck 1.0.0

An open-source, native IRIS-hosted operations environment built around observed state, operation rehearsal, explicit authority, authoritative read-back, and evidence-backed verification.

The v1.0.0 release was qualified against a disposable Docker IRIS 2026.2 / IPM 0.10.8 target. Its release qualification reports 259 tests. OpsDeck keeps requested action, observed state, execution authority, and verified outcome distinct.

- [Repository and README](https://github.com/KennethJSmithDev/OpsDeck)
- [v1.0.0 release](https://github.com/KennethJSmithDev/OpsDeck/releases/tag/v1.0.0)
- [v1.0.0 release qualification](https://github.com/KennethJSmithDev/OpsDeck/blob/main/docs/RC_1_0_0_QUALIFICATION_20261004.md)
- [Capability inventory](https://github.com/KennethJSmithDev/OpsDeck/blob/main/docs/CAPABILITY_INVENTORY.md)
- [Live demo](https://kennethjsmithdev.github.io/OpsDeck/)

## Frontier systems research

### Unreal Engine 5.8 · Native Wasm64 · WebGPU

Research into a native 64-bit WebAssembly browser execution path for Unreal Engine 5.8 and its interaction with browser GPU infrastructure. The work separates qualification layers so a pass at one boundary is not mistaken for proof of the next.

**Accepted milestones**

- Native Wasm64 compile and link for the real `webGPU_Lab` Web/Game target.
- Controlled browser startup through UE `PreInit`.
- Controlled Dawn adapter and device initialization.
- 60 foreground browser animation-frame callbacks in qualified controls.
- Diagnostic RHI surface/backbuffer presentation.

**Still open**

- Fully cooked `webGPU_Lab` browser Game startup and Game/world execution.
- UE Renderer scene pixels from the real Game path.
- Full Web cook, currently blocked in global shader compilation.
- Full exporter/product completion.

The accepted milestones establish a browser runtime path and diagnostic presentation; they do not establish full UE Renderer output or a completed browser product. Public descriptions focus on architecture, qualification boundaries, and findings. Engine-derived source, licensed assets, and unpublished implementation remain private.

## Intent-driven and agentic systems

### Assembly

A research direction for translating intent into inspectable, validated creation:

`intent → semantic requirements → capability discovery → provider resolution → inspectable plan → creation/materialization → observation → validation → evidence → human review`

The broader provider-neutral architecture remains in development. Historical bounded Assembly prototype evidence is distinct from this wider direction.

### Doc's Lab

An AI-directed, human-reviewed production environment exploring how agents can create complex software while real environments retain authority over state and consequential decisions remain reviewable.

### EGEHAR

**Evidence-Gated Execution + Hierarchical Adaptive Representation** is an evolving engineering methodology shaped by repeated work on uncertain systems. Its working principles include establishing current reality, identifying ownership, bounding authority and scope, reusing existing capability, validating deterministically, and preserving evidence and uncertainty. It remains a practice evaluated through projects, not a universally validated theory.

## Research portfolio

Current and emerging case-study work follows the question, reality, bet, execution, evidence, failure, decision, and public-boundary trail.

- **OpsDeck** — shipping and qualifying an evidence-first operations product.
- **Native Wasm64 / WebGPU** — qualifying a frontier browser runtime path one milestone at a time.
- **Babylon.js / WebGPU** — a failed visual qualification and the decision justified by its evidence.
- **Assembly / Doc's Lab** — exploring semantic intent, capability resolution, and human-reviewed creation.

Some case studies are still being prepared. Public material will expose architecture, acceptance criteria, sanitized receipts, and measured outcomes while withholding licensed or confidential implementation.

## How I work

```text
Ambiguous problem
      ↓
Establish reality and ownership
      ↓
Find existing capability
      ↓
Form the smallest useful bet
      ↓
Prototype and observe
      ↓
Accept, reject, or narrow the claim
      ↓
Preserve evidence and uncertainty
      ↓
Build what the evidence justifies
```

I use AI for research, implementation, and exploration. I do not treat generated output as authority. A successful API call, compile, link, runtime initialization, or rendered frame proves only the boundary it actually crossed.

The technologies change. The underlying work is to determine what should exist, discover what reality permits, build the smallest useful proof, and learn from what happens.
