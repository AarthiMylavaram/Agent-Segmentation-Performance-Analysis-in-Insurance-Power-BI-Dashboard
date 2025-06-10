Agent-Segmentation-Performance-Analysis-in-Insurance-Power-BI-Dashboard
The objective of this project is to analyze and improve the performance of independent insurance agents using a supervised predictive framework. The dashboard enables segmentation based on key performance indicators such as growth rate, hit ratio, retention ratio, and product line activity. This empowers stakeholders to identify top-performing agents, quote system efficiency, and areas needing strategic improvement.
 Tools & Technologies Used:
•	Power BI Desktop
•	Power Query Editor
•	DAX (Data Analysis Expressions)
•	Microsoft Excel (Data Source)
 Key Metrics Computed:
•	Hit Ratio = Bounds / Quotes (for each quote system)
•	Retention Ratio = Retained Policies / In-force Policies
•	Growth Rate (3Y) = ((Current Premium - Previous Premium) / Previous Premium) * 100
•	Agent Segmentation based on Growth and Retention Binning (High, Medium, Low)
 Dashboard Visuals:
1.	Summary Table by Agency:
Displays total premium, new business premium, policy count, retention ratio, and average hit ratio per agency.
2.	Product Line Analysis:
Visual comparison of premium distribution between Commercial Lines (CL) and Personal Lines (PL).
3.	Retention Ratio – Agency & State:
Bar chart highlighting agencies and states with the highest client retention performance.
4.	Hit Ratio by Quote System (PL/CL):
Clustered column chart comparing hit ratios across various quote systems like MDS, eQT, APPLIED, etc., split by product line.
5.	Trend Analysis (2006–2013):
Line chart showing premium growth over the years.
6.	KPI Cards:
At-a-glance metrics such as average hit ratio, average retention ratio, and year-over-year growth.
Segmentation Logic:
•	Growth Band:
o	High: Growth ≥ 10%
o	Moderate: 0% ≤ Growth < 10%
o	Negative: Growth < 0%
•	Retention Band:
o	High: Retention Ratio ≥ 0.85
o	Medium: 0.6 ≤ Retention < 0.85
o	Low: Retention < 0.6
These bands are used in slicers and filters to drill down into specific agent groups.
Outcome & Benefits:
•	Enabled clear visibility into agent performance across states and years.
•	Identified high-performing quote systems for targeted investment.
•	Facilitated data-driven segmentation for training, support, and strategic planning.
•	Created a reusable framework for predictive agent scoring models.
Conclusion:
This Power BI dashboard provides a powerful analytical layer for insurance management teams to monitor, compare, and improve agent performance. Through intuitive visuals and dynamic filters, it supports informed decision-making and contributes to improved customer retention, system utilization, and business growth.

