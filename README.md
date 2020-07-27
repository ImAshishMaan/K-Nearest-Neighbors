# K-Nearest-Neighbors
A Program to explain K Nearest Neighbors (KNN) concept of machine learning.<br>
KNN is a non-parametric, lazy learning algorithm. Its purpose is to use a database in which the data points are separated into several classes to predict the classification of a new sample point.

#### Non-parametric!!
Non-parametric means that it does not make any assumptions on the underlying data distribution or we can say, the model structure is determined from the data.

# KNN Working
KNN works by finding the distances between a query and all the examples in the data, selecting the specified number examples (K) closest to the query, then votes for the most frequent label (in the case of classification) or averages the labels (in the case of regression).<br>
![1 2zYNhLc522h0zftD1zDh2g](https://user-images.githubusercontent.com/56478257/88501908-804c4380-cfea-11ea-93d6-c6f07a4b0d83.png) <br>
In the above example of k-NN classification. The test sample (inside circle) should be classified either to the first class of Yellow circle or to the second class of purple circles. If k = 3, it is assigned to the class B because there are 2 circles in K=3 range and only 1 circle of class A. If, for example k = 6, it is assigned to the class A (4 circles vs. 2 circles).

# More Study
Just for reference, this is “where” KNN is positioned in the algorithm list of scikit learn. BTW, scikit-learn documentation is amazing! Worth a read if you’re interested in machine learning.
![ml_map](https://user-images.githubusercontent.com/56478257/88502318-b0e0ad00-cfeb-11ea-985a-95c6bbfca2a1.png) <br>

# CASE STUDY
The data in the notebook is anonymised classified data. So, we don't know what the numbers represent or we also don't know what those columns represent.
We just know that we need to use these features that are unknown to us in order to predict a target class 1 or 0.

# Libraries Used
NumPy <br>
pandas<br>
matplotlib<br>
sklearn<br>
seaborn<br>

# Usages
The notebook includes all the markdowns which explain all the process. <br>

# Example
#### Final result.
![3](https://user-images.githubusercontent.com/56478257/88502486-349a9980-cfec-11ea-89f1-b3a5ca283b81.PNG)
#### Elbow method graph to pick a good K Value.
![1](https://user-images.githubusercontent.com/56478257/88502487-36645d00-cfec-11ea-8a4b-bab62e10cb54.PNG)


