# Bank-customer-churn-dataset
## Table of Contents
- [Data Description](#dataset-description)
- [Content](#content)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Inference Analysis](#inference-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

### Dataset Description(Overview)
The Bank Customer Churn dataset contains information about bank customers, this includes their demographic details, credit score, account balance, tenure and other features.

### Content
 The dataset comprises 10000 row 13 columns, each illuminating different facets of activities in the bank customers dataset:

- **Customer Id**: A unique identifier for each customer
- **Surname**: The customer's last name
- **Credit Score**: A numerical value representing the customer's credit score
- **Geography**: The country where the customer resides (France, Spain or Germany)
- **Gender**: The customer's gender (Male or Female)
- **Age**:  The customer’s age
- **Tenure**: The number of years the customer has been with the bank
- **Balance**: The customer's account balance
- **Num Of Products**: The number of bank products the customer uses (e.g., savings account, credit card)
- **Has Cr Card**: Whether the customer has a credit card (1 = yes, 0 = no)
- **Is Active Member**: Whether the customer is an active member (1 = yes, 0 = no)
- **Exited**: Whether the customer has churned (1 = yes, 0 = no)

### Data Sources 

•	The data source for the analysis is a Comma Separated Values(csv) file named "bank customer churn.csv" gotten from Maven analytics data playgroung
### Tools:
* Python For data cleaning and preparation.
* Excel
* Pivot Table for proper analysis.
* Excel Dashboard for interactive visualizations
* Power point For reporting and communicating

### Data Cleaning
* 1. Null/empty value check to ensure no missing data.
* 2.  Pizza type column was created for proper analysis on “vegetarian and non vegetarian” set of Pizza.
* 3. Duplicate value check: no duplicates found.
* 4. The "" column is been split into Days, Month, and Year of purchase for proper analysis.

### Inference Analysis
  The analysis uses several techniques:
* 1. Stacked column: Analyzes the “top 10 customers with the highest estimated salary”.
* 2. 3-D Stacked column: Analyzes the “top 10 customers with the highest balance”.
* 3. 3-D Column Chart: Review the “Gender with the highest estimated salary and balance”.
* 4. Doughnut: Analyzed the “The total customers with and without credit card”.
* 5. 3-D pie: Analyzed “The active and inactive customers”.
* 6. Clustered bar: Analyzes the “Total geography balance”.
* 7. 3-D Clustered column: Shows “The top 10 age with the highest balance”.
* 8. 3-D Stacked column: Analyzes the “Age with the highest estimated salary”.
*9. 3-D Clustered column: Shows “The age with the highest exit”.
 
### Findings
* The total customers is 10,000.
* The total estimated salary is N1,000,902,399 and total balance is 764,858,893.
* The average estimated salary is N100,090 and total balance is 76,488.
* The non active customers have a balance of 374,024,593 while the Active customers balance is 390,834,299
* The non active customers have an Estimated salary balance of 488,620,171 while the Active customers Estimated salary balance is 512,282,227
* The Customer churn is 2,037 count and have a total balance of 185,588,094 and an total estimated salary balance of 206,685,585
* France has the highest Estimated Salary and highest balance next Germany and Spain.
* Customers that exited is 2,037 out of 10,000.
* Active customers is 5,151 none active 4,849.
* Total number of 3,547 customers are with the bank yet not active
* Total number of 735 customers have exit the bank but indicating active probably an update issue
* Customers with card is 7,055 without card is 2,945.
* Smith a 67 years active female customer from France has the highest value balance of 2,631,243 while Yeh a 37 years Female customer from France has the highest estimated salary 3,225,671.
* Ferri a 39 years female from Spain has the highest values count rows balance and also has the highest value counts rows of Credit Score also among the top Tenure, yet has no credit card and also less than an average of active customer counts.
* Male customers has the highest balance of 543,869,596 while the female customers is 457,032,803 balance.
* Male customers also have the highest value counts of customers, a count of 5,457 while Female is 4,543.
* France has the highest value counts of customers in terms of Geographical zones, a count of 5,014 next to Germany 2,509 and Spain 2,477.
* Highest age 92, maximum balance 250,898 maximum estimated salary 199,992 maximum tenure 10, maximum numbers of product 4, highest credit store 185.

### Recommendations
1. **Investigate Reason For Customer Churn**: There should be survey on the 2,037 customer churn in other to get feedback on the reason for churn and address a possible solution, high churn rates often indicate underlying issues, such as poor customer experience, inefficient processes, or a lack of competitive products and features, high cost of fee, poor fraud management. Therefore, understanding and managing customer attrition are crucial for banks to address these challenges and enhance their overall customer experience.

2. **Churn prevention strategies**:
- Leverage every channel (use multiple channels).
- Get client feedback.
- Communicate regularly.
- Improve customers satisfaction.
- Utilize re-engagement emails.
- Offer competitive incentive.
- Prioritize client education.
- Evaluate the target market.
- Identify valuables and at risk customers.
- Provides annual and long time agreements.
- App friendly
3. **Card fees and interest rate**: 2,945 customers have no credit card, reasons could be high rate cost of the credit card or the rate of frequent charges assign to credit card, therefore the bank should consider fees reduction on both in order to dive customers attention focusing on its important.
4. ** In-active prevention strategies **: 4,849 customers are not active, reasons could be high rate cost of products or lack of competitive products or the rate of frequent charges assign to service render, or App not friendly, therefore the bank should consider developing digital App friendly, provides competitive product and reduction in product and service fees.
5. **Provide excellent customers service**: Train staff to be helpful and friendly, creating a positive experience for banking.
6. **Create a welcoming atmosphere**: Ensure cleanliness, good lightning and comfortable seating.
7. **Leverage technology**: Implement user-friendly websites and mobile apps for navigation, promotion, and online banking options.
8. **General survey on inactive customers**: Total number of 3,547 customers are with the bank yet inactive which is no much different from exit due to their stagnation, reasons could be competitors offers, death occurrence or poor management system, a survey should be carry out on such customers to acquire useful information on feedback.

### Limitations
1. **Lack of customers feedback data**: Customer feedback would significantly enhance understanding of the rating distributions and offer targeted ways to improve customer satisfaction.
2. **Inadequate information**: Vital information where not included such as the date, customers rating and other banking information 

### Conclusion
- The bank should focus on improving customer experience, providing better products and services with a good working environment and loyalty program, also offering competitive product with fair rates, and being accessible through digital channels.


