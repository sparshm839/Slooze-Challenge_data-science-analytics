 📦 Inventory Optimization & Analytics Project
 🧠 Challenge Overview

A retail wine & spirits company operating across multiple locations manages millions of sales, purchase, and inventory transactions. Traditional spreadsheet-based analysis is no longer effective. This project introduces a data-driven solution to optimize inventory control, improve supply chain efficiency, and extract actionable insights from high-volume data.



Project Objectives

1. ABC Analysis
   Categorize inventory into A (high-value), B (moderate), and C (low-priority) items to prioritize critical stock.

2. EOQ Analysis (Economic Order Quantity)
   Calculate optimal order quantity to minimize both ordering and holding costs.

3. Demand Forecasting
   Use time series modeling (Prophet/ARIMA) to predict future product demand accurately.

4. Reorder Point (ROP) Calculation
   Identify when to reorder each item to avoid stockouts by factoring in average demand and lead time.

5. Lead Time Analysis
   Analyze vendor delivery patterns to optimize procurement timelines.

6. Statistical Visualizations
   Bar charts, boxplots, and time series graphs to present trends and patterns.

7. Power BI Dashboard 
   Visual analytics dashboard for business stakeholders (included in `PowerBI/` folder).


📁 Project Structure


inventory-analytics-project/
│
├── data/                         
│   ├── EndInvFINAL12312016.csv
│   ├── BegInvFINAL12312016.csv
|   ├── EndInvFINAL12312016.csv
|   ├──  InvoicePurchases12312016.csv
|   ├──  PurchasesFINAL12312016.csv
|   ├──  SalesFINAL12312016.csv
│
├── notebooks/                  
│   └── inventory_analysis.ipynb
│
├── PowerBI/                     
│   └── inventory_dashboard.pbix
|   └── dashboard.jpg
│
├── requirements.txt             
├── README.md                    




📊 Tools & Technologies

* Python (Pandas, Seaborn, Matplotlib, Scikit-learn)
* Time Series Models: Prophet, ARIMA, pmdarima
* Power BI for dynamic dashboards
* Jupyter Notebooks for analysis pipeline

