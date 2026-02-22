# Predictable Pain  
### A Machine Learning Investigation into Structural, Demographic, and Individual Determinants of Depression Classification  

## Overview

Depression is often understood through biological or psychological frameworks. This project approaches it as a measurable outcome influenced by structural conditions, demographic positioning, and individual behavioral patterns.

Using supervised machine learning, the analysis compares the relative predictive contribution of these feature categories in multi-class depression classification. The goal is analytical rather than normative: to estimate contribution, not assign responsibility.

---

## Research Question

> How much do structural factors (e.g., education, employment), demographic factors (e.g., age, gender), and individual behavioral and psychological variables influence the classification of depression subtypes?

---

## Dataset

The project uses **Mental Health Classification, Version 2 (2025)**:

- 1,998 survey responses  
- 21 encoded features  
- 12 depression subtype categories (`Depression_Type`)  
- No missing values  

The dataset supports controlled feature subset comparisons within a multi-class classification framework.

---

## Project Objectives

- Build a reproducible multi-class classification pipeline  
- Compare structural, demographic, and behavioral feature groups  
- Identify the strongest predictive variables  
- Detect and mitigate label leakage  
- Interpret results cautiously within an ethical and social context  

---

## Research Objective

To construct a controlled modeling framework that isolates and quantifies the relative predictive contribution of structural, demographic, and behavioral feature categories while keeping the machine learning architecture constant.


### Project Structure
```text
├── data/  
│   └── Mental Health Classification (raw).csv  # Raw dataset  
├── notebook/  
│   └── depression-ml.ipynb  # Main analysis notebook  
├── .gitignore  # Ignored files (e.g., checkpoints)  
├── README.md  # Project documentation

