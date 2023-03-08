#### [AWS API Gateway Overview](https://www.serverless.com/guides/amazon-api-gateway)

#### What is Amazon API Gateway?
 Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic.

#### Why is Amazon API Gateway an important part of the Serverless ecosystem?
  Because you need it to trigger the execution of a serverless function from an HTTP request. 

#### How does API Gateway integrate with other AWS services?
1. Invoking an AWS Lambda function.
2. Invoking another HTTP endpoint, with or without VPC Link.
3. Making an HTTP call against the API of any AWS service that provides an HTTP API.
4. Returning a mock response generated within API Gateway without calling out to other services.


## [AWS API Gateway](https://aws.amazon.com/api-gateway/)

#### What are the some benefits of using Amazon API Gateway?
Efficient API development,  low cost, easy to monitor, has different RESTful API options

#### What two API types might you choose from?
RESTful API, WebSocket APIs

## [AWS DynamoDB Guide](https://www.dynamodbguide.com/what-is-dynamo-db/)

#### What is DynamoDB?
noSQL database service

#### Under what circumstances would you recommend DynamoDB over MongoDB?
When you chose to use AWS. 


## [AWS DynamoDB](https://aws.amazon.com/dynamodb/)

#### Explain to a non-technical friend how DynamoDB works.
A place where you can organize and store different kinds of things like storage.


## [Dynamoose](https://dynamoosejs.com/getting_started/Introduction)

#### What is Dynamoose?
Dynamoose is a modeling tool for Amazon's DynamoDB
#### What are some key features of Dynamoose?
- Type safety
- High level API
- Easy to use syntax
- DynamoDB Single Table Design Support
- Ability to transform data before saving or retrieving items
- Strict data modeling (validation, required attributes, and more)
- Support for DynamoDB Transactions
- Powerful Conditional/Filtering Support
- Callback & Promise support
- AWS Multi-region support
