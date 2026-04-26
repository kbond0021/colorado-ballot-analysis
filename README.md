# Education, Ballot Language, and Voter Support Analysis

## Overview

This project examines how education levels relate to support for ballot initiatives when ballot wording changes. The analysis compares two Colorado constitutional amendments: Amendment T (2016) and Amendment A (2018), which addressed the same policy issue but used different language clarity.

Precinct-level election results were combined with demographic estimates from the American Community Survey to evaluate whether education levels help explain changes in voter support following revisions to ballot wording.

This project was completed as part of an academic research project and is part of ongoing research development.

---

## Research Question

How does education level influence support for ballot initiatives when ballot wording changes in clarity?

---

## Data Sources

Data were compiled from publicly available sources:

- Colorado Secretary of State election results (2016 and 2018)
- Precinct boundary shapefiles
- American Community Survey (ACS) demographic data
- Education-level estimates retrieved using the tidycensus package

Raw datasets are not included due to file size limitations.

---

## Methods

The analysis includes:

- Cleaning and preparing election results data  
- Importing and processing geographic shapefiles  
- Merging demographic data with precinct-level election results  
- Creating derived education variables  
- Visualizing geographic patterns using choropleth maps  
- Conducting regression analysis to model changes in voter support  
- Generating scatterplots and summary statistics  

---

## Tools and Libraries

This project was completed using R and Quarto.

Key packages used:

- dplyr — data cleaning and transformation  
- tidyverse — data manipulation  
- sf — spatial data processing  
- tidycensus — demographic data retrieval  
- ggplot2 — visualization  
- readr — data import  
- tidyr — data reshaping  

---

## File Structure

Main project file:

- `CodeCOProjectFall2025.qmd` — Primary analysis file containing code, figures, and modeling steps

---

## Example Analysis Components

The project includes:

- Choropleth maps showing geographic changes in support
- Scatterplots comparing education levels and vote outcomes
- Regression models estimating relationships between education and changes in support

---

## Status

This project is part of an ongoing research effort. Additional data processing and model refinement are currently underway as part of continued academic work.

---

## Author

Kayla Bond  
B.A. Political Science & Economics  
University of Florida  

Interested in data analysis, research support, and policy-related roles.
