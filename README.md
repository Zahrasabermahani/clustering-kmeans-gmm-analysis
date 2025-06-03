# clustering-kmeans-gmm-analysis
Clustering individuals using salary, height, weight, and housework time with K-Means and Gaussian Mixture Models (GMM). Gender labels are excluded during training for unbiased grouping.



##  Clustering Analysis with K-Means & GMM

-  **Goal**: Identify natural clusters in a population based on Salary, Height, Weight, and Housecare Time — without using gender labels.
-  **Dataset**: Synthetic data from `exercise5.csv` with M/F labels for later evaluation only.
-  **Algorithms Used**:
  - K-Means (`sklearn.cluster.KMeans`)
  - Gaussian Mixture Model (`sklearn.mixture.GaussianMixture`)
-  **Preprocessing**:
  - Normalization with `StandardScaler`
  - Dimensionality reduction with `PCA` for 2D visualization
-  **Evaluation**:
  - Clusters visualized in PCA space
  - Compared clusters with actual gender to interpret quality
-  **Key Insight**: Even without gender as input, clustering revealed distinct groupings, offering insight into natural structure in data.
