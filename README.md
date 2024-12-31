# Mammogram ML Project

This project focuses on detecting breast cancer by analyzing mammogram images using machine learning techniques.

## Key Components

- **Data Handling:** 
  The dataset (`mammographic_masses.data`) comprises records with attributes such as:
  - Age
  - Mass shape
  - Margin
  - Density
  - Severity (benign or malignant)

- **Notebook Implementation:**
  The Jupyter Notebook (`mammogram_ml.ipynb`) contains the code for:
  - Data preprocessing
  - Model training
  - Model evaluation

## Machine Learning Models Used

The project applies several supervised machine learning algorithms to classify mammogram masses as benign or malignant, including:

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)
- Logistic Regression

Additionally, a neural network is implemented using Keras.

## Development Environment

The project was developed using **Amazon SageMaker Studio**, with data stored in **Amazon S3**, enabling scalable machine learning workflows.

## Objective

This project aims to enhance the accuracy of breast cancer detection from mammogram images, potentially reducing unnecessary invasive procedures.
