# Implementation of Decision Tree using Spark Framework over a Databricks cluster
This project is a implementation of a Decision-Tree Supervised learning algorithm on Spark Execution Engine over Databricks Cluster (its Community Cloud Service)

[DBFS](https://docs.databricks.com/user-guide/dbfs-databricks-file-system.html) is a Databricks File System that allows you to store data for querying inside of Databricks. This notebook assumes that you have a file already inside of DBFS that you would like to read from.
 
I have performed the following in Spark:
1. Generate a categorical variable from a numeric variable
2. Aggregate the features into one single column
3. Randomly split the data into training and test sets
4. Create a decision tree classifier to predict days with low humidity.

The project has been also implemented using KNIME Software to test it with Spark results to check consistency.
