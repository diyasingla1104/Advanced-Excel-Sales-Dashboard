# Advanced Excel E-Commerce Dashboard

### Project Overview
This project demonstrates how Excel can be used as a powerful data analysis and visualization tool.  
Using a **Sample E-Commerce Database**, the project analyzes **Sales** and **Profit** performance across different **Months**, **Regions**, and **Product Categories**, and presents the results through an interactive dashboard.

## Objectives
- Organize and format raw data for analysis.  
- Calculate **Total Sales** and **Profit** using Excel formulas.  
- Create **month-wise** and **region-wise** summaries.  
- Build an **interactive dashboard** linked with a Combo Box filter for product categories.  
- Visualize key insights through dynamic charts.

## Dataset
- **Source:** Sample E-Commerce Database  
- **Key Columns:**  
  `Date`, `Region`, `Product Category`, `Quantity`, `Sales`, `Profit`  

## Methodology

### 1️⃣ Data Cleaning & Preparation
- Formatted the dataset for readability and consistency.  
- Standardized numeric and date formats.  
- Created a calculated column:  

### 2️⃣ Month-wise Analysis (Working Sheet)
- Created a table summarizing **Total Sales** and **Profit** by month.  
- Applied the `SUMIFS()` function to aggregate data:
- Total Sales  
- Profit  

### 3️⃣ Region-wise Analysis
- Used the `SUMIFS()` formula to compute **Total Sales per Region**.

### 4️⃣ Interactive Control (Combo Box)
- Inserted a **Combo Box (Form Control)** on a new sheet named **Dashboard**.  
- Linked the Combo Box to the **Product Category** field.  
- Modified formulas in the month-wise and region-wise tables to respond dynamically to Combo Box selections.

### 5️⃣ Visualizations
Created multiple chart types to enhance insights:
| Chart Type | Data Source | Purpose |
|-------------|--------------|----------|
| 📊 Column Chart | Month-wise Table | Compare monthly sales |
| 🥧 Pie Chart | Region-wise Table | Show region contribution |
| 🔵 Scatter Chart | Sales & Profit | Analyze relationship |
| 📈 Line Chart | Months & Sales | Display sales trend |

### 6️⃣ Dashboard Creation
- Combined all tables and charts into a single **Dashboard sheet**.  
- Linked visuals to the Combo Box for **real-time filtering**.  
- Applied consistent color theme and professional layout for clear presentation.

## 🧠 Excel Concepts & Functions Used
- `SUMIFS()` for conditional aggregation  
- `IF()` for logical filtering  
- `INDEX-MATCH()` for dynamic referencing  
- Named Ranges  
- Combo Box (Form Control)  
- Pivot Tables (optional for validation)  
- Chart Tools (Formatting, Data Labels, Axes Control)

## 🎨 Dashboard Highlights
- **Dynamic filtering** by product category  
- **Automatic chart refresh** based on Combo Box selection  
- **Clean, business-oriented design**  
- **Actionable insights** on monthly and regional performance  

## 🧠 Key Insights
- Identified high-profit months and regions.  
- Highlighted underperforming product categories.  
- Visualized the correlation between Total Sales and Profit.  
- Enabled quick comparisons and interactive exploration.

## 🧰 Tools & Skills
| Category | Tools/Skills |
|-----------|--------------|
| Software | Microsoft Excel |
| Techniques | Data Cleaning, Dashboard Design, Chart Visualization |
| Functions | SUMIFS, IF, INDEX-MATCH, Combo Box |
| Soft Skills | Analytical Thinking, Business Reporting |

