# Extruder

## Purpose
Biostruct-70 relies on **direct, high-pressure, on-site LFAM** without a drying phase.  
The extruder therefore defines the feasible operating window for:

- bead geometry and dimensional stability,
- interlayer welding and void collapse,
- thermal–pressure–shear history of the material.

This document evaluates two extrusion **set ups** relevant to Biostruct-70:

- **Screw extrusion (single / twin screw)** — optimized for **continuous flow**
- **Piston extrusion (single / dual piston)** — optimized for **maximum pressure**

The conclusion is intentionally **left open**, pending **Biostruct-70-des field testing**.

---

## Performance requirements (Biostruct context)

### Primary
- Continuous, low-pulsation bead delivery  
- High compaction pressure to activate hydrogen bonding and minimize porosity  
- Stable thermal window (plasticization without degradation)  
- Controlled shear (homogenization without thermal runaway or fiber damage)

### Secondary
- Fast start/stop response  
- Clog tolerance and safe de-clogging  
- Modular nozzle geometry  
- Instrumentation: pressure, temperature, torque/current, mass flow

---

## Set up A — Screw extrusion (continuous-flow optimized)

### A1. Single-screw pellet extruder
A rotating screw conveys, compresses, and meters pelletized or granulated feedstock through a heated barrel and nozzle.

**Strengths**
- Intrinsically continuous flow
- Scalable throughput
- Mature industrial ecosystem

**Limitations**
- Pressure ceiling vs piston systems
- Shear heating and residence-time sensitivity

---

### A2. Twin-screw extrusion
Co- or counter-rotating screws provide superior mixing and compounding.

**Strengths**
- Superior homogenization
- Better tolerance to heterogeneous feedstocks

**Limitations**
- Higher mechanical and thermal complexity

---

## Set up B — Piston extrusion (pressure-optimized)

### B1. Single-piston extrusion
Material is pushed directly through a nozzle using mechanical or hydraulic force.

**Strengths**
- Very high peak pressure

**Limitations**
- Non-continuous by default

---

### B2. Dual-piston continuous systems
Two pistons alternate extrusion and refill cycles via a valve/manifold system.

**Strengths**
- High pressure with near-continuous flow

**Challenges**
- Valve timing and pulsation suppression
- Seal wear and maintenance

---

## Research background and references

- Netto et al., *Screw-assisted extrusion additive manufacturing: a review*  
  https://doi.org/10.1016/j.addma.2021.102038

- Duty et al., *Structure and mechanical behavior of BAAM materials* (ORNL)  
  https://info.ornl.gov/sites/publications/files/Pub69762.pdf

- Brenken et al., *Large-scale polymer additive manufacturing*  
  https://doi.org/10.1016/j.addma.2018.01.002

- Love et al., *Importance of polymer processing to AM* (ORNL)  
  https://info.ornl.gov/sites/publications/files/Pub45789.pdf

- Buswell et al., *3D printing using concrete extrusion*  
  https://doi.org/10.1016/j.cemconres.2018.07.006

- WASP industrial large-scale printers  
  https://www.3dwasp.com/en/industrial-3d-printers/

---

## Current conclusion (open)
Screw extrusion remains the most robust route to continuous LFAM.  
Piston-based systems remain candidates if extreme compaction pressure proves decisive.

Final selection is pending **Biostruct-70-des field testing**.
