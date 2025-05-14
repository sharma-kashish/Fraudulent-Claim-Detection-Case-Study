# Fraudulent-Claim-Detection-Case-Study
> Developed a predictive model for detecting fraudulent insurance claims using logistic regression and random forest.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Key Insights](#key-insights)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- **Objective:** To build a data-driven fraud detection model for Global Insure, classifying claims as fraudulent or legitimate.
- **Business Problem:** Manual fraud detection is inefficient, leading to financial losses. The goal is to predict fraudulent claims early in the approval process.
- **Dataset Overview:** The dataset consists of 40 columns and 1000 rows, including customer profiles, claim details, and incident characteristics.
- **Project Workflow:**
  1. Data Preparation & Cleaning
  2. Exploratory Data Analysis (EDA)
  3. Feature Engineering
  4. Model Building (Logistic Regression & Random Forest)
  5. Model Evaluation (Accuracy, Sensitivity, Precision, Recall, F1 Score)
  6. Final Predictions and Business Insights

## Technologies Used
- **Python Libraries:**
  - numpy - version 1.26.4
  - pandas - version 2.2.2
  - matplotlib - version 3.8.4
  - seaborn - version 0.13.2
  - statsmodels - version 0.14.2
  - scikit-learn - version 1.4.2
  - imbalanced-learn - version 0.11.0

## Conclusions
- **Best Performing Model:** Logistic Regression outperformed Random Forest in fraud detection.
- **Final Model Accuracy:** Logistic Regression achieved 84.00% accuracy, with better sensitivity and precision compared to Random Forest (82.33% accuracy).
- **Deployment Recommendation:** Logistic Regression is more suitable due to its superior recall and generalization capability.

## Key Insights
- **Fraudulent Patterns:**
  - Claims with **major damage** show **60.9% fraud probability**.
  - **High total claim amounts, injury claims, and vehicle claims** are common in fraudulent cases.
  - Certain **insured occupations and hobbies** show higher fraud likelihood.

- **Feature Importance:**
  - **Incident severity** is a key predictor.
  - **Police report availability reduces fraud likelihood** slightly.
  - **Auto models like Civic, X6, Silverado** tend to have higher fraud rates.

- **Business Implications:**
  - Early fraud detection minimizes financial losses.
  - Insights can help **optimize insurance approval workflows** and **strengthen risk management strategies**.
  - Suggested improvements include **real-time fraud monitoring systems** and **ensemble model approaches**.

## Acknowledgements
- This project was inspired by fraud detection research and machine learning methodologies.
- References from financial risk management and predictive modeling papers were considered.
- The project was based on structured tutorials and industry case studies.

## Contact
Created by [@sharma-kashish] - feel free to contact me!