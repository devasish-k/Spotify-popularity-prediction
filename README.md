# 🎵 Spotify Popularity Prediction

## 📌 Overview

This project focuses on building predictive models to estimate the popularity of songs on Spotify. The goal is to assist stakeholders in the music industry—such as producers, marketers, and record labels—by providing insights that inform artist signings, song selections, marketing strategies, and promotional efforts.

---

## 🗂️ Project Structure

### Notebook 1: `Part_A.ipynb`
- I. Importing the Dataset  
- II. Data Cleaning  
- III. Exploratory Data Analysis (EDA)  
- IV. Popularity Prediction using Regression  

### Notebook 2: `Part_B.ipynb`
- IV (continued). Popularity Prediction using Classification – Oversampling  

### Notebook 3: `Part_C.ipynb`
- IV (continued). Popularity Prediction using Classification – Undersampling  
- V. Comparison: Regression vs. Classification  
- VI. Conclusion  

---

## 🎯 Business Understanding

**Objective:**  
To develop a predictive model for estimating the popularity of Spotify tracks. This will support data-driven decisions in artist discovery, playlist planning, and marketing campaigns.

---

## 📊 Data Understanding

**Data Collection:**  
The dataset was sourced from Spotify’s API and includes a wide variety of track-level features such as tempo, energy, valence, and a popularity score.

**Exploratory Data Analysis (EDA):**  
Performed to understand feature distributions, detect outliers, and explore correlations with popularity.

---

## 🧹 Data Preparation

- Handled missing values and removed irrelevant columns  
- Used cyclical encoding for time-based features and one-hot encoding for categoricals  
- Applied power transformations to normalize skewed numerical features for better modeling performance  

---

## 🤖 Modeling

### Approach
- **Regression Models:** Used to predict popularity as a continuous variable  
- **Classification Models:** Used to categorize popularity into bins for better interpretability  

### Handling Imbalanced Classes
- **SMOTE (Synthetic Minority Oversampling Technique)**  
- **Undersampling** for majority classes  

### Model Selection & Optimization
- Initial regression models showed overfitting and low generalization (low R²)  
- Switched to classification models like **Random Forest** and **XGBoost**  
- Used **RandomizedSearchCV** for hyperparameter tuning  

---

## 📈 Evaluation

- Evaluated using classification metrics: Accuracy, Precision, Recall, F1-Score  
- Feature importance analysis to identify key drivers of song popularity  

---

## 🚀 Deployment & Recommendations

### Strategic Insights
- Use predictions to inform music production, A&R decisions, and marketing strategy  
- Assist in identifying high-potential tracks and optimizing release plans  

### Future Work
- Explore deep learning models for improved performance  
- Incorporate external data sources (e.g., lyrics, social media)  
- Add real-time data support for streaming prediction  

---

## ✅ Conclusion

Using the CRISP-DM framework, this project showcases the power of machine learning in the music industry. It highlights the importance of agile, data-driven decision-making in a rapidly evolving digital landscape.

---

> 📁 **Note:** This repository contains three Jupyter notebooks, each focusing on different modeling techniques and evaluation strategies.
