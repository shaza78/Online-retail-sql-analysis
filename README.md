Online Retail Sales Analysis

Tools: SQL (DB Browser for SQLite), Excel
Dataset: Online Retail, 541,909 rows, Dec 2010 to Dec 2011

Cleaning

- 135,080 rows with blank CustomerID (guest checkouts, kept)
- 5,429 exact duplicate rows (noted, not deleted; used SELECT DISTINCT in queries)
- 1,719 rows with negative Quantity (returns, excluded)
- 38 countries, date formats consistent

Key findings

- Total revenue: £8,911,407.90
- Top product: Paper Craft Little Birdie, 80,995 units
- Top country: UK at £7,308,391.55, then Netherlands, EIRE, Germany, France
- 2,845 repeat buyers out of ~4.3k unique customers

Charts

- top-10-products-by-units-sold.png
- revenue-by-month.png (peak in Nov 2011 at £1.51M)