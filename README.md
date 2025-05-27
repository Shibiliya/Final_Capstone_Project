# Final_Capstone_Project
# Predicting Global Air Quality Levels Using Weather Data and Machine Learning
# Overview :
  This machine learning project predicts **air quality levels** based on weather-related features such as temperature, humidity, pressure, and wind speed. Using classification algorithms, the model categorizes air quality according to the **US EPA Index**, helping in environmental monitoring and public health awareness.
# Problem Statement :
The goal is to classify air quality into categorical levels (Good, Moderate, Unhealthy, etc.) using historical weather data. The classification helps in understanding pollution patterns and serves as a foundational step for real-time air quality alert systems.
# Technologies Used :
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- imbalanced-learn (for SMOTE)
- joblib (for saving models)  
- Google Colab
# Data Preprocessing :
- Dropped irrelevant or redundant features  
- Handled missing values  
- Target encoded categorical variables  
- Scaled numerical features using `StandardScaler`  
- Balanced the dataset using **SMOTE** (Synthetic Minority Over-sampling Technique)
# Models Tried :
- Logistic Regression  
- Support Vector Classifier (SVC)  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting Classifier

Each model was evaluated using multiple performance metrics. The **best-performing model** was selected based on F1-score and overall balance of precision and recall.
# Evaluation Metrics :
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  
- Classification Report
 # Deployment :
The final model is saved using `joblib` as `air_quality_rf_pipeline.pkl` and is ready for deployment in web or cloud-based applications using Flask, Streamlit, or other frameworks.
# Author :
**Shibiliya**
Aspiring Data Analyst | Passionate about Data Science & Machine Learning

