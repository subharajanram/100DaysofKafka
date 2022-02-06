**100DaysofKafka** Event Streaming Platform: Collect Store and Processing Data

Kafka = Distributed event streaming platform: combines reliable and scalable messaging 
and processing capabilities into a single unified platform
which is not supported by  individual technologies.

Traditional databases offer storage and data retrieval of past data but dont help if we need to process future events.
Messaging technologies do not have storage thus cannot handle past data.

By combining messaging and storage, Kafka is able to handle future and past data using some 
underlying storage known as distributed commit log.

Kafka is able to handle data from every point in time past present and future - opening for event streaming
applications.

Event Streaming applications: Handle events as they happen - present data while in transit.

==========================================

Hosted solution vs Managed services.

Managed services: Provide experience of Kakfa without knowledge of operating it.

Hosted solutions: Involve creating dedicated Kafka clusters, sclaing, patching, upgrading. 
User has this responsibility. (on premise)

Kafka ecosystem -> Confluent Schema Registry, Kafka Connect, Kafka Streams, ksqlDB, 

Serverless Computing Model:

Compute, Storage and Network ( Resources necessary to deploy a Kafka cluster in a given Cloud Provider)

============================================
Apache Kafka is a distributed streaming platform comprised of messaging, storage, and stream processing. By translating this into concrete technologies, you will find that Apache Kafka is made up of:

Core Kafka: brokers that implement messaging and storage capabilities
Clients API: framework for creating producers (writers) and consumers (readers)
Kafka Connect: framework for scalably moving data into and out of Apache Kafka
Schema Registry: repository service for metadata and schemas using the REST API
Kafka Streams: framework for implementing stream processing applications

