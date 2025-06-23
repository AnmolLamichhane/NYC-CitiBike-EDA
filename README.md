# NYC Citi Bike Trips - Exploratory Data Analysis (EDA)

Project Summary

This project presents a comprehensive Exploratory Data Analysis (EDA) of the NYC Citi Bike trip dataset to uncover usage patterns, station popularity, user behavior, and temporal trends. The analysis supports data-driven decisions for bike redistribution, station maintenance, and understanding customer demand dynamics.

---

Dataset Overview

- **Dataset Name:** NYC Citi Bike Trip Data
- **Dataset Link:** https://www.kaggle.com/datasets/hollyjordan/nyc-citi-bike-trip-data-october-2013?resource=download
- **Records:** Over 1 million trips
- **Features:**
  - Trip Duration
  - Start/End Station ID and Name
  - Start/End Time
  - User Type (Subscriber/Customer)
  - Gender
  - Birth Year

---

## 🛠️ Tools & Technologies

| Technology   | Purpose                      |
|-------------|-----------------------------|
| Python 3.x   | Programming Language        |
| Pandas      | Data manipulation and cleaning |
| Matplotlib  | Visualization                |
| Seaborn     | Statistical data visualization |
| Folium      | Geospatial visualizations (Map plotting) |

---

EDA Workflow Summary

1. **Data Quality Checks**
   - No missing values detected.
   - No duplicate records present.
   - Data types validated and consistent.

2. **Feature Engineering**
   - Extracted 'hour' feature from start time for time-based analysis.

3. **Univariate & Bivariate Analysis**
   - Identified most frequent start stations.
   - Scatterplot created to understand trip duration trends over hours.
   - Users segmented by Subscriber vs Customer.

4. **Geospatial Visualization**
   - Folium map used to plot start station locations.
   - Major station hotspots identified in Midtown Manhattan.

---

## 📈 Key Insights

- **Most Popular Start Station:**  
  `8 Ave & W 31 St` — consistently records the highest number of trip starts.

- **Peak Usage Hours:**  
  Highest demand observed during:
  - **Morning Commute:** 9 AM  
  - **Afternoon Peaks:** 2 PM – 3 PM  
  - **Evening Commute:** 5 PM – 6 PM

- **Trip Duration:**  
  Majority of trips are short (under 30 minutes), indicating commuter or casual city use.

- **User Base:**  
  `Subscribers` form the dominant user group, suggesting high daily/regular usage compared to occasional customers.

- **Station Concentration:**  
  Significant station density in Midtown Manhattan, close to commercial and tourist zones.

---

💡 Recommendations

- Ensure sufficient bike availability at **8 Ave & W 31 St** during peak commute hours.
- Consider expanding or maintaining stations in the Midtown area to handle heavy usage.
- Analyze weekend vs weekday trends for additional seasonal insights.
  
---


