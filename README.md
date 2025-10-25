# FUTURE_ML_01 - AI-Powered Sales Forecasting Dashboard
Repository for Task 1 of Machine Learning Internship – Exploratory Data Analysis, Model Building, and Evaluation.

## 📌 About the Task
This project is part of my **Future Interns Machine Learning Internship** (Task 1).
In this project, I built a predictive analytics dashboard to help retail businesses forecast future sales. Using historical transaction data, I applied a machine learning model to predict upcoming trends and presented the insights in an interactive Power BI dashboard.

## 🎯 Objectives
- Clean and structure historical retail sales data.
- Engineer features such as monthly sales and seasonal patterns.
- Train a **time series forecasting model** using **Facebook Prophet**.
- Build a Power BI dashboard for visualization.
- Provide clear **business insights** from the results.

---

## 🛠️ Tools & Technologies
```
- **Python** (Pandas, Prophet, Matplotlib, Scikit-learn, NumPy)
- **Power BI Desktop**
- **Superstore Sales Dataset**
- **GitHub** for code hosting
- **Prophet**
```
---

### ✅ Project Workflow

1.  **Data Cleaning & Preprocessing:** Loaded the dataset and handled missing values, corrected data types, and structured the data for time series analysis.
2.  **Feature Engineering:** Engineered features like monthly averages, holiday indicators, and seasonal trends to improve model accuracy.
3.  **Model Training:** Trained a time series forecasting model using Facebook Prophet to predict future sales for the next 12 months.
4.  **Dashboard Development:** Designed and built an interactive dashboard in Power BI, connecting the historical data and the forecasted data.
5.  **Data Visualization:** Created visuals to display past trends vs. future forecasts, monthly/yearly comparisons, and sales by category/region.

---


## 📊 Key Features in Dashboard
* ✔️ Sales trend line with actual vs. forecasted data
* ✔️ Monthly & yearly comparisons
* ✔️ Interactive filters by category, region, and date
* ✔️ KPI cards for quick insights (e.g., YoY Growth, Total Sales)
* ✔️ Insights and actionable business recommendations

---

## 📂 Project Structure
```text
│── data/                 # Raw and processed datasets
│   ├── dataset.csv
│
│── notebooks/            # Jupyter notebooks
│   ├── Task1_EDA.ipynb
│   ├── Task1_Model.ipynb
│
│── scripts/              # Python scripts
│   ├── preprocess.py
│   ├── train_model.py
│
│── results/              # Outputs like plots, reports
│   ├── accuracy_report.txt
│   ├── confusion_matrix.png
│
│── README.md             # Project overview
│── requirements.txt      # Dependencies (numpy, pandas, scikit-learn, matplotlib, etc.)
```

---

## 📷 Dashboard Preview
* <img width="1433" height="806" alt="Screenshot 2025-09-26 133701" src="https://github.com/user-attachments/assets/ece47722-419e-4653-8cff-5d5a8574ac1d" />
* <img width="929" height="288" alt="Screenshot 2025-09-26 133617" src="https://github.com/user-attachments/assets/3143edbc-6cb3-4791-8eed-48442c86342f" />

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/SheldonDsouzaML/FUTURE_ML_01.git
2. Navigate into the project folder:
   cd FUTURE_ML_01/code

3. Install dependencies:
   pip install -r requirements.txt

4. Run the Prophet forecasting script:
   python AI-Powered Sales Forecasting Dashboard.ipynb


5. The forecast results will be exported as forecast_results.csv.
   Open the Power BI file (AI-Powered Sales Forecasting Dashboard.pbix) to explore the dashboard.

📌 Internship Details

- **Internship Program** : Future Interns – Machine Learning Internship

- **Candidate ID (CIN)** : FIT/SEP25/ML2769


- **Task** : AI-Powered Sales Forecasting Dashboard (Task 1)
