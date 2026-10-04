
# Customer Segmentation using PCA & K-Means

Unsupervised customer segmentation on the Mall Customers dataset (200 customers; age, gender, annual income, spending score).

- **Methods:** StandardScaler, PCA (2 components, 59.9% variance), K-Means clustering
- **Choosing K:** Elbow Method and Silhouette Score analysis (K=2 to 10); best K=4 (silhouette 0.4164)
- **Output:** 4 customer segments profiled by age, income and spending, each with a suggested marketing action
- **Tech:** Python, scikit-learn, pandas, matplotlib, seaborn
