# Comparative Climate Trends Across Moist Highland, Moist Lowland, and Arid Lowland Zones of Eritrea using CHIRPS Satellite Product (1992–2024)

## Overview

This repository contains the datasets, scripts, notebooks, and outputs developed for a comprehensive assessment of long-term rainfall variability across the major agroecological zones of Eritrea using the **Climate Hazards Group InfraRed Precipitation with Station Data (CHIRPS)** satellite precipitation product.

The study investigates and compares historical climate trends across the **Moist Highland**, **Moist Lowland**, and **Arid Lowland** ecological zones from **1992 to 2024**. The project integrates geospatial analysis, climate statistics, and satellite-derived rainfall observations to evaluate spatial and temporal rainfall variability, identify climate trends, and support climate adaptation and environmental decision-making.

---

## Research Objectives

- Assess long-term rainfall trends across Eritrea (1992–2024).
- Compare precipitation characteristics among the Moist Highland, Moist Lowland, and Arid Lowland zones.
- Evaluate spatial and temporal rainfall variability using CHIRPS satellite observations.
- Generate climate trend maps and statistical summaries for each agroecological zone.
- Develop a reproducible geospatial workflow using Python and Google Colab.

---

## Study Area

The study focuses on three major agroecological zones of Eritrea:

- Moist Highland
- Moist Lowland
- Arid Lowland

These ecological regions represent contrasting climatic environments that are important for understanding regional climate variability and rainfall dynamics.

---

## Data

### Primary Dataset

- **Dataset:** CHIRPS Version 2.0
- **Variable:** Daily Rainfall
- **Spatial Resolution:** 0.05°
- **Temporal Coverage:** 1992–2024
- **Study Area:** Eritrea

### Additional Spatial Data

- Agroecological Zone Boundaries
- Administrative Boundaries
- Derived Spatial Products

---

## Repository Structure

```text
ERITREA_PROJECT_2/
│
├── DATA/
│   ├── RAW_STACKEDS/
│   ├── Arid_Lowland/
│   ├── Moist_Highland/
│   ├── Moist_Lowland/
│   ├── Arid_Highland/
│   ├── spatial_trends_arid_lowland_ExportFeatures/
│   ├── spatial_trends_moist_lowland_ExportFeatures/
│   ├── spatial_trends_moist_highland_ExportFeatures/
│   └── Processed/
│
├── notebooks/
├── scripts/
├── figures/
├── outputs/
├── docs/
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Methodology

The project follows the workflow below:

1. Data acquisition
2. Data preprocessing
3. Rainfall stacking
4. Temporal aggregation
5. Spatial clipping by agroecological zones
6. Statistical trend analysis
7. Spatial trend mapping
8. Comparative climate assessment
9. Visualization and reporting

---

## Software and Libraries

The analysis is implemented using:

- Python 3
- Google Colab
- NumPy
- Pandas
- GeoPandas
- Rasterio
- Xarray
- Matplotlib
- SciPy
- Jupyter Notebook

---

## Outputs

This repository contains:

- Processed climate datasets
- Rainfall trend maps
- Spatial analysis outputs
- Time-series visualizations
- Comparative statistical summaries
- Publication-quality figures
- Tables and supporting documentation

---

## Reproducibility

All analyses are fully reproducible. The notebooks and Python scripts included in this repository provide a complete workflow from data preprocessing to final visualization and statistical analysis.

---

## Citation

If you use this repository in your research, please cite the associated publication (when available) or acknowledge this repository appropriately.

---

## License

This repository is distributed under the MIT License unless otherwise specified.

---

## Author

**Project:** Comparative Climate Trends Across Moist Highland, Moist Lowland, and Arid Lowland Zones of Eritrea using CHIRPS Satellite Product (1992–2024)

Developed using Python, Google Colab, and geospatial data analysis techniques for climate variability assessment.
