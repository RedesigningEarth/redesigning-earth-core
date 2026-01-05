# Utility-Voids — Structural Log

## Status
IN PROGRESS  
Mechanism exploration  
Architectural-scale LFAM execution pending

## Scope
- Air ducts (supply / return)  
- Water supply and drainage  
- Heating and cooling channels  
- Data and control conduits  

## Rationale
Encode utilities as continuous voids inside the load-bearing print volume to eliminate secondary service layers and post-print penetrations.

This is treated as **structural mechanism exploration**, not a finalized construction system.

## Research — Directly Printed Utility Voids in LFAM (No Formwork)

### Scope delimitation
This research overview includes only approaches where cavities and channels are:
- generated directly during extrusion,
- permanently embedded in the structure,
- compatible with continuous, pressure-consolidated deposition,
- not relying on removable molds, sacrificial formwork, or post-processing removal.

### Void-first toolpath strategies
Peer-reviewed AM literature shows that internal channels must be treated as primary geometric constraints rather than subtractive features.

Key findings:
- Curvature-continuous routing is required to avoid collapse and stress concentration.
- Channel diameters must typically exceed ~1.2–1.5× nozzle diameter to remain open.
- Stability is governed by print-time rheology rather than cured-state strength.

Research basis:
- Tao, Y., Li, P., Pan, L. (2021). *A review on voids of 3D printed parts by fused filament fabrication*. Journal of Materials Research and Technology.  
  https://doi.org/10.1016/j.jmrt.2021.10.108  
  https://www.sciencedirect.com/science/article/pii/S2238785421012448

### Multi-scale internal channel networks
LFAM polymer and composite research demonstrates that hierarchical channel systems are mechanically superior to uniform cavities.

Key findings:
- Hierarchical (micro / meso / macro) channel networks improve load redistribution.
- Channels aligned with principal stress trajectories reduce structural penalties.
- Failure is dominated by fresh-state instability, not cured-state collapse.

Research basis:
- Tomholt, L., Meggers, F., Moini, R. (2024). *Angled planar toolpath strategies for internal channel stability in extrusion-based 3D printing*.  
  https://laratomholt.nl/dc2024.html

### Continuous voids vs discrete cavities
Across extrusion AM studies, continuous channels consistently outperform isolated cavities.

Key findings:
- Continuous voids allow longitudinal stress flow around cavities.
- Discrete cavities act as buckling and crack initiation sites.
- Junctions must be volumetric enlargements rather than sharp intersections.

Research basis:
- Desktop Metal. *Internal channels in additive manufacturing*.  
  https://www.desktopmetal.com/resources/internal-channels

### Functional differentiation of utilities
Direct-embed suitability varies by utility type.

Most compatible:
- Air distribution  
- Data conduits  
- Low-temperature hydronic loops  

Moderately compatible:
- Water supply  
- Drainage (requires slope + access volumes)

Least compatible without redundancy:
- High-pressure plumbing  
- Systems requiring frequent replacement

### Identified failure modes
Dominant unresolved risks in direct cavity printing:
- Fresh-state roof collapse  
- Void wall thinning under pressure  
- Interlayer discontinuities around curved voids  
- Stress amplification at junction nodes  
- Maintenance inaccessibility in monolithic networks  

## Interpretation (non-final)
Current LFAM research supports directly printed utility voids when voids are treated as primary geometry, routed continuously, and consolidated under sufficient pressure.

Biostruct’s high-pressure, solvent-free extrusion is structurally advantaged compared to drying-dependent systems.

## Open questions / Future scope (critical)
- Maximum unsupported span at target viscosity  
- Void-wall densification vs collapse threshold  
- Junction-node geometry limits  
- Long-term clogging and biofouling  
- Inspection and repair strategies in monolithic networks  

## Planned field test scope (next decisive step)

### Objective
Determine whether continuous utility voids can be printed and consolidated without compromising structural integrity.

### Minimum test matrix
1. Void stability during print  
2. Structural response under load  
3. Leak and collapse screening  

## Decision criteria
- **PROMISING** if voids remain stable without structural penalty.  
- **LIMITED** if sacrificial measures or heavy post-processing are required.  
- **FAILED** if collapse or closure dominates.

## Position in structural roadmap
Defines feasibility of monolithic structures with intrinsic service integration.
