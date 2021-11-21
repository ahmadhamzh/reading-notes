# Review, Research, and Discussion

### What’s the difference between a FIFO and a standard queue?

Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.

### How can the server be assured a message was properly received?

when the client get a message from the server the client wil send a message to the server that it receved the message.

### What classic design pattern is best represented by event driven programming?

observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

### How do you test an event driven system?

Service tests for event-driven systems operate on events for inputs and events for outputs and are unaware of other services. End-to-end Tests.

---


term   |   Discripe
-| -
**FIFO Queue** | is the type of AWS SQS queue that guarantees order and provides exactly once delivery of messages.
**Pub/Sub** | which stands for Publisher/Subscriber, allows services to communicate asynchronously, with latencies on the order of 100 milliseconds.

### SNS 

Amazon Simple Notification Service (Amazon SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication.

### SQS

Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.