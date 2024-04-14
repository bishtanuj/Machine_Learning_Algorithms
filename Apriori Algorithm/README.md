# _Apriori Algorithm_

_**Apriori Algorithm** is a classic data mining technique primarily used for **association rule mining**. It helps discover interesting relationships between variables in large databases._

### Overview
- The Apriori algorithm aims to find **frequent itemsets** in a dataset.
- It's named "Apriori" because it uses prior knowledge of frequent itemset properties.
- The algorithm follows an **iterative approach** or level-wise search to find k-frequent itemsets and generate association rules.

### Apriori Property
- All non-empty subsets of a frequent itemset must also be frequent.
- This property helps reduce the search space during level-wise generation of frequent itemsets.

### Algorithm Steps
- **Step 1 (K = 1)**:
    - Create a table containing the **support count** of each item (called C1, the candidate set).
    - Compare the support count of candidate set items with the **minimum support count** (min_support). Remove items with support counts below min_support to obtain itemset L1.
- **Step 2 (K = 2)**:
    - Generate candidate set C2 using L1 (join step).
    - Check if all the subsets of an itemset are frequent. Remove itemsets with non-frequent subsets.
    - Find the support count of the remaining itemsets by searching in the dataset.
    - Compare the candidate (C2) support count with min_support to obtain itemset L2.
- **Step 3 (K = 3 and beyond)**:
    - Generate candidate set C3 using L2 (join step).
    - Check if all subsets of these itemsets are frequent. Remove non-frequent itemsets.
    - Find all support count of the remaining itemsets.
    - Compare the candidate (C3) support count with min_support to obtain itemset L3 and so on.
 
### Applications
- **Market Basket Analysis**: Identifying associations between products purchased together.
- **Recommendation System**: Suggesting related items based on user behavior.
- **Web Usage Mining**: Analyzing user navigation patterns.

> _Remember, the Apriori algorithm helps uncover hidden patterns and associations in data, making it a valuable tool for decision-making!_

### Minimum Support Threshold
_Choosing the **minimum support threshold** in the Apriori algorithm is crucial for discovering frequent itemsets. Let's break it down:_

1. **Understanding Minimum Support**:
    - The minimum support represents the **minimum occurrence frequency** required for an itemset to be considered frequent.
    - It's expressed as a **percentage** or an **absolute count** of transactions.
    - Frequent itemsets are those that meet or exceed this minimum support.
2. **Steps to Choose the Minimum Support Threshold**:
    - **Percentage-Based Approach**:
        - If you're given a percentage (e.g., $60%$), follow these steps:
            1. Determine the total number of transactions in your dataset.
            2. Calculate the minimum support count by multiplying the percentage by the total number of transactions.
            3. For example, if you have 10 transactions and the minimum support is $60%$, the minimum support count would be $10 * 60$$%$ $= 6$.
      
      
