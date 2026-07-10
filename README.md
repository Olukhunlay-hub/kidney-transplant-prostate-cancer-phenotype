# Kidney Transplant Prostate Cancer Phenotype

This repository contains analysis code and outputs for the manuscript:

**Clinical characteristics and associated factors of de novo and recurrent prostate cancer after kidney transplantation**

## Overview

This study evaluates clinical, transplant, immunologic, and immunosuppression factors associated with recurrent versus de novo prostate cancer phenotype among kidney transplant recipients who developed post-transplant prostate cancer.

The analysis includes:

- data preprocessing and cohort construction
- baseline cohort characterization
- primary Firth penalized logistic regression
- sensitivity analyses
- exploratory machine learning analyses
- generation of manuscript tables and figures

## Repository contents

```text
kidney-transplant-prostate-cancer-phenotype/
│
├── prostate-cancer-kidney-transplant-analysis.ipynb
├── tables/
├── figures/
├── outputs/
└── README.md
```

## Data Availability
The data used in this study are third-party OPTN/UNOS registry data and cannot be publicly shared due to legal and contractual restrictions.

Researchers may request access directly from the Organ Procurement and Transplantation Network (OPTN)/United Network for Organ Sharing (UNOS).

This repository contains code only and does not include patient-level data.

## Software

The analyses were performed primarily in Python (version 3.12). Firth penalized logistic regression was implemented in R using the `logistf` package through the `rpy2` interface.

The computational environment and required Python packages are provided in the `requirements.txt` file.

## Reproducibility

Researchers with approved access to the relevant OPTN/UNOS data can use the notebook in this repository to reproduce the prostate cancer analytic cohort, preprocessing steps, statistical analyses, machine learning analyses, tables, and figures.

## Citation
If you use or adapt this code, please cite the associated manuscript once published.
