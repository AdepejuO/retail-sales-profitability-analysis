# Retail Sales \& Profitability Analysis

**ADIDAS RETAIL DATASET  |  EXCEL ANALYTICS \& DASHBOARD REPORTING**

A retail performance analysis using Excel to compare sales, product profitability, regional performance, retailer contributions and sales channels.

## 📊1.  Project at a glance

|Area|Project overview|
|-|-|
|Business focus|Sales performance, operating profitability, product mix, retailer contribution, regional results and channel demand|
|Tools|Microsoft Excel: structured source data, PivotTables, PivotCharts and dashboard reporting|
|Data structure|9,648 sales records; retailer, invoice date, region, state, city, product, unit price, units sold, total sales, operating profit, operating margin and sales method|
|Analysis period|2020–2021|
|Key metrics|Total sales, operating profit, units sold, operating profit margin, sales share and regional/product contribution|
|Currency|The workbook does not identify a currency; financial values are therefore shown without a currency symbol|
|Output|Excel dashboard with seven charts and supporting PivotTable summaries|

## 🎯2.  Business Context \& Core Questions

This project consolidates transactional data into clear summary measures and visual reports, enabling commercial teams to isolate key revenue drivers and identify margin pressures.



* Which retailers contribute the most sales and profit?
* Which product categories generate the greatest revenue and operating profit?
* How does performance vary across geographical regions and cities?
* How do in-store, outlet and online sales compare by units sold?
* Where do revenue and operating profit tell different stories?
* What findings should inform product, retailer and regional performance reviews?

## 📈3.  Measures and KPIs

|Measure|Definition and purpose|
|-|-|
|Total sales|SUM of recorded Total Sales; primary revenue measure.|
|Units sold|SUM of Units Sold; sales volume, not the number of transactions.|
|Operating profit|SUM of recorded Operating Profit; absolute contribution to operating performance.|
|Weighted operating margin|Total Operating Profit ÷ Total Sales × 100; appropriate for aggregated profitability.|
|Sales share|Category or retailer sales ÷ overall sales × 100; concentration and mix.|
|Average transaction margin|AVERAGE of individual Operating Margin values; separate descriptive measure that should not replace weighted margin.|

## 🛠️4.  Data preparation and analysis approach

The source table was organised by retailer, invoice date, geography, product, pricing, volume, revenue, profit and sales method. The analysis used Excel PivotTables to summarise the same measures across different business dimensions, with the dashboard drawing on these summaries.

|Step|Excel method and analytical purpose|
|-|-|
|Inspect the source|Check column headings, field types and the invoice-date range; keep the source data at transaction-row level.|
|Check data completeness|Review blanks, duplicate rows, zero-sales records and consistency between recorded sales, units and unit prices.|
|Aggregate measures|Use PivotTable SUM for sales, units and operating profit; group by retailer, product, region, city and sales method.|
|Compare performance|Calculate relative sales share and weighted operating margin for meaningful comparisons between groups.|
|Build the dashboard|Link PivotCharts to reporting tables, allowing the same measures to be reviewed across complementary business dimensions.|

## 🏪5.  Quality assurance and validation

Data-quality checks were considered at both source-record and reporting levels. Data-quality checks included reviewing the completeness and consistency of sales, units sold and operating profit records. A reconciliation check identified differences between recorded sales and values calculated from unit prices and quantities in some source records. The analysis used the supplied Total Sales and Operating Profit fields as the reporting measures, to maintain consistency across the PivotTables and dashboard. The discrepancy has been identified for source-level validation, while the analysis remained focused on sales performance, product profitability and regional comparisons within the supplied dataset.

### Validation checks evidenced by the analysis

|Check|Excel method|Result|
|-|-|-|
|Completeness|Count populated records; inspect core fields for blanks using filters or COUNTBLANK|The review covers 9,648 records and reports no blanks in core data fields.|
|Uniqueness|Review exact duplicates using COUNTIFS across the relevant identifiers / fields; confirm the intended sales-record grain.|No duplicates|
|Numerical validity|COUNTIF / COUNTIFS for negatives and zeros; check profit and margin boundaries and outliers.||
|Dates and categories: period and labels are consistent|MIN / MAX invoice dates; inspect blanks, spelling variations and unexpected retailers, products, regions or sales methods.|Date range was between 2020 to 2021|
|Sales and profit control totals|Reconcile SUM of source Total Sales, Units Sold and Operating Profit against PivotTable grand totals.|Portfolio reports 899.9m sales, 2,478,861 units and 332.1m operating profit. A dated signed-off reconciliation sheet is not included.|
|Unit price versus sales|Compare recorded Total Sales with Price per Unit × Units Sold using an absolute difference and an exception flag.|The source review identified systematic differences. They are source-quality exceptions, not confirmed errors in the PivotTable aggregation.|

## 🖥️6.  Dashboard and visualisation design

