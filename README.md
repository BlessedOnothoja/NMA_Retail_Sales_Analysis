# KNL Retail Sales Analysis Dashboard

## Overview

NMA is a retail business which deals on 3 product categories(Office supplies, furniture and technology) across 3 segments(consumer, corporate and home office). The organization has made a total sales of $2.30 million and a total profit of $442,530. This report analysis the sales performance across all variables, operations bottlenecks in order to identify opportunities for greater growth and productivity.


## Problem Statement

NMA decided to check its operations efficiency. This they did by investigating customer segments, product categories, deliveries across regions and states to identify bottlenecks, profits, losses, customers performance and employee performance. Hence, implementing recommendations to improve profit margins, staff efficiency and customer satisfaction. 

## Tools and Methodology
### Tools : 
Power Query: This was used for data cleaning, standardization and validation.

DAX: This was used to generate calculated measures required to properly identify relationships between variables.

Power BI: Interactive dashboard creation and visualization

### Methodology:
Data cleaning/Standardization/validation: A thorough data cleaning process was carried out on the data set. This includes removing of duplicates, data standardization through the entire dataset. Details of all data cleaning process was documented appropriately.

Data modelling: The dataset was segrated into fact and dimension tables which were connected using the star schema dimensional model.

Exploratory data analysis: DAX was used to create calculated measures which where neccessary to aggregate and meaningfully show relationship between variables in order to clearly identify trends.

Visualization: A three page interactive dashboard was built to clearly answer possible business questions.

## Dashboards

Page 1 link: (https://github.com/BlessedOnothoja/NMA_Retail_Sales_Analysis/blob/5d6e5e466f128ff18fc8c97b2557bdcda6083113/NMA%20RetailSales%20Page1.jpg)

Page 2 link:(https://github.com/BlessedOnothoja/NMA_Retail_Sales_Analysis/blob/5d6e5e466f128ff18fc8c97b2557bdcda6083113/NMA%20RetailSales%20Page2.jpg)

Page 3 link:(https://github.com/BlessedOnothoja/NMA_Retail_Sales_Analysis/blob/5d6e5e466f128ff18fc8c97b2557bdcda6083113/NMA%20RetailSales%20Page3.jpg)


NB: The dashboard display will change on application of different filters. To return back to status quo, simply hold Ctrl and click on the Reset arrow on the bottom left of the dashboard. 

## Possible Business questions

- What product category is more profitable?
- What are the possible reasons for returns?
- What segment/category performed well and what is the category/segment that battle losses?
- Are there any bottle necks in delivery and how can this be corrected?
- Which Customers and Staffs are aiding profitablity the most at NMA?
 



## Insights

A three page report was created on Power BI Desktop.

The following inferences can be drawn from the dashboard;

### [1] Sales Performance

- Technology category with total sales of $836.15k topped the sales performance chart, followed by furniture with a total of $742k before office supplies($719.05k). However, office supplies made more profits than furniture.
- Overall, furniture category made the highest loss($60.94k)
- Customer segment had a significant higher sales and made the highest profit than other segments, even though it had the highest loss($84.94k) which was about twice the loss from coporate segment.
- Overall, office supplies had significantly higher unique orders, quantity purchased and lower return rate than other product categories. However the profits vary through the months.

   


           The higher loss in furniture can be traced to a higher return rate compare to other product categories.

           Furthermore, it can be infered that the majority of NMA customers are from the consumer segment, such that even though they were having losses at some point, they had customers that were filling loopholes faster.

           Technology is definitely the best performing product category at NMA from this analysis.
           
### [2] Delivery/ Region Performance

 - Unique orders as well as sales was highest in the West region with a total sales of $725,458. Specifically, in the state of Clifornia total sales was $457,687. This was the largest sales by an individual state.
 - There were some issues with the shipping mode/deliveries. For example, 4 same day delivery customers recieved their packeges after 1-2 days, while 7 of them had their packages after 15 days. Furthermore, 288 first class customers had thei packeges delivered after 15 days.

 



        Clearly return rates are higher in the Central region. Management may want to consider options to improve the quality of service delivered in this region for improve performance.

        Overall, there is definitely a bottleneck with the shipping/delivery process which has to be addressed for better performance

  
  

 
  
  ### [3] Sales Rep/Customer Performance
  

- From the Sales rep angle, Anna Andreadi topped the chart in sales performance, with a total of $725,450. Chuk Magee topped in sales of technology category with a total sales of $264,970.

- Chuk Magee made the most total profit($68,460). He had his highest profit from the technology category.

- From the customers angle, Tamara Chand was the most profitable customer. NMA made a total profit of $9,025.60 from her purchase of 5 unique products. This is the highest profit from an individual customer purchase. Andrian Barton who is the 4th on the list had 10 unique orders with a total profit of $5,847.28


      Overall Anna Andreadi has a great sales strategy, but Chuk Magee is definitely better with sales of technology category.

      From the customer angle, it can be infered that it takes more than quantity to be a high profit customer, quality is also a factor.
            
## Conclusion/Recommendations
This analysis drills down to show clearly the performance of NMA across different variables and vivid opportunities for improvements across all regions. The following are some recommendations that can be considered to improve performance:

- Investigate issues with return rate associated with furniture product category.

- Expand market and formulate strategies to encourage good performing technology products.

- Investigate reasons for higher returns in Central region and tackle it.

- Investigate shipping mode/deliveries further to uncover specific challenges. A possible solution may be to automate customers requests and optimize staffing to push out deliveries more efficiently.

- Management should brainstorm and come up with retention strategies for high value customers and formulate means to encourage low value customers.

- Top performing employees should be considered for annual incentives and regular reward systems should be adopted.


Power BI Visualization: https://github.com/BlessedOnothoja/NMA_Retail_Sales_Analysis/blob/34ab5f765439d66cb9d5f17db6dee2f42415ed72/NMA%20Retailsales%20Report.pbix
