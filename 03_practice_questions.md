# AWS Certified Cloud Practitioner (CLF-C02) — Practice Questions

---

## Question 1 (Difficulty: Easy)  
Which AWS Cloud benefit helps a company avoid large upfront investments in physical infrastructure?  

A) Agility  
B) Elasticity  
C) Pay-as-you-go pricing  
D) Global reach  

**Answer Explanation:**  
Correct: **C** — Pay-as-you-go pricing allows customers to shift from capital expenditures (CapEx) to operational expenditures (OpEx), avoiding large upfront costs.  
Wrong: **A** — Agility refers to quickly deploying and iterating solutions, not cost structure.  
Wrong: **B** — Elasticity means scaling resources up or down based on demand.  
Wrong: **D** — Global reach means deploying applications in multiple regions worldwide.  

**Key AWS Concepts:**  
- CapEx vs OpEx  
- AWS pricing models  
- AWS Cloud benefits  

**Tags:** [domain=Cloud Concepts][service=Pricing][difficulty=Easy]

---

## Question 2 (Difficulty: Medium)  
Which AWS service can be used to register a domain name and route traffic to AWS resources?  

A) Amazon CloudFront  
B) Amazon Route 53  
C) AWS Global Accelerator  
D) Amazon API Gateway  

**Answer Explanation:**  
Correct: **B** — Amazon Route 53 is AWS’s scalable Domain Name System (DNS) service that can also register domain names and route traffic.  
Wrong: **A** — CloudFront is a CDN for content delivery, not domain registration.  
Wrong: **C** — Global Accelerator improves availability and performance but doesn’t handle domain registration.  
Wrong: **D** — API Gateway manages APIs, not domain names.  

**Key AWS Concepts:**  
- DNS  
- Domain registration  
- Traffic routing  

**Tags:** [domain=Technology][service=Route53][difficulty=Medium]

---

## Question 3 (Difficulty: Easy)  
Under the AWS Shared Responsibility Model, which of the following is the customer responsible for?  

A) Physical security of data centers  
B) Patching the underlying host operating system  
C) Managing IAM user access  
D) Maintaining hardware servers  

**Answer Explanation:**  
Correct: **C** — Customers are responsible for security **in** the cloud, including IAM user management.  
Wrong: **A** — AWS is responsible for physical security of its infrastructure.  
Wrong: **B** — AWS patches the underlying host OS for managed services; customers patch OS in unmanaged EC2.  
Wrong: **D** — AWS maintains the hardware.  

**Key AWS Concepts:**  
- Shared Responsibility Model  
- IAM management  
- Security responsibilities  

**Tags:** [domain=Security and Compliance][service=IAM][difficulty=Easy]

---

## Question 4 (Difficulty: Medium)  
Which AWS service provides object storage with virtually unlimited capacity and is ideal for backup and archival?  

A) Amazon EBS  
B) Amazon EFS  
C) Amazon S3  
D) Amazon RDS  

**Answer Explanation:**  
Correct: **C** — Amazon S3 is object storage, scalable to virtually unlimited size, and commonly used for backups.  
Wrong: **A** — EBS is block storage for EC2.  
Wrong: **B** — EFS is a shared file system.  
Wrong: **D** — RDS is a managed relational database.  

**Key AWS Concepts:**  
- Object storage  
- Backup and archival  
- S3 features  

**Tags:** [domain=Technology][service=S3][difficulty=Medium]

---

## Question 5 (Difficulty: Easy)  
Which AWS service is designed to detect malicious activity and unauthorized behavior in your AWS account?  

A) AWS Config  
B) AWS CloudTrail  
C) Amazon GuardDuty  
D) AWS Shield  

**Answer Explanation:**  
Correct: **C** — Amazon GuardDuty is a threat detection service that monitors for malicious activity.  
Wrong: **A** — AWS Config tracks resource configuration changes.  
Wrong: **B** — CloudTrail logs API calls but does not automatically detect threats.  
Wrong: **D** — AWS Shield protects against DDoS attacks specifically.  

**Key AWS Concepts:**  
- Threat detection  
- Account monitoring  
- Security services  

