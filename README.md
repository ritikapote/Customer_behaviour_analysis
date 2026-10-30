# 🛍️ Customer Shopping Behavior Analysis

### 📊 End-to-End Data Analytics Project | Python • MySQL • Power BI

## 📌 Overview

This project explores customer shopping behavior to understand purchasing patterns, product preferences, subscription trends, and discount usage.

The project follows an end-to-end data analytics workflow, from loading and cleaning raw data in Python to analyzing business questions using MySQL and building an interactive Power BI dashboard.

**🎯 Project Objectives**
- Analyze customer purchasing behavior and product preferences.
- Explore revenue and sales patterns across product categories.
- Examine subscription status and discount usage.
- Compare purchasing trends across customer age groups.
- Present insights through SQL queries, visualizations, and an interactive dashboard.

## 📂 Dataset

The project uses a customer shopping behavior dataset containing approximately **3,900 customer records**.

Key attributes include:

| Category | Example fields |
|---|---|
| Customer Information | Customer ID, age, gender, location |
| Purchase Details | Item purchased, category, purchase amount |
| Customer Preferences | Size, color, season, payment method |
| Shopping Behavior | Subscription status, discount usage, purchase frequency |
| Customer Feedback | Review rating |

## 🧰 Tools & Technologies

- 🐍 **Python** — Data loading, exploration, and cleaning
- 🧹 **Pandas** — Data manipulation and preprocessing
- 🗄️ **MySQL** — SQL queries and business analysis
- 📊 **Power BI** — Interactive dashboards and KPI visualization
- 📓 **Jupyter Notebook** — Python analysis and documentation
- 🤖 **Claude AI** — Assistance with presentation structure and content
- 🐙 **GitHub** — Project hosting and version control

## 🔄 Project Workflow

### 1. 🐍 Data Loading & Exploration

- Imported the dataset into Python using Pandas.
- Examined the dataset structure, column names, and data types.
- Reviewed summary statistics and checked for missing values and duplicate records.
- Explored customer demographics and purchasing variables.

### 2. 🧹 Data Cleaning & Preprocessing

- Investigated missing and inconsistent values.
- Checked for duplicate records and handled them where appropriate.
- Standardized data formats and corrected data types where necessary.
- Created an `age_group` column to support demographic comparisons.
- Prepared the dataset for further analysis.

### 3. 🗄️ SQL Analysis Using MySQL

- Loaded the dataset into a MySQL database.
- Wrote SQL queries to answer business-related questions.
- Used filtering, grouping, aggregation, sorting, and subqueries where appropriate.
- Analyzed purchase amounts, product ratings, discount usage, and customer behavior.

### 4. 📊 Power BI Dashboard

Developed an interactive dashboard to summarize customer shopping behavior.

**Dashboard highlights:**
- 👥 Number of Customers
- 💰 Average Purchase Amount
- ⭐ Average Review Rating
- 🥧 Customer Distribution by Subscription Status
- 📊 Revenue by Product Category
- 🛒 Sales by Product Category
- 👤 Revenue and Sales by Age Group
- 🎛️ Interactive slicers for customer and purchase attributes

### 5. 📝 Report & Presentation

- Used Claude AI to assist with organizing the PowerPoint presentation.
- Reviewed the final content for clarity and consistency with the analysis.

## 📊 Dashboard Preview

<img width="800" alt="Customer Shopping Behavior Dashboard" src="(keep your existing link here)" />


## 💡 Results & Key Insights

The analysis examines the following business questions:

- Which product categories generate the highest revenue and sales?
- How are customers distributed by subscription status?
- How do purchasing patterns differ across age groups?
- Which products receive higher average review ratings?
- Which products have the highest percentage of purchases with discounts applied?

## 📁 Project Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── eda_and_data_cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── presentation/
│   └── project_presentation.pptx
│
├── images/
│   └── dashboard.png
│
├── requirements.txt
└── README.md
```

*The structure above is a suggested layout. Adjust it to match the files actually present in your repository.*

## ⚙️ How to Run

### Prerequisites

- Python 3.x
- Jupyter Notebook
- MySQL Server and MySQL Workbench
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone <your-repository-url>
cd customer-shopping-behavior-analysis
```

### Step 2: Install Python Dependencies

If your repository contains a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Otherwise, install the core libraries used by your notebook:

```bash
pip install pandas numpy sqlalchemy mysql-connector-python jupyter
```

Install additional libraries only if your notebook uses them.

### Step 3: Run the Python Notebook

```bash
jupyter notebook
```

Open the notebook in the `notebooks/` directory and execute the cells in order. Update the dataset path and database connection settings if required.

### Step 4: Run the SQL Queries

1. Start MySQL Server.
2. Open MySQL Workbench.
3. Select the project database.
4. Ensure the dataset has been loaded into the required table.
5. Open and execute the SQL queries in the `sql/` directory.

### Step 5: Open the Power BI Dashboard

1. Open the `.pbix` file in Power BI Desktop.
2. Configure the data source connection if necessary.
3. Refresh the data.
4. Explore the dashboard using its charts and slicers.

### Step 6: Review the Report & Presentation

Open the project report and PowerPoint presentation to review the methodology, findings, and recommendations.

## 🚀 Conclusion

This project demonstrates practical experience with an end-to-end data analytics workflow, including data exploration, data cleaning, SQL querying, interactive dashboard development, and communicating insights through reports and presentations.

It showcases the use of Python, MySQL, and Power BI to transform customer shopping data into meaningful, business-oriented insights.

## 👩‍💻 Author

**[Ritika Pote]**

- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/)

---

⭐ *If you find this project useful, feel free to explore the repository and its analysis.*
