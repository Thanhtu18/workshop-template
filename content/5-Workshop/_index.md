---
title: "Workshop"
date: "2025-12-09"
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

# Building a Task Management Platform with DevOps on AWS Serverless

#### Overview

**AWS Serverless** enables you to build and deploy applications without managing servers, automatically scales based on demand, and you only pay for what you use.

In this workshop, we will learn how to design, build, and deploy a complete task management platform **TaskHub** using serverless architecture and automated DevSecOps practices.

We will create a system that includes frontend, backend API, database, and a complete CI/CD pipeline. The workshop focuses on three main components to build a production-ready application on AWS:

+ **Serverless Backend** - Use AWS Lambda for business logic processing, API Gateway as the communication layer, DynamoDB for data storage, and Cognito for user authentication management with optimized costs.

+ **Content Delivery** - Deploy Next.js application on S3, distribute globally via CloudFront with low latency, and protect with AWS WAF against common web attacks.

+ **DevOps Pipeline** - Automate the build, test, and deploy process using CodePipeline and CodeBuild, integrate security scanning with CodeGuru, and manage infrastructure as code with CloudFormation.

#### Content

1. [Workshop overview](5.1-Workshop-overview)
2. [Prerequiste](5.2-Prerequiste/)
3. [Access S3 from VPC](5.3-S3-vpc/)
4. [Access S3 from On-premises](5.4-S3-onprem/)
5. [VPC Endpoint Policies (Bonus)](5.5-Policy/)
6. [Clean up](5.6-Cleanup/)

[Setting Up IAM Policy](5.3-Policy/)
[Deploying Serverless Functions with AWS Lambda](5.4-Lambda/)
[Building an API Gateway with Amazon API Gateway](5.5-APIGateway/)
[Using Amazon DynamoDB High-Performance NoSQL Database](5.6-DynamoDB/)
[Simple and Secure Object Storage with Amazon S3](5.7-S3/)
[Accelerating Content Delivery with Amazon CloudFront (CDN)](5.8-CloudFront/)
[Managing User Identity and Access with Amazon Cognito](5.9-Cognito/)
[Managing Encryption Keys with AWS Key Management Service (KMS)](5.10-KeyManagementService/)
[Building CI/CD Pipelines with AWS CodePipeline](5.11-CodePileline/)
[Automate code building and testing with AWS CodeBuild](5.12-CodeBuild/)
[Automate code review and optimization with Amazon CodeGuru](5.13-CodeGuru/)
[Manage Infrastructure as Code (IaC) with AWS CloudFormation](5.14-CloudFormation/)
[Collect, monitor, and analyze logs with Amazon CloudWatch Logs](5.15-CloudWatchLogs/)

[Use Amazon SNS Simple Notification Service](5.16-SNS/)

[Set up Performance Monitoring and Alarming with Amazon CloudWatch](5.17-CloudWatch/)