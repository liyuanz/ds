# ds

K-Nearest Neighbor Algorithm Pseudocode:
Let (Xi, Ci) where i = 1, 2……., n be data points. Xi denotes feature values & Ci denotes labels for Xi for each i.
Assuming the number of classes as ‘c’
Ci ∈ {1, 2, 3, ……, c} for all values of i

Let x be a point for which label is not known, and we would like to find the label class using k-nearest neighbor algorithms.

Procedure:
Calculate “d(x, xi)” i =1, 2, ….., n; where d denotes the Euclidean distance between the points.
Arrange the calculated n Euclidean distances in non-decreasing order.
Let k be a +ve integer, take the first k distances from this sorted list.
Find those k-points corresponding to these k-distances.
Let ki denotes the number of points belonging to the ith class among k points i.e. k ≥ 0
If ki >kj ∀ i ≠ j then put x in class i.
