# DEPI-music-application-on-aws-cloud-infrastructure-
Host scalable,secure and high availability music application on aws infrastructure 
1. Overview of the Architecture
This project is based on a highly available architecture deployed on AWS. It consists of the following key components:
- VPC with two Availability Zones (AZ A and AZ B)
- Public and Private Subnets in both zones
- NAT Gateway and Internet Gateway for public access
- Bastion Hosts for SSH access
- EC2 instances within an Auto Scaling group for hosting the Music App
- Application Load Balancer (ALB) for traffic distribution
- DynamoDB for storing user and song data
- S3 for storing music files
- Replication of S3 data across zones
- Integration with AWS Lambda, SNS, and CloudWatch.
