<p align="center">
  <img src="banner.svg" alt="Naman Kishan Rastogi: probabilistic flood forecasting, teleconnections, Bayesian hydrology" width="100%">
</p>

<p align="center">
  <a href="https://nkrastogi.com"><img src="https://img.shields.io/badge/Website-nkrastogi.com-0b3d5c?style=flat-square" alt="Website"></a>
  <img src="https://img.shields.io/badge/PhD-CU%20Boulder%20%7C%20CIRES-1f6f8b?style=flat-square" alt="CU Boulder">
  <img src="https://img.shields.io/badge/Focus-Brahmaputra%20River%20Basin-2a9d8f?style=flat-square" alt="Brahmaputra">
</p>

---

I am a PhD researcher in Civil, Environmental and Architectural Engineering at the **University of Colorado Boulder (CIRES)**, advised by Prof. Balaji Rajagopalan. I build **probabilistic flood forecasting and early warning systems** for data-scarce, flood-prone river basins, with the Brahmaputra as my main testbed.

My work sits where **statistics, probability and hydrology** meet: Bayesian hierarchical models, causal networks, satellite observations and hydraulic simulation, combined into forecasts that carry honest uncertainty all the way to the flood map.

**Dissertation:** *Bayesian Hierarchical and Causal Network Based Models for Riverine Flood Risk Warning and Assessment*

## 🌊 The forecasting chain I work on

```mermaid
flowchart LR
    A[Climate drivers<br/>ENSO, IOD, MJO] --> B[Precipitation<br/>forecasts]
    B --> C[Bayesian<br/>post-processing]
    C --> D[Bayesian hierarchical<br/>stage forecasts]
    E[SWOT satellite<br/>water levels] --> D
    D --> F[HEC-RAS 2D<br/>ensembles]
    F --> G[Probabilistic<br/>inundation maps]
    G --> H[Early warning]
```

## 🔬 Research

| Theme | What it does | Methods |
|---|---|---|
| **BRACE** | Reconstructs continuous daily river water surface elevation from sparse SWOT satellite overpasses | Bayesian hierarchical nonstationary models, Stan |
| **Causal drivers of streamflow** | Finds which climate modes drive monsoon streamflow in the Brahmaputra | Bayesian causal networks, do-calculus, Exploratory Graph Analysis |
| **Precipitation post-processing** | Corrects space-time precipitation forecasts in the Brahmaputra and Narmada basins | Bayesian hierarchical spatial models |
| **Probabilistic inundation mapping** | Turns stage forecast ensembles into flood depth and exceedance probability maps around Guwahati | HEC-RAS 2D ensembles, terra |
| **Real-time flood warning** | Operational Brahmaputra forecasts from gauge-linked precipitation to inundation | Automated data pipelines, land surface model forecasts |

## 📄 Selected publication

- **Rastogi, N. K.**, Nanditha, J. S., & Rajagopalan, B. (2026). Bayesian Causal Networks for streamflow variability in the Brahmaputra River Basin. *Earth's Future*. [doi:10.1029/2026EF008056](https://doi.org/10.1029/2026EF008056)

## 🛠️ Tools

<p>
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/Stan-B2001D?style=flat-square" alt="Stan">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/HEC--RAS-4a6fa5?style=flat-square" alt="HEC-RAS">
  <img src="https://img.shields.io/badge/RiverWare-5a7d9a?style=flat-square" alt="RiverWare">
  <img src="https://img.shields.io/badge/NetCDF%20%7C%20GeoTIFF-3a5a40?style=flat-square" alt="NetCDF GeoTIFF">
  <img src="https://img.shields.io/badge/SLURM%20HPC-333333?style=flat-square&logo=linux&logoColor=white" alt="SLURM">
</p>

## 🏅 Recognition

- 2026 CIRES Graduate Student Research Award
- Primary convener, AGU Fall Meeting 2026 Session H096
- President, CU Boulder AWRA Student Chapter and Water Buffs (2026 to 2027)

---

<p align="center"><i>Open to collaborations on flood forecasting, Bayesian hydrology and SWOT applications.</i></p>
