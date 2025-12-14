\# AWS Highly Available Student Management Web Application



\## Overview

This project demonstrates how to design, deploy, and scale a student

management web application on AWS using best practices.



The project is implemented in multiple phases:

\- Phase 2: Single EC2 Proof of Concept (POC)

\- Phase 3: Database separation using Amazon RDS and Secrets Manager

\- Phase 4: High Availability and Scalability using ALB and Auto Scaling



\## AWS Services Used

\- Amazon EC2

\- Amazon VPC

\- Application Load Balancer (ALB)

\- Auto Scaling Group (ASG)

\- Amazon RDS (MySQL)

\- AWS Secrets Manager

\- AWS Cloud9



\## Architecture

The application is deployed inside a custom VPC with:

\- Public subnets for ALB and EC2

\- Private subnets for RDS

\- Secure communication using Security Groups



\## Architecture Diagram

!\[Architecture Diagram]



\## Documentation

Detailed step-by-step implementation is available in the `docs/` folder.



\## Access

Application is accessed using the ALB DNS name:xyzload-128953234.us-east-1.elb.amazonaws.com



