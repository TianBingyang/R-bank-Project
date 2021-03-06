# 5102Team6-BankProject
NUS BMK5102 R group project

# Process
- Data Loading
  - "bank-full.csv": 45211 * 17
  - "bank.csv": 4521 * 17
    - yes vs. no = 521:4000 -> not balanced
  - Use “bank.csv” to run your code for testing
- Data Cleaning
  - Make the data more readable and clear.
  - Make the data more balanced
  - “job”: mark as employed and unemployed, remove the rows with unknwon
  - "month", "day": remove these two cols
  - "age": divide this attribute to 2 types or 3 types depending on the result of clustering
- Factor Analysis [YW/ZY]
  - Try to address what are the most important factors that may affect customers' purchase.
- *Clustering (try) [BT/YS]
  - Find out which customer characteristics can be classified as similar categories. 
  - Visualization
- Predictive model
  - **Regression** [YW/ZY]
    - Linear or logictic?
    - Visualization
  - **Classification** [BT/YS]
    - Split the data into train and test datasets.
    - Create a model using training data
    - Find out what is the most accurate model for our case.
- Dashboard [YZ]
  - Dashboard using Shiny
  - Basic Visualization
  - predict


# Report
The report must include, but not limited to, the following components:
  - Case description
  - Data source
  - Case questions
    - What are the most important factors that may affect the probability of customers' subscription?
    - For those who successfully subscript to the bank, what characteristics do they share in common?
    - In order to get 100% probability of subscription, what should salesperson do in terms of contact method,duration...
  - Modeling methodology
  - Findings and conclusion
