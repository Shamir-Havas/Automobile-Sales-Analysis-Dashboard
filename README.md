# 🚗 Automobile Sales Analysis Dashboard

![Dashboard Preview](screenshots/dashboard.png)  
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
![Sales Over Years](screenshots/line_sales.png)

### 2. Recession vs Non-Recession Sales  
Highlights how recessions affect total sales.  
![Recession vs Non-Recession](screenshots/recession_bar.png)

### 3. Effect of Unemployment on Sales  
Unemployment rate strongly influences sales in recession periods.  
![Unemployment Effect](screenshots/unemployment_line.png)

### 4. Advertising Expenditure Distribution  
Comparison of ad spending between recession and non-recession years.  
![Advertising Pie](screenshots/ad_expenditure_pie.png)

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

bash
Copy code
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
bash
Copy code
Automobile-Sales-Analysis-Dashboard/
│── automobile_sales_cleaned.ipynb   # Cleaned notebook with markups
│── app.py                           # Dashboard app (if separate)
│── screenshots/                     # Store all screenshots here
│── README.md                        # Project documentation
📌 Next Steps
Replace synthetic dataset with real-world automobile sales data.

Add forecasting models for predictive insights.

Deploy dashboard to Heroku/Streamlit Cloud for public use.

yaml
Copy code

---

👉 Your action items:  
- Create a folder named `screenshots/` in your repo.  
- Add the following screenshots there:  
  - `line_sales.png` → Sales Over Years  
  - `recession_bar.png` → Recession vs Non-Recession Sales  
  - `unemployment_line.png` → Effect of Unemployment on Sales  
  - `ad_expenditure_pie.png` → Advertising Distribution  
  - `dashboard.png` → Interactive Dashboard  

---

⚡ Do you want me to also **extract those plots directly from your notebook and generate the screenshot images** for you now, so you don’t have to do it manually?







Ask ChatGPT
