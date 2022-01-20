- proximity measure
    - measurement of dissimilarity (distance)
- criterion function
    - evaluation of the clustering
        - within-cluster variation should be small
        - intra-cluster variation should be large
___
1. Select number of cluster, K
2. Initialize the k number of vectors (centroid) at random position
3. While the position centroid is not fixed:
    - For each data point, calculate its distance to the centroid and assign them to the nearest cluster.
    - Update the value of centroid with mean of all data points of the cluster
4. Determine optimal K using Elbow Method
    - Choose the elbow point by calculating intraclass variation/ total within-cluster sum of square, WSS 


