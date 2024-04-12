# _Naive Bayes Classifier_

_Naive Bayes classifiers are a collection of classification algorithms based on Bayes' Theorem. Although they are not a single algorithm, they share a common principle: **every pair of features being classified is independent of each other**_

### Why "Naive"?
- The "naive" part of the name indicates the simplifying assumptions made by the Naive Bayes classifier.
- It assumes that the features used to describe an observation are **conditionally independent**, given the class label.
- Despite this simplification, Naive Bayes remains practical and effective.

### Applications
- **Text Classification**: Naive Bayes is highly used in tasks like spam filtering, sentiment detection, and rating classification.
- **Speed and Prediction**: Its advantage lies in speed and ease of prediction, especially with high-dimensional data.

### Probabilistic Classifier
- Naive Bayes predicts the **probability** of an instance belonging to a class given a set of feature values.
- It assumes that one feature in the model is **independent** of the existence of another feature.
- Each feature contributes to predictions without any relation to other features.
