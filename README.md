# Churn-Analysis
 Churn customer prediction is an activity carried out to predict whether the customer will leave the company or not.
 Customer Churn, also known as customer attrition, customer turnover, or customer defection, in the loss of clients or customers.

Bank, insurance companies, streaming services companies and telcom service companies, often use customer churn analysis and customer churn rates as one of their key business metrics because the cost of retaining existing customers is far less than acquiring a new one.

This analysis focuses on the behavior of bank customers who are more likely to leave the bank (i.e. close their bank account). I want to find out the most striking behaviors of customers through Exploratory Data Analysis and later on use some of the predictive analytics techniques to determine the customers who are most likely to churn.


Now just a brief explaination of all the columns provided in the dataset:

RowNumber - corresponds to the record (row) number and has no effect on the output.

CustomerId— contains random values and has no effect on customer leaving the bank. However, it is unique identifier hence we will keep this column and can drop it before EDA.

Surname—the surname of a customer has no impact on their decision to leave the bank.

CreditScore—can have an effect on customer churn, since a customer with a higher credit score is less likely to leave the bank.

Geography—a customer's location can affect their decision to leave the bank.

Gender— Using this we can analyse if gender is important factor to predict the customer leaving the bank

Age— Age is relevant, since older customers are less likely to leave their bank than younger ones.

Tenure— Number of years that the customer has been a client of the bank. Normally, older customers are more loyal and less likely to leave a bank.

Balance— Good indicator of customer churn, as people with a higher balance in their accounts are less likely to leave the bank compared to those with lower balances.

NumOfProducts— Number of products that a customer has purchased through the bank.

HasCrCard— Whether or not a customer has a credit card. This column is also relevant, since people with a credit card are less likely to leave the bank.

IsActiveMember—active customers are less likely to leave the bank.

EstimatedSalary—People with lower salaries are more likely to leave the bank compared to those with higher salaries.

Exited-To see whether the customer left the bank or not.
