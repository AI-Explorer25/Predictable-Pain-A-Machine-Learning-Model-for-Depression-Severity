# Multi-Class Depression Classification

## Overview

This project investigates the relative predictive contribution of structural, demographic, and behavioral/psychological features in multi-class depression classification using a controlled Random Forest modeling framework.

## Research Objective

To isolate and compare the predictive signal of different feature categories while keeping the modeling architecture constant.

## Methodology

- Random Forest classifier
- Pipeline with preprocessing (encoding + scaling)
- SMOTETomek for class imbalance (within cross-validation)
- 5-fold stratified cross-validation
- Weighted F1 score as evaluation metric

## Feature Groups Compared

1. Structural features
2. Demographic features
3. Behavioral & Psychological features (leakage-controlled reduced set)

## Key Findings

- Behavioral features retained the strongest predictive signal (Weighted F1 ≈ 0.693)
- Structural features showed moderate predictive power (≈ 0.352)
- Demographic features contributed minimally in isolation (≈ 0.03)
- Initial 100% accuracy revealed leakage and high feature-target correlation

## Repository Structure

- `notebook.ipynb` — full analysis and modeling workflow
- `data/` — dataset 
- `README.md`
- `.gitignore`

## Notes

This project emphasises careful leakage testing, controlled modeling comparisons, and interpretative caution in predictive mental health modeling.
