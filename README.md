#  Weather Data Analysis (Canada - 2012)

Comprehensive Exploratory Data Analysis on one year of hourly weather data from Canada (2012).

---

##  Project Overview

This project performs in-depth **Exploratory Data Analysis (EDA)** on historical hourly weather data to uncover seasonal patterns, extreme weather events, and relationships between key meteorological variables.

**Objective**: Understand weather behavior, identify extreme conditions, and extract actionable insights useful for climate studies, aviation, transportation, and energy planning.

---

##  Technologies Used

- **Python** 3
- **Pandas** – Data cleaning & analysis
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook**

---

##  Key Insights

- **Most common weather conditions**: Mainly Clear and Mostly Cloudy (over 47% of observations)
- **Temperature range**: -23.3°C to +33.0°C
- **Highest wind speed**: 83 km/h
- **Visibility range**: 0.2 km (dense fog) to 48.3 km
- Fog and Snow are the primary causes of reduced visibility
- Clear weather is strongly associated with high visibility (>40 km)

---

##  Visualizations Included

### 1. Temperature Distribution with Extreme Thresholds
![Alt text](https://github.com/MishuTI/weather_data_analysis/blob/main/weather.PNG)
- Days with temperature > 30°C and < -15°C clearly marked

### 2. Monthly Clear Weather Hours
- Shows how many hours per month had "Clear" weather

### 3. Pressure Distribution by Weather Condition
- Boxplot showing atmospheric pressure across different weather types

### 4. Visibility vs Wind Speed (Fog Formation Analysis)
- Scatter plot with regression line to understand relationship between wind and visibility

### 5. Temperature vs Relative Humidity by Weather Condition (Facets)
- Separate clear, cloudy, and snow subplots with trend lines and correlation values

---

##  Advanced Analysis Performed

- **Extreme Temperature Days**
  - Hot days (> 30°C)
  - Cold days (< -15°C)

- **Hours of Clear Weather per Month**

- **Relationship between Atmospheric Pressure and Weather Conditions**

- **Visibility vs Wind Speed** (to understand fog formation patterns)

---

##  Conclusion

The 2012 weather data shows typical Canadian seasonal patterns:
- Extreme cold in winter (down to -23.3°C)
- Warm summers reaching up to 33°C
- Clear and Mostly Cloudy conditions dominated the year
- Low visibility events were mostly linked to fog and snow, particularly during low wind speeds

**Key Takeaway**: Fog formation is highly predictable during periods of high humidity and low wind speed — valuable information for aviation and transportation safety.

---

##  How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/MishuTI/weather_data_analysis.git
