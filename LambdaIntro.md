# AWS Developer: An Introudction to AWS Lambda

## Understanding Serverless Functions

### Contextualizing Serverless

- History of computing from mainframe  --> personal computers --> Virtual Machines  -->  Cloud  --> Serverless 

- Serverless !== no servers. It just means that you don't have to worry AS MUCH about the servers the code is running on. Everything is taken care of by AWS (or the servide provider)

#### What is a serverless function
1. Event driven - function only runs when triggered by an event (i.e. file upload, API request, or on a schedule)

1. Code focused - Instead of managing the infrastructure surrounding the code, we can write code that helps to solve business problems

1. Managed machines - Code runs on machines that are completely managed by AWS

### Key Elements of Serverless Functions

#### Event Examples

1. File upload - PNG uploaded to S3; code runs to resize the image to a specific size to be used as a profile photo

1. Schedule times - Triggered from a Cronjob (for instance)

#### Benefits vs Drawbacks
Benefits - Cost (only pay for the time the function is running), scaling, third-party utilizations

Drawbacks - can be hard to debug, less control, cutting edge quirks

### Project 1 - Lambda Canary
1. Set run interval
1. Function reviews website and determines if it's running
1. Website status recorded

### Project 2 - Twitter Bot
1. Trigger every hour
1. Run code to send a tweet (randomize times)

### Project 3 - Workflow Automation
1. Scheduled event trigger at various times
1. Run business automation tasks - reminders to clients and employees

### Project 4 - New Customer Service
1. API gateway
1. Store info in DB
1. Send email to admin

## Working With AWS
### Intro to AWS Free Tier


