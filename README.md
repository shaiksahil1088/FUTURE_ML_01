
# 🧠 AI-Powered Sales Forecasting Dashboard  
**Track Code:** ML | **Task 1 – Machine Learning**

## 📌 Objective
Build a dashboard that predicts **future sales trends** using **historical retail data**.

---

## 🚀 Task Description
🔹 **Task:** Develop a time series forecasting model and dashboard to predict upcoming sales.  
🔹 **Skills Gained:** Time series forecasting, regression, and trend analysis.  
🔹 **Tools Used:** Python (Prophet, Scikit-learn, Pandas), Matplotlib, Power BI.  
🔹 **Dataset:** Retail sales data (daily, weekly, or monthly).  
🔹 **Deliverable:** A forecasting model with visualizations showing **predicted trends**, **seasonality**, and **forecast** insights.

---

## 🧩 Steps Performed
1. **Data Preparation:** Loaded and cleaned historical retail sales data.  
2. **Exploratory Analysis:** Visualized trends and seasonality patterns.  
3. **Modeling:**  
   - Prophet model for time-series forecasting (with fallback to SARIMAX).  
   - Linear Regression baseline using Scikit-learn.  
4. **Forecast Generation:** Predicted next 12 months of sales with confidence intervals.  
5. **Visualization:**  
   - Line plots (historical + forecast) using Matplotlib.  
   - Optional Power BI dashboard for interactive insights.  

---

## 📊 Power BI Integration
You can import the CSV outputs (`forecast.csv`, `sample_retail_sales.csv`) into Power BI:  
1. **Get Data → CSV → Load Files**  
2. Ensure `ds` is a Date column.  
3. Plot actual vs forecast lines, and shade confidence bands.  
4. Add slicers for Year / Month.

---

## 🧠 Future Enhancements
- Add regressors like promotions, holidays, and regional factors.  
- Optimize hyperparameters (Prophet changepoints / SARIMAX orders).  
- Automate dashboard refresh with updated data.

---

## 📁 Files Included
| File | Description |
|------|--------------|
| `forecast_dashboard.ipynb` | Complete Jupyter notebook pipeline |
| `sample_retail_sales.csv` | Example dataset |
| `forecast.csv` | Prophet/SARIMAX forecast output |
| `sk_baseline_forecast.csv` | Linear regression baseline |
| `README.md` | Project documentation |

---

## 🏆 Outcome
A complete **AI-powered forecasting dashboard** demonstrating predictive analytics, time-series modeling, and visualization integration with Power BI.
