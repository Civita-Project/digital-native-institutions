# Computable Institutions — Canonical Technical Stack

## Epistemic Status

This file defines a **canonical realization stack** for
**Computable Institutions (CI)**.

It does **not** define what a Computable Institution *is*.
That definition is given in:

- `computable_institutions.md`
- `ontology.md`

This stack specifies **how CI-compliant institutions may be instantiated**
without violating CI invariants.

Any system may use a different stack and still qualify as CI,
provided all CI constraints are satisfied.

---

## Dependency Order (Hard)

1. computable_institutions.md   (meta-class)
2. ontology.md                  (Substrate-0′)
3. dni_theory.md                (institutional type)
4. sfeu_blueprint.md            (execution substrate)

This file is **downstream** of all the above.

---

## Purpose

This stack answers one question only:

> What technical components are minimally required to instantiate
> a **Digital Native Institution (DNI)** that qualifies as a
> **Computable Institution (CI)**?

It is a **realization guide**, not a definition.

---

## Stack Layers (CI-Constrained)

### Layer 1 — Identity (Fact Attribution)

- Cryptographic identity
- Non-repudiation
- Revocation

CI constraint:
Identity may attribute facts; it may not assign meaning.

---

### Layer 2 — Documents & Evidence

- Content-addressed storage
- Signature provenance
- Immutable lineage

CI constraint:
Evidence integrity ≠ semantic validity.

---

### Layer 3 — Rule Representation

- Typed schemas
- Deterministic rule DSLs
- Versioned rule sets

CI constraint:
Rules express norms; they do not interpret cases.

---

### Layer 4 — Context Binding

- Jurisdiction
- Temporal validity
- Rule version selection

CI constraint:
Context is selected, not inferred.

---

### Layer 5 — Execution (SFEU)

- Deterministic state transitions
- No discretion
- Explicit failure

CI constraint:
Execution enforces; it never decides.

---

### Layer 6 — Exception Routing

- Structured failure emission
- Governance handoff
- No silent override

CI constraint:
Exceptions surface institutional limits; they do not resolve them.

---

### Layer 7 — Settlement & Obligation

- Programmable consequences
- Traceable outcomes

CI constraint:
Settlement executes outcomes; it does not define justice.

---

### Layer 8 — Audit & Attestation

- Append-only logs
- Independent verification
- Reconstruction

CI constraint:
Auditability is mandatory, not optional.

---

### Layer 9 — Interpretation (Non-Binding)

- Human analysis
- RSI / AI explanation
- Simulation and diagnostics

CI constraint:
Interpretation has **zero execution authority**.

---

## What This Stack Forbids

Any stack claiming CI **must not**:

- embed interpretation in execution
- allow silent discretion
- collapse DNI and SFEU
- treat CI as a platform or product
- treat AI as decision-making authority

Violation → system is **not CI**, regardless of intent.

---

## Status

Frozen.

This file may change only if:

- CI definition changes,
- DNI theory is revised,
- or SFEU execution invariants change.
