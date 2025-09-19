# 📱 Telco Usage Pattern Analysis & Subscription Prediction  

This project analyzes **Malaysian telco user data** to uncover patterns in usage behavior and predict whether a user is a **prepaid** or **postpaid** subscriber.  
It combines **data analysis, visualization, and machine learning (KNN with K-Fold validation)** to build and evaluate predictive models.  

---

## 🎯 Objectives  
1. Analyze Malaysian telco user data and extract meaningful features indicating subscription behavior.  
2. Develop a predictive classification model using **K-Nearest Neighbors (KNN)** to differentiate between prepaid and postpaid users.  
3. Evaluate classification accuracy by testing model consistency across different usage patterns using **K-Fold validation**.  

---

## 🧑‍💻 Project Workflow  
- **Data Collection**: Survey responses from **681 respondents** on telco usage patterns.  
- **Data Preprocessing**: Cleaned and prepared categorical and numerical attributes.  
- **Exploratory Data Analysis (EDA)**: Visualized attributes using **Matplotlib** (bar plots, histograms, distributions).  
- **Model Training**: Applied **KNN** and validated results using **K-Fold cross-validation**.  
- **Evaluation**: Compared training and testing accuracy to assess model performance.  

---

## 📊 Results  
- **KNN Model**  
  - Train Accuracy: **1.0**  
  - Test Accuracy: **0.75**  

- **K-Fold Validation (KNN)**  
  - Train Accuracy: **1.0**  
  - Test Accuracy: **1.0**  

✅ The **K-Fold KNN model** performed best, achieving **100% accuracy** on test data, indicating high reliability in predicting subscription type.  

---

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/nurinqurratu/telco-subscription-prediction.git
