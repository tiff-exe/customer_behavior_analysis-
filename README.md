# Customer Shopping Behavior Analysis

## Overview

An end-to-end data analytics project exploring consumer purchasing patterns, demographic segmentations, and transactional drivers. The project encompasses exploratory data analysis (EDA) and data preprocessing in Python, relational querying in SQL, interactive visual storytelling in Power BI.

---

## Tech Stack & Tools

* **Programming & EDA:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`)


* **Database & Querying:** SQL (PostgreSQL / MySQL / SQL Server)


* **Business Intelligence:** Microsoft Power BI


* **Reporting & Presentation:** Gamma App



---

## Dataset

* **File:** `customer_shopping_behavior.csv`

* **Attributes:** Includes customer demographics (age, gender), product categories, purchase amounts, subscription statuses, discount applications, review ratings, and preferred payment/shipping methods.



---

## Project Workflow

1. **Data Ingestion & Preprocessing (Python):** Cleaned data in `Customer_shopping_behavior.ipynb`, checked for missing values, handled categorical data encoding, and identified statistical distributions.


2. **Exploratory Data Analysis (EDA):** Evaluated purchasing frequency, average spend by demographic group, and the relationship between discounts and customer satisfaction.


3. **Database Querying (SQL):** Authored structured queries in `customer_shopping_behavior.sql` to calculate aggregate metrics, segment revenue contribution, and extract targeted cohorts.


4. **Interactive Dashboarding (Power BI):** Built dynamic data models and visual metrics in `customer dashboard.pbix` with interactive filtering for customer segments, product categories, and purchase behavior.


5. **Executive Summary & Presentation:** Structured business insights and strategic recommendations into a presentation using Gamma.



---

## Dashboard Preview

*(Add screenshots or GIFs of your Power BI report here)*

* **Core Features:** Dynamic slicers for demographics and subscription status, KPI summary cards (Total Revenue, Average Review Rating, Repeat Purchase Rate), and categorical breakdown charts.



---

## Key Insights & Business Takeaways

* **Segment Contribution:** Analyzed customer demographic tiers to identify primary revenue drivers across product categories.


* **Promotional Impact:** Assessed discount code usage versus regular purchases to determine impact on average purchase value.


* **Channel & Loyalty Trends:** Identified shopping frequency differences between subscribed and non-subscribed customers to guide retention strategies.



---

## Repository Structure

```text
├── Customer_shopping_behavior.ipynb    # Python EDA and data cleaning notebook
├── customer_shopping_behavior.csv      # Raw dataset
├── customer_shopping_behavior.sql      # SQL queries and aggregations
├── customer dashboard.pbix             # Interactive Power BI dashboard
├── LICENSE                             # License information
└── README.md                           # Project documentation

```

---

## How to Run

### 1. Python Environment Setup

```bash
git clone https://github.com/[your-username]/customer_behavior_analysis.git
cd customer_behavior_analysis
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Customer_shopping_behavior.ipynb

```

### 2. SQL Queries Execution

* Open `customer_shopping_behavior.sql` in your preferred SQL management tool (e.g., pgAdmin, MySQL Workbench, SSMS).


* Import `customer_shopping_behavior.csv` into a database table and execute the query scripts.



### 3. Power BI Dashboard

* Open `customer dashboard.pbix` in **Power BI Desktop**.


* Refresh or reconnect the data source to your local path for `customer_shopping_behavior.csv`.
