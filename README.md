# CryptoClustering

This project is created for the University of Minnesota - Data Visualization and Analytics Bootcamp - Challenge DB

### Contributor : Indu Bandi

# Project Overview

In this project we will use python and unsupervised learning to predict if cryptocurrencies were affected by 24-hour or 7-day price changes.

Dataset for the challenge is under the [Resources](Resources) folder.

# Data Prep

1. Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.
2. Created the dataframe with the scaled data
3. Use K-Means to find the best value of K
4. Cluster Crypto currencies With K-Means using Original Data
5. Optimize Clusters with PCA - Principal Component Analysis
6. Use K-Means to find the best value of K Using PCA Data
7. Cluster Cryptocurrencies with K-means Using the PCA Data


# Analysis

Four clusters were the best configuration. However using PCA , the cluster distribution was more clear.

More description in the jupyter notebook.

# References

1. https://holoviz.org/tutorial/Composing_Plots.html
