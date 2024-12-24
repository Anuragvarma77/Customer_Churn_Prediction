# Customer_Churn_Prediction
# Customer Churn Prediction Using Decision Tree

This project aims to predict customer churn using a Decision Tree model, enabling businesses to identify at-risk customers and take proactive measures to improve retention.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [How to Use](#how-to-use)
- [Future Work](#future-work)
- [Contributing](#contributing)
- [License](#license)

## Overview
Customer churn prediction is crucial for businesses aiming to retain customers and reduce revenue loss. This project uses a Decision Tree classifier to analyze customer data and predict the likelihood of churn.

## Dataset
The dataset includes features such as:
- Customer Demographics (e.g., Age, Gender, Location)
- Account Information (e.g., Contract Type, Monthly Charges, Tenure)
- Usage Patterns (e.g., Internet Service, Phone Service)
- Churn Indicator (target variable)

The dataset is clean and publicly available, making it ideal for churn analysis.

## Data Preprocessing
Key preprocessing steps:
- Handling missing or inconsistent data.
- Encoding categorical variables using label encoding or one-hot encoding.
- Normalizing numerical features to improve model efficiency.
- Splitting the data into training and testing sets.

## Modeling
The Decision Tree model was chosen for its interpretability and ability to handle categorical and numerical data effectively. The following steps were performed:
- Training the Decision Tree classifier on the training data.
- Fine-tuning hyperparameters such as maximum depth and minimum samples split.
- Evaluating the model using metrics like accuracy, precision, recall, and F1-score.

The Decision Tree model effectively identified churn patterns and provided actionable insights.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Anuragvarma77/customer-churn-prediction.git
