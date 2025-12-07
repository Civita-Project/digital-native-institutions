# **The Corruption Migration Equilibrium Model (CME)**

### *Version 1.0 — Frozen Formal Model*

---

## **0. Purpose**

This document formalizes how corruption **migrates**, **adapts**, and **settles into new equilibria** when an institution transitions from:

* Paper-based → Digitally-transformed → **Digital Native (DNI)**

This directly supports:

* DNI theory
* NSU architecture
* Dissertation hypotheses (especially H4)
* Chapter 3 methodology (formal modeling)

This is the **first game-theoretic model** describing corruption under **protocol-constrained governance**.

---

# **1. Core Idea of CME**

**NSU does not eliminate corruption.**
It **changes where corruption becomes mathematically viable.**

Under traditional governance:

* corruption = front-office discretion
* high surface area
* low auditability

Under NSU/DNI:

* front-office discretion shrinks
* corruption **migrates** to:

  * **attestation layer**
  * **governance layer**
  * **exception routing**

This shift is **predictable**, and CME models the equilibrium.

---

# **2. Game-Theoretic Structure**

We define a repeated incomplete-information game across three institutional layers:

### **Layer L1 (Front-Office Administration)**

Players:

* Individual bureaucrats
* Citizens

Moves:

* Follow protocol
* Attempt off-protocol manipulation

Cost structure:

* NSU raises cost of off-protocol deviation

---

### **Layer L2 (Attestation Layer)**

Players:

* Human attesters
* Device attesters
* Institutional attesters

Moves:

* Truthful attestation
* False attestation (requires collusion)

Costs:

* Liability penalties
* Detectability from logs

---

### **Layer L3 (Governance / Oversight Layer)**

Players:

* Protocol governance board
* Exception reviewers
* NSU administrators

Moves:

* Correct drift
* Exploit drift
* Rewrite protocol rules

Costs:

* Political consequences
* Constitutional constraints
* Audit visibility

---

# **3. Players and Payoff Functions**

### **Players**

* **B** = Bureaucrat
* **A** = Attester
* **G** = Governance actor
* **C** = Citizen (external agent)

### **Payoffs**

Each player maximizes:

```
U = Benefit_from_Corruption – Probability_of_Capture × Penalty – Operational_Effort
```

Where each term changes under NSU.

### Under NSU:

* **Probability_of_Capture increases at L1 and L2**
* **Penalty increases for A and G**
* **Operational effort increases for L1 corruption**
* **Operational effort decreases for L3 manipulation** (more abstract, less visible)

Thus corruption **migrates upward**.

---

# **4. Strategy Sets**

### **For Bureaucrat (B)**

S_B = {FollowProtocol, DeviateOffProtocol}

### **For Attester (A)**

S_A = {Truth, Lie, Collude}

### **For Governance Actor (G)**

S_G = {CorrectDrift, ExploitDrift, ReinterpretRules, RewriteProtocol}

### **For Citizen (C)**

S_C = {Comply, Bribe_L1, Bribe_L2, Bribe_L3}

---

# **5. On-Protocol vs. Off-Protocol Corruption Dynamics**

### **Traditional Bureaucracy (no NSU)**

* Off-protocol = easy
* Discretion = high
* Logs = nonexistent
* Cost of deviation = low

### **Under NSU**

Front-office (L1) deviation requires:

* bypassing logs
* breaking deterministic workflows
* forging identity or signatures

Thus L1 corruption becomes:

```
Economically irrational at scale.
```

Attestation (L2) corruption emerges:

* Attesters can lie
* Must collude with citizens
* Lies are detectable in multi-attester chains
* Penalties escalate

Governance (L3) corruption becomes:

* Rare
* High leverage
* Slow-moving
* Strategically attractive

Thus **corruption does not vanish; it migrates and condenses**.

---

# **6. Migration Pathways**

Define migration function **M**:

```
M: L1 → L2 → L3
```

Under NSU, corruption flows upward based on **cost-pressure gradients**:

### **Stage 1: L1 → L2**

Threshold condition T1:

```
Cost_L1 > Cost_L2 + Collusion_Effort_L2
```

L1 corruption collapses. Attestation fraud rises.

---

### **Stage 2: L2 → L3**

Threshold condition T2:

```
Penalty_L2 × Probability_Detection_L2 
    > Expected_Benefit_L3
```

Attesters stop lying. Governance-level abuse rises.

---

### **Stage 3: Consolidated L3 Recoding**

Threshold condition T3:

```
Protocol_Rule_Manipulation_Benefit 
    > Political_Risk + Audit_Risk
```

This is the most dangerous failure mode.

Under NSU:

* corruption becomes **rarer**
* corruption becomes **more centralized**
* corruption becomes **more consequential**

This is exactly what a mature institutional theory must predict.

---

# **7. Nash Equilibria**

Define equilibrium states:

### **E1: Pre-DNI Equilibrium**

High corruption at L1, moderate L2, negligible L3.

Strategies:

* B deviates
* A lies if bribed
* G stays inactive

Stable equilibrium in Thailand today.

---

### **E2: Transitional NSU Equilibrium**

L1 collapses → L2 rises.

Strategies:

* B follows protocol
* A selectively lies
* G begins exerting oversight

Partially stable.

---

### **E3: Mature NSU Equilibrium**

Corruption appears primarily in L3.

Strategies:

* B follows protocol
* A tells truth
* G attempts institutional capture or drift-exploitation

This is stable **if and only if** governance bodies are constrained.

---

### **E4: Fully Constrained Equilibrium (Ideal DNI)**

Minimal corruption; limited to L3 exploit attempts that are quickly corrected.

Strategies:

* B follows protocol
* A tells truth
* G corrects drift proactively

Requires:

* strong constitutional constraints
* transparent protocol governance
* multi-stakeholder oversight

---

# **8. Stability Conditions**

We define stability using cost-benefit surfaces.

### **Stable NSU requires:**

**SC1. Cost_L1 > Benefit_L1**
Front-office corruption must be irrational.

**SC2. Penalty_L2 × Probability_Detection_L2 > Benefit_L2**
Attestation-stage corruption must be unprofitable.

**SC3. Oversight_Strength_L3 > Manipulation_Reward_L3**
Governance capture must be harder than compliance.

If SC1–SC3 hold → stable equilibrium.

If any fail → corruption migrates downward or sideways.

---

# **9. Threshold Functions**

Define:

* **θ1** = minimum protocol coverage for L1 collapse
* **θ2** = minimum penalty × detection rate for L2 collapse
* **θ3** = minimum transparency for L3 constraint

Mathematically:

```
θ1 = f(protocol determinism, workflow coverage)
θ2 = g(attestation liability, multi-signer requirements, device attestations)
θ3 = h(protocol governance transparency, composition of board, auditability)
```

These functions define **DNI viability**.

---

# **10. Implications for NSU Design**

### **D1. Mandatory Attestation Multiplicity**

Single attester → high L2 corruption
Multi-attester → raises θ2 thresholds

### **D2. Strict Exception Taxonomy**

Exception ambiguity → corruption re-enters at L2/L3
Formal exception rules → constrain drift

### **D3. Governance Transparency Protocol**

Because corruption migrates to L3, governance must be:

* transparent
* multi-stakeholder
* constitutionally constrained

### **D4. Automatic Liability Slashing (Z-Clause)**

Mitigates L2 manipulations by making corruption provably irrational.

### **D5. Immutable Workflow Enforcement**

Prevents L1–L2 regression.

---

# **11. Frozen**

This CME model is frozen unless contradicted by empirical data or simulation.

