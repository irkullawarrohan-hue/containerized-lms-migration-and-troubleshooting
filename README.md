# containerized-lms-migration-and-troubleshooting

## Overview of Project


## Scenario:

EduTech Solutions was modernizing their outdated LMS by migrating from an
on-premises environment to a containerized AWS application. The initial
deployment encountered critical issues that prevented proper functionality.
The objective of this project was to identify and resolve these containerization
issues before semester launch.


## Solution:

The containerized deployment environment was recreated with the same
issues encountered by EduTech's team. Troubleshooting was performed using
CloudWatch, ECS logs, and the AWS Console. This project provided experience
in diagnosing and resolving real-world container issues similar to those
encountered by cloud support engineers in production environments.


## Steps performed:
- AWS environment setup for containerized applications
- Container image preparation for the LMS frontend
- Deployment of the LMS frontend on ECS Fargate
- Comprehensive troubleshooting of container issues in ECS
- Resolution of ALB configuration issues
- Correction of security group misconfigurations
- Cleanup of resources


## Services Used:
• Amazon ECS with Fargate: Serverless compute engine for containers
• Application Load Balancer (ALB): Routes HTTP/HTTPS traffic to containers
• Amazon CloudWatch: Monitoring and observability for logs and metrics
• AWS IAM: Identity and access management for AWS resources
• Amazon ECR: Container registry for managing and deploying images
• AWS Security Groups: Virtual firewalls controlling network traffic


## The following architectural diagram represents the project:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/480c160d-22fa-4776-b31b-af845278c4b3" />


## Final Result:

<img width="1904" height="970" alt="ScreenRecording2026-06-05161303211-ezgif com-optimize" src="https://github.com/user-attachments/assets/86606c84-a795-44b1-afd2-c6e75ee1c715" />
