# Credit-Card-Customers-Segmentation
This project applies unsupervised machine learning to segment credit card customers based on their behavioral data. Using clustering algorithms such as KMeans, Agglomerative Clustering, DBSCAN, and Gaussian Mixture Models, we analyze and group similar customers to generate insights for marketing and customer relationship management.

# Dataset
Dataset contains anonymized data about 8,950 active credit card holders with 18 behavioral features, including balances, purchases, cash advances, and payment history over the past 6 months.
- Source: Kaggle
- Link: https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

# Project Phases
### 1. Data Exploration and Preprocessing
- Investigated dataset structure and features.
- Analyzed feature distributions and relationships.
- Handled missing values and cleaned anomalies.
- Performed dimensionality reduction on dataset.
- Highlighted patterns to guide clustering strategy.

### 2. Determining Optimal Clusters
Chose optimal number of clusters based on data behavior and statistical validation.
#### Models Applied:
- KMeans
- Agglomerative Clustering
- Gaussian Mixture Models
- DBSCAN
#### Evaluation Metrics:
- Elbow Method
- Silhouette Score (higher is better)
- Calinski-Harabasz Index (higher is better)
- Davies-Bouldin Index (lower is better)

### 3. Customer Segmentation
- Performed clustering using chosen clustering method (K-Mean) and optimal number of clusters (4 Clusters).
- Assigned cluster labels to customers.
- Created customer profiles such as:
  1. High Balance, Cash Oriented Customers
  2. Low Engagement, Low Activity Users
  3. High-Spending, Frequent Usage Customer
  4. Moderate Usage Customers

### 4. Visualization and Analysis
- Applied PCA for clusters visualization in 2D.
- Used Matplotlib and Seaborn for cluster visualization.
- Illustrated trends and distinctions across customer segments.
- Derived key insights from visual patterns.

### 5. Business Insights & Recommendations
- Explained each cluster's behavior from a business perspective.
- Suggested targeted strategies for each customer group:

### Key Technologies
- Python for Data analysis and modeling
- Pandas and NumPy for Data preprocessing
- Scikit-learn for Clustering and evaluation
- Matplotlib and Seaborn for Visualization
