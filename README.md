
Module: predicting-breast-cancer 
Version: 1.0 
Author: Poojan Patel
Description: Making prediction of presence of breast cancer using Wisconsin breast cancer dataset.  

Dataset obtained from https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

Attribute Information: 

Missing attribute values: none
Class distribution: 357 benign, 212 malignant

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

Python packages used:
1. Numpy
2. Pandas
3. Sklearn


There are two supervised algorithms applied to predict outcome- Logistic Regression and K-nearest neighbours

There are three files present in the repository:
1. Poojan_patel_breast_cancer_wisconsin.ipynb - Applied Logistic regression to predict results (Accuracy- 96.49%)
2. Poojan_patel_breast_cancer_2.ipynb - Applied KNN algorithm to predict results (Accuracy- 73.49%) 
3. data.csv - Dataset file

It can be deduced that Logistic regression model has higher accuracy than KNN for this particular dataset. 




