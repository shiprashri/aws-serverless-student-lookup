# Student Info Serverless Web App

This is a simple serverless web application built using AWS services.

## Tech Stack
- **Frontend**: HTML/CSS/JavaScript (hosted on S3)
- **Backend**: AWS Lambda + API Gateway
- **Database**: DynamoDB

## Features
- Fetch student data by roll number
- Real-time interaction using API
- Styled UI with error/loading/success states

## How It Works
1. User enters roll number
2. API Gateway triggers a Lambda function
3. Lambda fetches data from DynamoDB
4. Data is returned and displayed on the page

## Example
> Input: `101`  
> Output:  
> ✅ Name: Alice  
> 📧 Email: alice@example.com

## Deployment
- Static frontend deployed on AWS S3
- Backend deployed via AWS Lambda using API Gateway

---
[Live Demo](https://s3.ap-south-1.amazonaws.com/my.server.less.app-1/index.html)

![Screenshot](Screenshot (160).png)

