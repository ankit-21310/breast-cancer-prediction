PROJECT TITLE

Breast Cancer Classification Using Machine Learning


Overview

Breast cancer is one of the most prevalent cancers among women worldwide, and early detection is crucial for effective treatment. This project focuses on developing machine learning models to classify breast cancer cells as benign or malignant using the Breast Cancer Wisconsin (Diagnostic) Dataset. The aim is to enhance early detection accuracy, reduce reliance on invasive procedures, and improve patient outcomes.

Dataset

The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset, which includes features computed from digitized images of breast mass. These features are grouped into three categories:

1)Mean

2)Standard error

3)Worst or largest (mean of the three largest values)

Features include:

Radius, Texture, Perimeter, Area, Smoothness, Compactness, Concavity, Concave Points, Symmetry, and Fractal Dimension.


Key Objectives

Build models to accurately predict whether a tumor is benign or malignant.
Address challenges like model generalization, interpretability, and clinical applicability.
Develop models that can integrate seamlessly into clinical workflows.


Methods Used

Data Preprocessing:

Cleaned the dataset and removed missing values.
Standardized numerical features.
Applied PCA for dimensionality reduction and feature selection.

Machine Learning Models:


1)Naive Bayes

2)Logistic Regression

3)Random Forest

4)K-Nearest Neighbor (KNN)

5)Neural Network with PCA


Evaluation Metrics:

Accuracy

Precision

Recall

F1 Score

ROC-AUC


Results

Model Performance

Logistic Regression emerged as the best-performing model with the following metrics:

Accuracy: 98.25%

Precision: 98.25%

Recall: 96.49%

F1 Score: 98.25%

Random Forest closely followed with an accuracy of 97.37%.

Key Findings

Logistic Regression offers high performance with lower complexity, making it a suitable candidate for clinical integration.
Random Forest and Naive Bayes also demonstrated strong results, providing alternative modeling approaches.
Implementation
Requirements

Install the necessary Python libraries using:
bash

pip install -r requirements.txt

Steps to Run

Clone the repository.
Download the dataset and place it in the project directory.
Run the preprocessing script to prepare the data.
Train models using the provided Jupyter notebooks or scripts.
Evaluate performance using confusion matrices and other metrics.

Future Work


Incorporate ensemble methods for improved performance.
Extend the model to handle multiclass classification for other types of cancer.
Evaluate models on real-world clinical data for robustness and scalability.
Optimize models for deployment on cloud-based healthcare platforms.

Conclusion

This project demonstrates the potential of machine learning in breast cancer classification. Logistic Regression emerges as the most effective model, balancing performance, interpretability, and computational efficiency. With further optimization and real-world validation, these models can significantly aid in early detection and clinical decision-making.
