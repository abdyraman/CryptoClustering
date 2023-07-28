 In this repo I used unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
Steps accomplished:
1. Found the best value for k using the elbow method and a range from 1 to 11.
2. Clustered cryptocurrencies with K-Means using the optimal k value.
3. Visualized the clusters with a scatter plot using hvPlot.
4. Optimized clusters using Principal Component Analysis (PCA) with n_components=3.
