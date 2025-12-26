# 📊 Sales Analyzer using NumPy, Pandas & Matplotlib

🚀 **Sales Analyzer** is a beginner-friendly data analysis project created using **Python**, **NumPy**, **Pandas**, and **Matplotlib**.  
It demonstrates how to generate, analyze, visualize, and forecast sales data effectively.

👨‍💻 **Created by:** *Kundan Kumar Singh*

---

## 🔥 Project Features

✔ Generate synthetic sales data  
✔ Perform sales & profit calculations  
✔ Analyze top-selling products  
✔ Monthly sales trend visualization  
✔ Profit comparison by product  
✔ Simple sales forecasting using rolling average  
✔ Export data to CSV files  
✔ Practice Pandas operations (DataFrame, loc, iloc, groupby, fillna)  
✔ Includes basic Python programs (Prime number, Table generator)

---

## 🛠️ Technologies Used

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**

---

## 📂 Project Structure:

📁 Sales-Analyzer
│── sales_analyzer.py
│── sales_data.csv
│── detail_not.csv
│── python.csv
│── aman.csv
│── README.md


---

## 📈 Sales Analysis Overview

### 🔹 Dataset Columns
- `Date`
- `Product`
- `Units_Sold`
- `Price`
- `Cost`
- `Sales`
- `Profit`
- `Sales_Forecast`

---

## 📊 Visualizations Included

- 📉 **Monthly Sales Trend**
- 📊 **Profit by Product (Bar Chart)**
- 📈 **Sales Forecast using Rolling Mean**

---

## 🧮 Key Calculations

- **Total Sales**
- **Total Profit**
- **Top-Selling Products**
- **Product-wise Profit Analysis**

---

## 📌 Example Code Snippet

```python
df["Sales"] = df["Units_Sold"] * df["Price"]
df["Profit"] = df["Units_Sold"] * (df["Price"] - df["Cost"])
