---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
---

<p class="section-intro">
Below is the full CV. For a printable copy, use the button below.
</p>

<a href="{{ site.baseurl }}/files/Gaurav_Kumar_Gautam_CV.pdf" class="btn" download>📄 Download CV (PDF)</a>

---

## Research Profile

I am a Geomatics Engineering researcher specializing in multisource remote sensing, InSAR deformation monitoring, and machine learning for resource exploration, geohazard assessment, and mining-environment monitoring. My work integrates SAR (PSInSAR/SBAS time-series analysis), hyperspectral and optical imagery, thermal and nighttime-light data, spatial statistics, deep learning segmentation and restoration targeting, and generative diffusion models for data-scarce settings. I seek doctoral research that advances Earth-observation and AI methods for mineral and energy resource exploration and surface-deformation hazard monitoring, with a continuing interest in the socio-environmental and community-level dimensions of mining.

---

## Education

**M.Tech, Geomatic Engineering** *(Aug 2024 – May 2026)*
Indian Institute of Technology (ISM), Dhanbad — CGPA 8.48/10.00

*Thesis:* Multi-Temporal and Spatial Autocorrelation-Based Assessment of Mining-Induced Ecological Degradation Using a Restoration Priority Index: A Case Study of the Jharia Coalfield, India.
*Supervisor:* Prof. Dheeraj Kumar, Professor (HAG), Dept. of Mining Engineering.

