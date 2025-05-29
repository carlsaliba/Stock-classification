# Stock Classification – CFM Data Challenge

This project was developed as part of the **CFM Data Challenge** at École Centrale de Nantes, focused on classifying stocks from high-frequency trading data. Our team achieved **1st place in the class**.

## 🧠 Objective

Classify sequences of tick-level trading data into one of 24 stocks using machine learning and deep learning techniques.

## 🧰 Methods

- **Feature Engineering**: global statistics, spread features, venue frequency, autocorrelation
- **Models**:
  - Random Forest & XGBoost (tabular format)
  - XGBoost with wide-format features and GPU acceleration
  - **Bi-directional LSTM** – best performance (**Score: 0.4026**)

## 📊 Results

| Model         | Score   |
|---------------|---------|
| Random Forest | 0.2814 |
| XGBoost v1    | 0.2748 |
| XGBoost v2    | 0.2510 |
| **Bi-LSTM**   | **0.4026** ✅

## 🛠 Tools

- Python, Jupyter Notebook  
- Scikit-learn, XGBoost, TensorFlow/Keras  
- Kaggle (for GPU/TPU training)  
- Overleaf (report)

## 👥 Authors

Karl Saliba, Youssef Salhi  
Supervised by Bertrand Michel  
École Centrale de Nantes – December 2024
