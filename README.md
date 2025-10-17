# Supply Chain & Operations Analytics Dashboard (Power BI)

## 📊 Project Overview
This Power BI dashboard provides an analytical view of supply chain and operations performance. It tracks key business metrics such as sales, profit, shipping efficiency, and year-over-year growth.

## 🧠 Key Insights
- Total Sales, Profit, and Profit Margin
- Year-over-Year (YoY) Growth Analysis
- Regional and Segment Performance
- Average Shipping Days and Delivery Mode Insights

## ⚙️ Tools & Technologies
- Microsoft Power BI
- DAX (Data Analysis Expressions)
- Data Modeling and Relationships
- Excel/CSV Dataset

## 📈 Dashboard Preview

<img width="927" height="507" alt="Screenshot 2025-10-17 113156" src="https://github.com/user-attachments/assets/3698a882-c8e2-4185-816a-6451b2095eb9" />

## 🪄 Key DAX Measures
- Total Sales = SUM(Orders[Sales])
- Total Profit = SUM(Orders[Profit])
- Profit Margin = DIVIDE([Total Profit], [Total Sales])
- Avg Shipping Days = AVERAGE(Orders[Shipping_Days])
- YoY Growth % = DIVIDE([Total Sales] - [Sales LY], [Sales LY])

## 🚀 How to Use
1. Download the `.pbix` file.
2. Open it in Power BI Desktop.
3. Explore filters and slicers for insights.

## 👩‍💻 Author
Reshika Miriyala  
📫 LinkedIn Profile : https://www.linkedin.com/in/reshika-miriyala/
