Pizza Sales Analysis Dashboard (Power BI)
Overview

A Power BI dashboard built to analyze a year of pizza sales transaction data (48,620 orders) and answer three specific business questions using appropriate chart types for each.

Questions Answered
Which pizza category generates the most sales?
Which pizza size sells the most pizzas?
How do pizza sales change throughout the year?

Tools Used
Power BI — data import, modeling, and visualization
Dataset: pizza sales transaction data (order ID, date, pizza name, category, size, unit price, quantity, total sales)
Approach

For each question, I selected a chart type suited to the kind of comparison being made, rather than defaulting to one visual for everything:

Question	Chart Type	Why
Category → total sales	Clustered Bar Chart	Best for comparing a small number of discrete categories side by side
Size → quantity sold	Donut Chart	Shows proportion of total volume each size represents
Sales → time of year	Line Chart	Best for showing a trend across a continuous variable (time)
Key Findings
Classic pizzas generated the most total revenue ($220,053), narrowly ahead of Supreme ($208,197), Chicken ($195,920), and Veggie ($193,690) — the four categories are closer in performance than expected, with only about a 12% gap between the top and bottom category.
Large (L) pizzas were the best-selling size by volume (18,956 units sold), followed by Medium (15,635) and Small (14,403). Extra-large sizes (XL, XXL) made up a small fraction of total volume (under 2% combined).
Sales stayed fairly consistent across the year (ranging roughly $64K–$72K per month), with a peak in July ($72,558) and the lowest month in September ($64,180) — no single month dramatically outperformed the rest, suggesting steady, non-seasonal demand rather than sharp spikes.

What I'd Explore Next
Break down sales by day of week and time of day (the dataset includes order_time) to see if there are predictable ordering patterns
Analyze which specific pizzas (not just categories) are the strongest and weakest performers
Look at average order size (pizzas per order) to understand customer ordering behavior
Skills Demonstrated

Data import & modeling, chart type selection based on the analytical question being asked, aggregation and trend analysis, translating raw transactional data into business-relevant insights.
