# _Linear Regression_

_**Linear Regression** computes the linear relationship between a **dependent variable** (also known as the response or target variable) and one or more **independent features** (also called explanatory or predictor variables). The goal is to fit a linear equation to observed data, allowing us to make predictions on new datasets._

### Types of Linear Regression:
1. **Simple Linear Regression**: When there's only one independent feature.
2. **Multiple Linear Regression**: Involves more than one feature.
3. **Univariate Linear Regression**: With a single dependent variable.
4. **Multivariate Regression**: With multiple dependent variables.

### Why is Linear Regression Important?
- **Interpretability**: Linear regression provides clear coefficients, helping us understand the impact of each independent variable on the dependent variable.
- **Simplicity**: It's transparent, easy to implement, and serves as a foundation for more complex algorithms.
- **Foundational Concepts**: Linear regression underpins advanced models ike regularization and support vector machines.

### Assumptions of Linear Regression
1. **Linearity**: The relationship between variables is linear.
2. **Independence**: Residual (differences between actual and predicted values) are independent.
3. **Homoscendasticity**: Residuals follow a normal distribution.
4. **Normality**: Residuals follow a normal distribution.

### How Does Linear Regression Work?
1. **Best Fit Line**: Linear regression finds the line that best fits the data points. This line represents the relationship between the features and the target variables.
2. **Cost Function**: The algorithm minimizes the difference between predicted and actual values using a cost function (often mean squared error).
3. **Gradient Descent**: Optimization technique to adjust model parameters (coefficients) iteratively.

### Evaluation Metrics for Linear Regression
- **Mean Absolute Error (MAE)**: Average absolute difference between predicted and actual values.
- **Mean Sqaured Error (MSE)**: Average squared difference.
- **Root Mean Squared Error (RMSE)**: Sqaure root of MSE.
- **R - squared $(R^2)$**:
