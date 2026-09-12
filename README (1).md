\# 🚗 Automobile Sales Analysis \& Interactive Dashboard



> An end-to-end Python analytics project exploring automobile sales patterns across economic conditions, vehicle segments, pricing, advertising expenditure, unemployment, and seasonality — presented through analytical visualizations and an interactive Dash dashboard.



\---



\## 📌 Project Overview



Understanding how economic conditions affect automobile demand can help automotive businesses make better decisions around pricing, marketing, inventory, and product strategy.



This project analyzes automobile sales across different vehicle types and explores how sales vary with:



\- Economic conditions and recession periods

\- Unemployment rates

\- GDP

\- Average vehicle price

\- Advertising expenditure

\- Seasonal patterns

\- Vehicle type



The project combines \*\*data generation, exploratory data analysis, statistical aggregation, visualization, and interactive dashboard development\*\* into a single analytical workflow.



> \*\*Note:\*\* This project uses a synthetically generated dataset. The findings are therefore intended to demonstrate analytical methodology rather than represent real-world automotive market estimates.



\---



\## 🎯 Business Objectives



The analysis was designed to answer the following business questions:



1\. How do automobile sales change over time?

2\. How do sales differ between recession and non-recession periods?

3\. Which vehicle types generate the highest sales?

4\. How does vehicle price relate to sales during recession periods?

5\. How is advertising expenditure distributed across vehicle segments?

6\. Are there visible seasonal patterns in automobile demand?

7\. How do unemployment levels vary with vehicle sales during recession periods?



\---



\# 📊 Dataset



The project uses a \*\*synthetically generated automobile sales dataset\*\*.



The notebook generates monthly observations covering \*\*2000–2019\*\* across five vehicle categories. A fixed random seed is used to support reproducibility.



\### Dataset Characteristics



\- \*\*20 years\*\*

\- \*\*12 months per year\*\*

\- \*\*5 vehicle types\*\*

\- \*\*1,200 observations\*\*

\- \*\*9 analytical variables\*\*



\### Features



| Feature | Description |

|---|---|

| `Year` | Calendar year |

| `Month` | Month of observation |

| `Vehicle\_Type` | Automobile segment |

| `Automobile\_Sales` | Number of automobiles sold |

| `Advertising\_Expenditure` | Advertising expenditure |

| `GDP` | GDP indicator |

| `Unemployment\_Rate` | Unemployment rate |

| `Recession` | Recession indicator |

| `Average\_Price` | Average vehicle price |



\### Vehicle Segments



\- Smallfamilycar

\- Executivecar

\- Superminicar

\- Sports

\- Mediumfamilycar



The data-generation process incorporates vehicle-specific demand, seasonal effects, advertising expenditure, pricing, recession effects, GDP variation, and unemployment variation.



\---



\# 🔎 Exploratory Data Analysis



\## 1. Automobile Sales Over Time



Yearly automobile sales are aggregated and visualized to identify long-term demand patterns.



!\[Automobile Sales Over Years](Sales%20over%20years.png)



\### Key Observation



Sales fluctuate substantially over the observation period, with visible peaks and downturns rather than a simple linear growth pattern.



\---



\## 2. Recession vs Non-Recession Sales



Automobile sales are aggregated by recession status and vehicle type to compare demand under different economic conditions.



!\[Recession vs Non-Recession Sales](recession%20vs%20non%20recession.png)



\### Key Finding



Within the generated dataset, average annual automobile sales are lower during recession periods than during non-recession periods.



| Period | Average Annual Sales |

|---|---:|

| Non-Recession | 25,167.5 |

| Recession | 20,591.6 |



This represents an approximately \*\*18.2% lower average annual sales level during recession periods\*\* in the synthetic dataset.



\---



\## 3. Sales by Vehicle Type



Vehicle-level aggregation is used to identify differences in demand across automobile segments.



\### Recession-Period Sales



| Rank | Vehicle Type | Sales |

|---:|---|---:|

| 1 | Mediumfamilycar | 27,588 |

| 2 | Smallfamilycar | 27,234 |

| 3 | Superminicar | 22,756 |

| 4 | Executivecar | 15,125 |

| 5 | Sports | 10,255 |



The results show stronger sales volumes for the family-oriented vehicle categories within the recession sample.



\---



\## 4. Price vs Sales During Recession



The project examines the relationship between average vehicle price and automobile sales during recession periods.



!\[Price vs Sales](Scatter.png)



\### Analytical Observation



Higher-priced vehicle categories generally show lower sales volumes in the recession sample.



Because vehicle price is also associated with vehicle segment, this relationship should be interpreted as \*\*descriptive rather than causal\*\*.



\---



\## 5. Seasonality Analysis



Monthly automobile sales are aggregated across years to identify recurring seasonal patterns.



!\[Seasonality Analysis](Bubble.png)



The synthetic data incorporates seasonal demand variation, with higher sales multipliers during June–August and moderately higher values during November–December.



