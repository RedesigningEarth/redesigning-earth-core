# Biostruct-70-DES — Material Log

## Status
IN PROGRESS  
Current experimental frontier

## Composition (wt%)
- Chitin: 35%
- Chitosan: 35%
- Choline chloride: 15%
- Citric acid: 15%
  
## Technical Data Sheet / Material Preparation Protocol
[attachments/tds-biostruct-70-des.pdf](attachments/tds-biostruct-70-des.pdf)

## Rationale
Evaluate whether a deep eutectic solvent (DES) system can enable partial chitosan plasticization at reduced temperature while avoiding fully solvent-dominated behavior.

This formulation is treated as **mechanism exploration**, not a final construction formulation.

## Experimental results

### Test 1 — Static premix heating
**Date:** 2025-11-29  
**Method:** Static premix, heated  
**Temperature:** 140 °C

**Observations:**
- Localized pockets of plasticized DES.
- No observable bulk plasticization of chitosan.
- Powder matrix largely retained.

**Attachments (rename on upload):**
- [attachments/biostruct-70-des_2025-11-29_static-heat_140c_visual-01.jpg](attachments/biostruct-70-des_2025-11-29_static-heat_140c_visual-01.jpg)
- [attachments/biostruct-70-des_2025-11-29_static-heat_140c_visual-02.jpg](attachments/biostruct-70-des_2025-11-29_static-heat_140c_visual-02.jpg)

### Test 2 — DES pre-melt + incremental powder addition
**Date:** 2025-12-08  
**Method:** DES pre-melt, manual hot mixing, stepwise powder addition (15% → 30% → 50%)  
**Temperature:** 140 °C

**Observations:**
- DES fully plasticized prior to powder addition.
- Formation of viscous, dough-like composite during hot mixing.
- Partial plasticization of chitosan observed.
- Material becomes extremely rigid after cooling/drying (potential densification + strong bonding, brittleness risk).

**Attachments (rename on upload):**
- [attachments/biostruct-70-des_2025-12-08_des-premelt_140c_visual-01.jpg](attachments/biostruct-70-des_2025-12-08_des-premelt_140c_visual-01.jpg)
- [attachments/biostruct-70-des_2025-12-08_des-premelt_140c_visual-02.jpg](attachments/biostruct-70-des_2025-12-08_des-premelt_140c_visual-02.jpg)
- [attachments/biostruct-70-des_2025-12-08_des-premelt_140c_visual-03.jpg](attachments/biostruct-70-des_2025-12-08_des-premelt_140c_visual-03.jpg)
- [attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-01.jpg](attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-01.jpg)
- [attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-02.jpg](attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-02.jpg)
- [attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-03.jpg](attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-03.jpg)
- [attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-04.jpg](attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-04.jpg)
- [attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-05.jpg](attachments/biostruct-70-des_2025-12-08_hot-mix_140c_visual-05.jpg)

## Interpretation (non-final)
- DES enables localized and partial plasticization below decomposition limits.
- Observed transition: solid powder → viscous composite → rigid solid on cooling/drying.
- Structural suitability remains unknown pending extrusion/pressure testing and environmental durability tests.

## Open questions / Future scope (critical)
This formulation is unresolved with respect to:
- Continuous extrusion stability (feeding, pressure build-up, clogging)
- Phase homogeneity under shear (segregation / DES bleeding)
- Pressure–densification relationship (does pressure measurably improve density/strength?)
- Water sensitivity (uptake, swelling, softening, reversibility)
- Brittleness vs toughness trade-off
- Dimensional stability during drying/cooling

## Planned field test scope (next decisive step)

### Objective
Determine whether Biostruct-70-DES can be extruded and consolidated in a way that yields structurally relevant solids **without post-processing** beyond cooling/drying.

### Minimum test matrix
Record all settings and outcomes for each run.

1. **Extrusion feasibility**
   - Can the material feed continuously?
   - Can stable flow be maintained for ≥ ___ minutes?
   - Does pressure build without nozzle blowout or repeated clogging?

2. **Consolidation behavior**
   - Does higher pressure produce visibly denser output (lower porosity, higher mass/volume)?
   - Does interlayer bonding improve with pressure and thermal stability?

3. **Environmental response (screening)**
   - Water exposure: 1 h, 6 h, 24 h soak (mass change + visible degradation)
   - Dimensional change and cracking after re-drying

### Output artifacts
- At least one standardized bar/coupon geometry for comparison (even if non-ASTM), or a consistent printed bead geometry for densification and water tests.

## Decision criteria
Classify after field test as:
- **PROMISING** if extrusion is stable, pressure improves consolidation, and DES does not dominate final behavior.
- **LIMITED** if extrusion works but mechanical/water performance is marginal or requires non-scalable post-processing.
- **FAILED** if extrusion is unstable, phase separation dominates, or solvent-like behavior prevents structural integrity.

## Position in material roadmap
Defines the current boundary between:
- dry, pressure-dominated consolidation, and
- solvent-assisted plasticization mechanisms (DES).

Results will determine whether DES components are removed entirely or retained only as minor, transient processing aids.
