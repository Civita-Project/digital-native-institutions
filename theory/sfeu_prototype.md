# **Minimal NSU Prototype Architecture (v1.0)**

**Purpose:** Define the smallest viable instantiation of the National State Unit (NSU) that is:

* implementable in a 3–6 month pilot
* theoretically aligned with Searle-based ontology
* empirically testable
* suitable for inclusion in a PhD dissertation
* appropriate for World Bank / GovTech-grade scrutiny

The prototype focuses on **Business Registration**, the cleanest high-friction administrative workflow.

---

# **1. NSU Minimal Core**

The minimal NSU consists of **four irreducible primitives**:

### **1.1 Identity Binding (Who)**

* NDID / ThaID binding
* Public-key identity
* Role context (actor-as-applicant / actor-as-attester)

### **1.2 Document Lineage (What)**

* Hash-linked documents
* Content-addressable storage
* Signature wrapping and counter-signature pathways

### **1.3 Attestation Graph (How True)**

* Nodes = attestations
* Edges = dependencies
* Liability weights per attester class
* Revocation rules

### **1.4 State-transition Engine (Then What)**

* Deterministic transitions
* Status-function interpreter
* Exception boundaries
* Logging and lineage enforcement

If these four elements exist and operate coherently, an NSU exists.

---

# **2. State-Transition Engine (STE)**

*The computational heart of the NSU.*

The STE must satisfy three invariants:

### **2.1 Determinism**

Given `(state S, input X, attestation A)`, the transition to `S’` must be uniquely determined.

`δ(S, X, A) = S’`
No ambiguity, no human discretion inside the protocol.

---

### **2.2 Status-Function Binding**

The STE interprets Searle’s mapping:

**X counts as Y in context C.**

Examples for business registration:

* “Signature + ID Binding” *(X)* counts as “Legal authorization” *(Y)* in “DBD Registration Process” *(C)*
* “Surveyor attestation of location” *(X)* counts as “Legally valid place of business” *(Y)*

STE must evaluate:

* Validity
* Completeness
* Consistency

And produce the institutional state change.

---

### **2.3 Atomicity & Auditability**

Every transition must produce:

* **Atomic commit** of new state
* **Immutable log entry**
* **Attestation lineage update**

No partial failures.

---

# **3. Attestation Pathway (L2)**

The attestation subsystem follows:

### **3.1 Three Attester Classes**

* Human
* Device
* Institutional

Each attestation contains:

* Attester identity
* Evidence
* Signature
* Class-based liability weight
* Expiry/Validity context

---

### **3.2 Attestation Graph**

A directed acyclic graph where:

* Leaves = raw evidence
* Internal nodes = curated attestations
* Root = domain presiding attestation bundle

Business Registration Example:

* GPS/device attestation → Address proof
* Landlord / owner attestation → Usage rights
* Applicant attestation → Identity + Intent

---

### **3.3 Attestation Evaluation**

`Attestation_Valid(A) = Signature_Valid ∧ Evidence_Complete ∧ Liability_Compatible`

If false → send to **Exception Layer**.

---

# **4. Status-Function Interpreter**

*The theoretical breakthrough translated into executable logic.*

The interpreter enforces:

### **4.1 Constitutive Rules**

Mappings such as:
“X counts as Y in C אם and only if all required conditions are satisfied”

Example:

```
Document D _counts as_ Proof_of_Business_Name
_in_ Registration_Context  
IFF:
- D:Name_Reservation_Cert exists  
- Signed by DBD  
- Within 60-day validity  
```

---

### **4.2 Deontic Constraints**

Permission, obligation, prohibition:

* “Applicant must provide attestation of business address”
* “Business name must not conflict with reserved names”
* “If applicant < 20 yrs → parental consent required”

Interpreter ensures rules are **binding** and **computable**.

---

### **4.3 Status Degradation Rules**

Entities lose status when:

* Attestation revoked
* Time window expires
* Contradictory evidence emerges

E.g., business name reservation expires → status reverts to “available.”

---

# **5. Evidence Layer (L1)**

Where real-world reality enters the system.

Contains:

* Document uploads
* Device-captured evidence (GPS, timestamps)
* Verifiable credentials
* Cross-agency references (e.g., Ministry of Interior)

Properties:

### **5.1 Grounding Constraint**

Every institutional fact must have a brute-fact grounding in L1.

### **5.2 Provenance Metadata**

* Issuer
* Method of issuance
* Timestamp
* Cryptographic integrity proofs

---

# **6. Exception Layer**

Exception logic must be:

* **explicit**
* **bounded**
* **auditable**

Two classes:

### **6.1 Soft Exceptions**

Input error, missing fields.
→ send back to applicant, no staff needed.

---

### **6.2 Hard Exceptions (Human Judgment Required)**

Ambiguity, conflicting attestations, legal inconsistencies.
→ route to registrar with full lineage and logs.

Hard exceptions must:

* Record human judgment
* Snapshot reasoning
* Bind outcome to registrar’s identity
* Feed data back to drift analysis

This is where corruption could re-enter → monitored via CME.

---

# **7. Logging & Audit Layer**

### **7.1 Immutable Logs**

Every state transition yields:

* Timestamp
* Actor
* Attestations
* Input
* Output
* Exception linkage

### **7.2 Lineage Reconstruction**

Ability to reconstruct:

* Who did what
* Based on what evidence
* Under what rule context

### **7.3 Drift Detection**

Analytics cluster logs to detect:

* semantic drift
* protocol bypassing
* off-protocol activity

---

# **8. API Boundaries**

### **8.1 Public API**

* Submit application
* Query status
* Retrieve lineage
* Verify signatures
* Fetch canonical ruleset

### **8.2 Attester API**

* Submit attestation
* Revoke attestation
* Bind device identity

### **8.3 Inter-Agency API**

* Get authoritative documents
* Query legal statuses
* Push updates/patches

---

# **9. Deployment Envelope (Minimal Feasible)**

### **9.1 Infrastructure**

* Containerized service
* Stateless front-end
* PostgreSQL or equivalent for lineage storage
* Object storage for documents
* PKI or NDID integration

### **9.2 Security Envelope**

* TLS everywhere
* Hardware-backed key storage
* Post-quantum-ready signatures (optional but ideal)

### **9.3 Governance Envelope**

* Change control board
* Rule-update workflow
* Attestation-class management

---

# **10. Testable Pilot Domain — Business Registration**

### **Why this domain?**

* High friction
* Clear constitutive rules
* High corruption incentives
* Clean attestation structure
* Deterministic outcomes
* Low political volatility
* Easy measurable success metrics

### **Workflow Sketch**

1. **Applicant Identity Binding**
2. **Submit Name Reservation Evidence**
3. **Address Attestation Pathway Built**
4. **Upload Supporting Documents**
5. **Interpreter Checks Status Functions**
6. **STE Executes State Transition**
7. **Output: Certificate of Business Registration**
8. **Logs + Lineage Immutable**

### **Metrics**

* Latency
* Exception rate
* L1→L2 corruption migration
* Governance intervention frequency
* End-user trust

---

# **Frozen**

This file is **frozen**, as it defines the implementation artifact required by DSR methodology and enables empirical validation.
