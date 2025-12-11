# Air Quality Analysis in Indian Cities

This project analyzes air pollution levels across major Indian cities using historical PM2.5, PM10, Ozone, and other pollutant data. The visualizations help understand seasonal trends, city comparisons, pollutant relationships, and geographic hotspots.

---

## **Features**

- **City-wise Analysis:** Latest air quality metrics for each city.
- **Pollutant Trends:** Monthly and seasonal trends for PM2.5 and PM10.
- **AQI Calculation:** Custom AQI score combining PM2.5, PM10, NO₂, and O₃.
- **Interactive Maps:** Geographic heatmaps and AQI visualization using Folium.
- **Data Exploration:** Correlation analysis, distribution plots, and scatter matrices.

---

## **Charts & Insights**

- **City-wise PM2.5 & PM10 Trend**  
  - Line chart showing monthly PM2.5 and PM10 levels for a selected city.  
  - Highlights seasonal peaks and periods of high pollution.  
  - Helps stakeholders track trends and plan interventions for critical months.

<img width="902" height="690" alt="image" src="https://github.com/user-attachments/assets/9e58c44d-04d3-45dc-ba81-2d9da4666256" />

- **PM2.5 Trend Comparison Across Cities**  
  - Line chart comparing PM2.5 levels across multiple major cities.  
  - Highlights differences in pollution severity and seasonal variations.  
  - Allows prioritization of cities with consistently high pollution levels.

- **Top 10 Most Polluted Cities**  
  - Bar chart ranking cities by the highest PM2.5 levels.  
  - Quickly identifies pollution hotspots.  
  - Useful for awareness campaigns and city-level policy focus.

<img width="1003" height="612" alt="image" src="https://github.com/user-attachments/assets/f0fd9359-4378-4576-9cca-ca95030232bb" />

- **AQI Score by City**  
  - Bar chart showing a custom AQI score based on weighted pollutants.  
  - Provides a single metric to compare overall air quality.  
  - Highlights cities with the highest combined pollution impact.

- **PM2.5 vs PM10 Bubble Chart**  
  - Scatter plot of PM2.5 vs PM10, with bubble size representing NO₂ levels.  
  - Highlights cities where multiple pollutants are high simultaneously.  
  - Useful for assessing combined health risks.

- **Distribution of Pollutants (Boxplot)**  
  - Shows spread and variability of PM2.5, PM10, O₃, and NO₂ across cities.  
  - Detects outliers and extreme pollution events.  
  - Helps understand typical versus critical pollution conditions.

- **Correlation Heatmap**  
  - Displays pairwise correlation between key pollutants.  
  - Identifies pollutants that rise and fall together.  
  - Supports insights on pollution sources and mitigation strategies.
 
<img width="860" height="631" alt="image" src="https://github.com/user-attachments/assets/0cf64ca1-3a80-4517-ab05-1d5381af2611" />


- **Interactive Folium Heatmaps**  
  - **Pollution Index Map:** Visualizes weighted pollution index (PM2.5 & PM10).  
  - **AQI-like Map:** Displays combined AQI metric across cities.  
  - Helps identify geographic hotspots and compare pollution severity across regions.

---

## **How to Use**

1. Open the Colab notebook `air_quality_analysis.ipynb`.  
2. Install required packages if not already installed:
```bash
!pip install pandas matplotlib seaborn folium
