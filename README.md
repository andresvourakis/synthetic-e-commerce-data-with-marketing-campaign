# Synthetic E-commerce Data with Marketing Campaign

**Description:**
This dataset contains synthetic transactional data for a fictional e-commerce store, designed to simulate the impact of a marketing campaign on sales. The dataset includes detailed information about sales transactions, product details, and revenue generated over a period of 200 days, starting from January 1, 2021.

**Type of Data Included:**
Transactional Data: Information on sales transactions, including the date of sale, product details, quantity sold, unit price, and revenue generated.
Product Data: Unique identifiers for products sold in each transaction.
Financial Data: Revenue generated from each sale, calculated based on the quantity sold and the unit price of the product.
Time Period Covered:

The dataset spans from January 1, 2021, to September 07, 2021, representing 250 consecutive days of sales transactions.
Marketing Campaign:

The marketing_campaign column is a boolean indicator that specifies whether a marketing campaign was active on a given date.
The marketing campaign is simulated to begin on July 20, 2021, and continues through the end of the dataset.
Before the campaign launch, the marketing_campaign column is set to False, and it is set to True from the campaign launch date onward.
The impact of the campaign is reflected by a notable increase in the quantity of products sold starting from the intervention date.

**Columns and Descriptions:**

- date: The date of the transaction (e.g., 2021-01-01).
- customer_id: A unique identifier for each customer (ranging from 1 to 500). This column does not contain customer demographics but serves to identify repeat transactions by the same customer.
- product_id: A unique identifier for each product (ranging from 1 to 100).
- quantity: The number of units of the product sold on that date, with a notable increase post-intervention.
- unit_price: The price per unit of the product sold, ranging between 10 and 100.
- revenue: The total revenue generated from the sale of the product on that date (calculated as quantity * unit_price).
- marketing_campaign: A boolean indicating the presence of a marketing campaign (True post-intervention, False pre-intervention).

This dataset can be used to analyze the effectiveness of marketing campaigns on sales performance and revenue generation. It is suitable for various data analysis and machine learning tasks, including causal impact analysis, time series analysis, and A/B testing.
