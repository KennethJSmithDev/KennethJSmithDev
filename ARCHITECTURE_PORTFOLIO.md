# Architecture Portfolio

This page is a public-safe view of selected systems architecture, technical strategy, and engineering work.

It is intentionally selective. Active R&D, unreleased implementation details, private source, competition-sensitive material, and proprietary architecture remain private unless explicitly published elsewhere.

## Working pattern

I usually work from ambiguity toward evidence:

```text
Problem
  ↓
Current reality
  ↓
Constraints and ownership
  ↓
Capability map
  ↓
Candidate architectures
  ↓
Tradeoffs and smallest justified path
  ↓
Prototype / implementation boundary
  ↓
Validation and evidence
```

The goal is not to produce architecture theater. The goal is to reduce uncertainty enough that a team can make a defensible technical decision and know how to test it.

## Selected work

### OpsDeck

**Type:** Product architecture, operational tooling, provider integration, validation

**Problem:** Expose useful InterSystems IRIS operational state without inventing a second source of truth or hiding provider failures behind friendly UI.

**Architecture:** A thin web operations console over bounded provider adapters and authoritative IRIS APIs.

**Key design constraints:**
- IRIS remains authoritative.
- Provider errors stay distinct from valid empty results.
- Credentials are not persisted to repository files or browser storage.
- Read paths are bounded rather than arbitrary.
- Verification is claimed only where independently established.

**Evidence:** Public repository, live safe demo, automated tests, evaluator documentation, and qualified read-back behavior.

- Repository: https://github.com/KennethJSmithDev/OpsDeck
- Portfolio: https://kind-bush-04a42f20f.6.azurestaticapps.net/portfolio

### Assembly

**Type:** Systems architecture, creator tooling, semantic composition

Assembly is active development and its implementation remains private. The public case study is the authoritative public-facing surface for this work.

- Case study: https://kind-bush-04a42f20f.6.azurestaticapps.net/assembly

### Private R&D

Several active projects remain private because they contain unreleased architecture, experimental implementation, competition work, or material that would lose value if disclosed prematurely.

For those projects, the public portfolio exposes only the minimum useful evidence:
- problem class;
- constraints;
- high-level architecture;
- decisions and tradeoffs that are safe to disclose;
- validation status;
- what remains unverified;
- current maturity.

Private source code and implementation-specific details are not required to demonstrate systems thinking.

## Engagements

I am available for bounded remote work where the difficult part is determining what should be built before committing to implementation.

Typical work includes:
- technical discovery;
- system and solution architecture;
- product/system decomposition;
- feasibility studies;
- architecture and implementation planning;
- AI-assisted engineering workflows;
- prototype planning;
- technical due diligence;
- architecture review;
- validation strategy.

A typical engagement produces a concise handoff:

```text
Objective
→ current reality
→ constraints
→ architecture options
→ tradeoffs
→ recommended path
→ validation criteria
→ implementation handoff
```

## Evidence standard

Public claims are intentionally conservative. Active work may be described as in development, partially reproduced, or unverified rather than presented as finished.

That boundary matters more than making every project look complete.
