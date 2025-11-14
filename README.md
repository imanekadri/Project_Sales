# Monthly Sales Analysis (2025) – NumPy, Pandas, Matplotlib & Seaborn

## Project Overview
This project simulates a real-world business scenario where monthly sales data for four products is generated, analyzed, and visualized over the year 2025. The goal is to extract actionable insights about sales trends, best-selling products, peak months, and high-performing quarters using Python’s data science libraries.

## Project Structure
project_sales/


├── notebook.ipynb        # Main Jupyter notebook with all analysis and visualizations

├── utils.py              # Functions for data generation


├── data/
│   ├── initial.csv       # Raw generated dataset
│   ├── final.csv         # Dataset with calculated metrics
│   └── output.csv        # Pivot tables and summaries
└── requirements.txt      # Project dependencies



## Libraries Used
- **NumPy** – for generating random sales data.
- **Pandas** – for data manipulation, metrics, and pivot tables.
- **Matplotlib** – for line charts and stacked bar charts.
- **Seaborn** – for heatmaps and boxplots.

## Project Steps

### 1. Data Generation
- Generate monthly dates for 2025.
- Create random sales data for four products:
  - Product A: 50–100 units
  - Product B: 30–80 units
  - Product C: 20–60 units
  - Product D: 10–50 units
- Save the dataset as `initial.csv`.

### 2. Data Preparation
- Build a DataFrame with additional metrics:
  - Total sales per month
  - Average sales per month
  - Month-over-month growth
  - Quarter assignment (Q1, Q2, Q3, Q4)
  - Max and min sales product per month
- Save the updated DataFrame as `final.csv`.

### 3. Pivot Tables & Summaries
- Compute average sales per quarter for each product and total sales.
- Compute total sales per quarter.
- Save the results as `output.csv`.

### 4. Key Insights
- Identify the best month (highest total sales).
- Identify the best product (highest annual sales).
- Identify the best quarter (highest total sales).

### 5. Visualizations
- **Line Chart** – shows monthly trends per product.
- **Stacked Bar Chart** – shows total monthly sales broken down by product (best month annotated).
- **Heatmap** – visualizes monthly sales per product using colors.
- **Boxplot** – shows distribution of sales per product.

## Purpose of the Project
- Determine which product is the most popular throughout the year.
- Identify peak sales months and best-performing quarters.
- Provide data-driven insights to support marketing, inventory, and sales strategy.

### Screenshots
## Line Chart
<img width="850" height="470" alt="image" src="https://github.com/user-attachments/assets/6717ac2f-b015-4c43-a769-71dd1088be22" />

## Stacked Bar Chart
<img width="1023" height="646" alt="image" src="https://github.com/user-attachments/assets/d0eeb121-fbed-4e1f-80d1-03360a526617" />

## Heatmap
<img width="904" height="547" alt="Heatmap" src="https://github.com/user-attachments/assets/c38e116c-93bd-4a05-8c0f-381b61da542d" /> 

## Boxplot
<img width="695" height="528" alt="Boxplot" src="https://github.com/user-attachments/assets/7c3ae384-8cd2-4c42-8430-cc03558a2758" />

### Output Files

initial.csv – raw generated sales data.

final.csv – data with metrics added.

output.csv – pivot tables for analysis.

### Install required libraries:

pip install -r requirements.txt

Open notebook.ipynb in Jupyter Notebook or VSCode.

Run all cells to generate data, compute metrics, create pivot tables, and visualize results.


## How to Run
1. Clone the repository:
```bash

git clone https://github.com/yourusername/project_sales.git
pip install -r requirements.txt
 
 
 
