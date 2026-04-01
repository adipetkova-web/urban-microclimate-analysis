# Urban Microclimate Analysis

[View full report (HTML)](HumVe_Analysis.html)

## Overview
This project analyzes urban climate data collected using TU Berlin’s portable climate station (HuMVe).  
The goal is to understand how surface temperature and urban structure influence air temperature and solar radiation.

## Key Questions
- How strongly does surface temperature affect air temperature?
- Do different urban locations receive different levels of solar radiation?
- What role does urban structure (e.g. vegetation, street width) play?

## Methods
- Data cleaning and preprocessing in R
- Exploratory data analysis (EDA)
- Linear regression modeling
- Normality testing (Shapiro-Wilk)
- Non-parametric testing (Wilcoxon test)

## Key Findings
- Surface temperature is a strong predictor of air temperature (R² ≈ 0.86)
- Solar radiation differs significantly between locations
- Urban structure likely influences microclimate conditions

## Tools Used
- R
- dplyr
- ggplot2
- Custom function for reading the HumVe data, both provided by the TU Berlin

## Project Structure
- `analysis.R` → main analysis script
- `data/` → dataset (if included)
- `plots/` → visualizations

## Author
Adelina Petkova
