# Merchandise-Sales-Dashboard-using-Power-BI

## Merchandise Sales Analysis Dashboard

## Project Background

This project aims to analyze merchandise sales data to uncover key performance trends across product categories, customer demographics, and geographic locations. The goal is to provide actionable insights that help optimize marketing strategies, product offerings, and customer engagement for better business outcomes.

## Dataset Overview
The dataset contains transactional-level records with the following key fields:

- Column	Description
- Order ID	Unique identifier for each order.
- Order Date	Timestamp of when the order was placed.
- Product ID	Unique identifier for each product sold.
- Product Category	Type of product sold: Clothing, Ornaments, or Other.
- Buyer Gender	Gender of the customer (Male/Female).
- Buyer Age	Age of the customer.
- Order Location	City where the order was made.
- Latitude / Longitude	Geolocation data for mapping city-level sales.
- International Shipping	Whether the order was international (Yes/No).
- Sales Price	Base price of the product.
- Shipping Charges	Additional cost for international shipping.
- Sales per Unit	Final unit price including shipping.
- Quantity	Number of units purchased.
- Total Sales	Total revenue for the order.
- Rating	Star rating (1–5) provided by customer.
- Review	Customer review comments (text-based sentiment).

Power BI was used for data modeling, KPI analysis, and dashboard creation to deliver a clear and interactive summary of key business drivers.

## Executive Summary

The merchandise sales analysis covering one year (Nov 2023 to Nov 2024) reveals a total revenue of $856K, with the United States contribut ing the most ($283K), followed by the United Kingdom ($55K). Clothing is the top-selling category, accounting for approximately 75% of sales. 

The core customer segment consists of males aged 21–35, contributing significantly to order volume and revenue. Domestic orders dominate shipping volume, but international cities like Sydney and Mumbai have higher average order values, offering a premium revenue opportunity.

To drive growth, the business should expand high-performing product lines, introduce seasonal bundles, and enhance loyalty initiatives. Strategic use of social media, optimized shipping, and localized campaigns in underperforming regions can boost both customer retention and global sales performance.

## Visualization

<p align="center">
  <img src="https://github.com/user-attachments/assets/5006e9f1-4031-440c-a499-63deaf7d035b" alt="Merchandise Dashboard Page 1" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fa50f33e-5c21-4a25-8d73-b0e761306420" alt="Merchandise Dashboard Page 2" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d336e6af-c1bb-4637-ba4b-572bbabe6da7" alt="Merchandise Dashboard Page 3" width="700"/>
</p>




## Insights Deep-Dive

### 1. Monthly Sales Trend

- Merchandise sales totaled $856K over the 12-month period, averaging $66K per month.
- May 2024 marked the highest-performing month, generating $81K in revenue, largely fueled by strong Clothing sales ($62K).
- In contrast, November 2024 saw a dramatic drop to $10K, suggesting a potential seasonal downturn or missing reporting.
- Between February and September, sales remained stable, consistently ranging between $66K–$77K, reflecting reliable mid-year demand.
- Throughout the year, Clothing led all categories, contributing 65–75% of monthly revenue and significantly outperforming both Ornaments and Other products.
<p align="center">
  <img src="https://github.com/user-attachments/assets/556d6d82-a230-4dcb-a21d-ead414c137c6" alt="Monthly Sales Trend" width="700"/>
</p>

### 2. Key Product Performance

- Clothing emerged as the top-performing category, generating $637K from 6.1K units sold, representing nearly 75% of total sales.
- Ornaments followed with $156K in revenue from 3.8K units, and Other products generated $63K from 2.5K units.
- The top five products by revenue—BF1548 (~$190K), BF1543, BF1550, BF1549, and BF1546—were all from the Clothing category, reinforcing its commercial strength.
- Customer sentiment indicates room for improvement: only 60% of reviews were positive, while 25% were negative and 15% neutral, resulting in an average product rating of 3.5.
- Among product categories, "Other" items had the highest average rating (3.58), followed by Clothing (3.50) and Ornaments (3.45).

<p align="center">
  <img src="https://github.com/user-attachments/assets/57f633a6-3e5c-47f2-9e13-556e6663e9a3" alt="Top 5 Products by Sales" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7857fa20-9750-4ce5-9b0c-66500e4afd38" alt="Customer Review Sentiments" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/2f5d786f-e510-42fe-b35b-9167bfa7673d" alt="Sales by Product Category" width="700"/>
</p>






### 3. Geographic Sales Performance

- The United States was the top-performing country, generating $283K from 5,139 orders and 8,521 units, largely due to strong demand in cities like San Francisco, New Jersey, and Sacramento.
- The United Kingdom followed with $55K in sales, while France reported the lowest revenue at just $8K, signaling underperformance.
- Despite lower volume, Sydney recorded the highest city-level sales ($48K), driven by a high AOV of $261 and $18.4K in shipping charges.
- San Francisco had the highest domestic order quantity (746 units) and generated $41K in sales with $0 shipping cost, reflecting strong local fulfillment efficiency.
- Cities like Mumbai and New Delhi reported solid performance with $38K and $36K in sales respectively, despite higher international shipping fees.
<p align="center">
  <img src="https://github.com/user-attachments/assets/bb4d9aa9-4a28-4b24-b607-825425fe7e9c" alt="City-Level Sales Performance" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e20ebff0-e94e-4b3f-ad59-e1d20e23e50c" alt="Country-Level Sales Table" width="700"/>
