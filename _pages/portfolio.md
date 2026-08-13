---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: false
classes:
  - wide
  - research-v2-page
---

<section class="page-hero-v2">
  <p class="eyebrow-v2">RESEARCH</p>
  <h1>Geospatial AI and Earth observation for changing landscapes.</h1>
  <p>My work connects <strong>susceptibility modelling, spatially rigorous machine learning, multi-source remote sensing, and InSAR deformation monitoring</strong>. The recurring question is not only where environmental or geohazard risk is high, but whether our models remain geographically meaningful and correspond to physical change on the ground.</p>
</section>

<nav class="research-nav-v2" aria-label="Research areas">
  <a href="#sikkim-landslides"><span>01</span>Sikkim landslides</a>
  <a href="#gangtok-insar"><span>02</span>Gangtok InSAR</a>
  <a href="#geoai-synthetic-data"><span>03</span>GeoAI methods</a>
  <a href="#jharia-restoration"><span>04</span>Jharia restoration</a>
  <a href="#other-earth-observation"><span>05</span>Other EO research</a>
</nav>

<section class="research-program-v2" id="sikkim-landslides">
  <header class="research-program-v2__header">
    <div>
      <p class="eyebrow-v2">SIKKIM HIMALAYA · 2024 — PRESENT</p>
      <h2>Sikkim Landslide Research Program</h2>
    </div>
    <p>A connected progression from static susceptibility mapping to spatially validated ensemble learning, forming the modelling foundation for later deformation monitoring.</p>
  </header>

  <div class="research-timeline-v2">
    <div><span>01</span><strong>Knowledge-driven</strong><small>AHP · GIS-MCDM</small></div>
    <div><span>02</span><strong>Hybrid models</strong><small>AHP-FR · LR · FR</small></div>
    <div><span>03</span><strong>Ensemble ML</strong><small>XGBoost · WSRF · spatial CV</small></div>
    <div><span>04</span><strong>Dynamic monitoring</strong><small>PSInSAR · SBAS</small></div>
  </div>

  <div class="research-stage-v2">
    <div class="research-stage-v2__label"><span>Stage 1–2</span><h3>From AHP to hybrid susceptibility modelling</h3></div>
    <div class="research-stage-v2__content">
      <p>A GIS-MCDM framework integrated <strong>14 geo-environmental conditioning factors</strong> after multicollinearity assessment. The initial AHP model achieved <strong>AUC = 0.844</strong>, with slope identified as the most influential factor.</p>
      <p>A subsequent study compared <strong>AHP, Frequency Ratio, AHP-FR, and Logistic Regression</strong> using an inventory of <strong>211 landslides</strong>. The hybrid AHP-FR model achieved the strongest overall performance, with <strong>success AUC = 0.85</strong>, <strong>prediction AUC = 0.81</strong>, and sensitivity of <strong>0.79</strong>.</p>
    </div>
  </div>

  <div class="research-metrics" aria-label="Published landslide study metrics">
    <div><strong>211</strong><span>mapped landslides</span></div>
    <div><strong>14</strong><span>conditioning factors</span></div>
    <div><strong>0.85</strong><span>success AUC</span></div>
    <div><strong>0.81</strong><span>prediction AUC</span></div>
  </div>

  <figure class="research-figure research-figure--wide">
    <a class="research-figure__link" href="/images/research/sikkim-inventory-field.png" target="_blank" rel="noopener">
      <img src="/images/research/sikkim-inventory-field.png" alt="Sikkim landslide inventory map flanked by two field-observed landslides" loading="lazy" decoding="async">
    </a>
    <figcaption><strong>Landslide inventory and field assessment.</strong> Spatially mapped landslide occurrences were combined with imagery- and field-based verification for model development and validation. <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>

  <div class="output-strip-v2"><span class="status-pill-v2 status-pill-v2--published">Published</span><p>Peer-reviewed article in <em>Earth Surface Processes and Landforms</em> (2026).</p><a href="/publications/">Publication record →</a></div>

  <div class="research-stage-v2 research-stage-v2--accent">
    <div class="research-stage-v2__label"><span>Stage 3</span><h3>Ensemble learning with spatial validation</h3></div>
    <div class="research-stage-v2__content">
      <p>The latest modelling stage benchmarks <strong>Logistic Regression, Random Forest, Weighted Subspace Random Forest (WSRF), and XGBoost</strong> using <strong>677 landslides</strong> and <strong>five-fold spatial cross-validation</strong>.</p>
      <p>XGBoost provides the highest discrimination (<strong>AUC = 0.895; sensitivity = 0.955</strong>), while WSRF offers stronger zonation efficiency by concentrating <strong>84.5% of landslides within 28.2% of the study area</strong>. This explicitly separates predictive accuracy from operational spatial economy.</p>
    </div>
  </div>

  <div class="research-metrics" aria-label="Ensemble landslide modelling metrics">
    <div><strong>677</strong><span>landslides</span></div>
    <div><strong>0.895</strong><span>XGBoost AUC</span></div>
    <div><strong>0.955</strong><span>XGBoost sensitivity</span></div>
    <div><strong>3.00</strong><span>WSRF frequency ratio</span></div>
  </div>

  <div class="research-pair" aria-label="XGBoost and WSRF landslide susceptibility maps">
    <figure class="research-figure research-figure--panel">
      <a class="research-figure__link" href="/images/research/sikkim-xgboost.jpg" target="_blank" rel="noopener"><img src="/images/research/sikkim-xgboost.jpg" alt="XGBoost landslide susceptibility zonation map for Sikkim" loading="lazy"></a>
      <figcaption><strong>XGBoost.</strong> Strongest predictive discrimination. <span class="figure-hint">Full resolution ↗</span></figcaption>
    </figure>
    <figure class="research-figure research-figure--panel">
      <a class="research-figure__link" href="/images/research/sikkim-wsrf.jpg" target="_blank" rel="noopener"><img src="/images/research/sikkim-wsrf.jpg" alt="WSRF landslide susceptibility zonation map for Sikkim" loading="lazy"></a>
      <figcaption><strong>WSRF.</strong> Greater spatial economy in the Very High class. <span class="figure-hint">Full resolution ↗</span></figcaption>
    </figure>
  </div>

  <figure class="research-figure research-figure--wide">
    <a class="research-figure__link" href="/images/research/sikkim-zonation-comparison.png" target="_blank" rel="noopener"><img src="/images/research/sikkim-zonation-comparison.png" alt="Quantitative comparison of landslide susceptibility model zonation efficiency" loading="lazy"></a>
    <figcaption><strong>Model zonation efficiency.</strong> Landscape area, landslide concentration, and frequency ratio reveal why operational usefulness cannot be judged from AUC alone. <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>
