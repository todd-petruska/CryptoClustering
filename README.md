# CryptoClustering

Background:  Python and unsupervised learning are used to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. 
 
Folder contains the following files:  

* CryptoClustering.ipynb  

* Resources folder   

* crypto_market_data.csv

The code uses StandardScaler() module from scikit-learn to normalize data from the csv file, then creates a DataFrame indexed on the "coin_id".  The elbow method is used to determine the best value for "k".  Cryptocurrencies are clustered for the best value of "k" using the original scaled data and creates a scatterplot using hvPlot. 
The original scaled data is used to perform a principal component analysis (PCA) and reduce the features to three principal components.   The elbow method is used on the PCA data to find the best value for "k" and a line chart depicts the inertia values computed with the different values of "k" to visually identify the optimal value for "k".
Lastly, clusters are created for cryptocurrencies for the best value of "k" based on the PCA data, which creates a scatterplot using hvPlots. 

Resources:  Resources and code used for this project includes Instructor provided starter code, Office hours, course materials, geeksforgeeks, StackOverflow, GitHub, and holoviz.org. 
