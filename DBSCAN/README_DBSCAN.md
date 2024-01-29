# DBSCAN - Density-Based Spatial Clustering of Applications with Noise 

# Background
DBSCAN is an incredibly interesting data clustering algorithm, and differs from the other algorithms covered in this repo, because it has the ability to mark points as outliers. With K-Means, the algorithm clusters points together into groups, fitting in all data points. This means that (1) all data is included in a cluster and (2) outliers skew the creation of said clusters. Enter: DBSCAN.

DBSCAN "groups together points that are closely packed together (points with many nearby neighbors), marking as outliers points that lie alone in low-density regions (whose nearest neighbors are too far away)" (https://en.wikipedia.org/wiki/DBSCAN). I still remember how *stoked* I was to first learn about DBSCAN, and I hope that you are currently feeling the same way right now! By plotting points in space nad marking points in lower-density regions as outliers, clusters are able to be more tight-fitting around dense areas of points.

I haven't even mentioned the other (hopefully as exciting to you as it is to me) advantage of DBSCAN. In K-Means, you have to explicitly declare the number of clusters to group data, however DBSCAN automatically registers not only outliers, but also the number of clusters that should be created!

To illustrate this, here is an image from the DBSCAN wiki that shows a plot analyzed with DBSCAN:
![Plotted data, grouped into two groups (blue, green) and numerous outliers](https://en.wikipedia.org/wiki/DBSCAN#/media/File:DBSCAN-density-data.svg)

Two clusters are found, notated as blue and green, with outliers being colored gray. Running this data through a different clustering algorithm would likely result in these clearly visible two groups being possibly split into more than two, or the clusters being drawn differently to include the outlier points.


# Future
As you can tell, I am super excited about DBSCAN. I'm planning on polishing off this repo more and possibly expanding it to cover HDBSCAN (Hierarchical DBSCAN, https://link.springer.com/chapter/10.1007/978-3-642-37456-2_14).
