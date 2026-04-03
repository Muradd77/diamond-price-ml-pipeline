# diamond-price-ml-pipeline
End-to-end machine learning pipeline for predicting diamond prices using regression techniques.
# 💎 Diamond Price Prediction Pipeline

## 📌 Introduction
This project focuses on building an end-to-end Machine Learning pipeline to predict diamond prices based on various physical and categorical features. The pipeline automates preprocessing, feature engineering, and model training steps to ensure a scalable and clean workflow.

## 🎯 Objective
The main objective is to develop a regression model capable of accurately predicting diamond prices using structured data. This project also demonstrates how to integrate preprocessing and modeling into a single pipeline.

## 📊 Dataset Description
The dataset includes the following features:

- **Carat** – Weight of the diamond
- **Cut** – Quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- **Color** – Diamond color grading
- **Clarity** – Measurement of internal flaws
- **Price** – Target variable

## 🔍 Exploratory Data Analysis (EDA)
During the analysis phase:
- Checked for missing values
- Analyzed feature distributions
- Identified relationships between features and target variable
- Visualized correlations

## ⚙️ Data Preprocessing
The following preprocessing steps were applied:

- Handling categorical variables using encoding techniques
- Feature scaling (Standardization / Normalization)
- Splitting dataset into training and testing sets

## 🏗️ Machine Learning Pipeline
A pipeline was implemented using Scikit-learn to streamline the workflow:

- Data preprocessing
- Feature transformation
- Model training

This ensures:
- Cleaner code
- Reduced risk of data leakage
- Easier reproducibility

## 🤖 Model Selection
Regression algorithms were used to predict prices. The model was trained and evaluated using standard machine learning practices.

## 📈 Evaluation Metrics
The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

## 🚀 Results
- The model achieved reasonable prediction accuracy
- Pipeline structure improved efficiency and scalability

## 📁 Project Structure
