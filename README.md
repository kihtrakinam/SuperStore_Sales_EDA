# EDA on Super Store Sales: Project Overview 
* Use Statistics and Visualization techniques and understand the sales dataset and get business inferences

# Important EDA Questions
* Understanding our geographic spread of customers in US
* Check if any geographic region or city has significantly less profit and address why
* Check for any promising states/cities to expand our business
* Understanding which category sold improved revenue and profit
* Does shipping mode has any effect on revenue and profit

## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn 

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

![alt text](https://github.com/kihtrakinam/EDA/blob/4aa7d26a56560693b5586a13fd827485143f398e/top_rev_city_10.png "Top 10 Cities by Revenue")
![alt text](https://github.com/kihtrakinam/EDA/blob/f7ff2bc23ec70a0f9ce3e7db63b3f434334700f3/avg_rev_prof_city.png "Top Avg Revenue and Profit Cities")
![alt text](https://github.com/kihtrakinam/EDA/blob/f690b9fd86b8a22cc58533a3a5bf493e67a7e177/Central_Category.png "Revenue and Profit in Central US by Category")


## Important Business Inferences

1. In Central US, the furniture business is in loss and it is a concern to be addressed
2. Company gets high revenue from popular cities such New York, Los Angeles and Seattle, but small cities such as Jameston, Independence shows promise with high average revenue and profit per purchase
3. Technology products give the best average profit per purchase
4. In technology related products, copier gives 10x profit compared with any other sub category
5. Company should promote 'First Class' shipping modes for better revenue and profit per purchase 
