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

<div class="research-metrics" aria-label="Published landslide study metrics">
  <div><strong>211</strong><span>mapped landslides</span></div>
  <div><strong>14</strong><span>conditioning factors</span></div>
  <div><strong>0.85</strong><span>success AUC</span></div>
  <div><strong>0.81</strong><span>prediction AUC</span></div>
</div>

<figure class="research-figure research-figure--wide">
  <a class="research-figure__link" href="/images/research/sikkim-inventory-field.png" target="_blank" rel="noopener">
    <img src="/images/research/sikkim-inventory-field.png" alt="Sikkim landslide inventory map flanked by two field-observed landslides" width="2068" height="1477" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Landslide inventory and field assessment in Sikkim.</strong> Spatially mapped landslide occurrences were combined with imagery- and field-based verification to develop and validate susceptibility models across the Himalayan terrain. <span class="figure-hint">Open full resolution ↗</span></figcaption>
</figure>

**Output:** Peer-reviewed article in *Earth Surface Processes and Landforms* (2026). [See Publications →](/publications/)

### 3. Ensemble learning with spatial validation
The next stage benchmarked **Logistic Regression, Random Forest, Weighted Subspace Random Forest (WSRF), and XGBoost** using **677 landslides** and **five-fold spatial cross-validation**. XGBoost achieved the highest discriminative capability (**AUC = 0.895; sensitivity = 0.955**), while WSRF provided better zonation efficiency, capturing **84.5% of landslides within 28.2% of the study area**. Partial-dependence analysis identified a pronounced instability transition around **25°-30° slope**.

<div class="research-metrics" aria-label="Ensemble landslide modelling metrics">
  <div><strong>677</strong><span>landslides</span></div>
  <div><strong>0.895</strong><span>XGBoost AUC</span></div>
  <div><strong>0.955</strong><span>XGBoost sensitivity</span></div>
  <div><strong>3.00</strong><span>WSRF frequency ratio</span></div>
</div>

<div class="research-pair" aria-label="XGBoost and WSRF landslide susceptibility maps">
  <figure class="research-figure research-figure--panel">
    <a class="research-figure__link" href="/images/research/sikkim-xgboost.jpg" target="_blank" rel="noopener">
      <img src="/images/research/sikkim-xgboost.jpg" alt="XGBoost landslide susceptibility zonation map for Sikkim" width="1039" height="779" loading="lazy" decoding="async">
    </a>
    <figcaption><strong>XGBoost susceptibility zonation.</strong> Highest overall predictive discrimination. <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>
  <figure class="research-figure research-figure--panel">
    <a class="research-figure__link" href="/images/research/sikkim-wsrf.jpg" target="_blank" rel="noopener">
      <img src="/images/research/sikkim-wsrf.jpg" alt="WSRF landslide susceptibility zonation map for Sikkim" width="1039" height="779" loading="lazy" decoding="async">
    </a>
    <figcaption><strong>WSRF susceptibility zonation.</strong> Better spatial economy in the Very High class. <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>
</div>
<p class="research-pair-caption"><strong>Contrasting susceptibility zonation.</strong> XGBoost provides the strongest predictive discrimination, whereas WSRF concentrates observed failures within a smaller very-high-susceptibility footprint.</p>

<figure class="research-figure research-figure--wide">
  <a class="research-figure__link" href="/images/research/sikkim-zonation-comparison.png" target="_blank" rel="noopener">
    <img src="/images/research/sikkim-zonation-comparison.png" alt="Quantitative comparison of area, landslide concentration, and frequency ratio across XGBoost, WSRF, Random Forest, and Logistic Regression susceptibility classes" width="1189" height="948" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Model zonation efficiency.</strong> Comparing landscape area, observed-landslide concentration, and frequency ratio shows why operational usefulness cannot be judged from AUC alone. <span class="figure-hint">Open full resolution ↗</span></figcaption>
</figure>

### 4. Multi-Temporal InSAR Deformation Monitoring · Gangtok
A full-year Sentinel-1A deformation study extends susceptibility mapping from *where failure is likely* to *how active slopes are moving through time*.

**Data and processing.** **31 ascending** and **24 descending** SLC acquisitions from January-December 2025 were processed with the ISCE2 `topsStack` framework and MintPy. A four-connection nearest-neighbour network generated **114 ascending + 86 descending interferometric pairs**. The final time series contained approximately **6.3 million ascending** and **3.7 million descending** coherent pixels.

**Deformation results.** Mean LOS velocity fields from the ascending and descending geometries were jointly inverted into horizontal and vertical displacement components. The final PSInSAR maps below show the spatial structure of these velocity fields, while the time-series analysis captures distinct acceleration during the **June-September monsoon**, consistent with seasonal destabilization of active slopes.

