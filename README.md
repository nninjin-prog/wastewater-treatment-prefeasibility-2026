# Pre-Feasibility Design and Assessment of a Wastewater Treatment Plant for Khun Od Meat Processing Facility

> **GMIT Feasibility Study Project 2026 — Team 5**  
> *A 21-day interdisciplinary engineering study by 13 students across six engineering disciplines*

---

## Project Overview

Mongolia's meat processing sector operates almost entirely without industrial wastewater pretreatment. As of Q3 2025, only **1 of 47** registered facilities had installed a compliant system, despite MNS 6561:2024 — a binding national standard governing effluent quality before discharge to Ulaanbaatar's municipal sewer.

This project delivers a **complete pre-feasibility design** for a wastewater treatment plant at **Khun Od LLC**, a full-chain meat processing facility in Emeelt, Songinokhairkhan District, Ulaanbaatar — and establishes a **replicable framework** applicable to the remaining 46 non-compliant facilities nationwide.

**Recommendation: Go.** The plant is recommended to proceed to detailed engineering and construction.

---

## My Contributions

**Chapter 1 — Introduction:** Background and context, problem statement, project objectives and scope, added value, and report structure.

**Chapter 2 — Project Management:** Team overview, challenges faced and solutions implemented, and lessons learned across the 21-day study period.

---

## Technical Design Summary

### Wastewater Characteristics (Design Basis)
| Parameter | Design Value | MNS 6561:2024 Limit |
|-----------|-------------|----------------------|
| COD | 4,017 mg/L | ≤ 500 mg/L |
| BOD₅ | 2,069 mg/L | ≤ 300 mg/L |
| Ammonia | 101 mg/L | ≤ 45 mg/L |
| Total Phosphorus | 18 mg/L | ≤ 5 mg/L |
| FOG | 1,000 mg/L | ≤ 100 mg/L |
| Average Flow | 10.3 m³/day | — |

### Treatment Train
```
Influent → Bar Screen → Equalization Tank → Drum Screen
        → FeCl₃ Coagulation/Flocculation → Dissolved Air Flotation (DAF)
        → Sequencing Batch Reactor (SBR) → Screw Press Dewatering → Effluent
```
All unit processes specified as package equipment rated for operation at **−35°C**.  
Plant footprint: **181 m²** insulated building within Khun Od LLC's existing site.

### Sludge & Nutrient Recovery
- **~18.54 tonnes/year** of dewatered sludge cake generated
- Indoor aerated static pile composting converts sludge into **7–9 tonnes/year** of stabilized agricultural fertilizer
- Phased **struvite precipitation** subsystem for phosphorus recovery (second-stage)

### Automation & Control
- Highly Automated architecture: **5× Siemens SIMATIC S7-1200 PLCs** + central **MCGS Pro SCADA** workstation
- Critical effluent quality interlock — discharge blocked unless inline analyzers confirm MNS 6561:2024 compliance
- **30 kVA diesel generator** for biological treatment protection during grid outages

---

## Environmental & Safety Outcomes

| Metric | Value |
|--------|-------|
| COD diverted from municipal sewer | ~39 kg/day |
| FOG diverted from municipal sewer | ~10.3 kg/day |
| Operational carbon footprint | 71.5 t CO₂e/year |
| LCA outcome | Net-positive |
| HAZOP Critical hazards identified | 10 (all with pre-commissioning resolutions) |

---

## Economic Analysis

| Item | Value |
|------|-------|
| Total CAPEX | $282,916 |
| Unit cost | $9,431 per m³/day |
| Annual risk exposure (non-compliance) | $63,800–$123,000 |
| Simple payback on avoided costs | ~4 years |
| Financing option | DBM Green SME Facility at 8.5% |
| PV of avoided costs (14%, 10 yr) | $436,987 |

---

## Key Findings

1. **Technical feasibility confirmed** — The proposed treatment train achieves full compliance with all six MNS 6561:2024 parameters with substantial margin.
2. **Financially viable** — Cost avoidance from regulatory penalties delivers a ~4-year payback; concessional green financing is available.
3. **Replicable framework** — This pre-feasibility methodology is designed from the outset for adoption across the 46 facilities currently operating without pretreatment.
4. **Environmental net-positive** — LCA confirms net-positive outcome; plant diverts significant organic load from the Tuul River watershed.
5. **Safety-ready** — HAZOP study identified and resolved all Critical hazards before commissioning.

---

## Team & Disciplines

| Discipline Area | Contributors |
|----------------|-------------|
| Introduction & Project Management | Ninjin N. |
| Site & Regulatory Context | Munkh-Orgil Ts. |
| Process Design & Treatment Train | Anarmaa E., Temuulen D. |
| Nutrient Recovery & Sludge Management | Dulguun S. |
| Mechanical & Structural Design | Temuulen Kh., Tuvshinbayar B. |
| SCADA & Automation | Buyandelger J., Munkhsuld Sh., Erdenebat N. |
| Electrical & Energy | Namuun Ts., Khuslen A. |
| Environmental & Safety | Temuulen D., Chimeg-Erdene L. |

**Coach:** Prof. Bayanmunkh  
**Institution:** GMIT (Mongolian University of Science and Technology)  
**Location:** Ulaanbaatar, Mongolia | **Year:** 2026

---

## How to Use This Repository

This repository contains the full pre-feasibility report PDF. It documents a complete engineering study including:

- Wastewater characterization and design basis
- Full process design with mass balance calculations
- P&I diagrams and plant layout drawings
- SCADA/automation architecture
- Electrical load analysis and generator sizing
- Environmental Impact Assessment and Life Cycle Assessment
- HAZOP safety analysis
- Financial and economic analysis

---

*This project was completed as part of the GMIT Feasibility Study Program (FSP) 2026.*
