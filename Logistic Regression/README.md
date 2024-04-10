# _Logistic Regression_

_**Logistic regression** analyzes the relationship between independent features and a **binary** dependent variable (such as yes/no, true/false, spam/not spam). Unlike linear regression, which predicts continuous values, logistic regression predicts **probabilities** within the range of 0 to 1. It's like fitting an "S" - shaped curve (the **sigmoid function**) to the data, allowing us to estimate the likelihood of an instance belonging to a specific class._

### Types of Logistic Regression
- **Binomial**: For binary outcomes (e.g., pass/fail, spam/not spam).
- **Multinomial**: For more than two unordered classess (e.g., animal types: cat, dog, sheep).
- **Ordinal**: For ordered classes (e.g., low, medium, high).

### Why Is Logistic Regression Important?
- **Probability Estimation**: It provides probabilities rather than exact class labels.
- **Interpretability**: Coefficients reveal the impact of each feature on the probability.
- **Foundation for Classification**: Logistics regression serves as a building block for more complex classifiers.

### How Does Logistic Regression Work?
1. **Sigmoid Function (Logistic Function)**:
    - Maps real values to probabilities between 0 and 1.
    - Ensures predictions stay within valid bounds.
    - Threshold (usually 0.5) determines class assignment.
2. **Cost Function**:
    - Measures the difference between predicted and actual values.
    - Maximizes likelihood or minimizes log loss.
  
### Applications of Logistic Regression
- **Spam Detection**: Identifying spam emails.
- **Medical Diagnosis**: Predicting disease presence.
- **Credit Risk Assessment**: Determining creditworthiness.
- **Market Segemntation**: Categorizing customers.
