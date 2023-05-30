# Cryptocurrency Clustering

#### Tools Used

* VSCode 1.78
* Python
  * scikitLearn
  * pandas
  * hvplot
  * Plotly

### Overview

This analysis processes the clustering of cryptocurrencies using PCA and K-means. Data was preprocessed using pandas, dimensions reduced using principal component analysis, and clustered using K-means; identifying distinct groups of cryptocurrencies based on their features.

### Results

[elbow image]
By creating and evaluating an elbow curve a cluster total of 4 was chosen.

After implementing our K-means model with 4 clusters, the distribution of our class counts seem to be off.

Class | Count
     0   |  285
     1   |   6
     2   |   1
     3   |  240

The next step was plotting the data to make clearer the classes. 

It became clear the reasons for the "outlier" clusters. The 7 points between those two classes are clearly differentiated between the other 525 coins.

[3d plot]


### Summary

The clusters obtained from this analysis have the potential to provide valuable information, across several demographics, for understanding cryptocurrencies. By looking at these groupings, we can identify different segments within the market and gain insights into their characteristics and behavior. For investors, there is potential in identifying investment opportunities based on the performance of coins within each cluster. It also assists in assessing the risk associated with different clusters, as coins within the same cluster may exhibit similar risk profiles. They can provide insights into which types of cryptocurrencies are more popular or widely used. Additionally, these clusters can be useful for regulators and policymakers to better understand the nature of cryptocurrencies and develop appropriate regulations and policies. Overall, the clusters obtained through this analysis have the potential to offer valuable information for investors, market participants, and regulatory bodies, to make informed decisions and gain a deeper understanding of the cryptocurrency ecosystem.
