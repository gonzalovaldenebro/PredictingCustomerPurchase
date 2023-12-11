# Predicting Customer Purchase

See the code displayed live: [Here](https://rpubs.com/gonzaloV/1128119)

## 1. Introduction to data

This [dataset](https://www.kaggle.com/datasets/ddosad/customer-behaviour-tourism-portal) provides a snapshot of user behavior on a social media platform associated with a tourism company. It includes essential information such as user identification, ticket purchase predictions, and key metrics related to user engagement, preferences, and demographic details. The [dataset](https://www.kaggle.com/datasets/ddosad/customer-behaviour-tourism-portal) aims to unveil insights that can inform strategic decisions to enhance the customer experience and increase ticket sales for the tourism company.

# 2. Research Questions of the client

### Research Question 1: Impact of Social Engagement

**Client's Inquiry:** We were curious about the impact of social engagement, specifically regarding check-in likes. How does a customer's involvement in giving likes during other check-ins influence their likelihood of purchasing a ticket next month?

### Research Question 2: Effect of Company Engagement

**Client's Inquiry:** The client is interested in understanding the influence of customers following their company's account on their likelihood of purchasing a ticket. How does being a CompanyFollower affect the chances of buying a ticket next month?

### Research Question 3: Website Interaction and Ticket Purchases

**Client's Inquiry:** The client is interested in exploring the relationship between the number of visits to our website and the likelihood of customers purchasing a ticket. How do YearlyAvgPageVisits correlate with the odds of buying a ticket next month?

## 3. Recommendations

### 3.1. Strategic Social Media Engagement:

Let's develop a targeted social media engagement strategy to encourage more customers to follow our company's account. Given the substantial positive impact of being a CompanyFollower, increasing our follower base has the potential to significantly boost ticket sales.

### 3.2. Enhanced Online Experience:

Despite the small impact, let's consider optimizing our website to enhance the user experience. This could involve personalized content recommendations, targeted promotions, or other features aimed at increasing the conversion rate for website visits to ticket purchases.

### 10.3. Continuous Monitoring and Iteration:

We'll establish a routine for monitoring the model's performance and iterate as needed. While Model 7 has been chosen for its balance between simplicity and performance, periodic reassessment should be conducted to ensure continued relevance and accuracy.

## 4. Conclusions

### 4.1. Model Validation for Confidence:

Rest assured that the selected Model 7 demonstrates robust predictive performance, with a high AUC of 99.88%. The model's ability to correctly identify both positive and negative cases (sensitivity and specificity exceeding 99%) instills confidence in its reliability.

### 4.2. Key Drivers of Ticket Purchases:

CompanyFollower emerges as a key driver of ticket purchases, emphasizing the importance of building and maintaining a strong social media presence. While social interactions (TotalCheckInLikesReceived) play a role, their impact is relatively small and may require a more nuanced understanding.

### 4.3. Balancing Complexity and Efficiency:

I've opted for Model 7 over more complex models based on the variable importance plot, with variables beyond Model 7 contributing 37% or less to the model. This choice strikes a balance between model performance and computational efficiency, ensuring we get the most value with the least complexity.

### 4.4. Decision-Making Threshold:

The suggested probability threshold of 0.2325 provides a balanced trade-off between sensitivity and specificity. This threshold can be fine-tuned based on our business considerations and the acceptable level of false positives and false negatives.

### 4.5. Continuous Improvement Journey:

Let's emphasize the importance of ongoing monitoring and adaptation. As our customers' behaviors and preferences evolve, the model should be regularly updated to ensure its continued relevance and accuracy in predicting ticket purchases.

# 5. References

1.  [R Markdowon](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)
2.  [Dataset](https://www.kaggle.com/datasets/ddosad/customer-behaviour-tourism-portal)



















































