# Revenue-Growth-Drivers-and-Category-Investment-Decision-
Data-driven analysis of product categories to identify revenue growth drivers and guide investment decisions based on revenue, growth momentum, and risk.

## Problem Statement
The goal of this analysis is to determine **which product category the company should invest in next quarter** based on revenue trends, month-over-month (MoM) growth, volatility, and overall trend direction. This helps the Head of Sales make **data-driven investment decisions**.

---

## Dataset
The analysis uses a dataset of **superstore sales** containing **23 months of revenue data** for three product categories:

- **Furniture**  
- **Office Supplies**  
- **Technology**

**Columns include:**
- `Order Date` – Month of sale  
- `Category` – Product category  
- `Revenue` – Monthly revenue  
- MoM % growth (calculated for analysis)  

> Full dataset: `superstore_sales_project1.csv` in the `data/` folder.

---

## Metrics / Analysis Plan
To assess category performance, the following metrics were calculated:

1. **Average Monthly Revenue** – Measures the size/scale of each category.  
2. **Month-over-Month (MoM) Growth %** – Measures momentum and whether revenue is growing.  
3. **MoM Volatility (Standard Deviation)** – Measures risk and predictability of growth.  
4. **Trend Direction** – Compares early vs recent MoM averages to see if growth is improving or declining.

These metrics allow a **balanced assessment** of both revenue potential and investment risk.

---

## Calculations / Steps
1. **Average Monthly Revenue** – Calculated per category:  

| Category         | Avg Monthly Revenue |
|-----------------|-------------------|
| Furniture        | 15,124            |
| Office Supplies  | 20,284            |
| Technology       | 14,829            |

2. **Average MoM Growth %** – Calculated using the MoM % column:  

| Category         | Avg MoM % |
|-----------------|-----------|
| Furniture        | 4%        |
| Office Supplies  | 3%        |
| Technology       | 3%        |

3. **MoM Volatility** – Standard deviation of MoM %:  

| Category         | Volatility |
|-----------------|------------|
| Furniture        | 24%        |
| Office Supplies  | 17%        |
| Technology       | 24%        |

4. **Trend Direction** – Compare early (first 6 months) vs recent (last 6 months) MoM averages:

| Category         | Early Avg | Recent Avg | Trend      |
|-----------------|-----------|-----------|-----------|
| Furniture        | 8%        | 1%        | Declining |
| Office Supplies  | 4%        | 1%        | Declining |
| Technology       | 0%        | -1%       | Declining |

---

## Findings / Insights
- **Office Supplies**: Largest revenue and **lowest volatility**, making it the most stable and impactful category.  
- **Furniture**: Higher average growth but **highly volatile**; growth momentum is declining → should be monitored.  
- **Technology**: Low revenue, moderate growth, high volatility, and declining trend → underperforming and unsuitable for investment.  

---

## Decision / Recommendation

| Category         | Investment Decision | Reasoning |
|-----------------|-------------------|-----------|
| Office Supplies  | Invest            | Large revenue + stable growth → safest and most impactful investment |
| Furniture        | Monitor           | Higher growth but high volatility → potential but risky |
| Technology       | Do Not Invest     | Low revenue + declining trend → not worth investment |

---

## Tools Used / Skills Demonstrated
- **Excel** – Data cleaning, MoM calculations, volatility, trend analysis  
- **Data Analysis Skills** – Business insights, decision-making, risk evaluation  

---
## Summary Table

| Category         | Avg Monthly Revenue | Avg MoM Growth % | MoM Volatility | Trend       | Investment Decision |
|-----------------|-------------------|-----------------|----------------|------------|-------------------|
| Office Supplies  | 20,284            | 3%              | 17%            | Declining  | Invest            |
| Furniture        | 15,124            | 4%              | 24%            | Declining  | Monitor           |
| Technology       | 14,829            | 3%              | 24%            | Declining  | Do Not Invest     |

---

## Business Impact
Based on revenue scale, average growth, volatility, and trend direction: Office Supplies is the strongest candidate for investment due to its high revenue and stable performance. Furniture shows higher average growth but is too volatile and medium-sized, so it should be monitored. Technology is underperforming in both revenue and growth, making it unsuitable for investment.

---


