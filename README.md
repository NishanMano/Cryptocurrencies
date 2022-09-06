# Cryptocurrencies: 

This project is dealing with an investment bank looking to offer a new cryptocurrency investment portfolio for its customer. They have requested to have the numerous cryptocurrencies can be grouped to create a classification system for the new investment. This request doesn't really identify any known outputs, therefore we would have to use unsupervised learning to analyze a database of cryptocurrencies. 

Methods Used:
1. Preprocess the database provided
2. Use the Principal Component Analysis to reduce the data dimension to three components
3. Use the K-means method to cluster our data
4. Provide visual classification results through 2D and 3D scatter plots


## Data Visualization: 


1. ![ElbowCurve](https://i.ibb.co/Kx3q63X/K-Means-Elbow-Curve.png) 

This K-Means Elbow Curve model shows us that we had 4 various clusters out of our 532 tradable cryptocurrencies. We used this graph to determine the  number of clusters that would be optimal to categorize our cryptocurrencies. We will use this information to help build our 3D scatter plot. 


2. ![3DScatterPlot](https://i.ibb.co/7C1HdLt/3-D-Scatter-Plot.png)

We used the Principal Component Analysis (PCA) to reduce our cryptocurrency dimensions to three principal components. 

3. ![2DScatterPlot](https://i.ibb.co/BwT1sjX/Tradable.png)

This 2D scatter plot does not provide us with a valuable insight on the differences between the classes. The two cryptocurrency features shown in this graph are: 

(a) TotalCoinSupply

(b) TotalCoinsMined

## Summary:
We can use these clustering results as inputs when building our neuron networks for training our machine learning model. 
