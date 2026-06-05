# AWS-IAM
# Lab 1 - Introduction to AWS Identity and Access Management (IAM)
## NAME : Chiiradeep R
## REGISTER NO: 212224240028

# AIM:
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.

# Prerequisites
Basic understanding of cloud computing concepts
AWS Academy Lab access
Web browser with internet connectivity
# Tools Used
AWS Management Console
AWS Identity and Access Management (IAM)
Amazon EC2
Amazon S3
# Tasks Performed
## Task 1: Explore IAM Users and Groups
Reviewed pre-created IAM users: user-1, user-2, user-3
Explored IAM groups: EC2-Admin, EC2-Support, S3-Support
Inspected managed and inline policies attached to groups
## Screenshot:
<img width="1350" height="592" alt="549927159-9f1bf871-59cb-4de1-ac4a-73d58d850e19" src="https://github.com/user-attachments/assets/1281ac10-fc57-44ad-b48a-c17c536e7768" />

## Task 2: Add Users to Groups
Added user-1 to the S3-Support group
Added user-2 to the EC2-Support group
Added user-3 to the EC2-Admin group
## Screenshot:
<img width="1338" height="596" alt="549927284-1ad45e18-13cf-46ef-8d8a-f205036ab135" src="https://github.com/user-attachments/assets/39e55465-351b-4c98-a532-12ab753e8502" />

<img width="1336" height="592" alt="549927394-1cb60b5a-f6dc-4a4d-8b84-dea029abd825" src="https://github.com/user-attachments/assets/c5efae61-a70f-4c08-a78f-8b5a3f08ac4b" />

<img width="1334" height="596" alt="549927466-7dfdc707-e4ff-48a3-b638-3b551c4f8547" src="https://github.com/user-attachments/assets/6b09444c-3bdb-4034-a95c-cd05ba691bb0" />


## Task 3: Test IAM User Permissions
Logged in using IAM sign-in URL
Verified S3 access for user-1
Verified EC2 read-only access for user-2
Verified EC2 administrative access for user-3
## Screenshot:
<img width="1344" height="590" alt="549927538-afc80bff-58fa-43c1-afeb-5c161d9bb8be" src="https://github.com/user-attachments/assets/354ee92c-2c1f-4c61-b6ff-99e59a031208" />

<img width="1341" height="599" alt="549927618-74c1cbe1-1176-4045-ad1e-b01e0542ead4" src="https://github.com/user-attachments/assets/8ea82258-fc95-4f28-bbee-a30db7022854" />

# Workflow
Accessed IAM console and reviewed users and groups.

Inspected policy permissions attached to groups.

Assigned users to groups based on their roles.

Logged in as each IAM user using the sign-in URL.

Validated permissions by accessing AWS services.
# Learning Outcomes
Understood the role of IAM in AWS security.

Learned how IAM users, groups, and policies interact.

Gained practical experience implementing role-based access control.

Verified permission enforcement through real-time service testing.
# Result
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.
