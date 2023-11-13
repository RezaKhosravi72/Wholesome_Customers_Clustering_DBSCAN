# Wholesome Customers Clustering using DBSCAN

This repository contains notebooks applying DBSCAN clustering on customer data for segmentation and analysis.

## Notebooks

1. DBSCAN.ipynb
  
This notebook contains a general introduction to DBSCAN clustering algorithm and demonstrates its application on sample data.

2. DBSCAN_Hyperparameters.ipynb

This notebook tunes the eps and min_samples hyperparameters of DBSCAN using a grid search to find optimal values. 

3. Wholesome_Customers_Clustering_DBSCAN.ipynb

This notebook performs DBSCAN clustering on real customer data to segment them into meaningful groups based on spending behavior. Insights help optimize marketing strategies.

## Data

The 'wholesome_customers_data.csv' file contains demographic and purchase behavior data for 5000 customers of a wholesome goods retailer, including age, annual income, and spending score.

### The variables included are:
  
  - Customer ID (integer index)
  - Age (in years)
  - Annual Income (in dollars) 
  - Spending Score (1-100 rating of purchase amount)


- Age ranges from 18 to 80 years 
- Income ranges from $20,000 to $200,000
- Spending Score indicates customers from low to heavy spenders

      
**- This multi-dimensional data allows analyzing relationships between factors like how age/income impact spending habits.**

**- The data has been anonymized and samples real customers to model real-world scenarios.** 

**- It is used to identify natural groupings of similar customers based on the 3 variables.** 

**- Insights help understand customer profiles within each segment for targeted promotions, recommendations, loyalty programs etc.**

**- The continuous variables like Age, Income are standardized before clustering to give equal importance.**

**- DBSCAN effectively handles the non-spherical clusters and outliers expected in this customer behavior data.**

**- Results enable data-driven segmentation to optimize marketing approach for each segment.**

## Objectives

- Identify core customer clusters and outliers  
- Gain understanding of customer profiles within each segment
- Extract relationships between variables like age, income and spending
- Recommend targeted promotional strategies

## Requirements

- Python
- Scikit-learn 
- Pandas, NumPy, Matplotlib

The repositories provide implementing DBSCAN on different datasets to demonstrate its efficacy for various clustering problems.
