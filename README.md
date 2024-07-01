# Health Insurance Cross sell Prediction

## Overview

Vehicle Insurance Prediction is a machine learning project aimed at predicting customer interest in vehicle insurance based on various features such as age, vehicle age, and region. This project uses a dataset sourced from [source_name/link], which was preprocessed to handle missing values and encode categorical variables.

## Table of Contents 

Overview

Dataset

Installation

Usage

Models Implemented

Hyperparameter Tuning

Evaluation Metrics

Feature Importance

Conclusion

Contributing

## Installation

Clone the repository and install dependencies using pip:

pip install -r requirements.txt

## Models Implemented

Several machine learning models were implemented and evaluated:

**Decision Tree Classifier**

Accuracy: 82%

Hyperparameters: max_depth, min_samples_leaf, splitter

**Bagging Classifier**

Accuracy: 85%
Hyperparameters: n_estimators, max_samples, max_features

**Logistic Regression**

Accuracy: 87%

Hyperparameters: solver, C, penalty

**Hyperparameter Tuning**

Hyperparameters were tuned using Halving Randomized Search CV, balancing efficiency and effectiveness in finding optimal configurations.

**Evaluation Metrics.**

Evaluation focused on:

Accuracy 

Precision

Recall

F1-Score

ROC-AUC Score

Log Loss

These metrics provide insights into model performance and its suitability for predicting customer interest accurately.

**Feature Importance**

Feature importance was analyzed to identify key factors influencing predictions:


## Conclusion

The Bagging Classifier emerged as the best-performing model due to its balanced metrics and ability to handle imbalanced data effectively. Future improvements could involve exploring ensemble methods or incorporating more detailed customer behavior data.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or fixes. Feel free to open issues to report bugs or suggest new features.
