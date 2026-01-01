# Customer_Behavior_Analysis_Project
End-to-end customer shopping behavior analysis using Python, PostgreSQL, and Power BI. Analyzed 3,900 transactions to uncover insights on product performance, discounts, customer segments, and purchasing trends.

📊 Customer Shopping Behavior Analysis

📌 Overview
This project performs an end-to-end data analytics workflow to analyze customer shopping behavior using transactional data. The objective is to uncover insights related to customer demographics, purchasing patterns, product performance, discount usage, and subscription behavior to support data-driven business decisions.

The project covers the complete analytics pipeline—from data preparation in Python, SQL-based analysis in PostgreSQL, to visualization using Power BI and business storytelling through a presentation.

📂 Dataset
- Source: Customer shopping behavior dataset  
- Total Records: 3,900  
- Total Features: 18  

Key attributes include customer demographics, purchase details, and shopping behavior such as discounts, shipping preferences, review ratings, and purchase frequency.

🛠 Tools & Technologies
- Python (Jupyter Notebook)
- Pandas, NumPy
- PostgreSQL
- SQLAlchemy
- Power BI
- PowerPoint

🔍 Data Preparation & Analysis

Python (EDA & Cleaning)
- Loaded and explored the dataset using pandas
- Handled missing values using category-wise median imputation
- Standardized column names for consistency
- Engineered features such as age groups and purchase frequency
- Validated data consistency and removed redundant columns
- Loaded the cleaned dataset into PostgreSQL

SQL (PostgreSQL Analysis)
- Revenue analysis by gender and age group
- Subscriber vs non-subscriber spending comparison
- Identification of discount-dependent products
- Top-rated and most purchased products
- Customer segmentation based on purchase history
- Shipping type and spending analysis

📊 Dashboard (Power BI)
An interactive Power BI dashboard was built to visualize key metrics including revenue trends, product performance, customer segments, subscription impact, and discount usage, enabling stakeholder-friendly insights.

📈 Key Insights & Results
- Discount usage significantly impacts sales for select products
- Subscribers show higher average spending behavior
- Certain age groups contribute disproportionately to total revenue
- A small number of products dominate category-level sales

▶️ How to Run the Project
1. Clone the repository  
2. Open the Jupyter Notebook and install required Python libraries  
3. Run EDA and data cleaning steps in Python  
4. Load the cleaned dataset into PostgreSQL  
5. Execute SQL queries for analysis  
6. Open the Power BI file to explore the dashboard  
7. Review the presentation for summarized insights

📌 Project Outcome
This project demonstrates practical experience in data cleaning, SQL analytics, dashboard development, and business storytelling, aligned with Data Analyst and Business Intelligence roles.
