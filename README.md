DATASET OVERVIEW
Dataset Name: Superstore Sales Dataset
Dataset Type: sales/e-commerce

This project is a comprehensive analysis of "Superstore" sales data from https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting
using **Power BI** and **Excel**.
The main objective is to build an interactive dashboard that tracks sales performance, customer behavior, and product efficiency.

the data includes: (Order id ,Order Date ,Ship Date ,Ship Mode ,Customer ID ,Customer Name ,Segment ,Country ,City, State, Postal Code, Region, Product ID,
Category, Sub-Category, Product Name, Sales)
The data consists of 9801 rows and was used to analyze sales patterns.


  ### Tools and Techniques Used:

***Excel:For cleaning and preparing raw data.
  
***Power BI Desktop: For building reports and dashboards.

***DAX Formulas:For performing complex calculations and metrics.


  ### Advanced Analytical Metrics (Key Measures) 
_______________________________________________________
Custom DAX metrics are built to ensure the accuracy of the analysis:

***YoY Sales Growth:** Compare sales year-over-year to identify growth trends.

***Avg. Order Value (AOV):** Measure the average size of a customer's shopping basket.

***Avg. Unit Price:** Determine the average price per unit to evaluate pricing policies.

***Product Variety Growth:** Track the product variety sold year-over-year.

### Data Cleaning and processing:
_____________________________________
To ensure maximum accuracy and system performance, the following data engineering steps were performed:

***Performance Optimization:** 
Dropped the `Row ID` column to reduce model size and improve processing speed, as it provided no analytical value for the dashboard.
***Handling Mixed Data Types:** 
Identified and resolved issues in the Date columns where entries were inconsistently stored as both Text and Date formats. Unified the entire column into a standard Date format to enable Time Intelligence functions.
***Missing Data Imputation:** 
Conducted research to fill gaps in the 'Postal Code' column; for instance, missing codes for cities like **Vermont** were manually identified and integrated to ensure accurate geographical mapping[.
***Geographical Standardization:**
Audited City and State names to ensure consistency, preventing fragmentation in the "Sales by State" visuals.
***Shipping Efficiency:**
 Created a calculated column for Processing Days (Ship Date - Order Date).(in Power BI)


### Key Business Insights:
____________________________

Based on the interactive analysis, the following strategic insights were identified:

### 1. Customer Segmentation & Dominance
***The Consumer Powerhouse:**
 The "Consumer" segment is the primary revenue driver, accounting for **52.05%** of the total customer base and the highest sales volume. Strengthening loyalty programs in this segment is crucial for sustained growth.
***Top Customer Value:** 
A small group of elite customers (e.g., Sean Miller with over $25K in sales) contributes significantly to the revenue, highlighting the importance of VIP retention strategies.
***The Growth Gap:**
 While Transaction Growth soared by 49.8%, Customer Growth remained at 1.4%. This highlights a strong Customer Retention model where existing customers are buying more frequently,
 suggesting that the next strategic move should focus on new customer acquisition campaigns.

### 2. Product & Category Performance
* **High-Value Technology:**
 The **Technology** category leads in sales (**36.59%**), indicating high unit prices and strong market demand.
* **Inventory Optimization:** 
"Phones" and "Chairs" are the top-selling sub-categories. Conversely, the **"Bottom 5 Products"** analysis identifies items with near-zero sales (e.g., Eureka Disposable), providing a clear opportunity to liquidate underperforming inventory and reduce holding costs.

### 3. Growth & Operational Efficiency
* **Explosive Growth:**
 The business achieved a remarkable 46.90% Cumulative Sales Growth over the 4-year period (2015-2018), accompanied by a 49.8% increase in total transactions, signaling a strong and steady market expansion.

***The Growth Gap;**
: While total transactions nearly doubled over 4 years, New Customer Growth stood at only 1.4%. This indicates that the revenue surge is primarily driven by high loyalty and repeat purchases from the existing customer base rather than the acquisition of new clients.
The average **Processing Time is 4.0 days**, with **Standard Class** being the preferred shipping mode (**59.29%**). Improving logistics to reduce processing time could further boost the **1.4% Customer Growth rate**.

### 4. Geographical Trends
* **Regional Strongholds:** 
The **West Region** leads in total sales. However, the "Sales and Average Order Value by City" scatter plot reveals that high sales volume does not always correlate with high AOV, suggesting a need for price-optimization in high-volume cities like New York and Los Angeles.
***AOV Optimization in High-Volume Hubs:**
 The scatter plot analysis for New York and Los Angeles shows high sales volume but moderate Average Order Value (AOV). This indicates a massive opportunity to implement "Product Bundling" or "Upselling" strategies in these specific cities to increase the revenue per basket


###Lesson Learned: The Power of Raw Data:
________________________________________________ 

"During the transformation process, I learned the importance of maintaining a Raw Data Backup. 
A formatting error occurred during the Excel cleaning phase, but by having the original CSV as a Source , I was able to perform a Root Cause Analysis, identify the discrepancy, and roll back to the correct data state."


### Let's Connect!
***LinkedIn:** [https://www.linkedin.com/in/saiftarek2/]
***Email:** [saaiftarek666@gmail.com


















