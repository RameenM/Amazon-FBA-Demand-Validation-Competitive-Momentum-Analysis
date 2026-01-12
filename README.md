# Amazon FBA Demand Validation and Competitive Momentum Analysis

## Project Overview

This project evaluates the demand and competitive momentum of an Amazon FBA product to assess whether it is suitable for small-batch testing or scalable investment. It focuses on demand validation by examining sales stability, momentum, and competitive behavior while keeping other factors such as advertising, cost structures as null. Patter-based analysis with the support of Power BI is used to evaluate future product opportunities. 

## Product Context
For this project, the following product was used: 
- **Product:** VORA 2-Tier Spice Organizer for Cabinets  
- **ASIN:** B0DK724BZP  
- **Data Source:** Helium 10 (third-party estimates)

---

## Product Selection Logic

A moderately reviewed product was selected with approximately 200 reviews. This is because high review product reflects:  

- Fully established demand  
- Strong seller dominance  
- Outcomes driven primarily by brand trust and historical performance  

Altogether, these factors reduce opportunities for learning, testing or strategic differentiation which is essential for a new business. 

In contrast, products with lower but non-trivial review counts exhibit observable demand while remaining analytically informative. Sales patterns, ranking movement, and competitive shifts remain visible, allowing for clearer assessment of whether demand is emerging, stabilizing, or declining. This context is more suitable for small-batch testing and incremental scaling decisions.

Prior to analysis, additional validation checks confirmed that:

- Product ratings were positive  
- ASIN-level sales were increasing  
- Parent-level category sales were also trending upward  

Rising ASIN sales indicate preference for the specific product variant, while parent-level growth suggests expanding interest in the broader product category.

---

## Data Sources and Analytical Use

### Sales Estimation Data

Sales estimation data was obtained from Helium 10 and Alibaba and includes estimated daily units sold, listing price, and derived revenue values. Approximately 30 days of daily data were analyzed. These estimates are not treated as precise measurements but are used to identify consistency of purchases and demand trends. 

### Best Seller Rank (BSR) Data

BSR data provides a relative measure of product performance within its competitive environment. Between 30 and 90 days of BSR data were used to evaluate whether sales activity translated into improved competitive positioning within primary and subcategory. It is important to note here, however, that for this research only subcategory BSR data was used during the analysis. This is because sales fluctuations are more visible since the comparison is across similar BSRs. In the primary category this momentum would be slower.  

---

## Visual Analysis Overview 

### Daily Units Sold Trend

The daily units sold visualization shows a clear upward shift in baseline demand over time. Early observations remain around 10–16 units per day, while later values consistently reach 17–22 units, with multiple peaks approaching or exceeding 25 units per day. Despite normal daily volatility, there are no extended low-demand periods, indicating sustained and repeatable demand rather than isolated spikes.


### Estimated Revenue Trend

Estimated revenue increases alongside unit sales and does not exhibit prolonged flat or declining periods. The alignment between rising unit volume and rising revenue indicates that sales growth is not driven solely by aggressive price discounting, reinforcing the conclusion that demand growth is economically meaningful.


### Price vs. Units Sold

Estimated revenue rises alongside unit sales and does not show extended flat or declining periods. This indicates that higher sales volumes are generating higher revenue, suggesting that demand growth is not solely driven by price reductions and reflects economically meaningful demand.

### Weekly Subcategory BSR Trend

The subcategory BSR moves within a broad range and shows frequent ups and downs. Periods of improvement are often followed by declines, indicating active competition. This suggests that while the product can generate sales, competitive pressure in the market remains strong and ongoing.

### Sales and BSR Momentum Alignment

When weekly sales are compared with weekly subcategory BSR, higher sales do not always lead to better rankings. Some weeks show strong sales while rankings remain unchanged or decline. This happens because sales measure how much the product sells on its own, while BSR reflects how it performs relative to competitors. The mismatch shows that competition is increasing and absorbing part of the demand growth, not that demand is missing.

### 7-Day Rolling Average Demand

A seven-day rolling average calculates the average sales over the most recent seven days, updating this value each day. This smooths out normal day-to-day fluctuations and highlights the underlying demand trend. After applying this smoothing, demand remains consistently higher and does not return to earlier low levels, indicating that the increase in demand is sustained rather than driven by short-term noise.


### Average Daily Demand (Last 14 Days)

The final validation metric shows an average daily demand of **19 units sold** over the most recent 14-day period. This value is materially higher than early-period averages and confirms that demand remains active in the current period. The metric serves as a decision checkpoint by translating historical trends into a clear, current indicator of demand stability.

---

## Final Interpretation and Conclusion
The analysis shows that demand for the product is consistent and remains higher over time, with customers purchasing regularly rather than in short-lived spikes. At the same time, the BSR analysis indicates that competition limits how much this demand translates into ranking improvements, as stronger sales do not always lead to better rankings.
Overall, the product demonstrates real demand but operates in a competitive market. Demand momentum is present, even though competitive pressure affects visibility and ranking.
Based on these findings, the product is a good candidate for small-batch inventory testing. This approach allows new or risk-conscious FBA sellers to confirm demand and observe competition before investing significant capital, supporting a cautious test-and-learn strategy rather than immediate large-scale scaling.

---

## Limitations

- Sales and revenue figures are based on third-party estimates rather than audited transaction data  
- The analysis focuses on a single product and a limited time window  
- Longer-term seasonality and structural market shifts may not be captured  
- Advertising activity, inventory constraints, and external market factors are not explicitly modeled  
- Findings support directional decision-making rather than precise forecasting or guaranteed outcomes  
