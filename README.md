# Marketing Campaigns Performance Analysis - BCGX simulation

Dataset source: [Forage - BCGX simulation](https://www.theforage.com/simulations/bcg/data-for-decision-makers-tod0?reloaded=true)

## Project Overview
This project focuses on analyzing marketing campaign performance for NewCo, with the goal of providing actionable insights to guide strategic investment decisions.  
The analysis evaluates two campaign versions (Campaign A and Campaign B) distributed across multiple channels (Email, Instagram, Web Banner), each with distinct messaging styles and formats. By examining customer engagement, conversion rates, and time on site, the project aims to identify the most effective campaign-channel combinations and inform marketing strategy for the next quarter.

### Campaign Characteristics
* **Campaign A**: Focuses on a friendly, informal tone designed to build trust and engage new customers. Suitable for channels that favor personal and approachable messaging, like Email or Instagram posts.
* **Campaign B**: Uses a professional, sales-oriented tone to drive immediate conversions. Designed for channels where users are ready to purchase or respond to promotional content, such as Email and Web Banners.

### Tools and Skills Used
* **Excel**: Pivot tables, chart creation
* **Data Analysis**: Hypothesis testing, cohort analysis, segmentation
* **Business Intelligence**: KPI definition, performance metrics, strategic recommendations

## Analysis Approach
The analysis follows a hypothesis-driven, consulting-style approach.  
Starting from the client’s business questions, initial hypotheses were formulated based on campaign formats, channels, and customer segments. 

**Data & Tools:**
* The dataset was provided pre-cleaned by the BCGX simulation
* Analysis conducted entirely in Excel using pivot tables to aggregate and segment data
* Visualizations created with Excel charts to communicate findings effectively

<img src="./media/output/excel-demo.png">

These hypotheses were then tested using the Excel-based analysis to generate actionable insights.

## Business Questions
The client aims to understand the effectiveness of its marketing efforts and define future investment priorities.  
Key questions include:
1. Which campaign and channel combination delivered the most value?
2. What drove engagement from new customers?
3. Where should marketing investment be focused next quarter—and why?

## Hypotheses
Before conducting the analysis, the following hypotheses were formulated:
* Instagram, particularly in a 3:4 format with an informal tone, may generate higher engagement due to platform-specific user behavior.
* Email and web banner campaigns may perform better with a more professional and sales-oriented message.
* Different channels may drive value differently for new versus returning customers.

## Analysis & Key Findings

### Revenue Performance  
Email campaigns generated 54% of total revenues ($7.9k).

<img src="./media/output/graphs/channel-performance.png">

### Message Effectiveness  
Campaign B performed best in terms of overall sales ($8.7k), regardless of customer type.

<img src="./media/output/graphs/campaign-performance.png">

### Campaign-channel best performer 
The strongest campaign-channel combination in terms of sales was **Email + Campaign B**.

<img src="./media/output/graphs/overall-performance.png">

### Engagement Beyond Sales  
Instagram shows high interaction time among users who did not convert, highlighting top-of-funnel potential for future retargeting campaigns.

<img src="./media/output/graphs/interaction-time-non-converted.png">

### New Customer Acquisition  
**Email + Campaign A** was the most effective combination for attracting new customers ($3.5k of sales).

<img src="./media/output/graphs/new-customers-acquisition.png">

## Strategic Recommendations
Based on the insights:
* Increase investment in **Email + Campaign A** to continue driving new customer acquisition.
* Maintain **Email + Campaign B** to support overall revenue generation.
* Leverage Instagram primarily as an awareness and engagement channel, with potential retargeting strategies.
* Test follow-up email messages to optimize conversion while preserving the trust-building tone.

## Key Takeaways
* Maximizing revenue and acquiring new customers require different channel and message strategies.
* Email remains the most effective channel overall, but message tone significantly impacts outcomes.
* A key trade-off to consider is balancing short-term revenue with long-term new customer growth.

## Repository Structure
* **analysis/**
    * [campaigns-analysis.xlsx](./analysis/campaigns-analysis.xlsx) - Main analysis file with pivot tables, calculations and graphs
* **dataset/**
    * [campaign_data_week1.xlsx](./dataset/campaign_data_week1.xlsx) - Original dataset from BCGX simulation
* **media/**
    * [input](./media/input/) - Project brief and context documents
    * [output](./media/output/) 
        * [deliverables](./media/output/deliverables/) - Power Point and PDF final presentation as deliverables
        * [graphs](./media/output/graphs/) - All visualizations used in analysis

## How to Reproduce
1. Clone or download this repository
2. Open `analysis/campaigns-analysis.xlsx` in Microsoft Excel
3. Navigate through the pivot table sheets to explore the analysis
4. Review this `README.md` for complete findings and strategic recommendations

## About This Project
This analysis was completed as part of the BCG X Data for Decision Makers virtual experience program on Forage, demonstrating business analysis and strategic thinking skills applicable to marketing analytics roles.