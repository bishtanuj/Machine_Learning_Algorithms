# K - Mean Algorithm
- It is a clustering algorithm - an unsupervised learning approach.
- Aims to partition 'n' observations into K clusters in which each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster.
- K - Mean falls under the category of centroid based clustering.
- The three required information to proceed in the algorithm are as follows - <br>
&emsp; 1. n = number of instances <br>
&emsp; 2. k = number of clusters <br>
&emsp; 3. t = number of iterations 

## Steps of Algorithm
### Step 1: Choose the value of Hyperparameter (k)

### Step 2: Choose the cluster centres
- Randomly select any k data points as cluster centers.
- Select cluster centres in such a way that they are as farther as possible from each other.

### Step 3: Compute the distance between cluster centres and data instances
- Calculate the distance between each data point and each cluster center.
- The distance may be calculated either by using given distance function (like Euclidean distance or Manhattan distance formula).
&emsp; Euclidean Distance = $\sqrt{(x2-x1)^2 + (y2-y1)^2}$ <br>
&emsp; Manhattan Distance = |x2 - x1| + |y2 - y1|
