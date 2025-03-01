# CryptoClustering
bootcamp Crypto Clustering challenge


To effectively analyze cryptocurrency clusters, first, use the elbow method to determine the optimal number of clusters (k) by plotting inertia values for k values from 1 to 11. Then, apply K-Means clustering to the scaled data, visualize the results with hvPlot, and identify patterns in price changes. Next, optimize clustering using Principal Component Analysis (PCA) by reducing dimensions to three principal components and evaluating the explained variance. Repeat the elbow method on the PCA-transformed data to determine if the best k differs from the original dataset. Compare clustering results from both methods visually to assess the impact of dimensionality reduction.
