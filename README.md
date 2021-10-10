# Cryptocurrencies - Unsupervised Learning

## Overview
This module was to learn about unsupervised machine learning which is used to discover patterns or groups in data. It is unlike supervised learning where there is a known output, unsupervised learning does not have a known output and only uses input data. Information, such as customer segmentation, can be used to offer products to people by grouping customers into different categories. These could be age, geography, gender and many more.

The analysis is around cryptocurrencies and what is available for investment. The lesson included:
* Learning how to process data for an unsupervised learning model.
* Group the data using clustering and K-means algorithm
* Make the models for efficient using principle component analysis

For the challenge we were required to do the following:
* Preprocess the data for PCA
* Reduce data dimensions using PCA
* Clustering cryptocurrencies using K-means
* Visualizing cryptocurrencies results

## Results
After completing deliverable one and two, we were able to cluster the data using the K-means method. We were able to find the best value for K using the elbow curve. The results were that four should be used for the clusters.


![](Resources\elbow_curve.png)

We then initialized the K-means model to produce our predictions and clusters.  Finally, in deliverable four the following were produced from the clusters:

*3d-Scatter Plot*

![](Resources\3d.PNG)

 *Table of Data*

![](Resources\table.PNG)

*An hvplot.scatter*

![](Resources\hvplot.PNG)