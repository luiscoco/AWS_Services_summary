# AWS Services review

For guided tutorials visit AWS WorkShops: https://workshops.aws/

See the detailed AWS services docs in the following link: https://docs.aws.amazon.com/index.html

See also AWS WorkShop Studio: https://catalog.workshops.aws/

## 1. Compute services

### 1.1. AWS App Runner

https://aws.amazon.com/apprunner/

https://docs.aws.amazon.com/en_us/apprunner/

https://www.luminis.eu/blog/cloud-en/a-first-impression-of-aws-app-runner/

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/ebd6719b-aa71-426a-b656-d272b17c6552)

AWS App Runner builds and deploys web applications automatically, load balances traffic with encryption, scales to meet your traffic needs, and allows for the configuration of how services are accessed and communicate with other AWS applications in a private Amazon VPC.

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/3d97573c-ca35-48dc-840b-dcca30f0fb0e)

For getting started with AWS App Runner navigate to this URL and follow the wizard steps:

https://eu-west-3.console.aws.amazon.com/apprunner/home?region=eu-west-3#/create

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/cb4efc5b-e619-45c9-8617-944afd23d0bd)

**AWS App Runner: Deep Dive - AWS Online Tech Talks**: https://www.youtube.com/watch?v=x_1X_4j16A4

**AWS App Runner Explained | Overview and Console Walkthrough**: https://www.youtube.com/watch?v=TKirecwhJ2c

**AWS App Runner WorkShop**: https://www.apprunnerworkshop.com/

**Sample 1 AWS App Runnerhttps (youtube video)**://www.youtube.com/watch?v=ycdo9UyNs98

**Sample 2 AWS App Runner (youtube playlist)**: https://www.youtube.com/playlist?list=PLehXSATXjcQHjXDhdlypt0IB5BVD2xnoc

**AWS re:Invent 2023 - Modernize your web applications and API services using AWS App Runner**: 

https://www.youtube.com/watch?v=4-zqJA3Akx8

### 1.2. AWS Batch

https://aws.amazon.com/batch/

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/ddcf7cd3-2625-4ce7-a714-c044a096b0e9)

**Fully managed batch processing**

AWS Batch is a managed batch processing service that enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS

AWS Batch removes the undifferentiated heavy lifting of configuring and managing the required infrastructure

It dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized compute resources) based on the volume and specific resource requirements of the batch jobs submitted

With AWS Batch, there is no need to install and manage batch computing software or server clusters. This allows you to focus on analyzing results and solving problems

AWS Batch plans, schedules, and executes batch computing workloads using Amazon ECS, Amazon EKS, and AWS Fargate with an option to utilize spot instances

For getting started with AWS Batch navigate to this URL and follow the wizard steps:

https://eu-west-3.console.aws.amazon.com/batch/home?region=eu-west-3#wizard

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/bc98f2a0-35da-44ac-a41d-fa6fdada4f38)

Also you can getting start with AWS Batch following these links:

**AWS Batch WorkShop**: https://catalog.workshops.aws/aws-batch-deep-dive/en-US

**Getting Started with AWS Batch on Amazon EC2**: https://docs.aws.amazon.com/batch/latest/userguide/getting-started-ec2.html

**Getting Started with AWS Batch on Fargate**: https://docs.aws.amazon.com/batch/latest/userguide/getting-started-fargate.html

**Getting started with AWS Batch on Amazon EKS**: https://docs.aws.amazon.com/batch/latest/userguide/getting-started-eks.html

### 1.3. EC2

https://aws.amazon.com/ec2/?nc2=h_ql_prod_cp_ec2

https://docs.aws.amazon.com/ec2/?icmpid=docs_homepage_featuredsvcs

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/a2070879-0227-46c3-bc1d-a94c977b5ac9)

Amazon Elastic Compute Cloud (Amazon EC2) offers the broadest and deepest compute platform, with over 750 instances and choice of the latest processor, storage, networking, operating system, and purchase model to help you best match the needs of your workload

We are the first major cloud provider that supports Intel, AMD, and Arm processors, the only cloud with on-demand EC2 Mac instances, and the only cloud with 400 Gbps Ethernet networking

We offer the best price performance for machine learning training, as well as the lowest cost per inference instances in the cloud

