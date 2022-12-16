Creating a basic web application in AWS.
This is a project about creating a web application using serverless services in AWS. 
A bucket was created in mumbai and HTML file(refer index.html) is uploaded as object. The bucket is made as static website hosting(Refer s3 bucket policy). A function is created in Lambda and deployed(Refer lambda function file). An API Gateway was created to provide interaction between S3 website and Lambda. Now a dynamoDB was created to store the outputs from website as key-value pair, for this ti happen proper IAM permissions for Lambada was given(refer lambda iam policy).

![High level diagram](https://user-images.githubusercontent.com/62993058/208028699-257374be-0664-4d5d-830a-c3d7b8db5ffe.jpg)

