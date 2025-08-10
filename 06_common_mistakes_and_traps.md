# AWS Certified Cloud Practitioner (CLF-C02) — Common Mistakes and Traps

These are common pitfalls and misconceptions that can cause errors in the exam.

---

## 1. Misunderstanding the Shared Responsibility Model
- **Trap:** Thinking AWS is responsible for *all* security.
- **Reality:** AWS is responsible for security **of** the cloud (infrastructure), customers are responsible for security **in** the cloud (data, IAM, configurations).

---

## 2. Confusing AWS Services with Similar Names
- **CloudFront vs Route 53:** CloudFront is a CDN; Route 53 is DNS and domain registration.
- **EBS vs EFS vs S3:**  
  - EBS: Block storage for EC2.  
  - EFS: Shared file storage for EC2.  
  - S3: Object storage for virtually unlimited capacity.

---

## 3. Mixing Up Pricing Models
- **Trap:** Thinking Spot Instances are always the cheapest choice.  
- **Reality:** Spot is cheapest for flexible, fault-tolerant workloads, but Reserved Instances/Savings Plans are better for steady-state workloads.

---

## 4. Forgetting Free Tier Limitations
- Free Tier applies only to new accounts for the first 12 months (except “Always Free” services).
- Some services in the Free Tier still have usage limits; exceeding them incurs charges.

---

## 5. Confusing Security Services
- **GuardDuty:** Threat detection.  
- **CloudTrail:** Logs API calls.  
- **Config:** Tracks resource configuration changes.  
- **Shield:** Protects against DDoS.

---

## 6. Overestimating SLA Coverage
- High availability SLAs apply to specific services and configurations — exam questions may test which ones require multi-AZ deployment to meet SLA targets.

---

## 7. Misinterpreting Cost Tools
- **Pricing Calculator:** Pre-deployment cost estimates.  
- **Cost Explorer:** Historical cost analysis.  
- **Budgets:** Alerts for exceeding set limits.

---

## 8. Assuming All Data Transfers Are Free
- Data transfer **into** AWS is usually free, but data transfer **out** is often billed.
- Inter-region transfers usually incur charges.

---

## 9. Overlooking Regional Availability
- Not every service is available in all regions; exam questions may include scenarios where service availability matters.

---

## 10. Ignoring Well-Architected Principles
- Sometimes the correct answer is not the cheapest, but the one that follows best practices for security, reliability, and performance.

---