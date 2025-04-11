# Body Composition and Anthropometric Analysis of Minority Schools in Istanbul

## Project Overview
This project investigates health status differences among students from three ethnic Greek minority schools in Istanbul, Turkey: Zappeio Lyceum, Zographeio Lyceum, and Megali Scholi (Phanar Greek Orthodox Lyceum). Using anthropometric and body composition data collected in 2015, we applied statistical modeling to evaluate how school affiliation relates to key health metrics.

## Research Question
What are the key health status differences between students at the three minority schools, based on anthropometric and body composition measurements?

## Methods
We used:
- **Linear Mixed-Effects Models** to identify school-level differences while accounting for random effects from age and gender.
- **Principal Component Analysis (PCA)** to explore patterns and reduce dimensionality.
- **Descriptive statistics** and **correlation matrices** for preliminary insights and variable dependencies.

## 📈 Key Findings
- **Anthropometric Differences:** Arm length and waist measurements varied significantly by school.
- **Body Composition Differences:** Zographeio students showed significantly higher fat percentage and mass compared to Megali Scholi.
- **PCA Results:** Limited school-based clustering due to multicollinearity, but some separation consistent with lower fat mass in Megali Scholi.
- **Limitations:** Correlated variables, limited generalizability, and assumptions of normality.

## 🔧 Tools & Languages
- **R** (for modeling, PCA, and visualization)
- **Excel** (for table formatting and reporting)

## 📂 Contents
- `data_prep.Rmd` – Scripts for cleaning and preparing the datasets  
- `analysis.Rmd` – R scripts for modeling and visualizations  
- `consulting_memo.pdf` – Final memo summarizing research, methodology, and findings  
- `final_presentation.pptx` – Slide deck highlighting key results and visuals for stakeholder communicatione

## 👥 Authors
Ben Laufer, Lamitr Dhir, Roee Morag, Jacob Perez
