# Lab 5 – Build a Database Server (AWS)

## Author

* **Name**: KIRUTHIGA.B
* **Register Number**: 212224040160
* **Date of Submission**:27.02.2025

---

## Objective

The objective of this experiment is to understand how to deploy and configure a database server in AWS. This lab focuses on launching an EC2 instance, installing a database management system (DBMS), configuring basic database settings, creating a sample database, and validating connectivity to the database server.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* An existing VPC and EC2 knowledge (from previous labs)
* Basic knowledge of Linux commands and SQL

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Security Groups
* SSH Client (Terminal / PuTTY)
* MySQL / MariaDB / PostgreSQL (any one)

---

## Tasks Performed

### Task 1: Launch EC2 Instance for Database Server

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type and configure key pair and security group.

---

### Task 2: Configure Security Group for Database Access

Modify the security group to allow:

* SSH (Port 22) for remote access
* Database port (e.g., MySQL – 3306 or PostgreSQL – 5432)

---

### Task 3: Connect to EC2 Instance

Connect to the EC2 instance using SSH from your local machine.

---

### Task 4: Install Database Server

Install a database server software such as MySQL, MariaDB, or PostgreSQL on the EC2 instance using package manager commands.

---

### Task 5: Start and Configure Database Service

Start the database service and configure basic settings such as root password and user privileges.

---

### Task 6: Create a Sample Database

Create a sample database and a table inside it. Insert a few records into the table.

---

### Task 7: Test Database Connectivity

Test the database server by connecting to it locally or remotely and performing basic SQL queries.

---

## Workflow (Student Explanation)


1. Launched an Amazon Linux 2 EC2 instance with appropriate instance type, key pair, and security group.

2. Configured the security group to allow SSH (22) and database port (MySQL 3306/PostgreSQL 5432) access.

3. Connected to the EC2 instance via SSH from my local machine.

4. Installed a database server (MySQL/MariaDB/PostgreSQL) using package manager commands.

5. Started the database service, set root password, and configured user privileges.

6. Created a sample database and table, and inserted test records.

7. Verified database connectivity by executing basic SQL queries locally and remotely.

## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Instance for Database Server

<img width="1917" height="994" alt="Screenshot 2026-02-27 083536" src="https://github.com/user-attachments/assets/3f46a8a2-8a52-43f1-8ee3-5a1b1ad62b83" />


### Screenshot 2: Database Service Running

<img width="1919" height="983" alt="Screenshot 2026-02-27 083911" src="https://github.com/user-attachments/assets/4bfeb564-8a87-4d39-b15f-6a3a61b9d32c" />


### Screenshot 3: Sample Database and Table

<img width="1919" height="1089" alt="Screenshot 2026-02-27 090408" src="https://github.com/user-attachments/assets/9787dbe6-17a2-4dbd-80a3-59b02b64bd4e" />


## Result

This experiment demonstrated how to build a database server in AWS using an EC2 instance. By installing and configuring a DBMS, creating a sample database, and testing connectivity, the fundamentals of hosting and managing a cloud-based database server were underst
