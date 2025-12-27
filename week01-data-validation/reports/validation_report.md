# ML Data Validation & Leakage Prevention (Week 1)

## Overview
This project focuses on validating data before training machine learning models.
It demonstrates how to prevent data leakage and enforce data quality checks
using a used car price prediction dataset.

The goal is to apply QE-style validation practices to ML pipelines.

---

## Why This Project Matters
In real-world ML systems:
- Data leakage leads to inflated offline metrics
- Schema drift silently breaks models
- Outliers cause unstable predictions

Validating data before training is critical to building reliable ML systems.

---

## What This Project Covers

### Data Leakage Prevention
- Train/test split enforcement
- Preprocessing leakage avoidance
- Target leakage awareness
- Temporal and group leakage concepts

### Data Validation
- Schema validation (columns and data types)
- Missing value checks
- Value range validation
- Outlier detection using:
  - IQR (Interquartile Range)
  - Z-score

---


