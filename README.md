# Credit Card Fraud Detection
This repository contains a Python project focused on detecting fraudulent credit card transactions using machine learning techniques. The project includes a Jupyter notebook that details data preprocessing, model training, and evaluation.

# Project Overview
The primary objective of this project is to accurately identify fraudulent transactions from a given dataset. The project includes steps for data visualization, handling imbalanced datasets, and implementing a logistic regression model and Random forest Model.

# Dataset
The dataset used for this project is large and could not be uploaded directly to this repository. You can download the dataset from the following link:
https://drive.google.com/file/d/1xoRHAwxGycQaqt1vPIm2TLLEWcpJtd03/view

# Model Details
The model used in this project is a Logistic Regression model and Random Forest Model. Below are the key details of the model:

- **Algorithm**: Logistic Regression and Random Forest
- **Framework**: scikit-learn
- **Features**: The dataset includes various anonymized features (V1, V2, ..., V28), along with Time and Amount.
- **Performance**: The notebook includes evaluation metrics such as accuracy, precision, recall, and F1 score to assess model performance.
  
# Steps Involved in the Project
- **Importing Libraries**: Necessary libraries such as NumPy, pandas, scikit-learn, and others are imported to handle data manipulation, model training, and evaluation.

- **Data Loading**: The credit card transactions dataset is loaded into a pandas DataFrame.

- **Data Visualization**: Initial exploration and visualization of the dataset to understand the distribution and characteristics of the data.

- **Handling Imbalanced Dataset**: The dataset is highly imbalanced, with a much larger number of legitimate transactions compared to fraudulent ones. Techniques such as under-sampling are used to address this imbalance.

- **Data Preprocessing**: Steps like scaling features and splitting the data into training and testing sets are performed to prepare the data for model training.

- **Model Training**: A Logistic Regression model and Random Forest Model is trained on the preprocessed data.

- **Model Evaluation**: The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1 score to ensure both the models effectively identifies fraudulent transactions.

# Repository Contents
- **Credit_Card_Fraud_Detection.ipynb**: Jupyter notebook containing the code for data loading, preprocessing, visualization, handling class imbalance, model training, and evaluation.
- **README.md**: Detailed documentation of the project, including setup instructions and project overview.
