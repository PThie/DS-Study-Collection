# K-means clustering

## General notes

- unsupervised learning
- partioning clustering method
- does not require labeled data
- is not a classification algorithm

## Steps

1. Select number of cluster (_k_)
2. Randomly select _k_ data points ($\hat{=}$ initial clusters)
3. Measure the distance between each point and the initial clusters
4. Assign each point to nearest cluster
5. Calculate the mean of each cluster
6. Repeat and use the mean values as new cluster centroids 