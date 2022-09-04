# Project: Data Modeling with Cassandra

A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.
The objective is to create an Apache Cassandra database which can create queries on song play data to answer the questions. 

## Project Overview

The data modeling is done with Apache Cassandra and an ETL pipeline is developed using Python. Modelling of data is done by creating tables in Apache Cassandra to run queries. The ETL pipeline transfers data from a set of CSV files within a directory to create a streamlined CSV file to model and insert data into Apache Cassandra tables.
