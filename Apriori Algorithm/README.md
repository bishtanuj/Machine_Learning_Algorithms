# _Apriori Algorithm_

_**Apriori Algorithm** is a classic data mining technique primarily used for **association rule mining**. It helps discover interesting relationships between variables in large databases._

### Overview
- The Apriori algorithm aims to find **frequent itemsets** in a dataset.
- It's named "Apriori" because it uses prior knowledge of frequent itemset properties.
- The algorithm follows an **iterative approach** or level-wise search to find k-frequent itemsets and generate association rules.

### Apriori Property
- All non-empty subsets of a frequent itemset must also be frequent.
- This property helps reduce the search space during level-wise generation of frequent itemsets.
