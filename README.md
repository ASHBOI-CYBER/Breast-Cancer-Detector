# Breast Cancer Prediction Model

This project aims to predict whether a breast tumor is malignant or benign using a machine learning model. The dataset used is the famous Wisconsin Breast Cancer dataset, and the model is built using a Random Forest Classifier. The model is deployed as a simple web app where users can input features of a breast tumor to get a prediction.

## Features

- Data preprocessing and feature engineering
- Training with a Random Forest Classifier
- Model evaluation using accuracy and confusion matrix
- Simple web interface (e.g., Flask or Streamlit) for making predictions
- Model saved as a `.pkl` file for future use

## Project Structure

    ├── breast_cancer_model.pkl         # Trained Random Forest model
    ├── requirements.txt               # Python package dependencies
    ├── app.py / notebook.ipynb        # Main Python or Jupyter notebook file
    ├── data/                          # Dataset and data processing scripts
    ├── README.md                      # Project description

## Dataset

The dataset can be downloaded from the UCI Machine Learning Repository:
[Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

Ensure the dataset includes the following features:
- radius_mean
- texture_mean
- perimeter_mean
- area_mean
- smoothness_mean
- compactness_mean
- concavity_mean
- concave_points_mean
- symmetry_mean
- fractal_dimension_mean
- ... (various other features)

The target variable should be `label` where:
- 0: Benign
- 1: Malignant


## Model Evaluation

The model is evaluated based on:
- Accuracy: ~98% (depending on the dataset split)
- Confusion Matrix: Detailed analysis of true positives, false positives, true negatives, and false negatives


## License

This project is for educational purposes. You are free to modify and expand it as needed.
