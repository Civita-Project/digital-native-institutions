# **Counterfactual Framework**

**Version 2.1 — CI-Enforced · Execution-Grounded · Institutionally Adversarial**

---

## **0. Epistemic Status**

This file defines the **counterfactual falsification framework** for the dissertation.

It exists to answer one question only:

> **Under what alternative worlds would claims about DNI, SFEU, or CME be false?**

This is **not** a narrative device.  
This is a **falsification engine**.

All counterfactuals operate **within the envelope of Computable Institutions (CI)** and test whether **DNI** and **SFEU** claims remain falsifiable under alternative execution worlds.

**Any counterfactual that violates CI execution constraints or observability requirements is rejected as non-admissible and excluded from analysis.**

---

## **1. Scope and Preconditions**

Counterfactuals defined here apply **only when all of the following hold**:

1. DNI necessary conditions (N1–N6) are *claimed* to hold  
2. Execution is performed by an **SFEU-class** system  
3. Observations are derived from:
   - execution traces
   - attestation logs
   - exception routing
   - audit reconstruction

If these preconditions are absent, results are **non-evaluative**.

---

## **2. Counterfactual Classes (MECE)**

All counterfactuals fall into **four mutually exclusive and collectively exhaustive classes**.

---

## **CF-A — Execution Counterfactuals (Protocol Reality Tests)**

**Question:**  
What if execution is *claimed* to be protocol-bound, but is not?

---

### **CF-A1 — Hidden Discretion World**

**Assumption**

- SFEU exists in name
- Discretionary overrides exist (manual database writes, silent approvals)

**Expected Observation**

- Front-office corruption persists
- CME migration does *not* occur
- Audit reconstruction fails intermittently

**Falsification Trigger**

- If corruption migrates upward despite hidden discretion → **CME invalid**

---

### **CF-A2 — Silent Failure World**

**Assumption**

- Invalid X occasionally passes as Y
- Failures are suppressed or auto-corrected

**Expected Observation**

- Low exception rate
- High institutional error rate
- No attestation disputes

**Falsification Trigger**

- If CME signals appear without explicit failure → **SFEU definition violated**

---

## **CF-B — Institutional Boundary Counterfactuals**

**Question:**  
What if institutional meaning leaks into execution?

---

### **CF-B1 — Interpretive Protocol World**

**Assumption**

- Execution layer resolves ambiguity
- Protocol “decides” edge cases

**Expected Observation**

- Reduced exceptions
- Reduced governance visibility
- Apparent efficiency gains

**Falsification Trigger**

- If the system “works better” but CME disappears → **theory invalid**  
  *(category error detected)*

---

### **CF-B2 — Governance Substitution World**

**Assumption**

- SFEU substitutes for human governance
- Exception routing is bypassed

**Expected Observation**

- Reduced contestability
- Centralized power at execution layer

**Falsification Trigger**

- If corruption decreases without migration → **CME falsified**

---

## **CF-C — CME-Specific Counterfactuals (Equilibrium Tests)**

**Question:**  
What if corruption does *not* migrate as predicted?

---

### **CF-C1 — No-Migration World**

**Assumption**

- DNI and SFEU are fully enforced
- Corruption remains front-office and opaque

**Expected Observation**

- Bribery persists at execution points
- No increase in attestation or exception pressure

**Conclusion**

- **CME is false**

---

### **CF-C2 — Disappearance World**

**Assumption**

- Corruption metrics drop across *all* layers

**Expected Observation**

- Clean logs
- No disputes
- No exceptions

**Conclusion**

- Measurement invalid **or**
- Execution masking corruption  
Either case → **CME rejected**

---

## **CF-D — Domain Transfer Counterfactuals**

**Question:**  
Does the theory over-generalize beyond CI-eligible domains?

---

### **CF-D1 — Non-Administrative Domain World**

**Assumption**

- Apply SFEU logic to:
  - adjudication
  - moral reasoning
  - political decision-making

**Expected Observation**

- Breakdown of execution
- Explosion of exceptions

**Conclusion**

- Confirms **boundary conditions**  
- If it “works” → **ontology violated**

---

## **3. Counterfactual Evaluation Matrix**

| Counterfactual | DNI Holds? | SFEU Holds? | CME Holds? | Interpretation         |
|----------------|-----------|------------|-----------|------------------------|
| CF-A1          | ❌         | ❌          | ❌         | Execution invalid      |
| CF-A2          | ❌         | ❌          | ❌         | Protocol contamination |
| CF-B1          | ❌         | ❌          | ❌         | Category error         |
| CF-B2          | ❌         | ❌          | ❌         | Governance collapse    |
| CF-C1          | ✅         | ✅          | ❌         | CME falsified          |
| CF-C2          | ❌         | ❌          | ❌         | Measurement failure    |
| CF-D1          | ❌         | ❌          | N/A        | Boundary confirmed     |

---

## **4. Relation to Implementation (Critical)**

These counterfactuals are **not hypothetical**.

They are executed against:

- `sfeu_prototype.md`
- real execution traces
- real exception paths
- real audit logs

A counterfactual that cannot be operationalized is **invalid and removed**.

---

## **5. Thailand as Destructive Validator**

Thailand is treated as a **worst-case institutional environment**:

- high discretion
- high corruption pressure
- norm-driven governance
- low trust equilibrium

If CME holds **in Thailand**, it generalizes.  
If it fails here, the theory fails globally.

Thailand is **not** a case study.  
It is a **stress weapon**.

---

## **6. Falsification Priority Rule**

If **any** of the following occur:

1. Corruption does not migrate
2. Execution discretion persists
3. Exceptions are suppressed
4. Governance becomes opaque
5. Audit reconstruction fails

Then:

> **Either the theory is false or the implementation is dishonest.**

There is no third option.

---

## **7. Status**

**Frozen (v2.1).**

This file may change only if:

- `computable_institutions.md` changes,
- DNI theory is revised,
- CME is falsified, or
- SFEU execution invariants change.
