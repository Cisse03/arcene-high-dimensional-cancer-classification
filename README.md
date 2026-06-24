# High-Dimensional Cancer Classification on the ARCENE Dataset

## Project Overview

This project compares several statistical learning and machine learning methods for classifying cancer and normal samples using the ARCENE dataset. The dataset contains 200 observations and 10,000 features from mass spectrometry data, making it a high-dimensional classification problem. The goal is to determine which method provides the most accurate and interpretable classification of cancer and normal samples.

## Research Question

Which statistical learning or machine learning method provides the most accurate and interpretable classification of cancer versus normal samples in the ARCENE dataset?

Because missing a cancer diagnosis can have serious consequences, this project focuses primarily on sensitivity while also considering specificity and overall classification error.

## Methods


The following methods were compared:

* PCA + Logistic Regression
* PCA + Linear Discriminant Analysis (LDA)
* Bagging
* Random Forest
* Guided Regularized Random Forest (GRRF)

## Dataset

* Dataset: ARCENE
* Source: NIPS 2003 Feature Selection Challenge
* Observations: 200
* Features: 10,000
* Response Variable: Cancer vs. Normal

The dataset represents a high-dimensional setting where the number of predictors is much larger than the number of observations.

## Key Results

* PCA + LDA achieved the best overall performance among the methods evaluated.
* PCA + LDA correctly identified all cancer cases in the test set and had the lowest classification error.
* GRRF achieved perfect sensitivity while reducing the feature set to only 13 selected predictors.
* PCA + Logistic Regression and Random Forest produced competitive results and served as strong baseline models.
* Bagging had the weakest performance, particularly in terms of sensitivity.

Overall, PCA + LDA was selected as the recommended model because it provided the best balance of sensitivity, specificity, and overall classification accuracy.

## Skills Demonstrated

* Statistical Learning
* Machine Learning
* High-Dimensional Data Analysis
* Principal Component Analysis (PCA)
* Logistic Regression
* Linear Discriminant Analysis (LDA)
* Bagging
* Random Forest
* Guided Regularized Random Forest (GRRF)
* Feature Selection
* Model Evaluation
* Confusion Matrix Analysis
* R Programming

## Repository Contents

* arcene_final.Rmd
* arcene_final.html
* High-Dimensional Cancer Classification on the ARCENE Dataset.pdf
* Arcene_final.pptx

## Author

Massogona Cisse

Bachelor of Science in Mathematics–Statistics

Accelerated Degree Program (ADP) in Statistics

University of Central Oklahoma


