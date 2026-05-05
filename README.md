📌 Project Overview This project analyzes real-world transactional data from an online retail store to uncover sales trends, customer behavior, and key business insights. The dataset contains over 500,000 records, making it a practical case study in real-world data analysis.

🎯 Objective Understand sales patterns across products and regions Identify top-performing products and customers Analyze seasonal trends and revenue drivers Clean and transform raw data for meaningful insights

🛠️ Tools & Technologies Python Pandas, NumPy → Data Cleaning & Transformation Matplotlib, Seaborn → Data Visualization Jupyter Notebook

📂 Dataset Source UCI Machine Learning Repository Contains transactional data including: InvoiceNo, StockCode, Description Quantity, UnitPrice CustomerID, Country InvoiceDate

🧹 Data Cleaning Removed missing CustomerID values Filtered out negative quantities (returns/cancellations) Removed invalid price entries Converted date columns to proper datetime format Created new feature: TotalPrice = Quantity × UnitPrice

📊 Exploratory Data Analysis (EDA) Region-wise and country-wise sales analysis Top-selling products identification Monthly sales trend analysis Correlation analysis between key numerical variables

📈 Visualizations 📊 Bar charts → Top countries & products 📈 Line plots → Monthly sales trends 🔥 Heatmap → Correlation between variables

📊 Final Business Insights & Recommendations

🎯 Revenue Concentration (Geographic Risk) 
The United Kingdom contributes ~84% of total revenue. Remaining countries contribute marginally. The business is heavily dependent on a single market, creating geographic risk.

🛒 Product Concentration (Pareto Analysis) 
A small percentage of products generates ~80% of total revenue. Revenue is driven by a limited set of high-performing products.

👥 Customer Segmentation (RFM Analysis) 
Identified high-value customers with Low Recency (recent buyers), High Frequency (repeat purchases) and High Monetary value (high spend). A small segment of customers contributes a disproportionately high share of revenue.

🔁 Customer Behavior Patterns 
High-value customers purchase more frequently and recently and spend significantly higher amounts. Strong engagement and retention behavior exists among top customers.

⚠️ Business Risk 
Heavy reliance on UK market and small customer segment. Losing key customers or market demand may significantly impact revenue.

📈 Growth Opportunities & Recommendations
Convert mid-tier customers → high-value segment 
Expand geographically (EU, Australia) 
Promote high-performing products 
Diversify revenue streams to reduce dependency 
Prioritize inventory for top products 
Bundle slow-moving products with bestsellers 
Launch loyalty programs and provide exclusive offers
Focus on retention over acquisition
