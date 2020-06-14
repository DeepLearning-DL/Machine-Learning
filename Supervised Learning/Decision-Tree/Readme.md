Decision Tree is a Supervised learning technique.
It can be used for both classification and Regression problems, but mostly it is preferred for solving Classification problem.
In a Decision tree, there are two nodes, which are the Decision Node and Leaf Node. 
Decision nodes are used to make any decision and have multiple branches, whereas Leaf nodes are the output of those decisions and do not 
contain any further branches.

There are various parameters on which the algorithm depends these parameters are called as hyperparameters.

Hyperparameters for Decision Trees are as follows:
1). Maximum Depth
 The maximum depth of a decision tree is simply the largest possible length between the root to a leaf. A tree of maximum length k can 
 have at most 2^k  leaves.

2). Minimum number of samples to split
A node must have at least min_samples_split samples in order to be large enough to split. 
If a node has fewer samples than min_samples_split samples, it will not be split, and the splitting process stops.