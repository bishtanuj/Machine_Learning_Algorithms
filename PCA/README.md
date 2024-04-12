# _Principal Component Analysis (PCA)_

_**Principal Copmonent Analysis (PCA)** is a linear dimensionality reduction technique with applications in exploratory data analysis, visualization, and data preprocessing._

### Overview
- PCA transforms the original data into a **new coordinate system** where the directions (principal components) capturing the largest variation in the data are easily identified.
- The principal component are **orthogonal axes** that maximize the variance in the projected data.
- It's commonly used when variables are highly correlated, aiming to reduce their number while preserving information.

### Working
- The **first principal component** explains the most variance in the data.
- Subsequent components explain the remaining variance after removing the effect of the previous components.
- Iteratively, we find orthogonal directions that capture the most information.
