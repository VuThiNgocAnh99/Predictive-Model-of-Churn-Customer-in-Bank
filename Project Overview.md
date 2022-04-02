# Predictive Model of Churn Customer in Bank
The goal of this project is to find customer insights and build a model to predict churn customer at a bank. In this project, I have done 4 main tasks: 
- defining Churn Customer in bank, 
- cleaning the dataset, 
- exploring the dataset to find churn customers insights, 
- building and evaluating predictive model.
# The dataset overview
The raw dataset includes 100,000 observations and 35 attributions. 
This dataset is observed at 3 different time points:
- As of December 31, 2020: Observe transactions and customer behavior within the previous 1 week, 1 month before and 3 months before.
- March 2021: Observe customer behavior this whole month
- Juin 2021: Observe customer behavior this whole month
# Conclusion of this project
I chose K-Nearest Neghbors as the most efficient and optimal model for this dataset. Moreover, we found out some insights and behaviors of Churn Customers as follows:
- The lower a customer's total transaction amount in the 1-month, 3-month period before the customer leaves the bank, the more likely the customer is to become a Churn Customer.
- The lower the value of the customer's largest transaction in the 3 observation periods (1 week, 1 month, 3 months ago), the more likely the customer is to become a Churn Customer.
- The smaller the difference between the customer's largest transaction and the customer's smallest transaction in the three observation time periods, the more likely the customer is to become a Churn Customer.
- The less service the customer used in the three observation periods, the more likely the customer is to become a Churn Customer.
- The smaller the number of recipients of a customer's transactions, the more likely the customer is to become a Churn Customer.
- Churn Customers tend to being male, single and between the ages of 18 and 34.
- Churn Customers tend to use two payment codes 0 and 1, especially payment code 0 in the period of 1 week, 1 month, 3 months before leaving the bank.
- Churn Customers tend to use transaction group 1 in the previous week; or use transaction groups 1 or 2 in the previous 1 month; or use transaction groups 1, 2, 3 within 3 months before leaving the bank.
