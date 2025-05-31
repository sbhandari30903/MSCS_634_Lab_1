# Real Estate Data Analysis Lab

## Overview
This Jupyter notebook contains a comprehensive analysis of real estate sales data, focusing on data visualization, preprocessing, and statistical analysis. The project is part of the Advanced Big Data and Data Mining (MSCS-634-M40) course.

## Purpose
- To analyze real estate sales trends in Connecticut from 2001-2022
- To practice data preprocessing techniques on a real-world dataset
- To extract meaningful insights through statistical analysis and visualization
- To demonstrate proficiency in handling large-scale real estate data

## Key Insights
### Visualization Findings
- Monthly average sale amounts show an upward trend, with significant peaks in recent years
- Property distribution is dominated by residential properties (~75% of total sales)
- Top towns by average sale amount reveal significant price disparities across locations

### Statistical Insights
- High variance in sale amounts indicates a diverse real estate market
- Strong positive correlation (0.85) between assessed values and sale amounts
- Significant number of outliers identified through IQR analysis (~15% of data)

## Technical Challenges & Solutions
1. **Data Quality Issues**
   - Handled missing values using mean/mode imputation based on data type
   - Addressed outliers using IQR-based filtering to ensure reliable analysis

2. **Performance Optimization**
   - Implemented data reduction by sampling 10% of records
   - Dropped unnecessary columns to improve processing efficiency

3. **Data Transformation Decisions**
   - Applied both Min-Max scaling and Z-score normalization for comparison
   - Created categorical bins for sale amounts to facilitate analysis

## Features
- **Data Visualization**
  - Line plots showing monthly average sale amounts
  - Bar charts of average sale amounts by town
  - Pie charts displaying property type distribution

- **Data Preprocessing**
  - Missing value handling
  - Outlier detection using IQR
  - Data reduction techniques
  - Feature scaling (Min-Max and Z-Score)
  - Data discretization

- **Statistical Analysis**
  - Central tendency measures
  - Dispersion analysis
  - Correlation analysis
  - General data overview

## Dependencies
```python
pandas
numpy
matplotlib
```

## Dataset
The analysis uses the "Real_Estate_Sales_2001-2022_GL.csv" dataset containing real estate sales data from 2001-2022.

## Structure
1. Data Loading and Initial Exploration
2. Data Visualization
3. Data Preprocessing
   - Missing Value Treatment 
   - Outlier Detection
   - Data Reduction
   - Data Transformation
4. Statistical Analysis
   - Overview Statistics
   - Central Tendency Analysis
   - Dispersion Analysis
   - Correlation Analysis
