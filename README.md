# K-means_implementation
This script starting from a number of clusters, generates a random clustering of the objects: then applies iteratively two steps, namely assignment and update until convergence, to identify a proper clustering. The input are number of clusters and a CSV file. In this Jupyter notebook script are implemented two version of k-means: one based on lists (each line of the CSV file is translated into a list) and the other based on numpy vectors (each line of the CSV file is traslated into a numpy vector). 

Additionally the two implementation are tested to see how the performance changes in the two cases depending on the size of the vectors, the number of vectors and the number of clusters.
