#  Accessibility of Public Libraries in Washington – Spatial Data Analysis

This project investigates the spatial accessibility of public libraries in the state of Washington, USA. Accessibility to libraries is a fundamental aspect of equitable public service delivery. This analysis aims to understand the spatial distribution of libraries in relation to population centers and identify regions that are either underserved or overserved. The project includes spatial data preprocessing, accessibility score calculation, visualization, and spatial autocorrelation analysis using Moran’...

---

##  Background

Public library accessibility directly affects library usage. A disproportionate distribution of library infrastructure can create inequality in access to knowledge, especially across different geographic and socio-economic regions. 

Over the past decade, the number of libraries in Washington has increased, yet their placement has not always aligned with population needs. Some areas benefit from close proximity to libraries, while others lack easy access. By visualizing and quantifying accessibility using spatial regression and statistical methods, this project highlights existing disparities and suggests areas for potential improvement.

---

## 🎯 Objectives

- To map and visualize the current distribution of public libraries in Washington.
- To calculate and analyze accessibility scores for each census tract.
- To apply spatial statistical techniques (e.g., Moran’s I) to detect clustering of low or high accessibility.
- To identify geographic regions with underserved populations in terms of library access.

---

## 🗂️ Files in This Project

- `data_clean.ipynb`: The Jupyter Notebook containing all the preprocessing, analysis, and visualization code.
- `README.md`: This file.
- `Project Dataset/`: Folder (to be created by the user) where raw and processed spatial data files (e.g., shapefiles, CSVs) should be stored.

---

## ⚙️ How to Run the Code

## 📦 Required Libraries

To run this project, install the following Python libraries:

```bash
pip install geopandas pandas numpy matplotlib shapely seaborn pysal splot
```
## 📈 Analysis Summary

The notebook performs the following operations:

- Imports and cleans spatial and population data.  
- Merges geospatial and demographic information by tract.  
- Calculates accessibility scores based on proximity and population.  
- Applies log transformation for normalization.  
- Generates visual maps showing library locations and accessibility.  
- Conducts spatial autocorrelation analysis using Moran’s I to identify clustering.  
- Identifies potential underserved communities.

---
👤 Author  
Muhammad Tanveer Hassan Cheema  
Department of Computer Science  
bscs22144@itu.edu.pk

