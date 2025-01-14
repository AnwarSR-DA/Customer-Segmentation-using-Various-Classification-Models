# 📊Customer Segmentation using Various Classification Models

## 🛠️ Project Overview

This project focuses on customer segmentation using multiple classification models to understand customer behavior and boost retail sales performance. The goal is to predict user segments based on demographic and purchase data and compare the performance of various classification models.

## 📦 Dataset

- **Source**: e-Commerce Walmart Sales Dataset ([Kaggle Link](https://www.kaggle.com/datasets/devarajv88/walmart-sales-dataset))
- **Features**:
  - **Demographic**: Gender, Age, Occupation, Marital Status
  - **Location**: City Category, Years in Current City
  - **Product**: Product Category, Purchase Amount
- **Target Variable**: User segments classified as Low, Medium, and High based on purchase amount.

## 🧹 Data Preparation Steps

- **Data Cleaning**: No missing or duplicate values.
- **Data Transformation**: Encoded categorical features.
- **Data Splitting**: 60% training and 40% validation.
- **Standardization**: StandardScaler used for k-NN model.

## 📈 Models and Performance

- **k-Nearest Neighbors (k-NN)**: Accuracy 73.15%
- **Naive Bayes**: Accuracy 60.32%
- **Decision Tree (Default)**: Accuracy 75.78%
- **Pruned Decision Tree**: Accuracy 75.93%
- **Logistic Regression**: Accuracy 63.53%
- **Neural Networks**: Accuracy 74.27%
- **Linear Discriminant Analysis (LDA)**: Accuracy 63.04%

### 🎛️ Ensemble Methods:
- **Bagging**: 75.88%
- **AdaBoost**: 75.70%
- **Random Forest**: 75.72%

## ✅ Key Findings and Recommendations

- **Top Performers**: Bagging Ensemble and Pruned Decision Tree models achieved the highest accuracy rates (>75%).
- **Ensemble Advantage**: Ensemble methods consistently outperformed individual models.
- **Model Selection**: Consider trade-offs between accuracy, interpretability, and computational resources when choosing a model.

## 🌍 Real-World Implementation Scenarios

- **Personalized Marketing Campaigns**: Bagging and Pruned Decision Tree models can be used to segment customers for targeted marketing strategies, such as offering personalized discounts and advertisements.
- **Inventory Management**: Identify high-value customer segments to forecast demand for premium products and adjust stock levels accordingly.
- **Customer Retention Programs**: Classify customers who may need retention strategies based on their purchase behavior and design loyalty programs.
- **Business Insights**: Generate reports on customer segments to help stakeholders understand market behavior and make data-driven decisions.

## 📜 License

This project is licensed under the MIT License.
