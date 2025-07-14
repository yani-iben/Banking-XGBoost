# Predicting Term Deposit Subscriptions with XGBoost

This project applies machine learning techniques to analyze the effectiveness of a marketing campaign by a Portuguese bank. Using the XGBoost classifier, the goal is to **predict whether a customer will subscribe to a term deposit** based on various demographic and campaign-related factors.

---

## Project Objective

Given a dataset from a direct marketing campaign (phone calls) of a Portuguese banking institution, this project aims to:

- Predict whether a client will **subscribe to a term deposit**.
- Identify the most important factors that influence this decision.
- Use **XGBoost** for classification and performance.
- Visualize **feature importance** to better understand the campaign’s impact.

---

## Dataset Overview

The dataset includes information such as:

- Customer demographics (e.g., age, job, marital status)
- Contact communication type
- Campaign-related information (e.g., number of contacts, previous campaign outcome)
- Economic indicators (e.g., employment variation rate, consumer price index)

The target variable is `y`, indicating whether the customer subscribed to a term deposit (`yes` or `no`).

---

## Tools & Libraries

- **Python 3**
- **scikit-learn**
- **XGBoost**
- **category_encoders** (for Target Encoding)
- **Pandas / NumPy / Matplotlib / Seaborn**

---

## Methodology

1. **Data Cleaning & Preprocessing**
   - Handled categorical variables using **Target Encoding**.
   - Split the data into training and testing sets.
   
2. **Model Building**
   - Implemented a machine learning pipeline using `sklearn.pipeline.Pipeline`.
   - Used `XGBClassifier` as the final model with `random_state=8` for reproducibility.
   
3. **Evaluation**
   - Measured model performance using accuracy and confusion matrix.
   - Plotted **feature importance** to understand which factors most influenced subscription likelihood.

---

##  Key Insights

Some of the most important predictors for whether a customer subscribed to the term deposit were:

- **Customer age**
- **Employment variation rate** (a macroeconomic indicator)
- **Previous marketing contact outcome**
- **Number of contacts during the campaign**

These features suggest that both personal demographics and broader economic context influence customer decisions.

---

## Feature Importance Plot

At the end of the analysis, a **feature importance plot** is included to visualize the key drivers of model predictions.

---



