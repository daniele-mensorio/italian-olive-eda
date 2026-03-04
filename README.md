# 🫒 Italian Olive Oil — Exploratory Data Analysis & Visualisation

**Course:** Data Visualisation & Reporting  
**Institution:** Università degli Studi della Campania 'Luigi Vanvitelli'  
**Year:** 2nd year BSc · 2023–2024  
**Grade:** 30/30 cum laude  

---

## Overview

This project performs a full exploratory data analysis (EDA) and data visualisation on the classic **Italian Olive Oil dataset**, originally collected by Prof. J. Gasteiger and Prof. J. Zupan for the study of neural network classification methods in computational chemistry.

The dataset contains **572 observations** of Italian olive oils, each described by the percentage composition of **8 fatty acids** and classified by **region** (Southern Italy, Sardinia, Northern Italy) and **area** (9 sub-regions).

---

## Research Questions

- How is the dataset composed by region and area?
- What is the average fatty acid composition of Italian olive oils?
- How does fatty acid composition vary across regions and areas?
- Are there outliers or missing values in the data?

---

## Methods & Visualisations

- **Data cleaning & transformation** — factor encoding of categorical variables
- **Missing value analysis** — verified with `sapply()`
- **Outlier detection** — boxplots by region and area
- **Composition plots** — pie charts, treemaps (static + interactive D3), waffle charts
- **Regional comparison** — side-by-side pie charts for all 3 regions and 9 areas
- **Interactive visualisations** — `d3treeR` treemap for hierarchical exploration

---

## Stack

| Tool | Purpose |
|---|---|
| R | Main language |
| ggplot2 / tidyverse | Data manipulation and static plots |
| treemap / d3treeR | Hierarchical treemap visualisation |
| DT | Interactive data tables |
| summarytools | Data summary |
| patchwork / gridExtra | Multi-panel plot composition |
| R Markdown | Reproducible report |

---

## Repository Structure

```
italian-olive-eda/
├── olive_analysis.Rmd      # Main R Markdown report
├── olive_analysis.html     # Rendered HTML output
├── data/
│   └── olive.csv           # Dataset
└── README.md
```

---

## Dataset Reference

Forina, M. et al. (1983). *PARVUS: An extendable package for data exploration, classification and correlation.* Institute of Pharmaceutical and Food Analysis and Technologies, Genova, Italy.