Developed the first integrated decadal restoration prioritization framework for the Jharia Coalfield, fusing six degradation indicators across a ten-year satellite archive, and introducing two novel indices (Vol-NDVI and Surface Alteration Stress). The spatially validated Restoration Priority Index (Moran's I = 0.8831, ROC–AUC = 0.8355) identifies at 10-meter resolution where restoration is most urgent.

**B.Tech, Civil Engineering** *(Sep 2019 – Sep 2023)*
Bihar Engineering University, Patna — CGPA 7.99/10.00

*Final Year Project:* Modifying the GRIHA Rating System for Existing Buildings: A Case Study on Government Engineering College, Arwal — **Best Final Year Project, 2022–23**.

---

## Grants and Awards

- **Teaching Assistantship**, IIT (ISM) Dhanbad *(2024–2026)* — Competitive award through India's national postgraduate entrance exam.
- **Best Final Year Project Award**, Bihar Engineering University *(2022–23)*.
- **Chief Minister's Merit-cum-Support Scholarship for Higher Education**, Government of Bihar *(2019–2023)*.

---

## Research Experience and Projects

### Researcher — GCT-TabDDPM: Geo-Conditional Diffusion Model for Landslide Augmentation
*IIT (ISM) Dhanbad · Apr 2026 – Present*

Addressing chronic data scarcity in geohazard modeling. Development of a Geo-Conditional Transformer coupled with a Tabular Denoising Diffusion Probabilistic Model under ten domain-specific geomechanical constraints. Statistically faithful synthetic samples were generated to overcome class imbalance and spatial bias. Manuscript in preparation for the *International Journal of Disaster Risk Reduction*.

### Researcher — Multi-Temporal InSAR Landslide Monitoring, Gangtok, Sikkim
*Dept. of Mining Engineering, IIT (ISM) Dhanbad · Mar 2026 – present*

Multi-temporal InSAR characterization of ground-surface deformation across the Gangtok region. Full-year Sentinel-1A processing (55 scenes, ISCE2/MintPy pipeline, SBAS + PSInSAR, ~10 million coherent pixels). Joint inversion resolved 3D kinematics of active slow-moving landslides; monsoon acceleration of 3–5× confirmed. Manuscript ready for submission.

### Graduate Researcher (M.Tech Thesis) — Jharia Coalfield Restoration Prioritization
*Dept. of Mining Engineering, IIT (ISM) Dhanbad · Jan 2025 – Apr 2026 · Supervisor: Prof. Dheeraj Kumar*

First integrated decadal restoration prioritization framework for the Jharia Coalfield. Fused six degradation indicators from a ten-year archive (Sentinel-1/2, Landsat-8/9, VIIRS) via Theil–Sen slope estimation with Mann–Kendall significance. Introduced two new indices (Vol-NDVI, Surface Alteration Stress). Fuzzy AHP weighting with multicollinearity control; U-Net segmentation for restoration targeting. Validated on four independent dimensions (Moran's I = 0.8831; ROC–AUC = 0.8355; Monte Carlo CV = 2.56%; 77.48% coal-fire capture). Submitted to *Science of Remote Sensing* (Elsevier).

### Independent Researcher — Hyperspectral Mineral Mapping, Bailadila Iron Ore Mine
*Self-directed · Summer 2025*

Built an EO-1 Hyperion processing workflow in ENVI (FLAASH correction, PCA/MNF reduction, Spectral Angle Mapper) to map hematite, pyrite, and quartz-associated minerals.

### Graduate Researcher — Landslide Susceptibility Modeling, Sikkim Himalaya
*IIT (ISM) Dhanbad · Aug 2024 – Mar 2025*

Three-phase investigation of landslide susceptibility. Phase 1: GIS-based zonation using parameterized AHP (14 predictor layers, 672 landslide points). Phase 2: benchmarked AHP, Frequency Ratio, Logistic Regression, and hybrid models. Phase 3: XGBoost and Weighted Subspace Random Forest with 5-fold spatial cross-validation. XGBoost achieved AUC = 0.895; critical slope-instability transition identified between 25° and 30°.

### Data Science Intern — TEXMiN, IIT (ISM) Dhanbad
*Technology Innovation Hub for Excellence in Mining · Mar 2025 – Aug 2025*

Contributed to the predictive-monitoring program of TEXMiN, a national Mining Technology Innovation Hub, building Python machine-learning pipelines that extract environmental degradation metrics from high-resolution satellite imagery.

### Contributing Researcher — Groundwater Potential Zonation, Purulia, West Bengal
*Nov 2024 – Mar 2025*

Benchmarked AHP, Frequency Ratio, Logistic Regression, and Random Forest against 66 verified well observations across the hard-rock aquifers of the Chota Nagpur Plateau. Data-driven models (AUC = 0.75) outperformed expert weighting (AUC = 0.66).

### Contributing Researcher — Integrated Coastal Flood Risk Assessment, Sagar Island
*Springer book chapter (in press, 2025) · Sep 2024 – Feb 2025*

Co-authored a flood-risk framework for Sagar Island in the Indian Sundarbans, fusing remote-sensing exposure metrics with census-based socioeconomic vulnerability indicators.

### Civil Engineering Intern — Technoculture Building Center Pvt. Ltd
*Oct 2021 – Dec 2021*

Contributed to structural audits and green-building feasibility studies for residential developments.

---

## Publications

See the [full Publications page](/publications/) for grouped citations. Summary: one peer-reviewed journal article published; four manuscripts under review; one book chapter in press; two manuscripts in preparation.

---

## Research Skills

**Remote sensing & satellite data.** Multi-source acquisition and preprocessing across optical, SAR, thermal, and nighttime-light sensors (Landsat-8/9, Sentinel-1/2, EO-1 Hyperion, VIIRS); atmospheric correction; dimensionality reduction (PCA, MNF); spectral-angle classification; cloud-based processing in Google Earth Engine.
*Software:* ENVI, ERDAS Imagine, SNAP, Google Earth Engine.

**Geospatial modelling & GIS.** Spatial overlay, raster algebra, terrain modeling, hydrological analysis, cartographic production.
*Software:* ArcGIS, QGIS, CAMPAD.

**Programming & scientific computing.** Python geospatial and scientific stack (GeoPandas, GeoAI, Rasterio, Shapely, NumPy, SciPy, pandas, Matplotlib, OpenCV); JavaScript for Google Earth Engine workflows.

**Machine learning & deep learning.** Gradient-boosted ensembles (XGBoost), random forests, weighted subspace random forests, logistic regression, and generative diffusion models (Tabular DDPM with geo-conditional constraints).
*Frameworks:* PyTorch, TensorFlow, scikit-learn.

**Statistical & spatial methods.** Fuzzy AHP with VIF multicollinearity control; Theil–Sen slope estimation and Mann–Kendall testing; Moran's I and Getis–Ord Gi* autocorrelation; Monte Carlo sensitivity analysis; ROC–AUC and spatial cross-validation.

**Data management.** Spatial database management and querying (SQL, PostGIS); dashboards and reporting in Power BI; tabular analysis in Microsoft Excel.

**Languages.** English (full professional proficiency), Hindi (native).

---

## Interests and Activities

**Chess** — Intra-college (IIT (ISM) Dhanbad) General Championship winner; chess team captain; named best player at a Bihar Engineering University inter-college tournament. Member, Black Knight Chess Club.

**Sports leadership** — Sports General Secretary, Bihar Engineering University (2022–23); Coordinator, Badminton Club, IIT (ISM) Dhanbad. Active badminton and tennis player.

**Community engagement** — Volunteer teacher with [KARTAVYA](https://kartavya.org), a registered NGO providing educational outreach at IIT (ISM) Dhanbad. Teach Physics, Chemistry, and Mathematics to Grade 9–12 students from underprivileged backgrounds on weekends (2025–present).

**Trekking & fieldwork** — Completed Annapurna Base Camp and Mardi Himal Himalayan treks; field visits to active coal-mining areas and landslide-affected terrain in Sikkim.

---

## References

**Prof. Dheeraj Kumar** — M.Tech Thesis Supervisor
Professor (HAG), Dept. of Mining Engineering, IIT (ISM) Dhanbad
✉ dheeraj@iitism.ac.in · ☎ +91-326-223-5486

**Prof. Vasanta Govind Kumar Villuri** — Thesis Co-Supervisor
Associate Professor, Dept. of Mining Engineering, IIT (ISM) Dhanbad
✉ vgkvilluri@iitism.ac.in · ☎ +91-326-223-5069

**Prof. Radhakanta Koner** — Research Collaborator
Associate Professor, Dept. of Mining Engineering, IIT (ISM) Dhanbad
✉ rkoner@iitism.ac.in · ☎ +91-326-223-5739

**Mr. Anant Kumar** — B.Tech Project Supervisor
Assistant Professor, Dept. of Civil Engineering, Government Engineering College, Arwal, Bihar
✉ anant6295@gmail.com
