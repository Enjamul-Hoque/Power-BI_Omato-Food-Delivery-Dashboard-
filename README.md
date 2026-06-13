# Omato-Food-Delivery-Dashboard-

## Business Problem

A retail company wanted to analyze sales performance, profitability, regional contribution, product performance, and store-type contribution to identify growth opportunities and improve profitability.

## Tools Used

* Power BI
* Power Query
* Excel

## DAX Measures Used

* Total Sales = SUM(Fact_Sales[GrossSales])
* Total Quantity = SUM(Fact_Sales[Quantity])
* Profit = SUM(Fact_Sales[Profit])
* Profit Margin = DIVIDE([Profit],[Total Sales],0)
* Sales LY = CALCULATE([Total Sales], SAMEPERIODLASTYEAR('Calendar Table'[Date].[Date]))

## KPIs

* Total Sales = 1.22B
* Total Quantity = 82K
* Profit = 226M
* Profit Margin = 18.56%

## Key Insights

* Online stores generated 38.55% of total sales.
* South region contributed the highest share of sales.
* Several products consistently outperformed others across years.
* Profitability remained positive across most periods.

## Recommendations

* Increase investment in online sales channels.
* Focus marketing efforts on high-performing regions.
* Improve inventory planning for top-selling products.
* Monitor low-performing regions and categories.

## Dashboard Preview

<img src="https://github.com/Enjamul-Hoque/Power-BI-Sales-Dashboard/blob/5f0e5d11e812564091a009690022c4b37fcd81b7/Power%20BI%20Retail%20Sales%20Dashboard%20Screenshort.png" alt="Image Description" width="600">


<img src="https://github.com/Enjamul-Hoque/Power-BI_Omato-Food-Delivery-Dashboard-/blob/92cdea90f16fa29c7dce168e60b286aa1945deb0/Omato%20_%20food_dashbord%20sreenshort.png" width="600">

<br>
Different desing dashboard
<img src="https://github.com/Enjamul-Hoque/Power-BI_Omato-Food-Delivery-Dashboard-/blob/92cdea90f16fa29c7dce168e60b286aa1945deb0/Omat%20Dashboard%20Different%20Desing.png" width="600">

