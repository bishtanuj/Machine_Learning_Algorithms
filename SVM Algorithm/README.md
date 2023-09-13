# _Support Vector Machine (SVM) Algorithm_
* SVM is a orginally a binary classifiaction method that divides the given data into two groups in the best possibe way by using hyperplanes.
* A support vector machine (SVM) is a discriminitive classifier formally defined by a separarting hyperplane.
* In other words, given labeled training data (supervised learning), the algorithm outputs an optimal hyperplane which categorizes new examples.
* Support Vector Machine is a supervised machine learning algorithm which can be used for both classification and regression.
* Majorly used for classification.


## Support Vector
* Support Vector are data points that are closer to the hyperplane and influence the position and orientaion of the hyperplane.
* Using these support vectors, we maximize the margin of the classifier.
* Deleting the support vectors will change the position of the hyperplane.


## Hyperplane
* Hyperplanes are decision boundaries that help classify the data points.
* Data points falling on either side of the hyperplane can be attributed to different classes.
* In simple term, it is the ability of machine learning model to correctly differentiate/separate/classify between different groups of data. 


## Properties of Support Vector Machine
1. SVM is a maximum separator algorithm.
2. SVM is a kernel based technique.
3. SVM also operates with the high dimensional data and in turn prevents the curse of dimensionality issue.


## Advantages of SVM
1. It works efficiently with non-linear data by using kernel techinque.
2. It can be used for both classification problems as well as regression problems.
3. SVM has regularization features which prevent it from the overfitting problem.
4. SVM is more effective in high-dimesional spaces.
5. It gives us stable model. It means a small change to data doesnot greatly affect the hyperplane.


## Disadvantages of SVM
1. Choosing an appropriate kernel function to handle the non-linear data is not an easy task. It could be tricky and complex.
2. In case of using a high dimensional kernel, you might generate too many support vectors which reduce the training drastically.
3. Extensive memory requirement. Algorithmic complexity and memory requirement of SVM are very high, you need a lot of memory since you have to store all the support vectors also in the memory. 
4. SVM model requires feature scalling.
5. Long training time on large datasets.
6. Difficult to interpret, and difficult to understand by human being unlike decision tree.


## _Some important keywords of SVM_
#### _Linearly Separable Data:_
_Data that can be separate with the equation of line._

#### _Non-linearly Separable Data:_
Data that cannot be separate with the equation of line.

#### KERNEL:
It is used to convert the data from low dimension to high dimension, so that the seapration of data becomes easy.

#### Margin:
Distance between the closest point to hyperplanes of classes.

