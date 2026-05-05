online-retail-analysis
End-to-end data analysis using Python, including RFM and Pareto analysis

📌 Project Overview This project analyzes real-world transactional data from an online retail store to uncover sales trends, customer behavior, and key business insights. The dataset contains over 500,000 records, making it a practical case study in real-world data analysis.

🎯 Objective Understand sales patterns across products and regions Identify top-performing products and customers Analyze seasonal trends and revenue drivers Clean and transform raw data for meaningful insights

🛠️ Tools & Technologies Python Pandas, NumPy → Data Cleaning & Transformation Matplotlib, Seaborn → Data Visualization Jupyter Notebook

📂 Dataset Source UCI Machine Learning Repository Contains transactional data including: InvoiceNo, StockCode, Description Quantity, UnitPrice CustomerID, Country InvoiceDate

🧹 Data Cleaning Removed missing CustomerID values Filtered out negative quantities (returns/cancellations) Removed invalid price entries Converted date columns to proper datetime format Created new feature: TotalPrice = Quantity × UnitPrice

📊 Exploratory Data Analysis (EDA) Region-wise and country-wise sales analysis Top-selling products identification Monthly sales trend analysis Correlation analysis between key numerical variables

📈 Visualizations 📊 Bar charts → Top countries & products 📈 Line plots → Monthly sales trends 🔥 Heatmap → Correlation between variables
