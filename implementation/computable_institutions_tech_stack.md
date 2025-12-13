# **Computable Institutions — Technical Stack**

### *Version 1.0 (Constitutive, Execution-Bound)*

---

## **Epistemic Status**

This document specifies the **technical realization layer** for **Computable Institutions**.

It does **not** define institutional meaning, policy intent, or governance outcomes.
It defines the **minimum technical primitives and boundaries** required to make
**Digital Native Institutions (DNI)** *computable*, *verifiable*, and *falsifiable*.

Accordingly:

1. All components listed here operate **below institutional meaning**.
2. No component may:

   * interpret law,
   * infer intent,
   * resolve ambiguity,
   * or substitute human governance.
3. This stack exists to **execute and attest** status-function mappings defined elsewhere.

Any system claiming to be a Computable Institution **must map cleanly onto this stack**.

---

## **1. Naming Resolution (Canonical)**

To prevent future drift, the following terms are **fixed**:

| Term                                      | Meaning                                                                           |
| ----------------------------------------- | --------------------------------------------------------------------------------- |
| **Digital Native Institution (DNI)**      | The *institutional form* defined by status-function rules executable via protocol |
| **Computable Institution**                | A DNI that is *realized* using the technical stack defined in this file           |
| **SFEU (Status-Function Execution Unit)** | The execution engine that enforces DNI rules                                      |
| **Civita**                                | The ecosystem / deployment context in which multiple DNIs operate                 |

**Key rule:**

> *DNI is the theory. Computable Institution is the implementation class. SFEU is the execution machinery.*

No term may collapse into another.

---

## **2. Stack Overview (Layered, Non-Interpretive)**

The Computable Institution stack consists of **nine strictly bounded layers**.

Each layer is:

* necessary,
* non-substitutable,
* non-interpretive,
* and falsifiable.

---

## **3. Layer 1 — Digital Identity**

**Purpose**
Bind institutional actions to **who** performed them.

**Required properties**

* cryptographic uniqueness
* authentication
* non-repudiation
* revocability
* temporal validity

**Explicit limits**

* does not infer intent
* does not assign legal meaning
* does not grant status by itself

**Failure signature**

* identity ambiguity → execution must fail

---

## **4. Layer 2 — Digital Documents & Evidence**

**Purpose**
Represent **what** is being claimed as X.

**Required properties**

* hash-based integrity
* cryptographic signatures
* provenance tracking
* immutable lineage

**Explicit limits**

* does not interpret semantics
* does not judge legal sufficiency

**Failure signature**

* unverifiable evidence → explicit exception

---

## **5. Layer 3 — Rule Representation (Declarative)**

**Purpose**
Encode **constitutive and procedural rules** in machine-verifiable form.

**Acceptable forms**

* text-based DSLs (e.g. CUE, Rego-like)
* versioned, auditable rule sets
* diff-able, human-readable constraints

**Explicit limits**

* rules express *conditions*, not meaning
* no probabilistic inference
* no hidden discretion

**Failure signature**

* rule conflict or ambiguity → execution halt

---

## **6. Layer 4 — Context Binding**

**Purpose**
Determine **which context C applies**.

**Required properties**

* jurisdiction selection
* temporal versioning
* scope limitation

**Explicit limits**

* no reinterpretation of law
* no conflict resolution between statutes

**Failure signature**

* indeterminate context → explicit failure

---

## **7. Layer 5 — Status-Function Execution (SFEU Core)**

**Purpose**
Execute **X → Y-in-C** transitions.

**Implemented by**

* **SFEU (Status-Function Execution Unit)**

**Required properties**

* deterministic execution
* invariant enforcement
* explicit success or failure
* no discretionary override

**Explicit limits**

* never defines Y
* never redefines C
* never “fixes” bad inputs

**Failure signature**

* invariant violation → logged rejection

---

## **8. Layer 6 — Exception Routing**

**Purpose**
Handle cases where X **fails to count as Y-in-C**.

**Required properties**

* explicit failure signaling
* structured exception output
* governance handoff (outside protocol)

**Explicit limits**

* does not resolve disputes
* does not suppress failure

**Failure signature**

* silent success = system invalid

---

## **9. Layer 7 — Settlement & Obligation Execution**

**Purpose**
Execute **institutionally binding outcomes**.

**Required properties**

* machine-verifiable settlement
* timestamped execution
* traceable obligation fulfillment

**Explicit limits**

* no policy optimization
* no redistribution logic
* no discretionary adjustment

**Failure signature**

* settlement mismatch → audit alert

---

## **10. Layer 8 — Audit & Attestation Ledger**

**Purpose**
Record **what happened**, not why.

**Required properties**

* append-only logs
* cryptographic attestations
* independent verifiability

**Explicit limits**

* does not summarize meaning
* does not judge outcomes

**Failure signature**

* non-reconstructible history → invalid system

---

## **11. Layer 9 — Transport & Storage**

**Purpose**
Enable **open, inspectable persistence and transmission**.

**Acceptable mechanisms**

* open protocols (e.g. email)
* content-addressed storage (e.g. IPFS-class)
* protocol-agnostic addressing

**Explicit limits**

* transport ≠ authority
* storage ≠ meaning

**Failure signature**

* opaque storage → audit failure

---

## **12. Role of AI / RSI (Explicit Boundary)**

AI systems (including RSI):

* may assist humans in:

  * inspection
  * explanation
  * simulation
* **may not**:

  * execute status-functions,
  * override SFEU outcomes,
  * create institutional facts.

AI is **advisory only**.

---

## **13. Falsifiability Criteria**

A system claiming to be a **Computable Institution** is falsified if:

* execution outcomes cannot be reconstructed,
* corruption does not relocate observably,
* exceptions are silently bypassed,
* protocol resolves ambiguity,
* or execution requires discretionary override.

---

## **14. Relationship to DNI Theory**

* DNI theory defines **what must be true**.
* This stack defines **what must exist technically**.
* SFEU enforces the boundary.

No layer may contradict `ontology.md` or `dni_theory.md`.

---

## **15. Frozen**

This file is **frozen** unless:

* Substrate-0′ contradictions are found, or
* DNI theory changes at the ontological level.


