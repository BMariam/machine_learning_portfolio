This repository contains my machine learning projects.

## Projects

### Mall Customer Segmentation using KMeans
Data source [here](https://www.kaggle.com/shwetabh123/mall-customers)\
Input variables:\
  &nbsp;&nbsp;&nbsp;&nbsp;CustomerID\
  &nbsp;&nbsp;&nbsp;&nbsp;Genre\
  &nbsp;&nbsp;&nbsp;&nbsp;Age\
  &nbsp;&nbsp;&nbsp;&nbsp;Annual Income (k$\)\
  &nbsp;&nbsp;&nbsp;&nbsp;Spending Score (1-100)\
Dataset size: (200, 5)\
Resources used: Python 3.6.9, pandas, matplotlib, seaborn, sklearn\
Data preparation techniques used: StandardScaler, LabelEncoder\
Algorithms used: KMeans 

Model performance:

  &nbsp;&nbsp;&nbsp;&nbsp;silhouette_score = 0.443 using 'Age' and 'Annual Income' features and setting n_clusters = 3\
  &nbsp;&nbsp;&nbsp;&nbsp;silhouette_score = 0.438 using 'Age' and 'Spending Score' features and setting n_clusters = 4\
  &nbsp;&nbsp;&nbsp;&nbsp;silhouette_score = 0.554 using 'Annual Income' and 'Spending Score' features and setting n_clusters = 5\
  &nbsp;&nbsp;&nbsp;&nbsp;silhouette_score = 0.356 using 'Genre', 'Age', 'Annual Income' and 'Spending Score' features and setting n_clusters = 6

### Wine quality detection
Data source [here](https://archive.ics.uci.edu/ml/datasets/wine+quality)
