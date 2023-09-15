# _DECISION TREE_
A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consisits of a root node, branches, internal nodes and leaf nodes.

## _Types of Decision Tree_
There are following types of decision tree algorithms:
1. **ID3:** Stands for "Iterative Dichotomiser 3", developed by Ross Quinlan. This algorithm leverages entropy and information gain as metrics to evaluate candidate splits.
2. **C4.5:** This algorithm is considered a later iteration of ID3, which was developed by Quinlan. It can use information gain or gain ratios to evaluate split points within the decision trees.
3. **CART:** Stands for "Classification and Regreesion Tree" and was introduced by Leo Breiman. This algorithm typically utilizes Gini impurity to identify the ideal attribute to split on. Gini impurity measures how often a randomly chosen attribute is misclassified. When evaluating using Gini impurity, a lower value is more ideal.

## Advantages of Decision Tree
* Easy to interpret
* Little to no data preparation required
* More Flexible

## Disadvantages of Decision Tree
* Prone to overfitting
* High variance estimators
* More Costly
* Not fully supported in scikit-learn
