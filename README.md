# MLflow-Databricks-Azure

## Project Overview

This MLFlow Project Integration Series is a comprehensive guide to employing MLFlow for improving and tracking machine learning workflows across various frameworks. This series consists of five Jupyter notebooks, each focusing on a different aspect of the machine learning lifecycle. The notebooks cover a range of topics from basic MLFlow usage with ScikitLearn to advanced integration with Pyspark, TensorFlow, and Databricks.

## Notebooks Description

### 1. MLFlow with ScikitLearn

- **Objective**: Introduces MLFlow tracking with ScikitLearn using the credit card fraud detection dataset from Kaggle.
- **Key Components**:
  - Data preprocessing and feature scaling.
  - Model training, evaluation, and logging using MLFlow.
  - Visualization of performance metrics and confusion matrix.

### 2. MLFlow with TensorFlow 2.0 (Keras)

- **Objective**: Demonstrates MLFlow tracking with TensorFlow 2.0 (Keras) for deep learning models.
- **Key Components**:
  - Building and compiling a neural network model for the MNIST dataset.
  - Autologging of training process and metrics with MLFlow.
  - Model evaluation with accuracy and AUC scores.

### 3. MLFlow with Pyspark

- **Objective**: Showcases the use of MLFlow in a Pyspark environment to track machine learning experiments.
- **Key Components**:
  - Pyspark session setup and data handling.
  - Model training and evaluation with logistic regression.
  - Logging of training and evaluation metrics in MLFlow.

### 4. Local Model Serving and Deployment

- **Objective**: Guides on how to serve and query ML models locally using MLFlow and the command line.
- **Key Components**:
  - Model serving using MLFlow and `curl` requests.
  - Batching predictions and model querying using `subprocess` or `requests`.
  - Evaluation and visualization of batch prediction results.

### 5. MLflow with DataBricks

- **Objective**: Explores MLFlow integration with Databricks for cloud-based machine learning experiment management.
- **Key Components**:
  - Data exploration and preprocessing in a Databricks environment.
  - Logistic regression model training and hyperparameter tuning.
  - Experiment logging and comparison using MLFlow on Databricks.

## Getting Started

To get started with this series, ensure you have MLFlow installed and configured in your environment. Each notebook contains detailed steps on setting up MLFlow tracking, model training, and evaluation processes for different machine learning frameworks. 

## How to Use These Notebooks

It is recommended to go through the notebooks in order as each builds on the concepts and setup of the previous one. Ensure that the required libraries and frameworks are installed and that you have access to the datasets used in these notebooks.

### Data Sources

- The datasets used in these notebooks are primarily the Credit Card Fraud Detection dataset from Kaggle and the MNIST dataset.

### Installation Guides

- Detailed installation guides, such as "Spark Installation.pdf" for notebook 3, are provided within the notebooks or as separate documents.

### Prerequisites

- Familiarity with Python, machine learning, and the specific frameworks (ScikitLearn, TensorFlow, Pyspark) is beneficial.
- Basic understanding of MLFlow's capabilities in tracking and logging ML experiments.

## Conclusion

This project series is designed to give you hands-on experience with MLFlow and its integration with various machine learning frameworks. By the end of the series, you should be able to set up MLFlow tracking, understand how to log experiments, serve models locally, and conduct experiments in a cloud environment using Databricks.
