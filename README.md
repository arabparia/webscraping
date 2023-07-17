In this repository, our goal is to scrape data from the Komono website, a Belgian brand specializing in sunglasses and watches.
The website offers a wide range of products across multiple categories, which are spread across two different web pages.
Our code retrieves the necessary information from both URLs to gather comprehensive data on the available products in the summer sale.
![image](https://github.com/arabparia/webscraping/assets/137802161/4d35416e-ab93-4171-a2fc-297a1ab67e78)

Data Collection
The initial step involves scraping data from the Komono website using web scraping techniques. We gather product details such as category, model name, regular price, and promotional price. The collected data is stored in separate dataframes for sunglasses and watches.
Data Preparation
To create a comprehensive dataset, we combine the sunglasses and watches data frames into a single data frame named "df".
We then perform data cleaning and formatting tasks to ensure the data is in the desired format for analysis.
This includes removing the euro symbol from the regular price and promotional price columns and converting them to float data type.(In 146,147)
![2](https://github.com/arabparia/webscraping/assets/137802161/dc6d9934-458f-4da2-bb34-760eeb1c4916)

We also add a new column named "status" to indicate whether a product is promoted or not.
Additionally, a percentage column is created to calculate the percentage of promotion for each product.[In 148]

Data Analysis and Visualization
With the data prepared, we can now analyze and visualize the insights.
We start by creating a bar plot to visualize the number of products in each category.[In 150]
This provides an overview of the distribution of products across different categories.
Next, we calculate the average price for each category to compare price levels.[In 136]
This information helps us understand which category tends to have higher prices.
We visualize this data using a bar chart.
To analyze the promotional strategies, we create bar charts to showcase the share of promotions in each category.
The first chart represents the share of promotions based on the number of products,[In 153]
while the second chart represents the share of promotions based on the total value of each category.[In 152]
Based on the charts, it is evident that sunglasses hold the largest share of the Komono business.
This observation highlights the importance of sunglasses as a core product category for the company.
Furthermore, we examine the relationship between price levels and promotional activities.[In 154]
Although there isn't a direct correlation, several interesting observations can be made. For sunglasses, the most expensive items typically do not have promotions, catering to a niche market. Popular sunglasses are often priced at specific price points, attracting larger shares of promotions.
In the case of watches, higher-priced items tend to have fewer promotions, possibly due to the lower profit margin associated with these products. Interestingly, watches priced at 59 euros receive the largest share of promotions, indicating a strategic allocation based on profitability and customer appeal.
The findings from this analysis provide valuable insights into the relationship between price levels, promotional activities, and the different product categories offered by Komono.
Please refer to the Jupyter Notebook in this repository for detailed code implementations and visualizations.

