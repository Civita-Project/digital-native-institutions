# **DNI Blueprint v1.0**

**Definition • Conditions • Classification • Diagnostic Rubric • Cross-National Applicability**

This blueprint formalizes **Digital Native Institutions (DNI)** in a way that is:

* non-utopian
* falsifiable
* substrate-correct
* free of category errors
* evaluable across countries
* coherent with the NSU Blueprint and DNI Theory (Project File 2)

This is now the *canonical* definition of DNI for all dissertation chapters and implementations.

---

# **1. DNI Definition (Formal + Architectural)**

## **1.1 Formal Definition (Status-Function Correct)**

A **Digital Native Institution (DNI)** is:

> **An institution whose constitutive rules are directly executable as protocol-governed state transitions, such that institutional facts are generated through attested evidence, deterministic rule-application, and auditable state-change, without recourse to hidden discretion or off-protocol workflows.**

In Searle terms:

* Institutional facts are produced by explicit mappings:
  **X (evidence) counts as Y (institutional fact) in context C (domain)**
* These mappings are **computationally enforceable**
* Constitutive rules → Executable rules
* Brute-fact evidence → Verifiable attestations
* Interpretive discretion → Bounded exception layer

DNIs **do not** replace human judgment; they **contain** its domain.

---

## **1.2 Architectural Definition (Institutional Engineering)**

A DNI is an institution that satisfies:

> **Administrative transactions are executed via protocolized workflows in which identity, evidence, rules, and transitions are machine-verifiable, human auditable, and corruption-resistant by design.**

Architectural requirements:

* identity binding via MVLP attributes
* document integrity via hash/signature
* evidence → rule → transition pipeline
* deterministic computational execution
* exception pathways separately governed
* audit by design (not by policy)

**Key:**
DNI = institution whose *administrative substrate* is digital-native, not digitally retrofitted.

---

# **2. Institutional Classification Framework**

This classification framework categorizes any government institution, globally, along five axes determining DNI eligibility.

---

## **2.1 Axis 1 — **Rule Executability**

Question: *Can constitutive rules be expressed as deterministic, bounded, non-interpretive logic?*

Categories:

* **E1 (Executable):** Complete formalization possible
* **E2 (Semi-executable):** Formalizable core, interpretive fringes
* **E3 (Non-executable):** Rules rely heavily on contextual interpretation

DNI requires: **E1 or E2 (with exception layer)**.

---

## **2.2 Axis 2 — **Evidence Verifiability**

Question: *Can required evidence be reliably attested by devices/humans/institutions with bounded liability?*

Categories:

* **V1:** Fully verifiable evidence
* **V2:** Partially verifiable, structured evidence
* **V3:** Ambiguous or subjective evidence

DNI requires: **V1 or V2**.

---

## **2.3 Axis 3 — **Identity Minimality**

Question: *Can the domain operate using **minimum viable legal persona (MVLP)** attributes?*

Categories:

* **I1:** MVLP sufficient
* **I2:** Requires enriched identity
* **I3:** Requires contextual/social identity

DNI requires: **I1**.

---

## **2.4 Axis 4 — **Exception Profile**

Question: *Does the domain have a bounded, formalizable exception space?*

Categories:

* **X1:** Exceptions rare + formalizable
* **X2:** Exceptions moderate + partly formalizable
* **X3:** Exceptions common or contextual

DNI requires: **X1 or X2** + separate exception governance.

---

## **2.5 Axis 5 — **State-Transition Purity**

Question: *Does the domain’s output correspond to a discrete institutional fact?*

Categories:

* **T1:** Clean institutional fact outputs
* **T2:** Semi-structured outcomes
* **T3:** Political or moral judgments

DNI requires: **T1**.

---

## **2.6 Combined Classification Table**

| Axis                    | Required for DNI? | Category Allowed | Meaning                                    |
| ----------------------- | ----------------- | ---------------- | ------------------------------------------ |
| Rule executability      | Yes               | E1/E2            | Domain must be formalizable                |
| Evidence verifiability  | Yes               | V1/V2            | Evidence must be attestable                |
| Identity minimality     | Yes               | I1               | MVLP only                                  |
| Exception profile       | Yes               | X1/X2            | Edge cases must be bounded                 |
| State-transition purity | Yes               | T1               | Outputs must be formal institutional facts |

