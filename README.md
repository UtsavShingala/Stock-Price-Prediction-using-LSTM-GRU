# 📈 Stock Price Prediction using LSTM & GRU

## 📌 Overview
This project implements deep learning models — **Long Short-Term Memory (LSTM)** and **Gated Recurrent Unit (GRU)** — to predict **gold prices** based on historical market data. The goal is to leverage sequence modeling techniques for time series forecasting and compare the effectiveness of LSTM and GRU architectures.

## 🎯 Objectives
- Analyze gold price trends from historical data  
- Build and train LSTM and GRU models for future price prediction  
- Compare the modeling approaches on accuracy and efficiency  
- Visualize predicted vs. actual stock prices

## 📂 Dataset
- **Source:** [Kaggle / Public Financial Dataset](your-dataset-link) *(replace with actual link)*  
- **Features Used:** Date, Open, High, Low, Close, Volume  
- **Preprocessing Steps:**  
  - Handle missing values  
  - Normalize the dataset  
  - Convert time series into supervised learning format

## 🛠️ Tech Stack
- **Languages:** Python  
- **Libraries:**  
  - NumPy, Pandas, Matplotlib, Seaborn  
  - Scikit-learn  
  - TensorFlow / Keras  
- **Tools:** Jupyter Notebook, Google Colab, GitHub

## 🔍 Methodology
1. **Data Preprocessing:** Scaling, feature engineering, and sequence creation  
2. **Modeling:**  
   - LSTM for learning long-term dependencies  
   - GRU for faster computation with competitive performance  
3. **Training:** Hyperparameter tuning for optimal results  
4. **Evaluation:** MSE, RMSE, MAE, R² score  
5. **Visualization:** Time series plots for actual vs. predicted prices
