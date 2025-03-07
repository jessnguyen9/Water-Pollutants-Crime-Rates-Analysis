# Exploring the Relationship Between Lead Service Lines and Crime Rates in the U.S.

## Overview
This project investigates whether the presence of lead service lines (LSLs) in water infrastructure is associated with crime rates in the United States. By conducting Exploratory Data Analysis (EDA), we examine potential correlations between water contamination and violent crime to determine if lead exposure may be a contributing factor to criminal behavior.

## Objective
- To explore the relationship between lead contamination in drinking water and crime rates at the city level.
- To determine whether there is a significant correlation (positive, negative, or neutral) between the presence of lead service lines and violent crime.
- To leverage data analytics and visualization techniques to present meaningful insights.

## Team members
- Robert Erick
- Peter Stine
- Jess Nguyen

## Data Sources
We collected data from a variety of reputable sources, including:
- **Environmental Protection Agency (EPA):** Data on lead contamination and water quality.
- **Federal Bureau of Investigation (FBI) Uniform Crime Reporting (UCR) Program:** Crime statistics across U.S. cities.
- **U.S. Census Bureau:** Demographic and population data for context.
- **Kaggle Datasets:** Additional crime rate data for cross-validation.
- **Geoapify API:** Geolocation data for mapping city-specific trends.

## Data Acquisition
Extracted data from multiple sources, including government databases, APIs, and Kaggle.

Used Python libraries such as requests to fetch real-time geolocation data.

Collected historical records on lead exposure and violent crime trends.

## Data Preparation & Cleaning
Removed missing and incomplete values to ensure dataset reliability.

Standardized data formats to merge datasets from different sources.

Created new features to analyze lead exposure per capita and crime per capita.

Handled outliers to ensure accurate statistical correlations.

## Data Analysis & Visualization
Performed correlation analysis to measure the relationship between lead exposure and crime rates.

Used scatter plots and histograms to visualize trends in crime vs. lead contamination.

Identified cities with the highest correlation between lead exposure and violent crime (e.g., Kansas City).

Calculated statistical values such as the Pearson correlation coefficient (r = 0.26), indicating a weak but positive correlation.

![violence v number lead discharges in missouri](https://github.com/user-attachments/assets/85b30bf6-ef95-41a0-ac2f-e9d41b0446f4)

![LSLs per 100k people v violent crime](https://github.com/user-attachments/assets/eee5ca2d-c5b1-4548-ae66-b5f6db2f2f59)


## Key Findings
- Overall, there is a weak but positive correlation (r = 0.26) between the number of lead discharges and violent crime per capita.
- Kansas City has the highest correlation between lead exposure and crime, suggesting localized effects.
- While lead exposure alone is not a definitive predictor of crime, there may be other socio-economic and environmental factors at play.

## Limitations
The analysis does not establish causation, only correlation.

Some datasets had missing information, which may affect the accuracy of results.

Other variables (e.g., poverty rates, education levels) were not accounted for in this study.

## Future Improvements
Incorporate machine learning models to predict crime rates based on environmental factors.

Expand the dataset to include additional socio-economic variables.

Conduct a more in-depth time-series analysis to track trends over multiple years.

## Technologies & Tools Used
- **Python:** Data extraction, cleaning, and analysis (pandas, requests, matplotlib, hvplot)
- **APIs:** Geoapify API for geolocation data
- **Data Visualization:** Matplotlib for charts and scatter plots
- **Statistical Analysis:** Correlation calculations using pandas

## Conclusion
This project provides an exploratory analysis of how environmental factors, particularly lead contamination, may be linked to crime rates. While the correlation found is weak, it suggests that further investigation using more detailed datasets and controlled studies is needed to understand the potential long-term effects of lead exposure on behavior and public safety.
