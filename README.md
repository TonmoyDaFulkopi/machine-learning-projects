﻿# machine-learning-projects

 ## Assignment-1

 Data processing cleans and prepares raw data, removing errors and inconsistencies. Feature
 engineering creates new, meaningful variables from the data to help the model learn better.
 These steps are important for improving accuracy and reliability in machine learning models.
 In this assignment, you will learn the basic steps of importing a dataset into for a machine
 learning project, preprocessing the different variables of the dataset, removing missing values
 and redundancies, converting non-numerical variables into numeric format, normalization of the
 data ,correlation analysis of different variables with the targeted output, and selection of
 important features from the dataset for finally fitting a dataset into a machine learning pipeline.
 Please note that you can use python library functions for this assignment.
 Required Dataset:
 In this assignment we will use the “IBM HR Analytics Employee Attrition & Performance”
 dataset. You can download the dataset from the following link:
 https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-datase

 ## Assignment-2

 Introduction  
In ensemble learning, we combine decisions from multiple learners to solve a classification 
problem. In this assignment, you will implement a Logistic Regression (LR) classifier with 
bagging and stacking.  
Programming Language/Platform  
 Python 3 [Hard requirement]  
Dataset preprocessing 
You need to demonstrate the performance and efficiency of your implementation for the 
following three different datasets.  
1. https://www.kaggle.com/blastchar/telco-customer-churn 
2. https://archive.ics.uci.edu/ml/datasets/adult 
3. https://www.kaggle.com/mlg-ulb/creditcardfraud 
They differ in size, number and types of attributes, data quality (missing attribute values), data 
descriptions (whether train and test data are separate, attribute description format, etc.), etc. Your 
core implementation for LR, bagging and stacking must work for all three datasets without any 
modification. You should add a separate dataset-specific preprocessing script/module/function to 
feed your learning engine a standardized data file in matrix format. On the evaluation day, you 
will be given another new dataset for which you must create a preprocessor. Any lack of 
understanding about your own code will severely hinder your chances of success. Here are some 
suggestions for you, 
1. Design and develop your own code. You can take help from tons of materials available on 
the web, but do it yourself. This is the only way to ensure you know every subtle issue 
that needs to be tweaked during customization. 
2. Do not assume anything about your dataset. Keep an open mind. Deal with their subtleties 
in preprocessing. 
3. Use Python library functions for common preprocessing tasks such as normalization, 
binarization, discretization, imputation, encoding categorical features, scaling etc. 
Visithttp://scikit-learn.org/stable/modules/preprocessing.html for more information. 
4. Go through the dataset description given in the link carefully. Misunderstanding will lead 
to incorrect preprocessing. 
5. For the third dataset, don’t worry if your implementation takes long time. You can use a 
smaller subset (randomly selected 20000 negative samples + all positive samples) of that 
Page 1 of 3 
Document Version: 2024/09/12/02 
dataset for demonstration purpose. Do not exclude any positive sample, as they are 
scarce. 
6. Split your preprocessed datasets into 80% training and 20% testing data when the dataset 
is not split already. From the training set, separate out 20% data for validation. You can 
use the Scikit-learn built-in function for the train-test split. For splitting guidelines, see 
https://developers.google.com/machine-learning/crash-course/training-and-test
sets/splitting-data.


## Assignment-3

 Introduction
 In this assignment, you will have to implement a Feed-Forward Neural Network (FNN) from
 scratch and apply your FNN to classify apparel.
 Basic ComponentsoftheNetwork
 ● Dense Layer: A fully connected layer, defined by the dimensions of its input and
 output.
 ● Normalization: Batch Normalization
 ● Activation: ReLU
 ● Regularization: Dropout
 ● Optimization: Adaptive Moment Estimation (Adam)
 ● Regression: Softmax for Multi-class Classification
 Write separate classes for each of the aforementioned building blocks. Vectorize your code
 whenever possible to speed up training and inference. Modularize your code well, set
 up the architecture in one place such that it is trivial to change the model architecture later
 on (for possible online tasks or retraining).
 You will have to implement the backpropagation algorithm to train the model. The weights
 will be updated using mini-batch gradient descent with Adam optimization. No deep
 learning framework will be allowed for your implementation. Since the architecture is
 not fixed, you have to modularize your code in such a way that it works for any architecture
 that uses the aforementioned modules. To make your implementation efficient, you have to
 write each operation as matrix multiplication, whenever possible.
 For preparing, training and testing your model, write your codes in a jupyter notebook
 named as <YourRollNo>.ipynb. Clearly mention the separate blocks used for data loading,
 cleaning, building the architecture, training, validation, testing etc.


## Assignment-4

 Introduction
 Principal component analysis (PCA) and the expectation-maximization (EM) algorithm are
 two of the most widely used unsupervised methods in machine learning. In this
 assignment, you will implement PCA for dimensionality reduction and implement the EM
 algorithm for the Poisson mixture model.
 Principal component analysis (PCA)
 Dataset: You are given a space separated file titled “pca_data.txt” to be used as the dataset
 for this. The file contains 1000 rows and 500 columns. The 1000 rows correspond to 1000
 sample points and each sample is represented by a 500 dimensional feature vector.
 Tasks:
 ● Write code to perform PCA. You can call library functions to perform matrix
 operations such as eigendecomposition but do not call library functions to perform
 the entire PCA.
 ● Nowproject your data along the two eigenvectors corresponding to the two highest
 eigenvalues and create a 2D scatter plot showing the data.
 ● Uselibraryfunctions to create UMAP and tSNE plots of the original data
 Expectation-maximization (EM) algorithm
 Dataset: You are given a space file titled “em_data.txt” to be used as the dataset for this. The
 file contains 1000 rows. The 1000 rows correspond to the number of children in 1000
 (hypothetical) families.
