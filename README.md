# Sales-Analysis
🎯 Objective

Analyze 5 years of regional sales data to:

Identify revenue/profit inconsistencies across U.S. regions.

Understand seasonality, top-performing SKUs, and channel profitability.

Build an interactive dashboard for business teams to self-serve insights and support strategic decision-making.

🔄 Project Workflow

Data Collection & Preprocessing

Imported data from Excel sheets.

Normalized, cleaned, and joined tables.

Created new features (profit, profit_margin_pct, calendar fields).

Exported a clean dataset (Sales_data(EDA Exported).csv).

Exploratory Data Analysis (EDA)

Trend analysis (seasonality, revenue cycles).

Product performance comparison.

Channel contribution analysis (Wholesale, Distributor, Export).

State & regional performance mapping.

Customer segmentation (Revenue vs. Profit Margin).

Correlation analysis between numeric features.

Dashboard Creation (Power BI)

Page 1: Performance Summary (sales, profit, trends).

Page 2: Customer Segmentation (loyal, at-risk, profitable customers).

Page 3: Revenue Scenarios (what-if analysis, region/channel comparisons).

Presentation

Key findings and recommendations summarized in PPT.pptx.

📌 Key Insights

Seasonality: Sales dip in April, peak in May–June, lowest in January.

SKU Dependence: Products 25 & 26 contribute ~25% of revenue.

Channel Mix: Wholesale dominates (54%), Export leads margins (~38%).

Geographic Trends: California and the West region dominate sales.

Customer Segmentation: Top clients drive disproportionate revenue; margin monitoring required.

✅ Recommendations

Launch seasonal promotions to stabilize revenue swings.

Optimize SKUs: Double down on top performers, reprice/phase out low-margin products.

Expand Export partnerships for higher margins.

Replicate California’s model in other regions, especially Northeast & Midwest.

Implement margin monitoring to identify underperforming orders.

🚀 How to Run
1. Notebook (Python - Jupyter/Colab)
pip install pandas matplotlib seaborn plotly
jupyter notebook Regional_Sales_Analysis.ipynb

2. Power BI Dashboard

Open SALES REPORT.pbix in Power BI Desktop.

Connect to Sales_data(EDA Exported).csv if prompted.

3. Presentation

Open PPT.pptx for a structured overview of the project.

📦 Deliverables

Clean dataset → Sales_data(EDA Exported).csv

EDA Notebook → Regional_Sales_Analysis.ipynb

Interactive Dashboard → SALES REPORT.pbix

Business Presentation → PPT.pptx

👩‍💼 Stakeholder Value

Provides a data-driven roadmap for sales & marketing strategy.

Enables real-time decision making through Power BI.

Supports scalability—dashboard can onboard future datasets.
