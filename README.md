# Starbucks-Capstone-Challenge
----

## Packages 
- pandas
- numpy
- sklearn
- seaborn
- matplotlib
- pandasql

## Project Overview
As a final step in the Data Science Nanodegree program of Udacity. We are given an artificial data supposedly mimicking the customer behavior for a specific product type sold in Starbucks stores.
As a promotion policy Starbucks send offer to their customers via different channels like web, email, mobile and social for each offer type. 
As a company policy each customer take different offers in different days based on the demographic of the customer.

In this project we have provided 3 dataset containing information about customers, orders and transactions. I analzed the data and aggregate these datasets to answer exploratory questions related to the data.


## Data Dictionary

### Portfolio data: contains attributes of each offer type (10 rows)
* id — Identity of the offer type
* offer_type — category of the offer (discount, informational or bogo)
* channels — which promotion channels is used (web, email, mobile and/or social)
* duration — how long (days) the offer is valid after receiving
* difficulty — minimum purchase quantity needed to be eligible for the offer
* reward — the amount the the customer will get as a discount when the difficulty criteria is met in duration period.


### Profile data: demographics of customers (17000 rows)
* gender — gender of the customer (M: Male, F:Female, O: Other)
* age — age of the customer
* id — customer id
* become_member_on — the date customer created an account
* income — annual income of the customer

### Transcript data — contains all the user activity on a time table (306534 rows)
* event — event description ( transaction, offer received, offer viewed or offer completed)
* person — customer id
* time — time in hours since start of test. The data begins at time t=0
* value — details of each record. If a customer received or viewed an offer then it contains the offer id. If a customer completed an offer it contains offer id that the customer completed. And lastly if the record is a purchase record, it contains the transaction amount.


The medium article on the data analysis can be found in this [link](https://medium.com/@rdvnmemis/data-science-nanodegree-program-a-case-study-for-starbucks-73709a074c76)