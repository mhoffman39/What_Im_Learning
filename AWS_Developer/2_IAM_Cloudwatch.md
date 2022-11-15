# Sounding the Alarm with IAM and Cloudwatch

## CloudWatch - set alarms and notifications in response to events

### CloudWatch Overview
CloudWatch - a service to set alarms based on service metric thresholds (ex. CPU usage, estimated billing charges, etc.)

SNS - Simple Notification Service
1. Determines where alerts are sent (email, SMS, http requests, etc.)
1. Ten cents per alarm each month

The main structure in SNS is the topic. A topic is used to create a unique Amazon Resource Name (ARN) that can then have notifications sent to it.

CloudWatch can also trigger actions based on events (trigger Auto Scaling, add additional instances, etc.)
## IAM - simple user and access management
Controls who can have access to what.

Passwords, MFM, Access Keys, SSH Keys for all users on the account

Policy - a collection of permissions to access different services in a particular way 

### Configuring Users and Groups
Groups - apply policies to a group, vice an individual