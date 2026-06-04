# Global Happiness Data Analysis Dashboard

## 📖 Project Overview

This project presents a comprehensive Power BI dashboard analyzing global happiness metrics. The objective was to visualize the relationship between socioeconomic indicators—such as **Economy** and **Family support**—and a nation's **Happiness Rank** and **Happiness Score** over time.

## 🛠️ Data Preparation & Cleaning

The dataset was processed to ensure high analytical standards:

* **Data Structuring**: The data was organized into a "tidy" format, where each row represents a unique observation per country and year, ensuring compatibility for time-series and trend analysis.
* **Data Integrity**: Validated all numerical fields to ensure correct formatting as decimals or integers, facilitating accurate DAX calculations.
* **Analytical Strategy**: Utilized **Average** as the primary aggregation method for rank and score metrics. This approach maintains a consistent scale for comparisons across different regions and time periods, avoiding the distortions often associated with "Sum" aggregations.

## 📊 Key Findings

* **Economic Correlation**: The scatter plot reveals a clear negative correlation between economic stability and happiness rank; generally, as the "Average of Economy" increases, the "Average of Happiness Rank" decreases (indicating a higher, better position).
* **Regional Performance**: The bar chart highlights that regions like Australia and New Zealand lead in average happiness scores.
* **Driver Contribution**: The pie chart illustrates the proportional influence of "Average of Economy" and "Average of Family" on overall metrics.
* **Trend Analysis**: The line and column charts provide a longitudinal view of how average happiness scores and ranks have evolved between 2015 and 2019.

## 🚀 Tools & Techniques

* **Tool**: Power BI Desktop
* **Skills**: Data Cleaning, Tidy Data Structuring, DAX Aggregation, Trend Analysis, Scatter Plot Correlation, and Multi-visual Dashboard Design.