</section>

<section class="research-program-v2" id="gangtok-insar">
  <header class="research-program-v2__header">
    <div><p class="eyebrow-v2">GANGTOK · SENTINEL-1 · 2025</p><h2>Multi-Temporal InSAR Deformation Monitoring</h2></div>
    <p>This project moves the Sikkim research program from <em>where failure is likely</em> to <em>how active slopes are actually moving through time</em>.</p>
  </header>

  <div class="method-strip-v2"><span>ISCE2 topsStack</span><span>MintPy</span><span>PSInSAR</span><span>SBAS</span><span>Ascending + descending</span></div>

  <div class="research-stage-v2">
    <div class="research-stage-v2__label"><span>Data & processing</span><h3>Multi-geometry Sentinel-1 time series</h3></div>
    <div class="research-stage-v2__content">
      <p><strong>31 ascending</strong> and <strong>24 descending</strong> Sentinel-1A SLC acquisitions spanning January–December 2025 were processed using ISCE2 and MintPy. A four-connection nearest-neighbour network generated <strong>114 ascending + 86 descending interferometric pairs</strong>.</p>
      <p>The final analyses contained approximately <strong>6.3 million ascending</strong> and <strong>3.7 million descending</strong> coherent pixels. Joint inversion of the two LOS geometries produced horizontal and vertical displacement components, while the time series captured clear acceleration during the June–September monsoon period.</p>
    </div>
  </div>

  <div class="research-metrics">
    <div><strong>55</strong><span>Sentinel-1 scenes</span></div>
    <div><strong>200</strong><span>interferometric pairs</span></div>
    <div><strong>~10M</strong><span>coherent pixels</span></div>
    <div><strong>2</strong><span>motion components</span></div>
  </div>

  <h3 class="figure-group-title-v2">Decomposed surface motion</h3>
  <div class="research-pair research-pair--portrait">
    <figure class="research-figure research-figure--panel"><a class="research-figure__link" href="/images/research/gangtok-vertical.png" target="_blank" rel="noopener"><img src="/images/research/gangtok-vertical.png" alt="Vertical PSInSAR displacement velocity map for Gangtok" loading="lazy"></a><figcaption><strong>Vertical displacement velocity.</strong> <span class="figure-hint">Full resolution ↗</span></figcaption></figure>
    <figure class="research-figure research-figure--panel"><a class="research-figure__link" href="/images/research/gangtok-horizontal.png" target="_blank" rel="noopener"><img src="/images/research/gangtok-horizontal.png" alt="Horizontal PSInSAR displacement velocity map for Gangtok" loading="lazy"></a><figcaption><strong>Horizontal displacement velocity.</strong> <span class="figure-hint">Full resolution ↗</span></figcaption></figure>
  </div>

  <h3 class="figure-group-title-v2">Multi-geometry LOS observations</h3>
  <div class="research-pair research-pair--portrait">
    <figure class="research-figure research-figure--panel"><a class="research-figure__link" href="/images/research/gangtok-asc-los.png" target="_blank" rel="noopener"><img src="/images/research/gangtok-asc-los.png" alt="Ascending LOS PSInSAR velocity map for Gangtok" loading="lazy"></a><figcaption><strong>Ascending LOS velocity.</strong> <span class="figure-hint">Full resolution ↗</span></figcaption></figure>
    <figure class="research-figure research-figure--panel"><a class="research-figure__link" href="/images/research/gangtok-dsc-los.png" target="_blank" rel="noopener"><img src="/images/research/gangtok-dsc-los.png" alt="Descending LOS PSInSAR velocity map for Gangtok" loading="lazy"></a><figcaption><strong>Descending LOS velocity.</strong> <span class="figure-hint">Full resolution ↗</span></figcaption></figure>
  </div>

  <div class="contribution-box-v2"><strong>My contribution</strong><p>All software implementation, InSAR processing, coding, and computational analysis for this study.</p><span>Manuscript ready for submission · Code private during manuscript preparation</span></div>
