# Macdonald Customer Segmentation Project
**Overview**
This project aims to segment customers based on their characteristics using the Macdonald (Moving Average Convergence Divergence) dataset. The dataset contains information on 15 attributes for 1453 customers. The segmentation is performed using the k-means clustering method implemented in Python, It is an unsupervised ML Technique and after grouping them we can easily do our Marketing Process, EXAMPLE: New Product lunching or Specific Offers at that time we have different types of Customer Groups as per the requirement we can Target that Particular Group.

# Methodology
**Data Preprocessing:**
Imported necessary libraries such as pandas, numpy, matplotlib, and seaborn.
Handled missing values and performed exploratory data analysis (EDA) to gain insights into the data distribution.

**Feature Engineering:**
Utilized Principal Component Analysis (PCA) to reduce dimensionality and extract important features.
Clustering:

Applied the k-means clustering algorithm to group similar customers together based on their attributes.
Visualization:

Generated various graphs and visualizations to understand the clustering results and interpret customer segments.

# Requirements
**Python Jupiter-lab/notebook or Google-Colab**
**pandas**
**numpy**
**matplotlib**
**seaborn**
**scikit-learn**


# How to Run
**1 Use the Customer Eating Experience Data-set with pd.read_csv.**

**2 Install the required libraries using pip:**
  **EXAMPLE** **pip install pandas numpy matplotlib seaborn scikit-learn**
  
**3 Run the or Python script to execute the code.**

**4 Explore the clustering results and insights obtained from the visualizations.**

first insert the data-set and understand the structure of the data-set, columns and rows, and missing values, and outliers, anomaliers bad-junk data, after that start your EDA Process 
in the feature-engeenring i did these steps [null-values checking,missing values,duplicates checking ,bad-data,outliers,lable-encoding,standardization,plot some graphs to understand the data to get insights,to check the correlation between varibales(columns) with heat-map, to avoide bad permormance of our model i did PCA, and after that with the help of elbow curve i decide the number of groups i want, and in last i Applied K-Means Clustering Model,and plot the result in sclatter-Plot, and save the predicted Group result, the result link is available]


# Data
[Download Dataset](https://drive.google.com/file/d/1Yxwxczc0Nisk_0jfR1BKciilv4MsOXem/view?usp=sharing): Contains information on 15 attributes for 1453 customers.
# Results
[Download Results](https://drive.google.com/file/d/1_YgXNTfzDCgqgKPV8yVq0fXeDVZ7M2Uw/view?usp=sharing): Provides the output of the customer segmentation, including clusters and assigned labels.
