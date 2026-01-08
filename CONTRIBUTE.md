# Contributing to redesigning-earth-core

This repository is intended for open collaboration on materials, manufacturing methods, and self-supporting habitat systems under an open hardware / open design regime.

## License scope (read before contributing)

- The repository is licensed under **CERN Open Hardware Licence v2 – Strongly Reciprocal (CERN OHL v2-S)**.
- By submitting a contribution (pull request, issue with attached patches, or direct commit where permitted), you agree that your contribution is provided under **CERN OHL v2-S**.
- If anything in this repository conflicts with the LICENSE file, the **LICENSE** file governs.

## How to contribute (fast path)

1. **Open an Issue first** (recommended for non-trivial changes)
   - Describe: what you want to change, why, and what evidence supports it.
2. **Fork + branch**
   - Fork the repo, create a branch in your fork.
3. **Make changes**
   - Keep edits focused and well-scoped.
4. **Open a Pull Request (PR)**
   - Explain: motivation, exact change, evidence, risks, and any open questions.

## Canonical vs Variant contributions

This repo keeps a clean separation between:
- **Canonical docs**: the current best-known baseline maintained by the project.
- **Variants**: alternative approaches, local adaptations, speculative directions, or competing parameter sets.

### A) Proposing changes to canonical docs
Submit a PR that edits the relevant `.md` file(s). Your PR should include:
- Clear problem statement
- Proposed edits
- Supporting evidence (papers, test data, photos, logs, etc.)
- Safety/risks (material hazards, mechanical failure modes, etc.)
- Reproducibility details (exact formulations, temperatures, pressures, moisture %, equipment)

Canonical changes are merged only after maintainer review.

### B) Proposing a variant (preferred for speculative or context-dependent work)
Add a new file under a dedicated variants folder next to the topic, for example:

- `variants/<topic-slug>/v001__short-title__by-<githubuser>.md`

Include at the top of the variant:
- What it changes relative to canonical
- Why it may be better in a specific context
- Evidence and constraints

If you are unsure whether your contribution is canonical or variant, default to **variant**.

## Documentation standards (what makes a PR mergeable)

- **Be explicit**: numbers, units, ranges, equipment, and conditions.
- **Be reproducible**: a skilled person should be able to replicate the procedure.
- **Declare assumptions**: what you held constant, what you changed.
- **Track provenance**: link sources and cite papers; include DOIs where available.
- **Separate observation from interpretation**:
  - Observation: what happened
  - Interpretation: what you think it means

## Safety, legality, and ethics

- Do not include instructions intended to cause harm or evade regulations.
- Flag hazards clearly (corrosives, high temperature/pressure, fumes, allergens).
- If you propose field tests, include appropriate containment and disposal practices.

## Patents and contributions (high importance)

See **PATENTS.md**. In summary:
- The project is meant to stay free to use commercially.
- Contributions are accepted only on terms compatible with CERN OHL v2-S, including its patent-related provisions.
- Do not contribute material you cannot license under these terms.

## Maintainer workflow (what to expect)

Maintainers may:
- request additional evidence or clarification
- suggest restructuring into a variant instead of changing canonical
- edit wording for consistency and safety
- reject or close a PR if it is not reproducible or conflicts with the project direction

## Contact / coordination

For high-impact collaboration (suppliers, labs, industrial partners), open an Issue describing the scope and tag maintainers.

Thank you for helping keep this repository rigorous, reproducible, and defensively open.