<div class="research-metrics" aria-label="Gangtok InSAR study metrics">
  <div><strong>55</strong><span>Sentinel-1 scenes</span></div>
  <div><strong>200</strong><span>interferometric pairs</span></div>
  <div><strong>~10M</strong><span>coherent pixels</span></div>
  <div><strong>2</strong><span>resolved motion components</span></div>
</div>

<div class="research-pair research-pair--portrait" aria-label="Vertical and horizontal PSInSAR displacement maps">
  <figure class="research-figure research-figure--panel">
    <a class="research-figure__link" href="/images/research/gangtok-vertical.png" target="_blank" rel="noopener">
      <img src="/images/research/gangtok-vertical.png" alt="Vertical PSInSAR displacement velocity map for the Gangtok region" width="453" height="586" loading="lazy" decoding="async">
    </a>
    <figcaption><strong>Vertical displacement velocity.</strong> <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>
  <figure class="research-figure research-figure--panel">
    <a class="research-figure__link" href="/images/research/gangtok-horizontal.png" target="_blank" rel="noopener">
      <img src="/images/research/gangtok-horizontal.png" alt="Horizontal PSInSAR displacement velocity map for the Gangtok region" width="453" height="586" loading="lazy" decoding="async">
    </a>
    <figcaption><strong>Horizontal displacement velocity.</strong> <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>
</div>
<p class="research-pair-caption"><strong>Decomposed surface motion.</strong> Joint inversion of ascending and descending PSInSAR observations resolves horizontal and vertical displacement components across the Gangtok study area.</p>

<div class="research-pair research-pair--portrait" aria-label="Ascending and descending PSInSAR LOS velocity maps">
  <figure class="research-figure research-figure--panel">
    <a class="research-figure__link" href="/images/research/gangtok-asc-los.png" target="_blank" rel="noopener">
      <img src="/images/research/gangtok-asc-los.png" alt="Ascending line-of-sight PSInSAR velocity map for Gangtok" width="453" height="586" loading="lazy" decoding="async">
    </a>
    <figcaption><strong>Ascending LOS velocity.</strong> <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>
  <figure class="research-figure research-figure--panel">
    <a class="research-figure__link" href="/images/research/gangtok-dsc-los.png" target="_blank" rel="noopener">
      <img src="/images/research/gangtok-dsc-los.png" alt="Descending line-of-sight PSInSAR velocity map for Gangtok" width="453" height="586" loading="lazy" decoding="async">
    </a>
    <figcaption><strong>Descending LOS velocity.</strong> <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>
</div>
<p class="research-pair-caption"><strong>Multi-geometry LOS deformation.</strong> Ascending and descending Sentinel-1 observations provide complementary views of spatially variable ground motion before component decomposition.</p>

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

<div class="research-metrics" aria-label="Jharia restoration study metrics">
  <div><strong>~370 km²</strong><span>study area</span></div>
  <div><strong>10 years</strong><span>EO archive</span></div>
  <div><strong>0.8831</strong><span>Moran's I</span></div>
  <div><strong>0.8355</strong><span>ROC-AUC</span></div>
</div>

<figure class="research-figure research-figure--wide">
  <a class="research-figure__link" href="/images/research/jharia-rpi.png" target="_blank" rel="noopener">
    <img src="/images/research/jharia-rpi.png" alt="Restoration Priority Index map of the Jharia Coalfield with low, moderate, high, and critical priority zones" width="1379" height="1034" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Restoration Priority Index for the Jharia Coalfield.</strong> Multi-source Earth-observation indicators were integrated to classify the mining landscape into low, moderate, high, and critical restoration-priority zones. <span class="figure-hint">Open full resolution ↗</span></figcaption>
</figure>

**Integration and validation.** The six indicators were weighted using **Fuzzy AHP**. The resulting Restoration Priority Index was evaluated using four complementary checks:
- **Moran's I = 0.8831**
- **ROC-AUC = 0.8355**
- **Monte Carlo CV = 2.56%**
- **77.48%** capture of independently mapped coal-fire areas

<figure class="research-figure research-figure--wide">
  <a class="research-figure__link" href="/images/research/jharia-workflow.png" target="_blank" rel="noopener">
    <img src="/images/research/jharia-workflow.png" alt="Seven-phase methodological workflow for Jharia restoration-priority modelling from satellite preprocessing through decision framework" width="1379" height="931" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Methodological framework.</strong> The workflow integrates multi-temporal satellite preprocessing, parameter derivation, harmonization, Fuzzy AHP weighting, RPI modelling, priority zonation, and statistical/spatial validation. <span class="figure-hint">Open full resolution ↗</span></figcaption>
</figure>

The final product is a **10 m restoration-priority map** designed to identify both where intervention is most urgent and the degradation factors contributing to that priority.

