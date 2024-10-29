# CensusProject_ML_RandomForest
The objective of this project is to build a classification model using the Census Income dataset from the UCI Machine Learning Repository. The model predicts whether an individual's income exceeds $50,000 per year, based on their demographic and employment-related attributes.
## Overview
This project aims to classify whether an individual earns more than $50,000 per year, using data from the 1994 US Census. This classification task leverages demographic and employment-related attributes to predict income, making it an essential tool for income prediction and social-economic analysis.

## Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/census+income)
- **Size**: 48,842 instances, covering demographic, employment, and income data.

## Problem Statement
The goal is to predict if a person's income exceeds $50,000 per year based on their demographic attributes and work-related features.

## Project Tasks
### 1. Data Preprocessing
- **Handling Missing Values**: Managed missing entries to maintain data quality.
- **Encoding Categorical Variables**: Used encoding techniques to convert categorical data into numerical form.
- **Feature Scaling**: Applied scaling for algorithm compatibility and performance.

### 2. Exploratory Data Analysis (EDA)
Conducted EDA to explore feature relationships and visualize income distribution patterns. Key insights included trends based on age, education, occupation, and work hours.

### 3. Model Building and Evaluation
Developed multiple machine learning models for classification, with a focus on accuracy and robustness:
- **Best Model**: Random Forest Classifier, achieving **84% accuracy**.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score for comprehensive assessment.

## Results
- The Random Forest model achieved an accuracy of 84%, successfully predicting income categories with high performance.

## Installation and Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/gurramankit/census-income-classification.git
    ```
2. Install the necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the project:
    ```bash
    python main.py
    ```

## Project Structure
- `data/` - Contains the Census Income dataset.
- `notebooks/` - Jupyter notebooks for EDA, data preprocessing, and model development.
- `src/` - Python scripts for data processing and model implementation.
- `README.md` - Overview and instructions.
- `requirements.txt` - Dependencies for running the project.