|Dashboard visual|Why this is useful|
|-|-|
|Sales by retailer – bar chart|Ranks retailers clearly and allows comparisons without relying on pie-slice estimates.|
|Units sold by sales method – pie chart|Shows the relative contribution of three channels to total unit volume; a bar chart is also suitable for precise comparison.|
|Top five cities – bar chart|Focuses attention on the leading city-level sales contributors.|
|Sales by retailer and product – clustered bar chart|Shows how product mix and revenue vary across retailers.|
|Retailer performance – sales and profit comparison|Pairs revenue and profit to distinguish scale from financial return.|
|Operating profit by region – line chart|Displays differences across regions; a bar chart would be more appropriate for discrete geographical categories.|
|Profit and average margin by product – combination chart|Pairs the absolute profit contribution with a percentage; weighted margin would be preferable for a product-level performance KPI.|

## 🔍7.  Performance findings

### 🗺️Regional sales contribution

|Region|Recorded sales (millions; source currency not stated)|
|-|-|
|West|269.9|
|Northeast|186.3|
|Southeast|163.2|
|South|144.7|
|Midwest|135.8|

*(Visual chart in source document: Horizontal bar chart showing Recorded sales (millions; source currency not stated) across West (\~270), Northeast (\~186), Southeast (\~163), South (\~145), and Midwest (\~136)).*

### 👟Operating profit by product

|Product|Operating profit (millions; source currency not stated)|
|-|-|
|Men's Street Footwear|82.8|
|Women's Apparel|68.7|
|Men's Athletic Footwear|51.8|
|Women's Street Footwear|45.1|
|Men's Apparel|44.8|
|Women's Athletic Footwear|39.0|

*(Visual chart in source document: Horizontal bar chart showing Operating profit (millions; source currency not stated) across Men's Street Footwear (\~82.8), Women's Apparel (\~68.7), Men's Athletic Footwear (\~51.8), Women's Street Footwear (\~45.1), Men's Apparel (\~44.8), and Women's Athletic Footwear (\~39.0)).*

* **Portfolio-wide performance.** The dataset records 899.9 million in sales, 332.1 million in operating profit and 2.48 million units sold across 2020–2021 (currency not supplied).
* **Retailer concentration.** West Gear contributes 243.0 million in sales (27.0%) and Foot Locker 220.1 million (24.5%). Together they represent 51.5% of sales. Sports Direct generates 182.5 million in sales and has the highest weighted retailer margin among the six retailers, at 40.7%.
* **Regional comparison.** The West records the highest sales (269.9 million), but the South has the highest weighted operating margin (42.3%) despite lower sales of 144.7 million.
* **Product performance.** Men’s Street Footwear leads in sales (208.8 million) and operating profit (82.8 million). Women’s Apparel ranks second on both measures.
* **Sales channels.** Online accounts for 939,093 units (37.9%), compared with 849,778 units through outlets (34.3%) and 689,990 in-store (27.8%). In-store sales nonetheless contribute the highest recorded sales value.

**Conclusion:** The project brought sales, volume and operating profit into a single Excel reporting view. It showed where sales are concentrated, which products and locations contribute most to profit, and why volume, revenue and profitability should be read together. These findings will inform focused performance reviews, product and channel planning, and further investigation of variations in commercial results.

## 📋8.  How the analysis answered the business questions and supports decisions

|Business question|What the analysis established|Management decision supported|
|-|-|-|
|Retailer performance|West Gear and Foot Locker together contribute 51.5% of recorded sales. Sports Direct has a higher weighted operating margin (40.7%) than either of them.|Compare retailer relationships using both revenue contribution and profitability; review concentration in the largest accounts.|
|Product demand and profit|Men’s Street Footwear generates the highest revenue (208.8m) and operating profit (82.8m).|Prioritise product assortment and stock-planning reviews using demand alongside profit contribution.|
|Regional performance|The West leads sales (269.9m), while the South achieves the highest weighted margin (42.3%).|Investigate the factors behind regional margin differences and identify practices worth reviewing elsewhere.|
|Sales channel demand|Online has the largest share of units sold (37.9%); in-store generates the greatest sales value (356.6m).|Consider channel-specific inventory, sales planning and further investigation of value per unit.|
|Revenue versus profitability|Retailer and product rankings differ when comparing sales, operating profit and weighted margin.|Use a balanced KPI view rather than revenue alone when assessing commercial performance.|
|City concentration|New York City, San Francisco, Miami, Charleston and Orlando are the five highest-sales city locations in the supplied data.|Use city-level results to direct local performance reviews and test where demand is most concentrated.|

## 🎓9.  Skills demonstrated

* Excel PivotTables and PivotCharts
* KPI definition
* Grouped aggregation and comparative analysis
* Weighted margin calculation
* Regional, retailer, product and channel segmentation
* Dashboard design
* Management reporting

