# Blinkit Sales Dashboard (Power BI)

Step 1. Project Title
Blinkit Sales & Regional Performance Dashboard

2. Short Description / Purpose
A Power BI dashboard built for Blinkit to analyze "sales performance across outlets, regions, and product categories". It provides a centralized view of KPIs such as total sales, outlet establishment performance, item attributes (e.g., fat content), and category trends — enabling better business decisions.

3. Tech Stack
Power BI Desktop** (dashboard & reporting)
Power Query (M Language) (ETL: cleaning & shaping data)
DAX (measures and calculated columns)
CSV/Excel (sales & product data sources)
Git & Git LFS (version control for `.pbix` file)

4. Data Source
Origin: Sales dataset simulating Blinkit’s outlet performance.  
Grain: Sales records aggregated at "Outlet x Item x Year".  
Tables (Star Schema):  
FactSales: Transaction-level sales (`SalesAmount`, `Units`, `Ratings`)  
DimOutlet: Outlet details (`Outlet_ID`, `Tier`, `Size`, `EstablishmentYear`)  
DimItem: Product details (`Item_ID`, `ItemType`, `FatContent`)  
DimDate: Calendar mapping (`Year`, `Quarter`, `Month`)  

5. Features / Highlights

a) Business Problem
Blinkit’s management needed insights into outlet-wise sales performance, category mix, and item attributes. Without a single view, tracking "trends across tiers, outlet establishment age, and customer preferences" was challenging.

b) Goal of the Dashboard
Track "Total Sales, Average Sales, Ratings, and Item Counts".  
Compare outlet performance by "Tier, Size, and Establishment Year.  
Assess "item attributes" like Fat Content and Item Type.  
Highlight top-performing categories and growth trends.  

c) Walk-Through of Key Visuals
KPI Cards:  
$67.3K 'Total Sales'  
2K 'Average Sales' 
32 'Items'  
2.9 "Average Rating"  
"Outlet Establishment Line Chart": Sales trend over time with peaks in 2015 ($9.1K) and 2021 ($7.7K).  
"Outlet Size Donut": Sales contribution by outlet type (e.g., Grocery Store $23.1K).  
"Fat Content Breakdown": Sales split between "Low Fat" and "Regular" products.  
"Item Type Bar Chart": Frozen Foods, Soft Drinks, Baking Goods among top sellers.  
"Tier Analysis Table": Tier 3 with $67.3K sales across 32 items.  

d) Business Impact & Insights
"Tier 3 outlets" lead with "$67.3K" in sales and steady growth.  
"Category insights": Frozen Foods and Beverages drive revenue, guiding promotional focus.  
"Outlet maturity analysis": Recently established outlets show growth spurts, highlighting expansion opportunities.  
"Product attribute patterns": Balanced demand between "Low Fat vs. Regular" categories supports targeted marketing.  

# Blinkit Sales Snapshort 
link![[Blinkit Sales Dashboard](https://github.com/golukumar63/Blinkit-Sales-Dashboard-/blob/main/Blinkit%20Sales%20Snapshort%20.png)

