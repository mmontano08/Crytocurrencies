# Crytocurrencies

### Overview:
We are to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for a new investment. Doing so, we will need it to be processed to fit the machine learning models. Since there is no unknown output, we will use unsupervised learning. To group the crytocurrencies we will use clustering algothrim.

Four technical analysis will be delivered:
- Preprocessing the Data for PCA
- Reducing Data Dimensions Using PCS
- Clustering Cryptocurrencies Using K-means
- Visualizing Cryptocurrencies Results

### Results:
#### Crypto DataFrame:
![Module18_CryptoDataFrame](https://user-images.githubusercontent.com/83566868/131614262-4a268cb5-4af3-4938-8d52-0f04fd579fa7.png)

#### PCA DataFrame (we used this to reduce the dimensions to three pricipal components):
![Module18_PCADataFrame](https://user-images.githubusercontent.com/83566868/131614424-0f31eb5d-743c-4d7d-ab47-db69dc833bff.png)

#### Clustered DataFrame:
![Module18_ClusteredDataFrame](https://user-images.githubusercontent.com/83566868/131614554-d8ca2f7f-10db-4ef3-8323-6dc587af3d79.png)

#### Elbow Curve (was created using hvPlot to find the best value for K):
![Module18_ElbowCurve](https://user-images.githubusercontent.com/83566868/131614788-2501ef51-e68e-41f4-bdd2-b50a4d413e4c.png)

#### 3D Scatter plot(each data point shows the CoinName and Algorithm):
![Module18_3DScatterplot](https://user-images.githubusercontent.com/83566868/131615112-e134b8aa-c0ac-4272-830e-a2f433169ea6.png)
