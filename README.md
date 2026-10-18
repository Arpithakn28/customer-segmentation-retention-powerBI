# Customer Segmentation & Retention Analytics in Power BI

## Project Overview

An interactive Power BI business intelligence project designed to analyse customer purchasing behaviour, customer segments, revenue contribution, loyalty performance, and retention risk.

The dashboard helps demonstrate how customer data can be transformed into actionable insights for marketing, CRM, and business decision-making.

> **Project type:** Portfolio / learning project  
> **Data:** Synthetic sample data  
> **Tools:** Power BI Desktop, Power Query, DAX, Excel

## Objective

- Segment customers based on spending and purchasing behaviour.
- Monitor customer retention and churn status.
- Analyse revenue contribution by customer segment.
- Evaluate customer engagement, satisfaction, and loyalty tiers.
- Identify customers who may need targeted retention campaigns.
- Present business KPIs through an interactive dashboard.

## Industry Relevance

Customer analytics is relevant to e-commerce, retail, subscription businesses, and other customer-focused industries.

Organisations can use segmentation and retention reporting to understand purchasing patterns, personalise campaigns, monitor customer activity, and make better-informed marketing decisions.

## Tools Used

- **Microsoft Power BI Desktop:** Dashboard creation and reporting.
- **Power Query:** Data cleaning and transformation.
- **DAX:** KPI calculations and analytical measures.
- **Microsoft Excel / CSV:** Dataset storage and preparation.
- **GitHub:** Project versioning and portfolio presentation.

## Dataset Description

The project uses fictional data for learning and demonstration.

### Customers table

Includes customer ID, demographic information, location, occupation, income level, join date, last purchase date, purchase frequency, average order value, total spend, preferred product category, purchase channel, customer type, engagement score, satisfaction score, retention status, customer segment, and loyalty tier.

### Transactions table

Includes transaction ID, customer ID, purchase date, order amount, purchase channel, and product category.

### Data considerations

- Customer IDs uniquely identify customers.
- Transaction IDs uniquely identify purchases.
- Customer and transaction tables are connected using Customer ID.
- Monetary values are formatted in Indian rupees (INR).
- Customer status classifications are illustrative and should be validated against a real business definition before operational use.

## Power Query Steps

1. Imported customer and transaction data from CSV or Excel.
2. Standardised column names and text formats.
3. Checked missing values and handled invalid records.
4. Removed duplicate customer IDs and transaction IDs where appropriate.
5. Assigned suitable data types to numeric, text, and date columns.
6. Standardised city, category, and purchase-channel values.
7. Prepared purchase month and year fields.
8. Validated customer keys, dates, and monetary values.
9. Applied the transformations to Power BI.

## Data Model

The Customers table has a one-to-many relationship with the Transactions table.

`Customers[Customer ID]` → `Transactions[Customer ID]`

A separate Calendar table supports date filtering and transaction trends.

## DAX Measures

The project includes measures for:

- Total Customers
- Total Revenue
- Average Order Value
- Repeat Customers
- Retained Customers
- Retention Rate %
- Churned Customers
- Churn Rate %
- At-Risk Customers
- Average Customer Lifetime Spend
- Segment Revenue
- Average Engagement Score
- High Value Customers
- At-Risk Revenue
- Average Satisfaction

Retention and churn definitions must use a clearly specified customer population and time period. The starter dashboard's status-based percentages are not a substitute for full cohort retention analysis.

## Dashboard Features

### Customer Overview

- Total customer KPI
- Total revenue KPI
- Retention rate KPI
- Churn rate KPI
- Average order value KPI
- Customer segment comparison
- Revenue by segment
- Retention status distribution
- Monthly revenue trend
- Segment performance matrix

### Retention & Risk

- At-risk customer count
- At-risk revenue
- Retention status by region
- Engagement and satisfaction analysis
- Loyalty tier performance
- Customer and date filters

### Interactive Filters

- City / Region
- Customer Segment
- Purchase Channel
- Loyalty Tier
- Gender
- Purchase Date

## Key Insights

Use the completed dashboard to document actual findings.

Examples of questions to investigate:

1. Which customer segment contributes the most revenue?
2. Which customer groups have the highest at-risk count?
3. Which regions show the strongest retention?
4. How does customer performance differ by purchase channel?
5. Which loyalty tiers contribute the most revenue?
6. Is low satisfaction associated with at-risk or churned status?
7. Which customer segments may benefit from targeted campaigns?

**Important:** Replace these questions with findings supported by your actual Power BI results. Do not report illustrative patterns as verified business outcomes.

## Screenshots

### 1. Customer Overview
<img width="1157" height="642" alt="Customer retention dashboard" src="https://github.com/user-attachments/assets/85cd2410-d9ab-43bc-a273-92f1c84afade" />



### 2. Retention & Risk

<img width="1157" height="642" alt="Customer retention dashboard" src="https://github.com/user-attachments/assets/85cd2410-d9ab-43bc-a273-92f1c84afade" />



### 3. Segment Analysis

<img width="592" height="457" alt="Screenshot 2026-10-18 190711" src="https://github.com/user-attachments/assets/72b68e8c-f934-4a0f-a109-0c4bdf947ae9" />



*Replace these image paths with screenshots captured from the completed Power BI report.*

## Business Recommendations

Based on the actual findings, potential recommendations may include:

- Develop targeted re-engagement campaigns for at-risk customers.
- Personalise offers using purchasing behaviour and preferred categories.
- Evaluate loyalty benefits against customer spending and margin.
- Investigate customer satisfaction issues in weaker-performing segments.
- Monitor repeat purchase behaviour and retention over time.
- Evaluate campaign results using measurable business KPIs.

## Limitations

- The sample dataset is synthetic and does not represent a real company's performance.
- Customer segments and retention status are illustrative classifications.
- Historical spend is not a predictive customer lifetime value model.
- Reliable cohort retention requires historical customer activity data.
- Revenue contribution does not establish profitability without cost and margin data.

## Conclusion

This project demonstrates practical skills in Power Query, data modelling, DAX, Power BI visualisation, and customer analytics. It illustrates how customer information can be organised into an interactive reporting solution to support segmentation, retention monitoring, and marketing decisions.

## Project Structure

```text
customer-segmentation-retention-powerbi/
├── data/
├── powerbi/
├── screenshots/
├── documentation/
├── presentation/
├── exports/
└── README.md
```

## Author

Arpitha K N

MBA Student | Finance / H R

Skills: Power BI, DAX, Power Query, Excel, Customer Analytics



This is an educational portfolio project using synthetic sample data. It is not affiliated with or endorsed by any company.
