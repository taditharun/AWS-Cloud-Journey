<<<<<<< HEAD
AWS-Cloud-Journey
Documenting my AWS cloud learning journey with hands-on labs, notes, CloudFormation templates, and projects.


Day 1 - Amazon EC2
Topics Learned
What is Cloud Computing
What is AWS
EC2 Basics
AMI (Amazon Machine Image)
Instance Types
Launching EC2 Instances
Start, Stop, Reboot and Terminate Instances
Hands-On
Launched Linux EC2 Instance
Connected to Instance
Practiced Instance Management

Day 2 - Amazon S3
Topics Learned
What is Amazon S3
Buckets and Objects
Storage Concepts
Bucket Permissions
Hands-On
Created S3 Bucket
Uploaded Files
Downloaded Files
Deleted Objects

Day 3 - Amazon VPC
Topics Learned
What is VPC
CIDR Blocks
Public and Private Subnets
Route Tables
Internet Gateway
Security Groups
Hands-On
Created VPC
Created Subnets
Configured Route Tables
Configured Security Groups

Day 4 - Load Balancer
Topics Learned
Application Load Balancer (ALB)
Network Load Balancer (NLB)
Target Groups
Register Targets
Health Checks
Listener Ports
HTTP (80)
HTTPS (443)
Target Group Stickiness
SSL/TLS Basics
AWS Certificate Manager (ACM)
Hands-On
Created Target Group
Registered EC2 Instances
Created Application Load Balancer
Configured Listener Rules
Tested Health Checks
Deleted Resources After Practice
Current Goal
Learn AWS Cloud Practitioner Concepts
Learn AWS Networking
Learn AWS Security
Become a Cloud Engineer
Become an AWS Security Engineer
Upcoming Topics
IAM
Route 53
Auto Scaling
CloudWatch
RDS
Lambda
CloudFormation


# Day 5 - IAM, S3 and Auto Scaling

## IAM

### IAM Users

* Created IAM users for AWS practice.
* Learned that IAM users are separate from the root account.
* Understood that permissions are controlled using policies.

### IAM Groups

* Created IAM groups.
* Learned that multiple users can be added to a group.
* Permissions can be assigned to groups instead of individual users.

### IAM Policies

* Created a custom S3 Full Access policy.
* Learned the structure of a policy:

  * Effect
  * Action
  * Resource

## Amazon S3

### Hands-On

* Created an S3 bucket.
* Uploaded files.
* Downloaded files.
* Deleted objects.
* Deleted the bucket.

### Key Learning

* S3 is object storage.
* Creating a bucket is free.
* Charges apply only when storing data and using resources.

## Auto Scaling

### Concepts Learned

* Launch Template
* Security Groups
* Auto Scaling Group
* Scale Out
* Scale In

### Key Learning

* Auto Scaling automatically adds or removes EC2 instances based on demand.
* Helps improve availability and optimize costs.

## Summary

Today I practiced IAM, S3, and Auto Scaling concepts and gained a better understanding of AWS identity management, storage services, and automatic scaling.

