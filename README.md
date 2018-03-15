# AWS-Lambda-Example

It contains a very basic AWS Lambda example to start with. In order to run the project:

1) Create a jar of the project

> **mvn clean package**

2) Upload the jar in AWS lambda console.

3) Set up an API gateway for the lambda.

4) Hit the API gateway through postman with the following json body:

> **{
   "message" : "Hello Coders"
}**
