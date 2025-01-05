# Credit_Card_Financial_Dashboard
This Power BI project analyzing credit card transaction data to generate insightful customer reports, including spending patterns, customer segmentation, and key performance indicators (KPIs) for business decision-making.


See full Dashboard Here : - [https://app.powerbi.com/groups/me/reports/474a5dc8-8fe6-4697-a323-8b75d5b3cd82/88b9336782f706643276?experience=power-bi]



Here I am Using PostgreSQL Database for data connection into Power bi Desktop in my Pc.In this PostgreSQL Database Contain two tables namely :- 
(1). cc_detail, (2). cust_detail.
=> **Here is Overview Of these tables.**
# Table 1: cc_detail

# Client_Num: Unique identifier for each client. (INT)
# Card_Category: Type of credit card (e.g., Gold, Platinum, Signature). (VARCHAR(20))
# Annual_Fees: Annual fees associated with the credit card. (INT)
# Activation_30_Days: Card Is Activate within 30 days or not (0/1). (INT)
# Customer_Acq_Cost: Cost incurred to acquire the customer. (INT)
# Week_Start_Date: Starting date of the week for which the data is recorded. (DATE)
# Week_Num: Week number within the year. (VARCHAR(20))
# Qtr: Quarter of the year (e.g., Q1, Q2, Q3, Q4). (VARCHAR(10))
# current_year: Year for which the data is recorded. (INT)
# Credit_Limit: Maximum credit limit available to the client. (DECIMAL(10,2))
# Total_Revolving_Bal: Total outstanding balance on the credit card. (INT)
# Total_Trans_Amt: Total amount spent using the credit card. (INT)
# Total_Trans_Ct: Total number of transactions made. (INT)
# Avg_Utilization_Ratio: Average percentage of credit limit used whcih is (total_revolving_balance / card_limit) . (DECIMAL(10,3))
# Use_Chip: Indicates whether the card uses for (Chip, Online , Swipe ). (VARCHAR(10))
# Exp_Type: Type of expenditure (e.g., travel, dining, shopping). (VARCHAR(50))
# Interest_Earned: Interest earned on the outstanding balance. (DECIMAL(10,3))
# Delinquent_Acc: Indicates whether the account is delinquent or not (e.g., Yes/No, 0/1). (VARCHAR(5))


# Table 2: cust_detail

# Client_Num: Unique identifier for each client (foreign key referencing cc_detail). (INT)
# Customer_Age: Age of the customer. (INT)
# Gender: Gender of the customer. (VARCHAR(5))
# Dependent_Count: Number of dependents of the customer. (INT)
# Education_Level: Highest level of education attained. (VARCHAR(50))
# Marital_Status: Marital status of the customer. (VARCHAR(20))
# State_cd: State of residence of the customer. (VARCHAR(50))
# Zipcode: Zip code of the customer's residence. (VARCHAR(20))
# Car_Owner: Indicates whether the customer owns a car (e.g., Yes/No, 0/1). (VARCHAR(5))
# House_Owner: Indicates whether the customer owns a house (e.g., Yes/No, 0/1). (VARCHAR(5))
# Personal_Loan: Indicates whether the customer has a personal loan (e.g., Yes/No, 0/1). (VARCHAR(5))
# Contact: Contact information of the customer (e.g., phone number, email). (VARCHAR(50))
# Customer_Job: Occupation of the customer. (VARCHAR(50))
# Income: Annual income of the customer. (INT)
# Cust_Satisfaction_Score: Customer satisfaction score on a given scale between 1 to 5 . (INT)


= > **Project Goals:**

1. Gain insights into customer credit card usage patterns.
2. Identify relationships between customer demographics and credit card behavior.
3. Develop reports and visualizations to support data-driven decision-making.

=> **Next Steps:**

1.Explore the data further using data analysis tools.
2.Develop specific analyses based on the guided tutorial.
3.Create visualizations to communicate findings effectively.


=> **Learning Objectives:**

This project provides an opportunity to learn:

1. Data exploration techniques in PostgreSQL.
2. Data analysis concepts for customer segmentation and profiling.
3. Data visualization techniques using tools like Power BI .
4. The application of data analysis to business decision-making in the financial services industry.
5. Best practices for data cleaning, transformation, and preparation & Minning.
6. Agile project development methodologies (if applicable based on the tutorial).
7. This Guided Project Help me lot to understand power bi DAX QUERY in efficient and simple way.

8. Customer profiling: This involves creating detailed profiles of different customer segments based on their demographics, behavior, and preferences.
9. Data visualization: This emphasizes the importance of effectively communicating data findings through visual representations.
10. Business decision-making: This highlights how the insights gained from the analysis can be used to inform business strategies, marketing campaigns, and product development.
11. Data cleaning and preparation: This acknowledges the crucial steps of data cleaning and preparation before any meaningful analysis can be performed.
12. Agile project development: If the tutorial follows agile principles, this can be included as a valuable learning objective.
Credits

This project is heavily inspired by a guided tutorial on credit card financial analysis created by Sir Rishabh Mishra on the YouTube channel link
[https://www.youtube.com/@RishabhMishraOfficial] and project video link [https://youtu.be/8XoDVwWdaqI?si=AzHE1sKOYcPUrLNC].
