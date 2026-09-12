# 🚗 Automobile Sales Analysis & Interactive Dashboard

An end-to-end **Data Science and Business Analytics project** focused on analyzing automobile sales trends, recession impacts, advertising expenditure, vehicle-type performance, pricing, seasonality, and unemployment.

The project combines **Python-based exploratory data analysis (EDA)** with an **interactive Plotly Dash dashboard** to transform automobile sales data into business-oriented insights.

---

## 📌 Project Overview

The automobile industry is strongly influenced by economic conditions, consumer behavior, pricing, advertising, and seasonality.

This project analyzes automobile sales data from **2000 to 2019** to understand:

- How automobile sales change over time
- How recessions affect automobile sales
- Which vehicle categories perform best
- How advertising expenditure changes during economic downturns
- The relationship between automobile prices and sales
- Seasonal patterns in automobile sales
- The relationship between unemployment and automobile sales

An interactive **Dash dashboard** was also developed to allow users to explore the analysis through different reports and years.

---

## 🎯 Business Objectives

The main objectives of this project are to:

1. Analyze long-term automobile sales trends.
2. Compare automobile sales during recession and non-recession periods.
3. Identify vehicle types with stronger and weaker sales performance.
4. Examine advertising expenditure across vehicle categories.
5. Investigate seasonal patterns in automobile sales.
6. Explore the relationship between automobile prices and sales.
7. Examine the relationship between unemployment rates and automobile sales.
8. Build an interactive dashboard for business-oriented analysis.

---

# 📊 Dataset

The dataset used in this project is generated programmatically using **NumPy and Pandas** with a fixed random seed for reproducibility.

### Dataset characteristics

- **Time period:** 2000–2019
- **Observations:** 1,200
- **Features:** 9
- **Vehicle types:** 5

### Vehicle categories

- Superminicar
- Smallfamilycar
- Mediumfamilycar
- Executivecar
- Sports

### Features

| Feature | Description |
|---|---|
| `Year` | Year of observation |
| `Month` | Month of observation |
| `Vehicle_Type` | Automobile category |
| `Automobile_Sales` | Automobile sales |
| `Advertising_Expenditure` | Advertising expenditure |
| `GDP` | Gross Domestic Product |
| `Unemployment_Rate` | Unemployment rate |
| `Recession` | Indicates whether the observation belongs to a recession period |
| `Average_Price` | Average automobile price |

The recession years represented in the analysis are:

**2001, 2008, 2009, 2012, and 2015**

---

# 🔎 Exploratory Data Analysis

## 1. Automobile Sales Over Time

The analysis examines automobile sales across the full observation period to identify overall trends, fluctuations, and changes in demand.

The time-series analysis provides a high-level view of how sales evolve across different economic periods.

![Automobile Sales Over Years](images/sales_over_years.png)

---

## 2. Recession vs Non-Recession Sales

One of the main objectives of the project is to understand how economic downturns influence automobile sales.

The analysis compares average annual sales during recession and non-recession periods.

### Key finding

- **Average annual sales during recession:** 20,591.6
- **Average annual sales during non-recession:** 25,167.5

This represents approximately an **18.2% lower average annual sales level during recession periods**.

This demonstrates the potential impact of adverse economic conditions on automobile demand.

![Recession vs Non-Recession](images/recession_vs_non_recession.png)

> Note: The analysis is observational and does not establish a causal relationship between recession conditions and sales.

---

## 3. Sales Performance by Vehicle Type

The project analyzes sales performance across different automobile categories to identify which vehicle segments contribute most to overall sales.

During recession periods, the cumulative sales by vehicle type were:

| Vehicle Type | Recession Sales |
|---|---:|
| Mediumfamilycar | 27,588 |
| Smallfamilycar | 27,234 |
| Superminicar | 22,756 |
| Executivecar | 15,125 |
| Sports | 10,255 |

### Business interpretation

The results show that **Mediumfamilycar** and **Smallfamilycar** represent the strongest-performing vehicle categories during recession periods, while **Sports** vehicles have substantially lower sales.

This can help businesses understand how different vehicle segments behave under challenging economic conditions.

---

## 4. Seasonality Analysis

Automobile sales can vary depending on the month of the year.

The analysis investigates monthly sales patterns and identifies seasonal changes in automobile demand.

The generated dataset incorporates seasonal effects, allowing the project to explore how sales vary throughout the year.

![Seasonality Analysis](images/seasonality_analysis.png)

---

## 5. Advertising Expenditure

Advertising expenditure is analyzed alongside automobile sales to understand how marketing investment changes across different periods.

The analysis also compares advertising expenditure across vehicle types.

![Advertising Expenditure](images/advertising_expenditure.png)

---

## 6. Advertising Expenditure by Vehicle Type

The dashboard and EDA examine advertising expenditure across automobile categories.

This provides a business-oriented view of how marketing resources are distributed among different vehicle segments.

![Advertising by Vehicle Type](images/advertising_by_vehicle_type.png)

---

## 7. Unemployment Rate and Automobile Sales

The project also explores the relationship between unemployment and automobile sales.

The objective is to determine whether changes in unemployment coincide with changes in automobile demand.

![Unemployment vs Automobile Sales](images/unemployment_vs_sales.png)

> The relationship should be interpreted as exploratory rather than causal.

---

# 📈 Interactive Dashboard

A major component of this project is an interactive dashboard built using:

- **Plotly**
- **Dash**
- **Dash HTML components**
- **Dash Core Components**

The dashboard is titled:

> **Automobile Sales Statistics Dashboard**

Users can interact with the dashboard using report and year selections.

![Dashboard](images/dashboard_1.png)

---

# 📊 Dashboard Reports

## Recession Report

The Recession Report provides a focused analysis of automobile sales during recession periods.

It includes visualizations for:

- Yearly automobile sales during recession periods
- Automobile sales by vehicle type
- Advertising expenditure by vehicle type
- Automobile price and sales analysis

This allows users to examine how automobile businesses perform during economically challenging periods.

![Recession Dashboard](images/dashboard_2.png)

---

## Yearly Sales Statistics Report

The Yearly Sales Statistics report allows users to examine automobile sales for selected years.

The report includes:

- Monthly automobile sales by vehicle type
- Sales distribution by vehicle type
- Advertising expenditure by vehicle type
- Price and sales analysis

The interactive interface makes it easier to compare different years and vehicle categories.

---

# 🧠 Key Business Insights

Based on the analysis, several important observations emerge:

### 1. Automobile sales decline during recession periods

Average annual automobile sales were lower during recession periods compared with non-recession periods.

The difference was approximately **18.2%** based on the generated dataset.

### 2. Vehicle categories behave differently

Medium-family and small-family vehicles demonstrate stronger sales performance during recession periods than executive and sports vehicles.

### 3. Economic conditions matter

Variables such as GDP and unemployment are included to explore how broader economic conditions relate to automobile sales.

### 4. Seasonality influences sales

The analysis incorporates monthly patterns and investigates how automobile demand changes throughout the year.

### 5. Marketing expenditure can be analyzed alongside sales

Advertising expenditure is evaluated across periods and vehicle categories, providing a business perspective on marketing activity.

---

# 🛠️ Technical Approach

The project follows a typical data analytics workflow:

```text
Data Generation
       ↓
Data Preparation
       ↓
Exploratory Data Analysis
       ↓
Statistical Analysis
       ↓
Data Visualization
       ↓
Business Insights
       ↓
Interactive Dashboard
