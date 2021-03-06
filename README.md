# Spark Project

# Restaurant Management Analysis

# Description :

The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the establishment
of different types of restaurant at different places in Bengaluru.Bengaluru being an IT capital of India.
Most of the people here are dependent mainly on the restaurant food as they don't have time to cook for themselves.
With such an overwhelming demand of restaurants it has therefore become important to study the demography of a location. 
What kind of a food is more popular in a locality.


# Environment / Technologies

1. HDFS <br>
2. Hive <br>
3. Hadoop <br> 
4. SparkSQL <br>
5. PySpark <br>
6. Jupyter Notebook <br>

# Features :
1. Availability of 20 columns which gives the entire details of the restaurants
2. Maintaing the list of reviews
3. Availability of Rating and Voting of the restaurants
4. The average cost for two people are also maintained
5. Availability of extra features like acceptable payment mode, Discounts, Catering and Capacity of the restaurants 
6. Availability of online order and table booking facilities

# Getting Started :

Firstly, we have downloaded the Zomato dataset from Kaggle website by using the following link https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants
This dataset is very large and consisting of noisy data. So we perform preprocessing of data and the entire code for preprocessing the data is given in the jupyter file.
We also add few columns like discount, capacity, acceptable payment mode, catering etc to the existing data.

The structure of the data is as follows : <br>
 |-- url: string (nullable = true) <br>
 |-- address: string (nullable = true) <br>
 |-- name: string (nullable = true) <br>
 |-- online_order: string (nullable = true) <br>
 |-- book_table: string (nullable = true) <br>
 |-- rate: double (nullable = true) <br>
 |-- votes: integer (nullable = true) <br>
 |-- phone: string (nullable = true) <br>
 |-- location: string (nullable = true) <br>
 |-- rest_type: string (nullable = true) <br>
 |-- cuisines: string (nullable = true) <br>
 |-- approx_cost_for_two_people: integer (nullable = true) <br>
 |-- reviews_list: string (nullable = true) <br>
 |-- menu_item: string (nullable = true) <br>
 |-- listed_in_type: string (nullable = true) <br>
 |-- listed_in_city: string (nullable = true) <br>
 |-- payMode: string (nullable = true) <br>
 |-- Discount: integer (nullable = true) <br>
 |-- Capacity: integer (nullable = true) <br>
 |-- Catering: string (nullable = true) <br>

On this structured data we performed analysis and extracted usecases from user perspective. 
The usecases and their corresponding queries are clearly mentioned in the document file.
We performed the analysis in both PySpark and SparkSQL.
We performed partioning and bucketing too.

# Roles / Responsibilities <br>

1.After a lot of research, we utilized the Zomato restaurant dataset from the Kaggle website which is more suitable for the project. <br>
2.Preprocessed the dataset as it consists of a lot of messy data and added few columns to the existing dataset using Python pandas. <br>
3.Loaded the sample data into Hadoop HDFS, then created a table in the Hive warehouse. <br>
4.Configured the hive metastore in Spark in order to access the hive tables from Spark. <br>
5.Worked with Data Frames and SparkSQL functions to manipulate and query the restaurant data. <br>
6.Performed the same queries which are done through SparkSQL in Pyspark too using Python. <br>
7.Performed performance tunning i.e., partitioning and bucketing for better performance. <br>
8.Extracted various use cases from the tables from the user's perspective. <br>
9.Organized results into a PowerPoint presentation and uploaded the entire project into GitHub. <br>

# Team Members :

1. Eswar - Data Analytics <br>
2. Suleman - Data Collection and Preprocessing <br>
3. Neha - Quality Assurance <br>
4. Subodh - Cluster Manager <br>

