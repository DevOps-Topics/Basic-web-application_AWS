# AWS_Notes
This project we are going to see how to deploy a Basic web application in AWS using AWS services like (S3, Lambda, API Gateway, IAM Permissions, DynamoDB table). All the resources used in this project are under AWS Free tier.
1.S3 bucket will be created to store files related to our website and bucket will act as static website hosting.
2.Proper persmissions were given to lambda to make sure that lambda will be able to write in dynamodb table.
3.A lambda function will be triggered by API Gateway whenever events happen in index.html. 
4.As a result a output can be seen in index.html and also the outputs will be stored in Dynamodb table created by us. 




