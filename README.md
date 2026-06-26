# High Dimensional Cancer Classification on the ARCENE Dataset

## Project  Overview

This project compares several statistical learning methods for classifying cancer and normal samples using the ARCENE dataset.
The ARCENE dataset is a high-dimensional dataset containing 200 observations and 10,000 features derived from mass spectrometry data. 
The goal is to identify the method that provides the most accurate and interpretable classification while addressing the challenges of high-dimensional data.

## Research Question

Which statistical learning or machine learning method provides the most accurate and interpretable classification of cancer versus normal samples in the ARCENE dataset?

Because a missed cancer diagnosis has a greater clinical cost than a false positive result, model performance is evaluated primarily using sensitivity, while specificity and overall classification error are also considered.

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

The dataset represents a high-dimensional classification problem where the number of predictors is much larger than the number of observations.

## Key Results

* PCA + LDA achieved the best overall performance.
* PCA + LDA correctly identified all cancer cases in the test set (Sensitivity = 1.00).
* PCA + LDA also produced the highest specificity (0.852) and the lowest error rate (0.10).
* GRRF achieved perfect sensitivity while reducing the feature set from 9,940 predictors to only 13 selected features.
* PCA + Logistic Regression and Random Forest provided competitive results and served as strong baseline models.
* Bagging had the lowest sensitivity and was the weakest-performing method in this comparison.

Overall, PCA + LDA was selected as the recommended model because it provided the best balance of sensitivity, specificity, and classification accuracy for cancer detection.

## Skills Demonstrated

* Statistical Learning
* High-Dimensional Data Analysis
* Principal Component Analysis (PCA)
* Logistic Regression
* Linear Discriminant Analysis (LDA)
* Bagging
* Random Forest
* Guided Regularized Random Forest (GRRF)
* Feature Selection
* Model Evaluation and Confusion Matrices
* R Programming

## Repository Contents

* Arcene_Analysis.R
* Arcene_Analysis.Rmd
* Arcene_Report.pdf
* Arcene_Presentation.pptx
* Figures and Visualizations

## Author

Massogona Cisse

Bachelor of Science in Mathematics–Statistics

University of Central Oklahoma