</p>




### 4. Shipping Insights

- The majority of volume was fulfilled domestically, with 8,521 units shipped, more than double international shipments (3,813 units), reinforcing a strong domestic base.
- Domestic shipping is free, which may have helped increase conversion and order frequency.
- International orders incur high shipping costs, such as $18.4K in Sydney and $13K in Mumbai, yet these often come with higher-value purchases, evidenced by elevated AOVs.
- Across all markets, Clothing remained dominant, with 4.3K units shipped domestically and 1.8K internationally, indicating consistent demand across regions.
- Ornaments and Other categories followed the same trend—greater sales volumes domestically than internationally.
<p align="center">
  <img src="https://github.com/user-attachments/assets/5ce4f832-d53e-4d32-8e4f-969884a2a4c1" alt="Total Quantity Shipped by Shipping Method" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/42cc6bc1-99f7-4950-950c-2e6b48c5d6af" alt="Shipping Volume by Product Category" width="700"/>
</p>




### 5. Customer Demographics & Segmentation

#### Gender-Based Purchasing Patterns

- Male customers were the dominant revenue driver, accounting for ~$600K (around 70% of total sales), while female customers contributed $256K (30%).
- The data suggests that either marketing resonates more with male buyers, or they tend to purchase higher-ticket items and bundles.

#### Age Group Trends

- The platform’s core customer base falls in the 21–35 age range, with the highest order volume from:
  - 26–30: 2,057 orders
  - 21–25: 2,046 orders
  - 31–35: 2,018 orders
- While younger customers (18–25) show high engagement, older age groups tend to spend more per transaction, especially on higher-value Clothing items.

#### Product Preferences by Age

- Across all age segments, Clothing remains the most preferred category.
- Younger buyers (18–25) also purchase Ornaments and Other items at a slightly higher proportion.
- Older buyers (26–35) prioritize higher-end Clothing products, contributing more to total revenue.
- 
<p align="center">
  <img src="https://github.com/user-attachments/assets/db5fc8c8-bbfa-4624-a27d-6725990b2774" alt="Product Category Preferences by Age Group" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/3b4746e5-d46f-48cb-a8da-0a7b604f78dd" alt="Revenue Contribution by Age Segment" width="700"/>
</p>

### 6. City-Level Customer Behavior

- New Jersey: 434 orders
- Portland: 420 orders
- San Francisco: 414 orders
- These cities contribute significantly to domestic performance, benefiting from free shipping and faster delivery.
- In contrast, international cities like Sydney, Mumbai, and New Delhi placed fewer orders, but had a much higher AOV, balancing overall contribution.
<p align="center">
  <img src="https://github.com/user-attachments/assets/4f17f161-9246-4410-a919-ab64eb7d58d2" alt="City-Level Customer Behavior" width="700"/>
</p>



## Recommendations

### Sales Trend Optimization

- Develop a Seasonal Sales Strategy: Implement targeted campaigns during low-performing months (e.g., November). Leverage holiday periods like Black Friday, Cyber Monday, and Christmas.
- Implement a Year-End Campaign: Launch mid-October promotions with teaser offers and early access. Highlight high-performing categories like Clothing with urgency-driven messaging.
- Run Social Media Campaigns: Target core segments (21–35-year-olds, both genders) across Instagram, TikTok, and Facebook. Promote seasonal bundles and collaborate with influencers.
- Activate Email Marketing Sequences: Deploy teaser → launch → last chance phases with festive visuals and personalized recommendations.
- Introduce Flash Sales + Free Shipping Days: Offer 24–48-hour deals on high-AOV items and provide incentives like "Free Shipping over $75."

### Maximizing Product Offerings

- Expand the Clothing Product Line: Add seasonal collections, premium-tier options, and bundle offers targeted at high-spending groups.
- Improve Product Presentation: Enhance size guides, product descriptions, and imagery to boost perceived value and minimize returns.

### Customer Growth & Segmentation

- Drive Repeat Purchases: Use loyalty data to create exclusive campaigns for existing buyers and launch early access promotions.
- Engage Younger Segments: Use birthday-based rewards and gamified programs to convert first-time customers.
- Capitalize on Male Customers: Bundle high-margin items and tailor campaigns based on male purchase behaviors.
- Enhance Female Engagement: Test promotions that focus on value, style, and giftability to increase engagement.

### Geographic Expansion & Fulfillment Optimization

- Streamline Domestic Shipping: Enable faster delivery in top-performing cities using fulfillment partners.
- Leverage High-AOV International Cities: Offer "Free Shipping Over $X" in high-value regions like Sydney, Mumbai, and New Delhi.
- Explore Underperforming Markets: Analyze low-performing regions like France and test region-specific ads, bundles, or product adjustments.

# Contact
For any questions or inquiries, please contact evitanegara@gmail.com

