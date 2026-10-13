Olist E-Commerce Exploratory Data Analysis

This notebook performs a complete exploratory data analysis (EDA) on the Brazilian Olist e-commerce dataset using SQLite for query processing and Matplotlib / Pandas for data visualization.
Tech Stack & Methodology
Database: SQLite
Data Manipulation: Pandas
Visualization: Matplotlib
Filter Standard: order_status = 'delivered' (ensuring data integrity by evaluating completed transactions only).
Key Business Insights
1. Monthly Sales Trends
Finding: Revenue shows a steady upward trajectory with sharp seasonal peaks in Q4 (Black Friday and holiday period).
Impact: Order volume directly drives revenue spikes, requiring proactive inventory and server scaling ahead of peak sales months.
2. Geographical Performance (Top States)
Finding: Sao Paulo (SP) is the dominant market, driving over 40% of total revenue, followed by Rio de Janeiro (RJ) and Minas Gerais (MG).
Impact: Logistics infrastructure and targeted marketing efforts should remain concentrated in the Southeast region for maximum ROI.
3. Delivery Performance: Actual vs. Estimated
Finding: Actual delivery times average around 12 days, whereas initial estimates provided to customers average around 23 days.
Impact: While under-promising protects customer trust, overestimating delivery times by a wide margin may lead to cart abandonment at checkout.
4. Payment Installments & Order Value
Finding: Orders paid in 5 to 10 installments account for significantly higher Average Order Values (AOV) compared to single-payment orders.
Impact: Offering flexible, interest-free installment options directly incentivizes higher basket values for expensive item categories.
5. Review Scores vs. Delivery Delays
Finding: Customer satisfaction is heavily tied to delivery promptness. 1-star reviews correlate strongly with positive delay days (late deliveries), while 5-star reviews correlate with early fulfillment.
Impact: Logistics delay tracking must be automated to flag at-risk orders before delivery deadlines pass to protect platform rating.
6. Product Category Revenue vs. Freight Cost
Finding: High-revenue categories like Health & Beauty and Bed, Bath & Table enjoy low relative freight costs, whereas bulky categories like Furniture incur high freight fees.
Impact: Negotiating bulk shipping rates for heavy goods is critical to reducing customer drop-off during checkout.
