# Excel-Finance-Analysis-and-Dashboard-Project

# 📊 Finance Dashboard | Excel Project

An interactive Excel dashboard built to analyse sales data and turn raw finance figures into clear, actionable insights. It combines KPI cards, five linked charts, and slicers so the data can be explored by weekday, product, and price bucket.

## 🎯 Objective
To analyse the provided finance/sales dataset and present the results in a single, easy-to-read dashboard that helps answer:
- How much are we selling, and on which days do sales peak?
- Which price buckets and products drive the most revenue?
- How much do actual sales differ from sales rounded to the nearest ₹5?

## 📌 Key Metrics (KPIs)
| Metric | Value |
|---|---|
| Total Sales | ₹4,38,968 |
| Average Sale Value | ₹553 |
| Number of Products | 6 |
| Rounded Sales Variance | ₹103 |

## 📈 Dashboard Visuals
1. **Daily Sales: Total vs Average**: combo chart comparing total and average sales for each weekday.
2. **Actual Sales vs Rounded Sales (Nearest ₹5)**: shows the effect of rounding across price buckets.
3. **Sales Amount by Price Bucket**: revenue split across Below 300, 300-500, 500-700, and 700 Above.
4. **Products Sold by Price Bucket**: number of items sold in each price range.
5. **Product Sales Value vs Average Price**: total sales and average price for each Product ID (PIZB0001 to PIZB0006).

**Interactive slicers** for *Weekday* and *Product ID* update all charts and KPIs instantly.

## 🔍 Key Insights
- **Wednesday** is the strongest day (₹72,989 total, ₹570 average), while **Saturday** is the weakest (₹56,301 total, ₹526 average).
- The **700 Above** bucket brings in the most revenue (₹1,85,471, about 42% of total sales).
- **300-500** sells the most units (234), but contributes far less revenue than 700 Above.
- **Below 300** is the smallest segment, with 107 units and about 6% of revenue.
- **PIZB0001 to PIZB0004** each contribute roughly ₹94K to ₹96K in sales, while **PIZB0005** has the highest average price (₹584) but much lower total sales.
- **PIZB0006** has the lowest average price (₹504) and the lowest total sales (₹17,135).
- Rounding sales to the nearest ₹5 has a very small impact, with a total variance of only ₹103.

## 🛠️ Tools & Techniques
- **Microsoft Excel**
- Pivot Tables & Pivot Charts
- Slicers for interactive filtering
- Combo charts (column + line, dual axis)
- Formulas for rounding logic (`MROUND`) and variance calculation (`ABS`)
- Data cleaning, calculated fields, and dashboard layout design

## 💡 Skills Demonstrated
Data analysis · Data visualisation · Dashboard design · KPI reporting · Business insight generation

## 🎯 Purpose

The purpose of this project is to turn raw finance and sales data into a clear, interactive dashboard that supports quick, data-driven decisions. Instead of scanning rows of numbers, a viewer can see at a glance how the business is performing, which days, products, and price ranges drive revenue, and where sales are underperforming.

The project also served as hands-on practice in the full Excel analytics workflow: cleaning data, building pivot tables and charts, defining KPIs, and designing a dashboard that is easy for non-technical users to read and explore.
