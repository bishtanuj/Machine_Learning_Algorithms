# _K - Mean Algorithm_
- It is a clustering algorithm - an unsupervised learning approach.
- Aims to partition 'n' observations into K clusters in which each observation belongs to the cluster with the nearest mean, serving as a prototype of the cluster.
- K - Mean falls under the category of centroid based clustering.
- The three required information to proceed in the algorithm are as follows - <br>
&emsp; _n = number of instances_ <br>
&emsp; _k = number of clusters_ <br>
&emsp; _t = number of iterations_ 

## _Steps of Algorithm_
### Step 1: Choose the value of Hyperparameter (k)

### Step 2: Choose the cluster centres
- Randomly select any k data points as cluster centers.
- Select cluster centres in such a way that they are as farther as possible from each other.

### Step 3: Compute the distance between cluster centres and data instances
- Calculate the distance between each data point and each cluster center.
- The distance may be calculated either by using given distance function (like Euclidean distance or Manhattan distance formula). <br>
&emsp; Euclidean Distance = $\sqrt{(x2-x1)^2 + (y2-y1)^2}$ <br>
&emsp; Manhattan Distance = $\|x2 - x1| + |y2 - y1|$

### Step 4: Assignment of data instance to cluster on the basis of minimum distance
- Assign each data point to some cluster.
- A data point is aaigned to that cluster whose center is nearest to that data point.

### Step 5: 
- Re - compute the center of newly formed cluster.
- The center of a cluster is computed by taking mean of all the data points contained in that cluster.

### Step 6:
- Keep repeating the procedure from Step 3 to Step 5 until any of the following stopping criteria met: <br>
    - Center of newly formed clusters do not change.
    - Data points remain present in the same cluster.
    - Maximum number of iterations are reached.

---
