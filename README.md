# Machine Learning Models for Predicting Olympic Medal Outcomes

[![Paper](https://img.shields.io/badge/Paper-IEEE-blue)](https://ieeexplore.ieee.org/document/10984687)  
## Overview

This repository contains the code and dataset used in the paper:

**"Machine Learning Models for Predicting Olympic Medal Outcomes"**  
Published on IEEE Xplore: [https://ieeexplore.ieee.org/document/10984687](https://ieeexplore.ieee.org/document/10984687)

The project explores the prediction of Olympic medal winners using 13 different machine learning models, trained on an extensive dataset covering 128 years of Olympic history (1896–2024).

## Abstract

In this paper, the prediction of Olympic medal winners has been explored using various machine learning models, utilizing a dataset spanning 128 years of Olympic history from 1896 to 2024. Thirteen Machine Learning models — Logistic Regression, Polynomial Logistic Regression, XGBoost, Random Forest, KNN, Naive Bayes, LightGBM, AdaBoost, Decision Tree, Extra Trees, Gradient Boosting, Neural Network, and SVM — were used and evaluated. The dataset was preprocessed, and models were trained and tested to predict future medal outcomes. Superior performance metrics were demonstrated by ensemble models such as XGBoost, LightGBM, and Gradient Boosting with accuracy rates of 83%, 84%, and 84% respectively, and notable AUC values. Conversely, lower performances were exhibited by simpler models like Logistic Regression, Polynomial Logistic Regression, and SVM. Discrepancies in prediction graphs suggested potential issues in model training or dataset encoding. Future research will focus on integrating additional features and more sophisticated techniques to enhance model performance and prediction accuracy. The findings are anticipated to contribute significantly to the field of sports analytics and assist national Olympic committees in strategic planning and resource allocation for future Olympic Games.

## Key Features

- **Comprehensive Dataset**: Olympic data from 1896 to 2024 covering athlete, country, sport, and event details.
- **13 ML Models Implemented**: Includes traditional, ensemble, and neural network models.
- **Performance Evaluation**: Models are compared using accuracy, AUC, and prediction visualizations.
- **Insights & Future Work**: Discusses model discrepancies and outlines plans for more sophisticated feature engineering.

## Models Included

| Model                     | Type           |
|---------------------------|----------------|
| Logistic Regression       | Linear Model   |
| Polynomial Logistic Reg.  | Linear Model   |
| XGBoost                   | Ensemble       |
| Random Forest             | Ensemble       |
| K-Nearest Neighbors (KNN) | Instance-based |
| Naive Bayes               | Probabilistic  |
| LightGBM                  | Ensemble       |
| AdaBoost                  | Ensemble       |
| Decision Tree             | Tree-based     |
| Extra Trees               | Ensemble       |
| Gradient Boosting         | Ensemble       |
| Neural Network            | Deep Learning  |
| Support Vector Machine    | Kernel-based   |
