# Cryptocurrencies
## Overview :

A prominent investment bank is interested in offering a new cryptocurrency investment portfolio to its clients. The firm, however, is bewildered with the vast universe of cryptocurrencies and is requesting a report that includes which cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment product.


## Results: 

The data was not ideal and required reprocessing to use in machine learning models.  Furthermore,  outputs were unknown, so the unsupervised learning technique was applied with clustering algorithms.



- ### Preproscessing Data for Principal Component Analysis ('PCA')
For data processing, the focus was on making sure the data was set up for the unsupervised learning model, which required the following:

    1. Removing null values
    2. Using only numerical data
    3. Ensuring a normalize scale for the data

**Crypto Data Input:** *1,143* records from the data file.

**Crypto Data Output:** After preprocessing the data, only *531* records remained from the original data file.


- ### Reducing Data Dimensions using PCA

PCA is a statistical technique to speed up machine learning algorithms when the number of input features (or diemensions ) is too high.  PCA  decreases the number of dimensions by transforming a large set of variables into a smaller one that contains most of the informaiton from the original large set. This technique is often used to make data easy to explore and visualize.

For this exercise, three principal components were created.  These three principal components were transformed into a DataFrame to fit the K-Means:

<img width="1293" src="https://github.com/AQUINT01/Cryptocurrencies/blob/main/images/pca.png">


- ### Clustering Cryptocurrencies using K-Means

K-Means is an unsupervised learning algorithm used to identify and solve clustering issues. It groups the data into K clusters, where belonging to a cluster is based on some similarity, or distance measure to a centroid - a data point that is the arithmetic mean position of all the points on a cluster.




- ### Visualizing Cryptocurrencies Results


**Scatter**
<img width="1293"
src="https://github.com/AQUINT01/Cryptocurrencies/blob/main/images/scatter.png">


**Elbow Curve**
<img width="1293"
src="https://github.com/AQUINT01/Cryptocurrencies/blob/main/images/elbow.png">


**3D**
<img width="1293"
src="https://github.com/AQUINT01/Cryptocurrencies/blob/main/images/3D.png">
