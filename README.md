# **"Utilizing Sampling Methods and Machine Learning Models for Credit Card Fraud Detection"** 

## Overview

This project focuses on finding ways to fix the imbalance in datasets and test how well different machine learning models perform. The dataset used is for detecting credit card fraud, which has more legitimate transactions than fraudulent ones. The goal is to use five different techniques to balance the data and then test five machine learning models to see which one works best.

## Dataset

The dataset used in this project is available for download from the following link:
https://github.com/AnjulaMehto/Sampling_Assignment/blob/f0c491556cded07517283c75e603bccb70112c26/Creditcard_data.csv 
Credit Card Data CSV

## Data Description

Class: This shows whether the transaction is fraudulent (1) or not (0).

V1 to V28: These are different features that describe details about the transaction.

## Objective

Download and load the dataset.
Balance the dataset using different sampling techniques.
Apply five sampling techniques and evaluate them using five machine learning models.
Compare the performance of each sampling technique with each machine learning model to determine the best combination for detecting credit card fraud.

## Sampling Techniques

Random Undersampler : Randomly reduces the majority class to balance the dataset.

Random Oversampler : Randomly increases the minority class by replicating examples.

Tomek Links Sampling : Removes instances from the majority class that are the nearest neighbors of minority class examples.

SMOTE Sampling : Synthetic Minority Over-sampling Technique (SMOTE) generates synthetic examples in the feature space.

NearMiss Sampling : Selects examples of the majority class that are closest to the minority class.

## Machine Learning Models

Logistic Regression 

Decision Tree 

Random Forest 

GradientBoosting

ExtremeGradientBoost

Each model is trained and tested with the five sampling techniques, and performance is evaluated using accuracy.

![My Image](image.png)

## After evaluating the performance of various sampling techniques combined with different machine learning models, the results revealed that RandomForestClassifier along with oversampler sampling method had the most accuracy of 0.997817
