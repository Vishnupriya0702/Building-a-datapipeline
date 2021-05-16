# Building-a-datapipeline


First the source of a data - can be a Realtime datapipeline - (i.e Kafka) , which has source connector and sink connectors.
Secondly to make transformations - we use Spark. 
In Spark - we uses sqoop to take the data from Database and create partitions and perform transformations 
and create a file which can be send to respective vendors using MFT.

Kafka - source and sink connectors : SOurce is from where data is sourced from the Kafka Publisher
        Sink connectors : Data is published out of Kafka. 
        