</section>

<section class="research-program-v2 research-program-v2--concept" id="geoai-synthetic-data">
  <header class="research-program-v2__header">
    <div><p class="eyebrow-v2">GEOAI · RESEARCH IN PROGRESS</p><h2>GCT-TabDDPM / Synthetic Data for Landslide Inventories</h2></div>
    <p>A methodological project asking when synthetic augmentation genuinely improves spatial modelling and when apparent gains are artefacts of invalid geography or leakage.</p>
  </header>

  <div class="concept-grid-v2">
    <div><span>01</span><h3>Geographic consistency</h3><p>Environmental covariates should remain consistent with the geographic locations represented by synthetic samples.</p></div>
    <div><span>02</span><h3>Leakage-safe evaluation</h3><p>Spatial dependence can make conventional random validation look far stronger than true geographic transfer.</p></div>
    <div><span>03</span><h3>Downstream utility</h3><p>The central test is not whether samples look realistic, but whether augmentation provides valid and reproducible modelling benefit.</p></div>
  </div>

  <p>Current work began with GCT-TabDDPM and now includes a broader audit of tabular and geo-conditional generative approaches. Quantitative results are intentionally withheld while the methodology and evaluation framework are being finalized.</p>
  <div class="contribution-box-v2"><strong>My contribution</strong><p>Independently developed research design, implementation, evaluation framework, and code.</p><span>First-author manuscript in preparation</span></div>
</section>

<section class="research-program-v2" id="jharia-restoration">
  <header class="research-program-v2__header">
    <div><p class="eyebrow-v2">JHARIA COALFIELD · M.TECH THESIS · 2025–2026</p><h2>Mining-Environment Monitoring & Restoration Prioritization</h2></div>
    <p>A decadal Earth-observation framework designed to identify where ecological restoration is most urgent across a mining landscape affected by long-term extraction and persistent coal-seam fires.</p>
  </header>

  <div class="research-stage-v2">
    <div class="research-stage-v2__label"><span>Multi-source EO</span><h3>From degradation signals to intervention priority</h3></div>
    <div class="research-stage-v2__content">
      <p>Six degradation indicators were derived from a ten-year archive of <strong>Sentinel-1/2, Landsat-8/9, and VIIRS</strong> observations and summarized using Theil-Sen trend estimation with Mann-Kendall significance testing.</p>
      <p>The work introduced two indices in the mining context: <strong>Vol-NDVI</strong>, a SAR–optical fusion index for vegetation condition, and <strong>Surface Alteration Surface (SAS)</strong>, developed using PCA. Indicators were integrated through <strong>Fuzzy AHP</strong>.</p>
    </div>
  </div>

  <div class="research-metrics">
    <div><strong>~370 km²</strong><span>study area</span></div>
    <div><strong>10 years</strong><span>EO archive</span></div>
    <div><strong>0.8831</strong><span>Moran's I</span></div>
    <div><strong>0.8355</strong><span>ROC-AUC</span></div>
  </div>

  <figure class="research-figure research-figure--wide">
    <a class="research-figure__link" href="/images/research/jharia-rpi.png" target="_blank" rel="noopener"><img src="/images/research/jharia-rpi.png" alt="Restoration Priority Index map for the Jharia Coalfield" loading="lazy"></a>
    <figcaption><strong>Restoration Priority Index.</strong> The final 10 m product classifies the landscape into low, moderate, high, and critical restoration-priority zones. <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>

  <div class="validation-grid-v2">
    <div><strong>0.8831</strong><span>Spatial autocorrelation · Moran's I</span></div>
    <div><strong>0.8355</strong><span>Predictive validation · ROC-AUC</span></div>
    <div><strong>2.56%</strong><span>Monte Carlo coefficient of variation</span></div>
    <div><strong>77.48%</strong><span>Capture of mapped coal-fire areas</span></div>
  </div>

  <figure class="research-figure research-figure--wide">
    <a class="research-figure__link" href="/images/research/jharia-workflow.png" target="_blank" rel="noopener"><img src="/images/research/jharia-workflow.png" alt="Seven-phase workflow for Jharia restoration-priority modelling" loading="lazy"></a>
    <figcaption><strong>Methodological framework.</strong> Multi-temporal preprocessing, parameter derivation, harmonization, Fuzzy AHP weighting, RPI modelling, priority zonation, and spatial/statistical validation. <span class="figure-hint">Open full resolution ↗</span></figcaption>
  </figure>

  <div class="contribution-box-v2"><strong>My contribution</strong><p>Full research workflow: research design, data acquisition and processing, index development, weighting, coding, validation, interpretation, and manuscript preparation, under the supervision of Prof. Dheeraj Kumar.</p><span>First-author manuscript under review · Science of Remote Sensing</span></div>
