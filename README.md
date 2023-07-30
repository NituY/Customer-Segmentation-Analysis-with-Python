# Customer-Segmentation-Analysis-with-Python
In this code, we first load the customer dataset and select the features for clustering ('Age', 'Income', and 'Spending Score'). Then, we standardize the features to ensure they have the same scale. We use the Elbow Method to find the optimal number of clusters (k) based on the inertia (sum of squared distances within each cluster). We plot the Elbow Method graph to visually identify the best k value.

![image](https://github.com/NituY/Customer-Segmentation-Analysis-with-Python/assets/108191093/2e5d6e5e-f79e-4156-9958-7f2a57a8cce7)
Next, we apply K-Means clustering with the chosen k value and assign cluster labels to each customer. Finally, we visualize the clusters in a 2D scatter plot using 'Income' and 'Spending Score' as the x and y-axis, respectively.

![image](https://github.com/NituY/Customer-Segmentation-Analysis-with-Python/assets/108191093/d1f48969-588d-4bba-bec2-f988097fe079)


