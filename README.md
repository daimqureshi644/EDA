## Project Overview

This notebook performs an initial Exploratory Data Analysis (EDA) on a marketing campaign dataset. The primary goal is to understand the dataset's structure, identify missing values, and visualize key distributions and relationships between variables.

### Steps Performed:
1.  **Data Loading**: The `marketing_campaign.csv` file was loaded into a pandas DataFrame.
2.  **Initial Inspection**: Basic information about the dataset, such as its shape, data types, and descriptive statistics, was reviewed.
3.  **Missing Value Check**: Checked for and identified missing values, particularly in the 'Income' column.
4.  **Duplicate Check**: Verified and handled any duplicate rows.
5.  **Data Visualization**: Generated several plots to visualize data distributions and relationships, including:
    *   Histogram and Countplot of 'Income'
    *   Scatter plot of 'ID' vs 'Income'
    *   Box plot of 'Year_Birth' vs 'Income'
    *   Heatmap showing the relationship between 'Marital_Status' and 'Education'
    *   Box plot of 'Year_Birth' to identify potential outliers.
