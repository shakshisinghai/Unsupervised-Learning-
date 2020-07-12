# Unsupervised Learning
> Training of machine using information that is neither classified nor labeled and allowing the algorithm to act on that information without guidance

## **Unsupervised learning classified into two categories of algorithms:**
* Clustering 
* Association

**K Means Clustering**
> Clustering is the task of dividing the population or data points into a number of groups such that data points in the same groups are more similar to other data points in the same group than those in other groups

**STEPS:**
1. Specify the desired number of clusters K
2. Randomly assign each data point to a cluster
3. Compute cluster centroids
4. Re-assign each point to the closest cluster centroid
5. Re-compute cluster centroids
6. Repeat steps 4 and 5 until no improvements are possible

**Dataset Used:**
1. [make_blobs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_blobs.html)
2. MNIST hand written digits
