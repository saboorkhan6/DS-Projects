# Superstore Sales – Exploratory Data Analysis & Visualization

## 📌 Project Overview

This project focuses on exploring and visualizing the Superstore sales dataset using Python. The objective is to analyse sales and profitability patterns, identify trends, and understand relationships between different business factors through data visualization.

The project was completed as part of my Data Science training at **ILS**.

## 📂 Dataset

- **Dataset:** Superstore.csv
- **Records:** 9,994
- **Columns:** 21

The dataset contains information about orders, customers, product categories, sales, discounts, profits and geographical regions.

## 🛠️ Tools & Libraries

- **Python** – Programming language
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization

## 📊 Analyses & Visualizations

Five different analytical questions were explored using visualizations.

### 1. Sales by Product Category – Bar Chart

**Question:** Which product category generates the highest sales?

- Grouped sales by product category.
- Compared total sales across different categories.
- Used a bar chart to visualize the results.


### 2. Order Value Distribution – Boxen Plot

**Question:** How does order value vary across regions and product categories?

- Examined the distribution of sales across four regions.
- Compared product categories within each region.
- Used a logarithmic scale to visualize the distribution.



### 3. Regional Profitability – Heatmap

**Question:** Which product sub-categories generate the most or least profit in each region?

- Grouped profit by product sub-category and region.
- Compared profitability across different geographical regions.
- Used a heatmap to identify variations in profit.

### 4. Monthly Sales Trends – Line Chart

**Question:** How do sales change over time?

- Converted order dates into datetime format.
- Aggregated sales on a monthly basis.
- Used a line chart to visualize changes in monthly sales.

### 5. Discount vs Profit – Scatter Plot

**Question:** Do bigger discounts reduce profit?

- Examined the relationship between discounts and profit.
- Used product categories to distinguish observations.
- Visualized the relationship using a scatter plot.

## 📁 Project Structure

```text
1. Data Visualization & Analysis/
│
├── index.ipynb
├── Superstore.csv
├── README.md
│
├── 1_bar_category_sales.png
├── 2_box_sales_by_region_category.png
├── 3_heatmap_subcategory_region.png
├── 4_line_monthly_sales.png
└── 5_scatter_discount_profit.png
```

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas matplotlib seaborn jupyter
```

4. Make sure `Superstore.csv` is in the same folder as the notebook.
5. Run `index.ipynb` cell by cell to explore the analysis and visualizations.

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Working with a real-world dataset.
- Data inspection and exploratory data analysis.
- Data grouping, aggregation and manipulation using Pandas.
- Creating different types of visualizations.
- Analysing sales and profitability patterns.
- Interpreting data through graphical representations.

---

**Project completed as part of Data Science training at ILS.**
