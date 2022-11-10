# Cryptocurrencies
unsupervised Machine Learning



## Overview

The purpose of this analysis was to use data retrieved from CryptoCompare to provide a detailed report and show visualizations of currently traded cryptocurrencies that that can be grouping together to create a classification system. This would allow Accountability Accounting the ability to offer a new investment portfolio in the world of cryptocurrency to its customers. We will be preprocessing the data to fit an unsupervised Machine Learning Model that will allow us to run a clustering algorithm that will help us group the currencies.

In this analysis we learned and applied:

  • Preparing Data (Selection, Processing, and Transforming) - the process of helping to prepare data for Machine Learning Algorithms.
  
  • Clustering and the K-means Algorithm - the process of grouping similar objects/data points into clusters.
  
  • Elbow Curve to Find Centroids - method to determine the best number of clusters needed for the algorithm to group the objects by.
  
  • Principal Component Analysis (PCA) - statistical technique to speed up machine learning algorithms when the number of features is too 
    high.
  
  • Visualization (hvPlot, Plotly) - graphic libraries that allows us to create 2D and 3D graphs such as, scatter plots.



## Results

We started out with a dataset that contained 1,252 cryptocurrencies. We then reduced it to 1,144 by only using actively traded currencies. Through data munging we removed usless columns and Null Values, also only leaving currencies that had a total number of mined coins greater than 0. Ending with 532 coins to analyze. 

## 3D-Scatter

<img width="732" alt="3D-Scatter" src="https://user-images.githubusercontent.com/90155651/200984149-e5d41ab3-e527-44fb-81bb-b91d06b74f53.png">


## Tradeable table of cryptocurrencies

<img width="703" alt="Tradeable table of cryptocurrencies" src="https://user-images.githubusercontent.com/90155651/200984260-1eebe30a-721f-45a0-8280-53818cb4051b.png">


## Elbow Curve

<img width="719" alt="elbow curve" src="https://user-images.githubusercontent.com/90155651/200984388-15dd4c09-285f-4d4f-aee2-8d531367f661.png">




## Scatter plot of tradeable Crypto"

<img width="708" alt="Scatter plot of tradeable Crypto" src="https://user-images.githubusercontent.com/90155651/200984501-5d3912cf-e234-4b0a-a28c-d0440d449ce6.png">


