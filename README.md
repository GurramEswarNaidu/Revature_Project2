# Revature_Project2

# Description :

The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the establishment
of different types of restaurant at different places in Bengaluru.Bengaluru being an IT capital of India.
Most of the people here are dependent mainly on the restaurant food as they don't have time to cook for themselves.
With such an overwhelming demand of restaurants it has therefore become important to study the demography of a location. 
What kind of a food is more popular in a locality.

Firstly we have downloaded the zomato restaurant dataset from Kaggle.
You can download the dataset with the following link
https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants

As this dataset set is hugh and it has a lot of messy data, we performed preprocess of data and removed few records, replaced null values 
with appropriate values and we also add few columns like discount, capacity, acceptable payment mode, catering etc to the existing data.

The preprocessing code is given in the preprocessing file.

# The structure of the data is as follows :
 |-- url: string (nullable = true)
 |-- address: string (nullable = true)
 |-- name: string (nullable = true)
 |-- online_order: string (nullable = true)
 |-- book_table: string (nullable = true)
 |-- rate: double (nullable = true)
 |-- votes: integer (nullable = true)
 |-- phone: string (nullable = true)
 |-- location: string (nullable = true)
 |-- rest_type: string (nullable = true)
 |-- cuisines: string (nullable = true)
 |-- approx_cost_for_two_people: integer (nullable = true)
 |-- reviews_list: string (nullable = true)
 |-- menu_item: string (nullable = true)
 |-- listed_in_type: string (nullable = true)
 |-- listed_in_city: string (nullable = true)
 |-- payMode: string (nullable = true)
 |-- Discount: integer (nullable = true)
 |-- Capacity: integer (nullable = true)
 |-- Catering: string (nullable = true)


# Contributions :

1. Eswar - Data Analytics
2. Suleman - Data Collection and Preprocessing
3. Neha - Quality Assurance

The query processed on this data are detaily explained in the document please go through it.

# Environment / Technologies

HDFS, Hive, Hadoop, SparkSQL, PySpark
