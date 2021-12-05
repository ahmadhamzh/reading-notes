# Review, Research, and Discussion

### Describe the similarities between AWS API Gateway + Lambda functions and an ExpressJS Server

Amazon API Gateway and Express Gateway both have their strengths and weaknesses. Amazon API Gateway has a compelling case for massively scalable API gateways at a competitive price point. With Express Gateway, you are responsible for hosting and running your own API Gateway, which may be more or less expensive depending on your experience and the load on your API Gateway.

### List the AWS Database offerings and talk about the pros and cons of each

Amazon RDS Pros and Cons
Pros	|    Cons
-|-
Automated Patching	| Patching forces a downtime
Automated Backups	| No scale-out for write workloads
Encryption at rest and in-transit	| Downtime required for scaling operations
A significant improvement over on-premise databases	| No automated performance tuning
Integrated with the rest of the AWS ecosystem	 |Not a zero-administration database
No hardware maintenance needed |	No automated partition management
Simplified scaling in comparison to on-premise databases	| No automated compression management
Automated log shipping and read replica |	No root access to the server
Simplified disaster recovery and automatic failover |	No native support as a read replica for on-premise Databases
Automated additional storage allocation |	CPU and Storage performance is not guaranteed
Point in time recovery |	Zero data loss is not guaranteed


### What’s the difference between a FIFO and a standard queue?

Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.

### How can the server be assured a message was properly received?

by receiving a confirmation from the client that he receives the message.


term   |   Discripe
-| -
**Serverless API** | a cloud computing execution model where the cloud provider dynamically manages the allocation and provisioning of servers.
**Dynamo vs Mongo** | Both these databases support multi-document transactions, but with key differences: MongoDB supports read and writes to the same documents and fields in a single database transaction. DynamoDB lacks support for multiple operations within a single transaction.
**Dynamoose vs Mongoose** | Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, Mongoose is a packege allow yo o connect to mongoDB.

### SNS (Simple Notification Service)

Amazon SNS is a fast, flexible, fully managed push notification service that lets you send individual messages or to bulk messages to large numbers of recipients. Amazon SNS makes it simple and cost effective to send push notifications to mobile device users, email recipients or even send messages to other distributed services.


### SQS (Simple Queue Service)

Amazon SQS is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.

