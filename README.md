# Serverless-Web-Application
AWS Web Application - Project Documentation
Overview
This documentation provides insights into the design and implementation of a simple web application using AWS services. The application, focused on mathematical operations, utilizes AWS Amplify, Lambda, IAM, API Gateway, and DynamoDB to create a robust and scalable solution.

Project Architecture 
<img width="822" alt="archi" src="https://github.com/abiagus/Serverless-Web-Application/assets/111486295/fcf92fcf-bdb9-452a-aa02-b0dcd417fcd0">


Services Utilized
1. Amplify
AWS Amplify simplifies frontend development, authentication, and hosting. The Amplify configuration in the amplify directory outlines the setup for authentication, hosting, and other frontend-related configurations.

2. Lambda
AWS Lambda functions, located in the amplify/backend/function directory, handle the backend logic and mathematical computations. These serverless functions are executed in response to events triggered by API Gateway.

3. IAM (Identity and Access Management)
IAM is used to manage access to AWS resources securely. The amplify/backend/backend-config.json file specifies IAM roles and policies, defining the permissions required for the application.

4. API Gateway
Custom API Gateway endpoints, configured in the amplify/backend/api directory, facilitate secure communication between the frontend and Lambda functions. These endpoints define the routes for mathematical operations.

5. DynamoDB
DynamoDB, a NoSQL database, stores and retrieves data for the web application. The DynamoDB configuration, found in the amplify/backend/storage directory, defines the schema and settings for the database.

Recording of the Working Web Application in Uploaded in compressed format for your reference . 

Thank you, Happy learning, bye bye.