</section>

<section class="research-program-v2" id="other-earth-observation">
  <header class="research-program-v2__header"><div><p class="eyebrow-v2">ADDITIONAL RESEARCH</p><h2>Other Earth-observation & collaborative work</h2></div><p>Supporting projects that broaden my experience across hyperspectral sensing, groundwater assessment, and coastal risk.</p></header>

  <div class="supporting-project-grid-v2">
    <article class="supporting-project-v2">
      <div class="supporting-project-v2__image supporting-project-v2__image--portrait"><a href="/images/research/hyperspectral-mineral-map.png" target="_blank" rel="noopener"><img src="/images/research/hyperspectral-mineral-map.png" alt="Hyperion hyperspectral mineral classification map" loading="lazy"></a></div>
      <div><span class="project-type-v2">INDEPENDENT RESEARCH · 2025</span><h3>Hyperspectral Mineral Mapping · Bailadila</h3><p>EO-1 Hyperion processing using FLAASH atmospheric correction, PCA/MNF dimensionality reduction, and Spectral Angle Mapper classification for hematite, pyrite, and quartz-associated signatures.</p></div>
    </article>

    <article class="supporting-project-v2">
      <div class="supporting-project-v2__image"><a href="/images/research/groundwater-lr.png" target="_blank" rel="noopener"><img src="/images/research/groundwater-lr.png" alt="Groundwater potential zonation map for Purulia" loading="lazy"></a></div>
      <div><span class="project-type-v2">COLLABORATIVE · UNDER REVIEW</span><h3>Groundwater Potential Zonation · Purulia</h3><p>AHP, Frequency Ratio, Logistic Regression, and Random Forest benchmarked against <strong>66 verified wells</strong>. Data-driven models (AUC ≈ 0.75) outperformed the expert-weighted AHP baseline (AUC ≈ 0.67).</p><a class="text-link-v2" href="/images/research/groundwater-roc.png" target="_blank">View model ROC comparison ↗</a></div>
    </article>

    <article class="supporting-project-v2 supporting-project-v2--wide">
      <div class="supporting-project-v2__image"><a href="/images/research/sagar-flood-risk.jpg" target="_blank" rel="noopener"><img src="/images/research/sagar-flood-risk.jpg" alt="Flood hazard, vulnerability, and risk maps for Sagar Island" loading="lazy"></a></div>
      <div><span class="project-type-v2">COLLABORATIVE · BOOK CHAPTER IN PRESS</span><h3>Integrated Coastal Flood Risk · Sagar Island</h3><p>Physical flood hazard and census-based socioeconomic vulnerability integrated through a multi-criteria GIS framework to identify priority intervention zones in the Indian Sundarbans.</p></div>
    </article>
  </div>
</section>

<section class="methods-band-v2">
  <p class="eyebrow-v2">METHODS & TOOLS</p>
  <div><strong>InSAR</strong><span>Sentinel-1 · ISCE2 · MintPy · PSInSAR · SBAS</span></div>
  <div><strong>GeoAI</strong><span>XGBoost · Random Forest · PyTorch · generative models · spatial CV</span></div>
  <div><strong>Earth observation</strong><span>Optical · SAR · thermal · nighttime light · hyperspectral</span></div>
  <div><strong>Spatial analysis</strong><span>Fuzzy AHP · Moran's I · Getis-Ord Gi* · Theil-Sen · Mann-Kendall</span></div>
</section>
