# Instacart Grocery Shopping Behavior & Retail Analytics

An interactive grocery analytics dashboard built using **Microsoft Excel, Power Query, Power Pivot, and DAX** to analyze customer purchasing behavior, product demand, repeat-purchase patterns, and ordering trends across **33.8 million+ order-product records**.

## 📌 Project Overview

Online grocery platforms generate millions of transactions, making it challenging to identify purchasing patterns, understand repeat-purchase behavior, and plan for changing customer demand.

This project analyzes the Instacart Market Basket Analysis dataset to uncover patterns in product performance, customer order frequency, reorder behavior, and ordering times. An interactive Excel dashboard presents these findings and translates them into potential business actions.

## 🎯 Business Problem

The platform needs a consolidated view of customer shopping behavior and product performance to answer five key questions:

1. **Customer Behavior:** How frequently do customers place orders, and how are they distributed across order-frequency segments?
2. **Product Performance:** Which products and departments account for the highest purchase volumes?
3. **Repeat Purchasing:** Which departments demonstrate the strongest reorder behavior?
4. **Ordering Trends:** Which days and times experience the highest order volumes?
5. **Basket Behavior:** How many products are typically purchased per order, and what additional basket-level patterns can be explored?

## 📂 Dataset

* **Source:** [Instacart Market Basket Analysis Dataset](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset)
* **Scale:** 33.8M+ order-product records
* **Data Format:** CSV files
* **Core Data:** Orders, customers, products, reorder indicators, ordering timestamps, aisles, and departments.

The dataset includes order history and product-level purchasing information. It does not provide actual product prices, revenue, profit, or inventory levels.

## 🛠️ Tools & Technologies

* **Microsoft Excel 2019** — Dashboard development and reporting
* **Power Query** — Data cleaning, transformation, and preparation
* **Power Pivot** — Data modeling and relationship management
* **DAX** — Calculated measures and customer segmentation
* **PivotTables & PivotCharts** — Data aggregation and visualization
* **Excel Slicers** — Interactive filtering and exploration

## 🔄 Data Preparation & Modeling

Power Query was used to clean, transform, and prepare the source tables for analysis. The dataset was organized into a relational Data Model to support analysis across multiple tables.

### Data Model Components

* **Fact_OrderProducts:** Product-level order records, including product IDs, cart position, and reorder indicators.
* **Dim_Order:** Order details, customer IDs, order numbers, day of week, and hour of day.
* **Dim_Product:** Product names, aisle information, and department classifications.
* **Dim_Customer:** Unique customer IDs and derived order-frequency segments.

Relationships were established between the fact table and relevant dimensions to support cross-table analysis.

## 📊 Dashboard Features & KPIs

The interactive dashboard includes the following KPIs and visualizations:

### Key Performance Indicators (KPIs)

* **Total Orders:** Overall number of orders.
* **Total Customers:** Unique customers represented in the dataset.
* **Order-Product Records:** Total product-level records.
* **Average Basket Size:** Average number of products per order.
* **Reorder Rate:** Percentage of product records marked as reorders.

### Visualizations

* **Orders by Time of Day:** Compares ordering activity across different time periods.
* **Orders by Day of Week:** Identifies high- and low-demand days.
* **Department-Wise Purchase Volume:** Compares product demand across departments.
* **Top Products by Purchase Volume:** Ranks frequently purchased products.
* **Customer Order-Frequency Segments:** Shows the distribution of customers by their total order counts.
* **Top 5 Departments by Reorder Rate:** Identifies departments with stronger repeat-purchase behavior.

Interactive slicers enable users to explore the data across selected dimensions.

## 💡 Key Business Insights & Potential Actions

The analysis supports several business opportunities:

* **Demand Planning:** Align operational capacity with high-volume ordering days and periods.
* **Repeat-Purchase Opportunities:** Test personalized replenishment recommendations for departments with high reorder rates.
* **Product Prioritization:** Use high-volume products to guide demand planning and product recommendations.
* **Customer Engagement:** Explore targeted recommendations for different customer order-frequency segments.
* **Merchandising Strategy:** Compare department purchase volumes with reorder rates to distinguish demand scale from repeat-purchase behavior.

*These are proposed actions based on observed purchasing patterns, not proven improvements in sales or profitability.*

## 📚 Key Learnings

* Processed and analyzed a dataset containing more than 33 million records using Excel's analytical tools.
* Transformed and combined multiple datasets using Power Query.
* Designed a relational Data Model using Power Pivot.
* Created DAX measures for business metrics and customer segmentation.
* Built an interactive dashboard using PivotTables, PivotCharts, and slicers.
* Translated analytical findings into practical business recommendations.

## ⚠️ Project Limitations

* The dataset does not contain prices, revenue, profit, or inventory availability; therefore, financial performance and stockout analysis are outside the project's scope.
* Reorder behavior is measured using the dataset's reorder indicator and does not independently prove customer loyalty or retention.
* Product co-purchase analysis and cart-position analysis require additional analysis beyond the current dashboard.
* Recommended business actions would need further testing to establish their actual impact.

## 🏆 Project Outcome

Developed an interactive Excel dashboard that consolidates large-scale grocery transaction data into a structured analytical model, enabling exploration of product demand, repeat-purchase behavior, customer order frequency, and ordering-time trends.

The project demonstrates an end-to-end analytical workflow covering **data preparation, data modeling, DAX calculations, visualization, and business-oriented analysis** using Microsoft Excel.

## 👩‍💻 Author

**Sneha Vanjare**

* **GitHub:** [Sneha Vanjare](https://github.com/snehavanjare2705-art)

---

**Tools:** Microsoft Excel 2019 | Power Query | Power Pivot | DAX | Data Modeling | Business Analytics
