# 🔐 AWS Security Hardening & Cost Optimization

![AWS](https://img.shields.io/badge/AWS-Cloud-orange?logo=amazonaws)
![Security](https://img.shields.io/badge/Focus-Cloud%20Security-red)
![Cost Optimization](https://img.shields.io/badge/Focus-Cost%20Optimization-green)
![IAM](https://img.shields.io/badge/AWS-IAM-blue)
![S3](https://img.shields.io/badge/AWS-S3-blue)
![EC2](https://img.shields.io/badge/AWS-EC2-blue)
![CloudTrail](https://img.shields.io/badge/AWS-CloudTrail-blue)

> A hands-on AWS project focused on identifying security misconfigurations, implementing AWS security best practices, validating remediation, and improving cloud cost visibility.

---

## 📌 Project Overview

Cloud infrastructure should be secure, monitored, and cost-efficient.

This project demonstrates a practical **AWS Security Audit, Hardening, and Cost Optimization** workflow. The AWS environment was reviewed for common security weaknesses across identity, storage, compute, networking, monitoring, and cost management.

The identified issues were remediated using AWS security best practices including:

- Multi-Factor Authentication
- Least-Privilege Access
- Secure S3 Configuration
- Security Group Restriction
- EBS Encryption
- AWS Config
- CloudTrail Logging
- AWS Cost Explorer
- AWS Budgets

### Project Workflow

**Audit → Identify → Remediate → Validate → Monitor → Optimize**

---

## 🎯 Project Objectives

- Audit AWS resources for common security misconfigurations
- Identify IAM users without MFA
- Review overly permissive IAM policies
- Apply the principle of least privilege
- Secure Amazon S3 public access
- Restrict unnecessary Security Group access
- Enable EBS encryption
- Configure AWS Config for compliance monitoring
- Review CloudTrail logging
- Analyze AWS cloud spending
- Configure AWS Budgets
- Validate security improvements after remediation
- Improve AWS security posture and cost visibility

---

# 🏗️ AWS Security Architecture

The architecture combines AWS identity, compute, storage, networking, monitoring, security, and cost-management services.

![AWS Security Architecture](Architecture/aws-security-architecture.jpeg)

### Architecture Components

```text
                         AWS Environment
                                |
              +-----------------+-----------------+
              |                 |                 |
             IAM               S3                EC2
              |                 |                 |
             MFA          Public Access       Security Group
              |                 |                 |
              +-----------------+-----------------+
                                |
                               EBS
                                |
                         Encryption at Rest
                                |
                                v
                         AWS Config
                                |
                                v
                         CloudTrail
                                |
                                v
                    Security Monitoring
                                |
                                v
                     Cost Explorer
                                |
                                v
                         AWS Budgets
                         
