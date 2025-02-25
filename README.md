# Breast Cancer  Model

## Project Overview

This project implements a **Breast Cancer Classification Model** using **Logistic Regression**. The goal is to classify breast tumors as either **Malignant (M) or Benign (B)** based on input features extracted from biopsy data. The model is trained on labeled data and can make predictions on new, unseen inputs.

## Features 

- The model is built using **scikit-learn** and trained on a dataset containing **569 samples** with **32 numerical features**.
- These features describe various attributes of cell nuclei, such as **radius, texture, perimeter, area, and smoothness**.
- The dataset was preprocessed to remove any unnecessary columns and normalize feature values for better performance.

## Model Training and Evaluation

1. **Data Preprocessing**

   - Loaded the dataset using `pandas`.
   - Checked for missing values and cleaned unnecessary data.
   - Split the dataset into **training** and **testing** sets.

2. **Model Training**

   - Implemented **Logistic Regression** from `scikit-learn`.
   - Trained the model on the training dataset.

3. **Evaluation Metrics**

   - The model’s performance is evaluated using **accuracy score**.
   - It is tested on both training and test datasets to check for overfitting or underfitting.


