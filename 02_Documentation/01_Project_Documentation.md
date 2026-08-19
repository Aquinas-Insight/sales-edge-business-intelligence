# Sales Edge Business Intelligence Analysis

## Power BI Sales,Product, Profitability, Customer,Geographic & Shipping Analysis

> Turning historical transaction data into clear, actionable business insights.

**Project Type:** Business Intelligence / Data Analytics  
**Analysis Period:** January 2011 – December 2014  
**Tools:** Power BI | Power Query | DAX | 

---

## Table of Contents

- 1.Executive Summary
- 2.Business Problem
- 3.Project Objectives
- 4.Data Source
- 5.Data Description
- 6.Tools Used
- 7.Methodology
   - 7.1 Data Collection
   - 7.2 Data Profiling
   - 7.3 Data Cleaning
   - 7.4 Data Transformation
   - 7.5 Data Modeling
   - 7.6 DAX Measures
   - 7.7 KPI Development
   - 7.8 Dashboard Development
   - 7.9 Visual Design & User Experience
- 8.Key Insights
- 9.Business Recommendations
- 10.Limitations
- 11.Conclusion

- ---



# 1. Executive Summary

The **Sales Edge Business Intelligence Analysis** was developed to transform historical transaction-level sales and operational data into an interactive Power BI dashboard.

The analysis provides a consolidated view of business performance across:

- Sales
- Profitability
- Products
- Customer segments
- Geography
- Shipping & operations

The analysis covers the period from **January 2011 to December 2014**.

The objective was not simply to report business numbers, but to understand **what was driving performance, where profitability was under pressure, and where management could take action**.

### Overall Business Performance

| KPI | Result |
|---|---:|
| Total Orders | 25K |
| Total Sales | $12.6M |
| Total Profit | $1.5M |
| Profit Margin | 12% |
| Average Order Value | $505 |
| Total Shipping Cost | $1.4M |
| Average Shipping Cost | $54 |
| Average Shipping Duration | 4 days |

The business experienced strong growth during the analysis period.

Sales increased by approximately **26.3% year over year**, while profit increased by approximately **23.4%**.

However, profit margin declined by approximately **2.2%**.

This creates an important business question:

> **The business is growing, but is it growing profitably?**

The analysis identified several important performance patterns.

Technology emerged as the strongest profit-generating category. Furniture generated significant revenue but comparatively lower profit, while the Tables sub-category generated substantial sales but recorded a negative profit.

The Consumer segment contributed approximately **51.5% of total revenue**, while Central region contributed approximately **22.3% of total revenue**.

The shipping analysis also highlighted a clear relationship between delivery speed and shipping cost which result to high shipping cost fast delivery.

---

# 2. Business Problem

The business had access to a large amount of transactional data, but raw data alone does not provide management with a clear understanding of business performance.

The main challenge was to transform the available data into information that could answer practical business questions.

The analysis focused on questions such as:

- Are increasing sales also translating into increasing profitability?
- Which product categories generate the most profit?
- Which sub-categories are underperforming?
- Are discounts affecting profitability?
- Which customer segments generate the most revenue?
- Which regions and markets are performing well?
- Which markets require further investigation?
- How much is the business spending on shipping?
- Which shipping modes are the most expensive?
- Is faster delivery worth the additional cost?
- Where can management improve profitability?
- Where can operational efficiency be improved?

The project addresses these questions through an interactive Power BI dashboard that allows users to move from high-level performance to detailed analysis.

---

# 3. Project Objectives

The main objective was to build an interactive Business Intelligence dashboard that allows management to monitor business performance and identify areas for improvement.

### Specific objectives

- Measure total sales and profit.
- Track sales and profit trends over time.
- Monitor profit margin.
- Analyze product category and sub-category performance.
- Examine the relationship between discounts and profitability.
- Compare customer segment performance.
- Evaluate regional and market performance.
- Identify profitable and underperforming areas.
- Analyze shipping costs and delivery duration.
- Identify operational efficiency opportunities.
- Develop actionable business recommendations.
- Present the findings through an interactive Power BI dashboard.

---

# 4. Data Source

The project uses transaction-level sales and operational data covering:

**January 2011 – December 2014**

The dataset contains information relating to:

- Orders
- Customers
- Products
- Sales
- Profit
- Discounts
- Product categories
- Product sub-categories
- Customer segments
- Regions
- Markets
- Countries
- Shipping modes
- Shipping costs
- Order priority
- Shipping duration

The raw data was imported into Power BI and prepared using Power Query.

> **Note:** The dataset source should be credited here if the project uses a publicly available dataset.

---

# 5. Data Description

## 5.1 Sales & Order Data

| Field | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date the order was placed |
| Ship Date | Date the order was Shipped|
| Sales | Revenue generated |
| Profit | Profit generated |
| Quantity | Number of units ordered |
| Discount | Discount applied |

---

## 5.2 Product Data

| Field | Description |
|---|---|
| Product ID | Unique Product Identifier |
| Product Name | Individual product |
| Category | Main product category |
| Sub-Category | Product classification |

### Main Categories

- Technology
- Furniture
- Office Supplies

---

## 5.3 Customer Data

| Field | Description |
|---|---|
| Customer | Customer identifier |
| Segment | Customer classification |

### Customer Segments

- Consumer
- Corporate
- Home Office

---

## 5.4 Geographic Data

| Field | Description |
|---|---|
| Region | Geographic region |
| Market | Geographic Market |
| Country | Individual Country| 
|State| Individual State |

## Main Region

- Africa
- Canada
- Caribbean
- Central
- Central Asia
- East
- EMEA
- North
- North Asia
- Oceania
- South
- Southwest Asia
- West 

---

## 5.5 Shipping Data

| Field | Description |
|---|---|
| Ship Mode | Shipping method |
| Shipping Cost | Cost associated with shipping |
| Shipping Duration | Delivery duration |
| Order Priority | Priority assigned to the order |

### Shipping Modes

- Standard Class
- Second Class
- First Class
- Same Day

---

# 6. Tools Used

## Power BI

Power BI was used to build the final Business Intelligence solution.

It was used for:

- Data modeling
- DAX calculations
- KPI development
- Data visualization
- Interactive filtering
- Dashboard development
- Business analysis

---

## Power Query

Power Query was used for data preparation and transformation.

The main activities included:

- Data profiling
- Data cleaning
- Data type correction
- Missing-value review
- Duplicate review
- Data transformation
- Column standardization

---

## DAX

DAX was used to create the business measures required for the analysis.

These included measures for:

- Total Sales
- Total Profit
- Total Orders
- Profit Margin
- Average Order Value
- Shipping Cost
- YoY% Changes
- And More

---

# 7. Methodology

The analysis followed a structured end-to-end Business Intelligence process, starting with understanding the raw data and ending with an interactive dashboard and business recommendations.

### Overall Workflow

```text
Raw Data
   ↓
Data Collection 
   ↓
Data Profiling
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
KPI Development
   ↓
Dashboard Development
   ↓
Insight Generation
   ↓
Business Recommendations
