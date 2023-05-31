COMP41680/COMP47670 Assignment 2
----------------------------------

## SUMMARY 

This assignment involves working with a dataset of bank customer satisfaction survey responses. The general objective here is to predict whether customers are satisfied with the bank based on their survey responses. The dataset consists of two different representations for the same set of customers:

1. Tabular data (bank-tabular.csv) which contains demographic information about each customer and ratings scores (1-5) relating to different aspects of their bank. A manually-labelled ‘satisfied’ variable indicates whether a customer is ‘satisfied’ or ‘dissatisfied’ with the bank.

2. Text data (bank-comments.csv) which contains short textual comments indicating customers' opinions regarding the bank. 


## FILE FORMATS 

The file bank-tabular.csv is a tab-separated text file containing the following fields:

 - customer_id: A unique identifier for each customer.
 - date: The date on which the survey was conducted.
 - customer_gender: The gender of the customer.
 - customer_age: The age of the customer.
 - customer_location: The location of the customer in Ireland.
 - customer_type: The type of the customer.
 - has_cc: Indicates whether or not the customer has a credit card with the bank.
 - has_mortgage: Indicates whether or not the customer has a mortgage with the bank.
 - convenience: The customer's rating score (1-5) for the availability and accessibility of the bank. Customers want their bank to be easily accessible through multiple channels such as branches and ATMs.
 - customer_service: A rating score (1-5) for customer service, including response time, friendliness, and competence of bank staff.
 - online_banking: A score (1-5) for the ease of use, functionality, and availability of online banking services
 - interest_rates: A score (1-5), where customers may be more satisfied with their bank if they offer competitive interest rates on savings and mortgages.
 - fees_charges: A score (1-5), where customers may be more dissatisfied when they are charged fees for services they did not expect, or when the fees/charges are high.
 - community_involvement: A score (1-5), where customers may have a more favorable view of their bank if they are involved in the local community and support charitable causes.
 - products_services: A score (1-5) which relates to the quality and variety of products and services offered by the bank.
 - privacy_security: The customer's score (1-5) reflecting whether customers believe their bank provides high levels of security and privacy, and manage their personal data carefully.
 - reputation: A score (1-5) indicating whether customers believe their bank has a good reputation for reliability and ethical practices.
 - satisfied: A manually-assigned boolean value indicating whether a customer is satisfied overall with their bank.


The file bank-comments.csv is a tab-separated text file containing the following fields:

- customer_id: A unique identifier for each customer.
- date: The date on which the survey was conducted.
- comments: The short text comments provided by customers about their bank.