More SAP, high performance computing (HPC), ML, and Windows workloads run on AWS than any other cloud

For getting started with AWS EC2 create a new instance pressing the buttons highlighted in the following image

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/27d2ab95-a3e5-4cf4-901e-c32dfdf9d868)

Also you can getting start with AWS EC2 following these links:

**AWS EC2 WorkShop**: https://ec2spotworkshops.com/launching_ec2_spot_instances.html

### 1.4. EC2 Image Builder

https://aws.amazon.com/image-builder/

https://docs.aws.amazon.com/imagebuilder/latest/userguide/what-is-image-builder.html

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/2ad422ab-e7cc-49c5-b3df-1a1165efad46)

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/c5495eb3-d711-482b-94a0-6102b34d4946)

Image Builder provides a one-stop-shop to automate image management processes. Customers can generate an automated pipeline with an intuitive wizard in the AWS console to produce compliant Linux and Windows Server images for use on AWS and on-premises. When software updates become available, Image Builder automatically produces a new image and distributes it to stipulated AWS regions after running tests on it.

**AWS EC2 Image Builder | Automate Image Creation in AWS**: https://www.youtube.com/watch?v=5KsXwj2Jke4

**AWS EC2 Image Builder WorkShop**: https://catalog.us-east-1.prod.workshops.aws/workshops/d6c7ecdc-c75f-4ad1-910f-fdd994cc4aed/en-US/100-ec2-ib

**EC2 Image Builder (youtube video)**: https://www.youtube.com/watch?v=S1eUw8ztAm8

**AWS EC2 Image Builderhttps (youtube video)**://www.youtube.com/watch?v=KBF72Nq6N1k&t=22s

### 1.5. Elastic Beanstalk

https://aws.amazon.com/elasticbeanstalk

https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/30a8379e-6087-4cc3-a04e-b54355ed1ff4)

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/fc931bf1-cc10-451d-839c-4950de576bc2)

Elastic Beanstalk is a service for deploying and scaling web applications and services

Upload your code and Elastic Beanstalk automatically handles the deployment—from capacity provisioning, load balancing, and auto scaling to application health monitoring

For getting started create a new Elastic Beanstalk application

https://eu-west-3.console.aws.amazon.com/elasticbeanstalk/home?region=eu-west-3#/create-environment

