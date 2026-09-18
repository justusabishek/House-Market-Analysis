# House-Market-Analysis-Dashboard

## Dashboard Link : https://app.fabric.microsoft.com/groups/a5a9f667-ee00-4a24-9851-bfd1f2fa8653/reports/9bfa291b-2874-4bdc-9616-56ec0cf692f3/76aab9d0af260167f24f?experience=fabric-developer

## Problem Statement
This dashboard provides a comprehensive analysis of the housing market, covering regional price changes, sales performance, and property type comparisons. It helps stakeholders understand market dynamics such as median sales price shifts, YOY growth, and purchase vs. offer price trends. By integrating cleaned data from Google Cloud into Power BI, the dashboard delivers actionable insights for real estate decision-making.

## Steps followed
 - Step 1 : Uploaded dataset into Google Cloud Console.

 - Step 2 : Performed data cleaning using SQL queries in Google Cloud (handled nulls, standardized region names, removed duplicates).

 - Step 3 : Connected the cleaned dataset to Power BI Service through a Dataflow.

 - Step 4 : Configured the Dataflow for scheduled refresh and transformations.

 - Step 5 : Connected the Dataflow output into Power BI Desktop for report building.

 - Step 6 : Created DAX measures to calculate KPIs such as median sales price change, YOY growth, average SQM price, and inflation/interest/yield metrics.

 - Step 7 : Designed multiple dashboards with tabs:

   - House Market Overview

   - Sales Performance

   - House Type Analysis

 - Step 8 : Added slicers for filtering by Region, Sales Type, Area, and City.

 - Step 9 : Inserted card visuals for KPIs such as Units Sold, Last 12 Month Sales, and Supply/Demand metrics.

 - Step 10 : Built bar charts, scatter plots, line charts, and donut charts to represent regional and property-type comparisons.

 - Step 11 : Styled the dashboard with a professional theme, added project title and company logo.

 - Step 12 : Published the report to Power BI Service for collaboration and sharing.

## Snapshot of Dashboard (Power BI Service)
<img width="960" height="462" alt="Image" src="https://github.com/user-attachments/assets/a296f3cc-7db1-474b-8d04-cb37bd5afead" />

<img width="960" height="466" alt="Image" src="https://github.com/user-attachments/assets/f412852b-2f32-4c26-96f2-8e255c006a2f" />


<img width="960" height="485" alt="Image" src="https://github.com/user-attachments/assets/a8d8354d-a745-4bf6-b73c-090ff2516375" />

## Insights
A multi-page report was created in Power BI Desktop and published to Power BI Service.

### [1] House Market Overview
Median Sales Price Change varies by region: Zealand, Jutland, Fyn & Islands, Bornholm.

Units Sold (Latest Year & Quarter) = 77.

Last 12 Month Sales = 13bn.

Offer Price vs Purchase Price shows close alignment, indicating stable negotiations.

YOY Sales Growth: Auction sales (+0.29), Regular sales (-0.21), Family sales (-0.75).

### [2] Sales Performance
Sales by Region: Zealand (95bn) leads, followed by Jutland (81bn).

Key Influencers: Age ≥16 increases purchase price by 501K; Age >75 increases by 391K.

Offer to SQM Ratio: Regular sales highest (14.9K).

Average SQM Price: Zealand highest (20.85K), followed by Jutland and Fyn.

### [3] House Type Analysis
Offer vs Purchase Price: Farms (2.7M), Apartments (2.4M), Villas (1.8M).

Inflation/Interest/Yield: Farms yield highest (4.6), Apartments lowest (3.9).

Average SQM Price: Apartments highest (28.7K), Townhouses (19.4K), Summerhouses (15.2K).
