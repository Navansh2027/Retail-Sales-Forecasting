# Retail Sales Analysis & Forecasting (End-to-End AI Project)

##  Project Overview
This project analyzes retail transaction data to identify customer purchasing behaviors, seasonal trends, and profit drivers. It culminates in a **Machine Learning pipeline** that forecasts daily sales with high accuracy using **Random Forest Regressor** and engineered time-series features (Lag & Rolling Means).

The goal was to move beyond simple descriptive analytics and provide **actionable business intelligence** (Customer Segmentation) and **predictive capability** (Sales Forecasting).

## Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Linear Regression, Random Forest)
* **Techniques:** RFM Analysis, Time-Series Forecasting, Feature Engineering

---

## Key Analysis & Insights

### 1. Exploratory Data Analysis (EDA)
* **Seasonality:** Identified a consistent sales spike in **Q4 (November-December)**, indicating a strong holiday dependency.
* **Profitability:** While "Furniture" drives high revenue, it suffers from low profit margins compared to "Technology" and "Office Supplies."

### 2. Customer Segmentation (RFM Analysis)
Using **Recency, Frequency, and Monetary (RFM)** scores, I segmented the customer base to find high-value clients.
* **Top Insight:** identified the top 5% of "VIP Customers" who contribute disproportionately to revenue, enabling targeted retention strategies.

### 3. Sales Forecasting (Machine Learning)
Built a predictive model to forecast future daily sales.
* **Baseline Model:** Linear Regression (Captures general trend).
* **Advanced Model:** Random Forest Regressor (Captures non-linear seasonality).
* **Feature Engineering:** Improved model accuracy by adding **Lag Features** (Sales-1, Sales-7) and **Rolling Averages**, effectively giving the model "memory" of recent performance.

 **Result:** The Random Forest model significantly outperformed the Linear Regression baseline, reducing prediction error by adapting to weekly fluctuations.
