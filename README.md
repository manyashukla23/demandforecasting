# 📦 Demand Forecasting Using SARIMA

This project applies time series forecasting techniques to predict future product demand using three years of sales data from a superstore in Los Angeles, California.

## 🧠 Objective
To develop a machine learning model that accurately forecasts product demand to:
- Enhance customer service
- Improve order fulfillment and inventory planning
- Provide actionable insights into most/least demanding items

## 📂 Dataset
**Source:** [Superstore Sales Dataset on Kaggle](https://www.kaggle.com/datasets/shivam1901/superstore)  
Focus: Daily sales of paper products in Los Angeles

## 🔍 Approach

### 1. Exploratory Data Analysis
- Plotted monthly sales trends
- Identified strong seasonality in demand patterns

### 2. Stationarity Check
- Used the **Augmented Dickey-Fuller (ADF) test**
- P-value < 0.05 → data is stationary and ready for modeling

### 3. Model Selection: SARIMA
- **SARIMA** = Seasonal ARIMA, ideal for univariate time series with seasonal patterns
- Parameters tuned via:
  - ACF and PACF plots
  - Grid search for optimal seasonal and non-seasonal parameters

### 4. Model Training & Testing
- Split data into **21 months for training** and **3 months for testing**

## 📈 Model Output
- **Accuracy Measure**:  
  - **MAPE** (Mean Absolute Percentage Error): `8.26%`

## 🚀 Future Applications
- 📦 **Order Fulfillment**: Improve delivery speed and reduce lead times
- 🛍️ **Customer Experience**: Personalized promotions using demand trends
- 📣 **Proactive Communication**: Prepare for demand spikes
- 🎧 **Customer Service**: Equip teams with insights to respond better
- 🔁 **Feedback Loop**: Use customer input to fine-tune forecasts

## 🛠️ Tech Stack
- Python
- pandas, statsmodels, matplotlib
- Time series modeling with SARIMA

---

**Author:** Manya Shukla  
**Project Type:** Kaggle-based Time Series Forecasting  
