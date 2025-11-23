# Project Overview
This Power BI project analyzes global e-commerce sales data for a software retailer that sells subscriptions and add-ons across analytics, design, collaboration, and AI products. The dashboard helps identify loyal customers, revenue drivers, product performance, and the impact of promotions and discounts.
It provides actionable insights for business strategy, marketing, product management, and customer retention initiatives.

# Objectives
Identify loyal (repeat) customers and track their behavior over time.
Determine which channels and promotional campaigns drive repeat purchases.
Analyze sales trends, revenue contribution, and product performance.
Examine refund hotspots by product and channel.
Assess the impact of discounts and pricing on sales and repeat purchases.
Deliver a dynamic, slicer-driven Power BI dashboard with KPIs and visualizations.

# Dataset
The dataset includes the following tables:
1.	Events Table – captures all transactional events. Columns include: event id, event type, event date, customer id, product id, country, region, channel, payment method, currency, quantity, unit price local, discount local, discount code, tax local, net revenue local, fx rate to usd, net revenue usd, is refunded, refund datetime, refund reason.
2.	Products Table – product details such as product id, product category, billing cycle, product name.
3.	Customers Table – customer details such as customer id, age, region and segment. Dashboard Pages & KPIs

### 1. Sales Page: Overall sales performance, revenue trends, and discount impact.

KPIs:
Total Revenue (USD) - 31.8 million

Total Orders - 48,000 orders

Total Quantity sold - 289,000 

Average Order Value - 658

Discount impact % - -6.71

### 2. Customers Page: Customer behavior, loyalty, retention, and repeat rates.

KPIs:
Total Customers - 4001

Repeat/Loyal Customers - 4000

Repeat Rate (%) - 100

Median Days to second purchase - 31 days

Revenue from loyal customers (%) - 100

### 3. Products Page: Product-level performance, pricing, attach rate, and refunds.

KPIs:

Quantity Sold - 289,000

ASP (Average Selling Price) -$110

Refunds Rate (%) - 2.09

# Insights & Analysis Questions Answered
1.	Sales Trends: Sales show **strong early-year momentum**, rising from **January and peaking between April-June**. This period records the **highest MoM growth and 
the strongest revenue volumes**. From **July onward, growth plateaus and gradually declines, with the sharpest contractions in November and December**.
This indicates **seasonal demand**, mid year campaigns working well and an opportunity to strengthen end-of-year promotions.

2.	Channels: **Website** drive the bulk total Revenue and the Repeat customer activity is concentrated there and on **Direct Sales**, which show the highest loyalty
rates. Theses channels attract customers who are moe satisfied and likely to repurchase without discounts. Lower performing channels (Marketplace, Partners) may require 
better pricing, positioning or targeted promotions.

3.	Customer Loyalty: Loyal customers consistently contribute **40-70%** of monthly Revenue (varies by month). The share **peaks during mid-year boom**, highlighting 
that retention, not acquisition, drives revenue growth.

4.	Loyal/Repeat customers gravitate towards **Team seats Add-on monthly, Microsoft copilot for office Annual pro, Freshdesk growth Annual, and Microsoft copilot for 
office Annual**. These products typically integrate deeply into workflow, have annual plans and include bundled add-ons. These offerings create long-term stickiness.

5.	Discount Impact: Codes like **BFCM20, WELCOME10, NEWCUSTOMER10, BFCM10, SAVE5** drive the highest usage an much higher repeat rate. **LOYALTY15** drive acquisition,
but repeat rates are lower.

6.	Average Selling Price: ASP varies significantly by countries and thier currencies, **Germany, Netherland, Spain maintains the highest ASP due to EUR pricing**,
followed by **UK's and Australia's GBP and AUD**, while **USD has the lowest ASPs** due to larger customer volume and stronger pricing competition.

7. Refund: Most refunds are driven by sales **channel** and not product issues. Channels see a **2%** Refund rate, while individual products average just **0.03%**,
indicating high product satisfaction and highlighting the need for better channel onboarding.

8. Customers return for a second purchase within **31 days** on average, indicating strong early product adoption.

9. Add_Ons: **Team Seats Add_on Monthly, Zoom whiteboard Add_on Annual, Team Seats Add_on Annual, AI Annalytics Add_on Monthly, and Advanced Report Add_on Monthly**
are the most frequently paired with core products, showing the highest attach rates.

10. **Annual Plans** deliver **significantly higher revenue per customer** while **monthly plans domiinate in quantity sold**. Boyh plans generate the highest attached
Add_on orders, showing strong cross-sell opportunities across subscription types.

## Conclusion
This dashboard provides a complete view of sales, customer loyalty, product performance, and discount effectiveness. It is interactive, dynamic, and slicer-driven, enabling stakeholders to make data-driven decisions that improve revenue, retention, and product strategy.
