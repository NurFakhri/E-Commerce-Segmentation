# 🌟 Luxury E-commerce Customer Segmentation 🌟

## Project Overview
**This Project focuses** on segmenting customers of an e-commerce platform based on their purchasing behavior. The **RFM (Recency, Frequency, Monetary)** analysis technique is utilized to classify customers into meaningful segments. By examining how recently customers made purchases, how often they buy, and how much they spend. This project aims to uncover actionable insights about customer behaviors and preferences. Such insights are crucial for tailoring personalized marketing strategies and enhancing the overall customer experience.

**The primary objective** of this project is to implement data-driven customer segmentation to support strategic decision-making in e-commerce businesses. Through RFM analysis, businesses can identify high-value customers, re-engage dormant ones, and optimize customer retention efforts. **The benefits of this project** include improved marketing efficiency, enhanced customer satisfaction, and increased revenue by focusing on customer needs and behaviors more effectively. This segmentation framework can serve as a foundation for developing advanced customer analytics and predictive modeling in the future.

## Dataset Overview
The dataset required for this project should include customer transaction data with key features necessary for RFM analysis. These features include Customer ID (unique identifier for each customer), Transaction Date (date of each purchase), Transaction Amount (monetary value of each purchase), and optionally Product Details or Category for further analysis. The example of the dataset shows below:

| CustomerID | PurchaseDate | TransactionAmount | ProductInformation | OrderID | Location  |
|------------|--------------|--------------------|---------------------|---------|-----------|
| A100       | 2024-01-12   | 652.53            | Television          | 890075  | Tokyo     |
| C203       | 2024-01-12   | 39.70             | Mouse               | 176819  | London    |
| A320       | 2024-01-12   | 80.55             | PC                  | 340062  | New York  |
| B125       | 2024-01-12   | 321.44            | Laptop              | 239145  | London    |
| C543       | 2024-01-12   | 299.76            | Laptop              | 194545  | Paris     |

## System Process
1. **Gethering Requirement:** Identifying the business objectives, understanding customer segmentation goals, and determining the required dataset features.
2. **Data Wrangling:** Loading the dataset, assessing its quality, and performing cleaning tasks such as handling missing values, removing duplicates, and ensuring consistency in data formats.
3. **EDA:** Conducting exploratory data analysis to understand customer behaviors, detect patterns, and validate assumptions through visualizations and summary statistics.
4. **Grouping Data:** Aggregating transaction data for each customer to calculate metrics for Recency, Frequency, and Monetary value.
5. **Counting RFM:** Computing RFM scores for each customer based on the aggregated data to quantify their purchasing behavior.
6. **Segmenting Data:** Categorizing customers into meaningful segments using the RFM scores, such as high-value customers or inactive customers, to drive targeted business strategies.

## Customer Segmentation Categories  

1. **Champion**  
   Customers who are the most active, frequently shop, and spend significantly. They are the best and most valuable customers for your business.  

2. **Loyal**  
   Customers who remain consistent and often make purchases of a decent amount but are not yet at the highest level like champions.  

3. **Potential Loyalist**  
   Customers who recently shopped but have low frequency. They have potential to become more loyal in the future.  

4. **Promising**  
   Customers showing increased purchase frequency, though not as frequent as loyal customers.  

5. **Need Attention**  
   Customers who have previously made significant purchases but show a decline in recent activity.  

6. **At Risk**  
   Customers who used to shop frequently but have not made any purchases for a long time.  

7. **Engaged but Infrequent**  
   Customers who recently made a purchase but do not shop often, indicating infrequent engagement.  

8. **Dormant Loyalists**  
   Customers who were previously active but have not shopped for a long time, despite having a history of high purchase frequency.  

9. **Can't Lose Them**  
   Valuable customers who frequently shopped in the past but are now showing signs of disengagement.  

10. **Lost**  
   Customers who have not shopped for a very long time and rarely made transactions. They are nearly inactive.  

11. **Hibernating**  
   Customers who made a single purchase long ago and have not returned since.  

12. **Other**  
   Customers with inconsistent or unpredictable purchase patterns that do not fit other segmentation criteria.

## Result
