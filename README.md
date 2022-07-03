# Implementing_Data_Warehouse_for_e-Commerce_in_Hive

## Agenda
We will dig deeper into some of the Hive's analytical features for this hive project. Using
SQL is still highly popular, and it will be for the foreseeable future. Most big data
technologies have been modified to allow users to interact with them using SQL. This is
due to the years of experience and expertise put into training, acceptance, tooling,
standard development, and re-engineering. So, in many circumstances, employing
these excellent SQL tools to access data may answer many analytical queries without
resorting to machine learning, business intelligence, or data mining.
This big data project will look at Hive's capabilities to run analytical queries on massive
datasets. We will use the Adventure works dataset in a MySQL dataset for this project,
and we'll need to ingest and modify the data. We'll use Adventure works sales and
Customer demographics data to perform analysis and answer the following questions:

&emsp;● Which age group of customers contribute to more sales?

&emsp;● To find the upper and lower discount limits offered for any product

&emsp;● Sales contributions by customer

&emsp;● To Understand customer persona purchasing pattern based on gender, education
and yearly income

&emsp;● To find the sales contribution by customers on the overall year to date sales
belong to categorized by same gender, yearly income.

&emsp;● To identify the top performing territory based on sales

&emsp;● To find the territory-wise sales and their adherence to the defined sales quota.

## Aim
To perform Hive analytics on Sales and Customer Demographics data using big data
tools such as Sqoop, Spark, and HDFS.
## Data Description
Adventure Works is a free sample database of retail sales data. In this project, we will
be only using Customer test, Individual test, Credit card, Sales order details, Store,
Sales territory, Salesperson, Sales order header, Special offer tables from this
database.
## Tech Stack

➔ Language: SQL, Python

➔ Services: AWS EC2, Docker, MySQL, Sqoop, Hive, HDFS, Spark

### AWS EC2
Amazon EC2 instance is a virtual server on Amazon's Elastic Compute Cloud (EC2) for
executing applications on the Amazon Web Services (AWS) architecture. Corporate
customers can use the Amazon Elastic Compute Cloud (EC2) service to run
applications in a computer environment. Amazon EC2 eliminates the need for upfront
hardware investment, allowing customers to design and deploy projects quickly. Users
can launch up to 10 virtual servers, configure security and networking, and manage
storage on Amazon EC2.

### Docker
Docker is a free and open-source containerization platform, and it enables programmers
to package programs into containers. These standardized executable components
combine application source code with the libraries and dependencies required to run
that code in any environment.

### Sqoop
Sqoop is a data transfer mechanism for Hadoop and relational database servers. It is
used to import data from relational databases such as MySQL and Oracle into Hadoop
HDFS, Hive, and export data from the Hadoop file system to relational databases.

### Hive
Apache Hive is a fault-tolerant distributed data warehouse that allows for massive-scale
analytics. Using SQL, Hive allows users to read, write, and manage petabytes of data.
Hive is built on top of Apache Hadoop, an open-source platform for storing and
processing large amounts of data. As a result, Hive is inextricably linked to Hadoop and
is designed to process petabytes of data quickly. Hive is distinguished by its ability to
query large datasets with a SQL-like interface utilizing Apache Tez or MapReduce.

## Approach
&emsp;● Create an AWS EC2 instance and launch it.

&emsp;● Create docker images using docker-compose file on EC2 machine via ssh.

&emsp;● Create tables in MySQL.

&emsp;● Load data from MySQL into HDFS storage using Sqoop commands.

&emsp;● Move data from HDFS to Hive.

&emsp;● Integrate Hive into Spark.

&emsp;● Using python programming language, extract Customer demographics information
from data and senting it to hive through pyspark.

&emsp;● Create tables in Hive and load data in proper data format in hive.

&emsp;● Perform Hive analytics on Sales and Customer demographics data.

## Project Takeaways
&emsp;● Understanding various services provided by AWS

&emsp;● Creating an AWS EC2 instance

&emsp;● Connecting to an AWS EC2 instance via SSH

&emsp;● Introduction to Docker

&emsp;● Visualizing the complete Architecture of the system

&emsp;● Usage of docker-composer and starting all tools

&emsp;● Copying a file from a local machine to an EC2 machine

&emsp;● Understanding the schema of the dataset

&emsp;● Data ingestion/transformation using Sqoop, Spark, and Hive

&emsp;● Moving the data from MySQL to HDFS

&emsp;● Creating Hive table and troubleshooting it

&emsp;● Understanding the use of GROUP BY, GROUPING SETS, ROLL-UP, CUBE
clauses

&emsp;● Understanding different analytic functions in Hive

![Structure](https://user-images.githubusercontent.com/107996709/177049106-cbcd2545-9743-438d-8d8b-2a10753a7c7a.jpg)
