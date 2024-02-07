# Project: Build Serverless Web Application

##Summary

Following a [tutorial provided by AWS](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/) and a supplementary [video tutorial](https://youtu.be/zuKu0VFiwas?) by @tinytechnicaltutorials, I used 6 different AWS services to build a web application including Lambda, API Gateway, Amplify, DynamoDB, and Cognito. 

### Set up the repository in CodeCommit:

<img width="825" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/4372d727-9e3e-4cf9-a2f6-fa43591d7d07">

### Clone and populate the repository using Cloudshell:

<img width="1028" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/010522f7-189a-4d9e-acd5-533bbf345208">

### Deployed site using Amplify:

<img width="527" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/d8d644c3-1364-4999-9859-535efa6a211c">

### User Pool Created in Cognito:

<img width="1045" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/fbf23e94-152d-44cc-ae4f-e42f237264b9">

### Login successful!

<img width="1274" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/691fe912-bd34-4c79-9e28-15d5862272b3">

### Table created in DynamoDB:

<img width="674" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/c9902a32-2986-4202-aecf-a52b74302b84">

### Role Created in IAM for DynamoDB/Lambda:

<img width="844" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/d83c96dd-a588-489a-9b65-8df291f2ef2c">

### Lambda function created:

<img width="647" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/30d8b9aa-11b6-43a4-b133-5a3e71717081">

### DynamoDB showing test item:

<img width="419" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/bcb3b471-e45d-4a85-858c-285e9af2dfad">

### API Gateway test authoriser:

<img width="985" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/4321d18f-1148-468b-a900-97921c7dbb3e">

### After set up in API Gateway, the map works:

<img width="535" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/3c3f25e6-ee9c-4ef8-89b4-64f40fca0741">

### Request Unicorn works:

<img width="535" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/6bf2f929-e526-4979-a2a3-a2e8df99aaf5">

### Second item recorded in DynamoDB:

<img width="1191" alt="image" src="https://github.com/AlainaJensen/AWS-Projects/assets/157747964/d861e452-f99f-4f90-82f6-0aea03900076">

## What I Learned

This project was really useful in helping me to "connect the dots" between different AWS services and how to build something functional with them. 

## Difficulties

I ran into authentication errors while trying to use AWS CLI on my local machine for the early steps as suggested in the written tutorial. This was when I began following the video where CloudShell was suggested instead, so I switched to that.

## Next Steps

I would like to try again with CLI and troubleshoot the errors in order to learn more about the process. I would also want to try a different version with another kind of web application, and possibly integrate some non AWS tools like Terraform.