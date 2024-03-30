# Serverless Web-application.

This project primary aim is to store user registered information in a NoSql Database (DynamoDB) and uploaded the HTML, CSS, JS files in S3 bucket and given public access to the bucket so that anyone can access it with the bucket URL. Apart from that in Fit Fusion Hub provide a comprehensive online platform for fitness enthusiasts, offering a range of resources, tools, and community support to help individuals achieve their health and fitness goals. Whether you're a seasoned athlete or just starting your fitness journey, Fit Fusion Hub Gym has something for everyone.


### AWS Services.

* AWS DynamoDB.
* AWS Lambda.
* IAM Role.
* API Gateway.
* S3 (Simple Storage Service).


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
*	After Deploying API a URL is given to me and copied that URL and pasted in registration form java script code.
*	Then, created one S3 Bucket and uploaded all the HTML, CSS , JS files related to website in that bucket and given public access to the files and bucket.
*	Copied index.html file link in the bucket and pasted in the browser and gym website is opened. 
*	After that try registering dummy user in that form and it was successfully stored in AWS DynamoDB Table that I have created.
*	S3 bucket Which I have created is for public access to give that link to anyone for testing purpose, Creating S3 Bucket is not mandatory You can also Paste the API Gateway link in Registration form JS on Visual Studio Code, you will get the registration successful and the User data will be stored in the DynamoDB.



### Project Link.

* Video URL : https://drive.google.com/file/d/1mrwdPCgiUXjNtd3Pcz0pguMzZDZLly0t/view?usp=drive_link
