# Maven Market Sales Dashboard

An interactive Power BI dashboard that analyzes retail sales, profitability, and transaction patterns for Maven Market, a multi-country grocery retailer (USA, Mexico, Canada).

<img width="1331" height="741" alt="MavenMarket" src="https://github.com/user-attachments/assets/6c86130c-995f-4e8e-ade1-962dd324e20f" />

## Key KPIs

| KPI | Value |
|---|---|
| Total Revenue | 1.59M |
| Total Profit | 876.36K |
| Total Transactions | 270K |
| Profit Margin | 55.18% |
| Overall Return Rate | 0.99% |

## Key Insights

1. **Strong growth in 1998:** 1998 revenue was 1.08M (68% of the total) versus 0.51M in 1997 (32%), roughly 2x higher.
2. **Transactions are concentrated in the US West Coast:** Washington (87K), California (51K), and Oregon (43K) together account for about two-thirds of all transactions. Mexican states and British Columbia contribute the rest.
3. **Profit is stable, with a year-end peak:** Monthly profit stays around 70K for most of the year and rises in November and December (the highest month, December, is close to 88K), with a dip in October.
4. **Top brands by profit:** Hermanos (27.5K), Ebony (24.8K), and Tell Tale (24.8K) lead the ranking. Profit margins across the top brands stay between roughly 53% and 57%, and return rates are close to 1%.

## Dashboard Components

- **KPI cards:** Total Revenue, Total Profit, Total Transactions, Profit Margin
- **Sales by Year / Revenue by Year:** year-over-year comparison
- **Product Analysis table:** brands ranked by Total Profit, with Profit Margin and Return Rate
- **Transaction by Location:** treemap of transactions by state/province
- **Profit by Month:** monthly profit trend

## Tools & Techniques

- **Power BI** for report design and interactive visuals
- **Power Query** for data cleaning and transformation
- **DAX** for calculated measures (Revenue, Profit, Profit Margin, Transactions, Return Rate)
- Relationships between the transactions table and the products table.

## Data Source

[Kaggel]

