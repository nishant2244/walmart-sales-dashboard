# walmart-sales-dashboard
1. Walmart Sales Dashboard
   
   An end-to-end Power BI solution analyzing retail health—tracking revenue growth, departmental trends, and regional performance across Walmart’s supply chain.



2. Purpose

   The Walmart Sales Performance Dashboard is a comprehensive Power BI analytics tool designed to track and evaluate retail health across diverse store locations.    It provides stakeholders with actionable insights into revenue growth, departmental performance, and regional sales trends to drive data-informed inventory and    marketing decisions.



3. Tech Stack
- The Walmart Sales Dashboard was built using the following tools and technologies:

- Power BI Desktop – The primary data visualization platform used to design and develop the interactive reports.

- Power Query – Utilized for the Extract, Transform, and Load (ETL) process to clean and structure the Walmart transaction data.

- DAX (Data Analysis Expressions) – Used to create critical business measures such as Monthly Sales by YoY, Monthly Profit by YoY, and Average Delivery Day.

- Data Modeling – Relationships established between sales data, geographic locations, and product categories to enable cross-filtering across visuals like Sales by State and Sales by Segment.

- Geospatial Mapping – Integrated Microsoft Bing Maps to visualize the geographic distribution of sales and profit across the United State.

- File Format – .pbit for the development file and .png for high-resolution dashboard previews in this repository.



4. Data Source
The primary data for this project was sourced from Kaggle. It contains historical sales records for Walmart stores across the United States, covering the period from 2011 to 2014.



5. Dataset Structure
The dataset consists of approximately 3,000+ rows and 16 column attributes, including:

- Transactional Data: Order Date, Sales, Quantity, and Profit.

- Customer Information: Segments such as Consumer, Corporate, and Home Office.

- Product Details: Categories (Technology, Furniture, Office Supplies) and specific Sub-categories like Phones, Chairs, and Storage.

- Logistics & Geography: Shipping Modes (Standard, Second Class, First Class, Same Day), Ship Dates, and location data including States and Regions.

- Time Intelligence: A comprehensive timeline used to calculate Year-over-Year (YoY) growth and monthly performance trends.


6. Highlights

• Business Problem

  Retail giants like Walmart manage massive volumes of data across multiple years, regions, and product categories. Without a centralized analytical view, it is     difficult for stakeholders to identify which states drive the most revenue, how different customer segments behave, or if delivery timelines are meeting           efficiency standards.

• Goal of the Dashboard

 The goal of this Power BI project is to deliver an interactive visual tool that:

  - Tracks Core KPIs:
    Monitors total sales ($678.78K), profit ($91.52K), and order quantity (10.62K) at a glance.

  - Analyzes Temporal Trends:
    Visualizes performance growth from 2011 to 2014 to identify seasonal peaks.

  - Optimizes Operations:
    Evaluates shipping efficiency and delivery timelines.

  - Segments Performance:
    Uncovers which product categories and customer types contribute most to the bottom line.



• Walkthrough of Key Visuals

  - Executive KPI Header:
             Displays high-level metrics including Total Sales ($678.78K), Profit ($91.52K), and an Average Delivery Day of 4.
  
  - Regional Filter Panel:
             Includes interactive slicers for Central, East, South, and West regions to allow for targeted data exploration.
  
  - Sales by State (Map & Bar Chart):
             Provides a dual view of geographic performance, highlighting California ($458K) and New York ($311K) as top-earning states.
  
  - Monthly Sales & Profit YoY (Line Charts):
              Compares performance across 2011, 2012, 2013, and 2014, showing a significant upward trend in sales reaching $734K in 2014.

  - Sales by Category:
              A breakdown showing Technology ($264.97K) as the leading category, followed by Furniture and Office Supplies.
  
  - Sales by Segment (Donut Chart):
              Visualizes the customer base, dominated by the Consumer segment at 52%, followed by Corporate (30%) and Home Office (19%).
  
  - Sales by Ship Mode:
              Analyzes logistics, showing Standard Class as the most utilized shipping method ($153.95K)


• Business Impact & Insights

   - Revenue Growth:
          The dashboard highlights a consistent increase in annual sales, peaking at $734K in 2014, indicating successful market penetration.

   - Regional Dominance:
           By filtering for the East region (which shows as 100% in specific views), managers can isolate and replicate successful regional strategies.

   - Product Strategy:
           High-value sub-categories like Phones ($100.61K) and Chairs ($96.26K) are identified as primary revenue drivers for inventory prioritization.

  - Operational Benchmarking:
            Maintaining a 4-day average delivery serves as a vital benchmark for customer satisfaction and logistics health.


6. Demo
    The demo of dashboard is : ![Alt Text](https://github.com/nishant2244/walmart-sales-dashboard/blob/main/Snapshot%20of%20dashboard.png)
