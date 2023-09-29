# Diabetes Prediction using Support Vector Machine (SVM)
This repository contains code for predicting diabetes using a Support Vector Machine (SVM) classifier. The code is implemented in Python and makes use of the following libraries:

Numpy

Pandas

Sklearn

# Dataset
The code uses the diabetes dataset available on Kaggle (https://www.kaggle.com/uciml/pima-indians-diabetes-database). The dataset contains various attributes related to diabetes diagnosis and is stored in a CSV file. The data is pre-processed and used to train and test the SVM classifier.

# Model
The SVM classifier is trained on the pre-processed data. The data is first standardized using the StandardScaler function from the sklearn preprocessing library. The data is then split into a training set and a test set using the train_test_split function from the sklearn model_selection library. The SVM classifier is then trained on the training set using the linear kernel.

## How to run:
Note: This virtual environment created on anaconda command prompt.
#### Step 1: Clone the Repository
Explain how users can clone your project's GitHub repository to their local machine using the git clone command.
```
git clone https://github.com/OnCampus-Community/Diabetes-Prediction.git
```
#### Step 2: Create a Conda Environment
Guide users through the process of creating a Conda environment for your project. Explain why using a Conda environment is beneficial.

``````
conda create --name myenv5 python=X.X
``````
Replace myenv2 with your preferred environment name and X.X with the desired Python version.
#### Step 3: Activate the Conda Environment
Show users how to activate the Conda environment:
``````
conda activate myenv5
``````
#### Step 4: Install Project Dependencies
Explain how to install the project dependencies from the requirements_2.txt file.
The requirement file in this project based on jupyter notebook.
``````
pip install -r requirements_2.txt
``````
#### Step 5: Run the Project
Provide instructions on how to run your project. Include any specific commands or configuration that users need to know.

# Usage
To run the code, simply clone the repository and run the code. The code will load the dataset, pre-process the data, train the SVM classifier, and make predictions on a sample input data. You can also change the input data to predict for different cases.

3 Conclusion
The code demonstrates the usage of SVM classifier in solving the problem of diabetes prediction. The accuracy of the model may vary depending on the dataset used for training and the choice of kernel used in the SVM classifier. It is recommended to try different algorithms and hyperparameters to obtain the best results.
