# Predicting Hotel Booking Cancellations 🏨

## 📝 Background :
 Industry data shows that the average reservation cancellation rate is 37%, leading to losses every year. In the hospitality industry, the reservation cancellation rate is a critical factor that affects the operational balance and revenue of the hotel.

A high cancellation rate not only threatens the company's revenue, but also disrupts customer service quality.

## 📝 Objective : 
The purpose of this project is to analyze and understand the factors that contribute to the reservation cancellation rate at a hotel.
Identify cancellation patterns and trends, identify key factors that influence cancellation decisions, and provide business recommendations for hotel management.
Build a machine learning model to predict booking cancellations

📊 Dataset : The dataset includes 32 features, 83,293 rows, and 1 target.

## 🛠️ Method and Libraries 🛠️
I did EDA (Exploratory Data Analysis) as a start to explore and understand the patterns in the data. Then I did data preprocessing, starting with handling missing values, doing feature engineering, and encoding data.
I used several machine learning models for comparison. Then tuning the hyperparameters, and trying the SMOTE method to overcome imbalanced data.

This project uses basic packages such as `numpy`, `pandas`, `matplotlib`, `seaborn`, and `sklearn`, which have been faithful companions throughout this journey.

## Result 🔬
After careful exploration, data preprocessing, training of multiple models, and hyperparameter tuning, the Random Forest model emerged as the best performing model with the metric results shown below:

    F1 Score: 0.8384557407252324
    Recall: 0.809115888152578
    Precision: 0.870003475842892
    AUC: 0.9521200361214766
