# Print specifications

## Purpose
This document defines **baseline print specifications** for Biostruct-70 LFAM printing.  
The parameters below are not final prescriptions but **engineering targets** derived from first‑principle constraints (shear, pressure, thermal window, and print time).  
Final values remain **pending Biostruct-70-des field testing**.

---

## Nozzle specifications

### Diameter range
- **2–3 mm nominal nozzle diameter**

**Rationale**
- Enables **fine geometric detail** relative to LFAM norms
- Induces **high shear rates** in the nozzle land, reducing apparent viscosity of shear‑thinning biopolymer melts
- Improves **interlayer wetting and molecular contact** due to higher exit velocity and stress alignment

This range represents a compromise between:
- resolution,
- achievable mass flow,
- and acceptable pressure requirements.

---

## Print speed specifications

### Linear print speed
- **> 200 mm/s target print speed**

**Rationale**
- Limits total print duration for large structures
- Maintains material above glass‑transition / softening temperature during interlayer contact
- Supports continuous deposition regimes required for structural consistency

High print speed is only viable when paired with:
- sufficient pressure head,
- stable thermal control,
- and continuous flow extrusion.

---

## Proposed set up for transparent printing

### Objective
Achieve **optical or near‑optical transparency** in Biostruct‑70 by minimizing scattering sources at the micro‑ and meso‑scale.

Transparency is governed by:
- void fraction,
- refractive‑index discontinuities,
- molecular orientation,
- and surface roughness.

---

### Pressure regime
- **Very high extrusion pressure** (relative to standard LFAM)
- Objective: **collapse micro‑voids** and eliminate air inclusions
- Pressure must exceed elastic recovery forces of the polymer network at extrusion temperature

High pressure also promotes:
- chain proximity,
- hydrogen bond formation,
- and density homogenization.

---

### Molecular alignment
- High shear rates (small nozzle + high speed) induce **polymer chain alignment**
- Alignment reduces internal refractive index variation
- Analogous mechanisms are used in:
  - drawn polymer fibers,
  - hot‑pressed transparent bioplastics,
  - shear‑aligned nanocellulose films

Controlled alignment is beneficial up to the point where:
- birefringence becomes optically relevant.

---

### Maximum printable thickness (transparent sections)
- **Thin‑wall strategy required**
- Proposed single‑pass wall thickness: **≤ 5–8 mm**
- Thicker transparent sections require:
  - multi‑pass lamination under heat and pressure, or
  - post‑pressing / surface reflow

Bulk transparency is not expected in thick LFAM walls without secondary consolidation.

---

### Post‑processing (surface optics)
Even with void‑free bulk material, **surface roughness dominates optical loss**.

Required post‑processing:
- mechanical polishing (progressive grit reduction),
- optional thermal surface reflow,
- or controlled solvent vapor smoothing (if chemically compatible).

Surface treatment does not affect structural integrity if limited to the outer optical layer.

---

## Research background and references

### Shear‑induced viscosity reduction
Shear‑thinning behavior and viscosity collapse under high shear is well documented in polymer melts:

- Barnes, *Shear‑thinning liquids*, Journal of Rheology, 1997  
  https://doi.org/10.1122/1.550955

---

### Polymer chain alignment and optical clarity
Molecular orientation as a driver for transparency and mechanical strength:

- Ward & Sweeney, *An Introduction to the Mechanical Properties of Solid Polymers*, Wiley  
  https://onlinelibrary.wiley.com/doi/book/10.1002/9780470515247

- Dealy & Wissbrun, *Melt Rheology and Its Role in Plastics Processing*, Springer  
  https://doi.org/10.1007/978-94-007-6395-1

---

### Transparency in biopolymers and nanofibrillar systems
Void elimination and nanoscale uniformity are key for transparency:

- Nogi et al., *Optically transparent nanofiber paper*, Advanced Materials, 2009  
  https://doi.org/10.1002/adma.200803174

- Zhu et al., *Transparent and strong cellulose nanopaper*, Advanced Materials, 2011  
  https://doi.org/10.1002/adma.201100610

These mechanisms are directly relevant to chitin/chitosan‑based systems.

---

### Surface roughness and optical scattering
Surface finish dominates optical transmission losses:

- Bennett & Porteus, *Relation between surface roughness and specular reflectance*, JOSA, 1961  
  https://doi.org/10.1364/JOSA.51.001231

---

## Current conclusion (open)
- Fine nozzles (2–3 mm) combined with **high pressure and high speed** are theoretically compatible with both structural printing and localized transparency.
- Achieving transparency at LFAM scale is primarily a **compaction and surface‑finish problem**, not a material limitation.

Final parameter validation remains **pending Biostruct-70-des field testing**.
