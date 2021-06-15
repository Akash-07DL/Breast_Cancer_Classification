# Breast_Cancer_Classification_Scikit_Learn

# Classification
classification refers to a predictive modeling problem where a class label is predicted for a given example of input data.

# Objective:
Breast cancer classification(Malignant,  Benign) using Scikit-Learn.

# Data:
I use the "Wisconsin Breast Cancer" which is a default, preprocessed and cleaned datasets comes with scikit-learn. The target is to classify tumor as 'malignant' or 'benign'.

# Descriptions:

Techniques:

1.KNN 
Data is used directly to the knn classifier with neighbour = 8.
Then i use standard scalar and fit knn classifier with neighbour = 8.

2.SVM
Used sklearn SVC with **linear** kernel and fit the standard scaled data into the classifier.
After that used sklearn SVC **rbf** kernel and fit the standard scaled data into the classifier.

3.MLP
Used **MLPClassifier** with activation function as **relu**, optimization function as **adam**, batch size as 50, hidden_layer_sizes=(150,140,130) and used **adaptive** learning rate.
Fit the standard scaled data into the MLPClassifier.
Used **MLPClassifier** with activation function as **logistic**, optimization function as **adam**, batch size as 50, hidden_layer_sizes=(150,140,130) and used **adaptive** learning rate.

Evaluation:
Evaluated all model using confusion matrix, and by printing the classification_report from sklearn.

Result:
Best result gives by the sklearn SVC with **rbf** kernel.
