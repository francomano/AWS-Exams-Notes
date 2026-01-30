# AWS Exams Notes (CERTIFIED) ✅

**Personal study notes for AWS exams I've passed.** This README focuses only on the `.txt` files and a short summary of their contents.

---

## 📄 Notes (.txt files)

- `mla-c01/appunti-ML-Associate.txt` — Machine Learning (Associate) notes:
  - Data ingestion & storage: structured / unstructured / semi-structured data, data warehouses (schema-on-write) vs data lakes (schema-on-read), lakehouse concepts, and partitioning best practices (Parquet/ORC).
  - Pipelines & streaming: ETL/ELT patterns, AWS Glue (crawlers/catalog), Step Functions, EventBridge, Kinesis vs Amazon MSK, JDBC/ODBC, Avro/Parquet formats.
  - Transformation & feature engineering: EMR and Spark (EMR Serverless / EMR on EKS), Spark MLlib, PCA, TF-IDF, imputation strategies, handling imbalance (SMOTE), scaling/encoding, binning, and shuffling.
  - SageMaker ecosystem & managed services: training jobs, endpoints/batch transform, Data Wrangler, Ground Truth, Model Monitor, Feature Store, Canvas, and no-code options for quick experiments.
  - Analysis & serverless tools: Athena, QuickSight, Glue DataBrew, Glue Data Quality; practical tips (columnar formats, small number of large files, MSCK REPAIR TABLE) and exam-style reminders for cost/operational overhead.
  - Short exam-style reminders and quick formulas

- `soa-c03/appunti-cloudops.txt` — Cloud operations / Solutions-focused notes:
  - Compute & EC2: instance types, placement groups, purchasing options (On‑Demand/Reserved/Savings Plans/Spot/Capacity Reservation), instance store vs EBS, AMIs, status checks, hibernation, and SSH/troubleshooting tips.
  - Storage & S3: EBS / EFS / FSx differences, snapshots & lifecycle, S3 versioning & Object Lock (WORM), presigned URLs, transfer acceleration, and replication best practices.
  - Networking & CDN: VPC fundamentals (subnets, IGW, NAT, NACL vs Security Groups), VPC endpoints, Direct Connect, Site‑to‑Site VPN, Route 53 (routing policies & health checks), CloudFront caching/headers/cookie forwarding and origin concepts.
  - Load balancing & autoscaling: ALB/NLB/GWLB differences, sticky sessions, health checks, cross‑zone, connection draining, Auto Scaling groups and scaling policies (simple/step/target/predictive).
  - Databases & caches: RDS multi‑AZ vs read replicas, Aurora concepts, RDS Proxy, ElastiCache (Redis/Memcached) and caching patterns.
  - Management & automation: CloudFormation (ChangeSets, StackSets, CreationPolicy/cfn-signal), Systems Manager (Run Command, Session Manager, Parameter Store, Patch Manager), and Lambda limits.
  - Observability & ops: CloudWatch metrics/logs/agent/Insights, CloudTrail, EventBridge, alarms/anomaly detection, and log exports/subscriptions.
  - Security & compliance: WAF, Shield, GuardDuty, Inspector, Macie, Security Hub, KMS (CMK types & cross‑account), Secrets Manager rotation, and audit patterns.
  - DR, backup & cost: AWS Backup, DataSync, Snow family, Cost Explorer, Budgets, and practical exam tips for high availability, DR and cost optimisation.

**Badge:** [SOA-C03 Credential — View on Credly](https://www.credly.com/badges/d5d3f2ca-399b-43ec-bdf5-029a8ea2466d/public_url)  
![SOA-C03 Badge](https://www.credly.com/badges/d5d3f2ca-399b-43ec-bdf5-029a8ea2466d/public_url)

---

## ⚙️ How to use

- Open the `.txt` files for quick review; they are written as concise study prompts and checklists.
- Use search (grep/CTRL+F) to find topics quickly while revising.

---

> These are my personal notes and not official AWS documentation. Use them as a supplement to AWS whitepapers and official study guides.

---

If you'd like, I can expand any file's summary with extracted key points from the text — tell me which one you'd like expanded. ✍️