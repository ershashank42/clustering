# clustering data using k means algorithm and
# agglomerative hierarchical clustering
k-means clustering algorithm is used to cluster the data points into certain clusters with the help of euclidean distance. 
Firstly, random centroids of clusters are selected and then the euclidean distance is calculated for each data point from each of the random centroids and cluster membership is assigned to it. Then we calculate the centroid of each cluster in which the data points are assigned to. Then again we calculte the euclidean distance of each data point from the updated centroid values and again new cluster membership is assigned. The process goes on until the cluster membership does not change even for a single data point. Finally all the data points are assigned to a cluster.

Agglomerative hierarchical clustering algorithm is also a kind of clustering. It consists of many methods by which clustering can be done for given data points. The method which I have implemented is single linkage clustering. In this method we make proximity matrix for the given data points which consists of the distance between two points. The we find minimum distance and cluster those two points and again proximity matrix is calculated for the data points. The process is repeated until one single cluster is obtained.

Depending upon the order of the clustering of the data points. Dendrogram is made which is pictorial representation of the clustering order of the data points.

If someone wants to obtain clustering with other methods like complete linkage or average linkage or ward's method, then one can replace the word 'single' in hierarchical clustering.ipynb with 'complete' or 'average' or 'ward' respectively.
