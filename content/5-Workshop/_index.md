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