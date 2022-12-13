# AWS_Notes
This project we are going to see how to deploy a Basic web application in AWS using AWS services like (S3, Lambda, API Gateway, IAM Permissions, DynamoDB table). All the resources are under AWS Free tier.
S3 bucket will be created to store files related to our website and bucket will act as static website hosting.
A lambda function which will be triggered by API Gateway whenever events happen in index.html. As a result a output can be seen in index.html and also the outputs will be stored in Dynamodb table created by us. 
Proper persmissions will be given to lambda to make sure that lambda will be able to write in dynamodb table.



