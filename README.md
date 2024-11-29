# AML_ANN_Breast_Cancer

# Breast Cancer Diagnostic Machine Learning Project

## Overview
This project utilizes the Breast Cancer Wisconsin (Diagnostic) dataset to develop a machine learning classification model for detecting breast cancer.

## Dataset Characteristics
- **Total Instances**: 569
- **Number of Attributes**: 30 numeric predictive attributes and the class
- **Class Distribution**: 212 Malignant, 357 Benign

## Features
The dataset includes measurements of cell nuclei characteristics from fine needle aspirate (FNA) images:
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Concave points
- Symmetry
- Fractal dimension

For each feature, three values are computed:
- Mean
- Standard error
- "Worst" or largest value

## Libraries Used
- pandas
- numpy
- matplotlib
- scikit-learn
- TensorFlow/Keras
- joblib

## Data Preprocessing
1. Dataset loaded using `sklearn.datasets.load_breast_cancer()`
2. Converted to pandas DataFrame
3. Target variable added to indicate malignant (0) or benign (1) cases

## Machine Learning Models
The project implements two types of models:
1. Scikit-learn's MLPClassifier
2. TensorFlow/Keras Neural Network

## Feature Selection
- SelectKBest from scikit-learn is used for feature selection

## Model Evaluation
- Accuracy score
- Classification report

## Additional Components
- Early stopping callback for neural network training
- StandardScaler for feature normalization

## Potential Applications
- Breast cancer diagnostic screening
- Feature analysis of medical imaging data
- Binary classification using neural networks

## References
- Original dataset: UCI ML Breast Cancer Wisconsin (Diagnostic) dataset
- Created by Dr. William H. Wolberg, W. Nick Street, and Olvi L. Mangasarian

## Note
This documentation provides an overview of the project structure and components. For detailed implementation, refer to the actual notebook file.
