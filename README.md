# Detection and Prevention of Vehicle Insurance Claim Fraud

## Project Overview

This project addresses the significant challenge insurance companies face due to fraudulent claims, which result in financial losses and erode trust in the insurance system. The objective is to develop a dependable predictive model that efficiently detects fraudulent insurance claims by leveraging historical claim data. This model will assist insurance companies in reducing financial losses, enhancing claim processing efficiency, and maintaining fair premium pricing for customers.

## Dataset

### Name: Vehicle Claim Fraud Detection

- **Source**: Kaggle
- **Size**: 15,420 records
- **Variables**: 33 (both categorical and numerical)
- **Key Features**:
  - Month of the accident
  - Day of the week
  - Make of the vehicle
  - Accident area
  - Age of the policyholder
  - Various policy details
  - Indicator of whether the claim was fraudulent

The dataset offers a robust sample size for training and evaluating the predictive model and includes indicators for fraudulent claims, making it suitable for building a classification model.

## Project Structure

- **Exploratory Data Analysis (EDA)**: Detailed analysis of the dataset, feature engineering, and visualization of key metrics.
- **Modeling**: Implementation of multiple machine learning models (Decision Tree, XGBoost, Random Forest, K-Nearest Neighbor) with hyperparameter tuning and evaluation.
- **Evaluation**: Assessing model performance using accuracy, classification reports, and confusion matrices.

## Installation and Usage

### Prerequisites

- Python 3.x
- Required libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - matplotlib
  - seaborn
  - scikit-optimize (for Bayesian Optimization)
  - Jupyter Notebook

### Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/oxayavongsa/aai-510-ml-group-1
    cd aai-510-ml-group-1
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter Notebook for Exploratory Data Analysis (EDA):
    ```bash
    jupyter notebook revised-eda.ipynb
    ```

4. Follow the notebook steps to perform data cleaning, feature selection, and model training.

## Team Members

- **Team Leader/Representative**: Outhai Xayavongsa (Thai)
- **Technical Lead**: Aaron Ramirez
- **Members**:
  - Aaron Ramirez
  - Muhammad Haris
  - Outhai Xayavongsa (Thai)

## Comments / Roadblocks

None reported.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
