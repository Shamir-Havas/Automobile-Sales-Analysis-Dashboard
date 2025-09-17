# 🚗 Automobile Sales Analysis Dashboard

![Dashboard Preview](https://github.com/Shamir-Havas/Automobile-Sales-Analysis-Dashboard/blob/main/dash1.png)  
*A snapshot of the interactive dashboard.*

---

## 📌 Project Overview
This project analyzes **automobile sales trends** using both static visualizations and an **interactive dashboard**.  
The goal is to highlight how **recessions, unemployment, GDP, and advertising** influence automobile sales across different vehicle types.

This project demonstrates:
- **Data Wrangling & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Visualization (Matplotlib, Seaborn, Plotly)**
- **Dashboard Development (Dash, ipywidgets)**
- **Business Insights & Storytelling**

---

## 📊 Dataset
Since no public dataset was provided, a **synthetic dataset** was generated with realistic automotive sales and economic indicators.

**Key Features:**
- `Date`, `Year`, `Month` → Time period of sales  
- `Automobile_Sales` → Sales volume  
- `Vehicle_Type` → Vehicle categories (Sports, Executive, etc.)  
- `Recession` → Whether the year was in recession  
- `GDP`, `Unemployment_Rate`, `Consumer_Confidence` → Economic indicators  
- `Price`, `Advertising_Expenditure`, `Competition` → Market/business factors  
- `Seasonality_Weight` → Seasonal effects  

---

## 🔎 Exploratory Data Analysis (EDA)

### 1. Automobile Sales Over Years  
Shows long-term trend in automobile sales.  
![Sales Over Years](https://github.com/Shamir-Havas/Automobile-Sales-Analysis-Dashboard/blob/main/Sales%20over%20years.png)

### 2. Recession vs Non-Recession Sales  
Highlights how recessions affect total sales.  
![Recession vs Non-Recession](https://github.com/Shamir-Havas/Automobile-Sales-Analysis-Dashboard/blob/main/recession%20vs%20non%20recession.png)

### 3. Effect of Unemployment on Sales  
Unemployment rate strongly influences sales in recession periods.  
![Unemployment Effect](https://github.com/Shamir-Havas/Automobile-Sales-Analysis-Dashboard/blob/main/unemplyment%20effect.png)

### 4. Advertising Expenditure Distribution  
Comparison of ad spending between recession and non-recession years.  
![recession year](https://github.com/Shamir-Havas/Automobile-Sales-Analysis-Dashboard/blob/main/pie2.png)
![non-recession year](https://github.com/Shamir-Havas/Automobile-Sales-Analysis-Dashboard/blob/main/pie1.png)

---

## 📈 Interactive Dashboard
An interactive dashboard was built using **Dash + Plotly + ipywidgets**.

- **Recession Report:**  
  - Line chart: Sales per vehicle type  
  - Bar chart: Sales by vehicle type  
  - Scatter: Unemployment vs Sales  
  - Pie: Sales distribution  

- **Yearly Report:**  
  - Line chart: Total sales trend  
  - Bar chart: Vehicle sales in selected year  
  - Scatter: Price vs Sales  
  - Pie: Sales distribution  

📌 **Dashboard Preview:**  
![Dashboard Screenshot](screenshots/dashboard.png)

---

## 💡 Key Insights & Business Value
- Sales show **clear declines during recessions**.  
- **SUVs and sports cars** show unique patterns compared to smaller cars.  
- **Unemployment rates** strongly correlate with automobile sales in downturns.  
- Advertising expenditure shifts noticeably **between recession vs non-recession years**.  

These insights can support **business strategy, marketing optimization, and product planning**.

---

## ⚙️ How to Run

### Prerequisites
Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn plotly dash ipywidgets

Run Notebook
Open the Jupyter notebook:


jupyter notebook automobile_sales_cleaned.ipynb
Run Dashboard
To launch the dashboard locally:

bash
Copy code
python app.py
(If dashboard code is inside notebook, run the relevant cell.)

🛠️ Tech Stack
Python (Pandas, NumPy) – data wrangling & preprocessing

Matplotlib & Seaborn – static visualizations

Plotly Express & Dash – interactive dashboard

ipywidgets – dropdown filters and interactivity

✅ Skills Demonstrated
Data Wrangling & Feature Engineering

Exploratory Data Analysis (EDA)

Data Visualization (static + interactive)

Dashboard Development

Business Analytics & Storytelling

📂 Repository Structure

Automobile-Sales-Analysis-Dashboard/
│── automobile_sales_cleaned.ipynb   # Cleaned notebook with markups
│── README.md                        # Project documentation

