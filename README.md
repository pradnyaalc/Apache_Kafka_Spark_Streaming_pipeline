# Apache_Kafka_Spark_Streaming_pipeline
Analysis of fire in Victorian cities

### Requirements
- Apache Kafka
- Apache Spark
- Mongodb

### Steps to run

Start mongodb service

```
systemctl start mongodb
```

Start Kafka zookeeper and server:

```
bin/zookeeper-server-start.sh config/zookeeper.properties
bin/kafka-server-start.sh config/server.properties
```

Mongodb queries
- run the cells in Assignment_TaskA_TaskB.ipynb

Kafka Producers
- run the cells in Assignment_TaskC_Producer1.ipynb, Assignment_TaskC_Producer2.ipynb, Assignment_TaskC_Producer3.ipynb

Spark Streaming
- run the cells in Assignment_TaskC_Streaming_Application.ipynb

Visualizations
- run the cells in Assignment_TaskC_Data_visualisation.ipynb

