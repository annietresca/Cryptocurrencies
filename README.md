# Cryptocurrencies

## Overview
This project uses unsupervised machine learning to create a report grouping cryptocurrencies on the trading market. These groupings are going to be used to create a classification system for a new potential investment portfolio for customers at a prominent investment bank.

## Resources
- Data: crypto_data.csv
- Software: Python 3.7.9, Jupyter Notebook 6.0.3
- Methodologies: Unsupervised Machine Learning, Sklearn, Pandas, hvplot

## Results
Please refer to crypto_clustering.ipynb file for full cleaning of the data.


After cleaning the data, there are a total of 532 tradable cryptocurrencies. The following image is an Elbow Curve made using the K-Means method interating on k values from 1 to 10. Based on the location of the curve, it appears that an output of 4 clusters would be best to categorize the cryptocurrency options.
![elbow](https://github.com/annietresca/Cryptocurrencies/blob/main/Resources/elbow%20curve.png)



The following image is a 3D Scatter Plot with Clusters that reduces the number of dimensions to three principal components. As you can see, there are three major groups and one outlier.
![3D](https://github.com/annietresca/Cryptocurrencies/blob/main/Resources/3D%20Scatter%20with%20Clusters.png)



While there are many cryptocurrencies that fall in Class 0 or 1 (and some in Class 3), there is only one cryptocurrency that falls in Class 2 (BitTorrent).
![tradable](https://github.com/annietresca/Cryptocurrencies/blob/main/Resources/tradable.png)


This can also be seen in this 2D Scatter plot visual.
![2D](https://github.com/annietresca/Cryptocurrencies/blob/main/Resources/2D%20Scatter.png)



## Summary
In short, this analysis grouped all tradable cryptocurrencies into 4 groups. In order to make further recommendations, additional analysis is needed. At present, we can confidently say that a majority of profitable cryptocurrencies fall into two categories. 
