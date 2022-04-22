# Image Classification using K-NN, Logistic Regession and SVM

## Project Description
The purpose of this project is to implement image classification task on MNIST dataset using K-NN, Logistic Regression and SVM.
- We will implement a simple kNN Classifier on the MNIST dataset.
- We will perform binary classification using logistic regression. Just as in Part 1. we will use the MNIST dataset, however to obtain a result for each class using logistic regression we will need to use a One-vs-Rest (OvR) approach to acheive multi-class classification.
- We will use Scikit-learn to perform classification, again on the MNIST dataset. We can use the built in SVM library for classification. As with logistic regression, SVM is designed for binary classification. However, in this case Scikit-learn will handle the OvR models behind the scenes. We will compare different modes of the SVM and determine the best performer.

## K-NN

### K Value vs. Error Rate
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/K-Value-vs-Error-Rate.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/K-Value-vs-Error-Rate.png" width="300" height="300" alt="K Value vs. Error Rate" />

### Classification Report
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/K-NN-Classification-Report.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/K-NN-Classification-Report.png" width="300" height="300" alt="Classification Report" />

### Confusion Matrix
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/K-NN-Confusion-Matrix.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/K-NN-Confusion-Matrix.png" width="300" height="300" alt="Confusion Matrix" />

## Logistic Regression

### Classification Report
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/Logistic-Regression-Classification-Report.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/Logistic-Regression-Classification-Report.png" width="300" height="300" alt="Classification Report" />

### Confusion Matrix
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/Logistic-Regression-Confusion-Matrix.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/Logistic-Regression-Confusion-Matrix.png" width="300" height="300" alt="Confusion Matrix" />

## SVM

### Classification Report
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-Classification-Report.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-Classification-Report.png" width="300" height="300" alt="Classification Report" />

### Confusion Matrix
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-Confusion-Matrix.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-Confusion-Matrix.png" width="300" height="300" alt="Confusion Matrix" />

### C vs. Accuracy
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-C-vs-Accuracy.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-C-vs-Accuracy.png" width="300" height="300" alt="C vs. Accuracy" />

### C vs. Accuracy - l1 Penalty
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-C-vs-Accuracy-l1-penalty.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-C-vs-Accuracy-l1-penalty.png" width="300" height="300" alt="C vs. Accuracy - l1 Penalty" />

### C vs. gamma
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-C-vs-gamma.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-C-vs-gamma.png" width="300" height="300" alt="C vs. gamma" />

### Grid Search Classification Report
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-Grid-Search-Classification-Report.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-Grid-Search-Classification-Report.png" width="300" height="300" alt="Grid Search Classification Report" />

### Grid Search Confusion Matrix
<img src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-Grid-Search-Confusion-Matrix.png" data-canonical-src="https://github.com/alansary/Image-Classification-using-K-NN-Logistic-Regession-and-SVM/blob/main/images/SVM-Grid-Search-Confusion-Matrix.png" width="300" height="300" alt="Grid Search Confusion Matrix" />