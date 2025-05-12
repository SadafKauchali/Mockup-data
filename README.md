SQL MOCKUP DATA :

Project Goals
Using knowledge of SQLanalyze some mockup learners data. There are two tables:

users table:

user_id
email_domain
country
postal
mobile_app
sign_up_at

progress table:

user_id
learn_cpp
learn_sql
learn_html
learn_javascript
learn_java

 1) View the Tables
 2) First, use SELECT * from both tables and use your knowledge of queries and aggregate functions to get to know the data:

      a.What are the Top 25 schools (.edu domains)?
      b.How many .edu learners are located in New York?
      c.The mobile_app column contains either mobile-user or NULL. How many of these Codecademy learners are using the mobile app?


3)The data type of the sign_up_at column is DATETIME. It is for storing a date/time value in the database.

 The values are formatted like:
 2015-01-01 18:33:52
 So the format is:
 YYYY-MM-DD HH:MM:SS

(SQLite comes with a strftime() function - a very powerful function that allows you to return a formatted date.)
It takes two arguments:
strftime(format, column)

4.)
Join the two tables using JOIN and then see what you can dig out of the data!

 a) Do different schools (.edu domains) prefer different courses?
 b) What courses are the New Yorkers students taking?
 c) What courses are the Chicago students taking?
