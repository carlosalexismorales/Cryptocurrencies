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


<img width="1008" alt="Screen Shot 2022-09-28 at 9 40 40 PM" src="https://user-images.githubusercontent.com/102444078/192940399-5cfaed71-407e-4949-9ff8-c7a61f148b80.png">





<img width="1011" alt="Screen Shot 2022-09-28 at 9 40 57 PM" src="https://user-images.githubusercontent.com/102444078/192940438-828d9e2c-7783-410b-8e0e-5383287acb99.png">





<img width="1002" alt="Screen Shot 2022-09-28 at 9 41 11 PM" src="https://user-images.githubusercontent.com/102444078/192940476-947626bc-552c-404e-8b0c-9ff106c29615.png">



<img width="1016" alt="Screen Shot 2022-09-28 at 9 41 29 PM" src="https://user-images.githubusercontent.com/102444078/192940527-d9d82b22-7517-47c9-9597-773ef75d7b94.png">





<img width="1016" alt="Screen Shot 2022-09-28 at 9 41 44 PM" src="https://user-images.githubusercontent.com/102444078/192940556-90e89833-9543-48c7-acb1-0c7a15c3b8e6.png">






### Reducing Data Dimensions Using PCA

The images below show the code used for reducing dimensions 



<img width="1012" alt="Screen Shot 2022-09-28 at 9 42 20 PM" src="https://user-images.githubusercontent.com/102444078/192940623-f3bdb58f-36fa-49ef-a13a-7f36a965a111.png">









### Clustering Crytocurrencies Using K-Means

The images below show the elbow curve. The optimal number of clusters was determined to be 4. 





<img width="1004" alt="Screen Shot 2022-09-28 at 9 43 17 PM" src="https://user-images.githubusercontent.com/102444078/192940725-f1cfd254-f19b-4ab0-9cf5-9c74290d405f.png">








### Visualizing Cryptocurrencies Results

The images below show the 3D plot and scatter plot and hvTable. 


<img width="1015" alt="Screen Shot 2022-09-28 at 9 44 31 PM" src="https://user-images.githubusercontent.com/102444078/192940875-06634408-4f92-44fa-90f6-7bc82ad8254a.png">




<img width="1009" alt="Screen Shot 2022-09-28 at 9 44 47 PM" src="https://user-images.githubusercontent.com/102444078/192940899-727f209e-a0aa-4c2f-8c7d-cbeeafc98232.png">




<img width="1016" alt="Screen Shot 2022-09-28 at 9 45 11 PM" src="https://user-images.githubusercontent.com/102444078/192940963-5567dec5-a816-4e26-b2bc-b9091b208b09.png">






