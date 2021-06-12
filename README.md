Module: predicting-breast-cancer  
Version: 1.0  
Author: Poojan Patel  
Description: Making prediction of presence of breast cancer using Wisconsin breast cancer dataset.  

Dataset obtained from https://www.kaggle.com/uciml/breast-cancer-wisconsin-data  

:Attribute Information:  

-Missing attribute values: none  
-Class distribution: 357 benign, 212 malignant  

-ID number
-Diagnosis (M = malignant, B = benign) 3-32)
-Ten real-valued features are computed for each cell nucleus:

-radius (mean of distances from center to points on the perimeter)   
-texture (standard deviation of gray-scale values)   
-perimeter  
-area  
-smoothness (local variation in radius lengths)  
-compactness (perimeter^2 / area - 1.0)   
-concavity (severity of concave portions of the contour)  
-concave points (number of concave portions of the contour)  
-symmetry  
-fractal dimension ("coastline approximation" - 1)  

:Python packages used:

-Numpy
-Pandas
-Sklearn

:Module Details  
-There are two supervised algorithms applied to predict outcome- Logistic Regression and K-nearest neighbours

-There are three files present in the repository:

-Poojan_patel_breast_cancer_wisconsin.ipynb - Applied Logistic regression to predict results (Accuracy- 96.49%)  
-Poojan_patel_breast_cancer_2.ipynb - Applied KNN algorithm to predict results (Accuracy- 73.49%)  
-data.csv - Dataset file  

-It can be deduced that Logistic regression model has higher accuracy than KNN for this particular dataset. 
