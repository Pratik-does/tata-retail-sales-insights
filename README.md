# 📊 Tata Retail Sales Insights Dashboard

## Project Overview

This project delivers an end-to-end data visualization solution built on retail transaction data to generate actionable business insights for executive stakeholders. The analysis focuses on transforming raw data into a structured, decision-ready dashboard that highlights revenue performance, customer behavior, and geographic demand patterns.

Designed as part of the Tata / Forage Data Visualisation Virtual Experience Program, the project simulates a real-world business intelligence engagement, requiring data cleaning, analytical thinking, and executive-level communication.

---

## Business Objective

The primary objective of this project is to support executive decision-making by answering key business questions related to:

- Revenue trends and seasonality  
- High-performing international markets  
- Customer value concentration  
- Global demand distribution  

The insights generated aim to guide strategic planning, including market expansion, customer retention, and operational optimization.

---

## Data Preparation

To ensure analytical accuracy, the dataset was cleaned and transformed prior to analysis:

- Removed invalid transactions (negative quantities representing returns)  
- Filtered out incorrect pricing data (non-positive unit prices)  
- Created a **Revenue metric (Quantity × Unit Price)**  
- Prepared date fields for time-series analysis  
- Structured data for customer-level and geographic insights  

This step ensured that all insights are based on reliable and business-relevant data.

---

## Key Visuals

The dashboard is structured as an executive summary and includes the following core analyses:

- **2011 Monthly Revenue Trend** – Identifies seasonal patterns and peak demand periods  
- **Top 10 Countries by Revenue and Quantity (Excluding UK)** – Highlights international market performance  
- **Top 10 Customers by Revenue** – Reveals customer value concentration  
- **Global Demand by Country (Excluding UK)** – Shows geographic demand distribution  

---

## Key Insights

- Revenue peaks in the final quarter, indicating strong seasonal demand  
- A small number of countries drive the majority of international revenue  
- Revenue is highly concentrated among a limited group of high-value customers  
- Demand is unevenly distributed, with clear regional clusters of strong performance  

---

## Business Recommendations

- Align inventory and marketing strategies with seasonal demand patterns  
- Expand operations in high-performing international markets  
- Implement retention strategies for high-value customers  
- Diversify the customer base to reduce revenue concentration risk  
- Focus on high-demand regions for targeted growth  

---

## Tools Used

- Tableau  
- Microsoft Excel  

---

## Project Structure
```
tata-retail-sales-insights/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── tableau/
│   └── tata_retail_sales_insights.twbx
│
├── screenshots/
│
├── docs/
│   ├── project_summary.md
│   └── insights_and_recommendations.md
│
├── README.md
└── LICENSE
```
---

## How to View

- Open the Tableau workbook (`.twbx`) to interact with the dashboard  
- View screenshots in the `screenshots/` folder for a quick preview  

---

## Outcome

This project demonstrates the ability to move from raw data to executive-level insights by combining data cleaning, visualization best practices, and business-oriented storytelling. It reflects core competencies required for a data analyst role, including analytical thinking, data preparation, and stakeholder-focused communication.

