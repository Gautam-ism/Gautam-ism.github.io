---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

<p class="section-intro">
My research develops <strong>Earth-observation and AI methods</strong> to answer four interconnected questions: <em>Where will the ground fail? How is it moving now? Where should we heal it first? And what resources lie beneath?</em>
</p>

<div class="thread">
  <div class="thread-body">
    <span class="thread-tag">Thread 1 · GeoAI</span>
    <h3>Geospatial AI for Landslide Susceptibility</h3>
    <div class="thread-meta">Sikkim Himalaya · 2024 – present</div>
    <p>A three-phase investigation of landslide susceptibility in the tectonically active Sikkim Himalaya.</p>
    <p><strong>Phase 1</strong> developed GIS-based zonation using parameterized AHP with 14 predictor layers and 672 landslide points. <strong>Phase 2</strong> benchmarked AHP, Frequency Ratio, Logistic Regression, and hybrid models. <strong>Phase 3</strong> evaluated ensemble machine-learning algorithms (XGBoost and Weighted Subspace Random Forest) under 5-fold spatial cross-validation.</p>
    <p><strong>Result:</strong> XGBoost achieved the highest discrimination (<strong>AUC = 0.895</strong>). Partial dependence analysis identified a critical slope-instability transition between 25° and 30°, aligning with geomorphological friction theory.</p>
    <p><strong>Extension — GCT-TabDDPM.</strong> A Geo-Conditional Transformer coupled with a Tabular Denoising Diffusion Probabilistic Model, under ten domain-specific geomechanical constraints, to address chronic data scarcity in geohazard modeling. Manuscript in preparation for the <em>International Journal of Disaster Risk Reduction</em>.</p>
  </div>
  <div class="thread-figure">
    <img src="/images/research/01_landslide_susceptibility.png" alt="Landslide susceptibility map, Sikkim">
  </div>
</div>

<div class="thread reverse">
  <div class="thread-body">
    <span class="thread-tag">Thread 2 · InSAR</span>
    <h3>Multi-Temporal InSAR Deformation Monitoring</h3>
    <div class="thread-meta">Gangtok, Sikkim · Mar 2026 – present</div>
    <p>Multi-temporal InSAR characterization of ground-surface deformation across the Gangtok region, addressing the lack of pixel-scale monitoring in vegetated Himalayan urban centers.</p>
    <p><strong>Data &amp; pipeline.</strong> A full year of Sentinel-1A ascending and descending acquisitions (55 scenes) processed through the ISCE2/MintPy pipeline, applying both SBAS and Persistent Scatterer InSAR to generate 200 interferometric pairs and approximately <strong>10 million coherent pixels</strong>.</p>
    <p><strong>Method.</strong> Joint inversion decomposed line-of-sight displacement into horizontal and vertical components, resolving the 3D kinematics of active slow-moving landslides.</p>
    <p><strong>Result.</strong> Time-series analysis showed a <strong>three- to five-fold increase in speed during the June–September monsoon</strong>, providing quantitative evidence that pore-pressure increase from rainfall drives slope instability. Manuscript ready for submission.</p>
  </div>
  <div class="thread-figure">
    <img src="/images/research/02_insar_timeseries.png" alt="InSAR displacement time series, Gangtok">
  </div>
</div>

<div class="thread">
  <div class="thread-body">
    <span class="thread-tag">Thread 3 · M.Tech Thesis</span>
    <h3>Mining-Environment Monitoring &amp; Restoration Prioritization</h3>
    <div class="thread-meta">Jharia Coalfield, India · Jan 2025 – Apr 2026 · Supervisor: <a href="https://www.iitism.ac.in/">Prof. Dheeraj Kumar</a></div>
    <p>The first integrated decadal restoration prioritization framework for the Jharia Coalfield — a ~370 km² landscape affected by a century of mining and persistent underground coal-seam fires.</p>
    <p><strong>Data fusion.</strong> Six degradation indicators from a ten-year archive (Sentinel-1/2, Landsat-8/9, VIIRS), integrated via Theil–Sen slope estimation with Mann–Kendall significance.</p>
    <p><strong>Novel indices.</strong> <em>Vol-NDVI</em> — a SAR–optical fusion index distinguishing structural vegetation from ephemeral grasses. <em>Surface Alteration Stress</em> — quantifying anthropogenic mining pressure.</p>
    <p><strong>Method.</strong> Fuzzy AHP weighting with VIF multicollinearity control, followed by U-Net segmentation (GeoAI) to identify restoration target areas.</p>
    <p><strong>Validation.</strong> Moran's I = <strong>0.8831</strong> · ROC–AUC = <strong>0.8355</strong> · Monte Carlo CV = <strong>2.56%</strong> · <strong>77.48%</strong> capture of independently mapped coal-fire areas.</p>
    <p><strong>Impact.</strong> A 10-meter-resolution map for reclamation planners identifying where restoration is most urgent, and why. Manuscript submitted to <em>Science of Remote Sensing</em> (Elsevier); code and data openly archived on GitHub.</p>
  </div>
  <div class="thread-figure">
    <img src="/images/research/03_jharia_restoration.png" alt="Jharia restoration priority index">
  </div>
</div>

<div class="thread reverse">
  <div class="thread-body">
    <span class="thread-tag">Thread 4 · Spectroscopy</span>
    <h3>Hyperspectral Mineral Mapping</h3>
    <div class="thread-meta">Bailadila Iron Ore Mine · Summer 2025 · Independent research</div>
    <p>An EO-1 Hyperion processing workflow in ENVI (FLAASH atmospheric correction, PCA/MNF dimensionality reduction, Spectral Angle Mapper classification) to map hematite, pyrite, and quartz-associated minerals — extending methodological breadth in spaceborne spectroscopy toward resource exploration.</p>
  </div>
  <div class="thread-figure">
    <img src="/images/research/04_hyperspectral.png" alt="Hyperspectral mineral signatures, Bailadila">
  </div>
</div>

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
