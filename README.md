<img width="997" height="897" alt="Gemini_Generated_Image_22kfbp22kfbp22kf" src="https://github.com/user-attachments/assets/7cde1871-5831-41b3-9701-96d5400fd230" />📱 Day 1: Mobile Sales Data Analysis

The mobile phone industry is a highly competitive market driven by pricing, specifications, brand value, and logistics efficiency.
This project analyzes mobile sales transaction data to uncover insights related to sales performance, revenue generation, customer demand patterns, and operational efficienc





The analysis is performed using Python, Pandas, and data visualization techniques to simulate real-world business analytics!
📌 Project Objectives

This project focuses on solving key business problems in mobile retail analytics:

Revenue Analysis: Identify top-performing brands and regions generating maximum revenue.

Sales Performance: Analyze quantity sold across brands, RAM, and ROM configurations.

Pricing Insights: Understand price distribution and its impact on sales volume.

Regional Analysis: Compare sales and revenue across different regions.

Operational Efficiency: Analyze dispatch delays and their effect on sales.

Trend Analysis: Study monthly revenue trends over time.

📂 Dataset Information

The dataset is stored in a single CSV file containing transactional mobile sales data.

File Used

Mobile_Sales.csv

🧾 Dataset Schema
Column Name	Description
brand	Mobile brand name
price	Price of the mobile device
quantity_sold	Units sold
ram	RAM configuration
rom	ROM / storage configuration
region	Sales region
inward_date	Date product entered inventory
dispatch_date	Date product was dispatched
dispatch_days	Delivery delay in days (derived)
revenue	Total revenue (price × quantity sold)
🔧 Data Cleaning & Feature Engineering

Standardized column names (lowercase, snake_case)

Handled missing values using:

Median for numerical columns

Mode for categorical columns

Converted date columns to datetime format

Created new features:

Dispatch Days (Dispatch Date − Inward Date)

Revenue (Price × Quantity Sold)

Month for time-based analysis

❓ Business Questions Answered

What is the overall price distribution of mobile phones?

Which brands generate the highest revenue?

How does pricing vary across different brands?

Which regions contribute the most revenue?

Which regions sell the highest number of units?

Which RAM configurations are most popular?

Which ROM configurations sell the most?

What is the relationship between RAM, ROM, and quantity sold?

How does price impact quantity sold?

Do dispatch delays affect sales volume?

How does revenue change over time (monthly trend)?

📊 Key Analysis & Visualizations

Price distribution & outlier detection

Brand-wise price comparison

Revenue by brand

Revenue and unit sales by region

RAM-wise and ROM-wise sales analysis

RAM vs ROM heatmap (units sold)

Price vs quantity sold scatter plot

Dispatch delay vs sales analysis

Monthly revenue trend analysis

🛠 Tools & Technologies Used

Python

Pandas – Data manipulation & analysis

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Advanced statistical visualizations

Jupyter Notebook

📈 Key Insights

A small number of brands contribute the majority of total revenue.

Mid-range priced mobiles tend to sell in higher quantities.

Certain RAM–ROM combinations dominate customer preference.

Regional demand varies significantly in both revenue and units sold.

Dispatch delays can negatively impact sales volume.

Revenue shows noticeable variation across months, indicating seasonality.

🚀 Conclusion

This Mobile Sales Data Analysis project demonstrates how transactional data can be transformed into actionable business insights.
The project highlights skills in:

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Engineering

Business-Oriented Insight Generation

Data Visualization

This project is well-suited for Data Analyst / Business Analyst portfolios and reflects real-world retail analytics use cases.

📁 Repository Structure
Mobile-Sales-Data-Analysis/
│
├── data/
│   └── Mobile_Sales.csv
│
├── notebooks/
│   └── Mobile_Sales_Analysis.ipynb
│
└── README.md
