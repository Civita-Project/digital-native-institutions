# Presentation Layer Guide
## Version 2.0 — Truth-Preserving · Non-Authoritative · Drift-Resistant

---

## Epistemic Status (Hard Constraint)

This document governs **presentation only**.

It defines how **already-frozen truth artifacts** (ontology, theory, execution, falsification)
may be *expressed* in prose, diagrams, chapters, and defenses.

This guide:
- does **not** define ontology,
- does **not** define theory,
- does **not** define execution,
- does **not** define falsification,
- does **not** validate correctness.

If any presentation artifact changes meaning upstream, the presentation is invalid.

---

## Dependency Order (Explicit)

All presentation artifacts governed by this guide are strictly subordinate to:

1. `substrate0_prime_purity_test.md`
2. `arc_sequencing_protocol.md`
3. `ontology.md`
4. `dni_theory.md`
5. `dni_blueprint.md`
6. `sfeu_blueprint.md`
7. `sfeu_prototype.md`
8. `corruption_equilibrium.md`
9. `counterfactuals.md`
10. `failure_case_canon.md`
11. `dnm_methodology.md`
12. `dissertation_frame.md`

Presentation may not introduce constraints upstream of this list.

---

## One-Way Authority Rule

Truth flows **one way only**:

``
Substrate-0′ / Theory / Execution / Falsification
↓
Presentation
``


Any reverse influence → **INVALID**.

---

## Core Invariant: Deletability

> **If all presentation artifacts are deleted,  
> nothing upstream changes.**

If deletion alters:
- ontology,
- theory,
- execution design,
- falsification logic,
- empirical claims,

then the presentation violates this guide.

---

## Allowed Presentation Functions (MECE)

Presentation artifacts may:

1. **Describe**
- summarize frozen claims,
- restate definitions verbatim or with equivalent wording.

2. **Map**
- align chapters to frozen files,
- reference where claims originate.

3. **Sequence**
- order exposition for readability,
- manage cognitive load for examiners.

4. **Translate**
- adapt terminology to evaluator vocabulary,
- without introducing new meaning.

5. **Illustrate**
- visualize relationships already defined elsewhere,
- without adding entities or mechanisms.

---

## Explicitly Forbidden Actions

Presentation artifacts must **not**:

- introduce new concepts, entities, or mechanisms,
- reinterpret status-functions (X, Y, C),
- justify or defend theory choices,
- propose alternatives or improvements,
- weaken falsification conditions,
- smooth over counterfactual failures,
- claim desirability, inevitability, or superiority,
- substitute narrative for evidence,
- import evaluator standards as truth criteria.

Any violation → **FAIL (Purity Test)**.

---

## Chapter-Level Constraints (CUTIP Context)

### Chapter 1 — Problem & Framing
- May describe observed failures and context.
- Must not define new theory.
- All claims must point to upstream files.

### Chapter 2 — Theory & Literature
- May present DNI theory **as defined**, not extended.
- Literature is contextual, not authoritative.
- No reinterpretation of ontology permitted.

### Chapter 3 — Method & Design
- May describe SFEU and DNM **as frozen**.
- Must not add execution logic.
- All methodological claims must reference DNM.

---

## Diagrams & Visuals

All diagrams must:

- reference a frozen source file,
- label scope (ontology / theory / execution / presentation),
- avoid arrows implying reverse authority,
- avoid unstated causal claims.

Any diagram that introduces meaning independently is invalid.

---

## Citation Rule

Citations in presentation:

- provide **context**, not validation,
- do not override falsification,
- do not define correctness.

Authority resides in execution and counterfactuals, not citations.

---

## Relationship to EVP & Award Artifacts

EVP, award outlines, and rulers are **presentation-only** and are governed by this guide.

They must:
- pass deletability,
- respect one-way authority,
- never justify truth claims.

If conflict exists, **presentation artifacts are discarded**.

---

## Drift Detection Trigger

If any of the following appear in presentation text:
- new definitions,
- hidden assumptions,
- softened falsifiers,
- evaluator authority claims,
- execution judgments,

Action:
1. Stop.
2. Identify earliest violated upstream file.
3. Fix upstream or delete presentation text.

---

## Status

**Frozen (v2.0).**

This guide changes only if:
- ARC sequencing changes, or
- presentation is formally granted epistemic authority (which would invalidate the project).