This demonstrates how seasonality can be incorporated into automobile demand analysis and visualized for business decision-making.



\---



\## 6. Advertising Expenditure



Advertising expenditure is analyzed across economic conditions and vehicle types.



\### Advertising Expenditure: Recession vs Non-Recession



!\[Advertising Expenditure](Pie\_1.png)



\### Advertising Expenditure by Vehicle Type During Recession



!\[Advertising by Vehicle Type](Pie\_2.png)



The analysis demonstrates how marketing expenditure can be compared across vehicle segments and economic conditions.



\---



\## 7. Unemployment vs Automobile Sales



The project examines unemployment rates against automobile sales during recession periods.



!\[Unemployment vs Automobile Sales](unemplyment%20effect.png)



\### Analytical Observation



The visualization is used to explore the relationship between unemployment and vehicle sales during recession periods.



It should not be interpreted as evidence that unemployment directly causes changes in automobile sales.



\---



\# 📈 Interactive Dashboard



The project includes an interactive dashboard developed using \*\*Dash and Plotly\*\*.



The dashboard provides two analytical report types:



\### 🔴 Recession Report



The recession view displays:



\- Sales trend across recession years

\- Sales by vehicle type

\- Advertising expenditure by vehicle type

\- Price vs sales



\### 🔵 Yearly Sales Report



The yearly view allows the user to select a year and dynamically displays:



\- Monthly sales by vehicle type

\- Sales by vehicle type

\- Advertising expenditure by vehicle type

\- Price vs sales



The dashboard uses \*\*Dash callbacks\*\* to control the year selector and dynamically update visualizations based on the selected report type.



!\[Automobile Sales Dashboard](dash1.png)



!\[Automobile Sales Dashboard](dash2.png)



\---



\# 🛠️ Technical Approach



\## 1. Synthetic Data Generation



The dataset is generated programmatically using \*\*NumPy and Pandas\*\*.



The generation process incorporates:



\- Vehicle-specific baseline demand

\- Seasonal multipliers

\- Advertising expenditure

\- Vehicle pricing

\- Recession effects

\- GDP variation

\- Unemployment variation



A fixed random seed is used to support reproducibility.



\---



\## 2. Data Aggregation



Pandas `groupby()` operations are used to transform the raw observations into analytical datasets for:



\- Yearly sales

\- Monthly sales

\- Vehicle-level sales

\- Recession vs non-recession comparisons

\- Advertising expenditure

\- Economic indicators



\---



\## 3. Exploratory Data Analysis



The analysis focuses on:



\- Sales trends

\- Vehicle-segment differences

\- Economic-period differences

\- Seasonal patterns

\- Price-sales relationships

\- Advertising allocation

\- Unemployment and sales relationships



\---



\## 4. Data Visualization



\### Static Visualization



\- Matplotlib

\- Seaborn



\### Interactive Visualization



\- Plotly Express

\- Dash



The project uses:



\- Line charts

\- Bar charts

\- Scatter plots

\- Bubble charts

\- Pie charts



to communicate analytical findings.



\---



\# 💡 Key Business Insights



The analysis of the generated dataset demonstrates several business-relevant patterns.



\### 1. Automobile demand varies with economic conditions



Average annual sales are lower during recession periods than during non-recession periods in the synthetic dataset.



\### 2. Vehicle segments have different demand levels



Family-oriented vehicle categories show stronger sales volumes than premium and sports-oriented categories in the recession sample.



\### 3. Price can be useful for segment-level analysis



Higher-priced vehicle categories tend to have lower sales volumes during recession periods.



\### 4. Marketing expenditure differs across segments



Advertising expenditure is distributed across vehicle categories, providing a basis for evaluating marketing allocation.



\### 5. Seasonality affects demand patterns



The generated dataset contains recurring monthly patterns that demonstrate how seasonality can be incorporated into automobile sales analysis.



\---



\# 🎯 Skills Demonstrated



\## Data Analytics



\- Data generation

\- Data wrangling

\- Data aggregation

\- Group-by analysis

\- Descriptive analysis

\- Exploratory Data Analysis



\## Data Visualization



\- Matplotlib

\- Seaborn

\- Plotly Express

\- Time-series visualization

\- Bar charts

\- Scatter plots

\- Bubble charts

\- Pie charts



\## Dashboard Development



\- Dash

\- Interactive dropdown controls

\- Callback functions

\- Dynamic visualization updates

\- Multi-report dashboard design



\## Business Analysis



\- Recession analysis

\- Vehicle segmentation

\- Marketing expenditure analysis

\- Pricing analysis

\- Seasonality analysis

\- Business insight generation



\---



\# 💻 Tech Stack



| Technology | Purpose |

|---|---|

| Python | Core development |

| Pandas | Data manipulation and aggregation |

| NumPy | Synthetic data generation and numerical operations |

| Matplotlib | Static visualization |

| Seaborn | Statistical visualization |

| Plotly | Interactive charts |

| Dash | Interactive dashboard |



\---



