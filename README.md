# Serverless Web-application.

This project primary aim is to store user registered information in a NoSql Database (DynamoDB) using some AWS Service. Apart from that in Fit Fusion Hub provide a comprehensive online platform for fitness enthusiasts, offering a range of resources, tools, and community support to help individuals achieve their health and fitness goals. Whether you're a seasoned athlete or just starting your fitness journey, Fit Fusion Hub Gym has something for everyone.


### AWS Services.

* AWS DynamoDB.
* AWS Lambda.
* IAM Role.
* API Gateway.


### Web Technologies Used.

* HTML.
* CSS.
* JS.
* Python.

### IDE Used.

Visual Studio Code.


### Steps.

*	Created the Fit Fusion Hub Website in visual studio code using HTML, CSS, JS.
*	Created a DynamoDB Table in AWS and given a name and partition key.
*	Then Created IAM Role for AWS Lambda to give full access to AWS DynamoDB.
*	Then Created AWS Lambda function and given a name, runtime is python and finally attached the IAM Role that I have created for AWS Lambda.
*	After Creating Lambda function, I have given the python code and click on deploy. In the Python code given the DynamoDB table name that I have created.
*	After the python code is deployed, then I have created an API Gateway in AWS using REST API, inside that REST API I created a resource, methods, enabling CORS and Deploying API.
*	In the REST API Methods, I have given type as POST and Service is Lambda, it by automatically shows the Lambda Function that I created click on that and save.
*	After Deploying API a URL is given to me and copied that URL and pasted in registration form java script page.
*	After that try registering dummy user in that form and it was successfully stored in AWS DynamoDB Table that I have created.

