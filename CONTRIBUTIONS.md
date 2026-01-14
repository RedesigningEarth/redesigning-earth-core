# Contributions to redesigning-earth-core

This repository is intended for open collaboration on **materials, manufacturing methods, and self-supporting habitat systems** under a defensively open (strongly reciprocal) open-hardware regime.

Contributing here means operating inside a **high-coherence engineering system**.  
Behavioral discipline and technical rigor are treated as first-order constraints.

---

## 0. Interaction Protocol (Governing Constraint)

All interaction in this repository — issues, pull requests, reviews, discussions, and external references — is governed by the following invariants.

This protocol is **not cultural or optional**. It is an engineering constraint.

### Core axiom
> **People are not the unit of progress. Coherent contributions are.**

### 0.1 Errors are information
- Errors, flaws, and failures are treated as data.
- Identifying an error increases trust.
- Defensiveness is signal loss.

**Rule:**  
If you find a flaw, document it clearly.  
If a flaw is found in your work, acknowledge it and update or fork.

### 0.2 Disagreement is functional
- Disagreement indicates phase mismatch, not conflict.
- The dissenter is responsible for increasing clarity, not persuasion.

Allowed: models, diagrams, data, prototypes  
Not allowed: rhetoric, moral framing, identity-based arguments

### 0.3 Forking is neutral
- Forking is expected and healthy.
- Forks are not rejections or failures.
- Re-merging is encouraged when coherence allows.

**Rule:**  
Fork early, fork cleanly, document divergence.

### 0.4 No implicit hierarchy
- Authority is always traceable to current contributions.
- Reputation, seniority, or charisma confer no standing.
- Influence decays unless renewed via output.

**Rule:**  
If you want influence, contribute artifacts.

### 0.5 Action beats explanation
- Explanations without implementation are incomplete work.

**Rule:**  
If discussion exceeds three exchanges without convergence, produce an artifact or fork.

### 0.6 Operational psychological safety
Psychological safety here means:
- You can point out flaws without penalty
- You can be wrong without loss of standing
- You can fork without justification
- You can disengage without explanation

Violations are treated as **system bugs**.

---

## 1. License Scope (Read Before Contributing)

- Licensed under **CERN Open Hardware Licence v2 – Strongly Reciprocal (CERN OHL v2-S)**.
- By contributing, you agree your work is provided under these terms.
- If conflicts exist, the LICENSE file governs.

---

## 2. How to Contribute (Fast Path)

1. **Open an Issue first** (recommended for non-trivial changes)  
   Describe what you want to change, why, and what evidence supports it.

2. **Fork + branch**  
   Fork the repo and create a branch in your fork.

3. **Make changes**  
   Keep edits focused and well-scoped. Prefer artifacts over explanation.

4. **Open a Pull Request**  
   Explain motivation, exact change, evidence, risks, and open questions.

---

## 3. Canonical vs Variant Contributions

This repository enforces a strict separation:

### Canonical
The current best-known, reviewed baseline.

### Variants
Alternative approaches, speculative directions, or context-specific adaptations.

#### Canonical changes
PR must include:
- clear problem statement
- proposed edits
- supporting evidence
- safety and risks
- full reproducibility details

Merged only after maintainer review.

#### Variant contributions (preferred when unsure)
Add a file under:
```
variants/<topic-slug>/v001__short-title__by-<githubuser>.md
```

Include:
- what changes vs canonical
- why it may be better in context
- evidence and constraints

Default to variant if unsure.

---

## 4. Documentation Standards (Merge Criteria)

A contribution is mergeable only if it is:
- explicit (numbers, units, conditions)
- reproducible
- assumption-aware
- traceable (sources, DOIs)
- clearly separating observation from interpretation

---

## 5. Safety, Legality, and Ethics

- Do not include instructions intended to cause harm or evade regulation.
- Clearly flag hazards (corrosives, pressure, heat, fumes, allergens).
- Field tests require containment and disposal plans.

---

## 6. Patents and Contributions (High Importance)

See PATENTS.md.

- The project must remain free to use commercially.
- Contributions must comply with CERN OHL v2-S patent provisions.
- Do not contribute material you cannot license accordingly.

---

## 7. Maintainer Workflow

Maintainers may:
- request clarification or evidence
- suggest restructuring into variants
- edit wording for safety and coherence
- reject work that is not reproducible or aligned

Decisions are based on **artifact quality**, not intent or status.

---

## 8. Contact / High-Impact Coordination

For suppliers, labs, or industrial collaboration:
- Open an Issue describing scope
- Tag maintainers
- Provide concrete artifacts

---

## Final Note

Redesigning Earth is not a community or identity.

It is a **coherence engine for post-industrial civilization**.

If these constraints feel strict, that is intentional.
