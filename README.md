# 📊 Bright Coffee Shop Sales Analysis

**Business Insights for the New CEO**  
**Junior Data Analyst Project**  
**Due Date:** 31 March 2026  
**Submission Platform:** GitHub

---

## 🌟 Project Overview

Bright Coffee Shop recently appointed a new CEO with a clear mission: **grow revenue and improve product performance**.  

This end-to-end analytics project leverages historical transactional data to deliver **actionable insights** on:
- Top-performing products by revenue
- Peak sales hours throughout the day
- Sales trends by product category and 30-minute time intervals
- Strategic recommendations to boost overall performance

The final deliverables include a professional presentation, interactive dashboards, clean processed data, and full documentation — everything the CEO needs to make data-driven decisions.

---

## 🎯 Objectives

- Identify which products generate the **most revenue**
- Determine **what time of day** the store performs best
- Uncover **sales trends** across products and time intervals
- Provide **practical recommendations** for improving sales performance

---

## 🛠️ Tools & Technologies Used

| Category              | Tools                                      |
|-----------------------|--------------------------------------------|
| **Project Planning**  | Miro                                       |
| **Data Processing**   | Databricks • Snowflake • SQL               |
| **Data Analysis**     | Microsoft Excel • Pivot Tables             |
| **Visualization**     | Excel Charts & Dashboards                  |
| **Presentation**      | Microsoft PowerPoint                       |
| **Version Control**   | GitHub                                     |

---

## 📋 Project Tasks Completed

### Task 1: Planning & Architecture (Miro)
- Created a comprehensive **Data Flow & Architecture Diagram** showing:
  - Data source → ETL pipeline → Snowflake storage → Analysis & Presentation
- Defined key insights to deliver and outlined all calculations

### Task 2: Data Processing (Databricks + Snowflake)
- Converted raw Excel file to CSV
- Loaded data into Snowflake
- Performed data transformations:
  - Created `transaction_time_bucket` (30-minute intervals)
  - Fixed unit_price formatting (e.g., '3,1' → 3.1)
  - Calculated `total_amount = unit_price × transaction_qty`
- Wrote clean SQL queries for aggregations by product type, time bucket, etc.

### Task 3: Data Analysis & Visualization (Excel)
- Exported processed dataset
- Built interactive **pivot tables and dashboards** showing:
  - Total revenue per product type
  - Peak sales time intervals
  - Quantity sold by product category
  - Best-selling vs. underperforming items
- Designed clear, professional charts for storytelling

### Task 4: CEO Presentation (PowerPoint)
- **Methodology** document
- **Key Insights** backed by visuals
- **Recommendations**:
  - Targeted marketing during slow periods
  - Increase stock of best-sellers
  - Promotional strategies for low performers
- **Next Steps**:
  - Automate daily sales reporting
  - Expand to multi-location tracking
  - Launch loyalty programs based on peak hours

---

## 📁 Repository Contents

- **`Miro/`** – Data Flow Diagram + Key Insights board (exported as PDF/PNG)
- **`Data/`** – 
  - `bright_coffee_shop_sales_raw.csv` (original)
  - `bright_coffee_shop_sales_processed.xlsx` (with pivot tables & charts)
- **`SQL/`** – All SQL scripts used in Databricks/Snowflake
- **`Presentation/`** –
  - `Bright_Coffee_Shop_Sales_Analysis_Presentation.pptx`
  - `Methodology.pdf`
- **`README.md`** – This file

---

## 🚀 Key Insights (Preview)

*(Full details and visuals are in the PowerPoint and Excel dashboard)*

- **Top Revenue Driver:** [Product Name] – X% of total sales
- **Peak Performance:** [Time Bucket] consistently shows the highest transaction volume
- **Growth Opportunity:** [Underperforming Product] shows strong potential with targeted promotion
- **Daily Pattern:** Clear morning rush and afternoon lull identified

---

## 💡 Recommendations & Next Steps

- Run **morning rush-hour promotions** and **afternoon happy-hour campaigns**
- Prioritize inventory for top 3 revenue-generating products
- Introduce **loyalty program** timed to peak customer hours
- Automate daily sales reports for real-time CEO visibility

---

## 📸 Screenshots

*(Add screenshots of your Miro board, Excel dashboard, and PowerPoint slides here once uploaded)*

---

## 🙌 Acknowledgments

This project demonstrates end-to-end data analytics skills — from planning and ETL to insightful visualization and executive storytelling. Ready to help drive real business growth at Bright Coffee Shop!

---

**Made with ❤️ by [Your Name]**  
**Junior Data Analyst**  
**Cape Town, South Africa** | March 2026

---

*Feel free to clone, explore the data, and reach out if you'd like to discuss the analysis or collaborate on similar projects!*
