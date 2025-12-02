---
title: "Week 9 Worklog"
date: "2025-11-03"
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Week 9 Objectives:

* Learn how to use tags to manage AWS resources  
* Practice creating Resource Groups and filtering resources by tags  
* Manage access to EC2 using resource tags and IAM policies  
* Understand IAM permission boundaries and how to limit user permissions  

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ---- | ---------- | --------------- | ------------------ |
| 1   | - **Lab 27:** Manage Resources Using Tags and Resource Groups <br>&emsp;2. Using Tags <br>&emsp;2.1 Use tags on Console <br>&emsp;&emsp;- 2.1.1 Create EC2 instance with tag <br>&emsp;&emsp;- 2.1.2 Manage tags on AWS resources <br>&emsp;&emsp;- 2.1.3 Filter resources by tag <br>&emsp;2.2 Use tags with CLI <br>&emsp;3. Create a Resource Group <br>&emsp;4. Clean up resources | 03/11/2025 | 03/11/2025 | <https://000027.awsstudygroup.com/> |
| 2   | - **Lab 28:** Manage access to EC2 services with resource tags through IAM services <br>&emsp;1. Introduction <br>&emsp;2. Preparation <br>&emsp;&emsp;- 2.1 Create IAM user <br>&emsp;3. Create IAM Policy <br>&emsp;4. Create IAM Role <br>&emsp;5. Check Policy: <br>&emsp;&emsp;- 5.1 Switch Roles <br>&emsp;&emsp;- 5.2 Check IAM Policy <br>&emsp;&emsp;- 5.2.1 Access EC2 console in Tokyo Region <br>&emsp;&emsp;- 5.2.2 Access EC2 console in North Virginia Region <br>&emsp;&emsp;- 5.2.3 Create EC2 instance with/without required tags <br>&emsp;&emsp;- 5.2.4 Edit resource tag on EC2 instance <br>&emsp;&emsp;- 5.2.5 Policy check results <br>&emsp;6. Clean up resources | 04/11/2025 | 04/11/2025 | <https://000028.awsstudygroup.com/> |
| 3   | - **Practice:** Review Lab 27 & Lab 28 <br>&emsp;+ Repeat using tags on Console and CLI <br>&emsp;+ Practice filtering resources and using Resource Groups <br>&emsp;+ Practice tag-based access control for EC2 with IAM policies <br>&emsp;+ Note simple best practices for tags and access control | 05/11/2025 | 05/11/2025 | <https://000027.awsstudygroup.com/>, <https://000028.awsstudygroup.com/> |
| 4   | - **Lab 30:** Limitation of user rights with IAM Permission Boundary <br>&emsp;1. Introduction <br>&emsp;2. Preparation <br>&emsp;3. Create restriction policy (permission boundary) <br>&emsp;4. Create IAM limited user <br>&emsp;5. Test IAM user limits <br>&emsp;6. Clean up resources | 06/11/2025 | 06/11/2025 | <https://000030.awsstudygroup.com/> |
| 5   | - **Practice:** Review Tag, IAM Policy, and Permission Boundary <br>&emsp;+ Review how tags and Resource Groups help manage resources <br>&emsp;+ Review tag-based access control to EC2 from Lab 28 <br>&emsp;+ Review IAM permission boundary from Lab 30 <br>&emsp;+ Summarize what was learned in Week 9 | 07/11/2025 | 07/11/2025 | <https://000027.awsstudygroup.com/>, <https://000028.awsstudygroup.com/>, <https://000030.awsstudygroup.com/> |

### 🏆 **Week 9 Achievements**

* **Tags and Resource Management**
  * Used tags on the AWS Console to mark EC2 and other resources
  * Filtered resources by tags to find them more easily
  * Used CLI to work with tags and created Resource Groups

* **Tag-based Access Control for EC2**
  * Created IAM user, IAM policy, and IAM role for tag-based access
  * Tested EC2 console access in different Regions (Tokyo, North Virginia)
  * Tried creating EC2 instances with and without the required tags
  * Edited resource tags and saw how policies allowed or denied actions

* **IAM Permission Boundaries**
  * Created a restriction policy as a permission boundary
  * Created an IAM user with limited rights
  * Tested what the user can and cannot do in the AWS console

* **Practice and Cleanup**
  * Practiced using tags, Resource Groups, and IAM policies multiple times
  * Cleaned up all lab resources after finishing
  * Gained a clearer understanding of how tags and IAM work together to control access
