# 🛒Retail-Sales-Forcasting---Inventory-Optimization
From data preprocessing → feature engineering → model building (Linear Regression, Random Forest, XGBoost) → evaluation, this project gave me hands-on exposure to solving real-world business challenges with analytics.

## 📌 Project Overview 
This project focuses on forecasting retail store sales using historical data. Accurate sales forecasting helps retailers optimize inventory management, staffing, and promotional strategies.

## 🎯 Objectives
- Understand and clean the dataset
- Perform exploratory data analysis (EDA)
- Engineer relevant features
- Apply and compare multiple forecasting models
- Evaluate models using RMSE & MAE
- Select the best-performing model for predictions

## 🗂 Dataset
Source: retail_store.csv
Contains daily sales data of multiple stores

Key columns:
Date → Transaction date
StoreID → Store identifier
Sales → Target variable (daily sales)

## ⚙️ Tech Stack
- Language: Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
- Modeling: Linear Regression, Random Forest, XGBoost

## 🔑 Steps Followed
- Data Cleaning → Handled missing values, formatted dates, removed duplicates
- EDA → Trend analysis, seasonality check, correlation plots
- Feature Engineering → Extracted time features (month, day, week), encoded store IDs
- Modeling → Built ML models for regression forecasting
- Evaluation → Compared models using RMSE & MAE
- Result → Best model: Linear Regression (lowest RMSE)

## 📸 Sample Outputs
### Overall Sales Trend
<img width="1341" height="717" alt="Total Sales" src="https://github.com/user-attachments/assets/e3aca10d-df02-4b0c-b695-5de56ec19e5a" />

## 📊 Results & Insights
- XG Boost outperformed other models in forecasting accuracy
- Strong seasonal patterns were observed in sales
- Model can assist in inventory optimization and demand planning

### Linear Regression Model
<img width="1128" height="687" alt="Linear Regression" src="https://github.com/user-attachments/assets/48d950a3-3bcb-40bf-ba2b-1b1dcf16acb5" />

### XG Boost Model
<img width="1155" height="610" alt="XG Boost " src="https://github.com/user-attachments/assets/366cf690-d04e-4453-80a9-88776642bb23" />

## 🚀 Future Enhancements
- Implement LSTM / ARIMA for time-series forecasting
- Add external factors (holidays, promotions, weather)
- Deploy model with Streamlit / Flask for real-time predictions

## 📬 Contact
#### Linkdin Profile
(www.linkedin.com/in/ankita-ahirrao7)

#### Email
(ankitaahirrao6@gmail.com)




