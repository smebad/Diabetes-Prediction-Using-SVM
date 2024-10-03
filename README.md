# 🩺 Diabetes Prediction Using SVM

📋 Project Overview

This project aims to predict whether a person has diabetes using health-related features. The Support Vector Machine (SVM) algorithm is employed for classification, and the dataset is preprocessed with StandardScaler to ensure feature standardization.

Key Features:

* Predicts diabetes based on features like glucose level, BMI, age, etc.
* Standardizes the data to improve model performance.
* Achieves high accuracy with the SVM model.

🛠️ Technologies & Tools
* Programming Language: Python 🐍
* Libraries: pandas, numpy, scikit-learn
* Model: Support Vector Machine (SVM) 🧠
* Data Preprocessing: StandardScaler

📊 Dataset Description

The dataset contains 8 health-related features used to predict whether a patient has diabetes:

* Pregnancies: Number of times pregnant 🤰
* Glucose: Plasma glucose concentration
* BloodPressure: Diastolic blood pressure (mm Hg)
* SkinThickness: Triceps skin fold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml)
* BMI: Body Mass Index
* DiabetesPedigreeFunction: Diabetes pedigree function
* Age: Age of the person

The target variable is:
* Outcome: 0 (No diabetes), 1 (Has diabetes)

📈 Project Workflow
1. Data Loading 📥: Load the dataset using pandas and review the first few rows.
2. Data Exploration 🔍: Explore the dataset with summary statistics and check for imbalances in the target variable.
3. Data Preprocessing 🔄: Standardize the features using StandardScaler for better model performance.
4. Train/Test Split ✂️: Split the dataset into training and testing sets with an 80/20 ratio and stratification.
5. Model Training 🤖: Train an SVM classifier with a linear kernel on the training data.
6. Model Evaluation 🧪: Evaluate the model on the test data using accuracy score.
7. Prediction 🔮: Make predictions with new input data to check if the person has diabetes.

🚀 Results
* Accuracy: The model achieved a good accuracy score on the test data.
* Prediction: You can input new data and get a prediction about whether the individual has diabetes.

🤔 Why SVM?
* Effective for High-dimensional Spaces: SVM works well when there are many features.
* Memory Efficient: SVM uses only a subset of training points in decision making (support vectors).
* Versatile: Different kernel functions can be specified for different decision boundaries.

Enjoy predicting diabetes! 🌟
