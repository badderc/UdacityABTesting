# Udacity Project 2
## Practical Statistics: A/B Testing
An analysis of A/B test results for the practical statistics portion of the Udacity Data Analyst Nanodegree

## Premise
A/B tests are very commonly performed by data analysts and data scientists.  It is important to get some practice working with the difficulties of these tests.

For this project, I worked to understand the results of an A/B test run by an e-commerce website.  The goal was to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## Data
Fake company data provided by Udacity. The file ab_data.csv contained the following fields:
* user_id: A unique identifier for each user that entered the company website
* timestamp: The point in time that the user entered the website
* group: Whether the user was part of the control or treatment group
* landing_page: Whether the user received the old page or the new one
* converted: 0 if the customer did not convert and 1 if the customer did

## Tools and Skills
* Pandas, Numpy, random, statsmodels, and matplotlib packages were utilized
* Hypothesis testing
* Logistic Regression

