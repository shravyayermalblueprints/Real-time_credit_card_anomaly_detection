# Real-time-credit-card-anomaly-detection

Let's assume I have a bank card. My previous purchasing patterns will be discovered. Such as how much money I spend, where I shop, how often I spend, what I buy, etc. Based on this knowledge, my current credit transaction will be suspected of deception if it differs from my previous purchasing patterns; otherwise, it will be considered legitimate. Additionally, the interface will notify me of any fraudulent transactions.

Such forecasts will be based on millions of transactions. Therefore, distributed systems are employed, which can grow as the number of deals rises.

Technology used:

1. Spark:

Distributed Processing Framework.
Single platform for different kinds of data processing: In-memory Data Processing.
RDD, Data frame, and Data set are used to represent data in Spark.


Apache Spark: 
Spark SQL |
Spark Streaming |
Spark ML |
Spark GraphX |
Spark R |


2. Kafka:
Distributed Persistent Circular Message Queue.
Messages are stored on the disk for durability.


Apache Kafka:
The application will send MESSAGES to the Kafka cluster.
Some other application that will consume data from the Kafka cluster.


3. Cassandra:

Distributed NoSQL Columnar Database.
Storage layer in data data-intensive project.

Apache Cassandra:
It follows a ring architecture and column-oriented database.
No single point of failure.
Writes are pretty fast.
Cassandra is a linearly scalable and flexible data storage.

Limitations:
Cassandra has built-in aggregations and joins.









<img width="671" alt="Screenshot 2023-02-28 at 11 22 35 AM" src="https://user-images.githubusercontent.com/37536963/222216992-84703385-009c-4767-83fa-1de58452ac5a.png">




