
# 📊 Sales Forecasting with Machine Learning  

## 📚 Overview
This project predicts future sales for various product families across stores in Ecuador using different machine learning models. It evaluates models such as ARIMA, Random Forest, XGBoost, and LSTM, and provides insights into how external factors impact sales.  

##📊 Dataset Files

train.csv - Historical sales data

test.csv - Test set for predictions

stores.csv - Store metadata

oil.csv - Daily oil prices

holidays_events.csv - Holiday and event details

transactions.csv - Store transaction data

##⚙️ Requirements
Python 3.9+

Jupyter Notebook

Required Libraries:

pandas

numpy

matplotlib

seaborn

scikit-learn

statsmodels

xgboost

keras

tensorflow
# 📈 Model Comparison Summary: Sales Forecasting  

## 🎯 Objective
To develop an accurate sales forecasting model using multiple algorithms and compare their performance.  

---

## 🔥 **Model Evaluation Metrics**
| **Model**        | **R² Score** |
|------------------|--------------|
| ARIMA            |  -0.08       |
| Random Forest    |   0.96       |
| XGBoost          |   0.90       |
| LSTM             |   0.03       |

---

## 📊 **Best Model Performance**
- **Best Performing Model:** Random Forest 
- **Reason:**  
   - Achieved the lowest RMSE and MAPE with the highest R² score.
   - Effectively captured non-linear relationships and seasonal trends.

---

## 📈 **Key Insights**
1. **Impact of Holidays & Promotions:**  
   - Holidays and promotions significantly boost sales.  
   - Including these features improved model performance.  

2. **Correlation with Oil Prices:**  
   - Fluctuating oil prices impacted purchasing power and influenced sales.  
   - Incorporating `dcoilwtico` as a feature enhanced accuracy.  

3. **Government Paydays:**  
   - Increased demand observed around 15th and month-end periods.  
   - Adding a binary payday flag improved model predictions.

---

## 📢 **Business Recommendations**
✅ **1. Inventory Planning:** Optimize stock levels before holidays and promotional periods.  
✅ **2. Targeted Promotions:** Launch offers around paydays and low-demand periods.  
✅ **3. Dynamic Pricing:** Adjust pricing based on oil price trends to maximize sales.  

---

## 📊 **Final Recommendation**
To maintain accurate forecasting, it is advised to periodically retrain models with updated data and fine-tune hyperparameters.
