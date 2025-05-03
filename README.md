# DSCI-478-final-project
# Enhancing Diabetes Prediction Using Advanced Machine Learning Techniques

## Abstract

This report builds upon the work of Rajendra and Latifi's article "Prediction of diabetes using logistic regression and ensemble techniques" by further analyzing the PIMA Indians Diabetes dataset for diabetes diagnosis. While the original article achieved approximately 70% accuracy using several machine learning models, this report introduces four new models and incorporates feature engineering to enhance predictive performance. The findings demonstrate an improved accuracy of up to 76% through these advanced techniques, highlighting the potential for fine-tuning machine learning models to achieve better results in diabetes prediction.

## Contents

- [Abstract](#abstract)
- [1. Introduction](#1-introduction)
- [2. Literature Review](#2-literature-review)
- [3. Methodology](#3-methodology)
  - [3.1 Dataset Exploration](#31-dataset-exploration)
  - [3.2 Data Preprocessing](#32-data-preprocessing)
  - [3.3 Feature Engineering and Selection](#33-feature-engineering-and-selection)
    - [NF1 = BMI × Glucose](#nf1--bmi--glucose)
    - [NF2 = Age × Insulin](#nf2--age--insulin)
    - [NF3 = Blood Pressure ÷ BMI](#nf3--blood-pressure--bmi)
    - [NF4 = Glucose Squared (Glucose²)](#nf4--glucose-squared-glucose²)
  - [3.4 Proposed Machine Learning Models](#34-proposed-machine-learning-models)
  - [3.5 Model Evaluation Metrics](#35-model-evaluation-metrics)
- [4. Results and Discussion](#4-results-and-discussion)
  - [Random forest](#random-forest)
  - [Gradient boosting](#gradient-boosting)
  - [SVM](#svm)
  - [ANN](#ann)
  - [Comparison of results](#comparison-of-results)
- [5. Conclusion](#5-conclusion)
- [References](#references)

## 1. Introduction

Diabetes is a significant global health concern, affecting millions with no definitive cure to date. Early detection plays a crucial role in managing the disease and improving the quality of life for individuals affected. This report explores advanced machine learning techniques for enhancing the accuracy of diabetes prediction using the PIMA Indians Diabetes dataset.

## 2. Literature Review

This section provides a review of existing literature relevant to diabetes prediction using machine learning. It likely discusses various approaches and findings in the field, setting the context for the current study's contribution.

## 3. Methodology

This section details the steps taken in this research to improve diabetes prediction accuracy.

### 3.1 Dataset Exploration

This subsection describes the PIMA Indians Diabetes dataset, likely including its features (e.g., glucose levels, BMI, age) and characteristics.

### 3.2 Data Preprocessing

This part explains the data cleaning and preparation techniques applied to the dataset before model training. This might involve handling missing values, scaling features, or other necessary transformations.

### 3.3 Feature Engineering and Selection

Here, the report outlines the creation of new features (NF1-NF4) from the existing ones to potentially provide more informative inputs for the machine learning models.

- **NF1 = BMI × Glucose**
- **NF2 = Age × Insulin**
- **NF3 = Blood Pressure ÷ BMI**
- **NF4 = Glucose Squared (Glucose²)**

### 3.4 Proposed Machine Learning Models

This subsection introduces the four new machine learning models that were implemented and evaluated in this study, in addition to the models used in the original article by Rajendra and Latifi. The specific types of these new models (e.g., Support Vector Machines, Artificial Neural Networks) are detailed later in the "Results and Discussion" section.

### 3.5 Model Evaluation Metrics

This part describes the metrics used to assess the performance of the different machine learning models, such as accuracy, precision, recall, and F1-score.

## 4. Results and Discussion

This section presents the performance of each of the machine learning models.

### Random forest

The results obtained using the Random Forest model are discussed here.

### Gradient boosting

The performance of the Gradient Boosting model is analyzed in this subsection.

### SVM

The findings from the Support Vector Machine (SVM) model are presented here.

### ANN

This subsection details the results achieved with the Artificial Neural Network (ANN) model.

### Comparison of results

A comparative analysis of the performance of all the models, including those from the original article and the newly implemented ones, is provided here. The enhancement in accuracy achieved through the new models and feature engineering is highlighted.

## 5. Conclusion

This section summarizes the key findings of the report, emphasizing the improvement in diabetes prediction accuracy achieved through the advanced machine learning techniques and feature engineering. It also notes the limitations of the study, such as its academic nature and limited scale for commercial applicability, and suggests potential avenues for future research, such as further hyperparameter tuning.

## References

Al-Zebari, A., & Sengur, A. (2019). Performance comparison of machine learning techniques on diabetes disease detection. *2019 1st International Informatics and Software Engineering Conference (UBMYK)*, 1–4. https://doi.org/10.1109/ubmyk48245.2019.8965542

Fadziso, T. (2020). Diabetes Detection using Machine Learning: A Systematic Literature Review. *Malaysian Journal of Medical and Biological Research*, *7*(2), 129–134. https://doi.org/10.18034/mjmbr.v7i2.555

Kopitar, L., Kocbek, P., Cilar, L., Sheikh, A., & Stiglic, G. (2020). Early detection of type 2 diabetes mellitus using machine learning-based prediction models. *Scientific Reports*, *10*(1). https://doi.org/10.1038/s41598-020-68771-z

*PIMA Indians Diabetes Database*. (2016, October 6). Kaggle. Retrieved March 19, 2025, from https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database/data

Rajendra, P., & Latifi, S. (2021). Prediction of diabetes using logistic regression and ensemble techniques. *Computer Methods and Programs in Biomedicine Update*, *1*, 100032. https://doi.org/10.1016/j.cmpbup.2021.100032
