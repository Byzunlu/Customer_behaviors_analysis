# 📊 Data Analytics Project

> 🇹🇷 [Türkçe versiyon için tıklayın](README_TR.md)

## 📌 Overview

This project demonstrates an end-to-end data analytics workflow, from loading and cleaning raw data to performing exploratory data analysis (EDA), running SQL queries, building an interactive Power BI dashboard, and presenting the final insights through a report and presentation.

The goal of this project is to transform raw data into meaningful insights that can support data-driven decision-making.

---

## 🎯 Project Objectives

The main objectives of this project are to:

* Load and understand the dataset
* Perform Exploratory Data Analysis (EDA)
* Clean and prepare the data for analysis
* Identify trends, patterns, and key insights
* Use SQL to answer business-related questions
* Build an interactive Power BI dashboard
* Create a final report summarizing the analysis
* Present key findings and recommendations

---

## 📂 Dataset

The dataset was analyzed and prepared through several stages, including:

* Understanding the dataset structure
* Checking data types
* Identifying missing values
* Detecting duplicate records
* Handling inconsistent or incorrect data
* Creating new variables where necessary

The project uses both raw and cleaned versions of the dataset.

---

## 🛠️ Tools and Technologies

The following tools and technologies were used:

| Tool                            | Purpose                              |
| ------------------------------- | ------------------------------------ |
| Python                          | Data loading, cleaning, and analysis |
| Pandas                          | Data manipulation and analysis       |
| NumPy                           | Numerical operations                 |
| Matplotlib / Seaborn            | Data visualization                   |
| SQL                             | Data querying and analysis           |
| PostgreSQL / MySQL / SQL Server | Database management                  |
| Power BI                        | Interactive dashboard development    |
| Jupyter Notebook                | Data analysis workflow               |
| Gamma                           | Presentation creation                |

---

## 🔄 Project Workflow

### 1. Data Loading

The dataset was loaded into Python and initially examined to understand its structure.

The following checks were performed:

* Number of rows and columns
* Column names
* Data types
* Missing values
* Basic descriptive statistics

---

### 2. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to better understand the data and identify important patterns.

Key analysis areas included:

* Distribution of variables
* Trends over time
* Relationships between variables
* Category and segment comparisons
* Outlier detection
* Identification of important patterns

Visualizations were created to communicate the findings clearly.

---

### 3. Data Cleaning

The raw data was cleaned and prepared for further analysis.

The data cleaning process included:

* Handling missing values
* Removing duplicate records
* Correcting inconsistent data
* Converting data types
* Standardizing column values
* Creating new calculated columns where required

---

### 4. SQL Analysis

The cleaned dataset was imported into a relational database and analyzed using SQL.

The analysis includes queries using:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `JOIN`
* `CASE WHEN`
* Aggregate Functions
* Subqueries

SQL queries were used to answer relevant business questions and extract actionable insights from the data.

---

## 📊 Power BI Dashboard

An interactive dashboard was created in Power BI to visualize the key findings.

The dashboard includes:

* Key Performance Indicators (KPIs)
* Trend analysis
* Category comparisons
* Segment analysis
* Interactive filters
* Data-driven visualizations

The purpose of the dashboard is to make the analysis easier to understand and support effective decision-making.

---

## 🔍 Key Insights and Results

The analysis identified important trends and patterns within the dataset.

Key findings include:

* Identification of major performance trends
* Comparison of different categories and segments
* Detection of factors affecting overall performance
* Analysis of changes over time
* Discovery of opportunities for improvement

Detailed findings and recommendations are available in the final report and presentation.

---

## 📄 Report and Presentation

The final results of the project were documented in two formats:

* **Report:** Detailed explanation of the analysis process, methodology, findings, and recommendations
* **Presentation:** A summary of the key insights and conclusions for easier communication with stakeholders

The presentation was created using Gamma.

---

## 📁 Project Structure

```text
data-analytics-project/
│
├── data/
│   ├── raw/                      # Raw dataset
│   └── cleaned/                  # Cleaned dataset
│
├── notebooks/
│   ├── 01_data_loading.ipynb     # Data loading and initial exploration
│   ├── 02_eda.ipynb              # Exploratory Data Analysis
│   └── 03_data_cleaning.ipynb    # Data cleaning and preparation
│
├── sql/
│   └── analysis_queries.sql      # SQL queries
│
├── dashboard/
│   └── powerbi_dashboard.pbix    # Power BI dashboard
│
├── reports/
│   └── project_report.pdf        # Final report
│
├── presentation/
│   └── project_presentation      # Gamma presentation
│
├── README.md                     # English README
├── README_TR.md                  # Turkish README
└── requirements.txt              # Python dependencies
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone <repository-url>
cd data-analytics-project
```

### 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3. Run the Python Analysis

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then run the notebooks inside the `notebooks/` folder in the following order:

1. `01_data_loading.ipynb`
2. `02_eda.ipynb`
3. `03_data_cleaning.ipynb`

### 4. Run the SQL Queries

Import the cleaned dataset into your preferred database management system:

* PostgreSQL
* MySQL
* SQL Server

Then run the queries available in:

```text
sql/analysis_queries.sql
```

### 5. Open the Power BI Dashboard

Open the `.pbix` file located in the `dashboard/` folder using Power BI Desktop.

---

## 💡 Skills Demonstrated

This project demonstrates the following data analytics skills:

* Data Cleaning
* Data Preparation
* Exploratory Data Analysis (EDA)
* Data Visualization
* Python Programming
* Pandas and NumPy
* SQL Querying
* Database Analysis
* Power BI Dashboard Development
* Business Analysis
* Data Storytelling
* Report Writing
* Presentation of Analytical Insights

---

## 👤 Author

**[Beyza ÜNLÜ]**

Aspiring Data Analyst | Python | SQL | Power BI

* GitHub: [(https://github.com/Byzunlu/BeyzaNL)]
* LinkedIn: [(https://www.linkedin.com/in/beyza-%C3%BCnl%C3%BC-b17878333?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)]

---

## 📬 Contact

If you have any questions, feedback, or suggestions about this project, feel free to connect with me through GitHub or LinkedIn.
