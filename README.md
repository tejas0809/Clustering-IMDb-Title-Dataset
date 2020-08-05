# Clustering-IMDb-Title-Dataset
Clustering using Online K-means and K-means++ for IMDb dataset

## Summary
1. Performed feature engineering followed by clustering of movies in IMDb Title Dataset to cluster similar movies together.
1. Formalized the clustering problem as an optimization problem and used minibatch gradient descent to update the centers, and learnt them in an online manner, thereby improving performance than the usually used Lloyd's Algorithm.
1. Incorporated adagrad like learning rate for different centroids, based on the centroid being the nearest centroid to the points within the mini batch, therfore ensuring faster convergence.
1. Further improved the algorithm by using K Means++ initialization technique, based on picking successive centroids from a frequency distribution, proportional to the square of the distance between datapoints and the nearest centroid, which increases convergence rates and gives a better spread of centroids.

## Please refer to the attached PDF report for detailed analysis and plots. 
