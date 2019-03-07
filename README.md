# Prediction of Weather(low humidity days - susceptitbility for forest fire) through Implementation of Decision Tree using Spark Framework over a Databricks cluster
This project is used to predict weather forecast(low humidity days - susceptitbility for forest fire) through implementation of a Decision-Tree Supervised learning algorithm on Spark Execution Engine over Databricks Cluster (its Community Cloud Service) 

I have performed the following in Spark:
1. Generated low_humidity_days(a categorical variable) from relative_humidity_3pm (numeric variables)
2. Aggregate the features into one single column
3. Randomly split the data into training and test sets
4. Create a decision tree classifier to predict days with low humidity.

The project has been also implemented using KNIME Software to test it with Spark results to check consistency.
Note(regarding Databricks ) :  [DBFS](https://docs.databricks.com/user-guide/dbfs-databricks-file-system.html) is a Databricks File System that allows you to store data for querying inside of Databricks.
