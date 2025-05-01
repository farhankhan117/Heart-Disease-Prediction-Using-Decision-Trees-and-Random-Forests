# Decision-tree-Random-forest-
Heart Disease Prediction
Overview
This project uses machine learning techniques such as Decision Trees and Random Forests to predict the likelihood of heart disease in patients. The dataset contains several health-related features, and the goal is to use these features to classify whether a person has heart disease or not.

Dataset
The dataset used is heart.csv, which includes the following columns:

Column	Description
age	Age of the patient
sex	Gender (1 = male, 0 = female)
cp	Chest pain type (numeric values)
trestbps	Resting blood pressure
chol	Serum cholesterol level
fbs	Fasting blood sugar (> 120 mg/dl, 1 = true, 0 = false)
restecg	Resting electrocardiographic results (numeric values)
thalach	Maximum heart rate achieved
exang	Exercise induced angina (1 = yes, 0 = no)
oldpeak	Depression induced by exercise relative to rest
slope	Slope of the peak exercise ST segment
ca	Number of major vessels colored by fluoroscopy
thal	Thalassemia (1, 2, 3)
target	0 = No heart disease, 1 = Heart disease (target variable)

Objective
The objective of this project is to train and evaluate machine learning models, particularly:

Decision Trees

Random Forests

These models will be used to predict whether a patient has heart disease based on the given features.

Steps
1. Data Preprocessing
Loaded and preprocessed the dataset by splitting it into features (X) and the target variable (y).

Checked for any missing values and handled them if necessary (in this case, the dataset doesn't contain any missing values).

2. Model Training
Trained a Decision Tree Classifier and visualized the tree structure.

Trained a Random Forest Classifier to compare its performance with the Decision Tree.

Compared the accuracy of both models.

3. Model Evaluation
Evaluated the models using cross-validation to ensure that the models perform well on unseen data.

4. Feature Importance
Interpreted feature importance for the Random Forest model to identify which features contribute most to the prediction.

Requirements
Python 3.x

Libraries:

pandas

scikit-learn

matplotlib
