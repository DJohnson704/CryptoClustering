# CryptoClustering
Crypto Clustering Project
Overview
This project aims to perform cluster analysis on a dataset of cryptocurrency price changes. By applying dimensionality reduction techniques (such as PCA) and clustering algorithms (like K-Means), the goal is to group similar cryptocurrencies based on their performance over various time periods.

Files in the Repository
Crypto_Clustering.ipynb: The main Jupyter notebook that contains the code for data loading, preprocessing, clustering, and visualization.
Crypto_Clustering-checkpoint.ipynb: A checkpoint of the notebook to save progress periodically.
crypto_market_data.csv: The dataset containing market data for various cryptocurrencies, such as price changes over 24 hours, 7 days, 30 days, etc.
Dataset Description
The crypto_market_data.csv file contains the following key columns:

coin_id: Unique identifier for each cryptocurrency.
price_change_percentage_24h: Percentage price change in the last 24 hours.
price_change_percentage_7d: Percentage price change in the last 7 days.
price_change_percentage_14d: Percentage price change in the last 14 days.
price_change_percentage_30d: Percentage price change in the last 30 days.
price_change_percentage_60d: Percentage price change in the last 60 days.
price_change_percentage_200d: Percentage price change in the last 200 days.
price_change_percentage_1y: Percentage price change in the last year.
Project Workflow
Data Preprocessing:

Load the dataset and clean missing or irrelevant data.
Standardize the numerical features to ensure uniform scaling.
Dimensionality Reduction:

Apply Principal Component Analysis (PCA) to reduce the number of features while preserving most of the variance in the data.
K-Means Clustering:

Perform K-Means clustering on the dataset using different numbers of clusters (k).
Use the Elbow Method to determine the optimal number of clusters by plotting the inertia values against the number of clusters.
Visualization:

Visualize the clustering results using scatter plots to observe how cryptocurrencies are grouped together.
Compare the clusters generated from the original data and PCA-reduced data.
Key Results
Cluster Analysis: The project identified different clusters of cryptocurrencies based on their market performance over varying time periods.
Dimensionality Reduction: PCA was effective in reducing the feature space while retaining important patterns in the data.
K-Means Clustering: The Elbow method helped identify the optimal number of clusters to group similar cryptocurrencies.
Conclusion
This project demonstrates how to apply clustering techniques to cryptocurrency market data to group similar assets. The use of dimensionality reduction (PCA) helps improve computational efficiency while preserving the integrity of the data for clustering. The clusters reveal distinct groups of cryptocurrencies with similar performance characteristics.