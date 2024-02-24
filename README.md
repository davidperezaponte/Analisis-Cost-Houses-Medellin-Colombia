# Exploratory Data Analysis (EDA) and Data Cleaning

## Overview
This document provides an overview of the exploratory data analysis (EDA) and data cleaning process for the dataset of house prices in the city of Medellin, Colombia. The dataset contains information about various attributes of houses for sale, including area, number of bedrooms, bathrooms, garages, and price.

## EDA
- **Summary Statistics**: Initial exploration involves calculating summary statistics such as mean, median, minimum, maximum, and standard deviation for each numerical attribute to understand the central tendency and dispersion of the data.
- **Histograms**: Histograms are created to visualize the distributions of numerical variables like area, number of bedrooms, bathrooms, garages, and price. This helps identify any potential outliers or skewed distributions.
- **Correlation Analysis**: Correlation analysis is performed to investigate the relationships between numerical variables. Correlation coefficients are calculated and visualized using heatmaps to identify strong correlations that may indicate multicollinearity.

## Data Cleaning
- **Handling Missing Values**: Missing values, if any, are identified and handled appropriately. This may involve imputation techniques such as filling missing values with the mean or median of the respective attribute.
- **Outlier Detection and Removal**: Outliers are detected using statistical methods such as Z-score or interquartile range (IQR). Outliers are then removed or transformed to improve the quality of the data.
- **Feature Engineering**: New features may be created or existing features may be transformed to extract more meaningful information from the data. For example, the total number of rooms (bedrooms + bathrooms) or the price per square meter can be calculated.
- **Normalization/Standardization**: Numerical features may be normalized or standardized to bring them to a similar scale, which is often beneficial for machine learning models.

## Conclusion
The EDA and data cleaning process provide valuable insights into the dataset of house prices in Medellin, Colombia, and prepares the data for further analysis and modeling. By understanding the distribution of variables, identifying outliers, and handling missing values, we ensure the integrity and reliability of the dataset for subsequent tasks such as model building and evaluation.