![image](https://github.com/luiscoco/AWS_Services_summary/assets/32194879/a1d3d9bd-d188-4160-ab4d-faa1f288f34f)

See these video tutorials:

**Deploy a Web Application Using Elastic Beanstalk (New Version of UI) | AWS Tutorial for Beginners**: https://www.youtube.com/watch?v=2BoVhej0QVI



### 1.6. Lambda
Run code without thinking about servers

### 1.7. Lightsail
Launch and Manage Virtual Private Servers

### 1.8. AWS Outposts
Run AWS Services On Premises

### 1.9. Serverless Application Repository
Assemble, deploy, and share serverless applications within teams or publicly

### 1.10. AWS SimSpace Weaver
Build and run large-scale spatial simulations

## 2. Container services

### 2.1. Elastic Container Registry (ECR)
Fully-managed Docker container registry : Share and deploy container software, publicly or privately

### 2.2. Elastic Container Service (ECS)
Highly secure, reliable, and scalable way to run containers

### 2.3. Elastic Kubernetes Service (EKR)
The most trusted way to start, run, and scale Kubernetes

### 2.4. Red Hat OpenShift Service on AWS 
Fully managed Red Hat OpenShift service on AWS

## 3. Database services

### 3.1. Amazon DocumentDB
Fully-managed MongoDB-compatible database service

### 3.2. DynamoDB
Managed NoSQL Database

### 3.3. ElastiCache
In-Memory Cache

### 3.4. Amazon Keyspaces
Serverless Cassandra-compatible database

### 3.5. Amazon MemoryDB for Redis
Fully managed, Redis-compatible, in-memory database service

### 3.6. Neptune
Fast, reliable graph database built for the cloud

### 3.7. Amazon QLDB
Fully managed ledger database

### 3.8. RDS
Managed Relational Database Service

### 3.9. Amazon Timestream
Amazon Timestream is a fast, scalable, and serverless time series database for IoT and operational applications.

## 4. Developer tools

### 4.1. AWS AppConfig
Use feature flags, operational flags, and other runtime configuration to make changes quickly and safely on production

### 4.2. Application Composer
Visually design and build modern applications quickly

### 4.3. Cloud9
A Cloud IDE for Writing, Running, and Debugging Code

### 4.4. CloudShell
A browser-based shell with AWS CLI access from the AWS Management Console

### 4.5. CodeArtifact
Secure, scalable, and cost-effective artifact management for software development

### 4.6. CodeBuild
Build and Test Code

### 4.7. Amazon CodeCatalyst
Integrated DevOps Service

### 4.8. CodeCommit
Store Code in Private Git Repositories

### 4.9. CodeDeploy
Automate Code Deployments

### 4.10. CodePipeline
Release Software using Continuous Delivery

### 4.11. CodeStar
Quickly develop, build, and deploy applications

### 4.12. Amazon CodeWhisperer
Build applications faster with the ML-powered coding companion.

### 4.13. AWS FIS
Improve resiliency and performance with controlled experiments.

### 4.14. X-Ray
Analyze and Debug Your Applications

## 5. Storage services

### 5.1. AWS Backup
AWS Backup centrally manages and automates backups across AWS services

### 5.2. EFS
Managed File Storage for EC2

### 5.3. AWS Elastic Disaster Recovery
Scalable, cost-effective application recovery to AWS

### 5.4. FSx
Fully managed third-party file systems optimized for a variety of workloads

### 5.5. S3
Scalable Storage in the Cloud

### 5.6. S3 Glacier
Archive Storage in the Cloud

### 5.7. Storage Gateway
Hybrid Storage Integration

## 6. Networking and content delivery services

### 6.1. API Gateway
Build, Deploy and Manage APIs

### 6.2. AWS App Mesh
Easily monitor and control microservices

### 6.3. AWS Cloud Map
Build a dynamic map of your cloud

### 6.4. CloudFront
Global Content Delivery Network

### 6.5. Direct Connect
Dedicated Network Connection to AWS

### 6.6. Global Accelerator
Improve your application’s availability and performance using the AWS Global Network

### 6.7. AWS Private 5G
Deploy and scale private mobile networks on-premises

### 6.8. Route 53
Scalable DNS and Domain Name Registration

### 6.9. Route 53 Application Recovery Controller
Monitor application recovery readiness and manage failovers

### 6.10. VPC
Isolated Cloud Resources

## 7. Security, Identity and Compliance services

### 7.1. AWS Artifact
Security compliance reports and agreements

### 7.2. AWS Audit Manager
Continuously assess controls for risk and compliance

### 7.3. Certificate Manager
Provision, Manage, and Deploy SSL/TLS Certificates

### 7.4. CloudHSM
Managed Hardware Security Modules in the Cloud

### 7.5. Cognito
Consumer Identity Management and AWS Credentials for Federated Identities

### 7.6. Detective
Investigate and Analyze potential security issues

### 7.7. Directory Service
Host and Manage Active Directory

### 7.8. AWS Firewall Manager
Central management of firewall rules

### 7.9. GuardDuty
Intelligent Threat Detection to Protect Your AWS Accounts and Workloads

### 7.10. IAM
Manage access to AWS resources

### 7.11. IAM Identity Center
Manage workforce user access to multiple AWS accounts and cloud applications

### 7.12. Amazon Inspector
Continual vulnerability management at scale

### 7.13. Key Management Service
Securely Generate and Manage AWS Encryption Keys

### 7.14. Amazon Macie
Amazon Macie classifies and secures your business-critical content.

### 7.15. AWS Payment Cryptography
On-demand payment HSM functionality for card transactions and key management

### 7.16. AWS Private Certificate Authority
Managed private certificate authority service

### 7.17. Resource Access Manager
Share AWS resources with other accounts or AWS Organizations

### 7.18. Secrets Manager
Easily rotate, manage, and retrieve secrets throughout their lifecycle

### 7.19. Security Hub
AWS Security Hub is AWS’s security and compliance center

### 7.20. Security Lake
Automatically centralize all your security data with a few clicks

### 7.21. AWS Signer
Ensuring trust and integrity of your code

### 7.22. Amazon Verified Permissions
Manage, analyze and enforce permissions across your applications

### 7.23. WAF & Shield
Protects Against DDoS Attacks and Malicious Web Traffic

