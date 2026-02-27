# Lab 3 – Introduction to Amazon Elastic Compute Cloud (EC2)

## Author

* **Name**: KIRUTHIGA.B
* **Register Number**: 212224040160
* **Date of Submission**: 27.02.2026

---

## Objective

The objective of this experiment is to understand the fundamentals of Amazon Elastic Compute Cloud (EC2). This lab focuses on launching and managing a virtual server, understanding instance types and AMIs, connecting to an EC2 instance, monitoring its status, and performing basic instance operations such as start, stop, and terminate.

---

## Prerequisites

* Basic understanding of cloud computing concepts
* AWS account or AWS Academy Lab access
* Web browser with internet connectivity
* Basic knowledge of Linux commands (optional)

---

## Tools Used

* AWS Management Console
* Amazon EC2
* Key Pair
* Security Group
* SSH Client (PuTTY / Terminal)

---

## Tasks Performed

### Task 1: Explore Amazon EC2 Dashboard

Explore the EC2 service dashboard in the AWS Management Console. Observe the different sections such as Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs.

---

### Task 2: Launch an EC2 Instance

Launch a new EC2 instance using Amazon Linux 2 AMI. Select an appropriate instance type (t2.micro) under the free tier. Configure basic settings such as instance name, key pair, and security group.

---

### Task 3: Configure Security Group

Configure a security group to allow inbound access:

* SSH (Port 22) from your IP address
* HTTP (Port 80) from anywhere (0.0.0.0/0)

This security group acts as a firewall for the instance.

---

### Task 4: Connect to EC2 Instance

Connect to the running EC2 instance using SSH. Use the downloaded key pair and connect via terminal or PuTTY.

For Amazon Linux:

```
ssh -i "keyname.pem" ec2-user@<Public-IP>
```

---

### Task 5: Perform Basic Instance Operations

Perform the following operations from the EC2 console:

* Stop the instance
* Start the instance
* Reboot the instance

Observe the state changes of the instance.

---

### Task 6: Monitor EC2 Instance

Monitor the EC2 instance using the Monitoring tab. Observe metrics such as CPU utilization, network in/out, and instance status checks.

---

### Task 7: Terminate EC2 Instance

Terminate the EC2 instance after completing the experiment to avoid unnecessary AWS charges.

---

## Workflow (Student Explanation)

1. Explored the AWS EC2 dashboard and reviewed sections like Instances, AMIs, Instance Types, Key Pairs, Security Groups, and Elastic IPs to understand their functions.


2. Launched a new Amazon Linux 2 EC2 instance using the t2.micro free-tier instance type and configured basic settings including instance name and key pair.


3. Created and configured a security group to allow SSH (Port 22) from my IP address and HTTP (Port 80) from anywhere to control inbound traffic.


4. Connected to the running EC2 instance using SSH with the downloaded key pair and verified successful login to the server.


5. Performed instance operations such as stop, start, reboot, monitored performance metrics, and finally terminated the instance to prevent unnecessary charges.


## Output Screenshots (Attach 3)

### Screenshot 1: EC2 Dashboard / Instance List

<img width="1919" height="924" alt="Screenshot 2026-02-26 184809" src="https://github.com/user-attachments/assets/55ac53a9-f4d4-4bb5-b02e-0e2c694f6848" />


### Screenshot 2: SSH Connection to Instance


<img width="1914" height="984" alt="Screenshot 2026-02-26 185334" src="https://github.com/user-attachments/assets/404a2cf4-2e2c-4971-be5b-1590312dc015" />


### Screenshot 3: Instance Monitoring / Status

<img width="1917" height="926" alt="Screenshot 2026-02-26 191009" src="https://github.com/user-attachments/assets/b9b3f3b1-2aad-475d-bb9b-8c69c760e4ba" />


---

## Result 

This experiment provided hands-on experience with Amazon EC2 by demonstrating how to launch, connect, manage, and monitor a virtual server in AWS. It helped in understanding the concept of Infrastructure as a Service (IaaS) and how compute resources can be provisioned and controlled on demand in the cloud.
