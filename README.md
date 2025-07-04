# Amazon-products-DSA-project-
📦 Amazon Product Analysis Using Excel

📝 Project Description

This project focuses on analyzing scraped product data from Amazon using Microsoft Excel. The analysis is designed to answer key business intelligence questions about pricing, discounts, product performance, and customer engagement using PivotTables, formulas, and visualizations.

Each product in the dataset represents a unique row, with details such as name, category, price, discount, rating, number of reviews, and customer feedback.


---

📁 Data Fields

Field Name	Description

Product Name	Name of the product
Category	Product category (e.g., Electronics, Fashion, Beauty)
Price	Original product price
Discount	Percentage discount applied (e.g., 15%)
Rating	Average customer rating (e.g., 4.5)
Rating Count	Number of customer ratings
Review Title	Title of a customer review
Review Content	Body of a customer review



---

📊 Business Questions Answered

1. What is the average discount by product category?

Tool Used: PivotTable

Analysis: Calculated the average of the Discount field grouped by Category.

Insight: Categories like Fashion tend to offer higher average discounts compared to Electronics.



---

2. How many products are listed under each category?

Tool Used: PivotTable

Analysis: Counted the number of Product Name entries per Category.

Insight: Categories such as Home & Kitchen and Fashion often have the largest number of products.



---

3. What is the total number of reviews per category?

Tool Used: PivotTable

Analysis: Summed the Rating Count by Category.

Insight: Electronics usually garners the most reviews due to high customer interest.



---

4. Which products have the highest average rating?

Tool Used: Sorting in Excel or PivotTable with Max aggregation

Analysis: Filtered to find top products with the highest Rating values.

Insight: Products rated 4.9 – 5.0 are rare and typically have strong user satisfaction.



---

5. What is the actual versus discounted price by category?

Tool Used: Calculated field in Excel and PivotTable

Fields Added:

Discounted Price = Price × (1 - Discount%)


Visualization: Clustered bar chart comparing actual and discounted average prices per category.



---

6. Which products have the highest number of reviews?

Tool Used: Sorting Rating Count in descending order

Insight: These are typically popular or viral products, often tech gadgets or fashion staples.



---

7. How many products have a 50% discount?

Tool Used: Filter or COUNTIFS

Formula: =COUNTIFS(Discount, "50%")

Insight: Helps identify deep-discount promotional products.



---

8. What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)?

Tool Used: PivotTable

Analysis: Grouped ratings (e.g., bins like 2.0–2.9, 3.0–3.9, etc.)

Visualization: Histogram chart of rating distribution.



---

9. What is the total potential revenue per category?

Formula: Potential Revenue = Price × Rating Count

Tool Used: New calculated column and PivotTable by Category

Insight: Categories like Electronics have the highest revenue potential due to high price + engagement.



---

10. What are the unique product counts per price range buckets?

Tool Used: Bucketed using Excel formulas:

=IF(Price<=10000, "Low", IF(Price<=50000, "Mid", "High"))

PivotTable: Count products in each bucket

Insight: Visualized pricing tiers (e.g., < ₦10,000, ₦10,001–₦50,000, > ₦50,000)



---

11. What is the relationship between rating and discount level?

Tool Used: Scatter Plot in Excel

X-axis: Discount (%), Y-axis: Rating

Insight: Visualizes if products with higher discounts get better or worse ratings.



---

12. How many products have fewer than 1,000 reviews?

Formula: =COUNTIFS(Rating Count, "<1000")

Insight: Indicates products with lower customer reach or new market entries.



---

🛠 Tools & Techniques Used

Tool	Purpose

Microsoft Excel	Main analysis platform
PivotTables	Aggregation and summarization
Excel Formulas	Custom calculations (e.g., revenue)
Excel Charts	Data visualization (bar, scatter, pie)
Filters/Sorting	Exploratory data analysis



---

🧮 Sample Calculated Fields

Discounted Price = Price * (1 - Discount%)
Potential Revenue = Price * Rating Count
Price Range = IF(Price<=10000, "Low", IF(Price<=50000, "Mid", "High"))


---

📂 File Format

amazon_products.csv – Cleaned dataset

amazon_analysis.xlsx – PivotTables, charts, calculations

README.md – Project documentation (this file)



---

🎯 Project Outcomes

Provided actionable insights for pricing and discounting strategies

Identified top-rated and most reviewed products

Discovered hidden patterns between rating, pricing, and customer engagement
