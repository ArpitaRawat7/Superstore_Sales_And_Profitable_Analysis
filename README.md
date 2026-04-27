## Superstore Sales & Profitability Analysis

## 📊 Project Overview
This project analyzes retail data from a "Superstore" to identify growth trends and profitability leaks. The dashboard provides a executive summary of sales performance while allowing for deep dives into regional and product-level efficiency.

## 🗃️ Dataset
The data used in this analysis is sourced from the **Walmart Sales** dataset on Kaggle.
"https://www.kaggle.com/datasets/vivek468/superstore-dataset-final"

## 🛠️ Tools Used: 
Power BI, DAX, Power Query

## 🛠️ Technical Skills Demonstrated
1. Advanced DAX (Time Intelligence)
I implemented custom measures to track Year-over-Year (YoY) performance.
dax
// Example: Calculating Profit Margin for the previous year
Profit Margin LY = 
CALCULATE(
    [Profit Margin %], 
    SAMEPERIODLASTYEAR('Date'[Order Date])
)
2. Data Visualization Best Practices
KPI Visuals: Used to provide immediate context on performance vs. targets.
Scatter Charts: Employed for "Product Efficiency" to identify outliers and low-margin products.
Geospatial Analysis: Used a Map visual to identify regional sales distribution.

## 💡 Key Business Insights
Revenue Growth: Total Sales reached $499.40K, representing a +9.83% growth compared to the previous year.
Profitability Warning: Despite sales growth, overall Profit Margin declined by -10.5%, ending at 10.35%.
Underperforming Categories: The Tables sub-category is the most significant "profit bleeder," showing a net loss of nearly $20K despite high sales volume.
Regional Strength: The West region leads in both sales and profit margin, while the Central region shows high volatility in product efficiency.

## 📂 How to View
1. Download the 'Superstore_Performance.pbix' file from this repository.
2. Open in Power BI Desktop.
3. Interact with the Year Slicer at the top to see how metrics shift over time
