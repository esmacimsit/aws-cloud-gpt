# AWS Certified Cloud Practitioner (CLF-C02) — Service Limits & Defaults

These are common default limits and quotas that may appear on the exam.  
**Note:** Limits can change; always check the AWS documentation for the latest numbers.

---

## General
- **Service Quotas:** AWS has default quotas (soft limits) that can be increased via request.
- Many limits are **per Region**.

---

## Compute
- **EC2 Instances:**  
  - Default: ~20 On-Demand instances per Region.  
  - Can request an increase via AWS Support.
- **EC2 Security Groups:**  
  - 5 security groups per VPC (default).  
  - 50 inbound/outbound rules per security group.
- **Elastic IP addresses:**  
  - 5 per Region (default).

---

## Storage
- **S3 Buckets:**  
  - 100 buckets per AWS account (soft limit).  
  - Unlimited objects per bucket.
- **EBS Volumes:**  
  - Size: 1 GiB to 16 TiB.  
  - Up to 20 TiB snapshots.
- **EFS:**  
  - Automatically scales storage, no manual limit.

---

## Databases
- **RDS Instances:**  
  - Default: ~40 DB instances per account (across all regions, varies by engine).  
  - Max storage per DB: up to 64 TiB for some engines.
- **DynamoDB:**  
  - No limit on table size.  
  - On-Demand capacity adjusts automatically; provisioned mode has configurable limits.

---

## Networking
- **VPCs:** 5 per Region (default).
- **Subnets per VPC:** 200.
- **Internet Gateways:** 1 per VPC.
- **Elastic Load Balancers:**  
  - Soft limits per Region (varies by type).

---

## IAM
- **IAM Users:** Up to 5,000 per account.
- **IAM Groups:** Up to 300 per account.
- **IAM Roles:** Up to 1,000 per account.
- **Access Keys per User:** 2.

---

## Lambda
- **Timeout:** Max 15 minutes.
- **Memory Allocation:** 128 MB to 10,240 MB.
- **Concurrent Executions:** Default 1,000 per account.

---

## CloudFront
- **Distributions:** Default limit is 200 per account.
- **Max Cache Behavior per Distribution:** 25.

---

## API Gateway
- **Regional endpoints:** 10,000 requests per second (soft limit).
- **Payload size limit:** 10 MB for synchronous calls.

---