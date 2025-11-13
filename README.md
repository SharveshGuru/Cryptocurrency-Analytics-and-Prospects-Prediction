# 🚀 Cryptocurrency Analytics and Prospects Prediction
### Intelligent Crypto Market Forecasting and Analysis Platform

---

## 📘 Project Overview
**Cryptocurrency Analytics and Prospects Prediction** is an **AI-powered web application** designed to analyze, visualize, and predict cryptocurrency price movements using **machine learning models** and **data visualization techniques**.  

Developed as part of a **Capstone Project (Honours)** at *R.M.K. Engineering College*, the platform provides real-time market insights, predictive analytics, and asset discovery functionalities for both **investors** and **financial analysts**.  

---

## 🧠 Core Features
| Module | Description |
|:--|:--|
| **1. Data Acquisition** | Fetches real-time and historical cryptocurrency data using the Yahoo Finance API via `yfinance`. |
| **2. Data Pre-processing** | Handles missing values, outliers (via IQR), normalization, and data integrity. |
| **3. Feature Engineering** | Generates advanced technical indicators – SMA, EMA, RSI, MACD, Bollinger Bands, ATR, etc. |
| **4. Exploratory Data Analysis (EDA)** | Interactive visualization of trends, volatility, correlations, and risk distribution. |
| **5. Predictive Modeling** | Trains and compares multiple models: **Linear Regression**, **Random Forest**, **XGBoost**, and **ARIMA**. |
| **6. Asset Discovery & Ranking** | Identifies and ranks top-performing cryptocurrencies using a multi-factor composite score. |
| **7. Visualization Dashboard** | Streamlit-based dashboard with interactive charts, risk insights, and trading signal interpretation. |

## ⚙️ Tech Stack
| Category | Technologies Used |
|-----------|------------------|
| **Language** | Python 3.9+ |
| **Frontend / Dashboard** | Streamlit |
| **Libraries** | Pandas, NumPy, Scikit-learn, XGBoost, Statsmodels, Plotly, Matplotlib, Seaborn |
| **Data Source** | Yahoo Finance API (`yfinance`) |
| **Visualization** | Plotly Graph Objects, Plotly Express |
| **Version Control** | Git & GitHub |
| **Deployment (Optional)** | Streamlit Cloud |

## 🖥️ Running the Application
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/SharveshGuru/Cryptocurrency-Analytics-and-Prospects-Prediction
cd Crypto-Analytics-Prediction
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Launch the Streamlit App
```bash
streamlit run main.py
```
### 4️⃣ Access the Dashboard
Open your browser and navigate to:  
👉 http://localhost:8501  

---

## 🧰 Sidebar Configuration
The Streamlit sidebar allows the user to configure:
- **Cryptocurrency**: Select BTC, ETH, BNB, etc.
- **Time Period**: 1mo / 3mo / 6mo / 1y / 5y / max
- **Models to Train**: Choose from Linear Regression, Random Forest, XGBoost, ARIMA
- **Test Size**: Adjustable (10%–40%)
- **Feature Options**: Enable/disable technical indicators
- **Comparison Mode**: Compare multiple cryptocurrencies

---

## 📈 Sample Dashboard Sections
- **Trend Analysis Graphs** (SMA, RSI, MACD, Volume Trends)
- **Volatility & Risk Analysis**
- **Model Performance Comparison**
- **Prediction Visualization**
- **Feature Importance (Tree-Based Models)**
- **Asset Ranking Table**
- **Trading Signal Summary (Buy/Sell/Hold)**

---

## 🧩 Dataset
- **Source:** [Yahoo Finance](https://finance.yahoo.com)
- **Data Format:** OHLCV (Open, High, Low, Close, Volume)
- **Fetched via:** `yfinance` Python library
- **Update Frequency:** Real-time / On-Demand

---

## 📚 Academic Context
> **Capstone Project – 22CB932 (Honours)**  
> Department of Computer Science and Business Systems  
> **R.M.K. Engineering College (Autonomous)**  
> November 2025

**Authors:**
- 🧑‍💻 *S Sharvesh Guru*
- 🧑‍💻 *Kavindar A*
- 🧑‍💻 *Nirranjan Sai D H*
- 👩‍🏫 *Supervisor:* Mrs. S. Jhansi Ida (Associate Professor)

## 📄 License
This project is licensed under the **MIT License** – feel free to use and modify with attribution.
