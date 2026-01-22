# 📊 Flipkart Product Analysis and Insights

## Tools: Power BI | Excel | DAX | Power Query
### Domain: E-commerce | Retail Analytics

--------------------------------------------------------

### 🧩 Project Overview

This project analyzes the Flipkart product dataset, focusing on product performance, seller insights, and customer behavior. Using Excel for data cleaning and Power BI for visualization, the goal is to uncover trends and patterns in the e-commerce market.

--------------------------------------------------------

### 🎯 Project Objectives

* Analyze Product Performance: Study trends in product sales, ratings, and reviews across categories.
* Evaluate Seller Performance: Assess seller ratings, product offerings, and customer engagement.
* Understand Customer Behavior: Identify patterns in customer ratings, returns, and product preferences.
* Visualize Key Metrics: Create interactive dashboards to showcase product insights and seller performance.

--------------------------------------------------------

### 📂 Data Sources

* Flipkart Retail Product Dataset (Kaggle)
* https://www.kaggle.com/datasets/rohiteng/flipkart-retail-product-dataset/data

--------------------------------------------------------

### ❓ Problem Statement

Analyze product performance and seller metrics to identify top-performing products and sellers. Study customer behavior and preferences across product categories. Evaluate factors influencing product ratings and reviews.

--------------------------------------------------------

### 🧾 Attribute Details

| Attribute Name | Data Type | Description |
| --- | --- | --- |
| Product_Id | Text | Unique product identifier |
| Product_Name | Text | Product name |
| Category | Text | Product category |
| Brand | Text | Product brand |
| Seller | Text | Seller name |
| Seller_City | Text | Seller location |
| Price | Currency | Product price |
| Discount_Percent | Number | Discount percentage |
| Final_Price | Currency | Price after discount |
| Rating | Number | Product rating |
| Review_Count | Number | Number of reviews |
| Stock_Available | Number | Available stock |
| Units_Sold | Number | Number of units sold |
| Listing_Date | Date | Product listing date |
| Delivery_Days | Number | Delivery time in days |
| Weight_G | Number | Product weight in grams |
| Warranty_Months | Number | Warranty period |
| Color | Text | Product color |
| Size | Text | Product size |
| Return_Policy_Days | Number | Return policy duration |
| Is_Returnable | Text | Return policy status |
| Payment_Modes | Text | Available payment modes |
| Shipping_Weight_G | Number | Shipping weight in grams |
| Product_Score | Number | Product score |
| Seller_Rating | Number | Seller rating |

--------------------------------------------------------

### 🧹 Data Preprocessing Steps

* Data Cleaning (Excel): Removed duplicates, handled missing values, standardized formats.
* Applied visual formatting using Quick Analysis tools (data bars, color scales, icon sets).
* Prepared dataset for Power BI visualization.

--------------------------------------------------------

### 📉 Analysis & Visualizations

Developed interactive Power BI dashboards addressing key business questions using:

* Dashboard 1: Sales Performance
	+ Cards: Total Sales, Total Units Sold, YTD Sales, Best Selling Product
	+ Map: City-wise sales performance
	+ Line and Stacked column chart: Top 10 Products by Sales & Revenue
	+ Tree map: Total Units Sold by Category
	+ Multirow card: Max and Min Price by Brand
	+ Funnel Chart: Top Sellers Performance
	+ Donut Chart: Category-wise Unit Sales
	+ Line Chart: Revenue Trend Over Time
	+ Slicers: Brand, Category
	+ Buttons: Navigate to Dashboard 2

<img width="1486" height="835" alt="image" src="https://github.com/user-attachments/assets/aac50b71-662d-46e6-88c7-535f8e996ba7" />


* Dashboard 2: Returns and Warranty
	+ Cards: Average Return Policy Days, Average Warranty Months, Avg Rating
	+ Slicers: Brand, Category
	+ Buttons: Navigate to Dashboard 1
	+ Pie Chart: Popular Payment Methods, Returnability by Category
	+ Line chart: Returnability and Warranty Coverage
	+ Funnel Chart: Seller Return Policy Funnel
	+ Scatter plot: Product Performance: Rating vs Return Policy
	+ Line and column chart: Return Policy Trends by Category

<img width="1486" height="836" alt="image" src="https://github.com/user-attachments/assets/8aa9d3b5-efb1-4c82-9166-ebd16199e65f" />


--------------------------------------------------------

### 📈 Performance Insights

* Top performer: Philips Ultra 865 is the best-selling product, driving strong sales (Card visual)
* Top categories drive sales: Fashion (15.1%) and Appliances (14.8%) are among the top contributors (Tree map)
* City-wise sales vary: Top cities like Mumbai (15.5%), Hyderabad (13.3%), and Delhi (13.0%) drive sales, while smaller cities show growth potential (Map)
* Top sellers perform well: Sellers like UrbanRetails, QuickShop, and SmartDeals dominate sales, with ~41.3% combined market share (Funnel Chart)
* Revenue trends show growth: Revenue grew ~20% YoY in 2022, with Q4 (Dec) showing peak sales (~50% of yearly sales) (Line Chart)
* Return policies impact sales: Fashion products with longer return policies (high avg return days) have high ratings and sales (Scatter plot, Dashboard 2)
* Returnability by category: Categories with return policies (like Fashion) drive ~78% of sales (Pie chart)

--------------------------------------------------------

### 🧠 Conclusion

The analysis of Flipkart's sales data (using Excel and Power BI) reveals key drivers of performance. Key findings include:

* Philips Ultra 865 is the top-selling product
* Fashion and Appliances drive sales
* Mumbai, Hyderabad, and Delhi are top cities
* Return policies boost sales in categories like Fashion
This project transformed sales data into clear, actionable insights on product, city, and category performance.

--------------------------------------------------------

### 👩‍💻 Author

Padmaja K
Data Analyst | Power BI Developer

* 🌐 GitHub: https://github.com/padmaja1990
* 💼 LinkedIn: linkedin.com/in/padmajak1990
* 📧 Email: padmaja.nathan@gmail.com


If you found this project useful or have feedback, feel free to reach out!

--------------------------------------------------------

### 📚 Tags
#PowerBI #DataAnalysis #Ecommerce #RetailAnalytics #DAX #DataVisualization #ExcelPowerQuery
