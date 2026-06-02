# 🚀 VProfile Lift & Shift Migration

## Architecture Overview

### On-Prem Environment

![On-Prem Architecture](images/on-prem-architecture.jpg)

This diagram illustrates the original on-premises multi-tier architecture before migration to AWS.

---

### AWS Architecture

![AWS Architecture](images/aws-architecture.jpg)

The original environment was migrated to AWS using a Lift & Shift approach.

---

## Infrastructure

### EC2 Instances

![EC2 Instances](images/ec2-instances.jpg)

Application and backend services deployed on EC2 instances.

---

### Security Groups

![Security Groups](images/security-groups.jpg)

Tier-based security model controlling communication between components.

---

### Route 53

![Route53](images/route53-dns.jpg)

Public and private hosted zones for DNS resolution.

---

### Target Group Health Check

![Target Group](images/target-group-healthcheck.jpg)

Application Load Balancer target group health monitoring.

---

## Application

### Login Page

![Login](images/application-login.jpg)

Application login interface running on AWS infrastructure.

### Dashboard

![Dashboard](images/application-dashboard.jpg)

Successful application deployment validation after migration.


# Prerequisites
- JDK 17 or 21
- Maven 3.9
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch

# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql


