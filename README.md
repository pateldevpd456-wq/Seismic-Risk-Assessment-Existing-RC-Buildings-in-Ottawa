# 🏗️ Seismic Risk Assessment – Existing RC Buildings in Ottawa | CVG 6320
### Seismic Risk Assessment & Management of Existing Buildings | University of Ottawa | Jan – Feb 2025

---

## 📋 Project Overview

Performed seismic risk assessment for two 6-storey reinforced concrete buildings in Ottawa, ON, designed under NBC-1980 (between pre-code and post-benchmark). Using the **FEMA P-155 methodology**, building capacity curves were constructed and intersected with damped demand spectra to determine probabilities of collapse across four scenarios: baseline construction era, pre-code (1915), post-benchmark (2010), and severe vertical irregularity.

| Parameter | Value |
|---|---|
| Location | Ottawa, ON (Site Class C) |
| Building Height | 6 storeys × 3.6 m = 21.8 m (60 ft) |
| Seismicity Region | Moderately High (MH) — Sa(0.2) = 0.698g |
| Design Code | NBC-1980 (between Pre-Code & Post-Benchmark) |
| Methodology | FEMA P-155 Capacity Spectrum Method |
| Lognormal Std. Dev. (βc,p) | 0.75 |

---

## 🏢 Building Types

| Case | FEMA Type | SFRS | Building Description |
|---|---|---|---|
| Case 1 | C1 | Conventional Moment Resisting Frames | All frames identical in geometry & stiffness |
| Case 2 | C2 | Conventional Shear Walls | RC shear wall system |

---

## 🔑 Key Work Completed

- Classified Ottawa's seismicity as Moderately High (MH) using NBCC 2020 Seismic Hazard Tool (Sa(0.2) = 0.698g, Sa(1.0) = 0.218g)
- Constructed elliptical building capacity curves per FEMA P-155 Eq. 4-2 through 4-5, computing yield and ultimate points for each building type and construction era
- Intersected capacity curves with damped demand spectra to determine peak spectral displacement response
- Computed probability of complete damage using lognormal fragility function (FEMA P-155 Eq. 4-10) and converted to collapse probability using building-specific collapse factors
- Analyzed four scenarios: baseline NBC-1980, pre-code (1915), post-benchmark (2010), and severe vertical irregularity (soft first storey)

---

## 📊 Results Summary

### A) Baseline — NBC-1980 (Between Pre-Code & Post-Benchmark)

| Building | Peak Displacement D (in) | Sd,c (in) | P[Complete Damage] | P[Collapse] |
|---|---|---|---|---|
| Case 1 — MRF (C1) | 1.856 | 11.20 | 0.827% | **0.108%** |
| Case 2 — Shear Wall (C2) | 1.358 | 17.60 | 0.032% | **0.004%** |

### B) Pre-Code — 1915

| Building | Peak Displacement D (in) | Sd,c (in) | P[Complete Damage] | P[Collapse] |
|---|---|---|---|---|
| Case 1 — MRF (C1) | 1.856 | 11.20 | 0.827% | **0.108%** |
| Case 2 — Shear Wall (C2) | 1.358 | 16.00 | 0.050% | **0.007%** |

> Pre-code MRF risk is essentially unchanged from baseline; shear wall risk increases due to lower seismic design coefficient (Cs = 0.029 vs. 0.043) and reduced overstrength (λ = 1.5 vs. 2).

### C) Post-Benchmark — 2010

| Building | Peak Displacement D (in) | Sd,c (in) | P[Complete Damage] | P[Collapse] |
|---|---|---|---|---|
| Case 1 — MRF (C1) | 1.800 | 26.56 | 0.017% | **0.002%** |
| Case 2 — Shear Wall (C2) | 1.300 | 26.56 | 0.003% | **0.0004%** |

> Post-benchmark buildings show dramatically reduced collapse risk (~50–100× lower than baseline) due to higher Cs = 0.107, increased ductility (m = 5.08), and higher drift capacity (Δc = 0.083).

