# AWS: Events

## AWS SQS vs SNS

1. What is the difference betweeen SQS and SNS?

   - The main difference between SQS and SNS is that SQS is a fully managed message queue service that enables you to decouple and scale microservices, distributed systems, and serverless applications, while SNS is a fully managed push notification service that enables you to send messages to multiple subscribers or other applications.

2. What are some use cases for both SNS and SQS?

   - Some use cases for SNS include sending SMS messages, email notifications, and mobile push notifications, while some use cases for SQS include building decoupled architectures, load balancing, and distributing background jobs.

## AWS SNS and SQS

1. Describe how to use SQS and SNS in a “fanout” pattern.

   - In a "fanout" pattern, you can use SNS to broadcast messages to multiple SQS queues, which can then be processed independently by separate consumers.

2. Explain how “push notifications” work, using SNS.

   - Push notifications work by using SNS to send messages to mobile devices or other endpoints, which can then be displayed to the user or used to trigger other actions.

## SQS and SNS Basics

1. How might a large scale, distributed application make use of a Queue system like SQS?

   - A large scale, distributed application might make use of a queue system like SQS to decouple and scale different parts of the application, allowing them to process and react to events independently and asynchronously.
