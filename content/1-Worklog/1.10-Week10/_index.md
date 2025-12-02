---
title: "Week 10 Worklog"
date: "2025-11-10"
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Practice encryption at rest using AWS KMS with S3 and CloudTrail/Athena  
* Review IAM roles, conditions, and access control patterns  
* Practice IAM roles for applications (EC2 -> S3)  
* Learn core AWS database services: Amazon RDS, Aurora, Redshift, ElastiCache  

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| 1   | - **Lab 33:** Encrypt at rest with AWS KMS <br>&emsp;1. Introduction <br>&emsp;2. Preparation steps: <br>&emsp;&emsp;- 2.1 Create policy and role <br>&emsp;&emsp;- 2.2 Create group and user <br>&emsp;3. Create AWS Key Management Service (KMS) key <br>&emsp;4. Create Amazon S3: <br>&emsp;&emsp;- 4.1 Create bucket <br>&emsp;&emsp;- 4.2 Upload data to S3 <br>&emsp;5. Create AWS CloudTrail and Amazon Athena: <br>&emsp;&emsp;- 5.1 Create CloudTrail <br>&emsp;&emsp;- 5.2 Logging to CloudTrail <br>&emsp;&emsp;- 5.3 Create Amazon Athena <br>&emsp;&emsp;- 5.4 Retrieve data with Athena <br>&emsp;6. Test and share encrypted data on S3 <br>&emsp;7. Resource cleanup | 10/11/2025 | 10/11/2025 | <https://000033.awsstudygroup.com/> |
| 2   | - **Lab 44:** IAM Role & Condition <br>&emsp;1. Introduction about IAM <br>&emsp;&emsp;- 1.1 Request to AWS service <br>&emsp;&emsp;- 1.2 Authenticate requests <br>&emsp;&emsp;- 1.3 Assume Role process <br>&emsp;2. Create IAM Group <br>&emsp;3. Create IAM User: <br>&emsp;&emsp;- 3.1 Create IAM users <br>&emsp;&emsp;- 3.2 Check permissions <br>&emsp;4. Configure Role Condition: <br>&emsp;&emsp;- 4.1 Create Admin IAM Role <br>&emsp;&emsp;- 4.2 Configure switch role <br>&emsp;&emsp;- 4.3 Restrict role access: <br>&emsp;&emsp;&emsp;• 4.3.1 Limit switch role by IP <br>&emsp;&emsp;&emsp;• 4.3.2 Limit switch role by time <br>&emsp;5. Clean up resources | 11/11/2025 | 11/11/2025 | <https://000044.awsstudygroup.com/> |
| 3   | - **Practice:** Review Lab 33 & Lab 44 <br>&emsp;+ Practice creating and using KMS keys to encrypt S3 data <br>&emsp;+ Review CloudTrail and Athena queries for KMS/S3 activity <br>&emsp;+ Practice IAM roles with conditions (IP, time) and switching roles <br>&emsp;+ Write short notes about KMS, IAM Role, and conditions | 12/11/2025 | 12/11/2025 | <https://000033.awsstudygroup.com/>, <https://000044.awsstudygroup.com/> |
| 4   | - **Lab 48:** Granting authorization for an application to access AWS services with an IAM role <br>&emsp;1. Preparation: <br>&emsp;&emsp;- 1.1 Create EC2 instance <br>&emsp;&emsp;- 1.2 Create S3 bucket <br>&emsp;2. Use access key: <br>&emsp;&emsp;- 2.1 Generate IAM user and access key <br>&emsp;&emsp;- 2.2 Use access key to access S3 from application <br>&emsp;3. IAM role on EC2: <br>&emsp;&emsp;- 3.1 Create IAM role <br>&emsp;&emsp;- 3.2 Use IAM role from EC2 instead of access key <br>&emsp;4. Clean up resources | 13/11/2025 | 13/11/2025 | <https://000048.awsstudygroup.com/> |
| 5   | - **Module 06:** AWS Database Services <br>&emsp;+ Module 06-01: Database Concepts Review <br>&emsp;+ Module 06-02: Amazon RDS & Amazon Aurora <br>&emsp;+ Module 06-03: Amazon Redshift & ElastiCache <br>&emsp;+ Note key differences between relational, data warehouse, and in-memory cache services | 14/11/2025 | 14/11/2025 |  |

### 🏆 **Week 10 Achievements**

* **KMS and Encryption at Rest**
  * Used AWS KMS to create and manage encryption keys
  * Encrypted data in S3 and verified access using CloudTrail and Athena
  * Tested sharing encrypted S3 data and cleaned up lab resources

* **IAM Roles and Conditions**
  * Reviewed IAM basics: requests, authentication, assume role process
  * Created IAM users, groups, and admin roles
  * Applied role conditions to restrict access by IP address and time

* **Application Access with IAM Roles**
  * Created EC2 instance and S3 bucket for the lab
  * Used IAM user access keys to access S3, then replaced them with IAM roles
  * Verified that EC2 could access S3 securely using roles instead of long-term keys

* **Database Service Overview**
  * Reviewed core database concepts on AWS
  * Learned basics of Amazon RDS and Aurora for relational databases
  * Saw how Redshift and ElastiCache support analytics and caching workloads
