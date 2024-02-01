# EDA
This repository contains the code and documentation for an exploratory data analysis (EDA) project focused on bike sharing data and global car data.The goal of this analysis is to gain insights into the patterns, trends, and correlations present in the datasets, providing a comprehensive understanding of the dynamics in bike sharing systems and the automotive industry worldwide.

# Datasets:
# 1. Bike Sharing Data:
The bike sharing dataset includes information on bike usage patterns, user demographics, and environmental factors that influence bike sharing activities. The data has been sourced from [https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset].

# 2. Global Car Data:
The global car dataset encompasses information on various aspects of the automotive industry, distribution of the 'Founded_Year' column,Number of companies in each industry and pair plot for numeric columns. The data has been collected from [https://www.kaggle.com/datasets/shiivvvaam/car-companies-in-the-world].

# Key Analysis:
# Bike Sharing Insights:
1. Uncover patterns in bike usage over time.
2. Explore the impact of weather conditions and other factors on bike sharing trends.
3. Analyze user demographics and preferences.

# Global Car Trends:
1. Examine trends in founded year column
2. Discover number of companies in each industry 
3. Pair plot for numeric columns

# Repository Contents:
1. Jupyter Notebooks: EDA code written in Python using Jupyter Notebooks.
2. Datasets: Raw and cleaned datasets used in the analysis.
4. Visualizations: Plots, charts, and graphs generated during the EDA process.
5. Documentation: Detailed explanations and insights derived from the analysis.

# Usage:
Feel free to explore the Jupyter Notebooks and datasets provided in this repository to gain insights into the bike sharing industry and global car companies. Contributions and feedback are welcome!



# CHURN PREDICTION 
The provided code performs churn prediction analysis using a dataset, with a focus on understanding customer behavior and predicting factors influencing customer lifetime value. Here's a summary of the code:

1. **Data Loading and Exploration:**
   1. The code starts by importing necessary libraries and loading the dataset from a specified file path.
   2. Initial exploratory data analysis includes displaying a sample of the data, generating descriptive statistics, and examining the distribution of       the 'Contract' variable.

2. **Data Cleaning:**
   1. The 'TotalCharges' column is initially set to None and later converted to float64 by multiplying 'tenure' and 'MonthlyCharges'.
   2. The cleaned dataset is saved to a CSV file for further analysis.

3. **Visualization and Analysis:**
   1. Visualizations are created to explore patterns among customers who have churned.
   2. The dataset is divided into two groups based on the 80th percentile of 'TotalCharges', and various characteristics like contract type, internet        service, and additional services are analyzed for both groups.

4. **Multiple Linear Regression:**
   1. Dummy variables are created for categorical features, and a multiple linear regression model is fitted to understand the relationship between          different factors and 'TotalCharges'.
   2. Coefficients of the model are visualized to identify the impact of various variables on customer lifetime value.

5. **Analysis of Internet Service Subsets:**
   1. Dummy variables are generated for subsets of internet services, and another multiple linear regression is performed to analyze their impact on         'TotalCharges'.
   2. Coefficients of this model are visualized to assess the contribution of each subset of internet services to customer lifetime value.

The code provides a comprehensive approach to churn prediction, combining data exploration, cleaning, and visualization techniques. The insights gained from the analysis can be valuable for making informed decisions regarding customer retention strategies.


