# Credit_Risk_Analysis

Results:

The naive random oversampling has an accuracy score of 64.3%, a precision of nearly 100%, and a recall of 69%.

The smote oversampling algorithm has an accuracy score of 64.7% with a precision of nearly 100% and a recall of 73%.

The cluster centroid method, an undersampling method, has an accuracy score of 64.7% with precisions and recall of nearly 100% and 52% respectively.


Follow the instructions below to complete Deliverable 1.
1.	From the following Amazon Review datasetsLinks to an external site., pick a dataset that you would like to analyze. All the datasets have the same schemata, as shown in this image:

2.	Create a new database with Amazon RDS just as you did in this module.

3.	In pgAdmin, create a new database in your Amazon RDS server that you just create.

![image](https://user-images.githubusercontent.com/117233641/232625201-7276e7e3-40f4-4f44-8ea4-2fb0e9ecd8c4.png)

4.	Download the challenge_schema.sql file to your computer.

5.	In pgAdmin, run a new query to create the tables for your new database using the code from the challenge_schema.sql file.
      o	After you run the query, you should have the following four tables in your database: customers_table, products_table, review_id_table, and vine_table.

![image](https://user-images.githubusercontent.com/117233641/232625366-a1a91631-c32a-4e49-b03d-3d7d56c78bd2.png)


7.	Download the Amazon_Reviews_ETL_starter_code.ipynb file, then upload the file as a Google Colab Notebook, and rename it Amazon_Reviews_ETL.

8.	First extract one of the review datasets, then create a new DataFrame.

![image](https://user-images.githubusercontent.com/117233641/232625437-55a74da2-e703-4c91-87dc-bf93747282f6.png)

Next, follow the steps below to transform the dataset into four DataFrames that will match the schema in the pgAdmin tables:

![image](https://user-images.githubusercontent.com/117233641/232625508-7b888212-0888-4b42-8cc9-45dc6545b160.png)

![image](https://user-images.githubusercontent.com/117233641/232625531-ed29527f-bcec-4633-af3e-21d493811871.png)


The customers_table DataFrame

To create the customers_table, use the code in the Amazon_Reviews_ETL_starter_code.ipynb file and follow the steps below to aggregate the reviews by customer_id.

    •	Use the groupby() function on the customer_id column of the DataFrame you created in Step 7.

    •	Count all the customer ids using the agg() function by chaining it to the groupby() function. After you use this function, a new column will be created, count(customer_id).

    •	Rename the count(customer_id) column using the withColumnRenamed() function so it matches the schema for the customers_table in pgAdmin.

•	The final customers_table DataFrame should look like this:

![image](https://user-images.githubusercontent.com/117233641/232625633-b1dfb045-0363-4b2d-b94e-c3909a984516.png)



