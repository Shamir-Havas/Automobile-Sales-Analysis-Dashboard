Automobile Sales Analysis & Dashboard

This project analyzes synthetic automobile sales data using Python (Pandas, Matplotlib, Seaborn) and builds an interactive dashboard with Plotly Dash.
It fulfills academic grading requirements by implementing specific tasks such as line plots, bar charts, pie charts, bubble plots, scatter plots, and dashboard interactivity.

--------------------------------------------------------------------------------
Project Structure

Automobile_Sales_Project/
│── data/
│   └── automobile_sales.csv     # Synthetic dataset
│
│── images/                      # Saved plots for grading
│   ├── Line_plot_1.png
│   ├── Line_plot_2.png
│   ├── Bar_Chart.png
│   ├── Subplot.png
│   ├── Bubble.png
│   ├── Scatter.png
│   ├── Pie_1.png
│   ├── Pie_2.png
│   └── Line_plot_3.png
│
│── app.py                       # Dash Dashboard code
│── analysis.py                   # Data analysis and visualization code
│── README.txt                    # Project documentation

--------------------------------------------------------------------------------
Setup Instructions

1. Clone Repository
    git clone https://github.com/yourusername/automobile-sales-analysis.git
    cd automobile-sales-analysis

2. Create Virtual Environment
    python -m venv venv
    venv\Scripts\activate   (Windows)
    source venv/bin/activate  (Mac/Linux)

3. Install Dependencies
    pip install -r requirements.txt

4. Run Analysis Scripts
    python analysis.py

5. Launch Dashboard
    python app.py

    Dashboard will run at: http://127.0.0.1:8050/

--------------------------------------------------------------------------------
Key Features
✔ Synthetic dataset for automobile sales
✔ Line plots, bar charts, scatter, bubble & pie charts
✔ Subplots comparing recession vs non-recession GDP
✔ Interactive Dash dashboard with dropdowns & callbacks
✔ Professional code structure for reproducibility

--------------------------------------------------------------------------------
Grading Criteria Coverage
- Task 1.1 → Line plot of yearly sales
- Task 1.2 → Line plot by vehicle type during recessions
- Task 1.3 → Seaborn bar chart recession vs non-recession
- Task 1.4 → Subplots for GDP trends
- Task 1.5 → Bubble plot for seasonality
- Task 1.6 → Scatter plot sales vs price
- Task 1.7 → Pie chart (advertising expenditure)
- Task 1.8 → Pie chart (vehicle type advertisement split)
- Task 1.9 → Line plot (unemployment vs sales)
- Task 2.1 → Dash app title
- Task 2.2 → Dropdowns
- Task 2.3 → Output div
- Task 2.4 → Callbacks
- Task 2.5 → Recession report graphs
- Task 2.6 → Yearly report graphs

--------------------------------------------------------------------------------
Author
Shamir Havas
