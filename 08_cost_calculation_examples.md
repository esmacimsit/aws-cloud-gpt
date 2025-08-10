# AWS Certified Cloud Practitioner (CLF-C02) — Cost Calculation Examples

These examples illustrate how AWS billing works using common services and pricing models.

---

## Example 1: EC2 On-Demand Instance
- **Instance:** t3.micro (2 vCPU, 1 GiB RAM)
- **Region:** US East (N. Virginia)
- **Price:** $0.0104 per hour
- **Usage:** 24 hours/day for 30 days  
- **Cost:**  
  $0.0104 × 24 × 30 = **$7.49/month**

---

## Example 2: S3 Standard Storage
- **Storage used:** 50 GB
- **Price:** $0.023 per GB-month  
- **Cost:**  
  50 × $0.023 = **$1.15/month**

---

## Example 3: Data Transfer Out to the Internet
- **First 1 GB/month:** Free  
- **Next 49 GB:** $0.09 per GB  
- **Usage:** 50 GB outbound total  
- **Cost:**  
  (50 – 1) × $0.09 = **$4.41/month**

---

## Example 4: Combining EC2 + S3 + Data Transfer
- **EC2 (t3.micro, On-Demand):** $7.49/month  
- **S3 Standard (50 GB):** $1.15/month  
- **Data transfer out (49 GB billed):** $4.41/month  
- **Total Monthly Cost:**  
  $7.49 + $1.15 + $4.41 = **$13.05**

---

## Example 5: Using Reserved Instances
- **Instance:** t3.micro, 1-year Standard Reserved Instance, no upfront  
- **Price:** $0.0075 per hour  
- **Usage:** 24 hours/day for 30 days  
- **Cost:**  
  $0.0075 × 24 × 30 = **$5.40/month**  
- **Savings vs On-Demand:** $7.49 – $5.40 = **$2.09/month (~28%)**

---

## Example 6: AWS Lambda Pay-Per-Use
- **Requests:** 1 million/month (first 1M free)  
- **Execution time:** 512 MB memory for 1 second per request  
- **Price per GB-second:** $0.0000166667  
- **Cost:**  
  First 1M requests free → **$0.00** total.

---

## Example 7: Using AWS Pricing Calculator
- Always input:
  - Service type and configuration
  - Region
  - Usage hours/month
  - Storage size and data transfer
- The tool calculates estimated monthly and annual costs.

---

**Exam Tip:** In CLF-C02 questions, exact dollar values are often simplified — focus on understanding what factors increase or decrease the cost, not memorizing all regional prices.
