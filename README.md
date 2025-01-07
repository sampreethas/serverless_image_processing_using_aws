# serverless_image_processing_using_aws
## Overview
This project demonstrates how to build a simple image processing workflow using AWS Step Functions and several AWS serverless technologies. The workflow simulates a business process where a user uploads a profile picture, checks its uniqueness, generates a thumbnail, and stores metadata. The entire process is orchestrated using AWS Step Functions and includes Lambda functions, DynamoDB, and SNS for notifications.

## Tools & Technologies Used
AWS Step Functions: To orchestrate the workflow.
AWS Lambda: For running custom code such as photo uniqueness check, thumbnail generation, and metadata storage.
Amazon DynamoDB: To store metadata associating the user with their photo.
Amazon SNS: To send notifications upon workflow completion.
AWS CloudFormation: For deploying the infrastructure.

## Workflow
![image](https://github.com/user-attachments/assets/99f30003-d010-447a-a261-b05b055e0d36)

## AWS step functions workflow
![image](https://github.com/user-attachments/assets/6c591eff-246e-4173-bc1e-3ef9f833df27)
