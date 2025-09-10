# Domain 3: Cloud Technology & Services (≈ 33–34%)

## 1. Compute Services
- **EC2 (Elastic Compute Cloud)** → Virtual servers in the cloud, flexible instance types.  
- **Lambda** → Serverless compute, runs code without managing servers.  
- **Elastic Beanstalk** → PaaS to deploy apps automatically.  
- **ECS (Elastic Container Service)** → Container orchestration (Docker).  
- **EKS (Elastic Kubernetes Service)** → Managed Kubernetes cluster.  

### Key Concepts
- **On-demand vs reserved instances** → cost trade-offs  
- **Auto Scaling** → Adjust capacity automatically  
- **Regions & Availability Zones (AZs)** → High availability & fault tolerance  

---

## 2. Storage Services
- **S3 (Simple Storage Service)** → Object storage, scalable, secure.  
- **EBS (Elastic Block Store)** → Persistent block storage for EC2.  
- **EFS (Elastic File System)** → Shared file storage for multiple EC2 instances.  
- **Glacier / S3 Glacier** → Long-term archival storage, low cost.  

### Storage Concepts
- **Durability & Availability** → S3: 99.999999999% durability  
- **Lifecycle Policies** → Automatically move data to cheaper tiers  
- **Encryption** → Server-side (S3), client-side, KMS-managed  

---

## 3. Networking Services
- **VPC (Virtual Private Cloud)** → Isolated network for AWS resources.  
- **Route 53** → DNS service with global routing.  
- **CloudFront** → Content Delivery Network (CDN) for low latency.  
- **Direct Connect** → Dedicated network connection from on-premises to AWS.  

### Networking Concepts
- **Subnets & AZs** → Segment network and ensure redundancy  
- **Security groups & NACLs** → Control inbound/outbound traffic  
- **Low latency** → Fast response time (good), high latency (bad)  

---

## 4. Databases
- **RDS (Relational Database Service)** → Managed SQL (MySQL, PostgreSQL, Oracle, SQL Server).  
- **DynamoDB** → Managed NoSQL, key-value & document database.  
- **Aurora** → High-performance relational database compatible with MySQL/PostgreSQL.  
- **Redshift** → Data warehouse for analytics.  

### Database Concepts
- **Managed service advantages** → No patching, automated backups, scaling  
- **Read replicas** → Improve performance  
- **Multi-AZ deployments** → High availability  

---

## 5. Exam Blueprint Focus
- Know which service fits a given scenario (compute, storage, networking, database).  
- Understand **serverless** vs **traditional compute**.  
- Identify **high availability** strategies: multi-AZ, global regions, load balancers.  
- Recognize benefits of **managed services** (less operational overhead).  

---

## 6. Practice Triggers (Keywords to Watch)
- **“Serverless code execution”** → Lambda  
- **“Object storage with 11 nines durability”** → S3  
- **“Content delivery globally”** → CloudFront  
- **“Managed SQL database”** → RDS  
- **“Container orchestration”** → ECS / EKS  
