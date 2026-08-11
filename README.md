# Product-Sales-Analysis
## Project Overview

This project analyzes sales performance for **Head Rest Bed Company**, a multi-store retailer selling mattresses, pillows, frames, and linen.

The analysis covers **January 2018 – December 2019** and focuses on understanding what drives revenue and margin across stores, products, brands, managers, and promotional activity.

**Tool:** Microsoft Excel (PivotTables, PivotCharts, Data Model / Power Pivot concepts, DAX)

## Business Problem

Management needs clear visibility into:

- Which stores and products generate the most sales **and** the strongest margins
- Whether promotional discounting is helping or hurting overall profitability
- Seasonal patterns that should guide inventory and staffing
- Which brands, firmness levels, and managers perform best

Without structured analysis, the business risks chasing sales volume while eroding margin.

---

## Business Questions

1. Which stores generate the highest sales and the strongest margin %?
2. How do product categories and firmness levels contribute to volume vs. margin?
3. What is the monthly / seasonal sales pattern?
4. How do Full Price vs. Promo sales compare in units, revenue, and margin per unit?
5. Which managers deliver the best performance?
6. Do promotional discounts increase overall profit?
7. Which brands perform best by revenue and margin?
8. Are there under-performing products that need review?

---

## Dataset Structure

| Table        | Type       | Description                                      |
|--------------|------------|--------------------------------------------------|
| Sales        | Fact       | Transaction-level sales data                     |
| Dates        | Dimension  | Calendar attributes (Year, Month, Week, etc.)    |
| Products     | Dimension  | SKU, Brand, Category, Firmness, Size, Price      |
| Stores       | Dimension  | Store ID, Type, Location                         |
| Managers     | Dimension  | Manager details and time in service              |
| Commission   | Lookup     | Commission rates by years of service             |

**Key Metrics:**
- Total Sales: **~$65.5 Million**
- Total Margin: **~$19.25 Million** (~29.4%)
- Total Units: **~211,520**

---

## Dashboard Contents

The main **Dashboard** sheet includes:

- Sales trend (2018–2019)
- Best selling product types
- Profit comparison: Full Price vs Promotion
- Product / brand mix view

Supporting analysis is available in the Pivot Tables sheet.

---

## Key Insights

| Area                  | Insight                                                                 | Recommendation                                      |
|-----------------------|-------------------------------------------------------------------------|-----------------------------------------------------|
| Store Performance     | Las Vegas, Jersey City, and Austin lead in sales. Denver & New York have weaker margins. | Focus improvement efforts on low-margin stores while protecting top performers. |
| Product Category      | Pillows drive volume. Frames deliver strong margin per unit. Soft & Medium mattresses outperform Extra Soft. | Prioritize Soft/Medium inventory. Review Extra Soft performance. |
| Brand                 | Lux Bed leads in both sales and margin (~33.6%). Only Beds has high volume but lowest margin (~25%). | Protect and promote Lux Bed. Examine Only Beds discounting and cost structure. |
| Promotion Impact      | Full Price avg margin ≈ $96/unit. Promo avg margin ≈ $70/unit.         | Use promotions selectively. Avoid deep discounts on high-margin items. |
| Seasonality           | Strong peak in November–December. Weakest months are May–June.         | Align inventory, staffing, and marketing with seasonal peaks. |

---

## Tools & Techniques Used

- PivotTables & PivotCharts
- Excel Data Model (Power Pivot concepts)
- DAX measures
- Relationship design (One-to-Many)
- Calculated columns (Year, Month, Margin, etc.)
- Waterfall-style margin analysis
- Dashboard design for stakeholder presentation

---

## Data Preparation Steps

- Checked transaction data for consistency
- Linked Sales to Products, Stores, Managers, and Dates
- Calculated revenue, cost, and gross margin
- Created time intelligence fields (Year, Month, Quarter)
- Built relationships in the Data Model
- Developed PivotTables, PivotCharts, and Dashboard

---

## Data Limitations

- Visible Sales sheet contains a sample of ~1,000 rows; full metrics come from the data model
- Analysis period is limited to 2018–2019
- Some ManagerID values are missing
- Promo details are limited in the sample extract
- Commission rates exist but are not fully applied in all views

---

## How to Use This File

1. Open the Excel file in Microsoft Excel (Microsoft 365 recommended)
2. Start with the **Dashboard** sheet for the executive view
3. Explore **Pivot_tables&testing** for detailed breakdowns
4. Review **Project_Overview** for business context and methodology

---

## Author
## Min_Swam_Htet_Paing<img width="581" height="334" alt="Screenshot 2026-08-12 054157" src="https://github.com/user-attachments/assets/dc58ee03-61f2-40ab-ad86-6db4425dd639" />


Data Analysis Project – Head Rest Bed Company Sales Performance
