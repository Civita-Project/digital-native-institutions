# **CONTRIBUTING.md**

### *Guidelines for Contributing to the Digital Native Institutions Repository*

**Stable Theory • Controlled Extensions • High-Rigor Collaboration**

---

## **1. Purpose of This Document**

This repository contains:

* the **frozen academic theory** for Digital Native Institutions (DNI) and the National Service Unit (NSU)
* the **CUTIP PhD dissertation draft** based on that theory
* **implementation sketches**, **field data**, and **methodology artifacts**
* the **operational instructions** for SR0

This document explains how to contribute safely, rigorously, and without introducing conceptual drift.

---

## **2. Repository Structure (Must Understand Before Contributing)**

A contribution must respect the purpose of each folder:

```
/theory/         ← Frozen academic theory (do not modify)
/dissertation/   ← Evolving dissertation drafts
/docs/           ← Human-friendly explanatory materials
/implementation/ ← Prototype sketches, diagrams, data flows
/field-data/     ← Evidence, observations, anonymized interviews
/ops/            ← SR0 operational instructions (not theory)
/archive/        ← Deprecated or superseded files
```

**Only specific parts of this repository may be modified.**

---

## **3. What You May Edit**

Contributors may safely modify:

### **✔ `/dissertation/`**

Draft text, structure, examples, diagrams, or evaluation content, provided all changes:

* align with the frozen theory in `/theory/`
* follow CUTIP methodology
* preserve falsifiability
* introduce no conceptual drift

---

### **✔ `/docs/`**

Clarifications, improved explanations, better onboarding materials.

---

### **✔ `/implementation/`**

Prototype-oriented contributions:

* diagrams
* attestation flows
* state-transition sketches
* API skeletons

All contributions here must remain aligned with the NSU blueprint.

---

### **✔ `/ops/`**

Refinements to collaboration processes, SR0 instructions, or operational protocols.

---

## **4. What You May NOT Edit**

Modifications to `/theory/` are **prohibited** unless explicitly authorized by the project owner.

Do **NOT** alter any file inside:

```
/theory/
```

These files define the formal academic and institutional structure:

* ontology
* DNI theory
* NSU blueprint
* NSU prototype
* CME
* counterfactuals
* failure canon
* EVP
* purity test
* dissertation master frame

Any changes here require formal review and explicit approval.

---

## **5. How to Propose Changes**

Every proposed change must declare its classification:

### **A. Extension** (allowed)

Adds new material that fits within existing theory.

### **B. Refinement** (allowed)

Sharpens clarity without altering underlying meaning.

### **C. Mutation** (blocked unless explicitly authorized)

Alters a theoretical definition or conceptual boundary.

### **D. Contradiction** (blocked unless explicitly authorized)

Introduces something incompatible with existing theory.

State your classification at the top of your pull request.

---

## **6. SR0 Review Process**

All contributions are reviewed by SR0 using:

* frozen theory files
* the Substrate-0′ Purity Test
* methodological requirements (DSR, Searle, STS, institutional economics)
* dissertation constraints

SR0 may:

* accept
* request modification
* classify the change
* block it for purity reasons
* rewrite for alignment
* request redesign

SR0 will enforce correctness over convenience.

---

## **7. Purity Test Requirements**

Before submitting changes, ensure they satisfy:

* **status-function integrity**
* **protocol boundary correctness**
* **NSU primitive representability**
* **falsifiability**
* **CME dynamics**
* **DNI domain eligibility**
* **failure-canon alignment**

If unsure, SR0 will evaluate automatically.

---

## **8. Branching & Commit Rules**

### **Branches**

Use descriptive, non-theory names:

```
feature/attestation-diagram
draft/ch3-methodology
doc/overview-update
```

### **Commits**

Commits must be:

* clear
* atomic
* descriptive

Avoid speculative or unclear commit messages.

---

## **9. Adding Implementation Artifacts**

Allowed:

* new diagrams
* prototype logic
* attestation examples
* workflow mappings
* state-transition illustrations

Not allowed:

* introduction of new NSU primitives
* changes to boundary rules
* implicit redefinition of institutional mechanisms

---

## **10. Adding Field Data**

You may contribute:

* anonymized interviews
* administrative friction observations
* structured process traces

But not:

* identifiable personal information
* unverifiable claims
* politically sensitive data without anonymization

---

## **11. Contribution Philosophy**

This repository follows a **fork-first** model:

* Anyone may fork the repo.
* Anyone may remix or extend the ideas.
* Pull requests are welcome but optional.

The Fractal Open License explicitly allows derivative work.

---

## **12. Summary of Contributor Responsibilities**

Before contributing, a collaborator must:

* understand the repository structure
* respect frozen theory boundaries
* classify proposed changes
* avoid drift
* maintain academic rigor
* follow SR0 review protocol

Contributions that violate these norms will be rejected or rewritten.
