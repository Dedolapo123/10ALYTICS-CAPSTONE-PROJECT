PROJECT DESCRIPTION 

Nexus Bank is a financial institution dedicated to delivering unparalleled banking services to their clients. Their mission is to establish enduring relationships with our customers by providing tailored financial solutions that align with their individual needs and goals.

The Director of Nexux contacted you a Data Scientist because they are interested in leveraging the power of their data to gain insights into the bank and improve their efficiency. They want to identify patterns and trends in customer behavior to decipher if customer demographics such as age, educational level e.t.c influences customers attitude toward defaulting. The board specifically wants to anticipate future customer behavior and know the likelihood of deposits from customers.
Nexus Bank provided their customer data that will help gather more insights into the bank and improve their efficiency
I had used this data to identify patterns and trends in customer behaviour to decipher if customers demographics influences customer's attitude towards defaulting
Anticipate future customer behaviour and know the likelihood of deposits from customers

GOAL OF THIS ANALYSIS NEXUS BANK

•	Acquire more deposits
•	Leverage on the data to improve their efficiency
•	Optimize their operations 
•	Mitigate risks
MAJOR PROBLEM

The problem to be solved is to predict a customer's deposit probability based on various features. Banks can benefit from this solution by streamlining operations, improving marketing campaigns, reducing risk, and increasing customer deposits.
DATASET

A dataset containing the bank's customer details which have 45,211 rows and 17 columns was provided for this analysis
Dataset Attributes

Features
•	Age: the age of the customer who holds the bank account.
•	Job: the type of job that the customer has.
•	Marital: the marital status of the customer, which could be "married," "divorced," or "single".
•	Education: the education level of the customer, which could be "primary," "secondary," or "tertiary."
•	Default: This feature indicates whether the customer has previously defaulted on a loan or credit card payment, which could
•	be "yes" or "no.“
•	Balance: This feature represents the current balance in the customer's account.
•	Housing: This feature indicates whether the customer has a housing loan or not, which could be "yes" or "no."
•	Loan: This feature indicates whether the customer has a personal loan or not, which could be "yes" or "no."
•	Contact: the method of contact used to reach out to the customer, which could be "cellular,"
•	"telephone," or "unknown.“
•	Day: the day of the month when the customer was last contacted.
•	Month: the month of the year when the customer was last contacted.
•	Duration: the duration of the last contact with the customer, in seconds.
•	Campaign: the number of contacts made to the customer during this campaign.
•	Pdays: the number of days that passed by after the customer was last contacted from a previous
•	campaign.
•	Previous: the number of contacts made to the customer before this campaign.
•	Poutcome: the outcome of the previous marketing campaign, which could be "success," "failure," or "unknown."
Target/Label
•	Deposit: This feature indicates whether the customer has made a deposit, which could be "yes" or "no."

STEPS TAKEN TO SOLVE THIS PROBLEM

1.	Exploratory data analysis: Plotted the relationships between the deposit label and key features such as age, job, marital, education, default,  loan, etc by using graphs
2.	Explore correlations: visualized the correlations between numerical features and deposit.
3.	Univariate and multivariate analysis: Analyzed all features to understand their distribution using bar charts, pie chart, identified outliers, and explored their impact on deposit. I also analyzed the combination of different features to understand the interactions as well as the impact that can affect deposit potential.
4.	 Encoding categorical variables: Converted categorical variables such as job, marital status, education, default, housing, contact method, month into numerical variables using label encoding.
5.	Model selection, training, and validation: Tested with 3 supervised learning models ; logistic regression, decision trees, random forests and trained them on the data. Split the data into training and testing sets to allow evaluation of the models' performance.
6.	Model evaluation: Evaluated the trained models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC and analyzed the models' performance in predicting the likelihood of making a deposit and also defaulting.
7.	Chose the evaluation metrics that align with the bank's specific goals and requirements.
