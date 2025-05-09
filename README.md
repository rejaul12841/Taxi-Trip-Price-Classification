# Taxi-Trip-Price-Classification
# 🚕 Taxi Trip Pricing Prediction Using Feature Analysis

This project uses classification algorithms to predict taxi trip pricing levels (Low, Medium, High) based on trip-related features such as distance, duration, traffic, and weather.

## 📊 Problem Statement

Given various features of a taxi trip, predict the price level category of the trip:
- **Low**: Price ≤ 20
- **Medium**: 21 ≤ Price ≤ 40
- **High**: Price > 40

##  Dataset

The dataset contains information on:
- Trip Distance
- Trip Duration
- Time of Day
- Day of Week
- Traffic Conditions
- Weather
- Trip Price (target)

## 🧪 Methodology

- **Data Cleaning & Preprocessing**
  - Handled missing values.
  - Label encoding applied to categorical features.
  - Price column converted into 3-class categorical target (`Price_Level`).

- **Exploratory Data Analysis**
  - Count plots and histograms to understand data distribution.
  - Heatmap to identify feature correlation.

- **Train-Test Split**
  - 80:20 ratio used.
  - `random_state=42` for reproducibility.

- **Models Used**
  - Support Vector Machine (Linear Kernel)
  - Support Vector Machine (RBF Kernel)
  - Logistic Regression (L1 Regularization)
  - Logistic Regression (L2 Regularization)

## 📈 Performance Evaluation

| Model                      | Accuracy | Precision | Recall | F1-Score |
|---------------------------|----------|-----------|--------|----------|
| SVM (Linear Kernel)       | 0.98     | 0.98      | 0.98   | 0.979    |
| SVM (RBF Kernel)          | 0.945    | 0.949     | 0.945  | 0.939    |
| Logistic Regression (L1)  | 0.95     | 0.951     | 0.95   | 0.947    |
| Logistic Regression (L2)  | 0.91     | 0.911     | 0.91   | 0.906    |

**Conclusion:**  
SVM with Linear Kernel outperformed all other models, making it the most effective for this classification problem.

## 📎 Project Link (Kaggle)
(https://www.kaggle.com/code/rejaul5/project303)

## 📎 GitHub Repository
[Taxi Trip Price Classification Project](https://github.com/yourusername/Taxi-Trip-Price-Classification)
