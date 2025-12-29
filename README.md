## 🥗 NutriClass: Food Classification Using Nutritional Data
📌 Project Overview

NutriClass is a machine learning project that classifies food items into multiple food categories using their nutritional values and food attributes.
The goal of this project is to demonstrate how tabular nutritional data can be leveraged to build an effective multi-class classification system.

This project simulates a real-world scenario where food items need to be automatically identified and categorized for applications such as diet tracking, health monitoring, and meal planning systems.

## 🎯 Problem Statement

With increasing dietary awareness, understanding and categorizing food based on nutritional composition has become essential.
The objective of this project is to:

Predict the food category (Food_Name) based on nutritional attributes such as calories, protein, fat, carbohydrates, sugar, and other food-related features.

## 🧠 Approach & Methodology
## 1️⃣ Data Understanding & Exploration

Loaded and inspected dataset structure

Checked dataset size and feature types

Analyzed class imbalance

Identified missing values

## 2️⃣ Data Preprocessing

Handled missing values

Converted boolean features to binary format

Encoded categorical features

Scaled numerical features using standardization

Prepared data for machine learning models

## 3️⃣ Feature Engineering

Separated numerical and categorical features

Applied encoding techniques

(Optional) Applied dimensionality reduction for comparison

## 4️⃣ Model Training

Multiple machine learning models were trained and compared:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

K-Nearest Neighbors (KNN)

Gradient Boosting Classifier

## 5️⃣ Model Evaluation

Each model was evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

This allowed a fair comparison of model performance, especially considering the imbalanced nature of the dataset.

## 📊 Results & Insights

Tree-based models such as Random Forest and Gradient Boosting performed better on complex nutritional patterns.

Scaling significantly improved performance for distance-based models like KNN.

Nutritional features such as Calories, Fat, Sugar, and Sodium played a key role in classification.

Class imbalance impacted performance, making F1-score an important evaluation metric.


## 💼 Business Use Cases

🥑 Smart Dietary Applications – Food recommendations based on nutrition

🧑‍⚕️ Health Monitoring Tools – Assist dieticians in food categorization

📱 Food Logging Systems – Auto-classify food entries

🎓 Educational Platforms – Learn nutrition concepts through AI

🛒 Meal Planning Apps – Suggest alternatives within the same food category

## 👩‍💻 Author

## Bhargavi A B
Aspiring Data Analyst | Machine Learning Enthusiast
