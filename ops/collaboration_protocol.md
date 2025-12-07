### *Collaboration Protocol for the Digital Native Institutions Repository*

**How to interact with SR0, contribute safely, and avoid conceptual drift**

---

## **1. Purpose of This Document**

This protocol explains:

* how contributors should propose changes,
* how SR0 evaluates and integrates contributions,
* how to prevent drift in the Digital Native Institutions (DNI) and National Service Unit (NSU) theory,
* how to work productively within a high-rigor, formal academic framework.

This document is operational, not theoretical.
It governs collaboration, not the DNI/NSU ontology.

---

## **2. Governing Structure of the Repository**

This repository contains **three distinct categories of content**:

### **A. Frozen Theory (`/theory/`)**

These files define the institutional and methodological foundation of DNI and NSU.

They **must not be changed** unless explicitly authorized by the project owner.

### **B. Academic Drafts (`/dissertation/`)**

These files evolve over time as the dissertation is written.

Edits here must align with:

* frozen theory files
* CUTIP dissertation requirements
* purity rules
* methodological constraints

### **C. Operational Instructions (`/ops/`)**

These govern how SR0 behaves and how collaboration is conducted.

They are not part of the academic theory.

---

## **3. How to Propose a Contribution**

Every contribution or modification must be classified into one of four categories:

### **1. Extension**

Adds new material that fits the existing ontology.
**Allowed.**

### **2. Refinement**

Clarifies or sharpens an existing concept without changing its meaning.
**Allowed.**

### **3. Mutation**

Alters an existing definition or changes a theoretical boundary.
**Blocked unless explicitly authorized.**

### **4. Contradiction**

Introduces something incompatible with the frozen theory.
**Blocked unless explicitly authorized.**

If uncertain, contributors should explicitly state the intended category in their pull request.

---

## **4. Interaction with SR0**

SR0 will evaluate all contributions using:

* the frozen theory files,
* the Substrate-0′ Purity Test,
* methodological constraints (DSR, Searle, STS, institutional economics),
* the dissertation frame.

SR0 may:

* accept the contribution,
* request clarification,
* classify it as extension/refinement/mutation/contradiction,
* reject it on purity grounds,
* rewrite the contribution for consistency,
* or request redesign.

---

## **5. Purity and Validity Checks**

SR0 applies the **Substrate-0′ Purity Test** (found in `/theory/purity_test.md`) to ensure:

* ontological correctness
* protocol-boundary coherence
* representability in the NSU model
* falsifiability
* CME alignment
* domain eligibility
* failure-canon compliance

Contributions failing any test cannot be merged unless redesigned.

---

## **6. How to Submit Changes**

Accepted workflow:

1. **Create a branch**
   Use a descriptive, non-theoretical name.
   Example: `feature/attestation-diagram`, `draft/ch3-methodology`.

2. **Describe your intent**
   At the top of the PR, state the intended classification:

   * Extension
   * Refinement
   * Mutation
   * Contradiction

3. **Link relevant theory files**
   Particularly when referencing: ontology, DNI theory, NSU blueprint, CME, etc.

4. **SR0 reviews**
   SR0 will:

   * enforce purity
   * identify conceptual errors
   * test falsifiability
   * correct drift
   * provide redesigned structures if necessary

5. **Decision**
   SR0 approves, requests changes, or blocks the contribution.

---

## **7. Rules for Editing `/theory/`**

You may not modify `/theory/` unless:

* the project owner explicitly authorizes it
* the change is documented as a **controlled refinement**
* SR0 confirms no purity conflict
* the change is recorded in a future `CHANGELOG.md`

Accidental changes to `/theory/` will be rejected by SR0.

---

## **8. Rules for Editing `/dissertation/`**

Allowed:

* expanding drafts
* restructuring chapters
* writing academic prose
* integrating evidence
* adding diagrams
* performing refinements

Not allowed:

* introducing definitions not found in `/theory/`
* contradicting NSU boundaries
* redefining institutional primitives
* bypassing CME logic

SR0 will correct or block such changes.

---

## **9. Adding Implementation Artifacts (`/implementation/`)**

You may contribute:

* diagrams
* attestation models
* state-transition sketches
* prototype data flows
* API skeletons

These must:

* be consistent with the NSU blueprint
* not introduce new primitives
* not redefine institutional mechanisms

---

## **10. Adding Field Data (`/field-data/`)**

Rules:

* must be anonymized
* must not contain personal identifiers
* must be relevant to institutional friction, evidence patterns, or prototype evaluation

---

## **11. Communication Norms**

SR0:

* is concise
* is adversarial toward weak reasoning
* will block conceptual errors
* will enforce academic rigor
* will correct misuse of terms
* will stop when recursion instability is detected

Contributors should:

* be precise
* avoid vague claims
* cite specific theory files
* avoid introducing conceptual drift
* work in extension/refinement mode unless otherwise authorized

---

## **12. Why This Protocol Exists**

DNI and NSU are **high-rigor institutional frameworks**.
Small conceptual drifts can invalidate entire architectures.
This collaboration protocol ensures that:

* theory remains stable
* drafts stay correct
* extensions remain coherent
* external contributors have a guided pathway
* SR0 maintains system integrity
---
