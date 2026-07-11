---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

My research develops **Earth-observation and AI methods** to answer four interconnected questions: *Where will the ground fail? How is it moving now? Where should we heal it first? And what resources lie beneath?*

---

## 1. Geospatial AI for Landslide Susceptibility

*Sikkim Himalaya · 2024 – present*

A three-phase investigation of landslide susceptibility in the tectonically active Sikkim Himalaya.

**Phase 1** developed GIS-based zonation using parameterized AHP, integrating 14 predictor layers and 672 landslide points. **Phase 2** benchmarked AHP, Frequency Ratio, Logistic Regression, and hybrid models. **Phase 3** evaluated ensemble machine-learning algorithms (XGBoost and Weighted Subspace Random Forest) under 5-fold spatial cross-validation.

**Result:** XGBoost achieved the highest discrimination (AUC = 0.895). Partial dependence analysis identified a critical slope-instability transition between 25° and 30°, which aligns with geomorphological friction theory.

**Extension — GCT-TabDDPM** *(Apr 2026 – present).* A Geo-Conditional Transformer coupled with a Tabular Denoising Diffusion Probabilistic Model, developed under ten domain-specific geomechanical constraints, to address chronic data scarcity in geohazard modeling. The framework generates statistically faithful synthetic samples to overcome class imbalance and spatial bias. Manuscript in preparation for the *International Journal of Disaster Risk Reduction*.

*Outputs:* [Peer-reviewed paper (ESPL, 2026)](/publications/) · Manuscript under review · GCT-TabDDPM manuscript in preparation

---

## 2. Multi-Temporal InSAR Deformation Monitoring

*Gangtok, Sikkim · Mar 2026 – present*

A multi-temporal InSAR characterization of ground-surface deformation across the Gangtok region, addressing the lack of pixel-scale monitoring in vegetated Himalayan urban centers.

**Data & pipeline.** A full year of Sentinel-1A ascending and descending acquisitions (55 scenes) processed through the ISCE2/MintPy pipeline, applying both SBAS and Persistent Scatterer InSAR to generate 200 interferometric pairs and approximately 10 million coherent pixels.

**Method.** Joint inversion decomposed line-of-sight displacement into horizontal and vertical components, resolving the 3D kinematics of active slow-moving landslides.

**Result.** Time-series analysis showed a **three- to five-fold increase in speed during the June–September monsoon**, providing quantitative evidence that pore-pressure increase from rainfall drives slope instability.

*Outputs:* Manuscript ready for submission.

---

## 3. Mining-Environment Monitoring and Restoration Prioritization

*Jharia Coalfield, India · Jan 2025 – Apr 2026 · M.Tech Thesis*

The first integrated decadal restoration prioritization framework for the Jharia Coalfield — a ~370 km² landscape affected by a century of mining and persistent underground coal-seam fires.

**Data fusion.** Six degradation indicators from a ten-year satellite archive (Sentinel-1/2, Landsat-8/9, VIIRS), integrated via Theil–Sen slope estimation with Mann–Kendall significance.

**Novel indices.** Two new indices developed for this framework:
- *Vol-NDVI* — a SAR–optical fusion index distinguishing structural vegetation from ephemeral grasses.
- *Surface Alteration Stress* — quantifying anthropogenic mining pressure.

**Method.** Fuzzy AHP weighting with VIF multicollinearity control, followed by U-Net segmentation (GeoAI) to identify restoration target areas.

**Validation.** The resulting Restoration Priority Index was validated across four independent dimensions:
- Moran's I = **0.8831** (strong spatial coherence)
- ROC–AUC = **0.8355** (predictive discrimination)
- Monte Carlo CV = **2.56%** (sensitivity robustness)
- **77.48%** capture of independently mapped coal-fire areas

**Impact.** A 10-meter-resolution map for reclamation planners identifying where restoration is most urgent, and why.

*Outputs:* Manuscript submitted to *Science of Remote Sensing* (Elsevier) · Code and data openly archived on GitHub.

*Supervisor: [Prof. Dheeraj Kumar](https://www.iitism.ac.in/), Dept. of Mining Engineering, IIT (ISM) Dhanbad.*

---

## 4. Hyperspectral Mineral Mapping

*Bailadila Iron Ore Mine · Summer 2025 · Independent research*

An EO-1 Hyperion processing workflow in ENVI (FLAASH atmospheric correction, PCA/MNF dimensionality reduction, Spectral Angle Mapper classification) to map hematite, pyrite, and quartz-associated minerals — extending methodological breadth in spaceborne spectroscopy toward resource exploration.

---

## Additional Collaborative Work

**Groundwater Potential Zonation, Purulia, West Bengal** *(Nov 2024 – Mar 2025).* Benchmarked AHP, Frequency Ratio, Logistic Regression, and Random Forest against 66 verified well observations across the hard-rock aquifers of the Chota Nagpur Plateau. Data-driven models (AUC = 0.75) outperformed expert weighting (AUC = 0.66). Methodology relevant to India's National Aquifer Mapping Programme (NAQUIM).

**Integrated Coastal Flood Risk Assessment, Sagar Island** *(Sep 2024 – Feb 2025).* Co-authored a flood-risk framework for Sagar Island in the Indian Sundarbans, fusing remote-sensing exposure metrics with census-based socioeconomic vulnerability indicators to map priority intervention zones. Book chapter in press with Springer.

---

## Doctoral Research Interests

I am seeking a PhD position (Fall 2027) that advances Earth-observation and AI methods for:

- **Mineral and energy resource exploration** — extending my hyperspectral, InSAR, and multi-sensor fusion work to characterize subsurface targets and support responsible resource assessment.
- **Surface-deformation hazard monitoring** — scaling multi-temporal InSAR frameworks to regional and national coverage, coupling deformation signatures with physics-informed and generative models for early warning.
- **Socio-environmental dimensions of mining** — connecting geospatial hazard and degradation analytics to community-level vulnerability, restoration equity, and long-term reclamation planning.
