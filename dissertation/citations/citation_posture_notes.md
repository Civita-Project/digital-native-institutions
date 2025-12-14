# citation_posture_notes.md
**Status:** Private interpretive notes (NOT a project validator)  
**Purpose:** Internal guardrails for citation usage aligned with CUTIP AI grading behavior  
**Scope:** Chapters 1–3 only

---

## 0. Meta-Rule (Non-Negotiable)

> **Citations are not evaluated as objects.  
They are evaluated only through the structural effects they introduce.**

If a citation does not change the *necessity*, *scope*, or *coherence* of a claim, it is noise.

---

## 1. What CUTIP AI Does *Not* Reward

Do **not** optimize for:
- citation count
- journal prestige
- recency for its own sake
- exhaustive “related work”
- APA perfection beyond basic correctness

Observed pattern:  
High citation density without structural load **lowers** scores.

---

## 2. Acceptable Structural Roles of Citations

Every citation must play **exactly one** of these roles:

### 2.1 Ontological Anchor
- Establishes the *kind* of thing being discussed  
- Example: status functions, institutional facts

**Test:**  
If removed, the ontology collapses or becomes ambiguous.

---

### 2.2 Boundary Justification
- Explains why something is excluded or bracketed  
- Example: why policy, culture, or ethics are not primary layers

**Test:**  
If removed, the scope appears arbitrary.

---

### 2.3 Canonical Framing
- Places the problem in a recognized class  
- Example: information asymmetry, execution failure, institutional drift

**Test:**  
If removed, the problem looks idiosyncratic or anecdotal.

---

### 2.4 Disambiguation
- Prevents misreading of a common term or concept  
- Example: distinguishing execution from procedure or governance

**Test:**  
If removed, the reader could reasonably misinterpret the claim.

---

### 2.5 Stress-Test Reference
- Shows why naïve or popular alternatives fail  
- Example: why digitization alone is insufficient

**Test:**  
If removed, the critique loses bite.

---

## 3. Citation–Claim Isomorphism Rule (Critical)

> **A citation must support the *exact epistemic strength* of the claim it is attached to.**

Penalized patterns:
- Conceptual source cited for empirical claim
- Empirical source cited for ontological claim
- Weaker claim in source than asserted in text
- Adjacent but non-isomorphic theory

**Hard rule:**  
A misaligned citation is worse than no citation.

---

## 4. Temporal Appropriateness (Not Recency)

CUTIP AI distinguishes between:
- **Foundational claims** → old sources acceptable
- **Performance claims** → era-matched sources required

Safe:
- Old canonical theory in Chapter 1

Unsafe:
- Legacy technical work used to justify modern system performance
- Mixed eras without explanation

---

## 5. Scope Leakage via Citations (High Risk)

A citation can silently expand scope.

Red flags:
- User behavior literature without user sampling
- Policy reform literature without policy analysis
- Ethics frameworks without ethical mechanisms
- Cultural theory without cultural method

**Rule:**  
If a citation introduces obligations the dissertation does not fulfill → penalty.

---

## 6. Chapter-Specific Posture

### Chapter 1
- Low to moderate citation density
- Canonical, ontological, framing sources only
- No “related work” sections
- Over-citation is negative

### Chapter 2
- Higher density acceptable
- Theory-to-architecture mapping
- Comparative positioning allowed

### Chapter 3
- Methodological and validation sources
- Minimal theory citation
- Design-science grounding prioritized

---

## 7. “Missing Citation” Risk Profile

CUTIP AI flags missing citations **only when**:
- A claim sounds empirical
- A contested claim is asserted as fact

It does **not** flag:
- Explicitly owned analytical positions (“this dissertation treats…”)
- Internally defined constructs
- Structural reframings

---

## 8. Practical Self-Check Before Adding Any Citation

Ask:

1. What structural role does this citation play?
2. Which checklist axis would fail if it were wrong?
3. Does it expand scope silently?
4. Does it force a method I am not using?
5. Could removing it *increase* clarity?

If you cannot answer (1) precisely → **do not include the citation**.

---

## 9. Governing Principle

> **Citations serve structure.  
Structure does not serve citations.**

This file is guidance only.  
It must never override or modify project validators.
