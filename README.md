# Order Message Queue System

This project aims to create a scalable and reliable order message queue system using Amazon Web Services (AWS). The system utilizes Amazon Simple Queue Service (SQS) and AWS Lambda to efficiently handle incoming orders and process them in a distributed and fault-tolerant manner.

_Amazon SQS_: SQS is used as a scalable and fully managed message queuing service. Each coffee shop has its dedicated SQS queue where incoming orders are placed.

_AWS Lambda Functions_: Lambda functions are used for processing orders asynchronously. Each coffee shop has its set of Lambda functions responsible for handling orders from the respective SQS queue.

<img width="615" alt="Screenshot 2024-04-01 at 11 03 37" src="https://github.com/mohsn13/Order-Message-Queue-System/assets/157317409/972b3068-4bf9-44a0-beaa-20c45ba2165f">
