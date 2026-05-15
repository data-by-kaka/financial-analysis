# Financial Performance Analysis
## Project Overview
The Financial Performance Dashboard provides a comprehensive analysis of a company’s financial health by tracking revenue growth, profitability, cash flow, and working capital efficiency.
It enables stakeholders to monitor monthly trends, compare performance against budgets, and evaluate product/service profitability across different regions and timeframes.

### Tools Used
- Power BI – Dashboard design, KPI calculation, and visualization
- Excel – Data cleaning, transformation, and modeling
- DAX – Custom measures for financial KPIs
- Power Query – Data loading and shaping
 
### Objective
To analyze and visualize the company’s financial performance over time, focusing on:
- Revenue growth trends
- Gross profit and EBITDA margins
- Budget vs actual performance
- Cash flow movement
- Product/service-wise revenue distribution
- Receivables efficiency

### Dataset Description
The dataset includes the following key components:
1. Financial Metrics
   - Revenue
   - Cost of Goods Sold (COGS)
   - Gross Profit
   - Operating Expenses (Opex)
2. EBITDA
   - Cash Flow
   - Cash Inflows
   - Cash Outflows
   - Net Cash
3. Sales Data
   - Product/Service
   - Region
   - Month
4. Working Capital
   - Receivables Aging (Days)
   - Payables Aging (Days)
5. Budgeting
   - Revenue Budget
   - Budget Variance (%)

### Data Modeling
A Date Table was created to enable time-based analysis.
Key Features:
- Year, Quarter, Month hierarchy
- Year-Month format for trend analysis
- Relationship established between DateTable and Dataset

### Data Cleaning 
- Ensured all date fields are properly formatted for time intelligence
- Created calculated columns for aging buckets
- Handled missing values where necessary

### Dashboard Features
1. KPI Cards
   - Total Revenue
   - Gross Margin %
   - EBITDA %
   - Net Cash

2. Revenue & Profit Trend
Line chart showing:
   - Revenue
   - Gross Profit
Monthly trend analysis
3. Budget vs Actual
   - Variance analysis (%)
   - Helps track financial performance against targets
  
4. Cash Flow Waterfall
   - Visualizes:
   - Cash Inflows
   - Cash Outflows
   - Net Cash position
   - Receivables Aging
- Categorized into buckets:
   - 0–15 days
   - 16–30 days
   - 31–45 days
   - 46–60 days
Helps monitor collection efficiency

### Interactivity
The dashboard includes:
- Date range slicer (Month / Quarter / Year)
Filters:
- Region
- Product/Service
- Drill-down capabilities for deeper insights

### Key Insights 
- Revenue Growth: Steady month-over-month increase with December peaking due to strong product demand.
- Profitability: Gross Margin (45.55%) indicates efficient cost control; EBITDA Margin (24.81%) shows room for operational optimization.
- Cash Flow: Consistent increase in net cash indicates healthy liquidity and disciplined expense management.
- Product Performance: Product C and Service X are top performers; Product A and Service Y show potential for growth.
- Working Capital: Receivables collected within 26–31 days, reflecting efficient cash management.

### Recommendations
1. Optimize operational costs to improve EBITDA margins.
2. Reinvest surplus cash into high-performing products and regions.
3. Focus on cost control for underperforming services.
4. Continue maintaining a 30-day receivables cycle for liquidity stability.

### Conclusion
The dashboard provides a clear, data-driven view of the company’s financial status, empowering decision-makers to track performance, optimize costs, and plan for sustainable growth. It effectively visualizes financial KPIs and delivers actionable insights into profitability, liquidity, and operational efficiency.

## Dashboard Overview
![Dashboard Preview](https://github.com/data-by-kaka/financial-analysis/blob/main/Image/Financial-image.png)

