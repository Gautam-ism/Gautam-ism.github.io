---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

My research centers on **Geospatial AI and Earth observation for geohazards and Earth-surface/environmental processes**. Across projects, I work with InSAR time series, multi-source satellite data, spatial statistics, and machine learning, with an emphasis on methods that remain physically and geographically meaningful.

---

## Sikkim Landslide Research Program

*Sikkim Himalaya · 2024 - present*

This work has developed as a connected progression from static susceptibility mapping to spatially rigorous machine learning and dynamic deformation monitoring.

### 1. Knowledge-driven susceptibility modelling
A GIS-MCDM framework integrated **14 geo-environmental conditioning factors** after multicollinearity assessment and used the Analytic Hierarchy Process (AHP) to delineate landslide susceptibility across Sikkim. Sensitivity analysis identified slope as the most influential factor, and the model achieved **AUC = 0.844**.

### 2. Deterministic, statistical, and hybrid model comparison
A subsequent study compared **AHP, Frequency Ratio, AHP-FR, and Logistic Regression** using an inventory of **211 landslides**. The hybrid AHP-FR model achieved the strongest overall predictive performance (**success AUC = 0.85; prediction AUC = 0.81**), with sensitivity of **0.79** and strong spatial reliability.

**Output:** Peer-reviewed article in *Earth Surface Processes and Landforms* (2026). [See Publications →](/publications/)

### 3. Ensemble learning with spatial validation
The next stage benchmarked **Logistic Regression, Random Forest, Weighted Subspace Random Forest (WSRF), and XGBoost** using **677 landslides** and **five-fold spatial cross-validation**. XGBoost achieved the highest discriminative capability (**AUC = 0.895; sensitivity = 0.955**), while WSRF provided better zonation efficiency, capturing **84.5% of landslides within 28.2% of the study area**. Partial-dependence analysis identified a pronounced instability transition around **25°-30° slope**.

### 4. Multi-Temporal InSAR Deformation Monitoring · Gangtok
A full-year Sentinel-1A deformation study extends susceptibility mapping from *where failure is likely* to *how active slopes are moving through time*.

**Data and processing.** **31 ascending** and **24 descending** SLC acquisitions from January-December 2025 were processed with the ISCE2 `topsStack` framework and MintPy. A four-connection nearest-neighbour network generated **114 ascending + 86 descending interferometric pairs**. The final time series contained approximately **6.3 million ascending** and **3.7 million descending** coherent pixels.

**Deformation results.** LOS velocities range from **-15.8 to +41.8 cm/yr** in ascending geometry and **-19.9 to +10.2 cm/yr** in descending geometry. Joint inversion decomposed the observations into an east-west component (**-41.2 to +18.3 cm/yr**) and a vertical component (**-22.3 to +25.7 cm/yr**). Time-series analysis captures distinct acceleration during the **June-September monsoon**, consistent with seasonal destabilization of active slopes.

**Research contribution:** all software implementation, InSAR processing, coding, and computational analysis for this study.

**Output:** Manuscript ready for submission. Code is currently private during manuscript preparation.

---

## GCT-TabDDPM / Synthetic Data for Landslide Inventories

*Research in progress · Apr 2026 - present*

Current work investigates whether synthetic-data augmentation can improve landslide modelling **without breaking the geographic relationship between locations and environmental covariates**. The project began with GCT-TabDDPM and now includes a broader methodological audit of tabular and geo-conditional generative approaches.

The central concern is that apparently realistic synthetic samples may still be geographically invalid or may inflate downstream performance through spatial leakage. The research therefore emphasizes **constraint validity, raster-consistent covariates, leakage-safe spatial evaluation, and downstream utility**, rather than treating synthetic-data generation as an end in itself.

**Research contribution:** independently developed research design, implementation, evaluation framework, and code. Quantitative results are still being finalized, so preliminary performance claims are intentionally not reported here.

**Output:** Manuscript in preparation. Code will be released after the research workflow is finalized.

---

## Mining-Environment Monitoring and Restoration Prioritization

*Jharia Coalfield, India · Jan 2025 - Apr 2026 · M.Tech Thesis*

I developed a decadal restoration-prioritization framework for the **~370 km² Jharia Coalfield**, a landscape affected by long-term mining and persistent coal-seam fires.

**Data fusion.** Six degradation indicators were derived from a ten-year archive of **Sentinel-1/2, Landsat-8/9, and VIIRS** observations and summarized using Theil-Sen trend estimation with Mann-Kendall significance testing.

**Novel indices in the mining context.**
- **Vol-NDVI** - a SAR-optical fusion index designed to improve characterization of vegetation condition.
- **Surface Alteration Surface (SAS)** - a mining-surface alteration indicator developed using PCA.

**Integration and validation.** The six indicators were weighted using **Fuzzy AHP**. The resulting Restoration Priority Index was evaluated using four complementary checks:
- **Moran's I = 0.8831**
- **ROC-AUC = 0.8355**
- **Monte Carlo CV = 2.56%**
- **77.48%** capture of independently mapped coal-fire areas

The final product is a **10 m restoration-priority map** designed to identify both where intervention is most urgent and the degradation factors contributing to that priority.

**Research contribution:** I carried out the full research workflow, including research design, data acquisition and processing, index development, weighting, coding, validation, interpretation, and manuscript preparation, under the supervision of **Prof. Dheeraj Kumar**.

**Output:** First-author manuscript under review at *Science of Remote Sensing*. Code repository will be made public after the publication process permits release.

---

## Hyperspectral Mineral Mapping

*Bailadila Iron Ore Mine · Summer 2025 · Independent research*

A self-directed EO-1 Hyperion workflow exploring spaceborne hyperspectral methods for mineral mapping. Processing in ENVI included **FLAASH atmospheric correction, PCA/MNF dimensionality reduction, and Spectral Angle Mapper classification** to characterize hematite, pyrite, and quartz-associated signatures.

This project broadened my methodological experience from environmental and hazard mapping toward **spectral characterization for resource exploration**.

---

## Additional Collaborative Research

### Groundwater Potential Zonation · Purulia, West Bengal
Benchmarked AHP, Frequency Ratio, Logistic Regression, and Random Forest against **66 verified well observations** in hard-rock aquifers of the Chota Nagpur Plateau. Data-driven models (**AUC = 0.75**) outperformed expert weighting (**AUC = 0.66**). Manuscript under review.

### Integrated Coastal Flood Risk Assessment · Sagar Island
Co-authored a framework combining remotely sensed exposure indicators with census-based socioeconomic vulnerability to identify priority intervention zones in the Indian Sundarbans. Book chapter in press with Springer.

---

## Methodological Interests

**InSAR & deformation:** Sentinel-1, ISCE2, MintPy, PSInSAR, SBAS, multi-geometry decomposition  
**GeoAI & machine learning:** XGBoost, random forests, spatial cross-validation, PyTorch, generative models  
**Earth observation:** optical, SAR, thermal, nighttime-light, and hyperspectral sensing  
**Spatial analysis:** Fuzzy AHP, Moran's I, Getis-Ord Gi*, Theil-Sen, Mann-Kendall, Monte Carlo sensitivity analysis
