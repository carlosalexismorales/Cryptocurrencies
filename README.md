# Cyptocurrencies


## Project Overview

The purpose of this project is to analyze cryptocurrency data using Unsupervised Machine Learning. The original cryptocurrency data from CryptoCompare is preprocessed using Pandas to fit Unsupervised Machine Learning models. A clustering algorithm is used to group data and hvPlot visualization are used to share results.


## Challenge Overview

1. Preprocessing the Data for PCA
2. Reducing Data Dimensions Using PCA
3. Clustering Cryptocurrencies Using K-means
4. Visualizing Cryptocurrencies Results



## Results


### Preprocessing the data for PCA

The images below describe several steps for preprocessing such as:
 - All cryptocurrencies that are not being traded are removed
 - The 'IsTrading' column is dropped 
 - All the rows that have at least one null value are removed
 - The 'CoinName' column is dropped
 - A new DataFrame is created that stores all cryptocurrency names from the CoinName column and retains the index from the crypto_df DataFrame
 - The get_dummies() method is used to create variables for the text features, which are then stored in a new DataFrame, X
 - The features from the X DataFrame have been standardized using the StandardScaler fit_transform() function







### Reducing Data Dimensions Using PCA

The images below show the code used for reducing dimensions 





### Clustering Crytocurrencies Using K-Means

The images below show the elbow curve...






### Visualizing Cryptocurrencies Results

The images below show the 3D plot and scatter plot 



## Summary
