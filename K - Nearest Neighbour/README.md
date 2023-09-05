# K - Nearest Neighbour Algorithm
* It is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. 
* The algorithm is used when the datapoints are distributed are distributed non-linearly.
* The algorithm is used both for classification and regression.
* In case of outliers or class inbalance problems, KNN can give inaccurate result.
* The distance matrix used in KNN is euclidean distance, which is used to calculate the distance between any two points. <br>
&emsp; Euclidean Distance = $\sqrt{(x2-x1)^2 + (y2-y1)^2}$


## Advantages of KNN
1. KNN is easy to implement.
2. It requires only two parameter, value of K and the distance function.
3. New data can be added easily because it is a lazy learner, because it does no training at all when you supply the training data. At the training time, all it is doing is storing the complete dataset, but it doesn't do any calculation at this point.
4. No assumption about the data.
5. Quick calculation time.


## Disadvantages of KNN
1. It doesnot work well with the high dimension.
2. Computaional complexity increases with increase in the size of the dataset and in turn the speed decreases.
3. KNN is sensitive to noisy data, missing data and outliers. So, we need to manually input the missing values and remove the outliers.
4. Incorrect value of K, can lead to underfitting or overfitting problem.

### NOTE:
***UNDERFITTING:*** A model is said to be in underfitting if the training accuracy is low i.e., model is not able to perform well during the training time.

***OVERFITTING:*** A machine learning model is said to be overfitting if the training accuracy is high and the testing accuracy is low i.e., the model is not able to perform well or capture the variation in the test data.
