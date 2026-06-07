# 🌍 Global Climate Trends and Geographic Drivers of Temperature Variation 1891-2012.

## Overview

This project investigates historical climate records from major cities worldwide to understand how temperatures have evolved over time and what geographic factors influence regional climate differences. The analysis combines data quality assessment, exploratory data analysis, uncertainty evaluation, and geographic modeling to uncover long-term temperature patterns and assess the reliability of climate observations.

---

## Business Question

How have global temperatures evolved over time, and what geographic factors drive regional climate differences?

Understanding long-term climate patterns is essential for organizations involved in:
- Agriculture
- Infrastructure planning
- Energy management
- Environmental policy
- Climate risk assessment

---

## 📊 Dataset
- Source: Kaggle (GlobalLandTemperatures_GlobalLandTemperaturesByMajorCity)  
  [Dataset](GlobalLandTemperatures_GlobalLandTemperaturesByMajorCity.csv)
- Records: 293,178
- Time Period: 1743–2013
- Analysis Period: 1891–2012
 
--- 

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Plotly

---

## Key Findings
- Global temperatures exhibit a long-term warming trend.
- Temperature records before 1891 are sparse and less reliable.
- Measurement uncertainty decreases significantly over time.
- Sudan is the warmest country on average, while Russia is the coldest.
- Distance from the equator is strongly associated with temperature (r = -0.884).
- Extreme temperatures appear to be genuine climatic observations rather than measurement anomalies.

---

## Sample Visualizations

### Global Average Temperature Over Time

![Global Temperature Trend](Global_avg_temp_over_time.png)

### Cities by Average Temperature

![Warmest and coldest cities](Cities_by_avg_temp.png)

### Average Temperature vs Distance from Equator

![Distance from Equator](Distance_equator.png)

---

[analylis](Temperature_Analysis.ipynb)

## Conclusion

This analysis reveals that global temperatures have generally increased over the past century, with the most recent decades recording some of the highest average temperatures in the dataset. While early observations suggested substantial fluctuations, further investigation showed that these variations were largely driven by sparse data coverage and higher measurement uncertainty rather than genuine climate shifts. Restricting the analysis to the well-covered period from 1891 to 2012 provided a more reliable view of long-term climate behavior and revealed a clear and persistent warming trend.

The study also demonstrated that geographic location is one of the strongest drivers of regional climate variation. Temperature decreases significantly with increasing distance from the equator, with latitude explaining a substantial proportion of the observed differences between cities and countries. However, geographic position alone does not fully determine climate conditions, as local environmental factors such as topography, proximity to water bodies, and regional climate systems also contribute to temperature variability.

Importantly, the analysis showed that measurement uncertainty has steadily declined over time, indicating improvements in climate monitoring and data collection practices. Furthermore, extreme temperature observations were not associated with higher uncertainty, providing confidence that the hottest and coldest records in the dataset reflect genuine climatic conditions rather than data quality issues.

Overall, the findings suggest that both long-term warming and geographic location play fundamental roles in shaping global temperature patterns. These insights can support climate-risk assessment, environmental planning, infrastructure development, and other data-driven decisions that depend on understanding regional and temporal climate dynamics.

