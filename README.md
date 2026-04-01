# Urban Microclimate Analysis  

[View full report](https://adipetkova-web.github.io/urban-microclimate-analysis/HumVe_Analysis.html)

## Project Context  
Urban environments create highly variable microclimates due to differences in surface materials, shading, and spatial structure. These small-scale variations play a key role in urban heat dynamics and climate adaptation.

This project analyzes high-resolution climate data collected using TU Berlin’s portable **HuMVe station**, with the aim of understanding how local urban conditions influence temperature and radiation patterns.

## Research Focus  

- How strongly is **air temperature influenced by surface temperature**?  
- Do **solar radiation levels differ significantly between urban locations**?  
- What role does **urban structure (e.g. vegetation, street width)** play?  

## Analytical Approach  

The workflow reflects common challenges in environmental data analysis, such as non-normal distributions and real-world measurement variability:

- **Data preprocessing**  
  - Cleaning and structuring HuMVe data  
  - Handling missing and inconsistent values  

- **Exploratory data analysis**  
  - Visualizing distributions and site differences  
  - Identifying patterns and outliers  

- **Statistical analysis**  
  - Linear regression to quantify the relationship between surface and air temperature  
  - Shapiro-Wilk test to assess normality  
  - Wilcoxon test applied where parametric assumptions were not met  

## Key Results  

- **Strong surface–air temperature relationship**  
  Surface temperature explains a large share of air temperature variation  
  → R² ≈ 0.86  

- **Significant spatial variation in solar radiation**  
  Differences between locations are statistically significant  

- **Urban structure influences microclimate conditions**  
  The results highlight limitations in interpreting urban microclimate drivers. Despite the presence of trees, one site exhibited higher radiation levels, suggesting that   additional factors (e.g. street geometry or sky-view factor) likely influence the observed patterns. Further data would be required for a definitive explanation.

## Tools & Technologies  

- R  
- dplyr  
- ggplot2  
- Custom HuMVe data import functions (TU Berlin)  

## Repository Structure  
├── analysis.Rmd # Reproducible analysis
├── analysis.html # Rendered report
├── data/ # Dataset

##  Author  

Adelina Petkova 
