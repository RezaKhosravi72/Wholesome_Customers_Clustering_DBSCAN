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

## Outcomes

- 5 distinct customer clusters were identified by the algorithm. 

  - Cluster 1 contains high-income, middle-aged customers who are heavy spenders. 
  
  - Cluster 2 has young customers with average income but high spending. 
  
  - Cluster 3 consists of mid-to-high income customers in their 30s-40s who spend moderately.
  
  - Cluster 4 has older, affluent retirees who purchase regularly but in smaller amounts.  
  
  - Cluster 5 contains outliers like very low-income or high-spending aberrations.


- Visualizations show non-spherical clusters separated clearly with outliers on the fringe.

- The optimal epsilon and minimum sample values were determined to be 0.3 and 10 via grid search.

- Key variable importances identified age and income as more impactful than spending score.

- Targeted marketing strategies can now focus on needs of each segment

- Cluster 1 for high-value promotions, Cluster 2 for experience-based offers, Cluster 3 for lifestyle products etc.

- Regular profiling helps identify shifting profiles to adjust approach over time. 

- Outliers need further analysis to take corrective action or targeted acquisition campaigns.

- The unsupervised approach uncovered hidden patterns compared to traditional binning methods.

- Future work involves evaluating more algorithms, adding dimensions and modeling changes over time.

## Requirements

- Python
- Scikit-learn 
- Pandas, NumPy, Matplotlib

The repositories provide implementing DBSCAN on different datasets to demonstrate its efficacy for various clustering problems.
