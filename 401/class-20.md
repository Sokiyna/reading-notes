# Events

1- List the AWS Database offerings and talk about the pros and cons of each?

Relational ----> Traditional applications, ERP, CRM, e-commerce
Key-value ----> High-traffic web apps, e-commerce systems, gaming applications
In-memory ----> Caching, session management, gaming leaderboards, geospatial applications
Document -----> Content management, catalogs, user profiles
Wide Column ----> High scale industrial apps for equipment maintenance, fleet management, and route optimization.
Graph ---->Fraud detection, social networking, recommendation engines.
Time Series ----> IoT applications, DevOps, industrial telemetry
Ledger -----> Systems of record, supply chain, registrations, banking transactions.


2- What’s the difference between a FIFO and a standard queue?

FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.

3- How can the server be assured a message was properly received?

by getting an acknowledgement from the client.

### Terms

**Serverless API**: Its is an API deployed by serverless service.

**Triggers**: are pieces of code that will automatically respond to any events in DynamoDB Streams. Triggers allow you to build applications that will then react to any data modification made in DynamoDB tables.

**Dynamo vs Mongo :** Mongo can be deployed anywhere, Dynamo is only available on AWS Mongo is JSON based document store, Dynamo is limited key-value store with JSON support Mongo is rich query language, Dynamo is key-value queries.
**Dynamoose vs Mongoose:** Dynamoose is a DynamoDB API structured like Mongoose, lets us provide a schema and perform CRUD operations against a DynamoDB table, installed via node and configured based on role.

## Preparation Materials

SQS - Simple queue service Distributed queuing system Messages are not pushed to receivers, receivers have to poll SQS to receive messages Messages can’t be received by multiple receivers at the same time Any one receiver can receive a message, process and delete it, other receivers do not receive the same message later Mainly used to decouple applications or integrate applications Messages can be stored in SQS for short duration of time (max 14 days) SNS - Simple notification service Fast, flexible and fully managed push notification service that lets you send individual messages or bulk messages Distributed publish/subscribe system Messages are pushed to subscribers as and when they are sent by publishers to SNS SNS supports several end points such as email, sms, http end point and SQS If you want unknown number and type of subscribers to receive messages, you need SNS.
