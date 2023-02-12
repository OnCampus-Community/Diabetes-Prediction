# Diabetes Prediction using Support Vector Machine (SVM)
This repository contains code for predicting diabetes using a Support Vector Machine (SVM) classifier. The code is implemented in Python and makes use of the following libraries:

Numpy

Pandas

Sklearn

# Dataset
The code uses the diabetes dataset available on Kaggle (https://www.kaggle.com/uciml/pima-indians-diabetes-database). The dataset contains various attributes related to diabetes diagnosis and is stored in a CSV file. The data is pre-processed and used to train and test the SVM classifier.

# Model
The SVM classifier is trained on the pre-processed data. The data is first standardized using the StandardScaler function from the sklearn preprocessing library. The data is then split into a training set and a test set using the train_test_split function from the sklearn model_selection library. The SVM classifier is then trained on the training set using the linear kernel.

# Usage
To run the code, simply clone the repository and run the code. The code will load the dataset, pre-process the data, train the SVM classifier, and make predictions on a sample input data. You can also change the input data to predict for different cases.

3 Conclusion
The code demonstrates the usage of SVM classifier in solving the problem of diabetes prediction. The accuracy of the model may vary depending on the dataset used for training and the choice of kernel used in the SVM classifier. It is recommended to try different algorithms and hyperparameters to obtain the best results.
