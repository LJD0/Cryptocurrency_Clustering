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

<img alt='elbow image' style='width: 80vw' src='https://raw.githubusercontent.com/LJD0/Cryptocurrecy_Clustering/main/Output/ellbow_curve.png'>

By creating and evaluating an elbow curve a cluster total of 4 was chosen.

After implementing our K-means model with 4 clusters, the distribution of our class counts seem to be off.

<table>
  <tr>
    <th>Class</th>
    <th>Count</th>
  </tr>
  <tr>
    <td>0</td>
    <td>285</td>
  </tr>
  <tr>
    <td>1</td>
    <td>6</td>
  </tr>
  <tr>
    <td>2</td>
    <td>1</td>
  </tr>
  <tr>
    <td>3</td>
    <td>240</td>
  </tr>
</table>


The next step was plotting the data to make clearer the classes. 

It became clear the reasons for the "outlier" clusters. The 7 points between those two classes are clearly differentiated between the other 525 coins.

<img alt='cluster graph' style='width: 80vw' src='https://raw.githubusercontent.com/LJD0/Cryptocurrecy_Clustering/master/Output/cluster_graph.png'>


### Summary

The clusters obtained from this analysis have the potential to provide valuable information, across several demographics, for understanding cryptocurrencies. By looking at these groupings, we can identify different segments within the market and gain insights into their characteristics and behavior. For investors, there is potential in identifying investment opportunities based on the performance of coins within each cluster. It also assists in assessing the risk associated with different clusters, as coins within the same cluster may exhibit similar risk profiles. They can provide insights into which types of cryptocurrencies are more popular or widely used. Additionally, these clusters can be useful for regulators and policymakers to better understand the nature of cryptocurrencies and develop appropriate regulations and policies. Overall, the clusters obtained through this analysis have the potential to offer valuable information for investors, market participants, and regulatory bodies, to make informed decisions and gain a deeper understanding of the cryptocurrency ecosystem.
