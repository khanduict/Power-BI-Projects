# 📊 Marketing Effectiveness & Customer Behavior Dashboard (Power BI)

### Tool Stack: Power BI | DAX | Data Modeling | Power Query

## 📌 Scenario
The client is a small company still learning their market and evaluating customer behavior. They have recently launched six marketing campaigns and want deeper insight into:
- Performance of 6 recent marketing campaigns
- Product-level revenue contribution
- Customer demographic composition
- Drivers behind campaign acceptance and sales performance
The organization is in an early growth phase and requires data-driven clarity to optimize marketing spend and improve ROI.
  
## 🎯 Business Problem
- The client needs a BI solution to answer:
- How are our 6 recent marketing campaigns performing? 
- How are our products performing? -
- Who are our customers?
- What is driving campaign performance and buyer decision-making? 

## 🎯 Business Objectives
- Evaluate campaign effectiveness
- Identify high-performing product categories
- Understand customer demographics
- Determine key drivers influencing purchases and campaign acceptance

## 🖥️ Dashboard Overview
![!(https://github.com/khanduict/Marketing-Effectiveness-Customer-Behavior-Dashboard-Power-BI-/blob/main/Marketing%20effectiveness%20and%20customer%20behavior%20dashboard.gif) ](https://github.com/khanduict/Marketing-Effectiveness-Customer-Behavior-Dashboard-Power-BI-/blob/main/Marketing%20effectiveness%20and%20customer%20behavior%20dashboard.gif)

### 1️⃣ Campaign Performance Dashboard
### Findings
#### 🏆 Campaign 6 is the Benchmark Performer
- Highest purchase volume (334)
- Highest revenue (~$0.33M)
- Balanced multi-channel performance
- Strong Wine category contribution
#### Strategic Insight:
Campaign 6 provides a replicable model for future campaign design.
#### ⚠️ Campaign 2 Underperforms
- Lowest revenue (~$0.04M)
- Low purchase conversion
- Heavy reliance on Wine category but weak overall traction
#### Recommendation:
Reassess segmentation, messaging alignment, and targeting strategy.
#### 🍷 Revenue Concentration in Premium Categories
Top revenue drivers:
- Wine (~$0.48M)
- Meat (~$0.37M)
Lower revenue categories:
- Fruit & Sweets (~$0.06M)
#### Implication:
Profitability is strongly tied to premium product positioning.
#### 🏪 Channel Insights
Purchase distribution:
- Store: 13K+
- Web: 9K+
- Catalog: 6K+
- Deals: 5K+
#### Observation:
Physical retail remains dominant, but digital channels show scalable growth opportunity.

### 2️⃣ Buyer Composition Analysis
![Market Research Assignment dashboard_Page_2](https://github.com/user-attachments/assets/799807aa-63bf-4b4e-ad28-bb1c77221224)

#### Customer Profile Snapshot
- Total Customers: 2,240
- Avg Income: ~$52K
- Avg Age: 57
- Majority: Married households
- Highly educated (Graduation & Postgraduate dominant)

#### Strategic Demographic Insights
#### 🎓 Education & Income
- The customer base is predominantly well-educated and moderately affluent.
- Higher-income customers correlate strongly with higher campaign participation and sales contribution.
#### Business Implication:
Premium-focused campaigns align with the current customer profile.

#### 👨‍👩‍👧 Household Composition
- Majority households have 0–1 child
- Married customers dominate purchasing
#### Insight:
Family-oriented promotions can drive basket expansion.
#### 📈 Age-Based Behavior
- Older segments show higher Wine purchase proportion
- Younger customers display more diversified category engagement
#### Strategic Insight:
Age segmentation should influence product emphasis in campaigns.

### 3️⃣ Purchase Drivers & Key Influencers Analysis
This dashboard leverages Power BI’s Key Influencers visual to determine drivers of:
- Campaign acceptance
- Total sales increase
![Market Research Assignment dashboard_Page_3](https://github.com/user-attachments/assets/b8356b3c-03fa-435c-b57f-dbcc4ac391d5)
#### 🔑 Key Drivers of Campaign Acceptance (Example: Campaign 1)

#### Top Influencers:
- Income > ~$60K → 7.8x more likely to accept campaign
- 0 kids at home → 3.6x likelihood
- Low web visits (≤5/month) → 3.1x likelihood
- 0 teens at home → 1.8x likelihood

#### Interpretation:
Higher-income, smaller households are more receptive to marketing campaigns.

#### 💰 Key Drivers of Increased Total Sales
- Sales increase when:
- Income > ~$67K
- No kids at home
- Low web visits
- No teens at home

#### Senior-Level Insight:
Household size and income are stronger predictors of sales than digital engagement metrics.

#### 🧠 Integrated Strategic Insights

Across all three dashboards, a consistent pattern emerges:
- Revenue is driven by premium products (Wine & Meat).
- High-income customers significantly outperform other segments.
- Smaller households convert more effectively.
- Campaign structure + product mix + channel allocation jointly impact performance.
- Digital channels are under-optimized relative to store performance.

#### 📊 KPI Architecture Implemented
- Campaign KPIs
- Revenue by Campaign
- Purchase Volume
- Campaign Product Mix (%)
- Channel Contribution
- Customer KPIs
- Income Segmentation
- Age Distribution
- Education Level
- Household Composition
- Sales Drivers
- Campaign Acceptance Probability
- Income Threshold Impact
- Household Influence Factors

#### 🏗️ Data Modeling Approach

- Star schema structure
- Fact tables: Sales, Campaign Responses
- Dimension tables: Customers, Products, Channels, Campaigns
DAX measures for:
- Revenue calculations
- Campaign performance metrics
- Segmentation analysis
- Key influencer modeling

#### 💼 Business Value Delivered

This BI solution enables the organization to:
- Identify revenue-driving customer segments
- Improve marketing ROI
- Optimize product promotion strategy
- Personalize campaign targeting
- Make data-driven investment decisions


