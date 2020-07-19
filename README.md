# NCTU-Pattern-Recognition

## Introduction
These are work on class "Pattern-Recognition" in National Chiao Tung University. In this repository, serveral machine learning approach are implemented without directly using the existing package.

## Dataset
Following are the dataset we use in our assignment:
* [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
* [banknote authentication Data Set](https://archive.ics.uci.edu/ml/datasets/banknote+authentication)
* [Wine Data Set](https://archive.ics.uci.edu/ml/datasets/Wine)
* [Iris Data Set](https://archive.ics.uci.edu/ml/datasets/Iris)

## Topic of each assignment
### Prog1
In this assignment, we are going to implement the following classifier:
* Bayesian classifier: use Gaussian pdfs with parameters given by maximum-likelihood estimation.
* Naive-Bayes classifier
* Linear classifiers by perceptron algorithm (only to be applied to two-class datasets)

Also, we will implement the following evaluation method:
* Calculation of accuracy
* Confusion matrices
* ROC curves (as well as AUCs) 

### Exam1
In this assignment, we are going to use [libsvm](https://www.csie.ntu.edu.tw/~cjlin/libsvm/) for the two-class data in previous assignment. We will implement function to plot the boudary, and see how parameters of SVM affect this.

### Prog2
In this assignment, we are going to implement the following feature reduction method:
* LDA
* PCA

Also, we will experiment on face dataset for gender classification and face recognition, respectively, after PCA is applied to the images.

### Prog3
In this assignment, we are going to implement the clustering algorithms of the c-means family: HCM, FCM, and PCM.