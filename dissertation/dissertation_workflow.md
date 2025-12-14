# Section Drafting & Citation Workflow  
**Status:** Canonical · Drift-Preventing · SR0-Compatible  
**Applies to:** All dissertation sections (Chapters 1–3)

---

## Purpose

This document defines the **mandatory workflow** for drafting each dissertation section.

Its objective is to:
- prevent conceptual drift,
- separate thinking from presentation,
- enforce Substrate-0′ → Substrate-2 discipline,
- and ensure examiner-ready output under time constraints.

No section may be drafted outside this workflow.

---

## Non-Negotiable Constraints

- Theory layer is frozen.
- CI ⊃ DNI ⊃ SFEU hierarchy is authoritative.
- No new concepts may be introduced during drafting.
- No reinterpretation or refactoring is permitted.
- Prose operates at the **presentation layer only**.
- Citations support legibility, not ontology.

Violation of any constraint invalidates the section.

---

## Canonical Section Workflow (Required)

Each section **must** pass through the following stages **in order**.

---

### Stage 1 — Outline Lock

**Objective:**  
Define *what the section must establish*, not explain.

**Inputs:**
- `dissertation_frame.md`
- Relevant theory files (read-only)

**Output:**
- Section number and title
- One-sentence section intent
- 3–5 in-scope bullets
- Explicit out-of-scope exclusions

No prose is written at this stage.

---

### Stage 2 — Prose Drafting (SR0)

**Objective:**  
Generate examiner-ready prose with zero theory drift.

**Method:**
- Use the **Section Drafting Prompt Template**
- One section per prompt
- No citations beyond placeholders

**Rules:**
- Declarative, non-defensive tone
- No metaphors or narrative padding
- No literature synthesis
- No examples unless required by the frame

**Output:**
- Complete section prose (draft)

---

### Stage 3 — Single Correction Pass (Optional)

**Objective:**  
Improve surface quality without altering meaning.

**Allowed Instructions (choose one only):**
- **Compression**
- **Boundary-safe clarification**

**Rules:**
- Never stack corrections
- Never introduce new content
- If conceptual error is found → return to Stage 1

**Output:**
- Finalized section prose

---

### Stage 4 — Citation Insertion Pass

**Objective:**  
Align prose with orthodox academic expectations.

**Method:**
- Use the **Citation Insertion Prompt Template**
- Insert minimal in-text citations only

**Citation Roles (MECE):**
1. Conceptual anchors
2. Contrast class
3. Empirical backdrop
4. Methodological precedent

**Rules:**
- No citation as ontological authority
- Prefer under-citation to over-citation
- Placeholders allowed initially

**Output:**
- Submission-ready section with in-text citations

---

### Stage 5 — Reference Resolution

**Objective:**  
Resolve placeholders and finalize references.

**Tooling:**
- ResearchRabbit (primary discovery)
- Google Scholar (verification)
- Zotero / Mendeley (formatting)

**Rules:**
- Each citation must map to a clear role
- If no literature exists, do not force a citation
- Reference list is generated last

---

## ResearchRabbit Usage Protocol

ResearchRabbit is used for **validation**, not discovery.

### Citation Roles
- **A — Conceptual anchor**
- **B — Contrast class**
- **C — Empirical backdrop**
- **D — Method precedent**

Each search must target **one role only**.

### Admission Rule
A paper is admissible only if:
- its role can be stated in one sentence,
- it does not soften or reframe claims,
- it is examiner-recognizable.

Otherwise, discard.

---

## Completion Criteria for a Section

A section is considered **complete** only if:

- Its intent matches `dissertation_frame.md`
- No Substrate-0′ violations exist
- No new concepts were introduced
- Citations are minimal and orthodox
- Prose reads as institutional theory, not advocacy

Only completed sections may be assembled into chapters.

---

## Governing Principle

> **The dissertation is not written.  
> It is compiled.**

This workflow is the compiler.
