# nosql-challenge

for this challenge we have three parts that we are going to work with 
1 Database and Jupyter Notebook Set Up: on this part we are going to Import the data provided in the establishments.json file from the Terminal. 
                                      : on this part we Create an instance of the Mongo Client and we Confirm that we created the database and loaded the data properly

2 Update the Database : we are going to make the following changes to the establishments collection
3 Exploratory Analysis: we refers to the overall rating decided by the Food Authority and ranges from 1-5. The higher the value, the better the rating 
                       Note: This field also includes non-numeric values such as 'Pass', where 'Pass' means that the establishment passed their inspection but isn't given a number rating. We will coerce non-numeric values to nulls during the database setup before converting ratings to integers.

