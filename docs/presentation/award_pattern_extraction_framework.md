# **award_pattern_extraction_framework.md**
### *Version 1.1 — Descriptive Pattern Grammar (Non-Authoritative)*

---

## Epistemic Status (Strict)

This file defines a **descriptive pattern grammar** for analyzing the *language and structure*
used by external award bodies when they retrospectively describe work they recognize.

It is **explicitly non-authoritative**.

This file:
- does **not** define ontology,
- does **not** define theory,
- does **not** validate DNI,
- does **not** influence SFEU design,
- does **not** filter for Substrate-0′ compatibility,
- does **not** act as a validator.

Any use of this file that influences Substrate-0′ artifacts is **invalid**.

---

## Dependency Order (Explicit)

This framework is subordinate to:

1. `substrate0_prime_purity_test.md`
2. `ontology.md`
3. `dni_theory.md`
4. `dni_blueprint.md`
5. `sfeu_blueprint.md`
6. `sfeu_prototype.md`

If a conflict exists, this file is discarded.

---

## Purpose

Awards encode **implicit descriptive regularities** about how evaluators *talk about* impact,
rigor, novelty, and mechanism *after the fact*.

The purpose of this framework is to:

> Catalog **recurring descriptive categories** in award language  
> without importing their assumptions upstream.

No claim is made that these categories are correct, complete, or desirable.

---

## What This File Is NOT

This file must not be used to:

- derive evaluative criteria,
- define correctness,
- constrain ontology,
- shape institutional architecture,
- influence DNI necessary conditions,
- override falsification logic,
- replace empirical testing.

Awards do not validate institutions.  
They describe recognition narratives.

---

## Canonical Descriptive Pattern Classes (MECE)

These classes define **what types of language are observed**, not what is required.

---

### 1. Mechanism Description Patterns

Language describing:
- primitives mentioned
- causal sequencing
- determinacy claims
- scalability narratives
- exception or edge-case discussion

**Output label:** `mechanism_patterns`

---

### 2. Ontological Framing Patterns

Language referencing:
- object types
- level separation (facts / rules / execution)
- constitutive vs. regulative framing
- stability of categories

No ontological correctness is inferred.

**Output label:** `ontology_patterns`

---

### 3. Predictive & Falsification Language

Language describing:
- prediction claims
- distinctiveness
- empirical exposure
- stated failure modes
- claimed limits

This is descriptive only.

**Output label:** `predictive_patterns`

---

### 4. Counterfactual Language Patterns

Language referencing:
- “if not” scenarios
- alternative trajectories
- sensitivity to assumptions
- reversibility narratives
- detectability of differences

**Output label:** `counterfactual_patterns`

---

### 5. Contrast-Class Language

Language used to:
- differentiate from prior work
- establish non-absorbability
- define boundaries
- signal paradigm shifts

**Output label:** `contrast_patterns`

---

### 6. Empirical Grounding Language

Language referencing:
- real-world plausibility
- institutional realism
- implementation narratives
- transferability claims
- alignment with observed phenomena

**Output label:** `empirical_patterns`

---

## Explicit Non-Functions

This framework does **not** perform:

- Substrate-0′ filtering
- Drift removal
- Metaphysics cleansing
- DNI or SFEU application
- Ruler construction
- Gap analysis
- Validation

Those activities, if any, are governed elsewhere and must pass the
**Substrate-0′ Purity Test independently**.

---

## Output Structure (Descriptive Only)

For any award corpus, extracted patterns must be structured as:

``
mechanism_patterns:

[...]

ontology_patterns:

[...]

predictive_patterns:

[...]

counterfactual_patterns:

[...]

contrast_patterns:

[...]

empirical_patterns:

[...]

``


These outputs are **raw descriptive artifacts** only.

---

## Status

**Frozen (v1.1).**

May change only if:
- the Substrate-0′ Purity Test changes, or
- this framework is removed entirely.


