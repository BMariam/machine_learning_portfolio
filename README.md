This repository contains my machine learning projects.

## Projects

### Mall Customer Segmentation using KMeans
Data source [here](https://www.kaggle.com/shwetabh123/mall-customers)\
Input variables:\
  &nbsp;CustomerID\
  &nbsp;Genre\
  &nbsp;Age\
  &nbsp;Annual Income (k$\)\
  &nbsp;Spending Score (1-100)\
Dataset size: (200, 5)\
Resources used: Python 3.6.9, pandas, matplotlib, seaborn, sklearn\
Data preparation techniques used: StandardScaler, LabelEncoder\
Algorithms used: KMeans\ 
Model performance:\ 
  silhouette_score = 0.443 using 'Age' and 'Annual Income' features and setting n_clusters = 3\
  silhouette_score = 0.438 using 'Age' and 'Spending Score' features and setting n_clusters = 4\
  silhouette_score = 0.554 using 'Annual Income' and 'Spending Score' features and setting n_clusters = 5\
  silhouette_score = 0.356 using 'Genre', 'Age', 'Annual Income' and 'Spending Score' features and setting n_clusters = 6\
Scatterplot of best performed model: 
  
### Wine quality detection
Data source [here](https://archive.ics.uci.edu/ml/datasets/wine+quality)
