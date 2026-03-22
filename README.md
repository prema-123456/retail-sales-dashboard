# 📊 Retail Sales Dashboard & Analytics Pipeline

## Overview
This project demonstrates an **end-to-end retail sales analytics pipeline**.  
It includes:

1. **PySpark-based data pipeline** for local analysis:
   - Data cleaning
   - Feature engineering
   - Key KPIs & business insights
2. **Streamlit dashboard** (Pandas-based) for deployment:
   - Interactive web dashboard
   - Total revenue, category-wise, city-wise sales
   - Ready to share with recruiters or business stakeholders

> Note: PySpark is used for local processing; the dashboard uses Pandas for deployment due to environment limitations.

---

## 🔹 Features

- **Total Revenue Calculation**  
- **Category-wise Sales Analysis**  
- **City-wise Sales Analysis**  
- **Top Products by Quantity Sold**  
- **Interactive Dashboard with Streamlit**  
- **Clean & Recruiter-friendly Code Structure**

---

## 🗂 Project Structure
retail-sales-dashboard/
│── data/
│ └── sales.csv # Sample dataset
│── main.py # PySpark local pipeline
│── app.py # Streamlit dashboard (Pandas version)
│── requirements.txt # Required Python packages
│── README.md # Project documentation


---

## 📊 Local PySpark Analysis (`main.py`)

- **Run Locally**:

```bash
# Install PySpark
pip install pyspark

# Run PySpark pipeline
python main.py
