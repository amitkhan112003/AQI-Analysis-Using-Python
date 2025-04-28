
## AQI (Air Quality Index) Analysis of Different Cities in India
## Table of Contents

Table of Contents
Project Description

Steps Involved

Data Loading and Exploration

Handling Missing Values

Date Conversion

Data Visualization

Classifying AQI Categories

Key Insights

Conclusion
## Project Description

Project Description
This project analyzes AQI (Air Quality Index) data from various cities across India. The objective is to identify the most polluted cities, track air quality trends over time, and classify air quality into categories like "Good", "Moderate", and "Severe" for better environmental awareness. The project uses data manipulation and visualization techniques in Python, specifically utilizing libraries such as Pandas, Matplotlib, and Seaborn.

## Steps Involved

Data Loading and Exploration
The dataset, city_day.csv, is loaded and explored to understand its structure.

Initial checks include examining the first few rows and determining the data types and missing values.

Handling Missing Values
Missing values in the AQI column are handled using forward filling, ensuring that gaps in AQI data are filled appropriately for accurate analysis.

Date Conversion
The Date column is converted to a datetime type to facilitate time-based analysis and plotting.

Data Visualization
AQI Distribution: A histogram is used to visualize the distribution of AQI values across the dataset.

Top 10 Most Polluted Cities: A bar plot is created to show the top 10 cities with the highest average AQI.

AQI Trends Over Time: Line plots are generated to visualize how AQI values change over time for the top 5 cities with the highest average AQI.

AQI Categories: A pie chart is used to visualize the distribution of AQI categories like Good, Satisfactory, Moderate, etc.

Classifying AQI Categories
A function is created to classify AQI values into categories (Good, Satisfactory, Moderate, Poor, Very Poor, Severe), making it easier to assess air quality.
## Key Insights

This project provides valuable insights into air quality across Indian cities. By visualizing AQI distributions, identifying the most polluted cities, and tracking air quality trends over time, the project contributes to raising awareness about environmental issues. The classification of AQI into categories further simplifies the understanding of pollution levels and can be used for environmental reporting and decision-making. The cleaned dataset is saved for future analysis and potential predictive modeling.
## Conclusion

This project successfully demonstrates the process of importing data from CSV files into an SQL database for further analysis. The tables cc_detail and cust_detail were created and populated with data using the COPY command. Additional data was also inserted into the tables to keep the records up-to-date.

A Power BI dashboard was then created to visualize key insights from this dataset. This includes customer demographics, card usage patterns, and financial metrics such as credit limits and transaction amounts.

This project provides a foundation for building advanced analytical models and interactive reports using SQL and Power BI.