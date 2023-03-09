## [AWS SQS vs SNS](https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5)

#### What is the difference betweeen SQS and SNS?
SNS is a distributed publish-subscribe service, and SQS is distributed queuing service.
SNS supports several end points such as email, sms, http end point and SQS.
#### What are some use cases for both SNS and SQS?
SNS : Sending email, SMS, and push notifications to end-users in realtime
SQS : Asynchronous processing workflows

## AWS SNS and SQS

#### Describe how to use SQS and SNS in a “fanout” pattern.
 a message is sent to a single topic in SNS, which then sends the same message to multiple SQS queues.
#### Explain how “push notifications” work, using SNS.
Push notifications allow mobile applications to receive messages from remote servers. Using SNS, the server sends a message to the AWS SNS topic. The topic then delivers the message to mobile devices subscribed to the topic via push notifications. The devices receive and display the message to the user, enabling real-time communication between the server and the mobile application.


## SQS and SNS Basics

### How might a large scale, distributed application make use of a Queue system like SQS?
