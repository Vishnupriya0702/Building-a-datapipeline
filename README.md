# Building-a-datapipeline


First the source of a data - can be a Realtime datapipeline - (i.e Kafka) , which has source connector and sink connectors.
Secondly to make transformations - we use Spark. 
In Spark - we uses sqoop to take the data from Database and create partitions and perform transformations 
and create a file which can be send to respective vendors using MFT.

Kafka - source and sink connectors : SOurce is from where data is sourced from the Kafka Publisher
        Sink connectors : Data is published out of Kafka. 
        
Raw data from the network element from Kafka
Data from dimensional sources will be combined with Kafka data and then it will go into the Spark API's and then we use the data and then inject into the Databases.

From the Spark streaming data - we can send to Hive & external databases such as mongodb
This Data Movement has to go on hive table pipelines.

Schedulers used to run the data under this situation is Apache Airflow , Oozie





Bigdata Interview Questions:
How do you manage same dependency in multiple projects.
2. What is the licensing module you have as part of the product deployment.
3. How do you control volume of data getting injected into you data warehouse.
4. What is you day to day activities
5. What are the KPI's you use as part of your project.
6. . What's the size of data you deal with.

2. What is the size of your cluster.

3. What is the configuration of each node in the cluster

4. What is the most challenging thing you faced in your project & how did you overcome that.

