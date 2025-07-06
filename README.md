PROJECT 1
# Amazon-products-DSA-project-

🛍️ Amazon Product Review Analysis 

A detailed Excel-based analytics project on Amazon product reviews, discounts, and pricing. Developed as part of my data analysis portfolio at Madu Sound Hub, this project uses pivot tables, slicers, calculated fields, and interactive dashboards to extract actionable insights on product performance, customer engagement, and pricing strategy.

🔍 Objective: Analyze Amazon product and review data to uncover trends and business insights using Microsoft Excel.


---

🏢 Project Context
Client Name: ChiTechskill 
Industry: E-commerce Analytics
Role: Junior Data Analyst
Tools Used: Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Slicers, KPI Cards)



---
🧾 Dataset Description
Total Records: 1,465
Columns: 16
Source: Web-scraped Amazon product review data
Each row represents: A unique product
Fields included:
#.Product Name
#.Category
#.Actual Price & Discounted Price
#.Discount%
#.Rating
#.Number of Ratings
#.Review Content (Summarized)
#.Revenue Potential Fields (Derived Columns)

---

📊 Key Analytical Tasks & Solutions
#	Task Description	Excel Tools/Logic Used
1	Average discount % by product category
Pivot Table + AVERAGE
2	Number of products in each category	
Pivot Table + COUNT
3	Total number of reviews per category	
SUM of Rating Count
4	Products with highest average
ratings	Sorting by Average Rating
5	Actual vs discounted price by category
Grouped Bar Chart
6	Products with the most reviews	Top-N Sorting in Pivot
7	Products with ≥ 50% discount	
Filter + COUNTIF
8	Rating distribution	Histogram 
via Pivot Count
9	Revenue per category	New Column 
(Price × Count)
10	Products by price range	
IF Logic + Donut Chart
11	Rating vs Discount	
Dual-Axis Scatter Line Chart
12	Products with < 1,000 reviews	
COUNTIF + Bar Chart
13	Highest average discount by 
category
Sorted Pivot Table
14	Top 5 products by rating × reviews	
Ranking Logic



---

📁 Analyzed File

🔗 Click here to access the Excel file 
![117602](https://github.com/user-attachments/assets/f6327fd7-baaf-486f-ae66-509ea30e179c)
![117600](https://github.com/user-attachments/assets/9fdf4b1b-9f4b-4221-bf41-16ad13a73ca1)
![117601](https://github.com/user-attachments/assets/a2850820-428a-47f7-b3a6-31cbceff4ca9)




---

📸 Visuals & Dashboard

![117603](https://github.com/user-attachments/assets/e48ef872-60fc-4b4c-868b-0aaf7a5813b1)










---

🧠 Dashboard Highlights
Discount vs Rating: No strong correlation — price drops don’t guarantee satisfaction.
Price Buckets: Majority fall under ₹200–₹500 range.
Revenue Leaders: "Home Kitchen" and "Electronics" show top potential.
Most Reviewed: "Electronics" category leads in engagement.
Top 5 Products: High ratings + massive review counts = best performers.
Category Discounts: Health & Home items feature highest discounts.



---

🧠 Skills & Competencies Demonstrated
Skill	How I Applied It
Data Cleaning	Removed blanks, corrected formats, unified values
Data Aggregation	Used Pivot Tables to group by category and range
Excel Formulas	IF, COUNTIF, AVERAGEIFS, PROPER, etc.
Visualization	Designed charts (bar, donut, scatter, etc.)
Slicers & Cards	Built interactive filterable dashboards
Business Reasoning	Interpreted trends and explained causes/effects



---

💡 Business Insights
1. Deep Discounts Don’t Equal High Ratings — quality still matters.

2. Top Category: Electronics dominates user engagement.

3. Revenue Tip: Focus on high-rating, mid-price products.

4. Potential Fixes: Improve quality for high-review but average-rating items.
5. Power Products: Promote high-engagement items for cross-sell.




---

🔧 Tools & Environment
Microsoft Excel
Pivot Tables
Data Visualizations (Bar, Line, Donut)
Slicers
Conditional Formatting
Named Ranges

---

👨‍💻 About Me
Maduforo Chima Isaac
🎓 Data Enthusiast | 📊 Excel Analyst | Entrepreneur (Madu Sound Hub). 
I’m passionate about transforming messy data into clear, useful visuals. This project reflects my growth in Excel analysis and storytelling with data.


---


PROJECT 2

# Kultra-mega-store-inventory-analysis-DSA
- **Insight**: These customers could be targeted for upselling through tailored offers, onboarding campaigns, or customer service interventions to increase their lifetime value.

### 🔹 5. Shipping Method with the Highest Total Cost
- Shipping costs were aggregated by shipping mode.
- **Insight**: **Express Air** emerged as the most expensive shipping method. While it may offer faster delivery, its cost-effectiveness should be reassessed, especially for low-priority orders.

### 🔹 6. Most Valuable Customers & What They Buy
- Customers with the **highest total sales** were extracted along with the products they typically purchase.
- **Insight**: These high-value clients are important to retain. They often buy high-margin or frequently sold items, suggesting opportunities for bundling or loyalty incentives.

### 🔹 7. Top Small Business Customer
- The highest-spending **Small Business** customer was identified.
- **Insight**: This shows strong engagement from small business clients, warranting dedicated B2B offerings or relationship management.

### 🔹 8. Most Active Corporate Customer
- The **Corporate** customer with the **most orders** placed between 2009–2012 was extracted.
- **Insight**: Regular ordering indicates a stable B2B relationship. Consider special discounts or account-based marketing to maintain this loyalty.

### 🔹 9. Most Profitable Consumer
- The **Consumer** segment’s most profitable customer was determined using total profit generated.
- **Insight**: This customer could be studied for their purchasing habits and targeted with exclusive deals or referral programs.

### 🔹 10. Returned Orders and Segmentation
- Joined with the `Order_Status` table to identify customers who returned items.
- **Insight**: Returns came mostly from customers in a specific segment (e.g., Consumer or Small Business). This could point to issues with expectations, delivery delays, or product quality.

### 🔹 11. Are Shipping Costs Aligned with Order Priority?
- Shipping cost and mode were analyzed in relation to **Order Priority**.
- **Insight**: Some **low-priority orders were shipped using costly methods like Express Air**, which is inefficient. High-priority orders sometimes used slower shipping.
- **Recommendation**: Enforce shipping policies that align delivery method with priority:
  - **Express Air** for "Critical"/"High"
  - **Delivery Truck** for "Low" or "Not Specified"

---

## ✅ ultimate suggestion 

1. **Target low-value customers** with promotional strategies to drive revenue.
2. **Align shipping methods with order urgency** to reduce operational costs.
3. **Leverage top-performing customers and products** with loyalty incentives.
4. **Investigate reasons behind returns** in specific segments or product lines.
5. **Expand market efforts** in underperforming regions with growth potential.


---

📫 Contact
Email: chimexfur@gmail.com
Phone: +234 91 5097 2420 
GitHub:https://github.com/ChiTechskill/Amazon-products-DSA-project-.git
---



⭐ GitHub Project Tip
If this project helped or inspired you, give it a ⭐ — or fork it and make it yours!
