# Analysis-and-evaluation-of-Eniac-s-discount-strategy
Our team evaluated Eniac's current discount strategy, tasked to offer advice if the current discount strategy should be abandened of changed. After an intensive data cleaning and preparation phase and the following analysis, we came to the conclusion that the current discount strategy should be adjusted.  
# Dataset

orders: List of all orders and the price paid by the customers.

orderlines: Detailed list of all products involved in an order and the price paid for each product.

products: List of all products offered by Eniac.

# Key findings & Results

The orders and orderlines Dataframe needed extensive data cleaning before the actual analysis. As the original column for the discounts offered for each product was corrupted, the discounts were calculated by subtrating the unit price payed by the customer with the product price in the products DataFrame.

After our cleaning process and analysis, our key findings were: 

1. Cap standard discounts at 20%: Higher discounts wihtin our Dataset mostly performed considerable worse.

2. Rebalance discount towards high-end products, away from low-budget items: Low priced products get the biggest discounts (around 24.4%) but bring only 5.9% of total revenue. High-priced products are barely discounted(16%) yet bring in 56.1% of total revenue.

3. Seasonal patterns matter: November was the best month of the year regarding orders and average order value - without the year's highest discount.

# Technologies used

Presentation: Google Slides

Machine learning: ChatGPT

The entire data cleaning, analysis and visualisation of results was carried out with Python. The following modules were used:

Data cleaning and Analysis : Pandas

Data Visualization: Matplotlib, Seaborn 

# Project structure

README: Project documentation

Final_Data_cleaning: The whole data cleaning process, conducted by our team

Final_quality_assesement: Date time conversions and final preparations for the Visualizations.

Visualizations: Building visualizations for our final presentations

Presentation: The presentation of our team.

# Visualisations

