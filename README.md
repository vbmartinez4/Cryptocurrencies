# Cryptocurrencies-The Market’s Fastest Growing Trend

## Overview
In the recent years there has been an exponential rise of cryptocurrencies, an unregulated financial digital asset that investors are flocking to buy, sell, and trade. What started as a foreign financial investment has now paved a way to an entire universe of a multitude of cryptocurrencies that trade on the global markets daily. We are assisting Martha and her firm, Accountability Accounting, a prominent investment bank, who is interested in offering a new cryptocurrency investment portfolio for its customers. 

## Tools Used:
- Jupyter Notebook 
- Pandas
- Python

## Dataset:
- crypto_data.csv

## Objectives
- Describe the differences between supervised and unsupervised learning, including real-world examples of each.
- Preprocess data for unsupervised learning.
- Cluster data using the K-means algorithm.
- Determine the best number of centroids for K-means using the elbow curve.
- Use PCA to limit features and speed up the model.

## Results
Before we can run any algorithms, we first focus on cleaning and preprocessing the dataset. As we clean the data and filter the dataset to include only numerical values, we then focus to reduce the data dimensions that will assist use in utilizing the Principal Component Analysis (PCA). PCA is a statistical technique that is used alongside machine learning algorithms to speed up their output when there are a large number of input features. Given that we have altered the original dataset and more groups of the columns, PCA reduces the dataset to contain a small set of variables. This is essentially the pathway to using the input to see what results arises from grouping the data and obtain some sort of output.

Once the dimensions are reduced, we look to apply a clustering technique to the dataset, creating groups from out points. To determine the amount cluster for the size of the cryptocurrency data, the elbow curve and K-means algorithm are applied in our analysis. 

For the visualization component of our analysis, we create a scatter plot that depicts the distinct groups that correspond to the three principal components created. Separately, we create a new table depicting all of the currently tradeable cryptocurrencies. 
