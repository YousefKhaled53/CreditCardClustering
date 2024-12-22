# CreditCardClustering
Different clustering techniques applied on Credit Card dataset 

I used a credit card dataset from kaggle : https://www.kaggle.com/datasets/arjunbhasin2013/ccdata/data

This case requires to develop a customer segmentation to define marketing strategy. The
sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables.
I had 2 processes to be done in this project, first one preprocessing, the second is the modeling.
# Pre Processing
I did normal data preprocessing which you can explore in the MAIN notebook in the project.

Also using PCA reduction method on the dataset

# Modeling
I performed clustering twice, one for the original data without PCA and the other is with PCA.

**Types of clustering used:** 1- KMeans clustering , 2- Hierarchical clustering , 3- Spectral clustering.

**Model evaluation:** Used metric Dunn index and Silhouette Score to evaluate the quality of clustering of each model.

**Visualization:** Plotted the clusters for each method in the PCA-reduced 2D.
