##Operations SLA Analytics Dashboard

#Project Overview

The Operations SLA Analytics project analyzes customer support ticket data using Microsoft Power BI Desktop. The dashboard provides insights into ticket volume, resolution time, customer satisfaction, ticket status, and Service Level Agreement (SLA) breaches

#Internship

- Organization: Arrowstack
- Project: Project 2 — Operations SLA Analytics
- Tool: Microsoft Power BI Desktop
- Dataset: Customer Support Tickets
- Records: 8,469

#Objectives

- Analyze total, open, and closed support tickets.
- Measure average resolution time.
- Monitor SLA breach count and breach rate.
- Evaluate customer satisfaction ratings.
- Compare ticket patterns by priority, status, channel, type, and product.
- Provide actionable insights to improve support operations.

#Tools and Technologies

- Microsoft Power BI Desktop: Dashboard development.
- Power Query: Data preparation and transformation.
- DAX: KPI calculations and measures.
- Microsoft Excel: Dataset inspection and validation.

#Dataset Fields

The dataset includes fields used for ticket analysis, such as:

- Ticket ID
- Time to Resolution
- Customer Satisfaction Rating
- Ticket Priority
- Ticket Status
- Ticket Channel
- Ticket Type
- Product Purchased

#Key Performance Indicators (KPIs)

1. Total Tickets
2. Closed Tickets
3. Open Tickets
4. Average Customer Satisfaction Rating
5. Average Resolution Time (Hours)
6. SLA Breach Count
7. SLA Breach Rate

#Dashboard Visualizations

- Ticket Count by Status — Donut Chart
- Average Customer Satisfaction by Ticket Priority — Column Chart
- Ticket Count by Product Purchased — Bar Chart
- Average Resolution Time by Ticket Type — Bar Chart
- Ticket Count by Channel — Bar Chart
- SLA Breach Count by Ticket Priority — Bar Chart

#Interactive Filters

The dashboard includes slicers for:

- Product Purchased
- Ticket Type
- Ticket Priority
- Ticket Status
- Ticket Channel

These filters allow users to explore ticket performance across different categories.

#Key Findings

The current dashboard reports:

- Total tickets: 8,469
- Average customer satisfaction: 2.99
- Average resolution time: 12.52 hours
- SLA breach rate: 32.70%
- SLA breach count: Approximately 3K

These values should be interpreted alongside the dashboard filters and measure definitions.

#Data Validation

Validation activities include:

- Checking ticket identifiers for duplicates.
- Reviewing missing customer satisfaction ratings.
- Verifying data types and resolution-time units.
- Checking KPI calculations and chart aggregations.
- Testing slicer interactions.
- Reviewing dashboard readability and layout.

Refer to "Validation_Log.txt" for the detailed validation record.

#Assumptions and Limitations

- The resolution-time conversion assumes the source values are measured in minutes.
- Missing customer satisfaction ratings are excluded from the average, if confirmed by the DAX measure.
- The product chart displays a limited number of products for readability.
- SLA breach results depend on the defined SLA threshold and eligible-ticket population.
- Dashboard results describe observed patterns and do not independently establish the causes of operational issues.

#Project Files

- "operation sla.pbix" — Power BI report (use the actual filename if different).
- "Implementation_Documentation" — Project implementation details.
- "Validation_Log.txt" — Validation checks, results, and assumptions.
- "README.md" — Project overview and usage information.

#How to Use

1. Open the Power BI ".pbix" file in Microsoft Power BI Desktop.
2. Navigate to the Dashboard page.
3. Use the slicers to filter tickets by product, type, priority, status, or channel.
4. Review the KPI cards and charts.
5. Navigate to the Key Insights page to view business recommendations.

#Conclusion

The Operations SLA Analytics dashboard provides an interactive view of customer support performance. It helps users monitor ticket workloads, resolution efficiency, customer satisfaction, and SLA compliance to support data-driven operational improvements.
