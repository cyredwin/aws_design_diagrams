# ☁️ AWS CloudFormation Exercises

This repository contains my hands-on exercises and labs for learning **AWS CloudFormation**.

The goal of this repository is to practice **Infrastructure as Code (IaC)** by creating AWS resources using CloudFormation templates instead of manually creating resources from the AWS Management Console.

---

## 📌 About This Repository

In this repository, I will create different AWS CloudFormation exercises covering topics such as:

* EC2 instances
* VPCs
* Subnets
* Security Groups
* Internet Gateways
* Route Tables
* Elastic IPs
* S3 Buckets
* IAM resources
* Parameters
* Outputs
* Mappings
* Conditions
* CloudFormation intrinsic functions

Templates may be written in either **YAML** or **JSON**.

---

## 🎯 Learning Objectives

By completing these exercises, I aim to learn how to:

* Understand AWS CloudFormation template structure
* Create AWS infrastructure using code
* Deploy CloudFormation stacks
* Update existing stacks
* Delete CloudFormation stacks safely
* Use parameters to make templates reusable
* Reference resources using `Ref`
* Use intrinsic functions such as `Fn::GetAtt` and `Fn::Sub`
* Troubleshoot CloudFormation deployment errors
* Use AWS CLI with CloudFormation
* Organize Infrastructure as Code projects on GitHub

---

## 📁 Repository Structure

```text
aws-cloudformation-exercises/
│
├── 01-ec2/
│   ├── ec2.yml
│   └── README.md
│
├── 02-security-groups/
│   ├── security-group.yml
│   └── README.md
│
├── 03-vpc/
│   ├── vpc.yml
│   └── README.md
│
├── 04-subnets/
│   ├── subnet.yml
│   └── README.md
│
├── 05-s3/
│   ├── s3.yml
│   └── README.md
│
├── 06-complete-infrastructure/
│   ├── infrastructure.yml
│   └── README.md
│
└── README.md
```

Each directory contains a CloudFormation exercise and, when necessary, documentation explaining the objective and deployment process.
