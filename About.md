Heart Attack Prediction Model




Project Description: 


This repository contains a machine learning solution designed to predict the likelihood of heart attacks using clinical and lifestyle data. The model leverages various numerical features from patient records to identify patterns associated with cardiovascular risk, potentially enabling earlier intervention and preventive care.
Dataset




The model is trained on a comprehensive numerical dataset containing patient medical records with features including:




Age-
Sex-
Blood pressure measurements-
Cholesterol levels-
Blood sugar levels-
ECG results-
Maximum heart rate-
Exercise-induced angina-
ST depression induced by exercise-
Slope of peak exercise ST segment-
Number of major vessels colored by fluoroscopy-
Thalassemia type

Methodology:




Data Preprocessing: Standardization, handling missing values, feature scaling
Exploratory Data Analysis: Statistical analysis and visualization of feature distributions and correlations
Feature Engineering: Creation of relevant derived features and selection of optimal predictive variables
Model Development: Implementation of multiple classification algorithms including:


DT

Naive Bayes (gaussian - bernoli - multinomial)

Support Vector Machines

WKNN


Hyperparameter Tuning: cross-validation for optimal model parameters
Evaluation: Performance assessment using accuracy, precision, recall, F1-score, and ROC-AUC metrics



Integration of additional biomarkers and lifestyle factors
Deployment as a web application for clinical use
Exploration of explainable AI techniques to improve model interpretability

Technologies Used

Python
Pandas, NumPy
Scikit-learn
TensorFlow/Keras
Matplotlib, Seaborn
Jupyter Notebooks

