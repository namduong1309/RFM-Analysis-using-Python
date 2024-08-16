# RFM Analysis using Python
## Link project
https://drive.google.com/file/d/1BCSBfZshXyRVNLetdDYCwZTLLONTS7eX/view?usp=sharing
## Introduction
In this project, I conducted an RFM (Recency, Frequency, Monetary) analysis using Python to help SuperStore, a global retail company, better understand its customer base. With the holiday season approaching, the Marketing Department is eager to launch targeted campaigns to reward loyal customers and engage potential ones. However, due to the large volume of customer data, the team has struggled to manually segment customers as they have in previous years. They requested support from the Data Analytics Department to automate the segmentation process using RFM analysis, which had previously been done in Excel when the company was smaller.
### Approach
To tackle this challenge, I proposed the following steps:
1. **Data Preparation**: I first prepared the dataset to fit the RFM model, ensuring that all relevant data points were included.
2. **RFM Scoring**: I calculated the Recency, Frequency, and Monetary scores for each customer. Recency was calculated as of December 31, 2011. For scoring, I employed the quintile method, assigning each customer a score from 1 to 5 for each RFM metric.
3. **Customer Segmentation**: Based on the RFM scores, I categorized customers into distinct segments. This allowed for a more nuanced understanding of customer value and behavior.
4. **Data Visualization**: I visualized the distribution of customer segments across different dimensions, providing clear insights into the makeup of SuperStore’s customer base.
5. **Company Analysis and Recommendations**: I analyzed the current state of the company’s customer base and provided actionable recommendations for the Marketing team. This included identifying which RFM metric—Recency, Frequency, or Monetary—should be prioritized given SuperStore’s retail model.
By automating the RFM segmentation process through Python, I enabled SuperStore to efficiently categorize its large customer base and tailor its marketing efforts to different customer groups. This will help the company maximize the impact of its holiday campaigns and foster stronger customer relationships going forward.
## Insight
**Analysis of Current Company Status and Recommendations for the Marketing Team**
- **Customer Appreciation**:
   - The Marketing Department should focus its appreciation efforts on two key customer segments: *Champions* and *Loyal* customers. These two groups together represent nearly 30% of the total customer base and contribute over 70% of the company’s revenue.
   - These segments have very high RFM scores, indicating a strong loyalty to the company’s products. To retain these valuable customers, the following strategies should be considered:
     - **Personalized Customer Experiences**: Offer personalized gifts based on the product categories they purchase most frequently.
     - **Exclusive Shopping Perks**: Provide benefits like free shipping and priority delivery options.
     - **Special Holiday Packages**: Create distinctive Christmas and New Year gift sets by bundling some of the company’s top-selling products.
- **Targeting Potential Customers**:
   - The Marketing Department should also pay attention to customer groups with balanced ratios of customer numbers to revenue:
     - *Promising* (3% of customers, 3% of revenue)
     - *Need Attention* (5% of customers, 3% of revenue)
     - *At Risk* (9% of customers, 7% of revenue)
     - *Cannot Lose* (2% of customers, 3% of revenue)
   - For the *Promising* and *Need Attention* segments—customers who have made recent purchases with high order values but low frequency—implement strategies to encourage more frequent purchases, such as "buy 3, get 1 free" deals or complementary products as gifts.
   - For the *At Risk* and *Cannot Lose* segments—customers who used to buy frequently or make high-value purchases but haven’t returned in a while—conduct detailed surveys to understand why they stopped buying. Based on their feedback, create tailored campaigns to win them back.
**Recommendation for Key RFM Metric Focus**
- **Focus on Recency (R)**:
   - The company should prioritize the Recency metric because customers who have made recent purchases are more likely to respond positively to new marketing campaigns than those who haven’t bought in a long time.
   - The longer it has been since a customer’s last purchase, the less likely they are to return.
   - By targeting customers with high Recency scores, the company can more effectively influence their purchasing behavior and drive sales.
