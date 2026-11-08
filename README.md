# Datheon Data Analytics Internship Journey

A practical portfolio documenting my four-task data analytics internship
journey: from exploratory data analysis to interactive business
dashboards, customer churn analysis, and financial performance modeling.

> **About this repository:** This repository contains my learning work,
> analysis notebooks, dashboards, reports, and supporting files prepared
> for the Datheon internship task sequence. It is intended as a
> portfolio and a record of the process I followed.

## My internship journey

I approached each task as a step toward understanding how raw business
data can be transformed into useful decisions.

### Task 1 --- Exploratory Data Analysis (EDA): Superstore Retail Sales

**Goal:** Explore retail sales data, clean and prepare it, and identify
patterns in customer purchases, sales, profit, product categories,
regions, and discounts.

**Work covered** - Loaded and inspected the Superstore dataset. -
Reviewed missing values and data quality. - Prepared date-related fields
and grouped sales over time. - Explored sales and profit across
categories, regions, and customer segments. - Examined the relationship
between discounting and profit. - Summarized business observations and
findings.

**Main deliverable:** `Task-1-EDA/Datheon_Task_1_Superstore_EDA.ipynb`

### Task 2 --- Executive Sales & Profit Dashboard

**Goal:** Turn retail transaction data into an executive-level sales and
profitability view.

**Work covered** - Prepared a cleaned Superstore dataset. - Defined DAX
measures for sales, profit, orders, units, margin, and year-over-year
comparisons. - Designed dashboard views for monthly sales, regional
performance, category performance, and discount sensitivity. - Prepared
an executive PDF report and an interactive HTML dashboard.

**Main deliverables** - Interactive dashboard:
`Task-2-PowerBI-Sales-Profit/Datheon_Task2_Interactive_Dashboard.html` -
Executive report:
`Task-2-PowerBI-Sales-Profit/Datheon_Task2_Executive_Sales_Profit_Report.pdf` -
Cleaned data:
`Task-2-PowerBI-Sales-Profit/Datheon_Task2_Superstore_Cleaned.csv` - DAX
reference: `Task-2-PowerBI-Sales-Profit/Datheon_Task2_DAX_Measures.txt`

### Task 3 --- Customer Cohort & Churn Analytics

**Goal:** Understand customer churn and identify customer groups that
may need retention attention using the IBM Telco Customer Churn dataset.

**Work covered** - Cleaned customer-level fields and prepared churn and
retention flags. - Calculated overall churn and retention rates. -
Compared churn across contract types, payment methods, internet
services, and support options. - Built a tenure-band retention matrix
and supporting visualizations. - Developed practical retention
recommendations.

**Main deliverables** - Interactive dashboard:
`Task-3-Customer-Churn/Datheon_Task3_Telco_Churn_Dashboard.html` -
Analysis notebook:
`Task-3-Customer-Churn/Datheon_Task3_Customer_Churn_Analysis.ipynb` -
Report: `Task-3-Customer-Churn/Datheon_Task3_Churn_Analysis_Report.pdf`

**Data limitation:** The supplied Telco dataset includes customer tenure
but does not include customer signup dates or a shared observation date.
Therefore, the retention matrix is a cross-sectional comparison by
current tenure band and contract type; it is not a true
acquisition-vintage cohort or survival analysis.

### Task 4 --- Corporate Financial & Margin Performance

**Goal:** Analyze revenue, discounts, net sales, cost of goods sold
(COGS), and profit, then explore financial scenarios.

**Work covered** - Prepared the Microsoft Financial Sample dataset. -
Calculated financial KPIs, including gross profit margin and COGS
ratio. - Compared quarterly sales and profit and reviewed segment
profitability. - Visualized the movement from gross sales through
discounts, net sales, COGS, and profit. - Added editable scenario
assumptions and an illustrative budget-versus-actual planning baseline.

**Main deliverables** - Interactive dashboard:
`Task-4-Financial-Performance/Datheon_Task4_Interactive_Financial_Dashboard.html` -
Excel dashboard and scenario model:
`Task-4-Financial-Performance/Datheon_Task4_Financial_Dashboard_and_Model.xlsx` -
PDF report:
`Task-4-Financial-Performance/Datheon_Task4_Financial_Performance_Report.pdf`

**Data limitation:** The supplied financial dataset contains actual
sample records but no approved budget targets. The budget comparison is
explicitly illustrative and must be replaced with organization-approved
budget values before it is presented as official budget variance.

## Tools and technologies

-   Python
-   Pandas and NumPy
-   Matplotlib and Seaborn
-   Plotly
-   Jupyter Notebook
-   Microsoft Excel
-   Power BI concepts and DAX measure design
-   Data cleaning, exploratory analysis, KPI reporting, dashboard
    design, and scenario modeling

## Repository structure

``` text
Datheon_Internship_Portfolio/
├── README.md
├── .gitignore
├── Task-1-EDA/
│   └── Datheon_Task_1_Superstore_EDA.ipynb
├── Task-2-PowerBI-Sales-Profit/
│   ├── Datheon_Task2_Interactive_Dashboard.html
│   ├── Datheon_Task2_Executive_Sales_Profit_Report.pdf
│   ├── Datheon_Task2_Superstore_Cleaned.csv
│   └── Datheon_Task2_DAX_Measures.txt
├── Task-3-Customer-Churn/
│   ├── Datheon_Task3_Telco_Churn_Dashboard.html
│   ├── Datheon_Task3_Customer_Churn_Analysis.ipynb
│   └── Datheon_Task3_Churn_Analysis_Report.pdf
└── Task-4-Financial-Performance/
    ├── Datheon_Task4_Interactive_Financial_Dashboard.html
    ├── Datheon_Task4_Financial_Dashboard_and_Model.xlsx
    └── Datheon_Task4_Financial_Performance_Report.pdf
```

## How to view the work

1.  Open the HTML dashboard files in a modern browser to explore
    interactive charts.
2.  Open the `.ipynb` notebooks in Jupyter Notebook or Google Colab.
3.  Open the Excel workbook in Microsoft Excel or a compatible
    spreadsheet application.
4.  Open the PDF reports for concise summaries and recommendations.

## Important deliverable notes

-   The HTML dashboards, notebooks, Excel workbook, and PDF reports are
    included as the available project outputs.
-   These files are **not native Power BI `.pbix` reports**. Where an
    internship portal specifically requires a `.pbix`, that file must be
    created and saved in Power BI Desktop.
-   The analysis reflects the datasets supplied for the tasks.
    Limitations and illustrative assumptions are identified above and in
    the relevant reports.

## What I learned

This journey helped me practice the end-to-end analytics workflow:

1.  Understanding a business problem and its dataset.
2.  Cleaning, validating, and transforming data.
3.  Exploring patterns with descriptive statistics and visualizations.
4.  Translating analysis into KPIs and dashboard views.
5.  Explaining findings in business language.
6.  Using scenario assumptions carefully and communicating data
    limitations.

The biggest takeaway was that a good analytics project is not only about
charts or code. It is about asking the right questions, checking the
quality of the data, explaining what the results mean, and being
transparent about what the data cannot prove.

------------------------------------------------------------------------

*Prepared as a learning and portfolio record of my data analytics
internship task journey.*

