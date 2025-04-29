# 🌫 AQI (Air Quality Index) Analysis of Different Cities in India

## 📚 Table of Contents
- 📝 Project Description
- 📊 Steps Involved
- 📥 Data Loading and Exploration
- 🧩 Handling Missing Values
- 📅 Date Conversion
- 📈 Data Visualization
- 🧪 Classifying AQI Categories
- 🧠 Key Insights
- ✅ Conclusion

## 📝 Project Description
This project analyzes AQI (Air Quality Index) data from various cities across India. The objective is to identify the most polluted cities, track air quality trends over time, and classify air quality into categories like "Good", "Moderate", and "Severe" for better environmental awareness. The project uses data manipulation and visualization techniques in Python, specifically utilizing libraries such as Pandas, Matplotlib, and Seaborn.

## 📊 Steps Involved

### 📥 Data Loading and Exploration
- Loaded the `city_day.csv` dataset.
- Inspected initial rows and checked data types and null values.

### 🧩 Handling Missing Values
- Applied forward filling to handle missing AQI values.

### 📅 Date Conversion
- Converted the `Date` column to datetime format for time-based analysis.

### 📈 Data Visualization
- **AQI Distribution**: Histogram of AQI values.
- **Top 10 Polluted Cities**: Bar plot showing cities with the highest average AQI.
- **AQI Trends Over Time**: Line plots for top 5 most polluted cities.
- **AQI Categories**: Pie chart of categorized AQI levels.

### 🧪 Classifying AQI Categories
- Defined AQI categories such as Good, Moderate, Poor, Severe using a custom function.

## 🧠 Key Insights
- Identified most polluted cities based on AQI levels.
- AQI trends visualized over time for policy planning.
- Simplified interpretation of pollution levels using category classification.
- Cleaned data prepared for future prediction modeling.

## ✅ Conclusion
This project provides a detailed EDA of AQI data across Indian cities. The classification and visual representation of AQI help understand pollution distribution and trends, aiding environmental planning and awareness.
