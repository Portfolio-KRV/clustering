# Clustering
Developed in the Pattern Recognition in Data Mining course by: Kevin Reyes.
## Objectives
- Compare the clustering algorithms: K-means, hierarchical agglomerative clustering and DBSCAN in three different data sets.
- Identify advantages and disadvantages of each analyzed algorithm.

## Description
Comparative study of clustering algorithms: K-means, hierarchical agglomerative clustering and DBSCAN.

## Conclusions
- K-means recognizes clusters with circular shapes of similar size well, and has no problems with clusters of different densities, however, it fails when there are clusters of different sizes and has difficulties with non-circular clusters or complex shapes such as loops. In addition, the value of K must be found, which might not be easy in a high-dimensional space.
- DBSCAN detects clusters of any shape and of different densities, however, it fails when clusters are joined by outliers.
- HAC detects clusters of complete shapes, however, it is sensitive to outliers that can generate bridges between different clusters. In addition, the most suitable value of K and type of linkage must be found, which might not be easy in a high-dimensional space.

## Technology stack
- Scikit-learn.
- Matplotlib.
- Numpy.
- Pylab.