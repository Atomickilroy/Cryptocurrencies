# Cryptocurrencies
 
## Overview of Project
 
#### *Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.*
 
<!--![mobile](https://github.com/Atomickilroy/Credit_Risk_Analysis/blob/main/png/Screenshot%202022-09-17%20124821.png) -->
 
 
## Purpose
 
**The purpose of this project was to start learning tools that work hand and hand with Unsupervised Machine Learning:**
 
    - Describe the differences between supervised and unsupervised learning, including real-world examples of each.
    - Preprocess data for unsupervised learning.
    - Cluster data using the K-means algorithm.
    - Determine the best number of centroids for K-means using the elbow curve.
    - Use PCA to limit features and speed up the model.
 
## Results:  
 
### Preprocessing the Data for PCA:
 
    Using  Pandas, to preprocess the dataset:
 

![mobile](https://github.com/Atomickilroy/Cryptocurrencies/blob/main/images/d1.png)    
 
 
 
The preprocessing step gets the data set ready to be used for the unsupervised ML algorithms. Algorithms like K-means and Hierarchical Clustering only use numerical data so it's important to drop the unnecessary string columns and encode the ones that need to be used.
 
###  Reducing Data Dimensions Using PCA:

#### Elbow Curve
![mobile](https://github.com/Atomickilroy/Cryptocurrencies/blob/main/images/bokeh_plot%20(2).png)
 
 
 
PCA is a statistical technique to speed up machine learning algorithms when the number of input features (or dimensions) is too high. PCA reduces the number of dimensions by transforming a large set of variables into a smaller one that contains most of the information in the original large set.
 
 
### Clustering Cryptocurrencies Using K-means:

    Using the K-means algorithm to cluster the cryptocurrencies using the PCA data

![mobile](https://github.com/Atomickilroy/Cryptocurrencies/blob/main/images/d3%20clustering.png)    
 
   
 
 
###  Visualizing Cryptocurrencies Results:

    -  Visualize the distinct groups that correspond to the three principal components

 Plotly Express 3D scatter plot

![3-d](https://github.com/Atomickilroy/Cryptocurrencies/blob/main/images/newplot%20(3).png)
 
  Hvplot Scatter Plot 
 
![cluster](https://github.com/Atomickilroy/Cryptocurrencies/blob/main/images/bokeh_plot%20(1).png)
 
 
 
 
 
 
## ***Not Financial Advice***
