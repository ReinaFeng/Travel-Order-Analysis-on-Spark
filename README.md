# Travel-Order-Analysis-on-Spark
### Off-Online - Spark Core
### Real-time - SparkStreaming
* Based on the log data of Lvmama Travel Platform, implemented off-line analysis for user behaviors by SparkCore and real-time analysis for sale orders by SparkStreaming.
* Simulated the production of sales order data in JSON format. Received data from Kafka Topic and calculated real-time sales amount of each province and the top 5 provinces with the highest order amount in the last 20 minutes. Saved the results to Redis at the same time.
* Read log data from HDFS, executed ETL and saved a new table to HBase. Counted the number of new users on the basic dimension and browser dimension using SparkSQL. Saved the results to MySQL.
