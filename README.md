# 📈 Stock Price Prediction using Linear Regression

A simple yet effective **stock price prediction model** using **Linear Regression**. This project leverages **Yahoo Finance (`yfinance`) data**, applies **feature engineering**, and trains a **machine learning model** to predict **next-day stock prices**.

 **Why this is unique?**
- **Feature Engineering**: Uses **moving averages (MA_5, MA_10, MA_20)** alongside price & volume.
- **High Accuracy**: Achieves **R² score of 0.9591** with **low error (MAE = 1.61)**.
- **Easy to Run**: Works with minimal dependencies and clear structure.
- **Recruiter-Ready**: Well-documented for showcasing on GitHub.

---

## **Project Overview**
- **Goal**: Predict the next day's **closing stock price** using historical data.
- **Dataset**: Pulled from **Yahoo Finance** (`yfinance`).
- **Model**: **Linear Regression** (Baseline).
- **Performance**:
  -  **R² Score**: **0.9591** (95.91% variance explained)
  -  **MAE**: **1.61**
  -  **MSE**: **4.53**

---

## 🔧 **Installation**
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/stock-price-prediction-ML.git
cd stock-price-prediction-ML
```

### 2️⃣ Create & Activate a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 🚀 **Usage**
###  Run in Jupyter Notebook
1. Open Jupyter Notebook
```bash
jupyter notebook
```
2. Navigate to `notebooks/stock_price_prediction.ipynb` and run all cells.


## 📈 **Results & Insights**
- The model predicts **stock price trends accurately** using historical data.
- **Strong R² score (0.9591)** proves that price movement is **highly correlated with past values**.
- **Limitations**:  
  - Doesn't capture **market events/news impacts**.  
  - Works well for **trend following**, but less for **sharp price swings**.  

 **For a detailed performance review, check [`reports/key_insights.pdf`](reports/key_insights.pdf).**

---
💡 Found an issue? Want to contribute? Fork this repo and submit a pull request!  
---

## 🛠️ **License**
This project is **open-source** and available under the **MIT License**.