**Tags:** [domain=Security and Compliance][service=GuardDuty][difficulty=Easy]

---

## Question 6 (Difficulty: Medium)  
A company wants to deploy an application without managing servers and only pay for execution time. Which service should they use?  

A) Amazon EC2  
B) AWS Lambda  
C) AWS Elastic Beanstalk  
D) Amazon Lightsail  

**Answer Explanation:**  
Correct: **B** — AWS Lambda is serverless and charges only for the time code runs.  
Wrong: **A** — EC2 requires managing servers.  
Wrong: **C** — Elastic Beanstalk automates server provisioning but still uses managed infrastructure.  
Wrong: **D** — Lightsail is a simple VPS, billed by instance.  

**Key AWS Concepts:**  
- Serverless  
- Event-driven computing  
- Pay-per-execution  

**Tags:** [domain=Technology][service=Lambda][difficulty=Medium]

---

## Question 7 (Difficulty: Medium)  
Which support plan is required to get 24/7 phone, chat, and email access to AWS Cloud Support Engineers?  

A) Basic  
B) Developer  
C) Business  
D) Enterprise  

**Answer Explanation:**  
Correct: **C** — Business plan provides 24/7 access to Cloud Support Engineers.  
Wrong: **A** — Basic has only account and billing support.  
Wrong: **B** — Developer plan provides business hours email support.  
Wrong: **D** — Enterprise also provides 24/7 support but is intended for mission-critical workloads.  

**Key AWS Concepts:**  
- AWS Support Plans  
- SLA differences  
- Support access levels  

**Tags:** [domain=Billing, Pricing, and Support][service=Support][difficulty=Medium]

---

## Question 8 (Difficulty: Easy)  
Which AWS pricing model offers the highest discount for long-term workloads with predictable usage?  

A) On-Demand Instances  
B) Spot Instances  
C) Reserved Instances  
D) Free Tier  

**Answer Explanation:**  
Correct: **C** — Reserved Instances provide significant discounts (up to 72%) for committing to 1 or 3 years.  
Wrong: **A** — On-Demand is flexible but not discounted.  
Wrong: **B** — Spot offers steep discounts but is for interruptible workloads.  
Wrong: **D** — Free Tier is limited in duration and resources.  

**Key AWS Concepts:**  
- Pricing models  
- Cost optimization  
- Long-term commitments  

**Tags:** [domain=Billing, Pricing, and Support][service=EC2][difficulty=Easy]

---

## Question 9 (Difficulty: Medium)  
A company needs to store infrequently accessed data at the lowest cost, with retrieval times of several hours. Which storage option should they choose?  

A) Amazon S3 Standard  
B) Amazon S3 Glacier Deep Archive  
C) Amazon EFS  
D) Amazon EBS Cold HDD  

**Answer Explanation:**  
Correct: **B** — S3 Glacier Deep Archive is the lowest-cost storage for archival data with retrieval times up to 12 hours.  
Wrong: **A** — S3 Standard is for frequently accessed data.  
Wrong: **C** — EFS is for file sharing across instances.  
Wrong: **D** — EBS Cold HDD is for low-cost, infrequently accessed block storage, not archival.  

**Key AWS Concepts:**  
- S3 storage classes  
- Cost vs retrieval time  
- Archival storage  

**Tags:** [domain=Technology][service=S3][difficulty=Medium]

---

## Question 10 (Difficulty: Medium)  
Which AWS service lets you estimate your monthly AWS bill before you deploy resources?  

A) AWS Budgets  
B) AWS Pricing Calculator  
C) AWS Cost Explorer  
D) AWS Trusted Advisor  

**Answer Explanation:**  
Correct: **B** — AWS Pricing Calculator estimates costs before launching resources.  
Wrong: **A** — AWS Budgets monitors spending after deployment.  
Wrong: **C** — Cost Explorer analyzes past and current usage.  
Wrong: **D** — Trusted Advisor offers recommendations but doesn’t estimate costs.  

**Key AWS Concepts:**  
- Cost estimation  
- Billing tools  
- Pre-deployment planning  

**Tags:** [domain=Billing, Pricing, and Support][service=Pricing Calculator][difficulty=Medium]

---