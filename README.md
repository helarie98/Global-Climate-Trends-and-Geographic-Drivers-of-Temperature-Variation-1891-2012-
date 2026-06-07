# 🌍 Global Climate Trends and Geographic Drivers of Temperature Variation 1891-2012.

## Overview

This project investigates historical climate records from major cities worldwide to understand how temperatures have evolved over time and what geographic factors influence regional climate differences. The analysis combines data quality assessment, exploratory data analysis, uncertainty evaluation, and geographic modeling to uncover long-term temperature patterns and assess the reliability of climate observations.

---

## Business Question

How have global temperatures evolved over the past century, and what geographic factors drive regional climate differences?

Understanding long-term climate patterns is essential for organizations involved in:
- Agriculture
- Infrastructure planning
- Energy management
- Environmental policy
- Climate risk assessment

---

## 📊 Dataset
- Source: Kaggle (GlobalLandTemperatures_GlobalLandTemperaturesByMajorCity)  
  [Raw Dataset](Raw_data.csv) #link to it in github

### Dataset Size
- Initial observations: 293,178
- Geographic coverage: Major cities worldwide
- Time range: 1743–2013
  
--- 

Features
Column | Description
--- | ---
dt | Observation date
AverageTemperature | Average temperature (°C)
AverageTemperatureUncertainty | Measurement uncertainty
City | City name
Country | Country
Latitude | Geographic latitude
Longitude | Geographic longitude



Data Quality Assessment

Several preprocessing steps were performed before analysis:

Data Cleaning
Converted date column to datetime format
Extracted Year, Month, and Day features
Removed records with missing temperature values
Evaluated missing values and duplicates
Assessed data coverage across years
Coverage Assessment

Analysis revealed highly inconsistent data availability before 1891:

Sparse observations between 1743–1890
Stable coverage between 1891–2012
Incomplete observations for 2013

To ensure reliable trend analysis, the study focuses on:

1891–2012

Key Analyses
1. Long-Term Temperature Trends

The analysis reveals a persistent increase in average temperatures over time.

While early observations exhibit substantial variability due to limited data coverage, temperatures show a clearer and more consistent upward trend after the late nineteenth century.

Key Finding

Recent decades are among the warmest periods observed in the dataset.

2. Data Coverage Assessment

Early fluctuations in average temperature were investigated by analyzing the number of observations recorded each year.

The results show that:

Early years contain very few observations
Data coverage expands significantly during the nineteenth century
Coverage becomes stable after 1891
Key Finding

Many apparent early temperature fluctuations are more likely caused by sparse data rather than genuine climate changes.

3. Seasonal Patterns

Average temperatures exhibit a strong seasonal cycle.

Key Findings
January is the coolest month (~12.2°C)
July is the warmest month (~24.2°C)
Temperatures follow a consistent annual cycle
4. Regional Climate Differences
Country-Level Analysis

City-Level Analysis

Key Findings
Sudan is the warmest country in the dataset
Russia is the coldest country on average
Umm Durman (Sudan) is the warmest city
Harbin (China) exhibits some of the coldest observed temperatures

This demonstrates the substantial geographic variation in global climate conditions.

5. Measurement Uncertainty Analysis

To assess data reliability, temperature uncertainty was analyzed across time.

Key Findings
Measurement uncertainty decreases steadily over time
Modern observations are more reliable than historical records
Extreme temperatures generally exhibit low uncertainty

These findings suggest that observed climate extremes are genuine measurements rather than artifacts of poor data quality.

6. Temperature vs Measurement Uncertainty

Correlation analysis produced:

r = -0.0017
Key Finding

Temperature and measurement uncertainty are effectively independent.

This indicates that extremely hot and cold observations are not systematically less reliable than moderate temperatures.

7. Geographic Drivers of Temperature

A geographic analysis was performed using latitude information.

A new feature, Distance From Equator, was engineered to investigate how location influences climate.

Results
Correlation = -0.884
Key Findings
Temperatures decrease as distance from the equator increases
Latitude is a strong predictor of climate conditions
Geographic location explains a substantial portion of observed temperature variation
Key Insights
Climate Trends
Global temperatures show a long-term warming trend
Recent decades are among the warmest periods in the dataset
Data Reliability
Measurement uncertainty decreases over time
Climate observations become increasingly reliable throughout the twentieth century
Geographic Effects
Distance from the equator is strongly associated with temperature
Latitude is one of the strongest drivers of regional climate differences
Climate Extremes
Extreme temperatures in cities such as Baghdad, Riyadh, and Harbin appear to represent genuine climatic conditions rather than measurement anomalies
Business Implications

The findings demonstrate that both temporal and geographic factors play critical roles in shaping climate patterns.

Organizations can leverage these insights for:

Agricultural planning
Energy demand forecasting
Climate risk assessment
Infrastructure design
Environmental policy development

Additionally, latitude-based information can serve as a simple yet powerful predictor of regional temperature conditions.

Tools Used
Python
Pandas
NumPy
Matplotlib
Plotly
Conclusion

This analysis demonstrates that global temperatures have generally increased over the last century while measurement reliability has simultaneously improved. Geographic location, particularly distance from the equator, emerges as one of the strongest determinants of regional climate variation.

Together, these findings provide evidence of both long-term warming trends and the significant influence of geographic factors on global temperature patterns.

One final recommendation

Before pushing to GitHub, export every plot as a PNG and place them in an images/ folder. Repositories with visual outputs consistently look more professional and receive more attention from recruiters than notebooks alone.
