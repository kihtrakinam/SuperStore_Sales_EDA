# EDA on Super Store Sales: Project Overview 
* Use Statistics and Visualization techniques and understand the sales dataset and get business inferences
* Model building - Pending

# Important EDA Questions
* Understanding our geographic spread of customers in US
* Check if any geographic region or city has significantly less profit and address why
* Check for any promising states/cities to expand our business
* Understanding which category of products have high revenue and profit
* Does shipping mode has any effect on revenue and profit

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, matplotlib, seaborn 

## Dataset Features and Descripment
* Ship Mode    - Shipping mode of the purchased products
* Segment      - Segment of the products
* Country
* City
* State
* Postal Code
* Region       - Divided by East, West, South, Central
* Category     - Category of the product in the segment
* Sub-Category - Based on the product, further divided into Sub-Category
* Sales        - Revenue obtained from the purchase
* Quantity     - Quantity of products in the purchase
* Discount     - % Discount availed
* Profit       - Profit/Loss

## Data Cleaning
*	No null values or improper values present
*	34 Duplicate purchases available but considered them as different purchases since no unique key available in the dataset
*	Changed Postal Code feature to object 

## EDA Steps
* **Five point Descriptive Statistics** - Univariate description of both the numerical and categorical variables
* **Correlation and Pair plot** - Distribution and the relation between the numerial variables
* **Bivariate and multivariate Analysis** - Plotting Pieplot and Barplots to visualize and infer the significance of the features

## Important Graphs
1. New York and Los Angeles among top 10 Revenue contributing Cities
![alt text](https://github.com/kihtrakinam/SuperStore_Sales_EDA/blob/4aa7d26a56560693b5586a13fd827485143f398e/top_rev_city_10.png "Top 10 Cities by Revenue")
2. Relatively smaller cities such as Jameston and Independence have higher revenue and profit per purchase on average
![alt text](https://github.com/kihtrakinam/SuperStore_Sales_EDA/blob/f7ff2bc23ec70a0f9ce3e7db63b3f434334700f3/avg_rev_prof_city.png "Top Avg Revenue and Profit Cities")
3. Central Region trending in less profits because of loss in Furniture category
![alt text](https://github.com/kihtrakinam/SuperStore_Sales_EDA/blob/f690b9fd86b8a22cc58533a3a5bf493e67a7e177/Central_Category.png "Revenue and Profit in Central US by Category")
4. Office supplies have been given high discount at times, but Furnitures have wider possible range of discount
![alt text](https://github.com/kihtrakinam/SuperStore_Sales_EDA/blob/ae106e1c77a60aaf99aff013dde6501214bdb175/Discount_cat.png "Discount Distribution by Category")
5. Products on technology category yields best revenue and profit per purchase
![alt text](https://github.com/kihtrakinam/SuperStore_Sales_EDA/blob/ae106e1c77a60aaf99aff013dde6501214bdb175/Category.png "Top Avg Revenue and Profit Cities")
6. Copiers yield 10x profit per purchase comparatively
![alt text](https://github.com/kihtrakinam/SuperStore_Sales_EDA/blob/ae106e1c77a60aaf99aff013dde6501214bdb175/Technology_sub_category.png "Copiers are imp")
7. Standard Class is the most preferred. First Class Shipping mode yield more profit per purchase
![alt text](https://github.com/kihtrakinam/SuperStore_Sales_EDA/blob/19069426f8b711fd2283757650a989be419b1e85/Ship_Mode.png "Copiers are imp")


## Important Business Inferences

1. In Central US, the furniture business is in loss and it is a concern to be addressed
2. Company gets high revenue from popular cities such New York, Los Angeles and Seattle, but small cities such as Jameston, Independence shows promise with high average revenue and profit per purchase
3. Technology product category yields the best average profit per purchase
4. In technology related products, copier gives 10x profit compared with any other sub category
5. 'First Class' shipping modes have better revenue and profit per purchase than others but has less market share. Let's promote it
