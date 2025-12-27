# ML Data Validation & Leakage Prevention

## Overview
This project demonstrates how to validate data before training machine learning models
using a used car price dataset.

The focus is on preventing data leakage and enforcing data quality checks
before model training.

---

## Why This Matters
In real-world ML systems:
- Data leakage inflates offline metrics
- Schema drift silently breaks models
- Outliers destabilize predictions

Validating data early is critical for building reliable ML pipelines.

---

## What This Project Covers
- Train/test leakage prevention
- Preprocessing and target leakage awareness
- Schema validation
- Missing value checks
- Outlier detection (IQR & Z-score)
- QE-style assertions applied to ML pipelines

---

## Repository Structure
week01-data-validation/
├── RAW_DATA/
│ └── carprices.csv
├── notebooks/
│ ├── 05_data_leakage.ipynb
│ └── 06_schema_outliers.ipynb
├── reports/
│ └── validation_report.md
└── README.md

## How to Run
1. Open the notebooks in VS Code or Jupyter
2. Run notebooks top to bottom:
   - `05_data_leakage.ipynb`
   - `06_schema_outliers.ipynb`

---

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn