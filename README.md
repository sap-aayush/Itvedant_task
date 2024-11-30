# Literacy and Unemployment Trends Analysis in India

## Objective

This project explores the relationship between literacy rates and unemployment trends across various districts and states in India. The goal is to identify whether higher literacy rates correlate with lower unemployment and provide insights for policymakers to focus education-driven interventions.

## Dataset

The analysis is based on the **Census 2011 Literacy Data** for districts in India. The dataset contains the following features:

- **District**: Name of the district.
- **State**: Name of the state corresponding to the district.
- **Literacy Rate**: Percentage literacy in the district.

## Key Tasks

1. **Data Cleaning and Preparation**:
   - Standardizing column names and state names.
   
2. **Exploratory Data Analysis**:
   - Visualizing the top 50 districts by literacy rate.
   - Generating a boxplot to observe literacy rate distribution across states.
   - Ranking states based on average literacy rates.
   
3. **Clustering Analysis**:
   - Applying K-Means clustering to group states based on their literacy rates into three categories.
   - Visualizing these clusters using a scatter plot.

4. **Hypothesis Testing**:
   - Exploring whether higher literacy rates consistently correlate with lower unemployment.
   - Investigating differences between rural and urban areas in terms of literacy and unemployment.

# Unemployment Rate Analysis in India

## Overview

This project aims to analyze unemployment trends across various states in India, using data from 2019 to 2020. The analysis explores different aspects of unemployment, such as regional disparities, urban vs rural differences, and the impact of the COVID-19 pandemic on employment rates. The goal is to provide insights into the factors influencing unemployment and identify potential areas for policy improvement.

### Objectives
- Analyze unemployment trends across states and regions.
- Investigate the relationship between unemployment and employment metrics.
- Explore the difference in unemployment rates between rural and urban areas.
- Build a machine learning model to predict unemployment rates based on labor participation rates.

---

## Dataset

The dataset contains the following columns:

- **Region**: The state or region in India.
- **Date**: The date for the unemployment data, with monthly entries.
- **Frequency**: The frequency of data collection (monthly).
- **Unemployment Rate (%)**: The estimated unemployment rate for the given region and date.
- **Estimated Employed**: The number of employed individuals.
- **Labour Participation Rate (%)**: The percentage of the working-age population actively participating in the labor force.
- **Area**: Indicates whether the data is from rural or urban areas.

The data spans from **2019 to 2020**, covering a period of economic disruptions, especially due to the COVID-19 pandemic.

---

## Project Workflow

### 1. **Data Preprocessing**
- **Missing Data Handling**: Checked for missing values and dropped invalid entries.
- **Date Conversion**: Converted the 'Date' column to datetime format for time-series analysis.
- **Filtering**: Filtered out irrelevant or incorrect records.

### 2. **Exploratory Data Analysis (EDA)**
- **Descriptive Statistics**: Computed mean, median, standard deviation, and range for key columns like unemployment rate, labor participation rate, and employment numbers.
- **Visualization**:
  - Bar chart of **average unemployment rate by state**.
  - Line chart for **monthly unemployment rate trends**.
  - Pie chart comparing **unemployment rates in rural vs urban areas**.

### 3. **Insights & Correlation**
- Analyzed the correlation between unemployment rates and employment numbers.
- Visualized the correlation matrix using a heatmap.

### 4. **Predictive Modeling**
- Built a **linear regression model** using the **Labour Participation Rate** as the independent variable to predict unemployment rates.
- Model evaluation was performed using **Mean Squared Error (MSE)**.

### 5. **Final Insights**
- Identified regions with the highest unemployment rates and seasonal trends.
- Recommended targeted employment programs for rural areas.
- Suggested policies to improve labor participation and reduce unemployment.

---

## Visualizations

1. **Average Unemployment Rate by State**:
   A bar chart showing the average unemployment rate across various states.

2. **Monthly Unemployment Rate Trends**:
   Line plots visualizing monthly fluctuations in unemployment rates for different states.

3. **Unemployment Rate by Area (Urban vs Rural)**:
   A pie chart that shows the proportion of unemployment in rural vs urban regions.

4. **Correlation Heatmap**:
   A heatmap to visualize the correlation between unemployment rate, labor participation rate, and other variables.

---
