##**Churn prediction**  

It is the practice of analyzing data to detect customers who are likely to cancel their subscriptions, i.e. churn out. Subscription based businesses conduct their own form of churn prediction analysis to identify customers most at-risk of churning, and, when done well, it leads to huge business savings and improved customer lifetime value (LTV). 

Even low churn rates in the ballpark of 5% can lead to catastrophic damages to the business due to compounding. Thus, understanding this is extremely important.

The data used for this experiment has been collected from Kraggle: https://www.kaggle.com/blastchar/telco-customer-churn. This dataset contains the people who left the services of a telecom service provider called Churn, along with all the necessary details like:
-   Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
-   Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
-   Demographic info about customers – gender, age range, and if they have partners and dependents

A Churn prediction task remains unfinished if the data patterns are not found in EDA. It is important to note that finding patterns in Exploratory Data Analysis (EDA) is as important as the final prediction itself. Thus, EDA has been performed on the data to understand the underlying patterns. 

For this model, metrices have been used to find out the underlaying importance of features. 
Features such as :
1. gender, 
2. is senior citizen
3.  have a partner
4.  dependents
5.  tenure
etc, has been used to find the mutual feature importance, co-feature selection correlation coefficient and risk ratio.  

The importance of each of these features can be used further for our advantage, i.e., if a feature show's its extreme likeliness to churn, necessary steps can be taken to avoid any loss. With these we can also find the reason and the steps that may lead to the churn, which can be further avoided. 

On the business development side of things, churn trends can help marketers build customer personas to target a market segment with better messaging and boost customer acquisition.  

In this project a similar linear regression model has been created to predict the customers leaving the company, with an accuracy of 80%. The primary focus has been on the interpretability of machine learning and understanding the churn. 
