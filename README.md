![image](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

# AWS-Solution-Architect-Associate
A guided path to pass AWS certified solution architect associate exam

## Day 1: Introduction to Cloud
1. What is Cloud?
2. public cloud Vs private cloud
3. Why Public cloud is popular?
4. Popular public cloud providers ( AWS, Azure, GCP )
5. Why AWS?


## Day 2: Introduction to AWS
1. History of AWS
2. AWS Marketshare among the cloud providers
3. AWS Global Infrastructure
4. Creating a AWS free tier account
5. AWS Regions Vs Availablity zones Vs Data centers
6. AWS Global services Vs Region scoped Services

## Day 3: Identity And Access Management IAM
1. Creating Users from your root account
2. Users Vs Groups Vs Policies Vs Roles
3. Creating your own policies and roles
4. Account Protection Using MFA and Password policies
5. Different ways to access AWS through( Management Console, CLI tool, SDK )
6. IAM Best Practices and guidelines

## Day 4: Elastic Compute Cloud EC2
1. What is EC2 Instance
2. EC2 Instance types and Configuration Options
3. EC2 Instances Naming conventions
4. What are Security Groups
5. EC2 Instances Purchasing Options
6. Public IP vs Private IP vs Elastic IP
7. What are Placement Groups

## Day 5 : EC2 Storage 
1. What are EBS volumes
2. What are EBS Snapshots and features
3. EBS Volume types (gp2/gp3 .. etc )
4. EBS Multi Attach
5. EC2 Instance Store
6. What are AMIs (Amazon Machine Images)
7. What is Amazon EFS
8. EFS Performance and Storage Classes
9. EFS vs EBS vs Instance Store

## Day 6 : High Availablity and AutoScaling
1. Vertical and Horizontal Scaling
2. Elastic Load Balancer
3. Why to use LB?
4. Why to use ELBs?
5. Elastic Load balancer Security Groups
6. Application vs Network vs Gateway vs Classic Load balancer
7. ELB target groups
8. Sticky Sessions
9. Cross Zone Load balancing
10. Connection Draining
11. Auto Scaling Groups
12. CloudWatch Alarms and Scaling

## Day 7 : AWS RDS
1. What is RDS?
2. Why to use RDS inplace of EC2 DB deploment?
3. RDS Storage auto Scaling
4. Read Replicas
5. Multi AZ
6. RDS Custom
7. Amazon Aurora and Db cluster
8. Autoscaling and High Availablity
9. Features of Aurora
10. RDS backups
11. RDS security
12. RDS proxy
13. AWS ElastiCache
14. Redis vs Memcache

## Day 8 : AWS Route 53
1. What is DNS?
2. DNS Terminologies ( Domain registrar, dns records, zonde file,name server, top level and second level domain)
3. URL breakdown
4. How DNS works?
5. Route 53
6. Record and types of records (A,AAAA,CNAME,NS,TTL,ALIAS)
7. Hosted Zones (Private vs Public HZ)
8. Route 53 routing policies (Simple,weighted,latency,geolocation,failover,geoproximity,ip-based,multivalued)

## Day 9 : Elastic Beanstalk
1. How to instantiate Application Quickly?
2. Golden AMIs, EC2 User Data
3. Developers Problems on AWS
4. Creating Application in beanstalk
5. Creating Env in beanstalk
6. Deploying a simple application code on beanstalk
7. Review underline infrastructure build by beanstalk in CloudFormation template stacks

## Day 10 : AWS S3
1. What is S3 service?
2. S3 buckets and objects
3. Usecases of S3
4. S3 Security
5. S3 Bucket policies
6. S3 Versioning
7. S3 Storage Classes
8. S3 Replication
9. S3 Lifecycle Rules
10. S3 Event Notification
11. Amazon EventBridge
12. S3 Performance
13. S3 Encryption (SSE,CSE)
14. S3 delete MFA
15. S3 Access logs

## Day 11 : AWS CloudFront and Global Accelerator
1. WHat is CDN?
2. Globally Edge Locations on AWS
3. What is Cloudfront origin?
4. Unicast and Anycast IP
5. Global accelerator
6. Leverage AWS network over public network
7. Cloudfront vs accelerator

## Day 13 : AWS VPC 
1. What is VPC (Virtual Private Cloud)
2. CIDR (Classless Inter Domain Routing) IPv4
3. Private Vs Public IPs
4. Base IP And Subnet Mask
5. Understand Subnet Mask with Examples
6. VPC Specifications in AWS
7. Private and Public Subnets
8. Internet Gateway
9. Baston Hosts
10. NAT Instances
11. NAT Gateway
12. What is NACL (Network Access Control List)
13. Inbound and Outbound rules in NACL
14. Emphemeral Port

## Day 14 : AWS VPC
16. Security Groups VS NACL
17. VPC Peering
18. VPC Endpoints
19. Types of Endpoints
20. VPC Flow Logs
21. Troubleshooting Issues in NACL and SGs
22. Direct Connect (DX)
23. Transit Gateway
24. VPC Traffic Mirroring
25. Site 2 Site VPN connection
26. IPv6
27. Egress Only Internet Gateway
28. Networking Cost in AWS
29. Minimize Egress Cost
30. Network Protection In AWS
31. AWS Network Firewall

## Day 15 : Containers On AWS
1. Docker
2. Containers Vs Virtual Machines
3. ECS vs EKS vs ECR
4. What is Fargate
5. ECS Launch types (EC2, Fargate)
6. ECS and ALB integration
7. Mount EFS on ECS tasks
8. ECS Tasks vs Service
9. ECS service auto scaling
10. Amazon ECR
11. Amazon EKS overview
12. EKS Data Volumes Support
13. AWS App Runner

## Day 16 : Storage Extras
1. AWS Snowball Family
2. Amazon FSx
3. Storage Gateways
4. AWS Transfer Family
5. AWS DataSync
6. AWS Storage services comparison

## Day 17 : AWS SQS
1. Why need to decouple applications?
2. Standard Queue
3. Multiple EC2 Consumers
4. SQS with ASG
5. SQS Security
6. SQS - Message Visiblity Timeout
7. Long Polling
8. FIFO Queues

## Day 18 : AWS SNS
1. Pub/Sub Model
2. Topic publish Vs Direct publish
3. SNS security
4. SNS + SQS Fan out Architecture
5. FIFO topics
6. Message Filtering

## Day 19 : Kinesis
1. Why need message streaming platform
2. Kinesis Data Streams (KDS)
3. Kinesis Data Firehose (KDF)
4. Kinesis Data Analytics (KDA)
5. Kinesis Video streaming (KVS)
6. KDS Capacity modes
7. KDS Security
8. SQS vs SNS vs KDS
9. Amazon MQ (managed service as rabbitMQ)

## Day 20 : Databases in AWS
1. RDS
2. Aurora
3. ElastiCache
4. DynamoDB
5. DocumentDB (Managed mongoDB)
6. Neptune
7. Keyspaces (Apache Cassendra)
8. QLDB (Quauntum Ledger DB)
9. Timestream

## Day 21 : AWS Serverless
1. Aws serverless services
2. AWS lambda
3. Lambda integration
4. Serverless cron jobs
5. lambda Pricing
6. lambda limitation
7. lambda snapstart
8. Lambda in VPC
9. Integration with RDS / Aurora

## Day 22 : AWS Serverless
10. DynamoDB
11. DynamoDB capacity Modes
12. DynamoDB accelator
13. Streamprocessing
14. Global tables
15. Backups and disaster recovery
16. DynamoDB integration with S3
17. AWS API Gateway
18. API Gateway security
19. Step Functions
20. Amazon Cognito

## Day 23 : Machine Learning
1. Amazon Rekognition
2. Amazon Transcribe
3. Amazon Polly
4. Amazon Translate
5. Amazon Lex
6. Amazon Connect
7. Amazon Comprehend
8. Amazon SageMaker
9. Amazon Forecast
10. Amazon Kendra
11. Amazon Personalize
12. Amazon Textract

## Day 24 : Data Analytics on AWS
1. Amazon Athena
2. Amazon Redshift
3. Redshift cluster + Snapshots + disaster recovery
4. Redshist spectrum
5. Amazon OpenSearch
6. Amazon EMR
7. Amazon Quicksight
8. Amazon Glue
9. AWS Data lake Formation
10. Kinesis Data Analytics
11. Amazon MSK
12. Big Data Ingestion pipeline on AWS