**Research contribution:** I carried out the full research workflow, including research design, data acquisition and processing, index development, weighting, coding, validation, interpretation, and manuscript preparation, under the supervision of **Prof. Dheeraj Kumar**.

**Output:** First-author manuscript under review at *Science of Remote Sensing*. Code repository will be made public after the publication process permits release.

---

## Hyperspectral Mineral Mapping

*Bailadila Iron Ore Mine · Summer 2025 · Independent research*

A self-directed EO-1 Hyperion workflow exploring spaceborne hyperspectral methods for mineral mapping. Processing in ENVI included **FLAASH atmospheric correction, PCA/MNF dimensionality reduction, and Spectral Angle Mapper classification** to characterize hematite, pyrite, and quartz-associated signatures.

This project broadened my methodological experience from environmental and hazard mapping toward **spectral characterization for resource exploration**.

<figure class="research-figure research-figure--portrait">
  <a class="research-figure__link" href="/images/research/hyperspectral-mineral-map.png" target="_blank" rel="noopener">
    <img src="/images/research/hyperspectral-mineral-map.png" alt="Mineral classification map derived from EO-1 Hyperion hyperspectral imagery" width="543" height="765" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Hyperspectral mineral classification.</strong> Spectral Angle Mapper output showing mapped mineral signatures from the Hyperion scene. <span class="figure-hint">Open full resolution ↗</span></figcaption>
</figure>

---

## Additional Collaborative Research

### Groundwater Potential Zonation · Purulia, West Bengal
Benchmarked AHP, Frequency Ratio, Logistic Regression, and Random Forest against **66 verified well observations** in hard-rock aquifers of the Chota Nagpur Plateau. Data-driven models (**AUC ≈ 0.75**) outperformed expert weighting (**AUC ≈ 0.67**). Manuscript under review.

<div class="research-metrics research-metrics--compact" aria-label="Groundwater modelling metrics">
  <div><strong>66</strong><span>verified wells</span></div>
  <div><strong>4</strong><span>models compared</span></div>
  <div><strong>0.753</strong><span>best ROC-AUC</span></div>
</div>

<figure class="research-figure research-figure--wide">
  <a class="research-figure__link" href="/images/research/groundwater-roc.png" target="_blank" rel="noopener">
    <img src="/images/research/groundwater-roc.png" alt="ROC curves comparing AHP, Frequency Ratio, Logistic Regression, and Random Forest groundwater-potential models" width="1880" height="1586" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Predictive model comparison.</strong> Logistic Regression and Random Forest provide the strongest discrimination, outperforming the deterministic AHP baseline. <span class="figure-hint">Open full resolution ↗</span></figcaption>
</figure>

<figure class="research-figure research-figure--wide">
  <a class="research-figure__link" href="/images/research/groundwater-lr.png" target="_blank" rel="noopener">
    <img src="/images/research/groundwater-lr.png" alt="Logistic Regression groundwater potential zonation map for Purulia, West Bengal" width="2068" height="1551" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Groundwater potential zonation.</strong> Logistic Regression maps spatial variation in groundwater potential across the study area's hard-rock aquifer system. <span class="figure-hint">Open full resolution ↗</span></figcaption>
</figure>

### Integrated Coastal Flood Risk Assessment · Sagar Island
Co-authored a framework combining remotely sensed exposure indicators with census-based socioeconomic vulnerability to identify priority intervention zones in the Indian Sundarbans. Book chapter in press with Springer.

<figure class="research-figure research-figure--wide">
  <a class="research-figure__link" href="/images/research/sagar-flood-risk.jpg" target="_blank" rel="noopener">
    <img src="/images/research/sagar-flood-risk.jpg" alt="Three-panel Sagar Island maps showing flood hazard, flood vulnerability, and integrated flood risk" width="1379" height="839" loading="lazy" decoding="async">
  </a>
  <figcaption><strong>Integrated coastal flood-risk assessment.</strong> Physical flood hazard and socioeconomic vulnerability are combined through a multi-criteria GIS framework to reveal the spatial pattern of composite flood risk. <span class="figure-hint">Open full resolution ↗</span></figcaption>
</figure>

---

## Methodological Interests

**InSAR & deformation:** Sentinel-1, ISCE2, MintPy, PSInSAR, SBAS, multi-geometry decomposition  
**GeoAI & machine learning:** XGBoost, random forests, spatial cross-validation, PyTorch, generative models  
**Earth observation:** optical, SAR, thermal, nighttime-light, and hyperspectral sensing  
**Spatial analysis:** Fuzzy AHP, Moran's I, Getis-Ord Gi*, Theil-Sen, Mann-Kendall, Monte Carlo sensitivity analysis
