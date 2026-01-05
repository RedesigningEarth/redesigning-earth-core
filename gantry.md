# Gantry — Motion System Log

## Status
IN PROGRESS  
Motion ststem selection  
Baseline configuration chosen: track-gantry + limited-tilt printhead

## Scope
- On-site LFAM for full-scale habitation shells and integrated functions  
- High-pressure, solid-state extrusion (pressure-dominated consolidation)  
- Continuous printing over multi-building footprints  
- Limited non-planar deposition (≤45° nozzle tilt / head rotation)

## Rationale
Full-scale structural LFAM is dominated by:
- force closure under high extrusion pressure,
- positional repeatability over long duration,
- deterministic kinematics suitable for process control and later certification.

A track-mounted gantry provides the most scalable stiffness and repeatability for continuous structural deposition, while a limited-tilt head enables non-planar features (e.g., sloped slabs, collision avoidance, smoother transitions) without adopting full serial-robot kinematics.

## Research — Relevant prior art and enabling research (links)

### Track-mounted construction gantries (site scale)
- COBOD BOD3 product overview (modular steel gantry + extendable ground-based track system):  
  https://cobod.com/the-bod3/

- COBOD announcement describing the BOD3 track system for continuous extension along the print length axis (Y):  
  https://cobod.com/cobod-launches-the-most-advanced-3d-printer-so-far/

- N3XTCON deliverable describing gantry-based 3D construction printer development and rapid tool changing / customizable carriage concepts (including different tools on the carriage):  
  https://www.teknologisk.dk/_/media/90338_N3XTCON_Gantry-Based%203DC-Printer.pdf

### Construction-scale design-to-printing workflows (in-situ printing)
- Xu, W. et al. (2022). Design-to-printing workflow for robotic in-situ 3D printing of a full-scale farmhouse (process chain and in-situ constraints):  
  https://www.sciencedirect.com/science/article/pii/S2214509522005745

### Limited non-planar / nozzle reorientation research (relevant to ≤45° head tilt)
- Darweesh, B. et al. (2023). Non-planar granular 3D printing (nozzle reorientation used to avoid collisions and improve print consistency):  
  https://link.springer.com/article/10.1007/s41693-023-00107-5

- Li, S. et al. (2023). Digital design and parametric study for 3D printing on non-planar surfaces (toolpath generation for non-planar deposition):  
  https://www.sciencedirect.com/science/article/abs/pii/S0926580522004940

- Ji, Z. et al. (2023). Conformal printing onto uneven substrates (non-planar toolpaths derived from planar inputs):  
  https://www.nature.com/articles/s41598-023-48547-x

### Why limited tilt matters for “roof / slab” geometries at house scale
- Discussion of ICON’s roof-printing constraints and the role of overhang angles in layer-based construction printing (context for slope strategies):  
  https://www.construction-physics.com/p/what-progress-has-icon-made-on-3d

- ICON robotics overview (context on house-scale printer systems):  
  https://iconbuild.com/robotics

## Decision tree — Selecting motion system for Biostruct

### Step 1 — Is the process pressure-dominated (high extrusion force) and continuous?
- YES → prioritize stiffness, repeatability, and predictable force closure over dexterity.

### Step 2 — Is the required build envelope house-scale (multi-meter spans, multi-room, potential multi-unit runs)?
- YES → prefer motion systems that scale by extending linear axes/rails.
  - Track-mounted gantry scales by extending ground rails and repeating steel modules.

### Step 3 — Is geometry primarily walls + slabs with limited non-planar segments?
- YES → do not adopt full serial robot arm as the primary motion system.
  - Add limited head rotation/tilt to handle:
    - sloped deposition transitions,
    - collision avoidance at corners/returns,
    - reduced stair-stepping on visible surfaces.

### Step 4 — Are slopes/overhangs required beyond planar stacking limits?
- YES → add a controlled tilt DOF (≤45°) to extend slope envelopes while keeping the platform stiff.

### Step 5 — Does the workflow require printing multiple buildings without repeated teardown/setup?
- YES → prefer extendable track systems to minimize reinstallation and preserve calibration.

### Output decision
SELECT:
- Track-mounted gantry (Cartesian) as primary motion platform  
- Flexible printhead with limited rotation/tilt (≤45°) as secondary degree of freedom

REJECT (as primary platform):
- Serial robot arm for structural printing under high pressure (reach stiffness and drift penalties)

## Implementation notes (Biostruct-specific)
- Treat the gantry as the metrology backbone (reference frame).  
- Implement head tilt as a constrained DOF with:
  - collision model,
  - tilt-aware slicing / toolpath projection,
  - tilt-dependent bead geometry and compaction limits.  
- Reserve any additional dexterity (wrist/arm) for:
  - finishing,
  - non-structural features,
  - inspection / sensing heads.

## Open questions / Future scope (critical)
- Tilt-dependent bead stability and compaction under pressure  
- Layer bonding consistency when tool normal changes  
- Calibration strategy across long tracks and multi-day runs  
- Head mass vs dynamic error limits on gantry carriage

## Position in automation roadmap
Defines the baseline motion system for house-scale Biostruct LFAM:
a scalable, stiff platform (track gantry) augmented with minimal dexterity (≤45° printhead tilt).
