# Superstore-Data-Analysis

This is a data analysis project for the superstore dataset
Objectives:
1. Exploratory Data Analysis
2. Identify a business problem
3. Identify a solution

# DashBoard
![2023-07-16](https://github.com/hrishabh08/Superstore-Data-Analysis/assets/76394992/7f540429-4b78-49f0-a745-464045fdd8dc)

# 5.Total observation from EDA
#### What are total sales and profit?
* Total Sales = 2,296,195.56 USD
* Total Profit = 286,241.42 USD

#### Top 10 States by Sales and Profits
* Top sales
'California', 'New York, 'Texas', 'Washington', 'Pennsylvania',' Florida', 'Illinois', 'Ohio', 'Michigan', 'Virginia' 

* Top Profit: 'California', 'New York, 'Washington', 'Michigan', 'Virginia',' Indiana', 'Georgia', 'Kentucky', 'Minnesota', 'Delaware'

* California and New York are the 2 highest in both sales and profit

#### How does discount affect profit and Sales
 * When Discount = 0 sales and profit are positively correlated which shows that profit increases with sale
 * When the Discount is not 0, sales and profit are negatively correlated which shows profit decreases with an increase in sales
 * As the discount amount increases the sales increase but profit decreases for overall cases

#### Checking for all Sub-Categories
* For Machines the sales are high but the profit is least (-ve), the reason is: discount is second highest for this category
* This proves that giving heavy discounts decreases profit to a great extent

#### Checking for all regions
* The only region with a -ve profit product is the central region and the product is furniture
* All the shipping modes produce the -ve profit in this case
* Using heatmap it is proved that sales and profit are negatively correlated with discount, so increasing discount is decreasing both sales and profit

### Final Insights from the Analysis
1. If we give more discount sale may increase in some of the cases but the profit will decrease
2. In Technology products we get more profit because the discount is less
2. In Sub-categories Machines are having the least profit because it has the second highest discount
4. In some of the cases the discount negatively affects both sales and profit(like furniture in central region)
5. To increase profits we need to increase sales in 'Fasteners','labels'and 'Art' category which are very weak.
6. To increase profit we need to sell more to the states which are liking our products like California and New York

