# Inscribed-Sales-Performance-Analysis
 **Tools Used:**  <img src="https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white" alt="Excel Skill Badge"> [Pivot Tables, Charts, Timeline, Slicers]
## Introduction
Inscribed, a retail company with physical stores across the United States, is preparing for expansion. The sales team asked for a dashboard that could summarize sales performance at a glance and provide insights to guide strategic decisions. Their questions were clear: What is the summary of sales? How have sales patterns evolved over time? Which customers make the most purchases? Which regions or states represent strongholds? Which product categories generate the most revenue?
This documentation gives insight into how those questions were answered, weaving together KPIs, trends, and breakdowns into a narrative that highlights Inscribed’s growth journey and the way forward for the business.


### Core Purpose
The aim of this project was to design a dashboard that translates raw sales data into actionable insights. By focusing on sales patterns, customer segments, regions, and product categories, this analysis equips the sales team to decide where best to expand, which products to prioritize, and how to improve the business.

## Outline
-	Methodology
-	Analysis
-	Key Insights
-	Recommendations
-	Conclusion

## Methodology
**Data preparation:** Cleaned the dates in the dataset ensuring the date columns had the right datatype, removed irrelevant fields from the dataset, and built a Date Table for YOY analysis.

**Pivot construction:** Monthly revenue, orders, quantity, discount, product categories, customer segments, and regions.

**Added Measures:** Defined KPIs (Revenue, Profit, Orders, Discount, Quantity) and YOY metrics.

**Dashboard design:** Balanced detail with readability, using KPI cards for quick insights and charts for context.

**Validation:** Cross‑checked totals across pivots to ensure consistency.


## Analysis
<img src="Images/Inscribed dashboard overview.png" alt="Inscribed dashboard overview">

The analysis of Inscribed’s sales performance data focuses on several Key Performance Indicators (KPIs) that highlight trends across overall revenue growth, purchasing behavior by customer segments, product category contributions, and regional strongholds. These measures provide a clear view of how sales have evolved over time, which types of customers drive the most purchases, and where geographic opportunities for expansion exist. By combining time‑series comparisons with category and segment breakdowns, the dashboard delivers a concise yet comprehensive overview of Inscribed’s business trajectory. 

### Performance Analysis

##### 1. Key Performance Indicators (KPIs)
<img width="726" height="1061" src="Images/Insp-yearly KPI.png" alt="Yearly KPI">

Answering the first question posed by the sales team, the following KPIs summarize the company’s sales performance across 2012, 2013, and 2014.
Headline KPIs show the company’s overall trajectory:
- 2012: Revenue $470.53K, Orders 1,038, Quantity 7,979.
- 2013: Revenue $608.47K, Orders 1,310, Quantity 9,810.
- 2014: Revenue $1.22M, Orders 2,661, Quantity 20,084.
  
**Insight:** Analysing 2013 vs 2012, Revenue ▲29.3%, Orders ▲26.2% showcases a significant increase compared to 2012.
This confirms steady growth, with 2013 as the turning point.

#### 2. Sales Patterns Over Time
For the second query, "Pattern of sale Over Time",the time series pivots reveal the rhythm of growth:
- 2012 vs 2011: Revenue ▼2.8%, Orders ▲7.1%.
- 2013 vs 2012: Revenue ▲29.3%, Orders ▲26.2%.
- 2014 vs 2013: Revenue ▲20.6%, Orders ▲29.2%.
  
**Insight:** Monthly trends show that 2013’s uplift was broad‑based, with strong increases in February, May, October, and December. This uplift was not a seasonal spike but shows a structural shift in strategy.

#### 3. Customer Segments 
<img width="926" height="661" src="Images/By CX-CAT.png" alt="Customer Segment">

This gives insight into the question "What kind of customers make the most purchases"
Customer breakdown reveals who drives sales:
- 2012: Consumers $266.5K, Corporate $128.8K, Home Office $75.2K.
- 2013: Corporate surged to $206.9K (+61%), Home Office rose to $105.2K (+40%), Consumer grew to $296.3K (+11%).
- 2014: Consumers remained largest ($332.5K), but Corporate expanded to $242K and Home Office to $159.5K.

**Insight:** Consumers segment remain largest, but Corporate growth was the standout driver in 2013, diversifying the customer base.

#### 4. Product Categories

To find out which product categories make the most sales, category pivot table was created to reveal the the backbone of revenue:
- 2012: Furniture $170.5K, Technology $162.8K, Office Supplies $137.2K.
- 2013: Technology $226.1K (+39%), Office Supplies $183.5K (+34%), Furniture $198.9K (+17%).
- 2014: Technology $272K, Office Supplies $246.5K, Furniture $215.4K.

