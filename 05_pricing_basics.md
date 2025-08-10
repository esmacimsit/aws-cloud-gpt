# AWS Certified Cloud Practitioner (CLF-C02) — Pricing & Cost Basics

---

## 1. Key Factors That Affect AWS Pricing
- **Compute:** Charged based on instance type, number of instances, and usage time.
- **Storage:** Charged by the amount of data stored and storage class (S3 Standard, Glacier, etc.).
- **Data transfer:** Charged for data transferred out of AWS (inbound is usually free).

---

## 2. AWS Pricing Models
- **On-Demand:** Pay for compute capacity by the hour or second, no long-term commitment.
- **Reserved Instances (RI):** 1- or 3-year commitment for significant savings (Standard, Convertible).
- **Savings Plans:** Flexible pricing model offering lower rates for a commitment to a consistent amount of usage.
- **Spot Instances:** Purchase unused EC2 capacity at steep discounts; instances can be terminated by AWS.
- **Free Tier:**  
  - 12-month free usage for new customers (e.g., 750 hours of t2.micro or t3.micro per month).  
  - Always free offers (e.g., Lambda 1M requests/month).  
  - Trials for certain services.

---

## 3. AWS Cost Management Tools
- **AWS Pricing Calculator:** Estimate monthly costs before deploying resources.
- **AWS TCO Calculator:** Compare the cost of AWS Cloud vs. on-premises.
- **AWS Cost Explorer:** Visualize, understand, and manage AWS spending over time.
- **AWS Budgets:** Set custom cost and usage budgets and receive alerts.
- **Consolidated Billing (AWS Organizations):** Combine usage across accounts for volume discounts.

---

## 4. Cost Optimization Best Practices
- **Right-size resources:** Match instance types and sizes to workload needs.
- **Use Auto Scaling:** Scale in/out based on demand to avoid overprovisioning.
- **Leverage Spot Instances:** Use for flexible, fault-tolerant workloads.
- **Choose the right storage class:** Store infrequently accessed data in lower-cost storage.
- **Monitor and review:** Regularly analyze spending and usage patterns.

---