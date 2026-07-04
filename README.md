# PCA & Clustering — Dimensionality Reduction and Profile Segmentation

Unsupervised-learning project that applies **Principal Component Analysis (PCA)**
and **clustering** to segment a dataset into distinct profiles, then visualises
the results in an interactive **Power BI** dashboard to support data-driven
decisions.

## Overview

The project reduces the dimensionality of the data with PCA, groups observations
into clusters, and characterises each resulting profile. The final segments are
exported for interactive exploration in Power BI.

## Repository structure

```
.
├── mine.ipynb                       # Main notebook: PCA, scaling, clustering and visualisation
├── datos.csv                        # Original dataset
├── datos_final.xlsx                 # Clean/transformed dataset after PCA + clustering
├── pca_clusters.xlsx                # Generated clusters
├── caracteristicas_cluster.json     # Qualitative description of each detected profile
├── cluster_perfiles_powerbi.xlsx    # Table ready for Power BI
├── PCA_PowerBI.pbix                 # Interactive Power BI report
└── README.md
```

## Tech stack

Python (scikit-learn, pandas, matplotlib, seaborn) · Power BI · JSON / Excel

## Usage

1. Open `mine.ipynb` to reproduce the PCA, clustering and profiling.
2. Open `PCA_PowerBI.pbix` in Power BI Desktop to explore the segments
   interactively.

```bash
jupyter lab            # open mine.ipynb
```

## Goal

Identify groups or profiles within a set of observations using unsupervised
techniques, and make them easy to interpret through interactive visualisation.

---

> **Note:** notebook comments are written in Spanish.
