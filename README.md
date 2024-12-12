# Rt-Data-Streaming
 Random Guest Generator API – Streaming Data Pipeline [Apache Airflow | PostgreSQL | 
Apache Kafka | Apache Spark | Cassandra | Docker] 
This project involves generating random guest data via an API, which is sent to Apache Airflow for 
orchestrating workflows. The data is stored in PostgreSQL and streamed to Apache Kafka, managed 
by Zookeeper. Kafka then streams the data to Apache Spark for distributed processing using its 
master-worker architecture. The processed data is stored in Cassandra for real-time querying. 
Docker is used for containerization, ensuring efficient deployment and scalability. 
