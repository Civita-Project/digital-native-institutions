# Arc Sequencing Protocol
## Version 2.0 — File-Level ARC Control (Substrate-0′ Enforced · Drift-Resistant · MECE)

---

## Epistemic Status (Hard Constraint)

This document defines the **mandatory sequence** for making changes to project files.

It is a **process control artifact**:
- It governs *order of operations*.
- It does not define ontology, theory, or execution.
- It enforces Substrate-0′ precedence through sequencing discipline.

Any action that violates this sequencing is **invalid**, even if the content “sounds correct”.

---

## Dependency Order (Non-Negotiable)

All sequencing must preserve this dependency order:

1. `substrate0_prime_purity_test.md` (validator)
2. `ontology.md` (Substrate-0′)
3. `dni_theory.md` (constitutive theory)
4. `dni_blueprint.md` (theory → architecture)
5. `sfeu_blueprint.md` (execution definition)
6. `sfeu_prototype.md` (DSR artifact)
7. `corruption_equilibrium.md` (CME dynamics)
8. `counterfactuals.md` (falsification surface)
9. `failure_case_canon.md` (comparative validation)
10. `dnm_methodology.md` (evidence methodology)
11. `dissertation_frame.md` (presentation frame)

All other files are subordinate and must not override any above.

---

## Core Rule: One-Way Influence

Truth flows one way only:

``
Substrate-0′ / Theory / Execution / Falsification
↓
Presentation & Evaluation Artifacts
``

Reverse influence is prohibited.

---

## ARC Stages (Canonical)

### Stage 1 — Global Coherence & Structural Repair
Objective:
- eliminate naming residue (e.g., NSU),
- restore correct boundaries (DNI ≠ SFEU),
- enforce CME relocation framing,
- harden falsification and exception pathways,
- make all spine files mutually consistent.

Output:
- coherent spine (files 1–11 in Dependency Order)

Gate to exit Stage 1:
- all spine files pass `substrate0_prime_purity_test.md`
- no forbidden terms or forbidden boundary violations remain

---

### Stage 1.5 — Enforcement Activation (Process + Guardrails)
Objective:
- ensure the project cannot drift silently again.

Required actions:
- validator file is clean (`substrate0_prime_purity_test.md`)
- evaluator stack is quarantined (`meta_ruler.md`, award files)
- methodology is explicit and subordinate (`dnm_methodology.md`)
- presentation firewall artifacts exist and are referenced:
- `presentation_layer_guide.md`
- `presentation_layer_visual_map.md`

Gate to exit Stage 1.5:
- every file reference used in any “governing” document is resolvable (exists)
- custom instructions (external to repo) are updated to enforce:
- one-file-at-a-time
- dependency order
- no Stage-2 without explicit user command

---

### Stage 2 — Chapter Integration (Presentation Layer Only)
Objective:
- map the frozen spine into examiner-legible Chapters 1–3 using the presentation-layer guide and visual map.

Hard constraint:
- Stage 2 may not begin without explicit user instruction:
- “Proceed to Stage-2”

---

## Change Control Protocol (Applies to All Stages)

### CCP-1 — Single-File Mutation
Only one file may be edited per step.

### CCP-2 — Reference Integrity
If a file introduces a reference to another file, that referenced file must:
- exist in the project files, and
- match canonical naming.

If not, the change is invalid.

### CCP-3 — Forbidden Backflow
Any file classified as “presentation” or “evaluation” must pass:
- Deletability test: removing it changes nothing upstream.

### CCP-4 — No Hidden Parallel Changes
A “parallel change” is valid only if:
- explicitly listed, and
- applied by text-level enforcement across affected files.

Assuming parallel change was applied is prohibited.

---

## Classification of File Types (MECE)

### Type A — Canonical Spine (Truth-Defining)
Files 1–11 in Dependency Order.
These define ontology, theory, execution, falsification, and frame.

### Type B — Guardrails (Truth-Preserving)
- `substrate0_prime_purity_test.md`
- this file (`arc_sequencing_protocol.md`)
- `presentation_layer_guide.md`
- `presentation_layer_visual_map.md`

These prevent drift and enforce separation.

### Type C — Evaluation/Visibility (Truth-Describing Only)
- `evp_v3.md`
- `meta_ruler.md`
- award extraction / pattern / ruler files

These must never influence Type A.

---

## Drift Trigger

If any of the following occurs:
- a forbidden term reappears (e.g., NSU),
- evaluation language becomes upstream authority,
- discretion or interpretation enters SFEU execution,
- CME becomes “elimination” instead of relocation,
- counterfactual discriminators become narrative,

Trigger response:
- Stop.
- Revert.
- Fix the earliest violating file by dependency order.

---

## Status

Frozen (v2.0).

This file changes only if:
- the project’s dependency order changes, or
- ARC stage definitions are explicitly revised by the user.