A domain is **DNI-eligible** if and only if it satisfies all 5 axes.

---

# **3. Evaluation Rubric (DNI Readiness Index)**

To determine readiness, score each axis:

| Criterion               | Score Range | Weight |
| ----------------------- | ----------- | ------ |
| Rule executability      | 0–2         | 25%    |
| Evidence verifiability  | 0–2         | 20%    |
| Identity minimality     | 0–2         | 20%    |
| Exception profile       | 0–2         | 15%    |
| State-transition purity | 0–2         | 20%    |

Interpretation:

* **8–10:** Fully DNI-ready
* **6–7:** Conditionally DNI-ready
* **4–5:** Not currently ready (requires redesign)
* **0–3:** Fundamentally non-DNI

This rubric applies to:

* tax systems
* business registries
* land offices
* licensing agencies
* immigration systems
* welfare agencies
* procurement systems

---

# **4. DNI Diagnostic Test (Applied to Any Domain)**

A government domain passes the **DNI Diagnostic Test** iff:

## **Test 1 — Formalizability Test**

Can we write the constitutive rules as machine-verifiable conditions?
If NO → domain cannot be DNI.

## **Test 2 — Attestation Test**

Can all required evidence be tied to attestable sources?
If NO → domain requires partial DNI or hybrid design.

## **Test 3 — Identity Minimality Test**

Can the domain operate on MVLP alone?
If NO → domain risks identity overreach and coercion.

## **Test 4 — Exception Test**

Can exceptions be isolated into a separate adjudicative module?
If NO → NSU cannot execute the domain.

## **Test 5 — Institutional Fact Test**

Does the domain produce **institutional facts** (registrations, licenses, approvals)?
If NO → domain belongs to interpretive institutions.

Only domains that satisfy **all five tests** qualify for DNI/NSU execution.

---

# **5. Cross-National Applicability**

This is critical: DNI is *not Thailand-specific*.
The blueprint explicitly generalizes to all administrative states.

---

## **5.1 Universal Variables**

DNI depends on features common to all bureaucracies:

* constitutive rules
* evidence requirements
* institutional fact outputs
* identity representation
* exception handling

Thus DNI applies to:

* unitary states
* federal states
* common-law systems
* civil-law systems
* developing countries
* advanced countries

---

## **5.2 Country-Dependent Modifiers**

DNI’s implementation varies by:

### **A. Legal Tradition**

* Civil law → easier constitutive-rule extraction
* Common law → larger exception domain

### **B. Digital Infrastructure**

* Estonia/Singapore → full DNI feasible
* India/Indonesia → partial DNI feasible
* Thailand → ideal test case (high-friction + high-corruption + high-potential)

### **C. Administrative Culture**

* High discipline → easier protocol enforcement
* High discretion → more leak pathways, slower migration

---

## **5.3 Comparative Positioning**

| Country       | DNI Feasibility     | Reason                                                  |
| ------------- | ------------------- | ------------------------------------------------------- |
| **Estonia**   | Very high           | Structured rules + digital ID + minimal corruption      |
| **Singapore** | High                | Strong institutions + digital maturity                  |
| **Thailand**  | High-medium         | Severe friction → large upside, but corruption migrates |
| **India**     | Medium              | Strong DPI but bureaucratic drift                       |
| **Indonesia** | Medium-low          | Identity fragmentation + corruption                     |
| **U.S.**      | Medium              | Federal fragmentation + legacy systems                  |
| **China**     | High (but coercive) | Strong enforcement + surveillance risk                  |

This prepares the dissertation for a **cross-case generalizability chapter**.

---

# **Frozen**

This DNI Blueprint is now the authoritative foundation for:

* Chapter 1 (Problem & framing)
* Chapter 2 (Lit review + conceptual positioning)
* Chapter 3 (Methodology + institutional analysis)
* All subsequent implementation and evaluation work

All future designs—including NSU prototype, corruption model, etc.—must conform to this definition.

