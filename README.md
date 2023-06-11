# Credit Risk Analysis

## Overview

Credit Risk Analysis is an essential process for banks and other financial institutions that provide loans to individuals or companies. This repository contains a machine learning based solution that predicts credit risk, using historical lending activity data from a peer-to-peer lending services company.

The primary objective of this project is to build a model that accurately identifies the creditworthiness of borrowers. It poses a classification problem that's inherently imbalanced, as healthy loans easily outnumber risky loans. The challenge here is to ensure that our model is well-trained to identify both classes effectively.

## Description

This project involves building and comparing two machine learning models:
1. Logistic Regression Model trained on original data
2. Logistic Regression Model trained on resampled data using the RandomOverSampler module from the imbalanced-learn library

The stages of machine learning included splitting the data into training and testing sets, creating the Logistic Regression model with the original data, predicting using this model, and repeating this process with a resampled training dataset.

## Results

The results of this analysis are documented in the Credit Risk Analysis Report. It includes the balanced accuracy scores, and the precision and recall scores of both machine learning models. This information provides an understanding of the performance of the models in terms of accuracy, false-positive rate, and the ability to detect high-risk loans.

## Conclusion

The analysis concluded with the comparison of the performance of the two models and a recommendation for the model to be used. The model trained with oversampled data performed better in detecting high-risk loans, hence is recommended for use.

## How to Use

The code for this analysis is contained within a Jupyter Notebook. To use, you would clone the repository, install the necessary Python libraries, and then open and run the Jupyter Notebook.

## Dependencies

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Pathlib
