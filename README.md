# Retail-Analytics-Dashboard

This repository contains a Power BI dashboard project for Blinkit, a quick-commerce platform specializing in rapid delivery of groceries and essentials. The dashboard consolidates key performance indicators (KPIs) to monitor orders, inventory, delivery, customer feedback, and operational metrics. 

## Problem Statement

Blinkit operates at a large scale, handling high volumes of data on orders, inventory, delivery times, customer feedback, and metrics. Without a centralized dashboard, decision-making is inefficient, leading to operational challenges and reduced customer satisfaction.

**Challenge**: 
- Overwhelming data management for orders, inventory, deliveries, feedback, and revenue.
- Lack of real-time visualization and interactive exploration hinders performance monitoring and optimization.

**Goals**:
1. Visualize KPIs like daily/weekly/monthly orders, delivery trends, inventory status, customer satisfaction, revenue, and profit margins.
2. Support real-time updates, dynamic filtering, and interactive exploration.
3. Provide actionable insights for operational efficiency and customer experience improvements.

**Key Features**:
- Intuitive charts (bar, line, pie, donut, gauge, etc.).
- Drill-down capabilities.
- Filters by time, regions, or categories.
- Export options for reports.

## Interact with the dashboard:

- Navigate pages: Home, Sales Overview, Customer, Feedbacks, Inventory, Marketing.
- Use filters for time (e.g., last 6 months), regions, or categories.
- Drill down on charts for details.
- Export reports as PDF or images.

The dashboard is interactive, with real-time updates if connected to live data sources.

## Analysis Steps

1. **Overview Page**:
- Total Deliveries Over Time (Line Chart): Trends for resource allocation.
- Delivery Completion Rate (Donut Chart): Efficiency insights.
- Revenue Contribution by Regions (Bar Chart): Focus on high-demand areas.

2. **Customer Page**:
- Customer Retention Rate (Gauge Chart): Loyalty program effectiveness.
- Top Customers by Revenue (Table): Prioritize high-value customers.
- Customer Feedback Trends (Word Cloud/Sentiment): Perception analysis.

3. **Marketing Page**:
- Campaign ROI Analysis (Bar/Funnel Chart): Budget allocation.
- Customer Acquisition by Channel (Pie Chart): Channel effectiveness.
- Marketing Spend by Region (Stacked Bar Chart): Regional ROI.

4. **Inventory Page**:
- Stock Levels by Product Category (Bar Chart): Prevent stockouts.
- Inventory Turnover Ratio (KPI Card): Management efficiency.
- Low Stock Alerts (Heatmap/Table): Timely reordering.

5. **Sales Overview Page**:
- Revenue by Product Category (Column Chart): Profitability insights.
- Monthly Sales Trends (Line Chart): Target setting.
- Average Order Value (KPI Card): Upselling opportunities.

Data is visualized with charts, KPIs, and tables, supporting filters and drill-downs.

## Dashboard Visuals

### Home Page
![Home Page](./images/home_page.png)  
*Description: Overview of sales growth, marketing metrics, inventory status, and feedback snippets. Shows quantity for 2025 at 3.82K with -2.30% growth, marketing clicks at 239.37K, and high available stock at 98.22%.*

### Sales Overview Page
![Sales Overview Page](./images/sales_overview_page.png)  
*Description: Payment methods, customer segments, monthly trends, top areas, and products. Highlights Wallet as top payment (32.06K), Regular customers (31.33K), and areas like Ghaziabad leading in quantity.*

### Customer Page
![Customer Page](./images/customer_page.png)  
*Description: Top customers, customer counts by month, and slicers for order analysis. Top customer Ikshita Sarna with 73 quantity; shows customer growth variations and repeat sales at 58.40K.*

### Feedbacks Page
![Feedbacks Page](./images/feedbacks_page.png)  
*Description: Rating distributions, feedback categories, segments, and detailed customer feedback table. Positive feedback at 70.38%, with App Experience and Customer Service each ~25%.*

### Inventory Page
![Inventory Page](./images/inventory_page.png)  
*Description: Stock movement, damaged and available stock, daily trends. Available stock at 469.0K (71.53%), damaged at 109.5K (16.69%), with daily received stock around 65K-79K.*

### Marketing Page
![Marketing Page](./images/marketing_page.png)  
*Description: Marketing value by month and keys, overall clicks, conversions, impressions, revenue, and spend. Clicks at 711.88K, revenue at 711.88K, with slight 0.62% growth in 2025 quantity.*

## Key Findings

- **Sales Overview**:
- Quantity declined slightly from 2024 (61.92K) to 2025 (61.15K, -1.24% growth).
- Top payment: Wallet (32.06K); Top segment: Regular (31.33K).
- Monthly trends show fluctuations (e.g., growth -10% to +10%); Top areas: Ghaziabad, Aurangabad.
- Customer orders: 14K customers ordered >0 times; Repeat: 58.40K sales.

- **Customer Insights**:
- Top customers: Ikshita Sarna (73 quantity), Jack Gandhi (69).
- Customer growth: Varies by month (-20% to 0%).
- Total customers: ~6K new/lost, ~4.5K repeat.

- **Feedbacks**:
- Positive sentiment dominates (70.38%), with App Experience and Customer Service as top categories (~25% each).
- Ratings: High in 4-5 stars (9,446 + 7,211 = ~16.7K), low in 1-2 (688 + 648 = 1.336K).

- **Inventory**:
- Available stock: 469.0K (71.53%), Damaged: 109.5K (16.69%), Received: 546.2K.
- Stock movement: 28.5%; Daily trends show ~65K-79K received.

- **Marketing**:
- Clicks: 711.88K, Conversions: 224.67K, Impressions: 2.88M, Revenue: 711.88K, Spend: 1.02M.
- Slight growth in 2025 quantity (5.38K, +0.62%).
- Trends by day/month, with keys like clicks, conversions, ROAS.

Overall: Slight sales dip but strong positive feedback and inventory health; focus on marketing ROI and customer retention.

## Recommendations

Based on the dashboard insights:

1. **Operations**: Address delivery bottlenecks to improve completion rates; allocate resources for peak days (e.g., Fri/Sat).
2. **Customer**: Enhance loyalty programs for inactive segments (31.04K); use positive feedback in marketing.
3. **Marketing**: Invest in high-ROI channels; analyze underperforming regions.
4. **Inventory**: Monitor low stock alerts; improve turnover for slow-moving items.
5. **Sales**: Promote upselling to increase average order value; target profitable categories and regions like Ghaziabad.


