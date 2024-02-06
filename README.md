# Breast Cancer Diagnosis Prediction
This project aims to predict the diagnosis of breast cancer (malignant or benign) based on various features extracted from digitized images of fine needle aspirate (FNA) of breast mass. The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) dataset1, which contains 569 samples and 30 features.

## Models
Two models are trained and compared for this classification task: logistic regression and support vector machine (SVM).

#### Model 1: Logistic Regression
* Description: Logistic regression is a supervised learning method that models the probability of a binary outcome based on a linear combination of predictor variables2. It uses a sigmoid function to map the log-odds of the outcome to a probability between 0 and 1.
* Data: The data is split into 80% training and 20% testing sets. The features are standardized to have zero mean and unit variance.
* Performance: The logistic regression model achieves an accuracy of 0.956 on the test set, with a precision of 0.947 and a recall of 0.947 for the malignant class.
* Usage: To use the logistic regression model, load the logreg_model.pkl file using pickle and call the predict method on the new data.
#### Model 2: Support Vector Machine (SVM)
* Description: Support vector machine (SVM) is a supervised learning method that finds a hyperplane that maximizes the margin between two classes3. It can also use a kernel function to perform non-linear classification by mapping the data to a higher-dimensional feature space.
* Data: The data is split into 80% training and 20% testing sets. The features are standardized to have zero mean and unit variance.
* Performance: The SVM model achieves an accuracy of 0.974 on the test set, with a precision of 0.974 and a recall of 0.961 for the malignant class. The SVM model uses a radial basis function (RBF) kernel with a gamma parameter of 0.01 and a regularization parameter of 10.
* Usage: To use the SVM model, load the svm_model.pkl file using pickle and call the predict method on the new data.
## Installation
To run this project, you need to have Python 3 and the following packages installed:
* numpy
* pandas
* scikit-learn
* pickle
You can install the packages using pip or conda.

## Contributing
If you want to contribute to this project, please follow these steps:

## Fork the repository
Create a new branch for your feature or bug fix
Make your changes and commit them with a clear message
Push your branch to your fork
Open a pull request and describe your changes

## References
1: Dua, D. and Graff, C. (2019). UCI Machine Learning Repository [http://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.
2: Introduction to Logistic Regression - Statology
3: Support vector machine - Wikipedia
