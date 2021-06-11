## Breast Cancer Wisconsin (Diagnostic) Prediction
*This project intends to find whether the cancer is benign or malignant*

For this project we have used the Wisconsin dataset which is available on: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

**Information about the attributes:**

*1) ID number 2) Diagnosis (M = malignant, B = benign) 3-33)* Includes various real-world features that is being diagnosed to check the cancer type like radius_mean (this is distances from center to points on the perimeter and taking mean of it), fractal dimension ("coastline approximation" - 1) and their are more parameters.

The dataset includes 569 Rows and 33 columns(1 is dependent variable)

**This prediction is a classfication based problem hence supervised learning algorithm here. Hence, for making prediction I have used Logistics Regression and K-Nearest nighbour here.**

**Class distribution:**

![image](https://user-images.githubusercontent.com/55655289/121757053-e88c1100-cb39-11eb-81a0-121eaadf59e3.png)

![image](https://user-images.githubusercontent.com/55655289/121757065-f3df3c80-cb39-11eb-948b-ff4acb86c71f.png)

Algorithm                  | Accuracy
-----------                | --------
Logistic Regression        |  96.5 %
KNN Classifier             |  72.51 %

Logistic Regression - Sachin_Singh_Breast_Prediction_LogReg.ipynb

K-Nearest Neighbour - BreastCancerDiagnostic_KNN.ipynb
