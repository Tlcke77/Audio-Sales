## Overview

To illustrate the dashboard creation, I used a fictional business, "Asces Sound," a company specializing in premium audio equipment, including headphones, amplifiers, and microphones. The business required a dashboard to provide insights into key product performance metrics, helping them monitor sales trends, and optimize profitability.
# Power BI Dashboard: Audio Sales

<img src="https://github.com/Tlcke77/pics/blob/main/audio%20sales.PNG" alt="Image" width="900" height="520">

* Below is a demonstration of the dashboard's interactivity. Each click on a product image dynamically updates the dashboard, providing tailored insights and real-time data.

<img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2F6aW1lajhnNWF2ZjF2MmVscWZ0Y2plODQ1aDZ1Y2ZlNjVyazNsbiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/t56gLshxnODuqzqlZw/giphy-downsized-large.gif" alt="Image" width="900" height="520">


## Questions:

1. Revenue by Country: Top Performing regions with the corresponding values
2. Revenue by Date and Year: Comparative trends
3. Profit and Revenue of each product
4. Revenue breakdown by Discont Band: Distrobution of revenue across different discount categories
5. Detailed Table View: Revenue and profit by country and year.


## Data Sources and Types

To build the dashboard, various datasets were utilized to capture a comprehensive view of product performance, sales trends, and discount impacts. These datasets included product details, sales transactions, and discount information, providing a well-rounded basis for analysis. Below is an overview of the data types available:

### 1. Product Data

This dataset contained detailed information about the products offered by the business, enabling insights into product-specific metrics like profitability and category performance. Key fields included:

* Product ID: A unique identifier for each product.
* Product Name: The name of the product (e.g., "Bluetooth Headphones Model X").
* Category: The product category (e.g., headphones, speakers, amplifiers).
* Cost Price: The cost of manufacturing or acquiring the product.
* Sale Price: The retail price at which the product is sold.
* Brand: The manufacturer or brand associated with the product.
* Description: A brief description of the product's features.

 ### 2. Product Sales Data

This dataset captured transactional information, enabling analysis of sales performance across different dimensions such as time, geography, and customer segments. Key fields included:

* Date: The date of the sale transaction.
* Customer Type: The type of customer (e.g., individual, corporate).
* Country: The geographic location of the sale.
* Product: The name of the product sold.
* Discount Band: The range of discounts applied to the sale (e.g., 10%-20%).
* Units Sold: The quantity of the product sold in the transaction.

### 3. Discount Data

This dataset provided details on the discounting strategy and its impact on revenue distribution. Key fields included:

* Month: The month in which the discount was applied.
* Discount Band: The range of discounts offered (e.g., 0%-10%, 10%-20%).
* Discount Percent: The specific percentage discount applied within the discount band.
