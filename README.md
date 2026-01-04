# Customer-Shopping-Behavior-Analysis
A complete end-to-end analytics project on customer shopping behavior using Python, SQL and Power BI. Covers data cleaning, feature engineering, cohort analysis, segmentation, and interactive dashboards to derive actionable insights on revenue, loyalty, and subscriptions.

Overview
This project is an end-to-end data analytics case study on customer shopping behavior. It covers data loading, exploratory data analysis (EDA), data cleaning, SQL-based business analysis, dashboard creation in Power BI, and final storytelling through a written report and presentation.
​

Dataset: 3,900 purchase records across multiple product categories
18 features including:
Customer demographics (age, gender, location, subscription status)
Transaction details (item, category, amount, season, size, color)
Behavior signals (discount applied, previous purchases, review rating, shipping type)
​

Tools & Technologies
Programming: Python (pandas, numpy, matplotlib/seaborn)

Databases: PostgreSQL / MySQL / SQL Server (interchangeable SQL layer)

BI & Visualization: Power BI

Documentation: Written report (PDF)

Presentation: Gamma-powered slide deck
​

Project Steps
1. Data Loading & Understanding
Imported raw dataset into Python using pandas.

Inspected schema, data types, and basic stats to understand quality and distribution.
​

2. Exploratory Data Analysis (EDA)
Analyzed distributions of key features (age, purchase amount, review rating, frequency).

Explored relationships between demographics, discounts, subscription status, and revenue.

Identified missing values, outliers, and potential data quality issues.
​

3. Data Cleaning & Feature Engineering
Handled missing values (e.g., imputed missing review ratings with category-wise medians).

Standardized column names and formats for consistency.

Created derived fields such as age groups and purchase frequency indicators.

Removed redundant features (e.g., overlapping discount-related fields).
​

4. SQL Business Analysis
Executed a series of SQL queries on the cleaned dataset in PostgreSQL/MySQL/SQL Server to answer key business questions, including:

Revenue by gender and age group

Impact of discounts on high-spending customers

Top products by review rating and purchase volume

Comparison of spend by shipping type

Subscriber vs non-subscriber revenue and average spend

Customer segmentation (New, Returning, Loyal)

Discount-dependent products and repeat buyer behavior
​

5. Power BI Dashboard
Built an interactive Power BI dashboard to surface insights visually:

KPIs: total revenue, average purchase amount, churn/loyalty-style segments

Customer segmentation by demographics, subscription status, and purchase behavior

Product performance by category, rating, and discount usage

Revenue contribution by age groups and shipping preferences
​

6. Report & Presentation
Compiled a structured written report summarizing the methodology, analysis, and recommendations.

Created a Gamma-based slide deck highlighting key visuals, business insights, and next steps for stakeholders.
​

Results & Insights (High-Level)
Clear visibility into which segments and products drive the most revenue.

Understanding of how discounts, subscriptions, and shipping choices influence customer value.

Actionable recommendations around subscriptions, loyalty programs, discount strategy, and targeted marketing.
​

How to Run
Clone the Repository

bash
git clone <your-repo-url>.git
cd <your-repo-folder>
Set Up Python Environment

Create and activate a virtual environment.

Install dependencies (requirements.txt if provided):

bash
pip install -r requirements.txt
Run the Python Analysis

Open the Jupyter notebook or Python script (e.g., eda_and_cleaning.ipynb / .py).

Execute cells/sections in order to:

Load data

Perform EDA

Clean and transform the dataset

Export cleaned data to CSV or directly to the database
​

Load Data into Database

Configure database connection details in the SQL/Python config file.

Run the script/notebook section that writes the cleaned dataset to PostgreSQL/MySQL/SQL Server.

Execute SQL queries from the /sql folder using your preferred client or via notebook.
​

Open Power BI Dashboard

Open the .pbix file in Power BI Desktop.

Refresh data connections to point to your local database or cleaned CSV.

Interact with filters and visuals to explore insights.
​

View Report & Presentation

Open the PDF report in the /reports folder.

Open the Gamma presentation link or exported PDF in the /presentation folder.
​

Intended Audience
Recruiters and hiring managers evaluating data analytics, SQL, and BI skills

Teams looking for an example of an end-to-end analytics project—from raw data to insights and storytelling

