# K-mean Clustering

Unsupervise ML model which created 5 clusters and predicted or categorized the customer
based on Annual Income and money spend in the mall.

Data consist of the customers Annual Income, Gender, Money spend in the mall who visited the mall.
We find the optimized value of k by using 'Elbow methond' then we predict and made clusters.

<p align="Center">
  <img src="Output/kmeanelbow.png" width="400" height="350">
  <img src="Output/kmeancluster.png" width="400" height="350">
</p>

<p align="Center">
<img src="Output/dendogram.png" width="400" height="350">
<img src="Output/HCoutput.png" width="400" height="350">
</p>

Cluster 1 shows the customers with average salary and average spending so we can categorize these customers as "Balance"
Cluster 2 shows the customer has a high income but low spending, so we can categorize them as "Careful".
Cluster 3 shows the low income and also low spending so they can be categorized as "Sensible"
Cluster 4 shows the customers with low income with very high spending so they can be categorized as "Careless"
Cluster 5 shows the customers with high income and high spending so they can be categorized as "Target", and these customers can be the MOST PROFITABLE CUSTOMERS for the mall owner.
