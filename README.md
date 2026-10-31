# Retail Sales & Profitability Analysis
### Sales Dataset | Excel Dashboard & Commercial Performance Insights

An analysis of transactional retail sales records to evaluate revenue and operating profit distribution across retail partners, product categories, geographical regions, and sales channels.

## 📊 Project at a Glance

| Area | Dataset and Deliverables |
| :--- | :--- |
| **Source** | Excel sales database with 9,648 populated sales records across 2020–2021 |
| **Coverage** | Six retailers, five regions, six product groups, and three sales methods |
| **Tools** | Microsoft Excel (Structured tabular data, PivotTables, and dashboard charts) |
| **Outputs** | Retailer performance, channel mix, regional profitability, product sales, and margins |

---

## 1. Business Context & Core Questions
This project consolidates transactional data into clear summary measures and visual reports, enabling commercial teams to isolate key revenue drivers and identify margin pressures.

**The analysis directly addresses four commercial questions:**
* Which retail partners generate the largest share of total sales?
* Which product categories and regions contribute most to revenue and operating profit?
* How does sales-channel performance differ when comparing financial value against unit volumes?
* Which product segments are most profitable, and how should that profitability be interpreted?

---

## 2. Analytical Approach & Methodology

1. **Data Structuring:** The source transactional table tracks invoices across key dimensions (date, geography, retailer, product, sales method) and financial values (price, units sold, total sales, operating profit, operating margin).
2. **Reconciliation & Controls:** Aggregates were reconciled across all 9,648 rows to ensure perfect data integrity. The clean dataset contains no blank values in core fields and balances exactly to:
   * **Total Sales:** 899,902,125
   * **Operating Profit:** 332,134,761
   * **Units Sold:** 2,478,861
3. **Metric Definitions:** Calculations enforce strict financial logic. The overall **Weighted Operating Profit Margin (36.9%)** is derived strictly as *Total Operating Profit ÷ Total Sales*. Averaging row-level margins is deliberately avoided as it introduces statistical skew.

---

## 3. Headline Performance Indicators

| KPI | Result | Interpretation |
| :--- | :--- | :--- |
| **Total Recorded Sales** | 899.9m | Aggregate value of sales across the analysed period |
| **Operating Profit** | 332.1m | Combined profitability measure supplied in the source data |
| **Weighted Operating Margin** | 36.9% | True operating profit divided by total sales |
| **Units Sold** | 2,478,861 | Volume of product units moved across all sales methods |
| **Sales Records** | 9,648 | Total transactional rows checked and validated |

*> Note: Currency is not explicitly specified in the raw dataset and is therefore left unassumed throughout the analysis.*

---

## 4. Key Findings & Commercial Insights

### Retailer & Product Contribution
* 🥇 **Top Retailers:** **West Gear** leads the portfolio with 243.0m (**27.0%** of total), followed closely by **Foot Locker** at 220.1m (**24.5%**). Combined, these two partners command **51.5%** of all recorded sales.
* 👟 **Core Product:** **Men’s Street Footwear** stands out as the single largest product segment, generating 208.8m (**23.2%** of total revenue).

### Regional Profit Performance
* 🗺️ **Geography:** The **West region** yields the largest total operating profit at 89.6m, with the **Northeast** following at 68.0m. 
* ⚠️ **Insight:** Comparing revenue side-by-side with operating profit reveals that higher sales volumes do not automatically yield uniform profit margins across regions.

### Sales Channels & Unit Mix
* 📦 **In-Store vs. Online:** **In-store** channels drive the highest financial value at 356.6m (**39.6%** of sales), while **Online** generates 247.7m (**27.5%**).
* 🔄 **The Volume Divergence:** Despite lower revenue, **Online leads on unit volume with 939,093 units (37.9% of all units)**. This underscores why financial revenue and physical unit volumes must be evaluated together. **Outlet** sales bridge the gap at 295.6m from 849,778 units.

---

## 5. Excel Techniques & Reporting Deliverables

The accompanying workbook implements specialized features to transform raw line-items into decision-ready assets:
* **Data Organisation:** Enforces uniform structures across geographical, categorical, and chronological dimensions.
* **PivotTable Summaries:** Leverages multi-dimensional aggregations to evaluate cross-tab performance (e.g., assessing specific product category volumes sold *by* individual retail partner).
* **Dashboard Reporting:** Consolidates **seven interactive charts** onto a unified dashboard tab, backed cleanly by isolated calculation sheets.
* **Quality Auditing:** Implements built-in reconciliation summaries to verify that dashboard visuals align perfectly back to the main transactional table.

---

## 6. Skills & Competencies Demonstrated
* **Excel Data Analysis:** Building multi-layered PivotTables, utilizing conditional aggregations, and executing row-grain validation.
* **Performance Reporting:** Evaluating revenue metrics, volume balances, and calculating true weighted commercial margins.
* **Data Visualisation:** Structuring executive-level dashboards and streamlined chart environments.
* **Commercial Insight:** Translating corporate transactional ledgers into targeted performance summaries regarding channel mix and partner concentration.

---

## 7. Project Files
* 📁 **Source Workbook:** `Adidas Sales Dataset.xlsx` (Includes transactional database, summary tables, and final Dashboard worksheet)
