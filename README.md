# Customer Segmentation using K-Means Clustering

This project demonstrates customer segmentation using the K-Means clustering algorithm. 
We identify distinct groups of customers based on their annual income and spending score 
from a mall customer dataset.
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

The dataset contains customer data including:
- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

Elbow Method
A technique to find the optimal number of clusters (K). It plots inertia (within-cluster sum of squared errors) for different values of K. The 'elbow point' indicates the best K.

Inertia
It is the sum of squared distances between each point and its assigned cluster center. Lower inertia means tighter clusters.

Silhouette Score
Measures how similar a point is to its own cluster compared to others. Ranges from -1 to 1.Higher silhouette score means better-defined clusters.

Choosing K
Use the Elbow method and Silhouette Score to determine the best number of clusters.In this case, K=5 was optimal.

Clustering vs Classification
  - Clustering is unsupervised (no labels), used to group similar data.
  - Classification is supervised (uses labels), used to assign data to known categories.
  - Optimal clusters found: 5
  - Clear customer segments identified
  - Visualizations included:
    - Elbow Method Plot
    - Clustered Scatter Plot of Income vs Spending Score
  - Inertia: For assessing compactness of clusters.
  - Silhouette Score: For evaluating how well-separated and dense the clusters are.

The main goal is to segment customers into groups with similar behaviors for better marketing strategies and personalized services.
