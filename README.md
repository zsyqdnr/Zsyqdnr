[English](README.md) | [中文](README.zh.md)

---

**`README.md`（英文版框架）**

```markdown
# Qiao Ou (That Man)

**Independent Researcher | Developer of the Anchoring Framework**

> Using one unified framework to identify system response patterns to perturbations — from galaxy rotation curves to mountain watershed hydrology.

📫 **Contact**: 505808957@qq.com
🆔 **ORCID**: [0009-0008-4540-1381](https://orcid.org/0009-0008-4540-1381)
💻 **GitHub**: https://github.com/Zsyqdnr

---

## Three Preprints

| Paper | Field | DOI |
|---|---|---|
| **Anchoring Framework: A Zero-Dark-Matter Explanation for Galaxy Rotation Curves** | Galactic Physics | [10.5281/zenodo.22714393](https://doi.org/10.5281/zenodo.22714393) |
| **Two-Layer Anchoring: Stellar Disks Obey Newton, Gas Disks Deviate** | Galactic Physics | [10.5281/zenodo.22771462](https://doi.org/10.5281/zenodo.22771462) |
| **Snow-Dependence Modulates Warming-Induced Seasonal Extremization in Mountain Watersheds** | Hydrological Climate | [10.5281/zenodo.22736287](https://doi.org/10.5281/zenodo.22736287) |

All three papers use the **same Anchoring Framework**, applied at different scales.

---

## Framework Overview

The core idea of the Anchoring Framework: any wave packet — from galaxies to watersheds, from the cosmos to the microscopic — resonates with its environment. The environmental structure determines the coherence of the wave packet: whether it can resist perturbations and maintain its own structure.

Three core quantities:

| Symbol | Meaning | Application |
|---|---|---|
| **S** (Survival Factor) | Coherence time ÷ Perturbation period | The wave packet's ability to resist perturbation |
| **G_anchor** (Anchoring Stiffness) | Background frequency ÷ Wave density × S | The constraint strength of the environment |
| **R** (Resonance Overlap) | Overlap area of environmental and local spectra | Whether the wave packet matches its environment |

The framework expresses itself at different scales:

- **Cosmic scale**: Galaxy rotation curves are determined by anchoring stiffness, without dark matter
- **Hydrological scale**: Seasonal runoff structure in watersheds is determined by the stability of the snow anchor
- **Microscopic scale**: Coherence and transition behavior in any time series can be characterized by S and G_anchor

---

## Key Cases

### Case 1: Galaxy Rotation Curves — Single-Layer Anchoring (Cosmic Scale)

Fitting 98 SPARC galaxies with the Anchoring Framework yields a median residual of 9.14 km/s, **without dark matter**. The α parameter (density sensitivity of the survival factor) correlates significantly with the galaxy's gas fraction (r² = 0.439).

### Case 2: Galaxy Rotation Curves — Two-Layer Anchoring and Mass-Scale Coupling (Cosmic Scale)

Analysis of 159 SPARC galaxies reveals:

- **Stellar disks obey pure Newtonian gravity** (k_star = 0.005 ± 0.005 /kpc, consistent with zero)
- **Gas disks deviate from Newtonian gravity** (k_gas = 0.244 ± 0.022 /kpc, characteristic length 4.1 kpc)
- **Gas-layer anchoring is driven by two independent quantities**: gas mass fraction w_gas and HI disk radius R_HI
- **Double-variable model**: k = 0.127·w_gas + 0.530/R_HI, 5-fold CV R² = 0.62
- **Independent validation with THINGS survey**: 14 overlapping galaxies, massive galaxies show consistent k (difference < 0.03)

This provides a dark-matter-free explanation of flat rotation curves, distinguishable from MOND because MOND does not differentiate between mass types or distribution scales.

### Case 3: Altai West Sub-basin (Hydrological Scale, High Sensitivity)

- Location: 86.0–87.5°E, 47.0–48.2°N
- SRF (Spring Runoff Fraction): 0.384
- SEI trend: -0.0092/yr (58-year cumulative: -37.6%)
- Snow depth trend: -0.058 cm/yr
- Conclusion: Triple consistent signal, rapidly shifting toward a rain anchor

### Case 4: Hutubi River (Hydrological Scale, Low Sensitivity)

- Location: 86.05–87.08°E, 43.07–45.20°N
- SRF: 0.377
- SEI trend: -0.0019/yr (58-year cumulative: -6.5%)
- Snow depth trend: +0.009 cm/yr (essentially stable)
- Conclusion: Weak signal, glacier buffering may be at play

> **Key comparison**: Two watersheds have nearly identical SRF (0.384 vs 0.377), yet exhibit drastically different system sensitivities. Traditional water source analysis cannot distinguish them. This framework can.

---

## Service Products

### Product A: Hydrological Diagnostic Report

**Suitable for**: Water resource planning institutes, consulting firms, prefecture-level water departments (internal pre-research, preliminary assessment)

**Deliverables**:
- Watershed anchor type diagnosis
- SEI trend over the past 30–60 years
- Winter snow depth trend over the past 30–40 years
- Snowmelt peak date trend
- Plain-language conclusions + actionable recommendations

**Price**: 500–2000 CNY / watershed
**Delivery**: 3–5 business days

### Product B: Drought Risk Prediction Report

**Suitable for**: Insurance companies, green finance institutions, ESG assessment, research projects

**Deliverables**: Everything in Product A, plus:
- 5–10 year SEI trend projection
- Multi-emission scenario comparison (RCP4.5 / RCP8.5)
- Confidence intervals and RMSE prediction errors
- Standardized risk rating
- Full methodology appendix and references

**Price**: 2000–20000 CNY / project
**Delivery**: 7–20 business days

### Batch Screening Service

**Suitable for**: Consulting firms and planning institutes needing rapid priority ranking of dozens of watersheds

**Deliverables**: Batch screening table (watershed name, anchor type, SRF, SEI trend, sensitivity level) + diagnostic reports for key watersheds

**Price**: Negotiable based on watershed count

### Cross-Scale Analysis Service

**Suitable for**: Any time series data requiring coherence analysis, trend detection, or state transition identification

- Galaxy rotation curve fitting
- General time series trend analysis
- State transition early warning
- Scientific data visualization

**Price**: Negotiable based on project complexity

---

## Tech Stack

- **Data Sources**: SPARC galaxy database, THINGS survey, CNRD v1.0, China Long-Term Snow Depth Dataset, NASA POWER, USGS NWIS
- **Computing Environment**: Python (h5py, numpy, matplotlib, scipy, sklearn)
- **Analysis Framework**: Anchoring Framework (S, G_anchor, R)

---

## Collaboration

I provide **data analysis and report writing services**. I do not provide legally valid hydrological survey and water resource assessment results.

**Suitable scenarios**:
- Consulting firm subcontracting: batch watershed sensitivity screening
- Planning institute pre-research: preliminary regional water security assessment
- Research collaboration: cross-scale response pattern analysis
- Data science: general time series analysis

**Not suitable for**:
- Engineering project approval
- Water resource argumentation
- Final actuarial pricing for insurance

All deliverables include a full disclaimer clarifying usage boundaries.

---

## Citation

```bibtex
@article{ou2024anchoring,
  title={Anchoring Framework: A Zero-Dark-Matter Explanation for Galaxy Rotation Curves},
  author={Ou, Qiao},
  journal={Zenodo},
  year={2024},
  doi={10.5281/zenodo.22714393}
}

@article{ou2026twolayer,
  title={Two-Layer Anchoring: Stellar Disks Obey Newton, Gas Disks Deviate},
  author={Ou, Qiao},
  journal={Zenodo},
  year={2026},
  doi={10.5281/zenodo.22771462}
}

@article{ou2024snow,
  title={Snow-Dependence Modulates Warming-Induced Seasonal Extremization in Mountain Watersheds},
  author={Ou, Qiao},
  journal={Zenodo},
  year={2024},
  doi={10.5281/zenodo.22736287}
}
