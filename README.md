### Real-Time Fraud Detection Pipeline


The project uses Scala, Kafka, Spark and Cassandra to create an end-to-end fraud detection pipeline. <br />
The fraud detection process creates a K-means and a Random Forest Model, which we load on our pipeline using Spark Streaming and estimates whether the transactions injested and processed in real-time from kafka are fraudulent or not. <br /> <br />
The results are then stored into cassandra and exposed to the end user through a rest api using sse.
