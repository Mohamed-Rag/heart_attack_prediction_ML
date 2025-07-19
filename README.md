# Heart Attack Prediction using Machine Learning

## Overview
This project focuses on developing and comparing various machine learning models to predict the risk of heart attack based on numerical patient data. The goal is to identify the most effective model for early and accurate prediction, which can aid in preventive healthcare and timely medical intervention.

## Dataset
The project utilizes the `Heart Attack Data Set.csv` file, which contains various health parameters and a target variable indicating the presence or absence of heart disease.

## Models Implemented
Several machine learning algorithms have been implemented and evaluated:

- **Bernoulli Naive Bayes (`bernoli.ipynb`)**
- **Decision Tree (`dt.ipynb`)**
- **Gaussian Naive Bayes (`gaussian_naive_bayes.ipynb`)**
- **K-Nearest Neighbors (KNN) (`knn.ipynb`)**
- **Multinomial Naive Bayes (`multinomial.ipynb`)**
- **Support Vector Machine (SVM) (`svm.ipynb`)**
- **Weighted K-Nearest Neighbors (WKNN) (`wknn.ipynb`)**

Each Jupyter Notebook (`.ipynb`) file contains the implementation, training, and evaluation of a specific model.

## Getting Started
To run these models and reproduce the results, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Mohamed-Rag/heart_attack_prediction_ML.git
    cd heart_attack_prediction_ML
    ```
2.  **Install necessary libraries**:
    (Assumes Python 3 is installed. Specific library requirements can be found within each notebook, but common ones include `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`. )
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  **Open and run the Jupyter Notebooks**:
    Start Jupyter Notebook and open each `.ipynb` file to execute the code cells.
    ```bash
    jupyter notebook
    ```

## Project Structure
