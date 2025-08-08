# System Threat Detection

This project was a part of the **Diploma in Data Science Programme** offered by **IIT Madras**.  
It aims to detect whether a system is under threat using **data analysis** and **machine learning** methods.  
The project was completed under the guidance of **Dr. Ashish Tendulkar**, Research Software Engineer, Google AI.

This project was developed as a part of the  
[System Threat Forecaster Kaggle Competition](https://www.kaggle.com/competitions/System-Threat-Forecaster/leaderboard), where I was ranked at the **46th position** on a leaderboard of 1519 participants.

---

## Overview
The Jupyter Notebook walks through the complete workflow of threat detection, from raw data to actionable insights.  
The project is structured into four main stages:

1. **Data Cleaning** – Removing inconsistencies, handling missing values, and preparing data for analysis.
2. **Exploratory Data Analysis (EDA)** – Visualizing trends, anomalies, and relationships in the data.
3. **Feature Engineering** – Creating meaningful features to improve model performance.
4. **Machine Learning Models** – Implementing and evaluating multiple algorithms for threat detection.

A variety of **statistical methods** and **visualization techniques** (heatmaps, correlation plots, distribution analysis) were used to identify patterns and potential indicators of malicious activity. Three ML models were trained to detect threat, and the best one was employed for the final testing. 

---

## Key Highlights
- **Cleaned** the data (e.g. outlier removal, and data imputations)
- Extracted the **important features** (checks multi-collinearity, variance thresholds etc.)
- Applied **supervised learning** to classify normal vs. suspicious activity.
- Used **model evaluation metrics** such as accuracy, precision, recall, and F1-score.
- Identified the most significant features contributing to threat detection.

---

---

## Results
Three separate models were trained to generate the best output. The models were 
1. Random Forest
2. XGBoost
3. LightGBM

LightGBM generated best results on validation set. It achieved **63% accuracy** on unseen test data.

---