### D) Severe Vertical Irregularity (Soft First Storey: 5.5 m + 5 × 3.5 m)

| Building | Peak Displacement D (in) | Sd,c (in) | P[Complete Damage] | P[Collapse] |
|---|---|---|---|---|
| Case 1 — MRF (C1) | 1.856 | 3.629 | 18.57% | **9.28%** |
| Case 2 — Shear Wall (C2) | 1.358 | 5.832 | 2.60% | **1.30%** |

> Severe vertical irregularity causes collapse probability to spike 85× (MRF) and 325× (shear wall) compared to regular buildings, driven by reduced modal shape factor (α3 = 4), lower drift capacity (Δc = 0.028/0.045), and elevated collapse factor (0.5).

---

## ⚙️ FEMA P-155 Capacity Curve Parameters

### Case 1 — Moment Resisting Frame (C1) — Baseline

| Parameter | Value |
|---|---|
| Elastic Period Te | 0.89 s |
| Seismic Design Coefficient Cs | 0.043 |
| Yield Strength Factor γ | 1.8 |
| Overstrength Factor λ | 2.0 |
| Ductility Factor m | 3.82 |
| Yield Point (Ay, Dy) | 0.106g, 0.823 in |
| Ultimate Point (Au, Du) | 0.212g, 6.288 in |
| Storey Drift Ratio Δc | 0.035 |
| Collapse Factor | 0.13 |

### Case 2 — Shear Wall (C2) — Baseline

| Parameter | Value |
|---|---|
| Elastic Period Te | 0.65 s |
| Seismic Design Coefficient Cs | 0.043 |
| Yield Strength Factor γ | 1.8 |
| Overstrength Factor λ | 2.0 |
| Ductility Factor m | 3.82 |
| Yield Point (Ay, Dy) | 0.098g, 0.406 in |
| Ultimate Point (Au, Du) | 0.196g, 3.099 in |
| Storey Drift Ratio Δc | 0.055 |
| Collapse Factor | 0.13 |

---

## 📈 Key Findings

| Scenario | MRF P[Collapse] | Shear Wall P[Collapse] | Key Observation |
|---|---|---|---|
| NBC-1980 (Baseline) | 0.108% | 0.004% | Shear walls 27× safer than MRF |
| Pre-Code (1915) | 0.108% | 0.007% | MRF unchanged; shear wall slightly worse |
| Post-Benchmark (2010) | 0.002% | 0.0004% | Modern codes reduce risk ~50–100× |
| Vertical Irregularity | 9.28% | 1.30% | Soft storey causes 85–325× increase in risk |

---

## 🛠️ Methods & Standards

- **Methodology:** FEMA P-155 (Rapid Visual Screening & Seismic Assessment)
- **Capacity Curve:** Elliptical transition, Equations 4-2 through 4-5
- **Fragility Function:** Lognormal CDF, FEMA P-155 Equation 4-10
- **Seismic Hazard:** NBCC 2020 Seismic Hazard Tool — Ottawa, ON
- **Building Classification:** FEMA P-155 Table 3-3 (C1, C2)
- **Seismicity Classification:** FEMA P-155 Table 5-1 (Moderately High)
- **Tools:** Microsoft Excel

---

## 📁 Files

| File | Description |
|---|---|
| `Seismic_ass_2.xlsx` | Full Excel solution — all four scenarios, capacity curves, fragility calculations |
| `Seismic_Ass_2.pdf` | Full written assignment submission |
| `CVG6320_Assignment_2_Winter2025_Q.pdf` | Original assignment question |

---

*University of Ottawa – Faculty of Engineering, Department of Civil Engineering*
*Course: CVG 6320 – Seismic Risk Assessment & Management of Existing Buildings*
*Instructor: Reza Fathi-Fazl, Ph.D., P.Eng. | Due: February 15, 2025*
