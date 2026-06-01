# Multi-Agent ML Comparison System

## Overview

This project implements a Multi-Agent System for automating the Machine Learning workflow and comparing multiple classification algorithms on the Titanic dataset.

The system performs data loading, preprocessing, model training, hyperparameter optimization, evaluation, and visualization through specialized agents.

## Multi-Agent Architecture

### DataLoaderAgent
- Loads the Titanic dataset
- Performs initial data analysis
- Detects missing values
- Separates features and target variable

### PreprocessingAgent
- Handles missing values
- Encodes categorical variables
- Splits data into training and testing sets
- Creates multiple dataset variants

### ModelTrainerAgent
- Trains Machine Learning models
- Performs hyperparameter optimization using GridSearchCV
- Evaluates model performance
- Stores experiment results

### VisualizationAgent
- Generates performance tables
- Creates comparison charts
- Displays confusion matrices
- Produces automatic insights

## Dataset

The project uses the Titanic Dataset for binary classification.

Target variable:
- 0 = Did not survive
- 1 = Survived

## Preprocessing Techniques

The following dataset versions were generated:

- Original Dataset
- Standardized Dataset
- MinMax Scaled Dataset
- Robust Scaled Dataset
- Normalized Dataset

## Machine Learning Models

The following algorithms were evaluated:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest
- MLP Neural Network

## Hyperparameter Optimization

GridSearchCV with 5-Fold Cross Validation was used to identify the best hyperparameters for each model.

## Evaluation Metrics

Models were compared using:

- Accuracy
- Precision
- Recall
- F1 Score
- Train Accuracy
- Test Accuracy
- Overfitting Difference

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Repository Structure

```text
├── MultiAgentSistem.ipynb
├── Proiect_Multiagent.pdf
└── README.md
