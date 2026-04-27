# Coffee-Store-Data-Analysis (Interactive Dashboard using MS Excel)
I developed a comprehensive Excel project, creating an interactive dashboard to visualize the data of a coffee shop. Used XLOOKUP, INDEX/MATCH, nested IF functions among others to clean and enrich 1,000 orders spanning four years (2019–2022). Translated data into business insights to help strategic decision making. 
The dashboard visualizes Total Sales Over Time, Sales By Country and Top 5 Customers. Timelines and multiple Slicers facilitate business outcome analysis.

## Project Objective
To analyze four years of coffee shop sales data and identify growth opportunities, customer value drivers, and geographic market performance. Use the raw data to get to clear, strategic outcomes for business stakeholders.

## Business Questions
- Which coffee type generates the most revenue?
- Which markets (countries) are driving sales?
- Who are the highest-value customers, and what does their spending behavior reveal?
- How does loyalty card membership correlate with purchasing patterns?
- Are there seasonal trends in sales that the business should plan around?

## Project
- **Data source:** 1,000 orders across three linked tables: orders, customers, and products
- **Data enrichment:** Used XLOOKUP to pull customer name, email, country, and loyalty status from the customers table into the orders table; used INDEX/MATCH and nested IF functions to decode coffee type and roast type abbreviations into readable labels
- **Pivot tables & charts:** Built three analysis sheets: Total Sales (line chart over time by coffee type), CountryBarChart (bar chart of sales by country), and Top5Customers (bar chart of top spenders)
- **Interactive dashboard:** Assembled all visuals on a single Dashboard sheet with a Timeline (date filter) and Slicers for roast type, package size, and loyalty card status to enable flexible exploration

## Dashboard
<img width="862" height="468" alt="ScreenshotDashboard" src="https://github.com/user-attachments/assets/e6c9241e-158d-4de1-9c16-baec8a3d9f17" />

## Business Insights
- **Coffee type performance:** Excelsa leads revenue at $12,306, closely followed by Liberica ($12,054) and Arabica ($11,768). Robusta generates least revenue, at $9,005, which means there might be lower demand or a higher pricing opportunity.
- **Geographic insights:** The United States dominates with $35,639 (79% of total sales), while Ireland ($6,697, 15%) and the United Kingdom ($2,799, 6%) are significantly smaller markets. The US is the main revenue driver, but Ireland with a smaller population shows relative strength.
- **Customer value:** The top 5 customers (Allis Wilmore, Brenn Dundredge, Terri Farra, Nealson Cuttler, Don Flintiff) collectively account for $1,473 in sales. $1,473 out of $45,134 total sales is **3.27%**. This shows the business does not rely much on a handful of customers, but has a very broad customer base with low customer retention rate.
- **Loyalty card adoption:** 48% of customers hold a loyalty card. This presents a gap that could be addressed. But let’s see if the loyalty card is worth it in itself: I found that the card makes no measurable difference to behaviour at all. Non-loyalty card holders and loyalty card members result in a relatively similar sales revenue. Therefore the loyalty card isn't clearly driving higher spend.
- **Time trends:** Sales data spans 2019–2022. I found that changes from month to month are very large and inconsistent. When comparing the same months over different years it shows that there is also no clearly repeating seasonal pattern in the data.

## Findings & Recommendations
- Focus on the US market while developing targeted campaigns for Ireland, for its strong potential.
- Promote Excelsa and Liberica as premium lines given their revenue leadership.
- Redesign loyalty card, as the loyalty program now shows no measurable impact. The programme needs to be rethought with stronger incentives, such as rewards based on spending or exclusive products for members, to give customers a real reason to return.
