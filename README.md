## cassandra_ETL


# Introduction
A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

# overview
we will make cassandra model to help in some queries and answer on all questions we want

# Steps
- make ETL Pipeline to extract data from event_data 
- we make keyspace and tables(define columns ,put constraints ,parition,cluster column)
- insert all data in correct tables
- answer all question by query

# Tools
- python
- os
- glob
- pandas
- nosql(cassandra)
- json
- csv
