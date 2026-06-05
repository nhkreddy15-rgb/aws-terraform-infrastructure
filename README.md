# AWS Infrastructure Deployment using Terraform

## Overview

This project demonstrates Infrastructure as Code (IaC) using Terraform to provision and manage AWS infrastructure resources.

The infrastructure includes:

* VPC
* Public Subnet
* Internet Gateway
* Route Table
* Security Group
* EC2 Instance

Terraform was used to automate infrastructure deployment, validation, modification and removal through a repeatable workflow.

---

## Architecture

Internet → Internet Gateway → Route Table → Public Subnet → EC2 Instance

---

## Technologies Used

* AWS
* Terraform
* AWS CLI
* Linux

---

## Resources Provisioned

* Custom VPC (10.0.0.0/16)
* Public Subnet (10.0.1.0/24)
* Internet Gateway
* Route Table and Route Association
* Security Group allowing SSH (22) and HTTP (80)
* Amazon Linux EC2 Instance

---

## Terraform Workflow

```bash
terraform init
terraform validate
terraform plan
terraform apply
terraform destroy
```

---

## Project Structure

```text
aws-terraform-infrastructure/
│
├── provider.tf
├── variables.tf
├── main.tf
├── outputs.tf
├── README.md
│
└── screenshots/
    ├── terraform-apply.png
    ├── ec2-running.png
    ├── vpc.png
    ├── subnet.png
    ├── security-group.png
    └── terraform-destroy.png
```

---

## Learning Outcomes

* Infrastructure as Code (IaC)
* AWS VPC Networking
* Public Subnet Configuration
* Security Group Management
* EC2 Provisioning
* Terraform State Management
* Infrastructure Lifecycle Management
* AWS Resource Automation

---

## Screenshots

The screenshots folder contains evidence of successful infrastructure deployment and resource creation in AWS.

---

## Author

Hem Kumar Reddy N
