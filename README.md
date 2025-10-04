# 🧠 Customer Churn Analysis & Prediction

## 📋 Overview  
This project analyzes and predicts **customer churn** using data from Kaggle.  
It demonstrates an **end-to-end data analytics pipeline** — from SQL-based cleaning and EDA to machine learning in Python, and finally, interactive visualization in Power BI.

---

## 🏗️ Project Workflow  

### 🔹 1. Data Loading & Cleaning (SQL)
- Imported the Kaggle churn dataset into **SQL Server / MySQL**.  
- Performed **Exploratory Data Analysis (EDA)** to understand patterns and data quality.  
- Handled **missing values**, removed duplicates, and standardized categorical fields.

### 🔹 2. Visualization (Power BI - Summary Page)
- Created a **Summary Dashboard** to display customer distribution, churn rate, and service insights.  
- Added **filters, slicers, and KPIs** for interactive exploration and decision support.  

### 🔹 3. Model Development (Python)
- Trained a **Random Forest Classifier** using libraries like:
  - `pandas` for data handling  
  - `scikit-learn` for modeling  
  - `matplotlib` for visualization  
- Predicted churn probability and exported results as `Predictions.csv`.  

### 🔹 4. Prediction Integration (Power BI - Prediction Page)
- Imported the Python model output (`Predictions.csv`) into Power BI.  
- Designed a **Prediction Page** showing high-risk customers and churn probabilities.  
- Added navigation between **Summary** and **Prediction** pages for seamless interaction.

---

## 🛠️ Tech Stack  

| Layer | Tools / Technologies |
|--------|-----------------------|
| **Database & EDA** | SQL Server / MySQL |
| **Data Analysis & ML** | Python, pandas, scikit-learn, matplotlib |
| **Visualization** | Power BI |

---

## 📊 Output Dashboards  

### 🔸 Summary Page
- KPIs: Total Customers, Churn Rate, Average Monthly Charge  
- Visuals: Churn by State, Contract Type, and Tenure  

### 🔸 Prediction Page
- Churn probability distribution  
- Top high-risk customers table  
- Navigation buttons between pages  

---

## 🚀 Key Features  
✅ End-to-end pipeline: **SQL → Python → Power BI**  
✅ Fully interactive dashboards with navigation  
✅ Predictive insights using **Random Forest**  
✅ Clean, refreshable, and Power BI–ready CSV outputs  

---

## 🧩 Folder Structure  
Customer_Churn_Analysis/
│
├── data/
│ └── churn_data.csv
│
├── notebooks/
│ └── churn_model_random_forest.ipynb
│
├── outputs/
│ └── Predictions.csv
│
├── powerbi/
│ └── Churn_Analysis_Dashboard.pbix
│
└── README.md

---

## 🧠 Future Improvements  
- Add live database connection for real-time refresh  
- Try advanced models (XGBoost, CatBoost)  
- Integrate Power BI Service for automatic data refresh  

---

## ✨ Author  
**Your Name**  
📧 *youremail@example.com*  
💼 [LinkedIn Profile](https://www.linkedin.com/) | [GitHub Repository](https://github.com/)