**Insight:** Technology and Office Supplies overtook Tthe Furniture category in 2013 and cemented their lead in 2014.

#### 5. Regional Breakdown 
<img width="726" height="461" src="images/Cases across ptnts.png" alt="Case severity across patients">

Lastly, to find out which regions/states have strongholds or large customer bases
Regional pivots highlight geographic strengths:
- 2012: East $156.3K, West $140K, Central $102.9K, South $71.4K.
- 2013: East $180.5K (+15%), West $187K (+34%), Central $147.4K (+43%), South $93.5K (+31%).

**Insight:** East remained largest, but Central and West showed the fastest growth, especially in Corporate sales, marking them as strongholds for expansion.


## Key Insights
The anomaly in 2013 was not a random spike but a structural turning point in Inscribed’s business trajectory. Several interconnected factors explain this shift:
- Broad based monthly growth:
Revenue increases were spread across multiple months (February, May, October, and December) which all showed significant gains compared to 2012. This indicates that growth was sustained throughout the year rather than concentrated in a single season, reflecting stronger demand patterns and improved sales execution.
- Product mix shift toward Technology and Office Supplies:
Technology sales rose by 39% and Office Supplies by 34%, overtaking Furniture as the leading categories. This shift suggests customers were increasingly drawn to higher value and more frequently purchased items, positioning Inscribed to capitalize on categories with stronger long term potential.
- Customer diversification:
Corporate revenue surged by 61% and Home Office by 40%, while Consumer growth was more modest at 11%. This diversification reduced reliance on the Consumer segment and broadened the customer base, strengthening resilience and opening new avenues for expansion.
- Regional strength in Central and West:
The Central region grew by 43% and the West by 34%, outpacing the East and South. These regions became new strongholds, particularly for Corporate sales, highlighting geographic opportunities that were previously underdeveloped.

Together, these factors show that 2013 marked a strategic inflection point. Inscribed was no longer simply growing incrementally; it was reshaping its business by selling more high value products, reaching new customer segments, and expanding into regions. This strategy was carried into 2014, where growth continued across categories, customers, and geographies, confirming that the company had entered a new phase of sustainable expansion.


## Recommendations
- Product Strategy: Inscribed should place deliberate emphasis on Technology and Office Supplies, which consistently outperformed Furniture and became the company’s growth engines. Technology, in particular, showed the strongest trajectory, rising from $162K in 2012 to $272K in 2014.
- Strengthen Other Segments: While Consumers remain the largest segment, the Corporate and Home Office segments demonstrated the fastest growth, with Corporate expanding by 61% in 2013 alone. Strengthening these segments will diversify the customer base and reduce reliance on Consumers.
- Regional Strategy: The Central and West regions emerged as new strongholds, showing growth rates of 43% and 34% respectively in 2013. By investing in store presence, marketing, or partnerships in these geographies, Inscribed can capitalize on momentum and establish dominance in areas where competitors may be weaker.
- Seasonality: Revenue peaks in Q4, especially November and December. Planning promotions and campaigns towards this quarter can be a strategic window where the company can capture disproportionate gains.
- Replication: Replicating the conditions that helped drive a boost in performance in 2013, whether through product bundling, regional targeting, or segment‑specific campaigns will help sustain growth in future years.


## Conclusion
This analysis provides clear answers to the sales team’s core questions:
- Summary of sales: Revenue grew from $470K in 2012 to $1.22M in 2014, showing a strong upward trajectory.
- Pattern over time: 2013 was the turning point, with broad‑based growth that carried into 2014.
- Customers: Consumers remain the largest segment, but Corporate growth is the standout driver, reshaping the customer base.
- Regions: The East remains the largest, but Central and West are the fastest‑growing strongholds, offering new expansion opportunities.
- Products: Technology and Office Supplies overtook Furniture to become the leading categories, driving sustained growth.

Taken together, these insights confirm that Inscribed’s growth is structural, not seasonal. The company did not simply start selling more of the same products to the same customers in the same regions, it diversified across categories, broadening its customer base, and expanding geographically.
By focusing on Technology and Office Supplies, strengthening Corporate and Home Office segments, and investing in Central and West regions, Inscribed can replicate the success of 2013 and build a foundation for sustainable expansion. This analysis does more than report numbers; It equips the sales team and leadership with the right information to make confident, strategic decisions about the company’s next chapter.


