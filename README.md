# AIT 636 | Summary of the project

### Dataset

The dataset comprises of salary of the employee. It contains two data csv format files. Training and testing. 

Training data comtains - records and testing data contains - records. There are - features
The label feature is in binary 0 and 1. 0 is <50k and 1 is >50k

### Problem Statement

To find whether the employee will contain salary above 50k or less than 50k. It is a classification problem. 

### Machine Learning models classification

1. KNN (using classification and regression)
2. Decision Trees (using classification and regresssion)
3. Logistic Regression & Perceptron
4. SVM (linear and non-linear)
5. Multi-layer perceptron Classification (with and without using best subset algorithm)
6. Multi-Layer Perceptron Classification (with and without applying PCA)

### Feature Engineering

#### STEPS
* Removing or cleaning ' ?' data from the dataset. 
* Converting categorical features into numerics. 
* Standardizing the data by removing the noise data. Mapping features and labels into numbers 1 and 0.


### Model Results
> Accuracy Result for Classification:
Logistic Regression -- 74.07
Perceptron -- 73.36
Decision Tree Classifier -- 81.8

![image](https://user-images.githubusercontent.com/51665593/169723385-3c642c8b-2d9f-4f15-9709-f430c1a1b18c.png)

KNN Classification -- 79.94
MLP without PCA -- 81.19
Linear SVC -- 75.45
Non-linear SVC -- 80.11

> Root mean square error (RMSE) results:
Decision Tree Regressor -- 0.37

![image](https://user-images.githubusercontent.com/51665593/169723554-77c46206-03fe-48a3-9332-b2b906d53fb4.png)

KNN Regression -- 0.4
Accuracy of MLP classification model (with PCA) -- 80.93

![image](https://user-images.githubusercontent.com/51665593/169723768-7794d969-9286-4f68-9c1d-ea41fb512c0f.png)

Multi-linear Perceptron (Find best subset) -- Not yet resolved!!??


